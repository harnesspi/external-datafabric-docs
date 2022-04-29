# StreetSignaturesGridResponse
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
### keys


Type Description: Array of KeyValueLinks for SignatureKeyResponse
### usrn


Type Description: ValueLink for StreetResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : {"$ref" : "/schemas/valuelink"},
       "building_name" : "string",
       "start_number" : "string",
       "end_number" : "string",
       "keys" : {"type" : "array", "items" : {"$ref" : "/schemas/keyvaluelink"}},
       "usrn" : {"$ref" : "/schemas/valuelink"}
    }
}
```

## Related Entities
- [SignatureHPIDResponse](SignatureHPIDResponse.md)
- [ValueLink](ValueLink.md)
- [SignatureKeyResponse](SignatureKeyResponse.md)
- [KeyValueLink](KeyValueLink.md)
- [StreetResponse](StreetResponse.md)

