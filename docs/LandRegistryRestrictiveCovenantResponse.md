# LandRegistryRestrictiveCovenantResponse
## Properties
- title_number (String)

   
- lease_id (String)

   
- id (String)

   
- tenure (String)

   
- description (String)

   
- county (String)

   
- region (String)

   
- land_registry_restrictive_covenant_address_data_grid (Array of [LandRegistryRestrictiveCovenantAddressDataGridResponse](LandRegistryRestrictiveCovenantAddressDataGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "title_number" : ["string", "null"],
       "lease_id" : ["string", "null"],
       "id" : ["string", "null"],
       "tenure" : ["string", "null"],
       "description" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "land_registry_restrictive_covenant_address_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryRestrictiveCovenantAddressDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

