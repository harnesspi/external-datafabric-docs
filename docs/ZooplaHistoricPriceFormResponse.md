# ZooplaHistoricPriceFormResponse
## Description

## Properties
### property_id


Type Description: String
### address


Type Description: String
### locality


Type Description: String
### postcode


Type Description: String
### region


Type Description: String
### detail_url


Type Description: String
### bedrooms


Type Description: String
### bathrooms


Type Description: String
### reception_rooms


Type Description: String
### property_type


Type Description: String
### features


Type Description: String
### last_sale_date


Type Description: String
### last_sale_price


Type Description: String
### import_date


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
       "property_id" : ["string", "null"],
       "address" : ["string", "null"],
       "locality" : ["string", "null"],
       "postcode" : ["string", "null"],
       "region" : ["string", "null"],
       "detail_url" : ["string", "null"],
       "bedrooms" : ["string", "null"],
       "bathrooms" : ["string", "null"],
       "reception_rooms" : ["string", "null"],
       "property_type" : ["string", "null"],
       "features" : ["string", "null"],
       "last_sale_date" : ["string", "null"],
       "last_sale_price" : ["string", "null"],
       "import_date" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

