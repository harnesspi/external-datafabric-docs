# ZooplaHistoricPriceForm


## GET /zooplahistoricpriceform/{parameterPropertyID}
### Response 200 (application/json)
Content: [ZooplaHistoricPriceFormResponse](ZooplaHistoricPriceFormResponse.md)

#### Example 1
```
/ZooplaHistoricPriceForm/5020
```
```json
{
  "property_id": "5020",
  "address": "2 Upperkirkgate",
  "locality": "Aberdeen",
  "postcode": "AB10 1BA",
  "region": "Scotland",
  "detail_url": "https://www.zoopla.co.uk/property/2-upperkirkgate/aberdeen/ab10-1ba/5020",
  "open_property_url": null,
  "bedrooms": null,
  "bathrooms": null,
  "reception_rooms": null,
  "property_type": null,
  "features": null,
  "last_sale_date": null,
  "last_sale_price": null,
  "import_date": "2022-01-01T00:00:00",
  "signatures": [
    {
      "signature_hpid": {
        "value": "cdab780a-ccfa-96e0-7830-bb5f45ae59c9",
        "link": "/SignatureHPID/cdab780a-ccfa-96e0-7830-bb5f45ae59c9"
      },
      "building_name": null,
      "start_number": "2",
      "end_number": null,
      "usrn": {
        "value": "7601432",
        "link": "/Street/7601432"
      },
      "street": "UPPERKIRKGATE",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "25942010",
          "link": "/SignatureKey/BuildingPolygon/25942010"
        },
        {
          "key": "Estate",
          "value": "25942010",
          "link": "/SignatureKey/Estate/25942010"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000039194753",
          "link": "/SignatureKey/Ext.Toid/osgb1000039194753"
        },
        {
          "key": "Postcode",
          "value": "AB10 1BA",
          "link": "/SignatureKey/Postcode/AB10 1BA"
        },
        {
          "key": "TopUPRN",
          "value": "9051081449",
          "link": "/SignatureKey/TopUPRN/9051081449"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "cdab780a-ccfa-96e0-7830-bb5f45ae59c9",
      "internal_hpid": "da26ab83-2c87-b31b-0876-ad0116aec2a6",
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
      "keys": "UPRN:9051081449",
      "signature": " 2 UPPERKIRKGATE"
    }
  ],
  "no_signatures": []
}
```
