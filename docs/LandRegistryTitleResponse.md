# LandRegistryTitleResponse
## Properties
- title_number (String)

   
- tenancy (String)

   
- id (String)

   
- key_signatures (Array of [KeySignaturesGridResponse](KeySignaturesGridResponse.md))

   
- land_registry_title_upr_ns (Array of [LandRegistryTitleUPRNsGridResponse](LandRegistryTitleUPRNsGridResponse.md))

   
- key_signatures_internals (Array of [KeySignaturesInternalsGridResponse](KeySignaturesInternalsGridResponse.md))

   
- key_addresses_data_grid (Array of [KeyAddressesDataGridResponse](KeyAddressesDataGridResponse.md))

   
- title_details_data_grid (Array of [TitleDetailsDataGridResponse](TitleDetailsDataGridResponse.md))

   
- listings (Array of [SignatureKeyRelatedListingsGridResponse](SignatureKeyRelatedListingsGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "title_number" : ["string", "null"],
       "tenancy" : ["string", "null"],
       "id" : ["string", "null"],
       "key_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/KeySignaturesGrid"},
       "land_registry_title_upr_ns" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitleUPRNsGrid"},
       "key_signatures_internals" : {"type" : "array", "items" : {"$ref" : "/schemas/KeySignaturesInternalsGrid"},
       "key_addresses_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/KeyAddressesDataGrid"},
       "title_details_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/TitleDetailsDataGrid"},
       "listings" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureKeyRelatedListingsGrid"}
}
```

