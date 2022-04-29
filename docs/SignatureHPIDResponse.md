# SignatureHPIDResponse
## Description

## Properties
### signature_hpid


Type Description: String
### building


Type Description: String
### building_start_number


Type Description: String
### building_end_number


Type Description: String
### usrn


Type Description: String
### description


Type Description: String
### signature_internals


Type Description: Array of SignatureInternalsGridResponse
### signature_addresses


Type Description: Array of SignatureAddressesGridResponse
### signature_keys


Type Description: Array of SignatureKeysGridResponse
### listings


Type Description: Array of SignatureRelatedListingsGridResponse

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

## Related Entities
- [SignatureInternalsGridResponse](SignatureInternalsGridResponse.md)
- [SignatureAddressesGridResponse](SignatureAddressesGridResponse.md)
- [SignatureKeysGridResponse](SignatureKeysGridResponse.md)
- [SignatureRelatedListingsGridResponse](SignatureRelatedListingsGridResponse.md)

