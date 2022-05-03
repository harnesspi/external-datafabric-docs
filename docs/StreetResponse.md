# StreetResponse
## Properties
- usrn (String)

   
- street (String)

   
- street_signatures (Array of [StreetSignaturesGridResponse](StreetSignaturesGridResponse.md))

   
- street_no_signature_addresses_data_grid (Array of [StreetNoSignatureAddressesDataGridResponse](StreetNoSignatureAddressesDataGridResponse.md))

   
- listings (Array of [StreetRelatedListingsGridResponse](StreetRelatedListingsGridResponse.md))

   

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

