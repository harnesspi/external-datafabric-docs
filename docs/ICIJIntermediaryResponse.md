# ICIJIntermediaryResponse
## Description

## Properties
### intermediary_id


Type Description: String
### name


Type Description: String
### status


Type Description: String
### address


Type Description: String
### countries


Type Description: String
### country_codes


Type Description: String
### icij_source


Type Description: String
### note


Type Description: String
### addresses


Type Description: Array of ICIJIntermediaryAddressesDataGridResponse
### entities


Type Description: Array of ICIJIntermediaryEntitiesDataGridResponse

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

## Related Entities
- [ICIJIntermediaryAddressesDataGridResponse](ICIJIntermediaryAddressesDataGridResponse.md)
- [ICIJIntermediaryEntitiesDataGridResponse](ICIJIntermediaryEntitiesDataGridResponse.md)

