# LandRegistryRestrictiveCovenantResponse
## Description

## Properties
### title_number


Type Description: String
### lease_id


Type Description: String
### id


Type Description: String
### tenure


Type Description: String
### description


Type Description: String
### county


Type Description: String
### region


Type Description: String
### land_registry_restrictive_covenant_address_data_grid


Type Description: Array of LandRegistryRestrictiveCovenantAddressDataGridResponse
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
       "lease_id" : ["string", "null"],
       "id" : ["string", "null"],
       "tenure" : ["string", "null"],
       "description" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "land_registry_restrictive_covenant_address_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryRestrictiveCovenantAddressDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [LandRegistryRestrictiveCovenantAddressDataGridResponse](LandRegistryRestrictiveCovenantAddressDataGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

