# CompanyAppointmentResponse
## Properties
- person_number (String)

   
- title (String)

   
- forenames (String)

   
- surname (String)

   
- honours (String)

   
- care_of (String)

   
- po_box (String)

   
- address_line1 (String)

   
- address_line2 (String)

   
- post_town (String)

   
- county (String)

   
- country (String)

   
- person_postcode (String)

   
- partial_date_of_birth (String)

   
- occupation (String)

   
- nationality (String)

   
- usual_residential_country (String)

   
- appointment_date (String)

   
- app_date_origin (String)

   
- app_date_origin_description (String)

   
- appointment_type (String)

   
- appointment_type_description (String)

   
- file_name (String)

   
- line_number (String)

   
- old_person_postcode (String)

   
- old_person_number (String)

   
- old_appointment_type (String)

   
- correction_indicator (String)

   
- corporate_indicator (String)

   
- resignation_date (String)

   
- res_date_origin (String)

   
- res_date_origin_description (String)

   
- company_number (String)

   
- company_name (String)

   
- appointed_person_other_companies_data_grid (Array of [AppointedPersonOtherCompaniesDataGridResponse](AppointedPersonOtherCompaniesDataGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

