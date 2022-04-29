# RightmoveHistoricPriceResponse
## Description

## Properties
### property_id


Type Description: String
### address


Type Description: String
### postcode


Type Description: String
### has_images


Type Description: String
### detail_url


Type Description: String
### property_type


Type Description: String
### bedrooms


Type Description: String
### has_floor_plan


Type Description: String
### import_date


Type Description: String
### import_guid


Type Description: String
### transactions


Type Description: Array of RightmoveHistoricPriceTransactionsGridResponse
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
       "postcode" : ["string", "null"],
       "has_images" : ["string", "null"],
       "detail_url" : ["string", "null"],
       "property_type" : ["string", "null"],
       "bedrooms" : ["string", "null"],
       "has_floor_plan" : ["string", "null"],
       "import_date" : ["string", "null"],
       "import_guid" : ["string", "null"],
       "transactions" : {"type" : "array", "items" : {"$ref" : "/schemas/RightmoveHistoricPriceTransactionsGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [RightmoveHistoricPriceTransactionsGridResponse](RightmoveHistoricPriceTransactionsGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

