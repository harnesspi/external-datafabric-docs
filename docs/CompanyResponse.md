# CompanyResponse
## Properties
- company_number (String)

   
- company_name (String)

   
- reg_address_care_of (String)

   
- reg_address_po_box (String)

   
- reg_address_address_line1 (String)

   
- reg_address_address_line2 (String)

   
- reg_address_post_town (String)

   
- reg_address_county (String)

   
- reg_address_country (String)

   
- reg_address_post_code (String)

   
- snapshot_date (String)

   
- hpids (String)

   
- company_category (String)

   
- company_status (String)

   
- country_of_origin (String)

   
- dissolution_date (String)

   
- incorporation_date (String)

   
- accounts_account_ref_day (String)

   
- accounts_account_ref_month (String)

   
- accounts_next_due_date (String)

   
- accounts_last_made_up_date (String)

   
- accounts_account_category (String)

   
- returns_next_due_date (String)

   
- returns_last_made_up_date (String)

   
- sic_code_sic_text1 (String)

   
- sic_code_sic_text2 (String)

   
- sic_code_sic_text3 (String)

   
- sic_code_sic_text4 (String)

   
- limited_partnerships_num_gen_partners (String)

   
- limited_partnerships_num_lim_partners (String)

   
- conf_stmt_next_due_date (String)

   
- conf_stmt_last_made_up_date (String)

   
- mortgages_num_mort_charges (String)

   
- mortgages_num_mort_outstanding (String)

   
- mortgages_num_mort_part_satisfied (String)

   
- mortgages_num_mort_satisfied (String)

   
- historic_addresses (Array of [CompaniesHistoricAddressesDataGridResponse](CompaniesHistoricAddressesDataGridResponse.md))

   
- historic_names (Array of [CompaniesHistoricNamesDataGridResponse](CompaniesHistoricNamesDataGridResponse.md))

   
- company_appointments_data_grid (Array of [CompanyAppointmentsDataGridResponse](CompanyAppointmentsDataGridResponse.md))

   
- company_persons_with_significant_control_data_grid (Array of [CompanyPersonsWithSignificantControlDataGridResponse](CompanyPersonsWithSignificantControlDataGridResponse.md))

   
- signatures (Array of [MultiSignatureGridResponse](MultiSignatureGridResponse.md))

   
- internals (Array of [MultiInternalAddressesGridResponse](MultiInternalAddressesGridResponse.md))

   
- no_signatures (Array of [NoSignatureAddressesDataGridResponse](NoSignatureAddressesDataGridResponse.md))

   

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

