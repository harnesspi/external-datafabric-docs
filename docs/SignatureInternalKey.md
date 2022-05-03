# SignatureInternalKey


## GET /signatureinternalkey/{parameterInternalHPID}/{parameterKeyType}/{parameterKeyValue}
### Response 200 (application/json)
Content: [SignatureInternalKeyResponse](SignatureInternalKeyResponse.md)

#### Example 1
```
/SignatureInternalKey/4108cbdc-50e6-0bfc-290c-baa8adcf5033/LandRegistryFreehold/SY31257
```
```json
{
  "key_type": "LandRegistryFreehold",
  "key_value": "SY31257",
  "internal_key_signature_internals": [
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "internal_hpid": {
        "value": "4108cbdc-50e6-0bfc-290c-baa8adcf5033",
        "link": "/InternalHPID/4108cbdc-50e6-0bfc-290c-baa8adcf5033"
      },
      "organisation": null,
      "land": null,
      "plot": null,
      "block": null,
      "level": "BST",
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
    },
    {
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
    }
  ],
  "addresses": [
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
      "source_name": "ABP",
      "key": "2C4785FC-68B6-7F8F-8844-CF43F941A8AC",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "SignatureAddressForm&SourceName=ABP&AddressHPID=2C4785FC-68B6-7F8F-8844-CF43F941A8AC"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "503e5780-8eb8-364a-d2e1-60b020d0dc17",
      "source_name": "ABP",
      "key": "503E5780-8EB8-364A-D2E1-60B020D0DC17",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "SignatureAddressForm&SourceName=ABP&AddressHPID=503E5780-8EB8-364A-D2E1-60B020D0DC17"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "79c19d41-26e6-3f60-f529-2ea28de50cb8",
      "source_name": "ABP",
      "key": "79C19D41-26E6-3F60-F529-2EA28DE50CB8",
      "uprn": "10070709359",
      "organisation": null,
      "address": "BASEMENT  2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "SignatureAddressForm&SourceName=ABP&AddressHPID=79C19D41-26E6-3F60-F529-2EA28DE50CB8"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "bac3e2a4-2e53-515e-e0cf-83f24df18362",
      "source_name": "ABP",
      "key": "BAC3E2A4-2E53-515E-E0CF-83F24DF18362",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "SignatureAddressForm&SourceName=ABP&AddressHPID=BAC3E2A4-2E53-515E-E0CF-83F24DF18362"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "640463bb-e94c-8a06-45ec-a8d2c4c6db0d",
      "source_name": "Council Tax Bands",
      "key": "358861084",
      "uprn": null,
      "organisation": null,
      "address": "2A TOWNSHEND ROAD, Richmond, Surrey, TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "CouncilTaxBandForm&ID=358861084"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "e8099536-fd10-d25e-df8c-6f2f47855c1f",
      "source_name": "Council Tax Bands",
      "key": "358862084",
      "uprn": null,
      "organisation": null,
      "address": "2B TOWNSHEND ROAD, Richmond, Surrey, TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "CouncilTaxBandForm&ID=358862084"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "ada912e5-c092-cb6e-2fca-ee90ddf2821c",
      "source_name": "Council Tax Bands",
      "key": "358863084",
      "uprn": null,
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, Richmond, Surrey, TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "CouncilTaxBandForm&ID=358863084"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "3f4970f9-8577-c437-22d0-8da9059c3709",
      "source_name": "Epc Domestic",
      "key": "1801238232002020060814325075000758",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2, Townshend Road|||",
      "postcode": "TW9 1XH",
      "url_query": "EPCDomesticForm&LmkKey=1801238232002020060814325075000758"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "64c37995-d9ae-8ed4-442b-de2b4103e809",
      "source_name": "Epc Domestic",
      "key": "787279945232012051114521143968703",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2a, Townshend Road|||",
      "postcode": "TW9 1XH",
      "url_query": "EPCDomesticForm&LmkKey=787279945232012051114521143968703"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "ec9d8f92-bf2e-adf7-be0b-2baa2d4c014d",
      "source_name": "Land Registry Lease Entries",
      "key": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3|1",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryLeaseEntryForm&ID=1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3&EntryNumber=1"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "b2742f11-ed9e-6c01-45a6-2396eff7e430",
      "source_name": "Land Registry Lease Entries",
      "key": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49|1",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryLeaseEntryForm&ID=3DFCF8D9DAD727036065EDC19F132E59A8ACBE49&EntryNumber=1"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "7f4dc572-9cb0-9498-28cf-99eac88d3945",
      "source_name": "Land Registry Lease Entries",
      "key": "855C5C670F1D61E380780D6B6647416A9C2F39D1|1",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryLeaseEntryForm&ID=855C5C670F1D61E380780D6B6647416A9C2F39D1&EntryNumber=1"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "c740c04f-77c5-b43d-cea0-ee6b0cb3ad44",
      "source_name": "Land Registry Price Paid",
      "key": "5fd2b80c-280f-4f04-8a63-53fba5007e0e",
      "uprn": null,
      "organisation": null,
      "address": "|2A|TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryPricePaidForm&GUID=5fd2b80c-280f-4f04-8a63-53fba5007e0e"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "b7699eac-b46c-ec82-ef12-7a92f0fd7f5d",
      "source_name": "Land Registry Price Paid",
      "key": "8e292342-6004-4682-867a-94e51e91d839",
      "uprn": null,
      "organisation": null,
      "address": "|2A|TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryPricePaidForm&GUID=8e292342-6004-4682-867a-94e51e91d839"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "6891bf15-6490-6fe2-5787-8e5016c28803",
      "source_name": "Land Registry Price Paid",
      "key": "ffd92c92-d0ac-47eb-b81e-df2d4643a406",
      "uprn": null,
      "organisation": null,
      "address": "|2A|TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryPricePaidForm&GUID=ffd92c92-d0ac-47eb-b81e-df2d4643a406"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "32b6eee5-59d2-7574-84d3-78e25109d21a",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "16E4530833C41C33B35C1B61CCF073CD71B9A497|1",
      "uprn": null,
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryRestrictiveCovenantForm&ID=16E4530833C41C33B35C1B61CCF073CD71B9A497"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "bb052744-8e04-03d5-c536-5533a5bbfa55",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3|1",
      "uprn": null,
      "organisation": null,
      "address": "2B TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryRestrictiveCovenantForm&ID=1AE1BA724689FE4C9942CAAF8E72574B8A59B1C3"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "086ceb50-8141-c3da-e21f-6d09f6c01e1d",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "3DFCF8D9DAD727036065EDC19F132E59A8ACBE49|1",
      "uprn": null,
      "organisation": null,
      "address": "2 TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryRestrictiveCovenantForm&ID=3DFCF8D9DAD727036065EDC19F132E59A8ACBE49"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "991c781d-a8f1-c7f2-362c-12e89ca26ec7",
      "source_name": "Land Registry Restrictive Covenant Addresses",
      "key": "855C5C670F1D61E380780D6B6647416A9C2F39D1|1",
      "uprn": null,
      "organisation": null,
      "address": "2A TOWNSHEND ROAD, RICHMOND TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "LandRegistryRestrictiveCovenantForm&ID=855C5C670F1D61E380780D6B6647416A9C2F39D1"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "8070a79a-5ffb-8dcc-ff80-0814d363608a",
      "source_name": "Land Registry Title UPRNs",
      "key": "SGL428715|bac3e2a4-2e53-515e-e0cf-83f24df18362",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "TitleUPRNForm&AddressHPID=8070A79A-5FFB-8DCC-FF80-0814D363608A"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "4802f9f2-cf1a-4f2a-e689-1c8c1ac14761",
      "source_name": "Land Registry Title UPRNs",
      "key": "SY31257|2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "TitleUPRNForm&AddressHPID=4802F9F2-CF1A-4F2A-E689-1C8C1AC14761"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "9fffb980-c760-8f8f-c789-efc46d0b7a85",
      "source_name": "Land Registry Title UPRNs",
      "key": "SY31257|503e5780-8eb8-364a-d2e1-60b020d0dc17",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "TitleUPRNForm&AddressHPID=9FFFB980-C760-8F8F-C789-EFC46D0B7A85"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "a2d88e6e-678a-0550-aae4-a9928e6a9ac0",
      "source_name": "Land Registry Title UPRNs",
      "key": "SY31257|bac3e2a4-2e53-515e-e0cf-83f24df18362",
      "uprn": "100022318520",
      "organisation": null,
      "address": "2B TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "TitleUPRNForm&AddressHPID=A2D88E6E-678A-0550-AAE4-A9928E6A9AC0"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "f3636e3e-69fd-5d3c-57bf-e9a84870d03d",
      "source_name": "Land Registry Title UPRNs",
      "key": "TGL299890|2c4785fc-68b6-7f8f-8844-cf43f941a8ac",
      "uprn": "100022318519",
      "organisation": null,
      "address": "2A TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "TitleUPRNForm&AddressHPID=F3636E3E-69FD-5D3C-57BF-E9A84870D03D"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "d408c240-361b-4184-0789-fa7f9463fa6a",
      "source_name": "Land Registry Title UPRNs",
      "key": "TGL393746|503e5780-8eb8-364a-d2e1-60b020d0dc17",
      "uprn": "100022318523",
      "organisation": null,
      "address": "2 TOWNSHEND ROAD",
      "postcode": "TW9 1XH",
      "url_query": "TitleUPRNForm&AddressHPID=D408C240-361B-4184-0789-FA7F9463FA6A"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "17f184bd-4b68-8859-651b-b7458f9a6226",
      "source_name": "Rightmove Historic Prices",
      "key": "P37963904",
      "uprn": null,
      "organisation": null,
      "address": "2a, Townshend Road, Richmond, Greater London TW9 1XH|",
      "postcode": "TW9 1XH",
      "url_query": "RightmoveHistoricPriceForm&PropertyID=P37963904"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "address_hpid": "6acdd225-f326-82e2-f7f6-86ec25fe1ccb",
      "source_name": "Zoopla Historic Prices",
      "key": "24741703",
      "uprn": null,
      "organisation": null,
      "address": "2 Townshend Road|",
      "postcode": "TW9 1XH",
      "url_query": "ZooplaHistoricPriceForm&PropertyID=24741703"
    },
    {
      "signature_hpid": "fb9af3b0-8535-5e52-7974-ff7e077c0a65",
      "address_hpid": "7ff98a7d-76db-9466-9c8f-fa930d1bbdf2",
      "source_name": "Zoopla Historic Prices",
      "key": "24741730",
      "uprn": null,
      "organisation": null,
      "address": "2a Townshend Road|",
      "postcode": "TW9 1XH",
      "url_query": "ZooplaHistoricPriceForm&PropertyID=24741730"
    },
    {
      "signature_hpid": "66922cb1-7f85-39bf-46be-ae86436a4ff8",
      "address_hpid": "766d30f5-638d-81f0-6f6c-4ae065aab1dc",
      "source_name": "Zoopla Historic Prices",
      "key": "24741731",
      "uprn": null,
      "organisation": null,
      "address": "2b Townshend Road|",
      "postcode": "TW9 1XH",
      "url_query": "ZooplaHistoricPriceForm&PropertyID=24741731"
    }
  ]
}
```
