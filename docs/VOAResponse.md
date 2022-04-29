# VOAResponse
## Description

## Properties
### uarn


Type Description: String
### description


Type Description: String
### scat_code


Type Description: String
### address_date


Type Description: String
### source_name


Type Description: String
### firms_name


Type Description: String
### number_or_name


Type Description: String
### sub_street_level3


Type Description: String
### sub_street_level2


Type Description: String
### sub_street_level1


Type Description: String
### street


Type Description: String
### town


Type Description: String
### postal_district


Type Description: String
### county


Type Description: String
### postcode


Type Description: String
### assessments


Type Description: Array of VOAAssessmentsDataGridResponse
### list_entry_data_items


Type Description: Array of VOAListEntryDataItemsDataGridResponse
### list_entry_data_items_historic


Type Description: Array of VOAListEntryDataItemsHistoricDataGridResponse
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
       "uarn" : ["string", "null"],
       "description" : ["string", "null"],
       "scat_code" : ["string", "null"],
       "address_date" : ["string", "null"],
       "source_name" : ["string", "null"],
       "firms_name" : ["string", "null"],
       "number_or_name" : ["string", "null"],
       "sub_street_level3" : ["string", "null"],
       "sub_street_level2" : ["string", "null"],
       "sub_street_level1" : ["string", "null"],
       "street" : ["string", "null"],
       "town" : ["string", "null"],
       "postal_district" : ["string", "null"],
       "county" : ["string", "null"],
       "postcode" : ["string", "null"],
       "assessments" : {"type" : "array", "items" : {"$ref" : "/schemas/VOAAssessmentsDataGrid"},
       "list_entry_data_items" : {"type" : "array", "items" : {"$ref" : "/schemas/VOAListEntryDataItemsDataGrid"},
       "list_entry_data_items_historic" : {"type" : "array", "items" : {"$ref" : "/schemas/VOAListEntryDataItemsHistoricDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [VOAAssessmentsDataGridResponse](VOAAssessmentsDataGridResponse.md)
- [VOAListEntryDataItemsDataGridResponse](VOAListEntryDataItemsDataGridResponse.md)
- [VOAListEntryDataItemsHistoricDataGridResponse](VOAListEntryDataItemsHistoricDataGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

