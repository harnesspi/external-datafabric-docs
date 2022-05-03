# OrganisationRecordsDataGridResponse
## Properties
- source_hpid (String)

   
- source_name (String)

   
- row_key (String)

   
- registration_number (String)

   
- country_registered (String)

   
- postcode (String)

   
- url_query ([KeyValueLink](KeyValueLink.md) for [object](object.md))

   

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

