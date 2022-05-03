# PersonWithSignificantControlResponse
## Properties
- e_tag (String)

   
- person_hpid (String)

   
- kind (String)

   
- title (String)

   
- name (String)

   
- month_of_birth (String)

   
- nationality (String)

   
- country_of_residence (String)

   
- registration_number (String)

   
- country_registered (String)

   
- legal_authority (String)

   
- place_registered (String)

   
- notified_on (String)

   
- legal_form (String)

   
- link (String)

   
- snapshot_date (String)

   
- premises (String)

   
- address_line1 (String)

   
- address_line2 (String)

   
- locality (String)

   
- postal_code (String)

   
- county (String)

   
- region (String)

   
- country (String)

   
- company_number (String)

   
- company_name (String)

   
- sic_code_sic_text1 (String)

   
- natures_of_control (String)

   
- person_with_significant_control_companies_data_grid (Array of [PersonWithSignificantControlCompaniesDataGridResponse](PersonWithSignificantControlCompaniesDataGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

