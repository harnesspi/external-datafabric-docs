# CompanyAppointmentResponse
## Description

## Properties
### person_number


Type Description: String
### title


Type Description: String
### forenames


Type Description: String
### surname


Type Description: String
### honours


Type Description: String
### care_of


Type Description: String
### po_box


Type Description: String
### address_line1


Type Description: String
### address_line2


Type Description: String
### post_town


Type Description: String
### county


Type Description: String
### country


Type Description: String
### person_postcode


Type Description: String
### partial_date_of_birth


Type Description: String
### occupation


Type Description: String
### nationality


Type Description: String
### usual_residential_country


Type Description: String
### appointment_date


Type Description: String
### app_date_origin


Type Description: String
### app_date_origin_description


Type Description: String
### appointment_type


Type Description: String
### appointment_type_description


Type Description: String
### file_name


Type Description: String
### line_number


Type Description: String
### old_person_postcode


Type Description: String
### old_person_number


Type Description: String
### old_appointment_type


Type Description: String
### correction_indicator


Type Description: String
### corporate_indicator


Type Description: String
### resignation_date


Type Description: String
### res_date_origin


Type Description: String
### res_date_origin_description


Type Description: String
### company_number


Type Description: String
### company_name


Type Description: String
### appointed_person_other_companies_data_grid


Type Description: Array of AppointedPersonOtherCompaniesDataGridResponse
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
       "person_number" : ["string", "null"],
       "title" : ["string", "null"],
       "forenames" : ["string", "null"],
       "surname" : ["string", "null"],
       "honours" : ["string", "null"],
       "care_of" : ["string", "null"],
       "po_box" : ["string", "null"],
       "address_line1" : ["string", "null"],
       "address_line2" : ["string", "null"],
       "post_town" : ["string", "null"],
       "county" : ["string", "null"],
       "country" : ["string", "null"],
       "person_postcode" : ["string", "null"],
       "partial_date_of_birth" : ["string", "null"],
       "occupation" : ["string", "null"],
       "nationality" : ["string", "null"],
       "usual_residential_country" : ["string", "null"],
       "appointment_date" : ["string", "null"],
       "app_date_origin" : ["string", "null"],
       "app_date_origin_description" : ["string", "null"],
       "appointment_type" : ["string", "null"],
       "appointment_type_description" : ["string", "null"],
       "file_name" : ["string", "null"],
       "line_number" : ["string", "null"],
       "old_person_postcode" : ["string", "null"],
       "old_person_number" : ["string", "null"],
       "old_appointment_type" : ["string", "null"],
       "correction_indicator" : ["string", "null"],
       "corporate_indicator" : ["string", "null"],
       "resignation_date" : ["string", "null"],
       "res_date_origin" : ["string", "null"],
       "res_date_origin_description" : ["string", "null"],
       "company_number" : ["string", "null"],
       "company_name" : ["string", "null"],
       "appointed_person_other_companies_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/AppointedPersonOtherCompaniesDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [AppointedPersonOtherCompaniesDataGridResponse](AppointedPersonOtherCompaniesDataGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

