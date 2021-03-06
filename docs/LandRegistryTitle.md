# LandRegistryTitle


## GET /landregistrytitle/{parameterTitleNumber}
### Response 200 (application/json)
Content: [LandRegistryTitleResponse](LandRegistryTitleResponse.md)

#### Example 1
```
/LandRegistryTitle/SY31257/LandRegistryFreehold/SY31257
```
```json
{
  "title_number": "SY31257",
  "tenancy": "Freehold",
  "id": "16E4530833C41C33B35C1B61CCF073CD71B9A497",
  "key_type": "LandRegistryFreehold",
  "key_value": "SY31257",
  "date_context": null,
  "refresh_date_context": null,
  "view_map_iframe": null,
  "open_related_signatures": null,
  "customer_reference": null,
  "add_to_cart": null,
  "data_sources_chart": null,
  "key_signatures": [
    {
      "signature_hpid": {
        "value": "87fb49ea-9964-4612-bf91-9796ea75247e",
        "link": "/SignatureHPID/87fb49ea-9964-4612-bf91-9796ea75247e"
      },
      "building_name": null,
      "start_number": "2",
      "end_number": null,
      "usrn": {
        "value": "22406023",
        "link": "/Street/22406023"
      },
      "street": "TOWNSHEND RD",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "834018792",
          "link": "/SignatureKey/BuildingPolygon/834018792"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000003402921",
          "link": "/SignatureKey/Ext.Toid/osgb1000003402921"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureKey/LandRegistryFreehold/SY31257"
        },
        {
          "key": "Postcode",
          "value": "TW9 1XH",
          "link": "/SignatureKey/Postcode/TW9 1XH"
        },
        {
          "key": "TopUPRN",
          "value": "100022318523",
          "link": "/SignatureKey/TopUPRN/100022318523"
        }
      ]
    },
    {
      "signature_hpid": {
        "value": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
        "link": "/SignatureHPID/66922cb1-7f85-39bf-46be-ae86436a4ff8"
      },
      "building_name": null,
      "start_number": "2B",
      "end_number": null,
      "usrn": {
        "value": "22406023",
        "link": "/Street/22406023"
      },
      "street": "TOWNSHEND RD",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "834018792",
          "link": "/SignatureKey/BuildingPolygon/834018792"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000003402921",
          "link": "/SignatureKey/Ext.Toid/osgb1000003402921"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureKey/LandRegistryFreehold/SY31257"
        },
        {
          "key": "Postcode",
          "value": "TW9 1XH",
          "link": "/SignatureKey/Postcode/TW9 1XH"
        },
        {
          "key": "TopUPRN",
          "value": "100022318520",
          "link": "/SignatureKey/TopUPRN/100022318520"
        }
      ]
    },
    {
      "signature_hpid": {
        "value": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
        "link": "/SignatureHPID/fb9af3b0-8535-5e52-7974-ff7e077c0a65"
      },
      "building_name": null,
      "start_number": "2A",
      "end_number": null,
      "usrn": {
        "value": "22406023",
        "link": "/Street/22406023"
      },
      "street": "TOWNSHEND RD",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "834018792",
          "link": "/SignatureKey/BuildingPolygon/834018792"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000003402921",
          "link": "/SignatureKey/Ext.Toid/osgb1000003402921"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureKey/LandRegistryFreehold/SY31257"
        },
        {
          "key": "Postcode",
          "value": "TW9 1XH",
          "link": "/SignatureKey/Postcode/TW9 1XH"
        },
        {
          "key": "TopUPRN",
          "value": "100022318519",
          "link": "/SignatureKey/TopUPRN/100022318519"
        }
      ]
    }
  ],
  "land_registry_title_upr_ns": [
    {
      "address_hpid": "4802f9f2-cf1a-4f2a-e689-1c8c1ac14761",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH"
    },
    {
      "address_hpid": "a2d88e6e-678a-0550-aae4-a9928e6a9ac0",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH"
    },
    {
      "address_hpid": "9fffb980-c760-8f8f-c789-efc46d0b7a85",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH"
    }
  ],
  "key_signatures_internals": [
    {
      "matched": "True",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "internal_hpid": {
        "value": "4108cbdc-50e6-0bfc-290c-baa8adcf5033",
        "link": "/InternalHPID/4108cbdc-50e6-0bfc-290c-baa8adcf5033"
      },
      "organisation": null,
      "land": null,
      "plot": null,
      "block": null,
      "level": {
        "value": "BST",
        "link": "/SignatureKeyMatchingAttribute/LandRegistryFreehold/SY31257/Level/BST"
      },
      "arch": null,
      "unit": null,
      "flat": null,
      "room": null,
      "parking": null,
      "description": null,
      "object_type": null,
      "keys": [
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureInternalKey/4108cbdc-50e6-0bfc-290c-baa8adcf5033/LandRegistryFreehold/SY31257"
        },
        {
          "key": "UPRN",
          "value": "10070709359",
          "link": "/SignatureInternalKey/4108cbdc-50e6-0bfc-290c-baa8adcf5033/UPRN/10070709359"
        }
      ],
      "signature": " 2 TOWNSHEND RD"
    },
    {
      "matched": "True",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "internal_hpid": {
        "value": "e8fb290a-cb70-01d9-87c1-09b8c8f4172c",
        "link": "/InternalHPID/e8fb290a-cb70-01d9-87c1-09b8c8f4172c"
      },
      "organisation": {
        "value": "SHEPHERDS BUSH HOUSING ASSOCIATION LTD",
        "link": "/SignatureKeyMatchingAttribute/LandRegistryFreehold/SY31257/Organisation/SHEPHERDS BUSH HOUSING ASSOCIATION LTD"
      },
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
      "keys": [
        {
          "key": "LandRegistryLeasehold",
          "value": "SGL428715",
          "link": "/SignatureInternalKey/e8fb290a-cb70-01d9-87c1-09b8c8f4172c/LandRegistryLeasehold/SGL428715"
        }
      ],
      "signature": " 2B TOWNSHEND RD"
    },
    {
      "matched": "True",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "internal_hpid": {
        "value": "e08e2202-ad76-34be-ab67-84ba6938fcf6",
        "link": "/InternalHPID/e08e2202-ad76-34be-ab67-84ba6938fcf6"
      },
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
      "keys": [
        {
          "key": "EpcDomestic",
          "value": "787279945232012051114521143968703",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/EpcDomestic/787279945232012051114521143968703"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/LandRegistryFreehold/SY31257"
        },
        {
          "key": "LandRegistryLeasehold",
          "value": "TGL299890",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/LandRegistryLeasehold/TGL299890"
        },
        {
          "key": "LandRegistryPricePaid",
          "value": "5fd2b80c-280f-4f04-8a63-53fba5007e0e",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/LandRegistryPricePaid/5fd2b80c-280f-4f04-8a63-53fba5007e0e"
        },
        {
          "key": "LandRegistryPricePaid",
          "value": "8e292342-6004-4682-867a-94e51e91d839",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/LandRegistryPricePaid/8e292342-6004-4682-867a-94e51e91d839"
        },
        {
          "key": "LandRegistryPricePaid",
          "value": "ffd92c92-d0ac-47eb-b81e-df2d4643a406",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/LandRegistryPricePaid/ffd92c92-d0ac-47eb-b81e-df2d4643a406"
        },
        {
          "key": "UPRN",
          "value": "100022318519",
          "link": "/SignatureInternalKey/e08e2202-ad76-34be-ab67-84ba6938fcf6/UPRN/100022318519"
        }
      ],
      "signature": " 2A TOWNSHEND RD"
    },
    {
      "matched": "True",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "internal_hpid": {
        "value": "69cf416d-689c-22f6-c85d-31598ba1a238",
        "link": "/InternalHPID/69cf416d-689c-22f6-c85d-31598ba1a238"
      },
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
      "keys": [
        {
          "key": "EpcDomestic",
          "value": "1801238232002020060814325075000758",
          "link": "/SignatureInternalKey/69cf416d-689c-22f6-c85d-31598ba1a238/EpcDomestic/1801238232002020060814325075000758"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureInternalKey/69cf416d-689c-22f6-c85d-31598ba1a238/LandRegistryFreehold/SY31257"
        },
        {
          "key": "LandRegistryLeasehold",
          "value": "TGL393746",
          "link": "/SignatureInternalKey/69cf416d-689c-22f6-c85d-31598ba1a238/LandRegistryLeasehold/TGL393746"
        },
        {
          "key": "UPRN",
          "value": "100022318523",
          "link": "/SignatureInternalKey/69cf416d-689c-22f6-c85d-31598ba1a238/UPRN/100022318523"
        }
      ],
      "signature": " 2 TOWNSHEND RD"
    },
    {
      "matched": "True",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "internal_hpid": {
        "value": "b763599f-1707-cdba-e8d6-def74ffb65d5",
        "link": "/InternalHPID/b763599f-1707-cdba-e8d6-def74ffb65d5"
      },
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
      "keys": [
        {
          "key": "LandRegistryFreehold",
          "value": "SY31257",
          "link": "/SignatureInternalKey/b763599f-1707-cdba-e8d6-def74ffb65d5/LandRegistryFreehold/SY31257"
        },
        {
          "key": "LandRegistryLeasehold",
          "value": "SGL428715",
          "link": "/SignatureInternalKey/b763599f-1707-cdba-e8d6-def74ffb65d5/LandRegistryLeasehold/SGL428715"
        },
        {
          "key": "UPRN",
          "value": "100022318520",
          "link": "/SignatureInternalKey/b763599f-1707-cdba-e8d6-def74ffb65d5/UPRN/100022318520"
        }
      ],
      "signature": " 2B TOWNSHEND RD"
    }
  ],
  "key_addresses_data_grid": [
    {
      "records_count": "30",
      "ordinal_number": "1",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
      "source_name": "ABP",
      "key": "2C4785FC-68B6-7F8F-8844-CF43F941A8AC",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "ABP",
        "value": "2C4785FC-68B6-7F8F-8844-CF43F941A8AC",
        "link": "/Address/ABP/2C4785FC-68B6-7F8F-8844-CF43F941A8AC"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "2",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "503e5780-8eb8-364a-d2e1-60b020d0dc17",
      "source_name": "ABP",
      "key": "503E5780-8EB8-364A-D2E1-60B020D0DC17",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "ABP",
        "value": "503E5780-8EB8-364A-D2E1-60B020D0DC17",
        "link": "/Address/ABP/503E5780-8EB8-364A-D2E1-60B020D0DC17"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "3",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "79c19d41-26e6-3f60-f529-2ea28de50cb8",
      "source_name": "ABP",
      "key": "79C19D41-26E6-3F60-F529-2EA28DE50CB8",
      "uprn": "10070709359",
      "organisation": null,
      "address": "BASEMENT  2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "ABP",
        "value": "79C19D41-26E6-3F60-F529-2EA28DE50CB8",
        "link": "/Address/ABP/79C19D41-26E6-3F60-F529-2EA28DE50CB8"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "4",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "bac3e2a4-2e53-515e-e0cf-83f24df18362",
      "source_name": "ABP",
      "key": "BAC3E2A4-2E53-515E-E0CF-83F24DF18362",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "ABP",
        "value": "BAC3E2A4-2E53-515E-E0CF-83F24DF18362",
        "link": "/Address/ABP/BAC3E2A4-2E53-515E-E0CF-83F24DF18362"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "5",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "640463bb-e94c-8a06-45ec-a8d2c4c6db0d",
      "source_name": "Council Tax Bands",
      "key": "358861084",
      "uprn": null,
      "organisation": null,
      "address": "2A TOWNSHEND ROAD, Richmond, Surrey, TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Council Tax Bands",
        "value": "358861084",
        "link": "/CouncilTaxBand/358861084"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "6",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "e8099536-fd10-d25e-df8c-6f2f47855c1f",
      "source_name": "Council Tax Bands",
      "key": "358862084",
      "uprn": null,
      "organisation": null,
      "address": "2B TOWNSHEND ROAD, Richmond, Surrey, TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Council Tax Bands",
        "value": "358862084",
        "link": "/CouncilTaxBand/358862084"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "7",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "ada912e5-c092-cb6e-2fca-ee90ddf2821c",
      "source_name": "Council Tax Bands",
      "key": "358863084",
      "uprn": null,
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, Richmond, Surrey, TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Council Tax Bands",
        "value": "358863084",
        "link": "/CouncilTaxBand/358863084"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "8",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "3f4970f9-8577-c437-22d0-8da9059c3709",
      "source_name": "Epc Domestic",
      "key": "1801238232002020060814325075000758",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2, Townshend Road|||",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Epc Domestic",
        "value": "1801238232002020060814325075000758",
        "link": "/EPCDomestic/1801238232002020060814325075000758"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "9",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "64c37995-d9ae-8ed4-442b-de2b4103e809",
      "source_name": "Epc Domestic",
      "key": "787279945232012051114521143968703",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2a, Townshend Road|||",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Epc Domestic",
        "value": "787279945232012051114521143968703",
        "link": "/EPCDomestic/787279945232012051114521143968703"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "10",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "ec9d8f92-bf2e-adf7-be0b-2baa2d4c014d",
      "source_name": "Land Registry Lease Entries",
      "key": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3|1",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Lease Entries",
        "value": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3|1",
        "link": "/LandRegistryLeaseEntry/1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3/1"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "11",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "b2742f11-ed9e-6c01-45a6-2396eff7e430",
      "source_name": "Land Registry Lease Entries",
      "key": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49|1",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Lease Entries",
        "value": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49|1",
        "link": "/LandRegistryLeaseEntry/3DFCF8D9DAD727036065EDC19F132E59A8ACBE49/1"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "12",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "7f4dc572-9cb0-9498-28cf-99eac88d3945",
      "source_name": "Land Registry Lease Entries",
      "key": "855C5C670F1D61E380780D6B6647416A9C2F39D1|1",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Lease Entries",
        "value": "855C5C670F1D61E380780D6B6647416A9C2F39D1|1",
        "link": "/LandRegistryLeaseEntry/855C5C670F1D61E380780D6B6647416A9C2F39D1/1"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "13",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "c740c04f-77c5-b43d-cea0-ee6b0cb3ad44",
      "source_name": "Land Registry Price Paid",
      "key": "5fd2b80c-280f-4f04-8a63-53fba5007e0e",
      "uprn": null,
      "organisation": null,
      "address": "|2A|TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Price Paid",
        "value": "5fd2b80c-280f-4f04-8a63-53fba5007e0e",
        "link": "/LandRegistryPricePaid/5fd2b80c-280f-4f04-8a63-53fba5007e0e"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "14",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "b7699eac-b46c-ec82-ef12-7a92f0fd7f5d",
      "source_name": "Land Registry Price Paid",
      "key": "8e292342-6004-4682-867a-94e51e91d839",
      "uprn": null,
      "organisation": null,
      "address": "|2A|TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Price Paid",
        "value": "8e292342-6004-4682-867a-94e51e91d839",
        "link": "/LandRegistryPricePaid/8e292342-6004-4682-867a-94e51e91d839"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "15",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "6891bf15-6490-6fe2-5787-8e5016c28803",
      "source_name": "Land Registry Price Paid",
      "key": "ffd92c92-d0ac-47eb-b81e-df2d4643a406",
      "uprn": null,
      "organisation": null,
      "address": "|2A|TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Price Paid",
        "value": "ffd92c92-d0ac-47eb-b81e-df2d4643a406",
        "link": "/LandRegistryPricePaid/ffd92c92-d0ac-47eb-b81e-df2d4643a406"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "16",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "32b6eee5-59d2-7574-84d3-78e25109d21a",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "16E4530833C41C33B35C1B61CCF073CD71B9A497|1",
      "uprn": null,
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Restrictive Covenant Addresses",
        "value": "16E4530833C41C33B35C1B61CCF073CD71B9A497|1",
        "link": "/LandRegistryRestrictiveCovenant/16E4530833C41C33B35C1B61CCF073CD71B9A497"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "17",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "bb052744-8e04-03d5-c536-5533a5bbfa55",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3|1",
      "uprn": null,
      "organisation": null,
      "address": "2B TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Restrictive Covenant Addresses",
        "value": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3|1",
        "link": "/LandRegistryRestrictiveCovenant/1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "18",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "086ceb50-8141-c3da-e21f-6d09f6c01e1d",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49|1",
      "uprn": null,
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Restrictive Covenant Addresses",
        "value": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49|1",
        "link": "/LandRegistryRestrictiveCovenant/3DFCF8D9DAD727036065EDC19F132E59A8ACBE49"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "19",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "991c781d-a8f1-c7f2-362c-12e89ca26ec7",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "855C5C670F1D61E380780D6B6647416A9C2F39D1|1",
      "uprn": null,
      "organisation": null,
      "address": "2A TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Restrictive Covenant Addresses",
        "value": "855C5C670F1D61E380780D6B6647416A9C2F39D1|1",
        "link": "/LandRegistryRestrictiveCovenant/855C5C670F1D61E380780D6B6647416A9C2F39D1"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "20",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "8070a79a-5ffb-8dcc-ff80-0814d363608a",
      "source_name": "Land Registry Title UPRNs",
      "key": "SGL428715|bac3e2a4-2e53-515e-e0cf-83f24df18362",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Title UPRNs",
        "value": "SGL428715|bac3e2a4-2e53-515e-e0cf-83f24df18362",
        "link": "/TitleUPRN/8070A79A-5FFB-8DCC-FF80-0814D363608A"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "21",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "4802f9f2-cf1a-4f2a-e689-1c8c1ac14761",
      "source_name": "Land Registry Title UPRNs",
      "key": "SY31257|2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Title UPRNs",
        "value": "SY31257|2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
        "link": "/TitleUPRN/4802F9F2-CF1A-4F2A-E689-1C8C1AC14761"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "22",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "9fffb980-c760-8f8f-c789-efc46d0b7a85",
      "source_name": "Land Registry Title UPRNs",
      "key": "SY31257|503e5780-8eb8-364a-d2e1-60b020d0dc17",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Title UPRNs",
        "value": "SY31257|503e5780-8eb8-364a-d2e1-60b020d0dc17",
        "link": "/TitleUPRN/9FFFB980-C760-8F8F-C789-EFC46D0B7A85"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "23",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "a2d88e6e-678a-0550-aae4-a9928e6a9ac0",
      "source_name": "Land Registry Title UPRNs",
      "key": "SY31257|bac3e2a4-2e53-515e-e0cf-83f24df18362",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Title UPRNs",
        "value": "SY31257|bac3e2a4-2e53-515e-e0cf-83f24df18362",
        "link": "/TitleUPRN/A2D88E6E-678A-0550-AAE4-A9928E6A9AC0"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "24",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "f3636e3e-69fd-5d3c-57bf-e9a84870d03d",
      "source_name": "Land Registry Title UPRNs",
      "key": "TGL299890|2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Title UPRNs",
        "value": "TGL299890|2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
        "link": "/TitleUPRN/F3636E3E-69FD-5D3C-57BF-E9A84870D03D"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "25",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "d408c240-361b-4184-0789-fa7f9463fa6a",
      "source_name": "Land Registry Title UPRNs",
      "key": "TGL393746|503e5780-8eb8-364a-d2e1-60b020d0dc17",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Land Registry Title UPRNs",
        "value": "TGL393746|503e5780-8eb8-364a-d2e1-60b020d0dc17",
        "link": "/TitleUPRN/D408C240-361B-4184-0789-FA7F9463FA6A"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "26",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "d77f6687-90e8-6fb4-3c53-bc0097c8adfa",
      "source_name": "Land Registry Titles",
      "key": "SGL428715|c86c1546-9ed8-f397-cf5c-95143fe7cc0a",
      "uprn": null,
      "organisation": "SHEPHERDS BUSH HOUSING ASSOCIATION LIMITED",
      "address": "2b Townshend Road, Richmond (TW9 1XH)|",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Titles",
        "value": "SGL428715|c86c1546-9ed8-f397-cf5c-95143fe7cc0a",
        "link": "/LandRegistryTitleOwnership/SGL428715"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "27",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "17f184bd-4b68-8859-651b-b7458f9a6226",
      "source_name": "Rightmove Historic Prices",
      "key": "P37963904",
      "uprn": null,
      "organisation": null,
      "address": "2a, Townshend Road, Richmond, Greater London TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Rightmove Historic Prices",
        "value": "P37963904",
        "link": "/RightmoveHistoricPrice/P37963904"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "28",
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "6acdd225-f326-82e2-f7f6-86ec25fe1ccb",
      "source_name": "Zoopla Historic Prices",
      "key": "24741703",
      "uprn": null,
      "organisation": null,
      "address": "2 Townshend Road|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Zoopla Historic Prices",
        "value": "24741703",
        "link": "/ZooplaHistoricPriceForm/24741703"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "29",
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "7ff98a7d-76db-9466-9c8f-fa930d1bbdf2",
      "source_name": "Zoopla Historic Prices",
      "key": "24741730",
      "uprn": null,
      "organisation": null,
      "address": "2a Townshend Road|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Zoopla Historic Prices",
        "value": "24741730",
        "link": "/ZooplaHistoricPriceForm/24741730"
      }
    },
    {
      "records_count": "30",
      "ordinal_number": "30",
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "766d30f5-638d-81f0-6f6c-4ae065aab1dc",
      "source_name": "Zoopla Historic Prices",
      "key": "24741731",
      "uprn": null,
      "organisation": null,
      "address": "2b Townshend Road|",
      "postcode": "TW9 1XH",
      "url_query": {
        "key": "Zoopla Historic Prices",
        "value": "24741731",
        "link": "/ZooplaHistoricPriceForm/24741731"
      }
    }
  ],
  "title_details_data_grid": [
    {
      "description": "Ownership Data",
      "form_url": "LandRegistryTitlesOwnershipForm&TitleNumber=SY31257",
      "title_number": "SY31257",
      "id": ""
    },
    {
      "description": "Related Leaseholds",
      "form_url": "LandRegistryLeaseholdTitleForm&TitleNumber=SGL428715&ID=1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3",
      "title_number": "SGL428715",
      "id": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3"
    },
    {
      "description": "Related Leaseholds",
      "form_url": "LandRegistryLeaseholdTitleForm&TitleNumber=TGL116884&ID=",
      "title_number": "TGL116884",
      "id": null
    },
    {
      "description": "Related Leaseholds",
      "form_url": "LandRegistryLeaseholdTitleForm&TitleNumber=TGL299890&ID=855C5C670F1D61E380780D6B6647416A9C2F39D1",
      "title_number": "TGL299890",
      "id": "855C5C670F1D61E380780D6B6647416A9C2F39D1"
    },
    {
      "description": "Related Leaseholds",
      "form_url": "LandRegistryLeaseholdTitleForm&TitleNumber=TGL393746&ID=3DFCF8D9DAD727036065EDC19F132E59A8ACBE49",
      "title_number": "TGL393746",
      "id": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49"
    },
    {
      "description": "Restrictive Covenant",
      "form_url": "LandRegistryRestrictiveCovenantForm&TitleNumber=SY31257&ID=16E4530833C41C33B35C1B61CCF073CD71B9A497",
      "title_number": "SY31257",
      "id": "16E4530833C41C33B35C1B61CCF073CD71B9A497"
    }
  ],
  "listings": [
    {
      "listing_id": {
        "value": "Z59925707",
        "link": "/MarketViewListing/Z59925707"
      },
      "display_address": "Townshend Road, Richmond TW9",
      "property_type": "semi_detached",
      "bedrooms": "3",
      "transaction_type": "for-sale",
      "asking_price": "1395000",
      "relevancy": "2",
      "last_update": "2022-02-07T00:00:00",
      "inactive": "1"
    }
  ]
}
```
