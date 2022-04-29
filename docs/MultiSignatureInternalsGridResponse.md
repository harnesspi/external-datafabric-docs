# MultiSignatureInternalsGridResponse
## Description

## Properties
### signature_hpid


Type Description: String
### internal_hpid


Type Description: ValueLink for InternalHPIDResponse
### organisation


Type Description: ValueLink for MultiSignatureMatchingAttributeResponse
### land


Type Description: String
### plot


Type Description: String
### block


Type Description: String
### level


Type Description: ValueLink for MultiSignatureMatchingAttributeResponse
### arch


Type Description: String
### unit


Type Description: ValueLink for MultiSignatureMatchingAttributeResponse
### flat


Type Description: ValueLink for MultiSignatureMatchingAttributeResponse
### room


Type Description: String
### parking


Type Description: String
### description


Type Description: String
### object_type


Type Description: String
### keys


Type Description: Array of KeyValueLinks for SignatureInternalKeyResponse
### signature


Type Description: String

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

## Related Entities
- [](.md)
- [InternalHPIDResponse](InternalHPIDResponse.md)
- [MultiSignatureMatchingAttributeResponse](MultiSignatureMatchingAttributeResponse.md)
- [SignatureInternalKeyResponse](SignatureInternalKeyResponse.md)
