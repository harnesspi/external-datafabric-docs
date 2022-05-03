# VOAResponse
## Properties
- uarn (String)

   
- description (String)

   
- scat_code (String)

   
- address_date (String)

   
- source_name (String)

   
- firms_name (String)

   
- number_or_name (String)

   
- sub_street_level3 (String)

   
- sub_street_level2 (String)

   
- sub_street_level1 (String)

   
- street (String)

   
- town (String)

   
- postal_district (String)

   
- county (String)

   
- postcode (String)

   
- assessments (Array of [VOAAssessmentsDataGridResponse](VOAAssessmentsDataGridResponse.md))

   
- list_entry_data_items (Array of [VOAListEntryDataItemsDataGridResponse](VOAListEntryDataItemsDataGridResponse.md))

   
- list_entry_data_items_historic (Array of [VOAListEntryDataItemsHistoricDataGridResponse](VOAListEntryDataItemsHistoricDataGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

