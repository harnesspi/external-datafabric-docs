# ICIJIntermediaryResponse
## Properties
- intermediary_id (String)

   
- name (String)

   
- status (String)

   
- address (String)

   
- countries (String)

   
- country_codes (String)

   
- icij_source (String)

   
- note (String)

   
- addresses (Array of [ICIJIntermediaryAddressesDataGridResponse](ICIJIntermediaryAddressesDataGridResponse.md))

   
- entities (Array of [ICIJIntermediaryEntitiesDataGridResponse](ICIJIntermediaryEntitiesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "intermediary_id" : ["string", "null"],
       "name" : ["string", "null"],
       "status" : ["string", "null"],
       "address" : ["string", "null"],
       "countries" : ["string", "null"],
       "country_codes" : ["string", "null"],
       "icij_source" : ["string", "null"],
       "note" : ["string", "null"],
       "addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJIntermediaryAddressesDataGrid"},
       "entities" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJIntermediaryEntitiesDataGrid"}
}
```

