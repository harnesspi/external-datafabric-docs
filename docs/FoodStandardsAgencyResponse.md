# FoodStandardsAgencyResponse
## Description

## Properties
### fhrsid


Type Description: String
### local_authority_business_id


Type Description: String
### business_name


Type Description: String
### address_line1


Type Description: String
### address_line2


Type Description: String
### address_line3


Type Description: String
### address_line4


Type Description: String
### post_code


Type Description: String
### business_type


Type Description: String
### business_type_id


Type Description: String
### scheme_type


Type Description: String
### new_rating_pending


Type Description: String
### local_authority_code


Type Description: String
### local_authority_name


Type Description: String
### longitude


Type Description: String
### latitude


Type Description: String
### rating_date


Type Description: String
### rating_key


Type Description: String
### rating_value


Type Description: String
### hygiene


Type Description: String
### structural


Type Description: String
### confidence_in_management


Type Description: String
### snapshot_date


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
       "fhrsid" : ["string", "null"],
       "local_authority_business_id" : ["string", "null"],
       "business_name" : ["string", "null"],
       "address_line1" : ["string", "null"],
       "address_line2" : ["string", "null"],
       "address_line3" : ["string", "null"],
       "address_line4" : ["string", "null"],
       "post_code" : ["string", "null"],
       "business_type" : ["string", "null"],
       "business_type_id" : ["string", "null"],
       "scheme_type" : ["string", "null"],
       "new_rating_pending" : ["string", "null"],
       "local_authority_code" : ["string", "null"],
       "local_authority_name" : ["string", "null"],
       "longitude" : ["string", "null"],
       "latitude" : ["string", "null"],
       "rating_date" : ["string", "null"],
       "rating_key" : ["string", "null"],
       "rating_value" : ["string", "null"],
       "hygiene" : ["string", "null"],
       "structural" : ["string", "null"],
       "confidence_in_management" : ["string", "null"],
       "snapshot_date" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

