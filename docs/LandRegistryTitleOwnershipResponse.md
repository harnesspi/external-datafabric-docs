# LandRegistryTitleOwnershipResponse
## Description

## Properties
### title_number


Type Description: String
### tenure


Type Description: String
### property_address


Type Description: String
### district


Type Description: String
### county


Type Description: String
### region


Type Description: String
### postcode


Type Description: String
### multiple_address_indicator


Type Description: String
### price_paid


Type Description: String
### date_proprietor_added


Type Description: String
### additional_proprietor_indicator


Type Description: String
### land_registry_title_companies


Type Description: Array of LandRegistryTitleCompaniesGridResponse
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
       "tenure" : ["string", "null"],
       "property_address" : ["string", "null"],
       "district" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "postcode" : ["string", "null"],
       "multiple_address_indicator" : ["string", "null"],
       "price_paid" : ["string", "null"],
       "date_proprietor_added" : ["string", "null"],
       "additional_proprietor_indicator" : ["string", "null"],
       "land_registry_title_companies" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitleCompaniesGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [LandRegistryTitleCompaniesGridResponse](LandRegistryTitleCompaniesGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

