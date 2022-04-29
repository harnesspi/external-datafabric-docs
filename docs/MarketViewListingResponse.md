# MarketViewListingResponse
## Description

## Properties
### listing_id


Type Description: String
### summary


Type Description: String
### description


Type Description: String
### asking_price


Type Description: String
### display_address


Type Description: String
### postcode


Type Description: String
### import_date


Type Description: String
### update_date


Type Description: String
### inactive_date


Type Description: String
### listing_url


Type Description: String
### property_type


Type Description: String
### bedrooms


Type Description: String
### bathrooms


Type Description: String
### reception_rooms


Type Description: String
### size_sq_feet


Type Description: String
### category


Type Description: String
### transaction_type


Type Description: String
### condition


Type Description: String
### tenure


Type Description: String
### retirement_home


Type Description: String
### shared_ownership


Type Description: String
### display_size


Type Description: String
### price_paid_guid


Type Description: String
### price_paid_address_string


Type Description: String
### latitude


Type Description: String
### longitude


Type Description: String
### x


Type Description: String
### y


Type Description: String
### agent_brand


Type Description: String
### agent_branch


Type Description: String
### updated_on


Type Description: String
### update_reason


Type Description: String
### transactions


Type Description: Array of MarketViewListingTransactionsGridResponse
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
       "listing_id" : ["string", "null"],
       "summary" : ["string", "null"],
       "description" : ["string", "null"],
       "asking_price" : ["string", "null"],
       "display_address" : ["string", "null"],
       "postcode" : ["string", "null"],
       "import_date" : ["string", "null"],
       "update_date" : ["string", "null"],
       "inactive_date" : ["string", "null"],
       "listing_url" : ["string", "null"],
       "property_type" : ["string", "null"],
       "bedrooms" : ["string", "null"],
       "bathrooms" : ["string", "null"],
       "reception_rooms" : ["string", "null"],
       "size_sq_feet" : ["string", "null"],
       "category" : ["string", "null"],
       "transaction_type" : ["string", "null"],
       "condition" : ["string", "null"],
       "tenure" : ["string", "null"],
       "retirement_home" : ["string", "null"],
       "shared_ownership" : ["string", "null"],
       "display_size" : ["string", "null"],
       "price_paid_guid" : ["string", "null"],
       "price_paid_address_string" : ["string", "null"],
       "latitude" : ["string", "null"],
       "longitude" : ["string", "null"],
       "x" : ["string", "null"],
       "y" : ["string", "null"],
       "agent_brand" : ["string", "null"],
       "agent_branch" : ["string", "null"],
       "updated_on" : ["string", "null"],
       "update_reason" : ["string", "null"],
       "transactions" : {"type" : "array", "items" : {"$ref" : "/schemas/MarketViewListingTransactionsGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [MarketViewListingTransactionsGridResponse](MarketViewListingTransactionsGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

