# CompanyResponse
## Description

## Properties
### company_number


Type Description: String
### company_name


Type Description: String
### reg_address_care_of


Type Description: String
### reg_address_po_box


Type Description: String
### reg_address_address_line1


Type Description: String
### reg_address_address_line2


Type Description: String
### reg_address_post_town


Type Description: String
### reg_address_county


Type Description: String
### reg_address_country


Type Description: String
### reg_address_post_code


Type Description: String
### snapshot_date


Type Description: String
### hpids


Type Description: String
### company_category


Type Description: String
### company_status


Type Description: String
### country_of_origin


Type Description: String
### dissolution_date


Type Description: String
### incorporation_date


Type Description: String
### accounts_account_ref_day


Type Description: String
### accounts_account_ref_month


Type Description: String
### accounts_next_due_date


Type Description: String
### accounts_last_made_up_date


Type Description: String
### accounts_account_category


Type Description: String
### returns_next_due_date


Type Description: String
### returns_last_made_up_date


Type Description: String
### sic_code_sic_text1


Type Description: String
### sic_code_sic_text2


Type Description: String
### sic_code_sic_text3


Type Description: String
### sic_code_sic_text4


Type Description: String
### limited_partnerships_num_gen_partners


Type Description: String
### limited_partnerships_num_lim_partners


Type Description: String
### conf_stmt_next_due_date


Type Description: String
### conf_stmt_last_made_up_date


Type Description: String
### mortgages_num_mort_charges


Type Description: String
### mortgages_num_mort_outstanding


Type Description: String
### mortgages_num_mort_part_satisfied


Type Description: String
### mortgages_num_mort_satisfied


Type Description: String
### historic_addresses


Type Description: Array of CompaniesHistoricAddressesDataGridResponse
### historic_names


Type Description: Array of CompaniesHistoricNamesDataGridResponse
### company_appointments_data_grid


Type Description: Array of CompanyAppointmentsDataGridResponse
### company_persons_with_significant_control_data_grid


Type Description: Array of CompanyPersonsWithSignificantControlDataGridResponse
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
       "company_number" : ["string", "null"],
       "company_name" : ["string", "null"],
       "reg_address_care_of" : ["string", "null"],
       "reg_address_po_box" : ["string", "null"],
       "reg_address_address_line1" : ["string", "null"],
       "reg_address_address_line2" : ["string", "null"],
       "reg_address_post_town" : ["string", "null"],
       "reg_address_county" : ["string", "null"],
       "reg_address_country" : ["string", "null"],
       "reg_address_post_code" : ["string", "null"],
       "snapshot_date" : ["string", "null"],
       "hpids" : ["string", "null"],
       "company_category" : ["string", "null"],
       "company_status" : ["string", "null"],
       "country_of_origin" : ["string", "null"],
       "dissolution_date" : ["string", "null"],
       "incorporation_date" : ["string", "null"],
       "accounts_account_ref_day" : ["string", "null"],
       "accounts_account_ref_month" : ["string", "null"],
       "accounts_next_due_date" : ["string", "null"],
       "accounts_last_made_up_date" : ["string", "null"],
       "accounts_account_category" : ["string", "null"],
       "returns_next_due_date" : ["string", "null"],
       "returns_last_made_up_date" : ["string", "null"],
       "sic_code_sic_text1" : ["string", "null"],
       "sic_code_sic_text2" : ["string", "null"],
       "sic_code_sic_text3" : ["string", "null"],
       "sic_code_sic_text4" : ["string", "null"],
       "limited_partnerships_num_gen_partners" : ["string", "null"],
       "limited_partnerships_num_lim_partners" : ["string", "null"],
       "conf_stmt_next_due_date" : ["string", "null"],
       "conf_stmt_last_made_up_date" : ["string", "null"],
       "mortgages_num_mort_charges" : ["string", "null"],
       "mortgages_num_mort_outstanding" : ["string", "null"],
       "mortgages_num_mort_part_satisfied" : ["string", "null"],
       "mortgages_num_mort_satisfied" : ["string", "null"],
       "historic_addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/CompaniesHistoricAddressesDataGrid"},
       "historic_names" : {"type" : "array", "items" : {"$ref" : "/schemas/CompaniesHistoricNamesDataGrid"},
       "company_appointments_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/CompanyAppointmentsDataGrid"},
       "company_persons_with_significant_control_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/CompanyPersonsWithSignificantControlDataGrid"},
       "signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiSignatureGrid"},
       "internals" : {"type" : "array", "items" : {"$ref" : "/schemas/MultiInternalAddressesGrid"},
       "no_signatures" : {"type" : "array", "items" : {"$ref" : "/schemas/NoSignatureAddressesDataGrid"}
}
```

## Related Entities
- [CompaniesHistoricAddressesDataGridResponse](CompaniesHistoricAddressesDataGridResponse.md)
- [CompaniesHistoricNamesDataGridResponse](CompaniesHistoricNamesDataGridResponse.md)
- [CompanyAppointmentsDataGridResponse](CompanyAppointmentsDataGridResponse.md)
- [CompanyPersonsWithSignificantControlDataGridResponse](CompanyPersonsWithSignificantControlDataGridResponse.md)
- [MultiSignatureGridResponse](MultiSignatureGridResponse.md)
- [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md)
- [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md)

