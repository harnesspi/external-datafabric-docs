# LandRegistryLeaseholdTitleByID


## GET /landregistryleaseholdtitlebyid/{parameterID}
- Response 200 (application/json)
[LandRegistryLeaseholdTitleByIDResponse](LandRegistryLeaseholdTitleByIDResponse.md)

    ```
   /LandRegistryLeaseholdTitle/100462/5D0FA4909B7C0FD9477C2275E1948C8F135E233F
    ```
    ```json
   {
  "title_number": "100462",
  "tenancy": "Leasehold",
  "id": "5D0FA4909B7C0FD9477C2275E1948C8F135E233F",
  "price_paid": null,
  "description": "7 Agnes Street, Limehouse",
  "county": "GREATER LONDON",
  "region": "GREATER LONDON",
  "alienation_clause_indicator": "N",
  "view_map_iframe": null,
  "land_registry_lease_entries_data_grid": [
    {
      "id": "5D0FA4909B7C0FD9477C2275E1948C8F135E233F",
      "entry_number": "1",
      "reg_order": "2",
      "associated_property_id": "3125118",
      "associated_property_description": "7 AGNES STREET, LONDON E14 7DG",
      "uprn": "6044926",
      "lease_date": "1866-10-16T00:00:00",
      "term": "99 years from 24 June 1862"
    },
    {
      "id": "5D0FA4909B7C0FD9477C2275E1948C8F135E233F",
      "entry_number": "2",
      "reg_order": "2",
      "associated_property_id": "1001484188",
      "associated_property_description": "7A AGNES STREET, LONDON E14 7DG",
      "uprn": "6089966",
      "lease_date": "1866-10-16T00:00:00",
      "term": "99 years from 24 June 1862"
    },
    {
      "id": "5D0FA4909B7C0FD9477C2275E1948C8F135E233F",
      "entry_number": "3",
      "reg_order": "2",
      "associated_property_id": "1001583415",
      "associated_property_description": "7B AGNES STREET, LONDON E14 7DG",
      "uprn": null,
      "lease_date": "1866-10-16T00:00:00",
      "term": "99 years from 24 June 1862"
    }
  ],
  "land_registry_title_upr_ns": [
    {
      "address_hpid": "fcefb4d9-26a9-4074-4353-b97cd966fb3a",
      "signature_hpid": "47673024-ea82-a40a-5c5d-d05825ea8547",
      "uprn": "6044926",
      "organisation": null,
      "address": "7 AGNES STREET",
      "postcode": "E14 7DG"
    },
    {
      "address_hpid": "5ba56813-0900-6c62-3a4e-ad8fffa06097",
      "signature_hpid": "ef4a09c1-ce37-bb86-5cbe-3dce5545ab01",
      "uprn": "6089966",
      "organisation": null,
      "address": "7A AGNES STREET",
      "postcode": "E14 7DG"
    }
  ],
  "title_details_data_grid": [
    {
      "description": "Related Freeholds",
      "form_url": "LandRegistryTitleForm&TitleNumber=254292&KeyType=LandRegistryFreehold&KeyValue=254292",
      "title_number": "254292",
      "id": "5D0FA4909B7C0FD9477C2275E1948C8F135E233F"
    }
  ],
  "signatures": [
    {
      "signature_hpid": {
        "value": "ef4a09c1-ce37-bb86-5cbe-3dce5545ab01",
        "link": "/SignatureHPID/ef4a09c1-ce37-bb86-5cbe-3dce5545ab01"
      },
      "building_name": null,
      "start_number": "7A",
      "end_number": null,
      "usrn": {
        "value": "22700051",
        "link": "/Street/22700051"
      },
      "street": "AGNES ST",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "609052095",
          "link": "/SignatureKey/BuildingPolygon/609052095"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000041732883",
          "link": "/SignatureKey/Ext.Toid/osgb1000041732883"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "254292",
          "link": "/SignatureKey/LandRegistryFreehold/254292"
        },
        {
          "key": "Postcode",
          "value": "E14 7DG",
          "link": "/SignatureKey/Postcode/E14 7DG"
        },
        {
          "key": "TopUPRN",
          "value": "6089966",
          "link": "/SignatureKey/TopUPRN/6089966"
        }
      ]
    },
    {
      "signature_hpid": {
        "value": "52030606-2245-be90-d050-a830aed950b1",
        "link": "/SignatureHPID/52030606-2245-be90-d050-a830aed950b1"
      },
      "building_name": null,
      "start_number": "7B",
      "end_number": null,
      "usrn": {
        "value": "22700051",
        "link": "/Street/22700051"
      },
      "street": "AGNES ST",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "609052095",
          "link": "/SignatureKey/BuildingPolygon/609052095"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000041732883",
          "link": "/SignatureKey/Ext.Toid/osgb1000041732883"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "254292",
          "link": "/SignatureKey/LandRegistryFreehold/254292"
        },
        {
          "key": "Postcode",
          "value": "E14 7DG",
          "link": "/SignatureKey/Postcode/E14 7DG"
        },
        {
          "key": "TopUPRN",
          "value": "6146873",
          "link": "/SignatureKey/TopUPRN/6146873"
        }
      ]
    },
    {
      "signature_hpid": {
        "value": "47673024-ea82-a40a-5c5d-d05825ea8547",
        "link": "/SignatureHPID/47673024-ea82-a40a-5c5d-d05825ea8547"
      },
      "building_name": null,
      "start_number": "7",
      "end_number": null,
      "usrn": {
        "value": "22700051",
        "link": "/Street/22700051"
      },
      "street": "AGNES ST",
      "keys": [
        {
          "key": "BuildingPolygon",
          "value": "609052095",
          "link": "/SignatureKey/BuildingPolygon/609052095"
        },
        {
          "key": "Ext.Toid",
          "value": "osgb1000041732883",
          "link": "/SignatureKey/Ext.Toid/osgb1000041732883"
        },
        {
          "key": "LandRegistryFreehold",
          "value": "254292",
          "link": "/SignatureKey/LandRegistryFreehold/254292"
        },
        {
          "key": "Postcode",
          "value": "E14 7DG",
          "link": "/SignatureKey/Postcode/E14 7DG"
        },
        {
          "key": "TopUPRN",
          "value": "6044926",
          "link": "/SignatureKey/TopUPRN/6044926"
        }
      ]
    }
  ],
  "internals": [
    {
      "signature_hpid": "47673024-ea82-a40a-5c5d-d05825ea8547",
      "internal_hpid": "117d268e-23de-c05c-ee38-6f3382d638e5",
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
      "keys": "LandRegistryFreehold:254292,LandRegistryLeasehold:100462,UPRN:6044926",
      "signature": " 7 AGNES ST"
    },
    {
      "signature_hpid": "ef4a09c1-ce37-bb86-5cbe-3dce5545ab01",
      "internal_hpid": "f8b2a6f4-a431-9ea4-b1ab-f2bd15944242",
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
      "keys": "EpcDomestic:400930609402019113016172578017708,EpcDomestic:400930682012009112013144500919774,LandRegistryFreehold:254292,LandRegistryLeasehold:100462,LandRegistryLeasehold:EGL351900,LandRegistryPricePaid:2a289e9d-9cd3-cdc8-e050-a8c063054829,LandRegistryPricePaid:cb2b0d0a-e2c5-4835-b5d0-9223db475cba,UPRN:6089966",
      "signature": " 7A AGNES ST"
    },
    {
      "signature_hpid": "52030606-2245-be90-d050-a830aed950b1",
      "internal_hpid": "45777553-2106-374d-1df2-f36bd329bf9c",
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
      "keys": "LandRegistryFreehold:254292,LandRegistryLeasehold:100462,LandRegistryPricePaid:819f6851-4d9b-497b-9be1-166f72d20b2a,LandRegistryPricePaid:b4915456-c6db-404a-8524-d94701aadc92,UPRN:6146873",
      "signature": " 7B AGNES ST"
    }
  ],
  "no_signatures": []
}
    ```
