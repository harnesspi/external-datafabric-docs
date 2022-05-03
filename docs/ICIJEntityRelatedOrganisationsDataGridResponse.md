# ICIJEntityRelatedOrganisationsDataGridResponse
## Properties
- entity_id (String)

   
- organisation_hpid (String)

   
- related_organisation (String)

   
- source_name (String)

   
- row_key (String)

   
- row_key_subfix (String)

   
- registration_number (String)

   
- country_registered (String)

   
- url_query ([KeyValueLink](KeyValueLink.md) for [object](object.md))

   

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

