# StreetResponse
## Description

## Properties
### usrn


Type Description: String
### street


Type Description: String
### street_signatures


Type Description: Array of StreetSignaturesGridResponse
### street_no_signature_addresses_data_grid


Type Description: Array of StreetNoSignatureAddressesDataGridResponse
### listings


Type Description: Array of StreetRelatedListingsGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "usrn" : ["string", "null"],
       "street" : ["string", "null"],
       "street_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/StreetSignaturesGrid"},
       "street_no_signature_addresses_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/StreetNoSignatureAddressesDataGrid"},
       "listings" : {"type" : "array", "items" : {"$ref" : "/schemas/StreetRelatedListingsGrid"}
}
```

## Related Entities
- [StreetSignaturesGridResponse](StreetSignaturesGridResponse.md)
- [StreetNoSignatureAddressesDataGridResponse](StreetNoSignatureAddressesDataGridResponse.md)
- [StreetRelatedListingsGridResponse](StreetRelatedListingsGridResponse.md)

