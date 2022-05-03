# EPCDisplayResponse
## Properties
- lmk_key (String)

   
- address1 (String)

   
- address2 (String)

   
- address3 (String)

   
- postcode (String)

   
- posttown (String)

   
- local_authority (String)

   
- constituency (String)

   
- county (String)

   
- building_reference_number (String)

   
- property_type (String)

   
- total_floor_area (String)

   
- inspection_date (String)

   
- lodgement_date (String)

   
- building_environment (String)

   
- building_category (String)

   
- address (String)

   
- local_authority_label (String)

   
- constituency_label (String)

   
- nominated_date (String)

   
- or_assessment_end_date (String)

   
- lodgement_datetime (String)

   
- occupancy_level (String)

   
- current_operational_rating (String)

   
- y_r1_operational_rating (String)

   
- y_r2_operational_rating (String)

   
- operational_rating_band (String)

   
- aircon_present (String)

   
- aircon_kw_rating (String)

   
- estimated_aircon_kw_rating (String)

   
- ac_inspection_commissioned (String)

   
- electric_c_o2 (String)

   
- heating_c_o2 (String)

   
- renewables_c_o2 (String)

   
- main_benchmark (String)

   
- main_heating_fuel (String)

   
- other_fuel (String)

   
- special_energy_uses (String)

   
- renewable_sources (String)

   
- annual_thermal_fuel_usage (String)

   
- typical_thermal_fuel_usage (String)

   
- annual_electrical_fuel_usage (String)

   
- typical_electrical_fuel_usage (String)

   
- renewables_fuel_thermal (String)

   
- renewables_electrical (String)

   
- y_r1_electricity_c_o2 (String)

   
- y_r2_electricity_c_o2 (String)

   
- y_r1_heating_c_o2 (String)

   
- y_r2_heating_c_o2 (String)

   
- y_r1_renewables_c_o2 (String)

   
- y_r2_renewables_c_o2 (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

