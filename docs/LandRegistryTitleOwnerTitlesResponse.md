# LandRegistryTitleOwnerTitlesResponse
## Properties
- company_id (String)

   
- company_type_id (String)

   
- name (String)

   
- company_type (String)

   
- registration_no (String)

   
- country (String)

   
- companies (Array of [LandRegistryTitlesOwnedByCompanyGridResponse](LandRegistryTitlesOwnedByCompanyGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "company_id" : ["string", "null"],
       "company_type_id" : ["string", "null"],
       "name" : ["string", "null"],
       "company_type" : ["string", "null"],
       "registration_no" : ["string", "null"],
       "country" : ["string", "null"],
       "companies" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryTitlesOwnedByCompanyGrid"}
}
```

