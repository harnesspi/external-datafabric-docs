# ScottishAssessorsResponse
## Properties
- uarn (String)

   
- organisation_role (String)

   
- organisation (String)

   
- address_date (String)

   
- description (String)

   
- nav (String)

   
- rv (String)

   
- res_apportion (String)

   
- non_res_apportion (String)

   
- sub_building_start_number (String)

   
- sub_building_end_number (String)

   
- sub_building (String)

   
- building_start_number (String)

   
- building_end_number (String)

   
- building (String)

   
- thoroughfare (String)

   
- post_town (String)

   
- dependent_locality (String)

   
- postcode (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "uarn" : ["string", "null"],
       "organisation_role" : ["string", "null"],
       "organisation" : ["string", "null"],
       "address_date" : ["string", "null"],
       "description" : ["string", "null"],
       "nav" : ["string", "null"],
       "rv" : ["string", "null"],
       "res_apportion" : ["string", "null"],
       "non_res_apportion" : ["string", "null"],
       "sub_building_start_number" : ["string", "null"],
       "sub_building_end_number" : ["string", "null"],
       "sub_building" : ["string", "null"],
       "building_start_number" : ["string", "null"],
       "building_end_number" : ["string", "null"],
       "building" : ["string", "null"],
       "thoroughfare" : ["string", "null"],
       "post_town" : ["string", "null"],
       "dependent_locality" : ["string", "null"],
       "postcode" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

