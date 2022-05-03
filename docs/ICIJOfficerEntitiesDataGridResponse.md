# ICIJOfficerEntitiesDataGridResponse
## Properties
- entity_id ([ValueLink](ValueLink.md) for [object](object.md))

   
- officer_type (String)

   
- status (String)

   
- start_date (String)

   
- end_date (String)

   
- name (String)

   
- countries (String)

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "entity_id" : {"$ref" : "/schemas/valuelink"},
       "officer_type" : "string",
       "status" : "string",
       "start_date" : "string",
       "end_date" : "string",
       "name" : "string",
       "countries" : "string"
    }
}
```

