# EPCDisplayResponse
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
### posttown


Type Description: String
### local_authority


Type Description: String
### constituency


Type Description: String
### county


Type Description: String
### building_reference_number


Type Description: String
### property_type


Type Description: String
### total_floor_area


Type Description: String
### inspection_date


Type Description: String
### lodgement_date


Type Description: String
### building_environment


Type Description: String
### building_category


Type Description: String
### address


Type Description: String
### local_authority_label


Type Description: String
### constituency_label


Type Description: String
### nominated_date


Type Description: String
### or_assessment_end_date


Type Description: String
### lodgement_datetime


Type Description: String
### occupancy_level


Type Description: String
### current_operational_rating


Type Description: String
### y_r1_operational_rating


Type Description: String
### y_r2_operational_rating


Type Description: String
### operational_rating_band


Type Description: String
### aircon_present


Type Description: String
### aircon_kw_rating


Type Description: String
### estimated_aircon_kw_rating


Type Description: String
### ac_inspection_commissioned


Type Description: String
### electric_c_o2


Type Description: String
### heating_c_o2


Type Description: String
### renewables_c_o2


Type Description: String
### main_benchmark


Type Description: String
### main_heating_fuel


Type Description: String
### other_fuel


Type Description: String
### special_energy_uses


Type Description: String
### renewable_sources


Type Description: String
### annual_thermal_fuel_usage


Type Description: String
### typical_thermal_fuel_usage


Type Description: String
### annual_electrical_fuel_usage


Type Description: String
### typical_electrical_fuel_usage


Type Description: String
### renewables_fuel_thermal


Type Description: String
### renewables_electrical


Type Description: String
### y_r1_electricity_c_o2


Type Description: String
### y_r2_electricity_c_o2


Type Description: String
### y_r1_heating_c_o2


Type Description: String
### y_r2_heating_c_o2


Type Description: String
### y_r1_renewables_c_o2


Type Description: String
### y_r2_renewables_c_o2


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
       "posttown" : ["string", "null"],
       "local_authority" : ["string", "null"],
       "constituency" : ["string", "null"],
       "county" : ["string", "null"],
       "building_reference_number" : ["string", "null"],
       "property_type" : ["string", "null"],
       "total_floor_area" : ["string", "null"],
       "inspection_date" : ["string", "null"],
       "lodgement_date" : ["string", "null"],
       "building_environment" : ["string", "null"],
       "building_category" : ["string", "null"],
       "address" : ["string", "null"],
       "local_authority_label" : ["string", "null"],
       "constituency_label" : ["string", "null"],
       "nominated_date" : ["string", "null"],
       "or_assessment_end_date" : ["string", "null"],
       "lodgement_datetime" : ["string", "null"],
       "occupancy_level" : ["string", "null"],
       "current_operational_rating" : ["string", "null"],
       "y_r1_operational_rating" : ["string", "null"],
       "y_r2_operational_rating" : ["string", "null"],
       "operational_rating_band" : ["string", "null"],
       "aircon_present" : ["string", "null"],
       "aircon_kw_rating" : ["string", "null"],
       "estimated_aircon_kw_rating" : ["string", "null"],
       "ac_inspection_commissioned" : ["string", "null"],
       "electric_c_o2" : ["string", "null"],
       "heating_c_o2" : ["string", "null"],
       "renewables_c_o2" : ["string", "null"],
       "main_benchmark" : ["string", "null"],
       "main_heating_fuel" : ["string", "null"],
       "other_fuel" : ["string", "null"],
       "special_energy_uses" : ["string", "null"],
       "renewable_sources" : ["string", "null"],
       "annual_thermal_fuel_usage" : ["string", "null"],
       "typical_thermal_fuel_usage" : ["string", "null"],
       "annual_electrical_fuel_usage" : ["string", "null"],
       "typical_electrical_fuel_usage" : ["string", "null"],
       "renewables_fuel_thermal" : ["string", "null"],
       "renewables_electrical" : ["string", "null"],
       "y_r1_electricity_c_o2" : ["string", "null"],
       "y_r2_electricity_c_o2" : ["string", "null"],
       "y_r1_heating_c_o2" : ["string", "null"],
       "y_r2_heating_c_o2" : ["string", "null"],
       "y_r1_renewables_c_o2" : ["string", "null"],
       "y_r2_renewables_c_o2" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

