# LandRegistryRestrictiveCovenantAddressResponse
## Properties
- id (String)

   
- entry_number (String)

   
- address_id (String)

   
- address (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "id" : ["string", "null"],
       "entry_number" : ["string", "null"],
       "address_id" : ["string", "null"],
       "address" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

