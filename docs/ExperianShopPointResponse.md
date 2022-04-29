# ExperianShopPointResponse
## Description

## Properties
### location_urn


Type Description: String
### fascia


Type Description: String
### activity


Type Description: String
### brand


Type Description: String
### retail_group_name


Type Description: String
### address1


Type Description: String
### address2


Type Description: String
### locality


Type Description: String
### town


Type Description: String
### county


Type Description: String
### region


Type Description: String
### country


Type Description: String
### postcode


Type Description: String
### x


Type Description: String
### y


Type Description: String
### lat


Type Description: String
### long


Type Description: String
### output_area


Type Description: String
### postal_sector


Type Description: String
### standard_location_name


Type Description: String
### location_name


Type Description: String
### managed_site_name


Type Description: String
### site_classification


Type Description: String
### category


Type Description: String
### sub_class


Type Description: String
### top_class


Type Description: String
### report_type


Type Description: String
### group_name


Type Description: String
### sic_code_description


Type Description: String
### use_class


Type Description: String
### sq_ft


Type Description: String
### occupancy_confidence_level


Type Description: String
### source


Type Description: String
### concession


Type Description: String
### verification_date


Type Description: String
### trading_floors


Type Description: String
### car_park_spaces


Type Description: String
### comments


Type Description: String
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
       "location_urn" : ["string", "null"],
       "fascia" : ["string", "null"],
       "activity" : ["string", "null"],
       "brand" : ["string", "null"],
       "retail_group_name" : ["string", "null"],
       "address1" : ["string", "null"],
       "address2" : ["string", "null"],
       "locality" : ["string", "null"],
       "town" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "country" : ["string", "null"],
       "postcode" : ["string", "null"],
       "x" : ["string", "null"],
       "y" : ["string", "null"],
       "lat" : ["string", "null"],
       "long" : ["string", "null"],
       "output_area" : ["string", "null"],
       "postal_sector" : ["string", "null"],
       "standard_location_name" : ["string", "null"],
       "location_name" : ["string", "null"],
       "managed_site_name" : ["string", "null"],
       "site_classification" : ["string", "null"],
       "category" : ["string", "null"],
       "sub_class" : ["string", "null"],
       "top_class" : ["string", "null"],
       "report_type" : ["string", "null"],
       "group_name" : ["string", "null"],
       "sic_code_description" : ["string", "null"],
       "use_class" : ["string", "null"],
       "sq_ft" : ["string", "null"],
       "occupancy_confidence_level" : ["string", "null"],
       "source" : ["string", "null"],
       "concession" : ["string", "null"],
       "verification_date" : ["string", "null"],
       "trading_floors" : ["string", "null"],
       "car_park_spaces" : ["string", "null"],
       "comments" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

