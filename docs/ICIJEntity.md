# ICIJEntity


## GET /icijentity/{parameterEntityId}
- Response 200 (application/json)

[ICIJEntityResponse](ICIJEntityResponse.md)
    ```
   /ICIJEntity/10
    ```
    ```json
   {
  "entity_id": "10",
  "name": "HUGH POWER LIMITED",
  "original_name": "HUGH POWER LIMITED",
  "former_name": "",
  "jurisdiction": "SAM",
  "jurisdiction_description": "Samoa",
  "company_type": "",
  "address": "ORION HOUSE SERVICES (HK) LIMITED ROOM 1401; 14/F.; WORLD COMMERCE  CENTRE; HARBOUR CITY; 7-11 CANTON ROAD; TSIM SHA TSUI; KOWLOON; HONG KONG",
  "registration_number": "16464",
  "country_codes": "HKG",
  "countries": "Hong Kong",
  "incorporation_date": "2004-03-30T00:00:00",
  "inactivation_date": "2008-01-02T00:00:00",
  "struck_off_date": "2008-02-15T00:00:00",
  "dorm_date": null,
  "status": "Defaulted",
  "internal_id": "1000081",
  "icij_source": "Panama Papers",
  "service_provider": "Mossack Fonseca",
  "note": "",
  "addresses": [],
  "officers": [
    {
      "officer_id": {
        "value": "406068",
        "link": "/ICIJOfficer/406068"
      },
      "officer_type": "shareholder of",
      "status": "",
      "start_date": "2004-11-17T00:00:00",
      "end_date": "2004-11-17T00:00:00",
      "name": "LONG HARVEST INVESTMENTS LIMITED",
      "countries": "Niue"
    },
    {
      "officer_id": {
        "value": "388171",
        "link": "/ICIJOfficer/388171"
      },
      "officer_type": "shareholder of",
      "status": "",
      "start_date": "2004-03-30T00:00:00",
      "end_date": null,
      "name": "MOSSFON SUBSCRIBERS LTD.",
      "countries": "Samoa"
    }
  ],
  "intermediaries": [
    {
      "intermediary_id": {
        "value": "216244",
        "link": "/ICIJIntermediary/216244"
      },
      "intermediary_type": "intermediary of",
      "status": "",
      "start_date": null,
      "end_date": null,
      "name": "ORION HOUSE SERVICES (HK) LIMITED",
      "countries": "Hong Kong"
    }
  ],
  "related_organisations": [
    {
      "entity_id": "10",
      "organisation_hpid": "b4381382-93cc-be20-a575-599429fb3451",
      "related_organisation": "HUGH POWER LTD",
      "source_name": "Companies House",
      "row_key": "13806265",
      "row_key_subfix": "0|",
      "registration_number": "13806265",
      "country_registered": "UK",
      "url_query": {
        "key": "Companies House",
        "value": "13806265",
        "link": "/Company/13806265"
      }
    }
  ]
}
    ```
    ```
   /ICIJEntity/55
    ```
    ```json
   {
  "entity_id": "55",
  "name": "SEG MECHANICAL LTD.",
  "original_name": "SEG MECHANICAL LTD.",
  "former_name": "",
  "jurisdiction": "SAM",
  "jurisdiction_description": "Samoa",
  "company_type": "",
  "address": "EUROFIN SERVICES S.A. P.O.BOX  6003 LAUSANNE 1002, VAUD SWITZERLAND",
  "registration_number": "R28810",
  "country_codes": "CHE",
  "countries": "Switzerland",
  "incorporation_date": "2006-11-08T00:00:00",
  "inactivation_date": "2014-02-27T00:00:00",
  "struck_off_date": "2014-02-15T00:00:00",
  "dorm_date": null,
  "status": "Defaulted",
  "internal_id": "1001944",
  "icij_source": "Panama Papers",
  "service_provider": "Mossack Fonseca",
  "note": "",
  "addresses": [
    {
      "address_id": "558503",
      "address": "EUROFIN SERVICES S.A. P.O.BOX  6003 LAUSANNE 1002, VAUD SWITZERLAND",
      "name": "",
      "countries": "Switzerland",
      "icij_source": "Panama Papers",
      "note": ""
    }
  ],
  "officers": [
    {
      "officer_id": {
        "value": "377679",
        "link": "/ICIJOfficer/377679"
      },
      "officer_type": "shareholder of",
      "status": "",
      "start_date": "2008-07-03T00:00:00",
      "end_date": null,
      "name": "GOSFORTH INC.",
      "countries": "Panama"
    },
    {
      "officer_id": {
        "value": "273977",
        "link": "/ICIJOfficer/273977"
      },
      "officer_type": "shareholder of",
      "status": "",
      "start_date": "2006-11-08T00:00:00",
      "end_date": "2008-07-03T00:00:00",
      "name": "THE BEARER",
      "countries": ""
    },
    {
      "officer_id": {
        "value": "273978",
        "link": "/ICIJOfficer/273978"
      },
      "officer_type": "shareholder of",
      "status": "",
      "start_date": "2006-11-08T00:00:00",
      "end_date": "2008-07-03T00:00:00",
      "name": "THE BEARER",
      "countries": ""
    },
    {
      "officer_id": {
        "value": "273979",
        "link": "/ICIJOfficer/273979"
      },
      "officer_type": "shareholder of",
      "status": "",
      "start_date": "2006-11-08T00:00:00",
      "end_date": "2008-07-03T00:00:00",
      "name": "THE BEARER",
      "countries": ""
    }
  ],
  "intermediaries": [
    {
      "intermediary_id": {
        "value": "225897",
        "link": "/ICIJIntermediary/225897"
      },
      "intermediary_type": "intermediary of",
      "status": "",
      "start_date": null,
      "end_date": null,
      "name": "EUROFIN SERVICES S.A.",
      "countries": ""
    }
  ],
  "related_organisations": [
    {
      "entity_id": "55",
      "organisation_hpid": "80c4b2d3-2133-4839-ab84-49a24511d063",
      "related_organisation": "SEG MECHANICAL LTD",
      "source_name": "ICIJ Entities",
      "row_key": "184530",
      "row_key_subfix": null,
      "registration_number": "004584",
      "country_registered": "CHE",
      "url_query": {
        "key": "ICIJ Entities",
        "value": "184530",
        "link": "/ICIJEntity/184530"
      }
    }
  ]
}
    ```
