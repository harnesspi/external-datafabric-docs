# Data Fabric API

## Introduction
Data Fabric pulls together a wide variety of property address data, although this list is always growing some of the key data includes:

- addresses
- ownership
- valuation
- construction
- environmental risk
- utilities

The Data Fabric API consists of a set of REST endpoints that allow clients to easily naivigate this data in a flexible way to suit their integration requirements.

## Getting Started
### Security
When you start using the the Data Fabric APIs you will be provided with your own API Key to include in each request, either as a Header or Query Parameter with a value of `Subscription-Key`.

### HPID
???

## Links
???

### Find an address
The Data Fabric Address Finder is a search tool that can quickly identify properties using a partial address string. It's the ideal *entry point* to begin navigating through the Data Fabric APIs. This API call can work with a text box to allow users to search for properties in Data Fabric, providing quick response times as a user types.

The address finder will return an array of address information including an address string and HPID which can be used to lookup the address signature.

#### Request Format
```
HTTP GET

/AddressFinder/{search_string}
```
#### Request Example
```
/AddressFinder/THE SHARD 31 ST THOMAS
```
#### Response Example
```
[
    {
        "HPID": {
            "value": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
            "link": "/MultiSignature/f8ea03ec-5892-e4cb-c627-e8d194ee87bf"
        },
        "Address": "THE SHARD 31 ST THOMAS ST SE1 9BS"
    },
    {
        "HPID": {
            "value": "7b74eace-f404-0ba0-399c-f1caf78960dd",
            "link": "/MultiSignature/7b74eace-f404-0ba0-399c-f1caf78960dd"
        },
        "Address": "THE SHARD ST THOMAS ST SE1 9BS"
    }
]
```

### Signatures
The signatures endpoint can be used to lookup address signatures using one or more HPIDs returned by the address finder.

#### Request Format
```
HTTP GET

/MultiSignature/{hpid_csv}
```
#### Request Example
```
/MultiSignature/f8ea03ec-5892-e4cb-c627-e8d194ee87bf

/MultiSignature/f8ea03ec-5892-e4cb-c627-e8d194ee87bf,7b74eace-f404-0ba0-399c-f1caf78960dd
```

#### Response Example
```
{
    "HPIDs": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
    "CustomerReference": null,
    "AddToCart": null,
    "PolygonType": null,
    "ViewMapIframe": null,
    "OpenRelatedSignatures": null,
    "DataSourcesChart": null,
    "Signatures": [],
    "SignatureInternals": [],
    "Addresses": [ ],
    "Listings": []
}
```
The signatures response includes a number of object arrays containing items associated with  the HPIDs that were used to query the API, including:

- Signatures and Keys
- Signature internals
- Addresses
- Listings

#### Signatures and Keys
A detailed signature object for each HPID, including an array of keys thats can be used to lookup associated address data. 
##### Response Example
```
{
    "SignatureHPID": {
        "value": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
        "link": "/SignatureHPID/f8ea03ec-5892-e4cb-c627-e8d194ee87bf"
    },
    "Building Name": "THE SHARD",
    "Start Number": "31",
    "End Number": null,
    "USRN": {
        "value": "22502357",
        "link": "/Street/22502357"
    },
    "Street": "ST THOMAS ST",
    "Keys": []
}
```
Keys can refer to different types of data, some of the supported types are:
- BuildingPolygon
- Estate
- Ext. Toid
- Postcode
- TopUPRN
The keys endpoint is detailed below, it accepts a key type (e.g. postcode) and ID, a link to the key endpoint is included within the response.

##### Response Example

```
{
    "key": "Postcode",
    "value": "SE1 9QU",
    "link": "/SignatureKey/Postcode/SE1 9QU"
}
```

#### Signature Internals
A list of all the internal signatures that are part of the selected parent signatures.

##### Response Example

```
{
    "SignatureHPID": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
    "InternalHPID": {
        "value": "4d05c40f-474d-553e-05ab-68bceed5f18d",
        "link": "/InternalHPID/4d05c40f-474d-553e-05ab-68bceed5f18d"
    },
    "Organisation": {
        "value": "SHANGRI LA HOTELS PTE LTD",
        "link": "/MultiSignatureMatchingAttribute/f8ea03ec-5892-e4cb-c627-e8d194ee87bf/Organisation/SHANGRI LA HOTELS PTE LTD"
    },
    "Land": null,
    "Plot": null,
    "Block": null,
    "Level": {
        "value": "50",
        "link": "/MultiSignatureMatchingAttribute/f8ea03ec-5892-e4cb-c627-e8d194ee87bf/Level/50"
    },
    "Arch": null,
    "Unit": null,
    "Flat": null,
    "Room": null,
    "Parking": null,
    "Description": "FLR 52 BEING THE SHANGRI LA HOTEL",
    "ObjectType": null,
    "Keys": [
        {
            "key": "LandRegistryLeasehold",
            "value": "TGL395949",
            "link": "/SignatureInternalKey/4d05c40f-474d-553e-05ab-68bceed5f18d/LandRegistryLeasehold/TGL395949"
        }
    ],
    "Signature": "THE SHARD 31 ST THOMAS ST"
}
```


#### Addresses
A list of all the address data associated with the selected signatures.
##### Response Example

```
 {
    "SignatureHPID": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
    "AddressHPID": "bc04f9fd-6e3b-9f78-35dd-ed3b5b68fdc1",
    "SourceName": "VOA",
    "Key": "9969965000",
    "UPRN": null,
    "Organisation": null,
    "Address": "|PT LEVEL 27|||THE SHARD 31|ST THOMAS STREET",
    "Postcode": "SE1 9RY",
    "URLQuery": {
        "key": "VOA",
        "value": "9969965000",
        "link": "/VOA/9969965000"
    }
}

```
#### Listings
A list of listings that are linked to the selected signatures.

##### Response Example
```
{
    "ListingId": "R113747765",
    "DisplayAddress": "Telephone Kiosk, nr. The Shard o/s 17/19 St Thomas Street, London, SE1 9RY",
    "PropertyType": "Commercial Property",
    "Bedrooms": null,
    "TransactionType": "BUY",
    "AskingPrice": "49000",
    "Relevancy": "2",
    "Last Update": "2022-02-28T00:00:00",
    "Inactive": "0"
}

```
### Lookup Keys Data
Signatures in Data Fabric include keys for related data, a list of keys is returned in the signature lookup, detailed above. Keys can refer to different types of data, some of the supported types are:
- BuildingPolygon
- Estate
- Ext. Toid
- Postcode
- TopUPRN

#### Request Format
```
HTTP GET

/SignatureKey/{key_type}/{key}
```
#### Request Examples
```
/SignatureKey/BuildingPolygon/666126950
/SignatureKey/Estate/451951300
/SignatureKey/Postcode/SE1 9QU
```
#### Response Example
```
EXAMPLE HERE
```