# MultiSignatureResponse
## Description
This a test description
## Properties
### signatures


Type Description: Array of MultiSignatureGridResponse
### signature_internals


Type Description: Array of MultiSignatureInternalsGridResponse
### addresses


Type Description: Array of MultiSignatureAddressesGridResponse
### listings


Type Description: Array of MultiSignatureRelatedListingsGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "signature_internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureInternalsGrid"},
       "addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureAddressesGrid"},
       "listings" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureRelatedListingsGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiSignatureInternalsGridResponse](MultiSignatureInternalsGridResponse.md)
- [MultiSignatureAddressesGridResponse](MultiSignatureAddressesGridResponse.md)
- [MultiSignatureRelatedListingsGridResponse](MultiSignatureRelatedListingsGridResponse.md)

