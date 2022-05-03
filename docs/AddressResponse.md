# AddressResponse
## Properties
- signature_hpid (String)

   
- address_hpid (String)

   
- matching_type (String)

   
- source_name (String)

   
- row_key (String)

   
- row_key_subfix (String)

   
- uprn (String)

   
- usrn (String)

   
- organisation (String)

   
- sub_building_start_number (String)

   
- sub_building_end_number (String)

   
- sub_building (String)

   
- building_start_number (String)

   
- building_end_number (String)

   
- building (String)

   
- address (String)

   
- street (String)

   
- postcode (String)

   
- internals (String)

   
- floors (String)

   
- area_sq_mt (String)

   
- address_date (String)

   
- address_end_date (String)

   
- address_string_type (String)

   
- object_type (String)

   
- classification_code (String)

   
- classification_description (String)

   
- postal_addressable (String)

   
- address_record_signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- address_record_internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   

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

