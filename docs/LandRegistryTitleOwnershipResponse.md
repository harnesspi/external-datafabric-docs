# LandRegistryTitleOwnershipResponse
## Properties
- title_number (String)

   
- tenure (String)

   
- property_address (String)

   
- district (String)

   
- county (String)

   
- region (String)

   
- postcode (String)

   
- multiple_address_indicator (String)

   
- price_paid (String)

   
- date_proprietor_added (String)

   
- additional_proprietor_indicator (String)

   
- land_registry_title_companies (Array of [LandRegistryTitleCompaniesGridResponse](LandRegistryTitleCompaniesGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "title_number" : ["string", "null"],
       "tenure" : ["string", "null"],
       "property_address" : ["string", "null"],
       "district" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "postcode" : ["string", "null"],
       "multiple_address_indicator" : ["string", "null"],
       "price_paid" : ["string", "null"],
       "date_proprietor_added" : ["string", "null"],
       "additional_proprietor_indicator" : ["string", "null"],
       "land_registry_title_companies" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitleCompaniesGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

