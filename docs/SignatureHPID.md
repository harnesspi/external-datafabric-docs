# SignatureHPID


## GET /signaturehpid/{parameterSignatureHPID}
### Response 200 (application/json)
Content: [SignatureHPIDResponse](SignatureHPIDResponse.md)

#### Example 1
```
/SignatureHPID/87fb49ea-9964-4612-bf91-9796ea75247e
```
```json
{
  "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
  "building": null,
  "building_start_number": "2",
  "building_end_number": null,
  "usrn": "22406023",
  "description": "TOWNSHEND RD",
  "customer_reference": null,
  "add_to_cart": null,
  "open_related_signatures": null,
  "data_sources_chart": null,
  "signature_internals": [
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
      "level": {
        "value": "BST",
        "link": "/SignatureMatchingAttribute/87fb49ea-9964-4612-bf91-9796ea75247e/Level/BST"
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
      "signature": null
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
      "signature": null
    }
  ],
  "signature_addresses": [
    {
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
    }
  ],
  "signature_keys": [
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "BuildingPolygon",
      "key_value": "834018792"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "Ext.Toid",
      "key_value": "osgb1000003402921"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "LandRegistryFreehold",
      "key_value": "SY31257"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "ParentUPRN",
      "key_value": "100022318523"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "Postcode",
      "key_value": "TW9 1XH"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "Toid",
      "key_value": "osgb1000003402921"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "TopUPRN",
      "key_value": "100022318523"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "UPRN",
      "key_value": "100022318523"
    },
    {
      "signature_hpid": "87fb49ea-9964-4612-bf91-9796ea75247e",
      "key_type": "UPRN",
      "key_value": "10070709359"
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
