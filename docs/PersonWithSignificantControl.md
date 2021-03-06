# PersonWithSignificantControl


## GET /personwithsignificantcontrol/{parameterETag}
### Response 200 (application/json)
Content: [PersonWithSignificantControlResponse](PersonWithSignificantControlResponse.md)

#### Example 1
```
/PersonWithSignificantControl/000014ef02b2ecd132eed3d81e27616771376951
```
```json
{
  "e_tag": "000014ef02b2ecd132eed3d81e27616771376951",
  "person_hpid": "c8c41aa1-9f9c-185a-f952-b00be15ed482",
  "kind": "individual-person-with-significant-control",
  "title": null,
  "name": "Juliet Britto",
  "view_organisation": null,
  "month_of_birth": "1997/09",
  "nationality": "British",
  "country_of_residence": "United Kingdom",
  "registration_number": null,
  "country_registered": null,
  "legal_authority": null,
  "place_registered": null,
  "notified_on": "2020-03-11",
  "legal_form": null,
  "link": "/company/12510008/persons-with-significant-control/individual/VLbJao1Z3ldvfcXN3mcFVReAbFY",
  "snapshot_date": "2021-04-01T00:00:00",
  "premises": "125",
  "address_line1": "Ampleforth Road",
  "address_line2": null,
  "locality": "London",
  "postal_code": "SE2 9BG",
  "county": "Ampleforth Road",
  "region": null,
  "country": "England",
  "company_number": "12510008",
  "company_name": "YOUNG BIG STEPPER LTD",
  "view_company": null,
  "sic_code_sic_text1": "59200 - Sound recording and music publishing activities",
  "natures_of_control": "ownership-of-shares-25-to-50-percent",
  "person_with_significant_control_companies_data_grid": [],
  "signatures": [
    {
      "signature_hpid": {
        "value": "e6bdc3bf-22de-66fa-9766-d9428f9aad41",
        "link": "/SignatureHPID/e6bdc3bf-22de-66fa-9766-d9428f9aad41"
      },
      "building_name": null,
      "start_number": "125",
      "end_number": null,
      "usrn": {
        "value": "20800061",
        "link": "/Street/20800061"
      },
      "street": "AMPLEFORTH RD",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "833944438",
          "link": "/SignatureKey/BuildingPolygon/833944438"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000000040407",
          "link": "/SignatureKey/Ext.Toid/osgb1000000040407"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SGL263318",
          "link": "/SignatureKey/LandRegistryFreehold/SGL263318"
        },
        {
          "key": "Postcode",
          "value": "SE2 9BG",
          "link": "/SignatureKey/Postcode/SE2 9BG"
        },
        {
          "key": "TopUPRN",
          "value": "100020935115",
          "link": "/SignatureKey/TopUPRN/100020935115"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "e6bdc3bf-22de-66fa-9766-d9428f9aad41",
      "internal_hpid": "3dc7e7b2-4048-8d77-a869-f99206707358",
      "organisation": "YOUNG BIG STEPPER LTD",
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
      "keys": "CompanyNumber:12510008",
      "signature": " 125 AMPLEFORTH RD"
    }
  ],
  "no_signatures": []
}
```
#### Example 2
```
/PersonWithSignificantControl/41b1f09e415fd5a1c3634f58bdcc1ece65e862b8
```
```json
{
  "e_tag": "41b1f09e415fd5a1c3634f58bdcc1ece65e862b8",
  "person_hpid": "9084ae8d-4f51-5cc1-5843-0002b95888a6",
  "kind": "individual-person-with-significant-control",
  "title": "Mr",
  "name": "Mr Spencer David Green",
  "view_organisation": null,
  "month_of_birth": "1969/07",
  "nationality": "British",
  "country_of_residence": "United Kingdom",
  "registration_number": null,
  "country_registered": null,
  "legal_authority": null,
  "place_registered": null,
  "notified_on": "2016-04-06",
  "legal_form": null,
  "link": "/company/08813744/persons-with-significant-control/individual/m8ff4msAMs3G7B_xkoTnO7eo5hg",
  "snapshot_date": "2022-03-01T00:00:00",
  "premises": "Queen Square House",
  "address_line1": "18-21 Queen Square",
  "address_line2": null,
  "locality": "Bristol",
  "postal_code": "BS1 4NH",
  "county": "18-21 Queen Square",
  "region": null,
  "country": null,
  "company_number": "08813744",
  "company_name": "GDS INT HOLDINGS LIMITED",
  "view_company": null,
  "sic_code_sic_text1": "70100 - Activities of head offices",
  "natures_of_control": "ownership-of-shares-75-to-100-percent",
  "person_with_significant_control_companies_data_grid": [
    {
      "month_of_birth": "1973/01",
      "match": "0",
      "e_tag": "00280fe09c961a50fd9f9ff0959dd1b24d56462f",
      "company_number": "10352930",
      "company_name": "GREEN COAST GARDENS LTD",
      "natures_of_control": "ownership-of-shares-50-to-75-percent"
    }
  ],
  "signatures": [
    {
      "signature_hpid": {
        "value": "de3599a6-aaf5-cd62-eec7-c452ff8c52b1",
        "link": "/SignatureHPID/de3599a6-aaf5-cd62-eec7-c452ff8c52b1"
      },
      "building_name": null,
      "start_number": "18",
      "end_number": "21",
      "usrn": {
        "value": "4531919",
        "link": "/Street/4531919"
      },
      "street": "QUEEN SQUARE",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "646600792",
          "link": "/SignatureKey/BuildingPolygon/646600792"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000014955706",
          "link": "/SignatureKey/Ext.Toid/osgb1000014955706"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "BL121776",
          "link": "/SignatureKey/LandRegistryFreehold/BL121776"
        },
        {
          "key": "Postcode",
          "value": "BS1 4NH",
          "link": "/SignatureKey/Postcode/BS1 4NH"
        },
        {
          "key": "TopUPRN",
          "value": "325437",
          "link": "/SignatureKey/TopUPRN/325437"
        },
        {
          "key": "TopUPRN",
          "value": "325664",
          "link": "/SignatureKey/TopUPRN/325664"
        },
        {
          "key": "TopUPRN",
          "value": "360784",
          "link": "/SignatureKey/TopUPRN/360784"
        },
        {
          "key": "TopUPRN",
          "value": "360785",
          "link": "/SignatureKey/TopUPRN/360785"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "de3599a6-aaf5-cd62-eec7-c452ff8c52b1",
      "internal_hpid": "9b48b6a6-7f44-02d3-5e53-5ccf9116cd14",
      "organisation": "GDS INT HOLDINGS LTD",
      "land": null,
      "plot": null,
      "block": "QUEEN SQUARE HOUSE",
      "level": null,
      "arch": null,
      "unit": null,
      "flat": null,
      "room": null,
      "parking": null,
      "description": null,
      "object_type": null,
      "keys": "CompanyNumber:08813744",
      "signature": " 18-21 QUEEN SQUARE"
    }
  ],
  "no_signatures": []
}
```
