# LandRegistryTitleOwnerTitlesResponse
## Description

## Properties
### company_id


Type Description: String
### company_type_id


Type Description: String
### name


Type Description: String
### company_type


Type Description: String
### registration_no


Type Description: String
### country


Type Description: String
### companies


Type Description: Array of LandRegistryTitlesOwnedByCompanyGridResponse

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

## Related Entities
- [LandRegistryTitlesOwnedByCompanyGridResponse](LandRegistryTitlesOwnedByCompanyGridResponse.md)

