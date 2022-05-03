# CouncilTaxBandResponse
## Properties
- id (String)

   
- address (String)

   
- property_url (String)

   
- council_tax_band (String)

   
- deleted (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "id" : ["string", "null"],
       "address" : ["string", "null"],
       "property_url" : ["string", "null"],
       "council_tax_band" : ["string", "null"],
       "deleted" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

