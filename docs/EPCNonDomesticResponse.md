# EPCNonDomesticResponse
## Description

## Properties
### lmk_key


Type Description: String
### address1


Type Description: String
### address2


Type Description: String
### address3


Type Description: String
### postcode


Type Description: String
### building_reference_number


Type Description: String
### asset_rating


Type Description: String
### asset_rating_band


Type Description: String
### property_type


Type Description: String
### inspection_date


Type Description: String
### local_authority


Type Description: String
### constituency


Type Description: String
### county


Type Description: String
### lodgement_date


Type Description: String
### transaction_type


Type Description: String
### new_build_benchmark


Type Description: String
### existing_stock_benchmark


Type Description: String
### building_level


Type Description: String
### main_heating_fuel


Type Description: String
### other_fuel_desc


Type Description: String
### special_energy_uses


Type Description: String
### renewable_sources


Type Description: String
### floor_area


Type Description: String
### standard_emissions


Type Description: String
### target_emissions


Type Description: String
### typical_emissions


Type Description: String
### building_emissions


Type Description: String
### aircon_present


Type Description: String
### aircon_kw_rating


Type Description: String
### estimated_aircon_kw_rating


Type Description: String
### ac_inspection_commissioned


Type Description: String
### building_environment


Type Description: String
### address


Type Description: String
### local_authority_label


Type Description: String
### constituency_label


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
       "lmk_key" : ["string", "null"],
       "address1" : ["string", "null"],
       "address2" : ["string", "null"],
       "address3" : ["string", "null"],
       "postcode" : ["string", "null"],
       "building_reference_number" : ["string", "null"],
       "asset_rating" : ["string", "null"],
       "asset_rating_band" : ["string", "null"],
       "property_type" : ["string", "null"],
       "inspection_date" : ["string", "null"],
       "local_authority" : ["string", "null"],
       "constituency" : ["string", "null"],
       "county" : ["string", "null"],
       "lodgement_date" : ["string", "null"],
       "transaction_type" : ["string", "null"],
       "new_build_benchmark" : ["string", "null"],
       "existing_stock_benchmark" : ["string", "null"],
       "building_level" : ["string", "null"],
       "main_heating_fuel" : ["string", "null"],
       "other_fuel_desc" : ["string", "null"],
       "special_energy_uses" : ["string", "null"],
       "renewable_sources" : ["string", "null"],
       "floor_area" : ["string", "null"],
       "standard_emissions" : ["string", "null"],
       "target_emissions" : ["string", "null"],
       "typical_emissions" : ["string", "null"],
       "building_emissions" : ["string", "null"],
       "aircon_present" : ["string", "null"],
       "aircon_kw_rating" : ["string", "null"],
       "estimated_aircon_kw_rating" : ["string", "null"],
       "ac_inspection_commissioned" : ["string", "null"],
       "building_environment" : ["string", "null"],
       "address" : ["string", "null"],
       "local_authority_label" : ["string", "null"],
       "constituency_label" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

