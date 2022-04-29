# EPCDomesticResponse
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
### address


Type Description: String
### local_authority_label


Type Description: String
### constituency_label


Type Description: String
### certificate_hash


Type Description: String
### building_reference_number


Type Description: String
### current_energy_rating


Type Description: String
### potential_energy_rating


Type Description: String
### current_energy_efficiency


Type Description: String
### potential_energy_efficiency


Type Description: String
### property_type


Type Description: String
### total_floor_area


Type Description: String
### floor_level


Type Description: String
### built_form


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
### environment_impact_current


Type Description: String
### environment_impact_potential


Type Description: String
### energy_consumption_current


Type Description: String
### energy_consumption_potential


Type Description: String
### co2_emissions_current


Type Description: String
### co2_emiss_curr_per_floor_area


Type Description: String
### co2_emissions_potential


Type Description: String
### lighting_cost_current


Type Description: String
### lighting_cost_potential


Type Description: String
### heating_cost_current


Type Description: String
### heating_cost_potential


Type Description: String
### hot_water_cost_current


Type Description: String
### hot_water_cost_potential


Type Description: String
### energy_tariff


Type Description: String
### mains_gas_flag


Type Description: String
### flat_top_storey


Type Description: String
### flat_storey_count


Type Description: String
### main_heating_controls


Type Description: String
### multi_glaze_proportion


Type Description: String
### glazed_type


Type Description: String
### glazed_area


Type Description: String
### extension_count


Type Description: String
### number_habitable_rooms


Type Description: String
### number_heated_rooms


Type Description: String
### low_energy_lighting


Type Description: String
### number_open_fireplaces


Type Description: String
### hotwater_description


Type Description: String
### hot_water_energy_eff


Type Description: String
### hot_water_env_eff


Type Description: String
### floor_description


Type Description: String
### floor_energy_eff


Type Description: String
### floor_env_eff


Type Description: String
### windows_description


Type Description: String
### windows_energy_eff


Type Description: String
### windows_env_eff


Type Description: String
### walls_description


Type Description: String
### walls_energy_eff


Type Description: String
### walls_env_eff


Type Description: String
### secondheat_description


Type Description: String
### sheating_energy_eff


Type Description: String
### sheating_env_eff


Type Description: String
### roof_description


Type Description: String
### roof_energy_eff


Type Description: String
### roof_env_eff


Type Description: String
### mainheat_description


Type Description: String
### mainheat_energy_eff


Type Description: String
### mainheat_env_eff


Type Description: String
### mainheatcont_description


Type Description: String
### mainheatc_energy_eff


Type Description: String
### mainheatc_env_eff


Type Description: String
### lighting_description


Type Description: String
### lighting_energy_eff


Type Description: String
### lighting_env_eff


Type Description: String
### main_fuel


Type Description: String
### wind_turbine_count


Type Description: String
### heat_loss_corridoor


Type Description: String
### unheated_corridor_length


Type Description: String
### floor_height


Type Description: String
### photo_supply


Type Description: String
### solar_water_heating_flag


Type Description: String
### mechanical_ventilation


Type Description: String
### posttown


Type Description: String
### construction_age_band


Type Description: String
### lodgement_datetime


Type Description: String
### tenure


Type Description: String
### fixed_lighting_outlets_count


Type Description: String
### low_energy_fixed_light_count


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

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

