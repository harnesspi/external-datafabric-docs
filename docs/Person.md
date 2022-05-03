# Person


## GET /person/{parameterPersonHPID}
### Response 200 (application/json)
Content: [PersonResponse](PersonResponse.md)

#### Example 1
```
/Person/F3149A0A-6585-0D4A-686B-4834880E1C15/196211
```
```json
{
  "person_hpid": "f3149a0a-6585-0d4a-686b-4834880e1c15",
  "name": "IVI ORFANIDOU MICHAIL",
  "month_of_birth": [
    "196211"
  ],
  "person_records_data_grid": [
    {
      "source_name": "Company Appointments",
      "month_of_birth": "196211  ",
      "full_match": "1",
      "row_key": "Snapshot",
      "row_key_subfix": "18570876",
      "company": null,
      "url_query": "CompanyAppointmentForm&FileName=Snapshot&LineNumber=18570876"
    }
  ]
}
```
#### Example 2
```
/Person/F3149A0A-6585-0D4A-686B-4834880E1C15
```
```json
{
  "person_hpid": "f3149a0a-6585-0d4a-686b-4834880e1c15",
  "name": "IVI ORFANIDOU MICHAIL",
  "month_of_birth": [
    ""
  ],
  "person_records_data_grid": [
    {
      "source_name": "Company Appointments",
      "month_of_birth": "196211  ",
      "full_match": "0",
      "row_key": "Snapshot",
      "row_key_subfix": "18570876",
      "company": null,
      "url_query": "CompanyAppointmentForm&FileName=Snapshot&LineNumber=18570876"
    }
  ]
}
```
