# MultiSignatureResponse
## Description
This a test description
## Properties
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- signature_internals (Array of [MultiSignatureInternalsGridResponse](MultiSignatureInternalsGridResponse.md))

   
- addresses (Array of [MultiSignatureAddressesGridResponse](MultiSignatureAddressesGridResponse.md))

   
- listings (Array of [MultiSignatureRelatedListingsGridResponse](MultiSignatureRelatedListingsGridResponse.md))

   

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

