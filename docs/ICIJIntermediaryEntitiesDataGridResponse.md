# ICIJIntermediaryEntitiesDataGridResponse
## Description

## Properties
### intermediary_id


Type Description: String
### entity_id


Type Description: ValueLink for object
### intermediary_type


Type Description: String
### status


Type Description: String
### start_date


Type Description: String
### end_date


Type Description: String
### icij_source


Type Description: String
### name


Type Description: String
### countries


Type Description: String

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

## Related Entities
- [ValueLink](ValueLink.md)

