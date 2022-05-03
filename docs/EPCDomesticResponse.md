# EPCDomesticResponse
## Properties
- lmk_key (String)

   
- address1 (String)

   
- address2 (String)

   
- address3 (String)

   
- postcode (String)

   
- address (String)

   
- local_authority_label (String)

   
- constituency_label (String)

   
- certificate_hash (String)

   
- building_reference_number (String)

   
- current_energy_rating (String)

   
- potential_energy_rating (String)

   
- current_energy_efficiency (String)

   
- potential_energy_efficiency (String)

   
- property_type (String)

   
- total_floor_area (String)

   
- floor_level (String)

   
- built_form (String)

   
- inspection_date (String)

   
- local_authority (String)

   
- constituency (String)

   
- county (String)

   
- lodgement_date (String)

   
- transaction_type (String)

   
- environment_impact_current (String)

   
- environment_impact_potential (String)

   
- energy_consumption_current (String)

   
- energy_consumption_potential (String)

   
- co2_emissions_current (String)

   
- co2_emiss_curr_per_floor_area (String)

   
- co2_emissions_potential (String)

   
- lighting_cost_current (String)

   
- lighting_cost_potential (String)

   
- heating_cost_current (String)

   
- heating_cost_potential (String)

   
- hot_water_cost_current (String)

   
- hot_water_cost_potential (String)

   
- energy_tariff (String)

   
- mains_gas_flag (String)

   
- flat_top_storey (String)

   
- flat_storey_count (String)

   
- main_heating_controls (String)

   
- multi_glaze_proportion (String)

   
- glazed_type (String)

   
- glazed_area (String)

   
- extension_count (String)

   
- number_habitable_rooms (String)

   
- number_heated_rooms (String)

   
- low_energy_lighting (String)

   
- number_open_fireplaces (String)

   
- hotwater_description (String)

   
- hot_water_energy_eff (String)

   
- hot_water_env_eff (String)

   
- floor_description (String)

   
- floor_energy_eff (String)

   
- floor_env_eff (String)

   
- windows_description (String)

   
- windows_energy_eff (String)

   
- windows_env_eff (String)

   
- walls_description (String)

   
- walls_energy_eff (String)

   
- walls_env_eff (String)

   
- secondheat_description (String)

   
- sheating_energy_eff (String)

   
- sheating_env_eff (String)

   
- roof_description (String)

   
- roof_energy_eff (String)

   
- roof_env_eff (String)

   
- mainheat_description (String)

   
- mainheat_energy_eff (String)

   
- mainheat_env_eff (String)

   
- mainheatcont_description (String)

   
- mainheatc_energy_eff (String)

   
- mainheatc_env_eff (String)

   
- lighting_description (String)

   
- lighting_energy_eff (String)

   
- lighting_env_eff (String)

   
- main_fuel (String)

   
- wind_turbine_count (String)

   
- heat_loss_corridoor (String)

   
- unheated_corridor_length (String)

   
- floor_height (String)

   
- photo_supply (String)

   
- solar_water_heating_flag (String)

   
- mechanical_ventilation (String)

   
- posttown (String)

   
- construction_age_band (String)

   
- lodgement_datetime (String)

   
- tenure (String)

   
- fixed_lighting_outlets_count (String)

   
- low_energy_fixed_light_count (String)

   
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
       "address" : ["string", "null"],
       "local_authority_label" : ["string", "null"],
       "constituency_label" : ["string", "null"],
       "certificate_hash" : ["string", "null"],
       "building_reference_number" : ["string", "null"],
       "current_energy_rating" : ["string", "null"],
       "potential_energy_rating" : ["string", "null"],
       "current_energy_efficiency" : ["string", "null"],
       "potential_energy_efficiency" : ["string", "null"],
       "property_type" : ["string", "null"],
       "total_floor_area" : ["string", "null"],
       "floor_level" : ["string", "null"],
       "built_form" : ["string", "null"],
       "inspection_date" : ["string", "null"],
       "local_authority" : ["string", "null"],
       "constituency" : ["string", "null"],
       "county" : ["string", "null"],
       "lodgement_date" : ["string", "null"],
       "transaction_type" : ["string", "null"],
       "environment_impact_current" : ["string", "null"],
       "environment_impact_potential" : ["string", "null"],
       "energy_consumption_current" : ["string", "null"],
       "energy_consumption_potential" : ["string", "null"],
       "co2_emissions_current" : ["string", "null"],
       "co2_emiss_curr_per_floor_area" : ["string", "null"],
       "co2_emissions_potential" : ["string", "null"],
       "lighting_cost_current" : ["string", "null"],
       "lighting_cost_potential" : ["string", "null"],
       "heating_cost_current" : ["string", "null"],
       "heating_cost_potential" : ["string", "null"],
       "hot_water_cost_current" : ["string", "null"],
       "hot_water_cost_potential" : ["string", "null"],
       "energy_tariff" : ["string", "null"],
       "mains_gas_flag" : ["string", "null"],
       "flat_top_storey" : ["string", "null"],
       "flat_storey_count" : ["string", "null"],
       "main_heating_controls" : ["string", "null"],
       "multi_glaze_proportion" : ["string", "null"],
       "glazed_type" : ["string", "null"],
       "glazed_area" : ["string", "null"],
       "extension_count" : ["string", "null"],
       "number_habitable_rooms" : ["string", "null"],
       "number_heated_rooms" : ["string", "null"],
       "low_energy_lighting" : ["string", "null"],
       "number_open_fireplaces" : ["string", "null"],
       "hotwater_description" : ["string", "null"],
       "hot_water_energy_eff" : ["string", "null"],
       "hot_water_env_eff" : ["string", "null"],
       "floor_description" : ["string", "null"],
       "floor_energy_eff" : ["string", "null"],
       "floor_env_eff" : ["string", "null"],
       "windows_description" : ["string", "null"],
       "windows_energy_eff" : ["string", "null"],
       "windows_env_eff" : ["string", "null"],
       "walls_description" : ["string", "null"],
       "walls_energy_eff" : ["string", "null"],
       "walls_env_eff" : ["string", "null"],
       "secondheat_description" : ["string", "null"],
       "sheating_energy_eff" : ["string", "null"],
       "sheating_env_eff" : ["string", "null"],
       "roof_description" : ["string", "null"],
       "roof_energy_eff" : ["string", "null"],
       "roof_env_eff" : ["string", "null"],
       "mainheat_description" : ["string", "null"],
       "mainheat_energy_eff" : ["string", "null"],
       "mainheat_env_eff" : ["string", "null"],
       "mainheatcont_description" : ["string", "null"],
       "mainheatc_energy_eff" : ["string", "null"],
       "mainheatc_env_eff" : ["string", "null"],
       "lighting_description" : ["string", "null"],
       "lighting_energy_eff" : ["string", "null"],
       "lighting_env_eff" : ["string", "null"],
       "main_fuel" : ["string", "null"],
       "wind_turbine_count" : ["string", "null"],
       "heat_loss_corridoor" : ["string", "null"],
       "unheated_corridor_length" : ["string", "null"],
       "floor_height" : ["string", "null"],
       "photo_supply" : ["string", "null"],
       "solar_water_heating_flag" : ["string", "null"],
       "mechanical_ventilation" : ["string", "null"],
       "posttown" : ["string", "null"],
       "construction_age_band" : ["string", "null"],
       "lodgement_datetime" : ["string", "null"],
       "tenure" : ["string", "null"],
       "fixed_lighting_outlets_count" : ["string", "null"],
       "low_energy_fixed_light_count" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

