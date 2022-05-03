# LandRegistryTitleOwnerResponse
## Properties
- address (String)

   
- postcode (String)

   
- companies (Array of [LandRegistryTitlesOwnerCompaniesGridResponse](LandRegistryTitlesOwnerCompaniesGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "address" : ["string", "null"],
       "postcode" : ["string", "null"],
       "companies" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitlesOwnerCompaniesGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

