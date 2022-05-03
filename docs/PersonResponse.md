# PersonResponse
## Properties
- person_hpid (String)

   
- name (String)

   
- month_of_birth (String)

   
- person_records_data_grid (Array of [PersonRecordsDataGridResponse](PersonRecordsDataGridResponse.md))

   

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

