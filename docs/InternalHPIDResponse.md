# InternalHPIDResponse
## Properties
- signature_hpid (String)

   
- internal_hpid (String)

   
- organisation (String)

   
- description (String)

   
- level (String)

   
- unit (String)

   
- flat (String)

   
- room (String)

   
- parking (String)

   
- land (String)

   
- plot (String)

   
- block (String)

   
- arch (String)

   
- object_type (String)

   
- signature_internal_addresses (Array of [SignatureInternalAddressesGridResponse](SignatureInternalAddressesGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : ["string", "null"],
       "internal_hpid" : ["string", "null"],
       "organisation" : ["string", "null"],
       "description" : ["string", "null"],
       "level" : ["string", "null"],
       "unit" : ["string", "null"],
       "flat" : ["string", "null"],
       "room" : ["string", "null"],
       "parking" : ["string", "null"],
       "land" : ["string", "null"],
       "plot" : ["string", "null"],
       "block" : ["string", "null"],
       "arch" : ["string", "null"],
       "object_type" : ["string", "null"],
       "signature_internal_addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureInternalAddressesGrid"}
}
```

