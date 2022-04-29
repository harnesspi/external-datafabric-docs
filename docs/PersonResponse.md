# PersonResponse
## Description

## Properties
### person_hpid


Type Description: String
### name


Type Description: String
### month_of_birth


Type Description: String
### person_records_data_grid


Type Description: Array of PersonRecordsDataGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "person_hpid" : ["string", "null"],
       "name" : ["string", "null"],
       "month_of_birth" : ["string", "null"],
       "person_records_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/PersonRecordsDataGrid"}
}
```

## Related Entities
- [PersonRecordsDataGridResponse](PersonRecordsDataGridResponse.md)

