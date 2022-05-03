# MultiSignatureGridResponse
## Description
This a test description
## Properties
- signature_hpid ([ValueLink](ValueLink.md) for [SignatureHPIDResponse](SignatureHPIDResponse.md))

   Test description here
- building_name (String)

   
- start_number (String)

   
- end_number (String)

   
- usrn ([ValueLink](ValueLink.md) for [StreetResponse](StreetResponse.md))

   
- street (String)

   
- keys (Array of [KeyValueLinks](KeyValueLink.md) for [SignatureKeyResponse](SignatureKeyResponse.md))

   

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

