# SignatureKeyResponse
## Description

## Properties
### key_type


Type Description: String
### key_value


Type Description: String
### key_signatures


Type Description: Array of KeySignaturesGridResponse
### key_signatures_internals


Type Description: Array of KeySignaturesInternalsGridResponse
### key_addresses_data_grid


Type Description: Array of KeyAddressesDataGridResponse
### listings


Type Description: Array of SignatureKeyRelatedListingsGridResponse

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

## Related Entities
- [KeySignaturesGridResponse](KeySignaturesGridResponse.md)
- [KeySignaturesInternalsGridResponse](KeySignaturesInternalsGridResponse.md)
- [KeyAddressesDataGridResponse](KeyAddressesDataGridResponse.md)
- [SignatureKeyRelatedListingsGridResponse](SignatureKeyRelatedListingsGridResponse.md)

