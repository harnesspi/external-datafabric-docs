# LandRegistryTitleOwnerResponse
## Description

## Properties
### address


Type Description: String
### postcode


Type Description: String
### companies


Type Description: Array of LandRegistryTitlesOwnerCompaniesGridResponse
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
       "address" : ["string", "null"],
       "postcode" : ["string", "null"],
       "companies" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitlesOwnerCompaniesGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [LandRegistryTitlesOwnerCompaniesGridResponse](LandRegistryTitlesOwnerCompaniesGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

