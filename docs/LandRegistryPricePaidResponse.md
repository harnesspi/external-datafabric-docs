# LandRegistryPricePaidResponse
## Description

## Properties
### guid


Type Description: String
### postcode


Type Description: String
### building


Type Description: String
### flat


Type Description: String
### street


Type Description: String
### locality


Type Description: String
### town


Type Description: String
### district


Type Description: String
### county


Type Description: String
### property_type


Type Description: String
### new_build


Type Description: String
### estate_type


Type Description: String
### transaction_date


Type Description: String
### price


Type Description: String
### price_paid_type


Type Description: String
### id


Type Description: String
### title_number


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
       "guid" : ["string", "null"],
       "postcode" : ["string", "null"],
       "building" : ["string", "null"],
       "flat" : ["string", "null"],
       "street" : ["string", "null"],
       "locality" : ["string", "null"],
       "town" : ["string", "null"],
       "district" : ["string", "null"],
       "county" : ["string", "null"],
       "property_type" : ["string", "null"],
       "new_build" : ["string", "null"],
       "estate_type" : ["string", "null"],
       "transaction_date" : ["string", "null"],
       "price" : ["string", "null"],
       "price_paid_type" : ["string", "null"],
       "id" : ["string", "null"],
       "title_number" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

