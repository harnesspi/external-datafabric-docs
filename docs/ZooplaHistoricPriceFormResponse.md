# ZooplaHistoricPriceFormResponse
## Properties
- property_id (String)

   
- address (String)

   
- locality (String)

   
- postcode (String)

   
- region (String)

   
- detail_url (String)

   
- bedrooms (String)

   
- bathrooms (String)

   
- reception_rooms (String)

   
- property_type (String)

   
- features (String)

   
- last_sale_date (String)

   
- last_sale_price (String)

   
- import_date (String)

   
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

