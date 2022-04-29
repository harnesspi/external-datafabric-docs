# AddressResponse
## Description

## Properties
### signature_hpid


Type Description: String
### address_hpid


Type Description: String
### matching_type


Type Description: String
### source_name


Type Description: String
### row_key


Type Description: String
### row_key_subfix


Type Description: String
### uprn


Type Description: String
### usrn


Type Description: String
### organisation


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
### address


Type Description: String
### street


Type Description: String
### postcode


Type Description: String
### internals


Type Description: String
### floors


Type Description: String
### area_sq_mt


Type Description: String
### address_date


Type Description: String
### address_end_date


Type Description: String
### address_string_type


Type Description: String
### object_type


Type Description: String
### classification_code


Type Description: String
### classification_description


Type Description: String
### postal_addressable


Type Description: String
### address_record_signatures


Type Description: Array of MultiSignatureGridResponse
### address_record_internals


Type Description: Array of MultiInternalAddressesGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : ["string", "null"],
       "address_hpid" : ["string", "null"],
       "matching_type" : ["string", "null"],
       "source_name" : ["string", "null"],
       "row_key" : ["string", "null"],
       "row_key_subfix" : ["string", "null"],
       "uprn" : ["string", "null"],
       "usrn" : ["string", "null"],
       "organisation" : ["string", "null"],
       "sub_building_start_number" : ["string", "null"],
       "sub_building_end_number" : ["string", "null"],
       "sub_building" : ["string", "null"],
       "building_start_number" : ["string", "null"],
       "building_end_number" : ["string", "null"],
       "building" : ["string", "null"],
       "address" : ["string", "null"],
       "street" : ["string", "null"],
       "postcode" : ["string", "null"],
       "internals" : ["string", "null"],
       "floors" : ["string", "null"],
       "area_sq_mt" : ["string", "null"],
       "address_date" : ["string", "null"],
       "address_end_date" : ["string", "null"],
       "address_string_type" : ["string", "null"],
       "object_type" : ["string", "null"],
       "classification_code" : ["string", "null"],
       "classification_description" : ["string", "null"],
       "postal_addressable" : ["string", "null"],
       "address_record_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "address_record_internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)

