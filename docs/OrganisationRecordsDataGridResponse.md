# OrganisationRecordsDataGridResponse
## Description

## Properties
### source_hpid


Type Description: String
### source_name


Type Description: String
### row_key


Type Description: String
### registration_number


Type Description: String
### country_registered


Type Description: String
### postcode


Type Description: String
### url_query


Type Description: KeyValueLink for object

## Schema
```json
{
    "type":"object",
    "properties": {
       "source_hpid" : "string",
       "source_name" : "string",
       "row_key" : "string",
       "registration_number" : "string",
       "country_registered" : "string",
       "postcode" : "string",
       "url_query" : {"$ref" : "/schemas/keyvaluelink"}
    }
}
```

## Related Entities
- [KeyValueLink](KeyValueLink.md)

