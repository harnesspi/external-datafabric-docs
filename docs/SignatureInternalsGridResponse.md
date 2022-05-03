# SignatureInternalsGridResponse
## Properties
- signature_hpid (String)

   
- internal_hpid ([ValueLink](ValueLink.md) for [InternalHPIDResponse](InternalHPIDResponse.md))

   
- organisation ([ValueLink](ValueLink.md) for [SignatureKeyMatchingAttributeResponse](SignatureKeyMatchingAttributeResponse.md))

   
- land (String)

   
- plot (String)

   
- block (String)

   
- level ([ValueLink](ValueLink.md) for [SignatureKeyMatchingAttributeResponse](SignatureKeyMatchingAttributeResponse.md))

   
- arch (String)

   
- unit ([ValueLink](ValueLink.md) for [SignatureKeyMatchingAttributeResponse](SignatureKeyMatchingAttributeResponse.md))

   
- flat ([ValueLink](ValueLink.md) for [SignatureKeyMatchingAttributeResponse](SignatureKeyMatchingAttributeResponse.md))

   
- room (String)

   
- parking (String)

   
- description (String)

   
- object_type (String)

   
- keys (Array of [KeyValueLinks](KeyValueLink.md) for [SignatureInternalKeyResponse](SignatureInternalKeyResponse.md))

   
- signature (String)

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : "string",
       "internal_hpid" : {"$ref" : "/schemas/valuelink"},
       "organisation" : {"$ref" : "/schemas/valuelink"},
       "land" : "string",
       "plot" : "string",
       "block" : "string",
       "level" : {"$ref" : "/schemas/valuelink"},
       "arch" : "string",
       "unit" : {"$ref" : "/schemas/valuelink"},
       "flat" : {"$ref" : "/schemas/valuelink"},
       "room" : "string",
       "parking" : "string",
       "description" : "string",
       "object_type" : "string",
       "keys" : {"type" : "array", "items" : {"$ref" : "/schemas/keyvaluelink"}},
       "signature" : "string"
    }
}
```

