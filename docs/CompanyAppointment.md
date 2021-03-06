# CompanyAppointment


## GET /companyappointment/{parameterFileName}/{parameterLineNumber}
### Response 200 (application/json)
Content: [CompanyAppointmentResponse](CompanyAppointmentResponse.md)

#### Example 1
```
/CompanyAppointment/Snapshot/140559
```
```json
{
  "person_number": "037543250001",
  "title": null,
  "forenames": "ROGER",
  "surname": "BUSH",
  "honours": null,
  "care_of": null,
  "po_box": null,
  "address_line1": "12 SANDS FARM DRIVE",
  "address_line2": null,
  "post_town": "BURNHAM",
  "county": "BUCKINGHAMSHIRE",
  "country": null,
  "person_postcode": "SL1 7LD ",
  "partial_date_of_birth": "194404  ",
  "occupation": "PRINTER",
  "nationality": "BRITISH",
  "usual_residential_country": null,
  "appointment_date": "1994-01-03T00:00:00",
  "app_date_origin": "2",
  "app_date_origin_description": "Appointment date taken from Annual Return (form 363)",
  "appointment_type": "01",
  "appointment_type_description": "Current Director",
  "file_name": "Snapshot",
  "line_number": "140559",
  "old_person_postcode": null,
  "old_person_number": null,
  "old_appointment_type": null,
  "correction_indicator": null,
  "corporate_indicator": null,
  "resignation_date": null,
  "res_date_origin": null,
  "res_date_origin_description": null,
  "company_number": "00404804",
  "company_name": null,
  "view_company": null,
  "appointed_person_other_companies_data_grid": [
    {
      "company_number": "02665592",
      "company_name": "CREST COLOUR GRAPHICS LIMITED",
      "sic_code_sic_text1": "2222 - Printing not elsewhere classified"
    }
  ],
  "signatures": [
    {
      "signature_hpid": {
        "value": "8598dcda-81a2-1d95-7f05-5f9f0578ba99",
        "link": "/SignatureHPID/8598dcda-81a2-1d95-7f05-5f9f0578ba99"
      },
      "building_name": null,
      "start_number": "12",
      "end_number": null,
      "usrn": {
        "value": "35200196",
        "link": "/Street/35200196"
      },
      "street": "SANDS FARM DRIVE",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "375519179",
          "link": "/SignatureKey/BuildingPolygon/375519179"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000016597984",
          "link": "/SignatureKey/Ext.Toid/osgb1000016597984"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "BM65547",
          "link": "/SignatureKey/LandRegistryFreehold/BM65547"
        },
        {
          "key": "Postcode",
          "value": "SL1 7LD",
          "link": "/SignatureKey/Postcode/SL1 7LD"
        },
        {
          "key": "TopUPRN",
          "value": "100080495175",
          "link": "/SignatureKey/TopUPRN/100080495175"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "8598dcda-81a2-1d95-7f05-5f9f0578ba99",
      "internal_hpid": "466f9787-594a-e4c2-a2d9-46a8074e2250",
      "organisation": "FAKSIM FOTO LTD",
      "land": null,
      "plot": null,
      "block": null,
      "level": null,
      "arch": null,
      "unit": null,
      "flat": null,
      "room": null,
      "parking": null,
      "description": null,
      "object_type": null,
      "keys": "CompanyNumber:00404804",
      "signature": " 12 SANDS FARM DRIVE"
    }
  ],
  "no_signatures": []
}
```
#### Example 2
```
/CompanyAppointment/Snapshot/69
```
```json
{
  "person_number": "132910690001",
  "title": "MRS",
  "forenames": "ANNE LOUISE",
  "surname": "OLIVER",
  "honours": null,
  "care_of": null,
  "po_box": null,
  "address_line1": "2-4 BROADWAY PARK, SOUTH GYLE BROADWAY",
  "address_line2": null,
  "post_town": "EDINBURGH",
  "county": null,
  "country": "UNITED KINGDOM",
  "person_postcode": "EH12 9JZ",
  "partial_date_of_birth": "197201  ",
  "occupation": "UK TAX MANAGER",
  "nationality": "BRITISH",
  "usual_residential_country": "UNITED KINGDOM",
  "appointment_date": "2009-01-15T00:00:00",
  "app_date_origin": "1",
  "app_date_origin_description": "Appointment date taken from appointment document (includes 288a, AP01, AP02, AP03, AP04, RR01**, NI form 296, SEAP01, and SEAP02) ** Appointment of secretary on re-registration from private company to PLC.",
  "appointment_type": "00",
  "appointment_type_description": "Current Secretary",
  "file_name": "Snapshot",
  "line_number": "69",
  "old_person_postcode": null,
  "old_person_number": null,
  "old_appointment_type": null,
  "correction_indicator": null,
  "corporate_indicator": null,
  "resignation_date": null,
  "res_date_origin": null,
  "res_date_origin_description": null,
  "company_number": "00000633",
  "company_name": null,
  "view_company": null,
  "appointed_person_other_companies_data_grid": [],
  "signatures": [
    {
      "signature_hpid": {
        "value": "d127fb1d-6edc-f7ed-e7b0-d49e05b7a4df",
        "link": "/SignatureHPID/d127fb1d-6edc-f7ed-e7b0-d49e05b7a4df"
      },
      "building_name": null,
      "start_number": "3",
      "end_number": "4",
      "usrn": {
        "value": "7905365",
        "link": "/Street/7905365"
      },
      "street": "BROADWAY PRK",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "37943897",
          "link": "/SignatureKey/BuildingPolygon/37943897"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000002106117137",
          "link": "/SignatureKey/Ext.Toid/osgb1000002106117137"
        },
        {
          "key": "Postcode",
          "value": "EH12 9JQ",
          "link": "/SignatureKey/Postcode/EH12 9JQ"
        },
        {
          "key": "Postcode",
          "value": "EH12 9JZ",
          "link": "/SignatureKey/Postcode/EH12 9JZ"
        },
        {
          "key": "TopUPRN",
          "value": "906459160",
          "link": "/SignatureKey/TopUPRN/906459160"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "d127fb1d-6edc-f7ed-e7b0-d49e05b7a4df",
      "internal_hpid": "9245b300-571a-aac0-e484-e79206792f4e",
      "organisation": "SLALOM LAGER LTD",
      "land": null,
      "plot": null,
      "block": null,
      "level": null,
      "arch": null,
      "unit": null,
      "flat": null,
      "room": null,
      "parking": null,
      "description": null,
      "object_type": null,
      "keys": "CompanyNumber:00000633",
      "signature": " 3-4 BROADWAY PRK"
    }
  ],
  "no_signatures": []
}
```
