# ICIJOfficerResponse
## Properties
- officer_id (String)

   
- name (String)

   
- note (String)

   
- countries (String)

   
- country_codes (String)

   
- icij_source (String)

   
- addresses (Array of [ICIJOfficerAddressesDataGridResponse](ICIJOfficerAddressesDataGridResponse.md))

   
- entities (Array of [ICIJOfficerEntitiesDataGridResponse](ICIJOfficerEntitiesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "officer_id" : ["string", "null"],
       "name" : ["string", "null"],
       "note" : ["string", "null"],
       "countries" : ["string", "null"],
       "country_codes" : ["string", "null"],
       "icij_source" : ["string", "null"],
       "addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJOfficerAddressesDataGrid"},
       "entities" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJOfficerEntitiesDataGrid"}
}
```

