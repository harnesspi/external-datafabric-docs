# EPCNonDomesticResponse
## Properties
- lmk_key (String)

   
- address1 (String)

   
- address2 (String)

   
- address3 (String)

   
- postcode (String)

   
- building_reference_number (String)

   
- asset_rating (String)

   
- asset_rating_band (String)

   
- property_type (String)

   
- inspection_date (String)

   
- local_authority (String)

   
- constituency (String)

   
- county (String)

   
- lodgement_date (String)

   
- transaction_type (String)

   
- new_build_benchmark (String)

   
- existing_stock_benchmark (String)

   
- building_level (String)

   
- main_heating_fuel (String)

   
- other_fuel_desc (String)

   
- special_energy_uses (String)

   
- renewable_sources (String)

   
- floor_area (String)

   
- standard_emissions (String)

   
- target_emissions (String)

   
- typical_emissions (String)

   
- building_emissions (String)

   
- aircon_present (String)

   
- aircon_kw_rating (String)

   
- estimated_aircon_kw_rating (String)

   
- ac_inspection_commissioned (String)

   
- building_environment (String)

   
- address (String)

   
- local_authority_label (String)

   
- constituency_label (String)

   
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

