# ICIJIntermediaryEntitiesDataGridResponse
## Properties
- intermediary_id (String)

   
- entity_id ([ValueLink](ValueLink.md) for [object](object.md))

   
- intermediary_type (String)

   
- status (String)

   
- start_date (String)

   
- end_date (String)

   
- icij_source (String)

   
- name (String)

   
- countries (String)

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "intermediary_id" : "string",
       "entity_id" : {"$ref" : "/schemas/valuelink"},
       "intermediary_type" : "string",
       "status" : "string",
       "start_date" : "string",
       "end_date" : "string",
       "icij_source" : "string",
       "name" : "string",
       "countries" : "string"
    }
}
```

