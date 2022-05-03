# RightmoveHistoricPriceResponse
## Properties
- property_id (String)

   
- address (String)

   
- postcode (String)

   
- has_images (String)

   
- detail_url (String)

   
- property_type (String)

   
- bedrooms (String)

   
- has_floor_plan (String)

   
- import_date (String)

   
- import_guid (String)

   
- transactions (Array of [RightmoveHistoricPriceTransactionsGridResponse](RightmoveHistoricPriceTransactionsGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

