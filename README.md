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

The Data Fabric API uses the terms **Signature** and **HPID** a lot.
A **Signature** is Data Fabric's normalised, structured view on a street-level address, such a named building's address in a street, or simply a residential house in a terrace.
An **HPID** is the HARNESS Property Identifier, which identifies signatures (street level addresses) as well as internal address (for example, a unit on a floor in a large office). It is the smallest unit of resolution in Data Fabric, and is the foundation of its joining capability.

## Getting Started
Full API documentation can be found on the DataFabric GitHub Repo.
- https://github.com/harnesspi/external-datafabric-docs
- https://github.com/harnesspi/external-datafabric-docs/blob/main/docs/DataFabricAPI.md

### Security
When you start using the the Data Fabric APIs you will be provided with your own API Key to include in each request, either as a Header or Query Parameter with a value of `Subscription-Key`.

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
```json
[
    {
        "hpid": {
            "value": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
            "link": "/MultiSignature/f8ea03ec-5892-e4cb-c627-e8d194ee87bf"
        },
        "address": "THE SHARD 31 ST THOMAS ST SE1 9BS"
    },
    {
        "hpid": {
            "value": "7b74eace-f404-0ba0-399c-f1caf78960dd",
            "link": "/MultiSignature/7b74eace-f404-0ba0-399c-f1caf78960dd"
        },
        "address": "THE SHARD ST THOMAS ST SE1 9BS"
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
```json
{
    "hpids": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
    "customer_reference": null,
    "add_to_cart": null,
    "polygon_type": null,
    "view_map_iframe": null,
    "open_related_signatures": null,
    "data_sources_chart": null,
    "signatures": [],
    "signature_internals": [],
    "addresses": [ ],
    "listings": []
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
```json
{
    "signature_hpid": {
        "value": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
        "link": "/SignatureHPID/f8ea03ec-5892-e4cb-c627-e8d194ee87bf"
    },
    "building_name": "THE SHARD",
    "start_number": "31",
    "end_number": null,
    "usrn": {
        "value": "22502357",
        "link": "/Street/22502357"
    },
    "street": "ST THOMAS ST",
    "keys": []
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

```json
{
    "key": "Postcode",
    "value": "SE1 9QU",
    "link": "/SignatureKey/Postcode/SE1 9QU"
}
```

#### Signature Internals
A list of all the internal signatures that are part of the selected parent signatures.

##### Response Example

```json
{
    "signature_hpid": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
    "internal_hpid": {
        "value": "4d05c40f-474d-553e-05ab-68bceed5f18d",
        "link": "/InternalHPID/4d05c40f-474d-553e-05ab-68bceed5f18d"
    },
    "organisation": {
        "value": "SHANGRI LA HOTELS PTE LTD",
        "link": "/MultiSignatureMatchingAttribute/f8ea03ec-5892-e4cb-c627-e8d194ee87bf/Organisation/SHANGRI LA HOTELS PTE LTD"
    },
    "land": null,
    "plot": null,
    "block": null,
    "level": {
        "value": "50",
        "link": "/MultiSignatureMatchingAttribute/f8ea03ec-5892-e4cb-c627-e8d194ee87bf/Level/50"
    },
    "arch": null,
    "unit": null,
    "flat": null,
    "room": null,
    "parking": null,
    "description": "FLR 52 BEING THE SHANGRI LA HOTEL",
    "objectType": null,
    "keys": [
        {
            "key": "LandRegistryLeasehold",
            "value": "TGL395949",
            "link": "/SignatureInternalKey/4d05c40f-474d-553e-05ab-68bceed5f18d/LandRegistryLeasehold/TGL395949"
        }
    ],
    "signature": "THE SHARD 31 ST THOMAS ST"
}
```


#### Addresses
A list of all the address data associated with the selected signatures.
##### Response Example

```json
 {
    "signature_hpid": "f8ea03ec-5892-e4cb-c627-e8d194ee87bf",
    "address_hpid": "bc04f9fd-6e3b-9f78-35dd-ed3b5b68fdc1",
    "source_name": "VOA",
    "key": "9969965000",
    "uprn": null,
    "organisation": null,
    "address": "|PT LEVEL 27|||THE SHARD 31|ST THOMAS STREET",
    "postcode": "SE1 9RY",
    "url_query": {
        "key": "VOA",
        "value": "9969965000",
        "link": "/VOA/9969965000"
    }
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
```json
{
    "key_type": "Postcode",
    "key_value": "SE1 9QU",
    "customer_reference": null,
    "add_to_cart": null,
    "date_context": null,
    "refresh_date_context": null,
    "view_map_iframe": null,
    "open_related_signatures": null,
    "data_sources_chart": null,
    "key_signatures": [],
    "key_signatures_internals": [],
    "key_addresses_data_grid": [],
    "listings": []
}
```