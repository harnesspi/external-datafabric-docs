# SignatureInternalKeyResponse
## Description

## Properties
### key_type


Type Description: String
### key_value


Type Description: String
### internal_key_signature_internals


Type Description: Array of InternalKeySignaturesInternalsGridResponse
### addresses


Type Description: Array of SignatureInternalKeyAddressesGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "key_type" : ["string", "null"],
       "key_value" : ["string", "null"],
       "internal_key_signature_internals" : {"type" : "array", "items" : {"$ref" : "/schemas/InternalKeySignaturesInternalsGrid"},
       "addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureInternalKeyAddressesGrid"}
}
```

## Related Entities
- [InternalKeySignaturesInternalsGridResponse](InternalKeySignaturesInternalsGridResponse.md)
- [SignatureInternalKeyAddressesGridResponse](SignatureInternalKeyAddressesGridResponse.md)

