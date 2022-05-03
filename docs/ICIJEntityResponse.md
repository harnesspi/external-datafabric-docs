# ICIJEntityResponse
## Properties
- entity_id (String)

   
- name (String)

   
- original_name (String)

   
- former_name (String)

   
- jurisdiction (String)

   
- jurisdiction_description (String)

   
- company_type (String)

   
- address (String)

   
- registration_number (String)

   
- country_codes (String)

   
- countries (String)

   
- incorporation_date (String)

   
- inactivation_date (String)

   
- struck_off_date (String)

   
- dorm_date (String)

   
- status (String)

   
- internal_id (String)

   
- icij_source (String)

   
- service_provider (String)

   
- note (String)

   
- addresses (Array of [ICIJEntityAddressesDataGridResponse](ICIJEntityAddressesDataGridResponse.md))

   
- officers (Array of [ICIJEntityOfficersDataGridResponse](ICIJEntityOfficersDataGridResponse.md))

   
- intermediaries (Array of [ICIJEntityIntermediariesDataGridResponse](ICIJEntityIntermediariesDataGridResponse.md))

   
- related_organisations (Array of [ICIJEntityRelatedOrganisationsDataGridResponse](ICIJEntityRelatedOrganisationsDataGridResponse.md))

   

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

