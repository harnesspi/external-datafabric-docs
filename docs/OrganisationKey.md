# OrganisationKey


## GET /organisationkey/{parameterKeyType}/{parameterKeyValue}
- Response 200 (application/json)

[OrganisationKeyResponse](OrganisationKeyResponse.md)
    ```
   /OrganisationKey/CompaniesHouseRegNo/00000402
    ```
    ```json
   {
  "key_type": "CompaniesHouseRegNo",
  "key_value": "00000402",
  "description": null,
  "month_of_birth": null,
  "url_query": null,
  "open_key": null,
  "organisation_records": [
    {
      "hpid": "cc146c36-3ba4-5e09-d46f-3160cdfaf2f0",
      "name": "MILLBAY HOTEL LTD",
      "company_number": "00000402"
    },
    {
      "hpid": "ca2affa4-f773-7c9b-3222-eeb3976659b0",
      "name": "PLYMOUTH HOTEL COMPANY LTD THE",
      "company_number": "00000402"
    }
  ]
}
    ```
