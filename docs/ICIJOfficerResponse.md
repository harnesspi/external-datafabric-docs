# ICIJOfficerResponse
## Description

## Properties
### officer_id


Type Description: String
### name


Type Description: String
### note


Type Description: String
### countries


Type Description: String
### country_codes


Type Description: String
### icij_source


Type Description: String
### addresses


Type Description: Array of ICIJOfficerAddressesDataGridResponse
### entities


Type Description: Array of ICIJOfficerEntitiesDataGridResponse

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

## Related Entities
- [ICIJOfficerAddressesDataGridResponse](ICIJOfficerAddressesDataGridResponse.md)
- [ICIJOfficerEntitiesDataGridResponse](ICIJOfficerEntitiesDataGridResponse.md)

