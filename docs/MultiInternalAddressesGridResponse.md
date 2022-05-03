# MultiInternalAddressesGridResponse
## Properties
- signature_hpid (String)

   
- internal_hpid (String)

   
- organisation (String)

   
- land (String)

   
- plot (String)

   
- block (String)

   
- level (String)

   
- arch (String)

   
- unit (String)

   
- flat (String)

   
- room (String)

   
- parking (String)

   
- description (String)

   
- object_type (String)

   
- keys (String)

   
- signature (String)

   
- url_query ([KeyValueLink](KeyValueLink.md) for [object](object.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : "string",
       "internal_hpid" : "string",
       "organisation" : "string",
       "land" : "string",
       "plot" : "string",
       "block" : "string",
       "level" : "string",
       "arch" : "string",
       "unit" : "string",
       "flat" : "string",
       "room" : "string",
       "parking" : "string",
       "description" : "string",
       "object_type" : "string",
       "keys" : "string",
       "signature" : "string",
       "url_query" : {"$ref" : "/schemas/keyvaluelink"}
    }
}
```

