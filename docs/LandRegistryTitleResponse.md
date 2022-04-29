# LandRegistryTitleResponse
## Description

## Properties
### title_number


Type Description: String
### tenancy


Type Description: String
### id


Type Description: String
### key_signatures


Type Description: Array of KeySignaturesGridResponse
### land_registry_title_upr_ns


Type Description: Array of LandRegistryTitleUPRNsGridResponse
### key_signatures_internals


Type Description: Array of KeySignaturesInternalsGridResponse
### key_addresses_data_grid


Type Description: Array of KeyAddressesDataGridResponse
### title_details_data_grid


Type Description: Array of TitleDetailsDataGridResponse
### listings


Type Description: Array of SignatureKeyRelatedListingsGridResponse

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

## Related Entities
- [KeySignaturesGridResponse](KeySignaturesGridResponse.md)
- [LandRegistryTitleUPRNsGridResponse](LandRegistryTitleUPRNsGridResponse.md)
- [KeySignaturesInternalsGridResponse](KeySignaturesInternalsGridResponse.md)
- [KeyAddressesDataGridResponse](KeyAddressesDataGridResponse.md)
- [TitleDetailsDataGridResponse](TitleDetailsDataGridResponse.md)
- [SignatureKeyRelatedListingsGridResponse](SignatureKeyRelatedListingsGridResponse.md)

