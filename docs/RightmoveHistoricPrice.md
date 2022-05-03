# RightmoveHistoricPrice


## GET /rightmovehistoricprice/{parameterPropertyID}
- Response 200 (application/json)
[RightmoveHistoricPriceResponse](RightmoveHistoricPriceResponse.md)

    ```
   /RightmoveHistoricPrice/000004AC-23B1-55FF-6ABA-E63A9A746F18
    ```
    ```json
   {
  "property_id": "000004AC-23B1-55FF-6ABA-E63A9A746F18",
  "address": "7, Church Gardens, Middlestown, Wakefield, West Yorkshire WF4 4FD",
  "postcode": "WF4 4FD",
  "has_images": "False",
  "detail_url": null,
  "open_property_url": null,
  "property_type": "Flat",
  "bedrooms": null,
  "has_floor_plan": "False",
  "import_date": "2022-01-01T00:00:00",
  "import_guid": "1ca79eb6-c870-0720-5037-10cbe28391cb",
  "transactions": [
    {
      "date_sold": "2019-01-04T00:00:00",
      "display_price": "£90,000",
      "tenure": "Leasehold",
      "new_build": "False"
    },
    {
      "date_sold": "2012-07-30T00:00:00",
      "display_price": "£102,450",
      "tenure": "Leasehold",
      "new_build": "True"
    }
  ],
  "signatures": [
    {
      "signature_hpid": {
        "value": "e765b1db-0ba0-0874-0394-d015864d21c6",
        "link": "/SignatureHPID/e765b1db-0ba0-0874-0394-d015864d21c6"
      },
      "building_name": null,
      "start_number": "7",
      "end_number": null,
      "usrn": {
        "value": "41806698",
        "link": "/Street/41806698"
      },
      "street": "CHURCH GARDENS",
      "keys": [
        {
          "key": "Ext.Toid",
          "value": "osgb1000000086804633",
          "link": "/SignatureKey/Ext.Toid/osgb1000000086804633"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "WYK785265",
          "link": "/SignatureKey/LandRegistryFreehold/WYK785265"
        },
        {
          "key": "Postcode",
          "value": "WF4 4FD",
          "link": "/SignatureKey/Postcode/WF4 4FD"
        },
        {
          "key": "TopUPRN",
          "value": "63180462",
          "link": "/SignatureKey/TopUPRN/63180462"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "e765b1db-0ba0-0874-0394-d015864d21c6",
      "internal_hpid": "6a559679-928f-7462-b36f-0c7d813dedeb",
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
      "keys": "EpcDomestic:634161309742011060915094182790218,LandRegistryFreehold:WYK785265,LandRegistryLeasehold:YY7686,LandRegistryPricePaid:1ca61b18-6740-48a0-b478-0dfe3416bdd9,LandRegistryPricePaid:80e1aa98-f215-7bf8-e053-6c04a8c00bf2,UPRN:63180469",
      "signature": " 7 CHURCH GARDENS"
    }
  ],
  "no_signatures": []
}
    ```
