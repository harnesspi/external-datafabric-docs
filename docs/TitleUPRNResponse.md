# TitleUPRNResponse
## Description

## Properties
### signature_hpid


Type Description: String
### address_hpid


Type Description: String
### row_key


Type Description: String
### tenancy


Type Description: String
### id


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
### floors


Type Description: String
### address_start_date


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
### signatures


Type Description: Array of MultiSignatureGridResponse
### internals


Type Description: Array of MultiInternalAddressesGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : ["string", "null"],
       "address_hpid" : ["string", "null"],
       "row_key" : ["string", "null"],
       "tenancy" : ["string", "null"],
       "id" : ["string", "null"],
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
       "floors" : ["string", "null"],
       "address_start_date" : ["string", "null"],
       "address_end_date" : ["string", "null"],
       "address_string_type" : ["string", "null"],
       "object_type" : ["string", "null"],
       "classification_code" : ["string", "null"],
       "classification_description" : ["string", "null"],
       "postal_addressable" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)

