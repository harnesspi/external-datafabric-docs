# OrganisationResponse
## Description

## Properties
### organisation_hpid


Type Description: String
### normalised_organisation


Type Description: String
### significant_organisation_hpid


Type Description: String
### significant_organisation


Type Description: String
### company_number


Type Description: String
### is_companies_house


Type Description: String
### is_other_source


Type Description: String
### exact_name_sources


Type Description: Array of OrganisationRecordsDataGridResponse
### reg_no_related


Type Description: Array of RelatedRegNoOrganisationsDataGridResponse
### keys


Type Description: Array of OrganisationKeysDataGridResponse
### organisation_titles


Type Description: Array of OrganisationLandRegistryTitlesGridResponse

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

## Related Entities
- [OrganisationRecordsDataGridResponse](OrganisationRecordsDataGridResponse.md)
- [RelatedRegNoOrganisationsDataGridResponse](RelatedRegNoOrganisationsDataGridResponse.md)
- [OrganisationKeysDataGridResponse](OrganisationKeysDataGridResponse.md)
- [OrganisationLandRegistryTitlesGridResponse](OrganisationLandRegistryTitlesGridResponse.md)

