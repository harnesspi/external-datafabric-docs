# FoodStandardsAgencyResponse
## Properties
- fhrsid (String)

   
- local_authority_business_id (String)

   
- business_name (String)

   
- address_line1 (String)

   
- address_line2 (String)

   
- address_line3 (String)

   
- address_line4 (String)

   
- post_code (String)

   
- business_type (String)

   
- business_type_id (String)

   
- scheme_type (String)

   
- new_rating_pending (String)

   
- local_authority_code (String)

   
- local_authority_name (String)

   
- longitude (String)

   
- latitude (String)

   
- rating_date (String)

   
- rating_key (String)

   
- rating_value (String)

   
- hygiene (String)

   
- structural (String)

   
- confidence_in_management (String)

   
- snapshot_date (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

