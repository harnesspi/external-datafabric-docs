# SignatureInternalKeyResponse
## Properties
- key_type (String)

   
- key_value (String)

   
- internal_key_signature_internals (Array of [InternalKeySignaturesInternalsGridResponse](InternalKeySignaturesInternalsGridResponse.md))

   
- addresses (Array of [SignatureInternalKeyAddressesGridResponse](SignatureInternalKeyAddressesGridResponse.md))

   

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

