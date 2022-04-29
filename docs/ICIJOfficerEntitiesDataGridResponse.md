# ICIJOfficerEntitiesDataGridResponse
## Description

## Properties
### entity_id


Type Description: ValueLink for object
### officer_type


Type Description: String
### status


Type Description: String
### start_date


Type Description: String
### end_date


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

## Related Entities
- [ValueLink](ValueLink.md)

