# LandRegistryTitleOwnership


## GET /landregistrytitleownership/{parameterTitleNumber}
- Response 200 (application/json)
[LandRegistryTitleOwnershipResponse](LandRegistryTitleOwnershipResponse.md)

    ```
   /LandRegistryTitleOwnership/100073
    ```
    ```json
   {
  "title_number": "100073",
  "tenure": "Freehold",
  "property_address": "11 Stanley Crescent, London (W11 2NA)",
  "view_title": null,
  "district": "KENSINGTON AND CHELSEA",
  "county": "GREATER LONDON",
  "region": "GREATER LONDON",
  "postcode": "W11 2NA",
  "multiple_address_indicator": "N",
  "price_paid": null,
  "date_proprietor_added": "2015-07-09T00:00:00",
  "additional_proprietor_indicator": "Y",
  "land_registry_title_companies": [
    {
      "registration_no": null,
      "name": "US TRUST COMPANY OF DELAWARE",
      "organisation": null,
      "country": "U.S.A.",
      "description": "Corporate Body",
      "titles": "bb22061a-3be9-b247-6da2-632f7e34dcb6"
    }
  ],
  "signatures": [
    {
      "signature_hpid": {
        "value": "f1660a0b-c926-415b-c84f-2410a36fbef6",
        "link": "/SignatureHPID/f1660a0b-c926-415b-c84f-2410a36fbef6"
      },
      "building_name": null,
      "start_number": "11",
      "end_number": null,
      "usrn": {
        "value": "21701023",
        "link": "/Street/21701023"
      },
      "street": "STANLEY CRESCENT",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "765905739",
          "link": "/SignatureKey/BuildingPolygon/765905739"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000004035564",
          "link": "/SignatureKey/Ext.Toid/osgb1000004035564"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "100073",
          "link": "/SignatureKey/LandRegistryFreehold/100073"
        },
        {
          "key": "Postcode",
          "value": "W11 2NA",
          "link": "/SignatureKey/Postcode/W11 2NA"
        },
        {
          "key": "TopUPRN",
          "value": "217083156",
          "link": "/SignatureKey/TopUPRN/217083156"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "f1660a0b-c926-415b-c84f-2410a36fbef6",
      "internal_hpid": "45436c57-82e7-f3b0-6f0e-01776a5a8d8c",
      "organisation": "US TRUST COMPANY OF DELAWARE",
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
      "keys": "LandRegistryFreehold:100073",
      "signature": " 11 STANLEY CRESCENT"
    }
  ],
  "no_signatures": []
}
    ```
