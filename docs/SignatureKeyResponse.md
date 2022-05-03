# SignatureKeyResponse
## Properties
- key_type (String)

   
- key_value (String)

   
- key_signatures (Array of [KeySignaturesGridResponse](KeySignaturesGridResponse.md))

   
- key_signatures_internals (Array of [KeySignaturesInternalsGridResponse](KeySignaturesInternalsGridResponse.md))

   
- key_addresses_data_grid (Array of [KeyAddressesDataGridResponse](KeyAddressesDataGridResponse.md))

   
- listings (Array of [SignatureKeyRelatedListingsGridResponse](SignatureKeyRelatedListingsGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "key_type" : ["string", "null"],
       "key_value" : ["string", "null"],
       "key_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/KeySignaturesGrid"},
       "key_signatures_internals" : {"type" : "array", "items" : {"$ref" : "/schemas/KeySignaturesInternalsGrid"},
       "key_addresses_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/KeyAddressesDataGrid"},
       "listings" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureKeyRelatedListingsGrid"}
}
```

