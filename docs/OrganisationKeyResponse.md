# OrganisationKeyResponse
## Description

## Properties
### key_type


Type Description: String
### key_value


Type Description: String
### description


Type Description: String
### month_of_birth


Type Description: String
### url_query


Type Description: String
### organisation_records


Type Description: Array of KeyOrganisationsDataGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "key_type" : ["string", "null"],
       "key_value" : ["string", "null"],
       "description" : ["string", "null"],
       "month_of_birth" : ["string", "null"],
       "url_query" : ["string", "null"],
       "organisation_records" : {"type" : "array", "items" : {"$ref" : "/schemas/KeyOrganisationsDataGrid"}
}
```

## Related Entities
- [KeyOrganisationsDataGridResponse](KeyOrganisationsDataGridResponse.md)

