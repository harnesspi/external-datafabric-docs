# PersonWithSignificantControlResponse
## Description

## Properties
### e_tag


Type Description: String
### person_hpid


Type Description: String
### kind


Type Description: String
### title


Type Description: String
### name


Type Description: String
### month_of_birth


Type Description: String
### nationality


Type Description: String
### country_of_residence


Type Description: String
### registration_number


Type Description: String
### country_registered


Type Description: String
### legal_authority


Type Description: String
### place_registered


Type Description: String
### notified_on


Type Description: String
### legal_form


Type Description: String
### link


Type Description: String
### snapshot_date


Type Description: String
### premises


Type Description: String
### address_line1


Type Description: String
### address_line2


Type Description: String
### locality


Type Description: String
### postal_code


Type Description: String
### county


Type Description: String
### region


Type Description: String
### country


Type Description: String
### company_number


Type Description: String
### company_name


Type Description: String
### sic_code_sic_text1


Type Description: String
### natures_of_control


Type Description: String
### person_with_significant_control_companies_data_grid


Type Description: Array of PersonWithSignificantControlCompaniesDataGridResponse
### signatures


Type Description: Array of MultiSignatureGridResponse
### internals


Type Description: Array of MultiInternalAddressesGridResponse
### no_signatures


Type Description: Array of NoSignatureAddressesDataGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "e_tag" : ["string", "null"],
       "person_hpid" : ["string", "null"],
       "kind" : ["string", "null"],
       "title" : ["string", "null"],
       "name" : ["string", "null"],
       "month_of_birth" : ["string", "null"],
       "nationality" : ["string", "null"],
       "country_of_residence" : ["string", "null"],
       "registration_number" : ["string", "null"],
       "country_registered" : ["string", "null"],
       "legal_authority" : ["string", "null"],
       "place_registered" : ["string", "null"],
       "notified_on" : ["string", "null"],
       "legal_form" : ["string", "null"],
       "link" : ["string", "null"],
       "snapshot_date" : ["string", "null"],
       "premises" : ["string", "null"],
       "address_line1" : ["string", "null"],
       "address_line2" : ["string", "null"],
       "locality" : ["string", "null"],
       "postal_code" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "country" : ["string", "null"],
       "company_number" : ["string", "null"],
       "company_name" : ["string", "null"],
       "sic_code_sic_text1" : ["string", "null"],
       "natures_of_control" : ["string", "null"],
       "person_with_significant_control_companies_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/PersonWithSignificantControlCompaniesDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [PersonWithSignificantControlCompaniesDataGridResponse](PersonWithSignificantControlCompaniesDataGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

