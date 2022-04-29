# LandRegistryLeaseEntryResponse
## Description

## Properties
### title_number


Type Description: String
### id


Type Description: String
### entry_number


Type Description: String
### reg_order


Type Description: String
### associated_property_id


Type Description: String
### associated_property_description


Type Description: String
### uprn


Type Description: String
### lease_date


Type Description: String
### term


Type Description: String
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

## Related Entities
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

