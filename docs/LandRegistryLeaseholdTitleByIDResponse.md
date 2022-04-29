# LandRegistryLeaseholdTitleByIDResponse
## Description

## Properties
### title_number


Type Description: String
### tenancy


Type Description: String
### id


Type Description: String
### price_paid


Type Description: String
### description


Type Description: String
### county


Type Description: String
### region


Type Description: String
### alienation_clause_indicator


Type Description: String
### land_registry_lease_entries_data_grid


Type Description: Array of LandRegistryLeaseEntriesDataGridResponse
### land_registry_title_upr_ns


Type Description: Array of LandRegistryTitleUPRNsGridResponse
### title_details_data_grid


Type Description: Array of TitleDetailsDataGridResponse
### signatures


Type Description: Array of MultiSignatureGridResponse
### internals


Type Description: Array of MultiInternalAddressesGridResponse
### no_signatures


Type Description: Array of NoSignatureAddressesDataGridResponse

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

## Related Entities
- [LandRegistryLeaseEntriesDataGridResponse](LandRegistryLeaseEntriesDataGridResponse.md)
- [LandRegistryTitleUPRNsGridResponse](LandRegistryTitleUPRNsGridResponse.md)
- [TitleDetailsDataGridResponse](TitleDetailsDataGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

