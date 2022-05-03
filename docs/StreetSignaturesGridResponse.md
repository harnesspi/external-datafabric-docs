# StreetSignaturesGridResponse
## Properties
- signature_hpid ([ValueLink](ValueLink.md) for [SignatureHPIDResponse](SignatureHPIDResponse.md))

   Test description here
- building_name (String)

   
- start_number (String)

   
- end_number (String)

   
- keys (Array of [KeyValueLinks](KeyValueLink.md) for [SignatureKeyResponse](SignatureKeyResponse.md))

   
- usrn ([ValueLink](ValueLink.md) for [StreetResponse](StreetResponse.md))

   

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

