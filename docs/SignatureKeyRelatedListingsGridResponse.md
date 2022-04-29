# SignatureKeyRelatedListingsGridResponse
## Description

## Properties
### listing_id


Type Description: ValueLink for object
### display_address


Type Description: String
### property_type


Type Description: String
### bedrooms


Type Description: String
### transaction_type


Type Description: String
### asking_price


Type Description: String
### relevancy


Type Description: String
### last_update


Type Description: String
### inactive


Type Description: String

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

## Related Entities
- [ValueLink](ValueLink.md)

