# OrganisationResponse
## Properties
- organisation_hpid (String)

   
- normalised_organisation (String)

   
- significant_organisation_hpid (String)

   
- significant_organisation (String)

   
- company_number (String)

   
- is_companies_house (String)

   
- is_other_source (String)

   
- exact_name_sources (Array of [OrganisationRecordsDataGridResponse](OrganisationRecordsDataGridResponse.md))

   
- reg_no_related (Array of [RelatedRegNoOrganisationsDataGridResponse](RelatedRegNoOrganisationsDataGridResponse.md))

   
- keys (Array of [OrganisationKeysDataGridResponse](OrganisationKeysDataGridResponse.md))

   
- organisation_titles (Array of [OrganisationLandRegistryTitlesGridResponse](OrganisationLandRegistryTitlesGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "organisation_hpid" : ["string", "null"],
       "normalised_organisation" : ["string", "null"],
       "significant_organisation_hpid" : ["string", "null"],
       "significant_organisation" : ["string", "null"],
       "company_number" : ["string", "null"],
       "is_companies_house" : ["string", "null"],
       "is_other_source" : ["string", "null"],
       "exact_name_sources" : {"type" : "array", "items" : {"$ref" : "/schemas/OrganisationRecordsDataGrid"},
       "reg_no_related" : {"type" : "array", "items" : {"$ref" : "/schemas/RelatedRegNoOrganisationsDataGrid"},
       "keys" : {"type" : "array", "items" : {"$ref" : "/schemas/OrganisationKeysDataGrid"},
       "organisation_titles" : {"type" : "array", "items" : {"$ref" : "/schemas/OrganisationLandRegistryTitlesGrid"}
}
```

