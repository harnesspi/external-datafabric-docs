# StreetRelatedListingsGridResponse
## Properties
- listing_id ([ValueLink](ValueLink.md) for [object](object.md))

   
- display_address (String)

   
- property_type (String)

   
- bedrooms (String)

   
- transaction_type (String)

   
- asking_price (String)

   
- relevancy (String)

   
- last_update (String)

   
- inactive (String)

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "listing_id" : {"$ref" : "/schemas/valuelink"},
       "display_address" : "string",
       "property_type" : "string",
       "bedrooms" : "string",
       "transaction_type" : "string",
       "asking_price" : "string",
       "relevancy" : "string",
       "last_update" : "string",
       "inactive" : "string"
    }
}
```

