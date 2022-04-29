# InternalHPIDResponse
## Description

## Properties
### signature_hpid


Type Description: String
### internal_hpid


Type Description: String
### organisation


Type Description: String
### description


Type Description: String
### level


Type Description: String
### unit


Type Description: String
### flat


Type Description: String
### room


Type Description: String
### parking


Type Description: String
### land


Type Description: String
### plot


Type Description: String
### block


Type Description: String
### arch


Type Description: String
### object_type


Type Description: String
### signature_internal_addresses


Type Description: Array of SignatureInternalAddressesGridResponse

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

## Related Entities
- [SignatureInternalAddressesGridResponse](SignatureInternalAddressesGridResponse.md)

