# VOA


## GET /voa/{parameterUARN}
- Response 200 (application/json)

[VOAResponse](VOAResponse.md)
    ```
   /VOA/49110033
    ```
    ```json
   {
  "uarn": "49110033",
  "description": "Shop And Premises",
  "scat_code": "249",
  "address_date": "2017-04-01T00:00:00",
  "source_name": "voa2017.RatingListDetails",
  "firms_name": "The Occupier",
  "view_organisation": null,
  "number_or_name": "115",
  "sub_street_level3": null,
  "sub_street_level2": null,
  "sub_street_level1": null,
  "street": "REDCLIFFE STREET",
  "town": null,
  "postal_district": "SUTTON-IN-ASHFIELD",
  "county": "NOTTS",
  "postcode": "NG17 4ES",
  "assessments": [
    {
      "assessment_reference": "10000005000",
      "list_year": "2010",
      "from_date": "2010-04-01T00:00:00",
      "to_date": null,
      "primary_description_text": "Shop And Premises",
      "total_area": "103.15",
      "total_adj": null
    },
    {
      "assessment_reference": "16275179000",
      "list_year": "2017",
      "from_date": "2017-04-01T00:00:00",
      "to_date": "2018-03-04T00:00:00",
      "primary_description_text": "Shop And Premises",
      "total_area": "103.15",
      "total_adj": null
    },
    {
      "assessment_reference": "19979943000",
      "list_year": "2017",
      "from_date": "2018-03-05T00:00:00",
      "to_date": "2018-07-16T00:00:00",
      "primary_description_text": "Shop And Premises",
      "total_area": "53.12",
      "total_adj": null
    }
  ],
  "list_entry_data_items": [
    {
      "assessment_reference": "10000005000",
      "list_year": "2010",
      "primary_description_text": "SHOP AND PREMISES",
      "case_number": "12963883037",
      "rateable_value": "3650",
      "current_from_date": "2010-04-01T00:00:00",
      "current_to_date": null
    },
    {
      "assessment_reference": "23617749000",
      "list_year": "2017",
      "primary_description_text": "PROPERTY UNDER CONVERSION",
      "case_number": "34579362596",
      "rateable_value": null,
      "current_from_date": "2020-09-04T00:00:00",
      "current_to_date": null
    }
  ],
  "list_entry_data_items_historic": [
    {
      "assessment_reference": "16275179000",
      "list_year": "2017",
      "primary_description_text": "SHOP AND PREMISES",
      "case_number": "20203881036",
      "rateable_value": "5200",
      "historic_from_date": "2017-04-01T00:00:00",
      "historic_to_date": "2018-03-04T00:00:00"
    },
    {
      "assessment_reference": "19979943000",
      "list_year": "2017",
      "primary_description_text": "SHOP AND PREMISES",
      "case_number": "30576025036",
      "rateable_value": "5000",
      "historic_from_date": "2018-03-05T00:00:00",
      "historic_to_date": "2018-07-16T00:00:00"
    },
    {
      "assessment_reference": "20127528000",
      "list_year": "2017",
      "primary_description_text": "PROPERTY UNDER CONVERSION",
      "case_number": "30744569285",
      "rateable_value": "0",
      "historic_from_date": "2018-07-17T00:00:00",
      "historic_to_date": "2018-07-25T00:00:00"
    },
    {
      "assessment_reference": "20136248000",
      "list_year": "2017",
      "primary_description_text": "PROPERTY UNDER CONVERSION",
      "case_number": "30855491282",
      "rateable_value": "0",
      "historic_from_date": "2018-07-26T00:00:00",
      "historic_to_date": "2020-09-03T00:00:00"
    }
  ],
  "signatures": [
    {
      "signature_hpid": {
        "value": "7d06abc9-a194-2b1a-f4dc-62c732fb5cd2",
        "link": "/SignatureHPID/7d06abc9-a194-2b1a-f4dc-62c732fb5cd2"
      },
      "building_name": null,
      "start_number": "115",
      "end_number": null,
      "usrn": {
        "value": "1216104",
        "link": "/Street/1216104"
      },
      "street": "REDCLIFFE ST",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "259837655",
          "link": "/SignatureKey/BuildingPolygon/259837655"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000022561485",
          "link": "/SignatureKey/Ext.Toid/osgb1000022561485"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "NT219560",
          "link": "/SignatureKey/LandRegistryFreehold/NT219560"
        },
        {
          "key": "Postcode",
          "value": "NG17 4ES",
          "link": "/SignatureKey/Postcode/NG17 4ES"
        },
        {
          "key": "TopUPRN",
          "value": "100031256405",
          "link": "/SignatureKey/TopUPRN/100031256405"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "7d06abc9-a194-2b1a-f4dc-62c732fb5cd2",
      "internal_hpid": "8110f69b-c6e3-4bac-b2ba-45151cd64914",
      "organisation": null,
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
      "keys": "EpcNonDomestic:62424640062012040412500498040480,LandRegistryFreehold:NT219560,LandRegistryPricePaid:68feb20c-5f9a-38da-e053-6c04a8c051ae,UARN:49110033,UPRN:100031256405",
      "signature": " 115 REDCLIFFE ST"
    }
  ],
  "no_signatures": []
}
    ```
    ```
   /VOA/420475252
    ```
    ```json
   {
  "uarn": "420475252",
  "description": "PUBLIC HOUSE AND PREMISES",
  "scat_code": "226G",
  "address_date": "2019-10-21T00:00:00",
  "source_name": "voa2017.ListEntryDataItems",
  "firms_name": null,
  "view_organisation": null,
  "number_or_name": "MOORTHORPE HOTEL",
  "sub_street_level3": null,
  "sub_street_level2": null,
  "sub_street_level1": null,
  "street": "BARNSLEY ROAD",
  "town": "PONTEFRACT",
  "postal_district": "SOUTH KIRKBY",
  "county": "WEST YORKSHIRE",
  "postcode": "WF9 3BG",
  "assessments": [],
  "list_entry_data_items": [
    {
      "assessment_reference": "10484383000",
      "list_year": "2010",
      "primary_description_text": "PUBLIC HOUSE AND PREMISES",
      "case_number": "12791278244",
      "rateable_value": "3000",
      "current_from_date": "2010-04-01T00:00:00",
      "current_to_date": null
    },
    {
      "assessment_reference": "21316635000",
      "list_year": "2017",
      "primary_description_text": "PUBLIC HOUSE AND PREMISES",
      "case_number": "33722489282",
      "rateable_value": null,
      "current_from_date": "2019-10-21T00:00:00",
      "current_to_date": null
    }
  ],
  "list_entry_data_items_historic": [
    {
      "assessment_reference": "17196172000",
      "list_year": "2017",
      "primary_description_text": "PUBLIC HOUSE AND PREMISES",
      "case_number": "20075758257",
      "rateable_value": "2600",
      "historic_from_date": "2017-04-01T00:00:00",
      "historic_to_date": "2019-10-20T00:00:00"
    }
  ],
  "signatures": [],
  "internals": [],
  "no_signatures": [
    {
      "source_name": "VOA",
      "row_key": "420475252",
      "row_key_subfix": null,
      "organisation": null,
      "address": "|MOORTHORPE HOTEL|||",
      "usrn": "41800256",
      "street": "BARNSLEY RD",
      "postcode": "WF9 3BG",
      "building": null,
      "url_query": {
        "key": "VOA",
        "value": "420475252|",
        "link": "/VOA/420475252"
      }
    }
  ]
}
    ```
