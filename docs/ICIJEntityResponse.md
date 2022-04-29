# ICIJEntityResponse
## Description

## Properties
### entity_id


Type Description: String
### name


Type Description: String
### original_name


Type Description: String
### former_name


Type Description: String
### jurisdiction


Type Description: String
### jurisdiction_description


Type Description: String
### company_type


Type Description: String
### address


Type Description: String
### registration_number


Type Description: String
### country_codes


Type Description: String
### countries


Type Description: String
### incorporation_date


Type Description: String
### inactivation_date


Type Description: String
### struck_off_date


Type Description: String
### dorm_date


Type Description: String
### status


Type Description: String
### internal_id


Type Description: String
### icij_source


Type Description: String
### service_provider


Type Description: String
### note


Type Description: String
### addresses


Type Description: Array of ICIJEntityAddressesDataGridResponse
### officers


Type Description: Array of ICIJEntityOfficersDataGridResponse
### intermediaries


Type Description: Array of ICIJEntityIntermediariesDataGridResponse
### related_organisations


Type Description: Array of ICIJEntityRelatedOrganisationsDataGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "entity_id" : ["string", "null"],
       "name" : ["string", "null"],
       "original_name" : ["string", "null"],
       "former_name" : ["string", "null"],
       "jurisdiction" : ["string", "null"],
       "jurisdiction_description" : ["string", "null"],
       "company_type" : ["string", "null"],
       "address" : ["string", "null"],
       "registration_number" : ["string", "null"],
       "country_codes" : ["string", "null"],
       "countries" : ["string", "null"],
       "incorporation_date" : ["string", "null"],
       "inactivation_date" : ["string", "null"],
       "struck_off_date" : ["string", "null"],
       "dorm_date" : ["string", "null"],
       "status" : ["string", "null"],
       "internal_id" : ["string", "null"],
       "icij_source" : ["string", "null"],
       "service_provider" : ["string", "null"],
       "note" : ["string", "null"],
       "addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJEntityAddressesDataGrid"},
       "officers" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJEntityOfficersDataGrid"},
       "intermediaries" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJEntityIntermediariesDataGrid"},
       "related_organisations" : {"type" : "array", "items" : {"$ref" : "/schemas/ICIJEntityRelatedOrganisationsDataGrid"}
}
```

## Related Entities
- [ICIJEntityAddressesDataGridResponse](ICIJEntityAddressesDataGridResponse.md)
- [ICIJEntityOfficersDataGridResponse](ICIJEntityOfficersDataGridResponse.md)
- [ICIJEntityIntermediariesDataGridResponse](ICIJEntityIntermediariesDataGridResponse.md)
- [ICIJEntityRelatedOrganisationsDataGridResponse](ICIJEntityRelatedOrganisationsDataGridResponse.md)

