# MultiInternalAddressesGridResponse
## Description

## Properties
### signature_hpid


Type Description: String
### internal_hpid


Type Description: String
### organisation


Type Description: String
### land


Type Description: String
### plot


Type Description: String
### block


Type Description: String
### level


Type Description: String
### arch


Type Description: String
### unit


Type Description: String
### flat


Type Description: String
### room


Type Description: String
### parking


Type Description: String
### description


Type Description: String
### object_type


Type Description: String
### keys


Type Description: String
### signature


Type Description: String
### url_query


Type Description: KeyValueLink for object

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

## Related Entities
- [KeyValueLink](KeyValueLink.md)

