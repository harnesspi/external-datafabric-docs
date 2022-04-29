# ICIJEntityRelatedOrganisationsDataGridResponse
## Description

## Properties
### entity_id


Type Description: String
### organisation_hpid


Type Description: String
### related_organisation


Type Description: String
### source_name


Type Description: String
### row_key


Type Description: String
### row_key_subfix


Type Description: String
### registration_number


Type Description: String
### country_registered


Type Description: String
### url_query


Type Description: KeyValueLink for object

## Schema
```json
{
    "type":"object",
    "properties": {
       "entity_id" : "string",
       "organisation_hpid" : "string",
       "related_organisation" : "string",
       "source_name" : "string",
       "row_key" : "string",
       "row_key_subfix" : "string",
       "registration_number" : "string",
       "country_registered" : "string",
       "url_query" : {"$ref" : "/schemas/keyvaluelink"}
    }
}
```

## Related Entities
- [](.md)

