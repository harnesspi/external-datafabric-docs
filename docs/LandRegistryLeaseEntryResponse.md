# LandRegistryLeaseEntryResponse
## Properties
- title_number (String)

   
- id (String)

   
- entry_number (String)

   
- reg_order (String)

   
- associated_property_id (String)

   
- associated_property_description (String)

   
- uprn (String)

   
- lease_date (String)

   
- term (String)

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "title_number" : ["string", "null"],
       "id" : ["string", "null"],
       "entry_number" : ["string", "null"],
       "reg_order" : ["string", "null"],
       "associated_property_id" : ["string", "null"],
       "associated_property_description" : ["string", "null"],
       "uprn" : ["string", "null"],
       "lease_date" : ["string", "null"],
       "term" : ["string", "null"],
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

