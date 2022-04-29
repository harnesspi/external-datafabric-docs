# ScottishAssessorsResponse
## Description

## Properties
### uarn


Type Description: String
### organisation_role


Type Description: String
### organisation


Type Description: String
### address_date


Type Description: String
### description


Type Description: String
### nav


Type Description: String
### rv


Type Description: String
### res_apportion


Type Description: String
### non_res_apportion


Type Description: String
### sub_building_start_number


Type Description: String
### sub_building_end_number


Type Description: String
### sub_building


Type Description: String
### building_start_number


Type Description: String
### building_end_number


Type Description: String
### building


Type Description: String
### thoroughfare


Type Description: String
### post_town


Type Description: String
### dependent_locality


Type Description: String
### postcode


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

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

