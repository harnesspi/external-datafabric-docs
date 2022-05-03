# LandRegistryPricePaidResponse
## Properties
- guid (String)

   
- postcode (String)

   
- building (String)

   
- flat (String)

   
- street (String)

   
- locality (String)

   
- town (String)

   
- district (String)

   
- county (String)

   
- property_type (String)

   
- new_build (String)

   
- estate_type (String)

   
- transaction_date (String)

   
- price (String)

   
- price_paid_type (String)

   
- id (String)

   
- title_number (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

