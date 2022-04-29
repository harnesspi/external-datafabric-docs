# KeySignaturesGridResponse
## Description

## Properties
### signature_hpid
Test description here

Type Description: ValueLink for SignatureHPIDResponse
### building_name


Type Description: String
### start_number


Type Description: String
### end_number


Type Description: String
### usrn


Type Description: ValueLink for StreetResponse
### street


Type Description: String
### keys


Type Description: Array of KeyValueLinks for SignatureKeyResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : {"$ref" : "/schemas/valuelink"},
       "building_name" : "string",
       "start_number" : "string",
       "end_number" : "string",
       "usrn" : {"$ref" : "/schemas/valuelink"},
       "street" : "string",
       "keys" : {"type" : "array", "items" : {"$ref" : "/schemas/keyvaluelink"}}
    }
}
```

## Related Entities
- [SignatureHPIDResponse](SignatureHPIDResponse.md)
- [ValueLink](ValueLink.md)
- [StreetResponse](StreetResponse.md)
- [SignatureKeyResponse](SignatureKeyResponse.md)
- [KeyValueLink](KeyValueLink.md)

