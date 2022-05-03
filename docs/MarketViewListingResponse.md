# MarketViewListingResponse
## Properties
- listing_id (String)

   
- summary (String)

   
- description (String)

   
- asking_price (String)

   
- display_address (String)

   
- postcode (String)

   
- import_date (String)

   
- update_date (String)

   
- inactive_date (String)

   
- listing_url (String)

   
- property_type (String)

   
- bedrooms (String)

   
- bathrooms (String)

   
- reception_rooms (String)

   
- size_sq_feet (String)

   
- category (String)

   
- transaction_type (String)

   
- condition (String)

   
- tenure (String)

   
- retirement_home (String)

   
- shared_ownership (String)

   
- display_size (String)

   
- price_paid_guid (String)

   
- price_paid_address_string (String)

   
- latitude (String)

   
- longitude (String)

   
- x (String)

   
- y (String)

   
- agent_brand (String)

   
- agent_branch (String)

   
- updated_on (String)

   
- update_reason (String)

   
- transactions (Array of [MarketViewListingTransactionsGridResponse](MarketViewListingTransactionsGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

