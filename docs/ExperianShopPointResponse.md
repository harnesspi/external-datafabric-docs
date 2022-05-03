# ExperianShopPointResponse
## Properties
- location_urn (String)

   
- fascia (String)

   
- activity (String)

   
- brand (String)

   
- retail_group_name (String)

   
- address1 (String)

   
- address2 (String)

   
- locality (String)

   
- town (String)

   
- county (String)

   
- region (String)

   
- country (String)

   
- postcode (String)

   
- x (String)

   
- y (String)

   
- lat (String)

   
- long (String)

   
- output_area (String)

   
- postal_sector (String)

   
- standard_location_name (String)

   
- location_name (String)

   
- managed_site_name (String)

   
- site_classification (String)

   
- category (String)

   
- sub_class (String)

   
- top_class (String)

   
- report_type (String)

   
- group_name (String)

   
- sic_code_description (String)

   
- use_class (String)

   
- sq_ft (String)

   
- occupancy_confidence_level (String)

   
- source (String)

   
- concession (String)

   
- verification_date (String)

   
- trading_floors (String)

   
- car_park_spaces (String)

   
- comments (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

