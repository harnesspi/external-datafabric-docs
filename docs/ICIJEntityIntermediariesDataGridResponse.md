# ICIJEntityIntermediariesDataGridResponse
## Properties
- intermediary_id ([ValueLink](ValueLink.md) for [object](object.md))

   
- intermediary_type (String)

   
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
       "intermediary_id" : {"$ref" : "/schemas/valuelink"},
       "intermediary_type" : "string",
       "status" : "string",
       "start_date" : "string",
       "end_date" : "string",
       "name" : "string",
       "countries" : "string"
    }
}
```

