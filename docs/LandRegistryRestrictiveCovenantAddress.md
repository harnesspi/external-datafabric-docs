# LandRegistryRestrictiveCovenantAddress


## GET /landregistryrestrictivecovenantaddress/{parameterID}/{parameterEntryNumber}
### Response 200 (application/json)
Content: [LandRegistryRestrictiveCovenantAddressResponse](LandRegistryRestrictiveCovenantAddressResponse.md)

#### Example 1
```
/LandRegistryRestrictiveCovenantAddress/0000002FB084A15F3F49DC2B4A8DFF5328EC705E/1
```
```json
{
  "id": "0000002FB084A15F3F49DC2B4A8DFF5328EC705E",
  "entry_number": "1",
  "address_id": "24497029",
  "address": "12 COPELAND DRIVE, STONE ST15 8YP",
  "signatures": [
    {
      "signature_hpid": {
        "value": "e07877cb-0aa6-b82f-e3c3-76021606f0af",
        "link": "/SignatureHPID/e07877cb-0aa6-b82f-e3c3-76021606f0af"
      },
      "building_name": null,
      "start_number": "12",
      "end_number": null,
      "usrn": {
        "value": "37602339",
        "link": "/Street/37602339"
      },
      "street": "COPELAND DRIVE",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "511646237",
          "link": "/SignatureKey/BuildingPolygon/511646237"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000024661780",
          "link": "/SignatureKey/Ext.Toid/osgb1000024661780"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SF311313",
          "link": "/SignatureKey/LandRegistryFreehold/SF311313"
        },
        {
          "key": "Postcode",
          "value": "ST15 8YP",
          "link": "/SignatureKey/Postcode/ST15 8YP"
        },
        {
          "key": "TopUPRN",
          "value": "200001323722",
          "link": "/SignatureKey/TopUPRN/200001323722"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "e07877cb-0aa6-b82f-e3c3-76021606f0af",
      "internal_hpid": "e28a72de-fee0-ff25-6766-0ccf4e1dc798",
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
      "keys": "LandRegistryFreehold:SF311313,LandRegistryPricePaid:bddc65f7-d4ba-4fe3-9342-0ea394a6cee9,UPRN:200001323722",
      "signature": " 12 COPELAND DRIVE"
    }
  ],
  "no_signatures": []
}
```
