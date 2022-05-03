# SignatureHPIDResponse
## Properties
- signature_hpid (String)

   
- building (String)

   
- building_start_number (String)

   
- building_end_number (String)

   
- usrn (String)

   
- description (String)

   
- signature_internals (Array of [SignatureInternalsGridResponse](SignatureInternalsGridResponse.md))

   
- signature_addresses (Array of [SignatureAddressesGridResponse](SignatureAddressesGridResponse.md))

   
- signature_keys (Array of [SignatureKeysGridResponse](SignatureKeysGridResponse.md))

   
- listings (Array of [SignatureRelatedListingsGridResponse](SignatureRelatedListingsGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "signature_hpid" : ["string", "null"],
       "building" : ["string", "null"],
       "building_start_number" : ["string", "null"],
       "building_end_number" : ["string", "null"],
       "usrn" : ["string", "null"],
       "description" : ["string", "null"],
       "signature_internals" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureInternalsGrid"},
       "signature_addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureAddressesGrid"},
       "signature_keys" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureKeysGrid"},
       "listings" : {"type" : "array", "items" : {"$ref" : "/schemas/SignatureRelatedListingsGrid"}
}
```

