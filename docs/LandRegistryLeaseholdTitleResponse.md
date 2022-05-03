# LandRegistryLeaseholdTitleResponse
## Properties
- title_number (String)

   
- tenancy (String)

   
- id (String)

   
- price_paid (String)

   
- description (String)

   
- county (String)

   
- region (String)

   
- alienation_clause_indicator (String)

   
- land_registry_lease_entries_data_grid (Array of [LandRegistryLeaseEntriesDataGridResponse](LandRegistryLeaseEntriesDataGridResponse.md))

   
- land_registry_title_upr_ns (Array of [LandRegistryTitleUPRNsGridResponse](LandRegistryTitleUPRNsGridResponse.md))

   
- title_details_data_grid (Array of [TitleDetailsDataGridResponse](TitleDetailsDataGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "title_number" : ["string", "null"],
       "tenancy" : ["string", "null"],
       "id" : ["string", "null"],
       "price_paid" : ["string", "null"],
       "description" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "alienation_clause_indicator" : ["string", "null"],
       "land_registry_lease_entries_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryLeaseEntriesDataGrid"},
       "land_registry_title_upr_ns" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitleUPRNsGrid"},
       "title_details_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/TitleDetailsDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

