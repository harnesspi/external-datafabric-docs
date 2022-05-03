# OrganisationKeyResponse
## Properties
- key_type (String)

   
- key_value (String)

   
- description (String)

   
- month_of_birth (String)

   
- url_query (String)

   
- organisation_records (Array of [KeyOrganisationsDataGridResponse](KeyOrganisationsDataGridResponse.md))

   

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

