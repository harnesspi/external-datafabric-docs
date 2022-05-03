# Organisation


## GET /organisation/{parameterOrganisationHPID}
### Response 200 (application/json)
Content: [OrganisationResponse](OrganisationResponse.md)

#### Example 1
```
/Organisation/D7F187B1-EFDB-FC7F-CAB9-333789D6534A
```
```json
{
  "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
  "normalised_organisation": "NOTTING HILL HOME OWNERSHIP LTD",
  "significant_organisation_hpid": "d99939c1-3367-9fdc-e92a-d9779bf07291",
  "significant_organisation": "NOTTING OWNERSHIP",
  "company_number": "IP23066R",
  "is_companies_house": "1",
  "is_other_source": "1",
  "exact_name_sources": [
    {
      "source_hpid": "2090caf7-c507-eb2e-13b5-0029c7c07964",
      "source_name": "ABP",
      "row_key": "2090caf7-c507-eb2e-13b5-0029c7c07964",
      "registration_number": null,
      "country_registered": null,
      "postcode": "SE17 3DW",
      "url_query": {
        "key": "ABP",
        "value": "2090caf7-c507-eb2e-13b5-0029c7c07964",
        "link": "/Address/2090CAF7-C507-EB2E-13B5-0029C7C07964"
      }
    },
    {
      "source_hpid": "a6fc7781-a002-f76e-e90a-974eced5df97",
      "source_name": "ABP",
      "row_key": "a6fc7781-a002-f76e-e90a-974eced5df97",
      "registration_number": null,
      "country_registered": null,
      "postcode": "TW12 1QQ",
      "url_query": {
        "key": "ABP",
        "value": "a6fc7781-a002-f76e-e90a-974eced5df97",
        "link": "/Address/A6FC7781-A002-F76E-E90A-974ECED5DF97"
      }
    },
    {
      "source_hpid": "9f8dfcdc-f9f1-90ac-f4aa-2790d34273d0",
      "source_name": "Companies House",
      "row_key": "IP23066R",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Companies House",
        "value": "IP23066R",
        "link": "/Company/IP23066R"
      }
    },
    {
      "source_hpid": "eec15bf5-3b35-ad33-3707-4f05beb480f9",
      "source_name": "Company Appointments",
      "row_key": "Snapshot|22318789",
      "registration_number": "208242780001",
      "country_registered": null,
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Company Appointments",
        "value": "Snapshot|22318789",
        "link": "/CompanyAppointment/Snapshot/22318789"
      }
    },
    {
      "source_hpid": "b7189bbe-9041-dd60-fef0-ba149ee0c4f9",
      "source_name": "Company Appointments",
      "row_key": "Snapshot|22364323",
      "registration_number": "208242780001",
      "country_registered": null,
      "postcode": "W6 8DL",
      "url_query": {
        "key": "Company Appointments",
        "value": "Snapshot|22364323",
        "link": "/CompanyAppointment/Snapshot/22364323"
      }
    },
    {
      "source_hpid": "d99214b4-8d01-2e38-e572-70adca2a9b2e",
      "source_name": "Company Appointments",
      "row_key": "Snapshot|22579176",
      "registration_number": "208242780001",
      "country_registered": null,
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Company Appointments",
        "value": "Snapshot|22579176",
        "link": "/CompanyAppointment/Snapshot/22579176"
      }
    },
    {
      "source_hpid": "aaea88a8-a4ca-acc1-4558-664bf17e1a4e",
      "source_name": "Company Appointments",
      "row_key": "Snapshot|5013883",
      "registration_number": "208242780001",
      "country_registered": null,
      "postcode": "W6 0JL",
      "url_query": {
        "key": "Company Appointments",
        "value": "Snapshot|5013883",
        "link": "/CompanyAppointment/Snapshot/5013883"
      }
    },
    {
      "source_hpid": "5faa1a14-7083-5b6e-ce8b-c27e0713873e",
      "source_name": "Experian Shop Point Group",
      "row_key": "20913462636",
      "registration_number": null,
      "country_registered": null,
      "postcode": "NG20 9PZ",
      "url_query": {
        "key": "Experian Shop Point Group",
        "value": "20913462636",
        "link": "/ExperianShopPoint/20913462636"
      }
    },
    {
      "source_hpid": "a41b98b7-7ef7-a454-bea3-af6f9614f1ab",
      "source_name": "Land Registry Title Owners",
      "row_key": "0063fce8-c673-f31d-c204-d9c78f3d5661",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "0063fce8-c673-f31d-c204-d9c78f3d5661",
        "link": "/LandRegistryTitleOwner/0063fce8-c673-f31d-c204-d9c78f3d5661/598f9c69-beda-761e-9028-cb3052e6e3f8"
      }
    },
    {
      "source_hpid": "5f8b9252-88d0-0fc0-40ec-3e0da4fcb981",
      "source_name": "Land Registry Title Owners",
      "row_key": "00c75821-2862-0bd8-7a29-711372f906b6",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "00c75821-2862-0bd8-7a29-711372f906b6",
        "link": "/LandRegistryTitleOwner/00c75821-2862-0bd8-7a29-711372f906b6/721b6d58-56e8-a641-532d-ed17e716be0b"
      }
    },
    {
      "source_hpid": "e287d345-85a3-a21f-4d64-0e7022a1a477",
      "source_name": "Land Registry Title Owners",
      "row_key": "0410d34d-b866-e54f-89c3-82369acaf012",
      "registration_number": "IP232066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "0410d34d-b866-e54f-89c3-82369acaf012",
        "link": "/LandRegistryTitleOwner/0410d34d-b866-e54f-89c3-82369acaf012/685130ed-b589-b3a0-467b-6790c6a51147"
      }
    },
    {
      "source_hpid": "0c3979a6-1af0-dbeb-109c-a1e90401384a",
      "source_name": "Land Registry Title Owners",
      "row_key": "065b1eab-0817-0079-ceb0-7d199b9c623f",
      "registration_number": null,
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "065b1eab-0817-0079-ceb0-7d199b9c623f",
        "link": "/LandRegistryTitleOwner/065b1eab-0817-0079-ceb0-7d199b9c623f/93bce725-0c7f-549c-c832-07a352ecfd1d"
      }
    },
    {
      "source_hpid": "55570cba-0cfa-8fa7-3435-246ae8b2644c",
      "source_name": "Land Registry Title Owners",
      "row_key": "0d93effe-7d9d-fede-232b-30755ec2bef2",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "0d93effe-7d9d-fede-232b-30755ec2bef2",
        "link": "/LandRegistryTitleOwner/0d93effe-7d9d-fede-232b-30755ec2bef2/0440a9df-858a-6270-9c15-1da56dc41332"
      }
    },
    {
      "source_hpid": "61c4033b-e570-4ef4-5f76-2a44feab1563",
      "source_name": "Land Registry Title Owners",
      "row_key": "29f11825-7699-f8ec-b0f7-331c920b84b5",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "29f11825-7699-f8ec-b0f7-331c920b84b5",
        "link": "/LandRegistryTitleOwner/29f11825-7699-f8ec-b0f7-331c920b84b5/0339ff4f-69cb-20d8-3e1a-4a739d702c9f"
      }
    },
    {
      "source_hpid": "29459921-02a1-c350-a679-6bbbe838b327",
      "source_name": "Land Registry Title Owners",
      "row_key": "2b4e809f-ca83-a15c-ed21-ee0ff8893e7e",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "2b4e809f-ca83-a15c-ed21-ee0ff8893e7e",
        "link": "/LandRegistryTitleOwner/2b4e809f-ca83-a15c-ed21-ee0ff8893e7e/ae651350-2154-0fb3-40f8-126883c3a7a4"
      }
    },
    {
      "source_hpid": "bc21c4e0-1000-99e6-9063-d58e0788db11",
      "source_name": "Land Registry Title Owners",
      "row_key": "319aad12-d2e6-5502-1e7f-cd131f634ca5",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "319aad12-d2e6-5502-1e7f-cd131f634ca5",
        "link": "/LandRegistryTitleOwner/319aad12-d2e6-5502-1e7f-cd131f634ca5/0440a9df-858a-6270-9c15-1da56dc41332"
      }
    },
    {
      "source_hpid": "80985b2d-c310-59fc-b023-198c32bda558",
      "source_name": "Land Registry Title Owners",
      "row_key": "320645fd-c36e-e0bf-2fae-e1f76c089611",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "320645fd-c36e-e0bf-2fae-e1f76c089611",
        "link": "/LandRegistryTitleOwner/320645fd-c36e-e0bf-2fae-e1f76c089611/cc77b70f-c7bd-eb8c-98db-5e4d289cdd00"
      }
    },
    {
      "source_hpid": "74cc83af-cfd4-85a3-037e-e18a9d422d62",
      "source_name": "Land Registry Title Owners",
      "row_key": "38858f21-bded-054a-a7e0-03e1910687ec",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "38858f21-bded-054a-a7e0-03e1910687ec",
        "link": "/LandRegistryTitleOwner/38858f21-bded-054a-a7e0-03e1910687ec/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "14235a76-0956-5175-b2f7-b0606c4be409",
      "source_name": "Land Registry Title Owners",
      "row_key": "40af0e3d-a3ca-b7e2-3d63-b6824cee7540",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "40af0e3d-a3ca-b7e2-3d63-b6824cee7540",
        "link": "/LandRegistryTitleOwner/40af0e3d-a3ca-b7e2-3d63-b6824cee7540/36200fa8-f381-d163-3b42-0364fbdca8ce"
      }
    },
    {
      "source_hpid": "e0a06530-9b64-6cf0-d9e6-1b1fb1a5dda3",
      "source_name": "Land Registry Title Owners",
      "row_key": "4331ca49-6455-ce66-7dff-ccdb3f41fabb",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "4331ca49-6455-ce66-7dff-ccdb3f41fabb",
        "link": "/LandRegistryTitleOwner/4331ca49-6455-ce66-7dff-ccdb3f41fabb/ae651350-2154-0fb3-40f8-126883c3a7a4"
      }
    },
    {
      "source_hpid": "355ff76d-4320-4a4a-f32c-3de45fd0331c",
      "source_name": "Land Registry Title Owners",
      "row_key": "475125f1-b22c-fe00-b0e8-18a35611101b",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "475125f1-b22c-fe00-b0e8-18a35611101b",
        "link": "/LandRegistryTitleOwner/475125f1-b22c-fe00-b0e8-18a35611101b/ae651350-2154-0fb3-40f8-126883c3a7a4"
      }
    },
    {
      "source_hpid": "40a3e998-f14d-e0d4-b81b-1624d366762b",
      "source_name": "Land Registry Title Owners",
      "row_key": "4a9336a7-3156-743d-4377-99a8e30e6a16",
      "registration_number": "IP16558R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "4a9336a7-3156-743d-4377-99a8e30e6a16",
        "link": "/LandRegistryTitleOwner/4a9336a7-3156-743d-4377-99a8e30e6a16/1c2f6427-a5ba-bcaf-0031-d9951bef29d9"
      }
    },
    {
      "source_hpid": "3417d0da-48e0-f747-91d5-6bcfad2745b6",
      "source_name": "Land Registry Title Owners",
      "row_key": "4f667d93-8dad-b25a-3738-fdadb7881d67",
      "registration_number": null,
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "4f667d93-8dad-b25a-3738-fdadb7881d67",
        "link": "/LandRegistryTitleOwner/4f667d93-8dad-b25a-3738-fdadb7881d67/7b211a52-32f9-d9bb-bbb8-fa7d7e467f62"
      }
    },
    {
      "source_hpid": "faa24265-9df0-1410-f3c4-b0ec0e4d4ebe",
      "source_name": "Land Registry Title Owners",
      "row_key": "5279ca6a-9683-3513-e096-b881980d1e14",
      "registration_number": "IPSNOIP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "5279ca6a-9683-3513-e096-b881980d1e14",
        "link": "/LandRegistryTitleOwner/5279ca6a-9683-3513-e096-b881980d1e14/f10c0da1-8bee-2a4c-98bd-5b21d6781a73"
      }
    },
    {
      "source_hpid": "d503dd9b-02f6-398c-f4ea-e4c9a787c033",
      "source_name": "Land Registry Title Owners",
      "row_key": "59d179a4-5bf4-c51b-8eef-723ce0764083",
      "registration_number": "IP16558R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "59d179a4-5bf4-c51b-8eef-723ce0764083",
        "link": "/LandRegistryTitleOwner/59d179a4-5bf4-c51b-8eef-723ce0764083/07042fca-3874-324a-ffc2-add66f49450e"
      }
    },
    {
      "source_hpid": "df8e629b-175a-4fb9-d393-7c1cb7b0a3cd",
      "source_name": "Land Registry Title Owners",
      "row_key": "63fef6f9-36ff-a71f-1047-385ac6a41fee",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "63fef6f9-36ff-a71f-1047-385ac6a41fee",
        "link": "/LandRegistryTitleOwner/63fef6f9-36ff-a71f-1047-385ac6a41fee/598f9c69-beda-761e-9028-cb3052e6e3f8"
      }
    },
    {
      "source_hpid": "8bdd69da-4afb-ec2b-aec7-593ac7c50b00",
      "source_name": "Land Registry Title Owners",
      "row_key": "653a3eb6-7d26-9cce-3410-6c026017dd48",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "653a3eb6-7d26-9cce-3410-6c026017dd48",
        "link": "/LandRegistryTitleOwner/653a3eb6-7d26-9cce-3410-6c026017dd48/a92508f3-8e4c-9dbe-2437-a5bfcc22cf57"
      }
    },
    {
      "source_hpid": "b99fc742-3485-c4aa-de39-1c6dfa22b5ee",
      "source_name": "Land Registry Title Owners",
      "row_key": "712bde56-5e7e-7553-6aa5-651af122f2c8",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "712bde56-5e7e-7553-6aa5-651af122f2c8",
        "link": "/LandRegistryTitleOwner/712bde56-5e7e-7553-6aa5-651af122f2c8/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "00bb3026-db0a-22c3-5e96-cd50d8717d6f",
      "source_name": "Land Registry Title Owners",
      "row_key": "74709e16-1395-eda7-f34c-e31ff6a68921",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "74709e16-1395-eda7-f34c-e31ff6a68921",
        "link": "/LandRegistryTitleOwner/74709e16-1395-eda7-f34c-e31ff6a68921/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "4849a024-b7f2-4530-3a2a-703e6aa81bba",
      "source_name": "Land Registry Title Owners",
      "row_key": "878bc30b-dfc8-f54a-f8a9-46b02abfa15b",
      "registration_number": "IPR23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "878bc30b-dfc8-f54a-f8a9-46b02abfa15b",
        "link": "/LandRegistryTitleOwner/878bc30b-dfc8-f54a-f8a9-46b02abfa15b/0c6019c9-c647-14a1-cccd-941791b80f92"
      }
    },
    {
      "source_hpid": "639fbf37-bc3e-420e-808f-631eae5a0a91",
      "source_name": "Land Registry Title Owners",
      "row_key": "96460343-ba2d-d2a5-22a2-29d3ef81bf0b",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "96460343-ba2d-d2a5-22a2-29d3ef81bf0b",
        "link": "/LandRegistryTitleOwner/96460343-ba2d-d2a5-22a2-29d3ef81bf0b/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "185c1c0c-fb0b-4084-3efc-5c96353f3d09",
      "source_name": "Land Registry Title Owners",
      "row_key": "a638e9e7-ab08-83fc-3396-e64b1c71e4bc",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "a638e9e7-ab08-83fc-3396-e64b1c71e4bc",
        "link": "/LandRegistryTitleOwner/a638e9e7-ab08-83fc-3396-e64b1c71e4bc/0440a9df-858a-6270-9c15-1da56dc41332"
      }
    },
    {
      "source_hpid": "b01db397-5df1-337a-b595-8d36f3305275",
      "source_name": "Land Registry Title Owners",
      "row_key": "af407d62-45a1-6808-1145-bd6207e5d744",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "af407d62-45a1-6808-1145-bd6207e5d744",
        "link": "/LandRegistryTitleOwner/af407d62-45a1-6808-1145-bd6207e5d744/36200fa8-f381-d163-3b42-0364fbdca8ce"
      }
    },
    {
      "source_hpid": "0a598cb7-2389-99b1-48a4-0b1e47bc1742",
      "source_name": "Land Registry Title Owners",
      "row_key": "bc119e61-f712-cbf9-e4bd-aa05a65e5ba9",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "bc119e61-f712-cbf9-e4bd-aa05a65e5ba9",
        "link": "/LandRegistryTitleOwner/bc119e61-f712-cbf9-e4bd-aa05a65e5ba9/edbb0fb4-2cec-631d-763d-1b9a7ee6f0aa"
      }
    },
    {
      "source_hpid": "1f447b70-cb0d-384d-298c-8342f8ddd566",
      "source_name": "Land Registry Title Owners",
      "row_key": "be17251e-82c4-1702-f69b-be59fc338d78",
      "registration_number": null,
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "be17251e-82c4-1702-f69b-be59fc338d78",
        "link": "/LandRegistryTitleOwner/be17251e-82c4-1702-f69b-be59fc338d78/5b630412-ad72-babb-2242-049d429fcec9"
      }
    },
    {
      "source_hpid": "0f62e57f-abea-d8d6-8091-6100665fe72b",
      "source_name": "Land Registry Title Owners",
      "row_key": "c33f852e-dce0-e7d7-8f2b-ddc9f33d2b09",
      "registration_number": null,
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "c33f852e-dce0-e7d7-8f2b-ddc9f33d2b09",
        "link": "/LandRegistryTitleOwner/c33f852e-dce0-e7d7-8f2b-ddc9f33d2b09/e19a0eef-b747-b93b-e316-a0dfe39ab5dc"
      }
    },
    {
      "source_hpid": "3eabdc92-c191-a071-ebf4-8d8693ec427d",
      "source_name": "Land Registry Title Owners",
      "row_key": "cbd3fa10-d39e-b976-069d-f8bca1c332fd",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "cbd3fa10-d39e-b976-069d-f8bca1c332fd",
        "link": "/LandRegistryTitleOwner/cbd3fa10-d39e-b976-069d-f8bca1c332fd/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "5b9d7522-7499-22c2-d89e-056c2bc2fcd1",
      "source_name": "Land Registry Title Owners",
      "row_key": "cc01d1f9-3b7c-0d08-f2d7-4cc7308dc09b",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "cc01d1f9-3b7c-0d08-f2d7-4cc7308dc09b",
        "link": "/LandRegistryTitleOwner/cc01d1f9-3b7c-0d08-f2d7-4cc7308dc09b/36200fa8-f381-d163-3b42-0364fbdca8ce"
      }
    },
    {
      "source_hpid": "9e65e75f-76d8-008e-d53b-e43f0f8a8573",
      "source_name": "Land Registry Title Owners",
      "row_key": "cc15493b-7b48-b718-ba6c-b4898ab3340d",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "cc15493b-7b48-b718-ba6c-b4898ab3340d",
        "link": "/LandRegistryTitleOwner/cc15493b-7b48-b718-ba6c-b4898ab3340d/80123cc3-4350-9fdf-b755-0106b954e308"
      }
    },
    {
      "source_hpid": "48084b67-fab2-2694-930a-af56502a63b5",
      "source_name": "Land Registry Title Owners",
      "row_key": "ebfd3c24-96e4-1d40-4df2-0881c6bec4ce",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "ebfd3c24-96e4-1d40-4df2-0881c6bec4ce",
        "link": "/LandRegistryTitleOwner/ebfd3c24-96e4-1d40-4df2-0881c6bec4ce/e5c26784-1451-16db-7bc6-693042d969b6"
      }
    },
    {
      "source_hpid": "511a9670-0ac9-261e-876d-f90c8e3c9aa8",
      "source_name": "Land Registry Title Owners",
      "row_key": "ed2964c5-8769-7792-a1f7-af3e53239881",
      "registration_number": "IPNO23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "ed2964c5-8769-7792-a1f7-af3e53239881",
        "link": "/LandRegistryTitleOwner/ed2964c5-8769-7792-a1f7-af3e53239881/6ac3ae5d-d19c-8e15-19ca-2c135df42163"
      }
    },
    {
      "source_hpid": "9c93b3eb-c959-bead-34d8-f4c8615a2126",
      "source_name": "Land Registry Title Owners",
      "row_key": "f1703db1-8f45-2822-7757-d4f39a310071",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "f1703db1-8f45-2822-7757-d4f39a310071",
        "link": "/LandRegistryTitleOwner/f1703db1-8f45-2822-7757-d4f39a310071/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "36a35ab9-915a-6eac-ab3a-ecc783cdb08f",
      "source_name": "Land Registry Title Owners",
      "row_key": "f400582b-b497-12ae-ef5b-d8a7aed59493",
      "registration_number": "23066RR",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "f400582b-b497-12ae-ef5b-d8a7aed59493",
        "link": "/LandRegistryTitleOwner/f400582b-b497-12ae-ef5b-d8a7aed59493/6f34a66e-bc0a-d304-c582-7be42c62d19f"
      }
    },
    {
      "source_hpid": "bcc9f172-b021-4b45-6b53-b05f7a894730",
      "source_name": "Land Registry Title Owners",
      "row_key": "f5f9982f-c96c-302c-f37c-6fb3f7823180",
      "registration_number": "IP23660R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "f5f9982f-c96c-302c-f37c-6fb3f7823180",
        "link": "/LandRegistryTitleOwner/f5f9982f-c96c-302c-f37c-6fb3f7823180/170e7663-9ad6-ad0a-8249-117cf206f7a2"
      }
    },
    {
      "source_hpid": "9476df81-1ffc-b7be-bd4d-cbf995317c64",
      "source_name": "Land Registry Title Owners",
      "row_key": "f88a0fc9-758b-7ddc-0be3-35f79195a24c",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "f88a0fc9-758b-7ddc-0be3-35f79195a24c",
        "link": "/LandRegistryTitleOwner/f88a0fc9-758b-7ddc-0be3-35f79195a24c/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "659ff7ce-a2c0-77cb-f2e4-5e60e4aa29c8",
      "source_name": "Land Registry Title Owners",
      "row_key": "fa4be41a-18ef-0aeb-58da-80f852f2b8a9",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "fa4be41a-18ef-0aeb-58da-80f852f2b8a9",
        "link": "/LandRegistryTitleOwner/fa4be41a-18ef-0aeb-58da-80f852f2b8a9/ae651350-2154-0fb3-40f8-126883c3a7a4"
      }
    },
    {
      "source_hpid": "6fbda74a-bfca-77ae-623e-0c3e655bf99b",
      "source_name": "Land Registry Title Owners",
      "row_key": "fef035a0-4f02-d084-e6de-68dd36cdef76",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "fef035a0-4f02-d084-e6de-68dd36cdef76",
        "link": "/LandRegistryTitleOwner/fef035a0-4f02-d084-e6de-68dd36cdef76/fb2b38f2-a92a-b50a-81f8-7ebcba81d5dc"
      }
    },
    {
      "source_hpid": "2d42211b-59ee-e334-8d61-fbc0b4151217",
      "source_name": "Land Registry Title Owners",
      "row_key": "ffd2433b-ed96-b477-4ce5-17ce985c9993",
      "registration_number": "23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "ffd2433b-ed96-b477-4ce5-17ce985c9993",
        "link": "/LandRegistryTitleOwner/ffd2433b-ed96-b477-4ce5-17ce985c9993/66820c22-bad3-ab0b-3d37-5aa7a645bc2d"
      }
    },
    {
      "source_hpid": "60f56392-71c6-19b8-e7f2-a62547345163",
      "source_name": "Land Registry Title Owners",
      "row_key": "fff65412-0f15-0f71-cb5e-4ca7be74f159",
      "registration_number": "IP23066R",
      "country_registered": "UK",
      "postcode": null,
      "url_query": {
        "key": "Land Registry Title Owners",
        "value": "fff65412-0f15-0f71-cb5e-4ca7be74f159",
        "link": "/LandRegistryTitleOwner/fff65412-0f15-0f71-cb5e-4ca7be74f159/81427b00-b429-2fb7-4758-a9cd54021944"
      }
    },
    {
      "source_hpid": "8fa02bb8-8963-b39c-5bb0-8cb2758d7a5d",
      "source_name": "Persons With Significant Control",
      "row_key": "0a57384d3a7ee783cd47a5628fefd37f61a3fb56",
      "registration_number": "Ip23066r",
      "country_registered": "United Kingdom",
      "postcode": "W6 8DL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "0a57384d3a7ee783cd47a5628fefd37f61a3fb56",
        "link": "/PersonWithSignificantControl/0a57384d3a7ee783cd47a5628fefd37f61a3fb56"
      }
    },
    {
      "source_hpid": "a48481d9-a63c-c027-48c7-1b8a5687de08",
      "source_name": "Persons With Significant Control",
      "row_key": "1f4c756525d67232118988c48537ef762e23cca4",
      "registration_number": "Ip23066r",
      "country_registered": "England",
      "postcode": "W6 8DL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "1f4c756525d67232118988c48537ef762e23cca4",
        "link": "/PersonWithSignificantControl/1f4c756525d67232118988c48537ef762e23cca4"
      }
    },
    {
      "source_hpid": "b814675c-c823-28cb-f7fe-f04667f930c8",
      "source_name": "Persons With Significant Control",
      "row_key": "215be2ec443b6d0b0c0da63cfe2b03ff0c00ad81",
      "registration_number": "23066r",
      "country_registered": "England",
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "215be2ec443b6d0b0c0da63cfe2b03ff0c00ad81",
        "link": "/PersonWithSignificantControl/215be2ec443b6d0b0c0da63cfe2b03ff0c00ad81"
      }
    },
    {
      "source_hpid": "f5f0af10-c00c-4d5b-76f2-b72639b52d58",
      "source_name": "Persons With Significant Control",
      "row_key": "40708983aaeab9d73327ffc01d479b30eeac8a89",
      "registration_number": "23066r",
      "country_registered": "England",
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "40708983aaeab9d73327ffc01d479b30eeac8a89",
        "link": "/PersonWithSignificantControl/40708983aaeab9d73327ffc01d479b30eeac8a89"
      }
    },
    {
      "source_hpid": "b63149bb-5c2e-7d70-b54a-ee7bce825f27",
      "source_name": "Persons With Significant Control",
      "row_key": "4fcb0cc4270b69df74cec517b38bda66d362b39b",
      "registration_number": "Ip23066r",
      "country_registered": "England",
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "4fcb0cc4270b69df74cec517b38bda66d362b39b",
        "link": "/PersonWithSignificantControl/4fcb0cc4270b69df74cec517b38bda66d362b39b"
      }
    },
    {
      "source_hpid": "5ef1b897-f711-cee7-aad6-12aaf6226b52",
      "source_name": "Persons With Significant Control",
      "row_key": "50fd42880eb08f839ab58fc93f8e3127203e279d",
      "registration_number": "23066r",
      "country_registered": "England",
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "50fd42880eb08f839ab58fc93f8e3127203e279d",
        "link": "/PersonWithSignificantControl/50fd42880eb08f839ab58fc93f8e3127203e279d"
      }
    },
    {
      "source_hpid": "0e1f8e39-2948-5183-ee4a-5fa8406eea33",
      "source_name": "Persons With Significant Control",
      "row_key": "b8d6dc5f7858fec84a18a79333feeb8666811afd",
      "registration_number": "Ip23066r",
      "country_registered": "England",
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "b8d6dc5f7858fec84a18a79333feeb8666811afd",
        "link": "/PersonWithSignificantControl/b8d6dc5f7858fec84a18a79333feeb8666811afd"
      }
    },
    {
      "source_hpid": "d8eaafb4-afa1-d128-3b1b-09a1bfb07f24",
      "source_name": "Persons With Significant Control",
      "row_key": "d15f1922d4a5b04aae16276ef1f0c7fad3e6d466",
      "registration_number": "Ip23066r",
      "country_registered": "England And Wales",
      "postcode": "N1 9FL",
      "url_query": {
        "key": "Persons With Significant Control",
        "value": "d15f1922d4a5b04aae16276ef1f0c7fad3e6d466",
        "link": "/PersonWithSignificantControl/d15f1922d4a5b04aae16276ef1f0c7fad3e6d466"
      }
    },
    {
      "source_hpid": "932f5915-1492-af58-fc39-e85e9f94cf77",
      "source_name": "Social Housing Providers",
      "row_key": "SL3119",
      "registration_number": "SL3119",
      "country_registered": null,
      "postcode": null,
      "url_query": {
        "key": "Social Housing Providers",
        "value": "SL3119",
        "link": ""
      }
    }
  ],
  "reg_no_related": [
    {
      "key_type": "CompanyNumber",
      "organisation_hpid": "a417d0a8-c09e-949b-25dc-a77d9a097813",
      "normalised_organisation": "NOTTING HILL OWNERSHIP LTD",
      "reg_nos": "IP23066R"
    },
    {
      "key_type": "LandRegistryTitleOwnersRegNo",
      "organisation_hpid": "8de838c1-1f21-d848-e569-e826faa2f47c",
      "normalised_organisation": "J P C MULLIGAN PROPERTIES LTD",
      "reg_nos": "IP23066R"
    },
    {
      "key_type": "LandRegistryTitleOwnersRegNo",
      "organisation_hpid": "f51211bc-5766-6bcb-7d5d-05976b01f8d6",
      "normalised_organisation": "NOTTING HILL GENESIS",
      "reg_nos": "23066RR"
    },
    {
      "key_type": "LandRegistryTitleOwnersRegNo",
      "organisation_hpid": "54e41df8-ae62-2399-9241-c98a0319fc4b",
      "normalised_organisation": "NOTTING HILL HOUSING TRUST",
      "reg_nos": "IP16558R"
    },
    {
      "key_type": "LandRegistryTitleOwnersRegNo",
      "organisation_hpid": "5d696b59-8efb-1f1f-11ed-7904a6d3bdae",
      "normalised_organisation": "SPRINGBOARD TWO HOUSING ASSOCIATION LTD",
      "reg_nos": "23066R"
    },
    {
      "key_type": "PersonsWithSignificantControlRegNo",
      "organisation_hpid": "845435a0-edd5-9799-70c1-d3ed3d8e63c8",
      "normalised_organisation": "NOTTING HILL HOME OWNERSHIP",
      "reg_nos": "23066r"
    }
  ],
  "keys": [
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "RelevantAddresses",
      "key_value": "1AC6A68C-35EC-9415-C127-47BC45E6E153",
      "description": " 36 LIME GROVE",
      "month_of_birth": null
    },
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "RelevantAddresses",
      "key_value": "6C67E36A-394F-A884-5126-9D503B2AA674",
      "description": "GROVE HOUSE, 27 HAMMERSMITH GROVE",
      "month_of_birth": null
    },
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "RelevantAddresses",
      "key_value": "99CCBFC8-1AF3-E5E5-2908-ECB2313DCE92",
      "description": "BRUCE KENRICK HOUSE, KILLICK ST",
      "month_of_birth": null
    },
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "RelevantAddresses",
      "key_value": "E70C1F5F-5E23-8B7C-E007-40D9EF42061D",
      "description": "ST CLARE HOUSE, HOLLY RD",
      "month_of_birth": null
    },
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "RelevantAddresses",
      "key_value": "F7913844-FBB1-5FE7-DD73-A24234C6CCEB",
      "description": " 2 KILLICK ST",
      "month_of_birth": null
    },
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "SignificantOrganisation",
      "key_value": "D99939C1-3367-9FDC-E92A-D9779BF07291",
      "description": "NOTTING OWNERSHIP",
      "month_of_birth": null
    },
    {
      "organisation_hpid": "d7f187b1-efdb-fc7f-cab9-333789d6534a",
      "key_type": "SignificantOrganisationPostcode",
      "key_value": "D99939C1-3367-9FDC-E92A-D9779BF07291|N1 9FL",
      "description": "NOTTING OWNERSHIP + N1 9FL",
      "month_of_birth": null
    }
  ],
  "organisation_titles": [
    {
      "title_number": "127483",
      "property_address": "79 Ledbury Road, London (W11 2AG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "169355",
      "property_address": "81 Ledbury Road, London (W11 2AG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "192088",
      "property_address": "234, 236 and 240 Upper Tooting Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "196278",
      "property_address": "Carew House, 132 Leigham Court Road, and land lying to the South West of Leigham Court Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "219662",
      "property_address": "62 Brooksby's Walk, London (E9 6DA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "244595",
      "property_address": "73 Mantilla Road, London (SW17 8DY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "254644",
      "property_address": "50 Lawrence's Buildings, Brooke Road, Hackney, (N16 7LQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "259182",
      "property_address": "13 Bruce Road, London (E3 3HN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "260834",
      "property_address": "158 Royal College Street, London (NW1 0TA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "291590",
      "property_address": "13 Chippenham Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "292869",
      "property_address": "18 Dodbrooke Road, West Norwood, (SE27 0PF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "304916",
      "property_address": "Shaftesbury Arms, 38 Shaftesbury Street, London, (N1 7HE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "334583",
      "property_address": "38 St Stephen's Avenue, Shepherds Bush, Hammersmith, (W12 8JH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "355214",
      "property_address": "19 Fountain Road, (SW17 0HG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "405881",
      "property_address": "18 Thrale Road, Streatham, (SW16 1PA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "407127",
      "property_address": "Flats A-D (inc), 100 Edith Grove, Chelsea (SW10 0NH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "424515",
      "property_address": "160 Highlever Road, London (W10 6PJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "425884",
      "property_address": "52 Astbury Road, London (SE15 2NJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "435973",
      "property_address": "2 Mozart Street, London (W10 4LA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "436271",
      "property_address": "24 Hogarth Road, London (SW5 0PT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "44950",
      "property_address": "8 Bonchurch Road, London (W10 5SD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "452683",
      "property_address": "61 Oxford Gardens, London (W10 5UJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "452728",
      "property_address": "98 Cambridge Gardens, London, (W10 6HS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "453165",
      "property_address": "22 Bassett Road, London (W10 6JJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "453861",
      "property_address": "91 Cambridge Gardens, London (W10 6JE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "67092",
      "property_address": "104 Netherwood Road, London (W14 0BQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "9227",
      "property_address": "15 The Avenue, Coulsdon (CR5 2BN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL10027",
      "property_address": "36 Raleigh Road, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL10261",
      "property_address": "3 Pickwick Close, Hounslow (TW4 5ED)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL10287",
      "property_address": "66 Percival Road, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL10421",
      "property_address": "25-37 (odd), Crestwood Way, Hounslow (TW4 5EQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL10453",
      "property_address": "11 Cherry Crescent, Brentford (TW8 8NN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL10936",
      "property_address": "35 Old Oak Road, London and garage 6 (W3 7HW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL111144",
      "property_address": "land on the west side of Dormers Rise, Golf Links Estate, Southall",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL111300",
      "property_address": "127 Carmichael Close, Ruislip, (HA4 6LL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL111461",
      "property_address": "Cheseman Court, Baird Avenue, Rountree Court, 5, 7, 47, 49, 53, 57, 61 and 65 Dormers Rise, Southall",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL111490",
      "property_address": "Land lying to the south-east of London Road, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL11177",
      "property_address": "46 Berry Court, Hounslow (TW4 5EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL114189",
      "property_address": "108 Carmichael Close, Ruislip, (HA4 6LL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL114999",
      "property_address": "68 Carmichael Close, Ruislip, (HA4 6LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL115000",
      "property_address": "69 Carmichael Close, Ruislip, (HA4 6LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL115001",
      "property_address": "70 Carmichael Close, Ruislip",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL115003",
      "property_address": "72 Carmichael Close, Ruislip (HA4 6LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL115004",
      "property_address": "73 Carmichael Close, Ruislip (HA4 6LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL115288",
      "property_address": "99 Carmichael Close, Ruislip, (HA4 6LL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL115418",
      "property_address": "229 High Street, Acton (W3 9BY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL115922",
      "property_address": "96 Carmichael Close, Ruislip, (HA4 6LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL116268",
      "property_address": "22 Linslade Close, Hounslow (TW4 5BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL116269",
      "property_address": "24 Linslade Close, Hounslow (TW4 5BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL116368",
      "property_address": "New Fieldways, Dollis Valley Way, Barnet (EN5 2UL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL116375",
      "property_address": "Broadfields Resource Centre, Springwood Crescent, Broadfields, Edgware (HA8 8FW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL117158",
      "property_address": "6 Eldrick Court, Feltham (TW14 8SG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL11733",
      "property_address": "9 and 10 Hazlitt Close, Feltham (TW13 6QU) and Land on the south side of 2 Hazlitt Close, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL119922",
      "property_address": "Flat 46 Lanacre Avenue, London (NW9 5FN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL119923",
      "property_address": "48 Lanacre Avenue, London (NW9 5FN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL119928",
      "property_address": "56 Lanacre Avenue, London (NW9 5FN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL122171",
      "property_address": "Maple Leaf Court, 62 Bell Road, Hounslow (TW3 3PB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL122854",
      "property_address": "36 Loxwood Close, Feltham (TW14 8SQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL124094",
      "property_address": "2 Filton Close, Hendon, London (NW9 5AQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL125675",
      "property_address": "65 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL125677",
      "property_address": "72 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL125678",
      "property_address": "63 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL125682",
      "property_address": "71 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL125684",
      "property_address": "61 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL125685",
      "property_address": "62 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126283",
      "property_address": "80 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126284",
      "property_address": "82 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126285",
      "property_address": "73 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126286",
      "property_address": "74 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126287",
      "property_address": "75 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126288",
      "property_address": "76 Martlesham Walk, Hendon, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126289",
      "property_address": "77 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL126290",
      "property_address": "78 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL127003",
      "property_address": "8 Sheridan Court, 6 Milton Road, London (W7 1LF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128509",
      "property_address": "55 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128511",
      "property_address": "56 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128512",
      "property_address": "57 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128515",
      "property_address": "60 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128847",
      "property_address": "50 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128848",
      "property_address": "51 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL128851",
      "property_address": "53 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL130630",
      "property_address": "44 Martlesham Walk, Hendon (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL130849",
      "property_address": "Flat 48 Martlesham Walk, Hendon, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL131466",
      "property_address": "31 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL131468",
      "property_address": "33 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL132176",
      "property_address": "40 Lanacre Avenue, London (NW9 5FN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL13323",
      "property_address": "1, 3, 5 and 7 Crestwood Way, Hounslow  (TW4 5EQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL133467",
      "property_address": "11 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133477",
      "property_address": "18 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133510",
      "property_address": "17 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133525",
      "property_address": "21 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133537",
      "property_address": "8 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133555",
      "property_address": "15 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133581",
      "property_address": "25 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133590",
      "property_address": "30 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133597",
      "property_address": "28 Booth House, High Street, Brentwood (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133605",
      "property_address": "29 Booth House, High Street, Brentwood (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL133623",
      "property_address": "14 Booth House, High Street, Brentford (TW8 8LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL137169",
      "property_address": "37 Warmwell Avenue, London (NW9 5DB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL138828",
      "property_address": "28-39 Temeraire Place, Brentford (TW8 0HW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL139898",
      "property_address": "72 Kenley Avenue, London (NW9 5WP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL141341",
      "property_address": "34 Warmwell Avenue, London (NW9 5DB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL141342",
      "property_address": "32 Warmwell Avenue, London (NW9 5DB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL142364",
      "property_address": "22 Holbeach Close, London (NW9 5BB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL142936",
      "property_address": "60 Kenley Avenue, London (NW9 5WP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL142938",
      "property_address": "7 Coningsby Avenue, London (NW9 5BL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL143113",
      "property_address": "17 Boscombe Circus, London (NW9 5EJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL14347",
      "property_address": "57 Morris Road, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL144332",
      "property_address": "4 Warmwell Avenue, London (NW9 5DB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL144398",
      "property_address": "23 Warmwell Avenue, Hendon, London (NW9 5DB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL144502",
      "property_address": "2 Martlesham walk, London (NW9 5FN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL144503",
      "property_address": "3 Martlesham Walk, London (NW9 5FN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL145243",
      "property_address": "17 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL146184",
      "property_address": "27 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL146185",
      "property_address": "29 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL146201",
      "property_address": "25 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL146257",
      "property_address": "49 Kenley Avenue, London (NW9 5WP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL146258",
      "property_address": "47 Kenley Avenue, London (NW9 5WP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL147156",
      "property_address": "22 Warmwell Avenue, London (NW9 5DB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL14903",
      "property_address": "89-91 Grange Road, Hayes (UB3 2RS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL149615",
      "property_address": "7 Martlesham Walk, London (NW9 5BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL150898",
      "property_address": "land on the south west side of Langham Road, Tottenham",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL15095",
      "property_address": "123 Staveley Gardens, Chiswick",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL15140",
      "property_address": "Nine Elms Farm, High Road, Cowley",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL153065",
      "property_address": "Block A, 661 London Road, Isleworth (TW7 4ES)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL15318",
      "property_address": "40 Reservoir Road, Ruislip, Middlesex",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL156036",
      "property_address": "178 to 283 (inclusive) Wooldridge Close, Feltham (TW14 8BY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL15977",
      "property_address": "24a West End Road, Ruislip",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL161281",
      "property_address": "Block B, 661 London Road, Isleworth (TW7 4ES)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL166117",
      "property_address": "305 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166119",
      "property_address": "297 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166120",
      "property_address": "296 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166123",
      "property_address": "334 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166124",
      "property_address": "333 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166125",
      "property_address": "330 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166127",
      "property_address": "318 Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL166130",
      "property_address": "326b Summerwood Road, Isleworth (TW7 7QP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL166132",
      "property_address": "322 Summerwood Road, Isleworth (TW7 7QB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL166147",
      "property_address": "309 Summerwood Road, Isleworth (TW7 7QB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL166149",
      "property_address": "311 Summerwood Road, Isleworth (TW7 7QB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL166152",
      "property_address": "314 Summerwood Road, Isleworth (TW7 7QB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL167837",
      "property_address": "137 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169178",
      "property_address": "138 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169188",
      "property_address": "140 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169489",
      "property_address": "139 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169883",
      "property_address": "131 Wooldridge Close, Feltham, (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169884",
      "property_address": "127 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169885",
      "property_address": "129 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169887",
      "property_address": "132 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169888",
      "property_address": "134 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169901",
      "property_address": "130 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169912",
      "property_address": "125 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169925",
      "property_address": "133 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL169929",
      "property_address": "126 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL170273",
      "property_address": "128 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL171944",
      "property_address": "136 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL172801",
      "property_address": "Marlborough House, Park Lodge Avenue, West Drayton (UB7 9FJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL174631",
      "property_address": "Flat 2, Block B Paragon Site, Boston Park Road, Brentford (TW8 9RN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL176686",
      "property_address": "Flat 4, Block B Paragon Site, Boston Park Road, Brentford (TW8 9RN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL177487",
      "property_address": "Flat 1, Luminosity Court, 49 Drayton Green Road, London (W13 0NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL177522",
      "property_address": "Flat 5, Luminosity Court, 49 Drayton Green Road, London (W13 0NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL178670",
      "property_address": "125 Wooldridge Close, Feltham (TW14 8BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL179378",
      "property_address": "Flat 6, Luminosity Court, 49 Drayton Green Road, London (W13 0NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL179388",
      "property_address": "Flat 7, Luminosity Court, 49 Drayton Green Road, London (W13 0NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL179391",
      "property_address": "Flat 10, Luminosity Court, 49 Drayton Green Road, London (W13 0NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL183560",
      "property_address": "Land lying to the north of Tentelow Lane, Southall",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL184713",
      "property_address": "223 Wooldridge Close, Feltham (TW14 8BJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL18493",
      "property_address": "1 Newstead Court, Byron Way, Northolt (UB5 6BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL19224",
      "property_address": "10 Briarwood Close, Feltham (TW13 4QL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL196112",
      "property_address": "12-26 (inc), Garland House, 30 Park Lodge Avenue, West Drayton (UB7 9FY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL198330",
      "property_address": "Block F1, Porters Way, West Drayton",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL203703",
      "property_address": "1,2,20,21,22,23,24 and 25, Osbury Court, 52 Northolt Road, Harrow (HA2 0DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL204636",
      "property_address": "1 to 11 (inc), Reservoir Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL205991",
      "property_address": "Flat 1, Orchid Court, 171 Granville Road, London (NW2 2BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL205992",
      "property_address": "Flat 2, Orchid Court, 171 Granville Road, London (NW2 2BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL205993",
      "property_address": "Flat 3, Orchid Court, 171 Granville Road, London (NW2 2BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215212",
      "property_address": "Apartment 401, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215222",
      "property_address": "Apartment 403, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215225",
      "property_address": "Apartment 402, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215227",
      "property_address": "Apartment 406, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215231",
      "property_address": "Apartment 407, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215232",
      "property_address": "Apartment 405, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215234",
      "property_address": "Apartment 301, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215235",
      "property_address": "Apartment 302 Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215243",
      "property_address": "Apartment 504, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215245",
      "property_address": "Apartment 505, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215250",
      "property_address": "Apartment 603, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215251",
      "property_address": "Apartment 404, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215258",
      "property_address": "Apartment 203, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215259",
      "property_address": "Apartment 303, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215261",
      "property_address": "Apartment 204, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215273",
      "property_address": "Apartment 307, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215274",
      "property_address": "Apartment 206, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL215275",
      "property_address": "Apartment 207, Gilbert House, Great West Quarter, Ealing Road, Brentford (TW8 0GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL217306",
      "property_address": "Hardy House, Union Lane, Isleworth (TW7 6GU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL218018",
      "property_address": "Flats 1-8 (inclusive), 15, 19-33 (inclusive), 40, and 44-58 (inclusive) Gascoigne Close, Tottenham, London N17 8BA lying within the area shown edged with red on the plan of the above title filed at the Registry",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL218019",
      "property_address": "Flats 1, 2, 4, 6, 7 and 10-16 (inclusive) Sidi Court, Milton Road, Tottenham, London (N15 3DZ) lying within the area shown edged with red on the plan of the above title filed at the Registry",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL218022",
      "property_address": "Flats 1-11 (inclusive) Garwoods Lodge, 421 High Road, Wood Green, London (N22 8JU) lying within the area shown edged with red on the plan of the above title filed at the Registry",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL218124",
      "property_address": "Block AF-12, Ridgemont, Frith Lane, Barnet",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL219200",
      "property_address": "Part of Block B, Paragon Site, Boston Park Road, Brentford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL222732",
      "property_address": "Flats 3, 5, 8, 9 and 17 Sidi Court, Milton Road, Tottenham, London (N15 3DZ) lying within the area shown edged with red on the plan of the above title filed at Land Registry",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL229856",
      "property_address": "Parking Space 31, Paragon Site, Boston Park Road, Brentford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL230618",
      "property_address": "Flat 710, Vantage Building, Station Approach, Hayes (UB3 4FB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL230621",
      "property_address": "Flat 712, Vantage Building, Station Approach, Hayes (UB3 4FB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL230626",
      "property_address": "Flat 716, Vantage Building, Station Approach, Hayes (UB3 4FB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL230627",
      "property_address": "Flat 717, Vantage Building, Station Approach, Hayes (UB3 4FB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL230628",
      "property_address": "Flat 718, Vantage Building, Station Approach, Hayes (UB3 4FB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL230933",
      "property_address": "land lying to the south of Anmer Lodge, Rainsford Close, Stanmore",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL231117",
      "property_address": "116 Clifford Gardens, London (NW10 5JB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL231891",
      "property_address": "Block C, 21 Wapping Lane, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL23835",
      "property_address": "land on the South Side of Crispen Road, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL239697",
      "property_address": "Flat 123, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239699",
      "property_address": "Flat 227, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239701",
      "property_address": "Flat 228, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239705",
      "property_address": "Flat 230, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239706",
      "property_address": "Flat 125, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239707",
      "property_address": "Flat 324, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239708",
      "property_address": "Flat 327, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239709",
      "property_address": "Flat 127, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239712",
      "property_address": "Flat 328, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239715",
      "property_address": "Flat 129, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239716",
      "property_address": "Flat 329, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239717",
      "property_address": "Flat 330, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239723",
      "property_address": "Flat 430, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239724",
      "property_address": "Flat 530, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL239725",
      "property_address": "Flat 529, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL241082",
      "property_address": "Flat 126, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL24296",
      "property_address": "101 Southville Close, Bedfont, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL247764",
      "property_address": "Flat 204, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247767",
      "property_address": "Flat 205, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247769",
      "property_address": "Flat 301, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247771",
      "property_address": "Flat 302, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247775",
      "property_address": "Flat 403, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247776",
      "property_address": "Flat 404, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247778",
      "property_address": "Flat 107, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247780",
      "property_address": "Flat 203, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247781",
      "property_address": "Flat 304, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247787",
      "property_address": "Flat 402, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247789",
      "property_address": "Flat 307, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247791",
      "property_address": "Flat 305, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247795",
      "property_address": "Flat 613, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247797",
      "property_address": "Flat 701, Vantage Building, Station Approach, Hayes (UB3 4FB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247800",
      "property_address": "Flat 606, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247805",
      "property_address": "Flat 406, Vantage Building, Station Approach, Hayes (UB3 4FA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247807",
      "property_address": "Flat 314, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247811",
      "property_address": "Flat 306, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247812",
      "property_address": "Flat 112, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL247823",
      "property_address": "Flat 202, Vantage Building, Station Approach, Hayes (UB3 4BQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL251021",
      "property_address": "Flat 10, Eagle Mansions, Salcombe Road, London (N16 8AU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL253",
      "property_address": "34 Shaftesbury Avenue, Feltham (TW14 9LP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL255606",
      "property_address": "Block B Essex House, 18 Douglas Close, Block C Fulford House, 19 Douglas Close, Block D Fox House, 20 Douglas Close, Block E Thorneycroft House, 21 Douglas Close, Stanmore (HA7 3SP), 1 to 6 (inclusive) Douglas Close and 22 to 31 (inclusive) Douglas Close, Stanmore (HA7 3SP) and car parking spaces",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL25766",
      "property_address": "100 Granville Road (UB10 9AG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL259193",
      "property_address": "Flat 1, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL259197",
      "property_address": "Flat 3, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL259199",
      "property_address": "Flat 4, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL259202",
      "property_address": "Flat 5, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL259209",
      "property_address": "Flat 7, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL259210",
      "property_address": "Flat 8, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL259212",
      "property_address": "Flat 10, Biggs Court, 1 Harvey Close, London (NW9 5WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL263920",
      "property_address": "Land on the north-west side of Seward Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL267",
      "property_address": "69 Eldridge Close, Feltham, (TW14 9NG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL267669",
      "property_address": "Apartment G08, Cordage House, 15 Cobblestone Square, London (E1W 3AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL2760",
      "property_address": "7 Canterbury Road, Hanworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL278401",
      "property_address": "Flats 75-135 (odds), Williams Way, Wembley (HA0 2FP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL281155",
      "property_address": "Plot 5, Block G Holland Estate, Commercial Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282294",
      "property_address": "Plot 2, Block G Holland Estate, Commercial Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282295",
      "property_address": "Plot 3, Block G Holland Estate, Commercial Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282298",
      "property_address": "Flat 6, Sloane Apartments, 54 Old Castle Street, London (E1 7AJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282300",
      "property_address": "Flat 9, Sloane Apartments, 54 Old Castle Street, London (E1 7AJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282307",
      "property_address": "Plot 12, Block G Holland Estate, Commercial Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282312",
      "property_address": "Plot 17, Block G Holland Estate, Commercial Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL282313",
      "property_address": "Plot 18, Block G Holland Estate, Commercial Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL284803",
      "property_address": "1 to 15 (inc) Potash House, 1 Canning Square, 1 to 15 (inc) Mill House, 4 Canning Square, 17 to 39 (odd) and 51 to 87 (odd) Canning Square, and 1 to 26 (inc) Lewis House, 7 Melling Drive, Enfield",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL285093",
      "property_address": "Block D, 21 Wapping Lane, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286503",
      "property_address": "Flat 23, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286508",
      "property_address": "Flat 26, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286509",
      "property_address": "Flat 27, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286512",
      "property_address": "Flat 28, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286515",
      "property_address": "Flat 30, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286516",
      "property_address": "Flat 31, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286517",
      "property_address": "Flat 32, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286519",
      "property_address": "Flat 33, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286521",
      "property_address": "Flat 34, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286525",
      "property_address": "Flat 36, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286529",
      "property_address": "Flat 40, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286531",
      "property_address": "Flat 41, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286533",
      "property_address": "Flat 42, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286537",
      "property_address": "Flat 45, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286541",
      "property_address": "Flat 49, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286543",
      "property_address": "Flat 50, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286544",
      "property_address": "Flat 51, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286545",
      "property_address": "Flat 52, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286546",
      "property_address": "Flat 53, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286548",
      "property_address": "Flat 55, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286549",
      "property_address": "Flat 56, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286550",
      "property_address": "Flat 57, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286551",
      "property_address": "Flat 58, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286552",
      "property_address": "Flat 59, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286554",
      "property_address": "Flat 60, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286555",
      "property_address": "Flat 61, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286556",
      "property_address": "Flat 62, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286558",
      "property_address": "Flat 64, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286559",
      "property_address": "Flat 65, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286560",
      "property_address": "Flat 66, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286561",
      "property_address": "Flat 67, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286562",
      "property_address": "Flat 68, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL286563",
      "property_address": "Flat 69, Frost Court, 1 Salk Close, London (NW9 5XH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL290794",
      "property_address": "units at Malthouse Court, High Street, Brentford (TW8 0FR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL29221",
      "property_address": "1, 1a, 7 and 7a, 21 Argyle Avenue, Whitton and Parking Spaces",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL294600",
      "property_address": "33c Windsor Road, London (W5 3UL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL29558",
      "property_address": "9 Greenford Avenue, London (W7 1LD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL295745",
      "property_address": "Land on the west side of Boulcott Street, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL30423",
      "property_address": "18 Dudley Road, Feltham (TW14 8EH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL31658",
      "property_address": "165 Tivoli Road, Hounslow (TW4 6AS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL316629",
      "property_address": "Parking Space 29, Paragon Site, Boston Park Road, Brentford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318942",
      "property_address": "Apartment 2, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318944",
      "property_address": "Apartment 3, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318947",
      "property_address": "Apartment 4, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318949",
      "property_address": "Apartment 5, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318952",
      "property_address": "Apartment 6, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318953",
      "property_address": "Flat 7, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318959",
      "property_address": "Apartment 8, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318961",
      "property_address": "Apartment 9, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318964",
      "property_address": "Apartment 10, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318994",
      "property_address": "Apartment 11, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318996",
      "property_address": "Flat 12, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL318998",
      "property_address": "Apartment 13, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319001",
      "property_address": "Apartment 14, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319005",
      "property_address": "Apartment 15, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319015",
      "property_address": "Apartment 18, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319019",
      "property_address": "Apartment 20, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319024",
      "property_address": "Apartment 22, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319029",
      "property_address": "Apartment 24, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319033",
      "property_address": "Apartment 26, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL319036",
      "property_address": "Apartment 28, Horizons Tower, 1 Yabsley Street, London (E14 9BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL32167",
      "property_address": "4 Gunnersbury Lane, London (W3 8EB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL32326",
      "property_address": "2 Stirling Grove, Hounslow (TW3 1QG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL32328",
      "property_address": "3 Stirling Grove, Hounslow (TW3 1QG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL32332",
      "property_address": "6 Stirling Grove, Hounslow (TW3 1QG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL32335",
      "property_address": "10 Stirling Grove, Hounslow (TW3 1QG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL333426",
      "property_address": "The Playing Field St George, Headstone, Pinner View, Harrow (HA1 1RJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL333994",
      "property_address": "the first floor flat being Flat 4, Marina Court, 2 Ashridge Close, London, (N3 3AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL333995",
      "property_address": "Parking Space PH4, Ashridge Close, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL334000",
      "property_address": "the first floor flat being Flat 3 Marina Court, 2 Ashridge Close, London (N3 3AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL334135",
      "property_address": "the ground floor flat being Flat 2 Marina Court, 2 Ashridge Close, London (N3 3AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL336184",
      "property_address": "Land on the north side of the broadway and the west side of Dennis Lane, Stanmore",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL3397",
      "property_address": "74 Leybourne Road, Uxbridge (UB10 9HF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL34320",
      "property_address": "17 to 34 Curtis Drive, Westcott Park, Acton and parking spaces (W3 6YL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL346155",
      "property_address": "33 Deacon Road, London (NW2 5NP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL347863",
      "property_address": "92 to 100 (even) Bowes Road, 1 to 5 (inclusive) Lynton Court, Bowes Road and land lying to the north of Bowes Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL34814",
      "property_address": "7 Kingsley Gate, Kingsley Road, Hounslow East and parking space",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL35198",
      "property_address": "1 to 14 (inclusive) Boston Lodge, Windmill Road, London (W5 4BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL35418",
      "property_address": "503-509 Uxbridge Road, Hayes (UB4 8HH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL356470",
      "property_address": "Flats 1 to 24 (inclusive), Waxham Apartments, 44 Bocking Street, London (E8 3FP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL361916",
      "property_address": "Land lying to the north of The Broadway, Stanmore",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL366717",
      "property_address": "12, Duckham Court, Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366724",
      "property_address": "6, Duckham Court, Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366727",
      "property_address": "4, Duckham Court, Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366733",
      "property_address": "Flat 204, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366735",
      "property_address": "Flat 304, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366737",
      "property_address": "Flat 305, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366741",
      "property_address": "Flat 403, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366763",
      "property_address": "Flat 101, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366765",
      "property_address": "Flat 102, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366769",
      "property_address": "Flat 103, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366771",
      "property_address": "Flat 106, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366779",
      "property_address": "Flat 203, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366781",
      "property_address": "Flat 206, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366784",
      "property_address": "Flat 301, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366786",
      "property_address": "Flat 302, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366787",
      "property_address": "Flat 303, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL366790",
      "property_address": "Flat 401, Duckham Court, 8 Nauticus Walk, London (E14 9ZT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL37965",
      "property_address": "7-20 (inc), William Close, Southall (UB2 4UP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL390551",
      "property_address": "4 To 30 (even), Wells Mews, Enfield (N11 2DQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL391914",
      "property_address": "Flat G01, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391917",
      "property_address": "Flat G02, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391919",
      "property_address": "Flat 101, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391921",
      "property_address": "Flat 102, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391923",
      "property_address": "Flat 103, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391925",
      "property_address": "Flat 104, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391927",
      "property_address": "Flat 201, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391929",
      "property_address": "Flat 202, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391930",
      "property_address": "Flat 203, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391931",
      "property_address": "Flat 204, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391933",
      "property_address": "Flat 301, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391935",
      "property_address": "Flat 302, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391936",
      "property_address": "Flat 401, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391938",
      "property_address": "Flat 402, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391940",
      "property_address": "Flat 501, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391942",
      "property_address": "Flat 502, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391945",
      "property_address": "Flat 601, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391948",
      "property_address": "Flat 602, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391950",
      "property_address": "Flat 603, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391951",
      "property_address": "Flat 604, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391953",
      "property_address": "Flat 605, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391955",
      "property_address": "Flat 606, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391957",
      "property_address": "Flat 701, Heritage Tower, 118 East Ferry Road, London (E14 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391959",
      "property_address": "Flat 702, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391961",
      "property_address": "Flat 703, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391963",
      "property_address": "Flat 801, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL391964",
      "property_address": "Flat 1303, 7 Limeharbour, London (E14 9NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL404866",
      "property_address": "17, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL404869",
      "property_address": "Flat 19, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL404872",
      "property_address": "Flat 47, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL404873",
      "property_address": "1 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405001",
      "property_address": "Flat 41, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405006",
      "property_address": "Flat 43, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405007",
      "property_address": "Flat 48, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405011",
      "property_address": "Flat 39, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405174",
      "property_address": "Flat 40, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405175",
      "property_address": "44, Coral Court, 9 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405176",
      "property_address": "Flat 45, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405177",
      "property_address": "Flat 46, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405334",
      "property_address": "Flat 42, Coral Court 9, Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405335",
      "property_address": "Flat 38, Coral Court, 9 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405338",
      "property_address": "23, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405340",
      "property_address": "21, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405527",
      "property_address": "16, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405530",
      "property_address": "18, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405531",
      "property_address": "20, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405534",
      "property_address": "22, Coral Court, 3 Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL405674",
      "property_address": "1a Telford Road, London (N11 2RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL409900",
      "property_address": "34 Coningsby Avenue, London (NW9 5BL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL41156",
      "property_address": "1 Wellington Road North, Hounslow (TW4 7AL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL41879",
      "property_address": "59 Triandra Way, Hayes (UB4 9PB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL42194",
      "property_address": "Shire Place, The Ham, Brentford (TW8 8HE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL423136",
      "property_address": "71 Wrottesley Road, London (NW10 5UD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL423680",
      "property_address": "112 Fishers Way, Wembley (HA0 2FU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL423682",
      "property_address": "110 Fishers Way, Wembley (HA0 2FU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL423684",
      "property_address": "111 Fishers Way, Wembley (HA0 2FU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL423685",
      "property_address": "113 Fishers Way, Wembley (HA0 2FU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL423687",
      "property_address": "109 Fishers Way, Wembley (HA0 2FU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL423688",
      "property_address": "114 Fishers Way, Wembley (HA0 2FU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL42872",
      "property_address": "6, 8, 14, 16, 20, 26, 28, 34 and 36 Porters Way and 31 and 32 Hanson Close, West Drayton",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL430393",
      "property_address": "Phase 1A, Lampton Road, Hounslow",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL430396",
      "property_address": "Phase 1B, Lampton Road, Hounslow",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL432639",
      "property_address": "31 Rowan Close, London (W5 4AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL43332",
      "property_address": "Reynard Mills Trading Estate, Windmill Road, Brentford (TW8 9LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL434577",
      "property_address": "2 to 22 (even), Williams Way, Wembley (HA0 2FR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL439026",
      "property_address": "137-169 (odd), Williams Way, Wembley (HA0 2FT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL439114",
      "property_address": "Land at Phase 1A, Lampton Road, Hounslow",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL44388",
      "property_address": "Flat 2, Frobisher House, Western Avenue, London (W5 1HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL44701",
      "property_address": "59 Hanover Circle, Hayes, (UB3 2TL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL447019",
      "property_address": "Parking Space 15, Paragon Site, Boston Park Road, Brentford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL458035",
      "property_address": "25 Rowan Close, London (W5 4AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL465708",
      "property_address": "Flat 1, 21-22 London Fields East Side, London (E8 3SA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL465719",
      "property_address": "Flat 4, 21-22 London Fields East Side, London (E8 3SA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL469719",
      "property_address": "Blocks E and F Equipment Works, Forest Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL473289",
      "property_address": "Flat 4, 2 St Pauls Avenue, London (NW2 5SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL473920",
      "property_address": "land lying to the south of Western Avenue, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL473923",
      "property_address": "6 Flats block 9 Site, 12 Western Avenue, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL481174",
      "property_address": "1-10,Cassatt Court, and 1-6 Manet Gardens, London (W3 7BW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL48212",
      "property_address": "15 Allenby Close, Greenford, (UB8 9SA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL48313",
      "property_address": "45 Clydesdale Close, Isleworth (TW7 6ST)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL485340",
      "property_address": "Flat F.0.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485344",
      "property_address": "Flat F.0.03, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485346",
      "property_address": "Flat F.0.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485348",
      "property_address": "Flat F.0.06, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485350",
      "property_address": "Flat F.0.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485351",
      "property_address": "Flat F.0.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485353",
      "property_address": "Flat F.1.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485355",
      "property_address": "Flat F.1.02, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485356",
      "property_address": "Flat F.1.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485357",
      "property_address": "Flat F.1.05, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485358",
      "property_address": "Flat F.1.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485359",
      "property_address": "Flat F.1.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485360",
      "property_address": "Flat F.1.09, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485362",
      "property_address": "Flat F.2.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485364",
      "property_address": "Flat F.2.02, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485365",
      "property_address": "Flat F.2.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485418",
      "property_address": "Flat F.2.05, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485419",
      "property_address": "Flat F.2.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485422",
      "property_address": "Flat F.2.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485425",
      "property_address": "Flat F.2.09, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485426",
      "property_address": "Flat F.3.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485427",
      "property_address": "Flat F.3.02, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485429",
      "property_address": "Flat F.3.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485430",
      "property_address": "Flat F.3.05, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485431",
      "property_address": "Flat F.3.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485435",
      "property_address": "Flat F.3.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485436",
      "property_address": "Flat F.3.09, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485437",
      "property_address": "Flat F.3.10, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485438",
      "property_address": "Flat F.4.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485440",
      "property_address": "Flat F.4.02, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485441",
      "property_address": "Flat F.4.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485447",
      "property_address": "Flat F.4.05, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485449",
      "property_address": "Flat F.4.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485450",
      "property_address": "Flat F.4.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485451",
      "property_address": "Flat F.4.09, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485453",
      "property_address": "Flat F.4.10, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485455",
      "property_address": "Flat F.5.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485457",
      "property_address": "Flat F.5.02, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485459",
      "property_address": "Flat F.5.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485461",
      "property_address": "Flat F.5.05, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485463",
      "property_address": "Flat F.5.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485464",
      "property_address": "Flat F.5.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485465",
      "property_address": "Flat F.5.09, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485466",
      "property_address": "Flat F.5.10, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485477",
      "property_address": "Flat F.6.01, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485482",
      "property_address": "Flat F.6.02, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485486",
      "property_address": "Flat F.6.04, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485487",
      "property_address": "Flat F.6.05, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485490",
      "property_address": "Flat F.6.07, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485492",
      "property_address": "Flat F.6.08, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485493",
      "property_address": "Flat F.6.09, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL485495",
      "property_address": "Flat F.6.10, Goodluck Hope, Orchard Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL487769",
      "property_address": "Mahler House, Holst Road, London (W3 0BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL49288",
      "property_address": "248 Westmacott Drive Feltham TW14 9XA",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL49305",
      "property_address": "46 Bankside, Isleworth, (TW7 7EW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL49669",
      "property_address": "100 Shaftesbury Gardens, Acton and parking space",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL49670",
      "property_address": "102 Shaftesbury Gardens, Acton and parking space",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL49672",
      "property_address": "106 Shaftesbury Gardens, Acton and parking space",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL49676",
      "property_address": "105 Shaftesbury Gardens, Acton and parking space",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL504065",
      "property_address": "Land lying to the east of Reynard Way, Brentford",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL51092",
      "property_address": "Flats 1-14 (inc) Gardner Court, Bath Road, Hounslow (TW3 3BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL51656",
      "property_address": "Bordeston Court, The Ham, Brentford (TW8 8HW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL518829",
      "property_address": "Flat 2, Hartingtons Court, Coster Avenue, London (N4 2WL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518831",
      "property_address": "Flat 77, Hartingtons Court, Coster Avenue, London (N4 2WL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518832",
      "property_address": "Flat 78, Hartingtons Court, Coster Avenue, London (N4 2WL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518835",
      "property_address": "Flat 128, Hartingtons Court, Scrimgoeur Place, London (N4 2ZG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518836",
      "property_address": "Flat 129, Hartingtons Court, Scrimgoeur Place, London (N4 2ZG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518837",
      "property_address": "Flat 130, Hartingtons Court, Scrimgoeur Place, London (N4 2ZG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518838",
      "property_address": "Flat 131, Hartingtons Court, Coster Avenue, London (N4 2WL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518839",
      "property_address": "Flat 132, Hartingtons Court, Coster Avenue, London (N4 2WP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518840",
      "property_address": "Flat 80, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518841",
      "property_address": "Flat 81, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518842",
      "property_address": "Flat 82, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518843",
      "property_address": "Flat 83, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518844",
      "property_address": "Flat 84, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518845",
      "property_address": "Flat 85, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518846",
      "property_address": "Flat 86, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518848",
      "property_address": "Flat 87, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518849",
      "property_address": "Flat 135, Hartingtons Court, Coster Avenue, London (N4 2WP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518861",
      "property_address": "Flat 88, Hartingtons Court, Coster Avenue, London (N4 2WQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518863",
      "property_address": "Flat 89, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518864",
      "property_address": "Flat 90, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518865",
      "property_address": "Flat 91, Hartingtons Court, Coster Avenue, London (N4 2WQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518866",
      "property_address": "Flat 92, Hartingtons Court, Coster Avenue, London (N4 2WQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518868",
      "property_address": "Flat 93, Hartingtons Court, Coster Avenue, London (N4 2WQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518869",
      "property_address": "Flat 94, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518873",
      "property_address": "Flat 95, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518875",
      "property_address": "Flat 96, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518876",
      "property_address": "Flat 97, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518877",
      "property_address": "Flat 98, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518879",
      "property_address": "Flat 99, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518880",
      "property_address": "Flat 100, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518883",
      "property_address": "Flat 101, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518884",
      "property_address": "Flat 149, Hartingtons Court, Coster Avenue, London (N4 2WP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518906",
      "property_address": "Flat 102, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518908",
      "property_address": "Flat 103, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518910",
      "property_address": "Flat 104, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518912",
      "property_address": "Flat 105, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518914",
      "property_address": "Flat 106, Hartingtons Court, Coster Avenue, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518915",
      "property_address": "Flat 107, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518918",
      "property_address": "Flat 108, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518920",
      "property_address": "Flat 156, Hartingtons Court, Coster Avenue, London (N4 2WP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518928",
      "property_address": "Flat 109, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518930",
      "property_address": "Flat 110, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518931",
      "property_address": "Flat 111, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518935",
      "property_address": "Flat 113, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518937",
      "property_address": "Flat 114, Hartingtons Close, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518938",
      "property_address": "Flat 115, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518941",
      "property_address": "Flat 116, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518945",
      "property_address": "Flat 117, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518946",
      "property_address": "Flat 118, Hartingtons Close, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518947",
      "property_address": "Flat 119, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518948",
      "property_address": "Flat 120, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518950",
      "property_address": "Flat 121, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518959",
      "property_address": "Flat 123, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518960",
      "property_address": "Flat 124, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518961",
      "property_address": "Flat 125, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL518962",
      "property_address": "Flat 126, Hartingtons Court, Coster Avenue, London (N4 2WN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL519671",
      "property_address": "Renoir House, Cezanne Road, London (W3 7AX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL53466",
      "property_address": "39 Burket Close, Southall (UB2 5NR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL54745",
      "property_address": "75 Nene Gardens, Feltham (TW13 5PJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL56298",
      "property_address": "Flats 1-10 (inc), 177 The Vale, London (W3 7RD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL56378",
      "property_address": "3-10 (inc) Phoenix Court, Green Dragon Lane, Brentford (TW8 0HY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL56432",
      "property_address": "The Cygnets, Grove Crescent, Hanworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL57823",
      "property_address": "4,5,8,9,11 and 20 Penard Road, Southall (UB2 4XN) and parking spaces",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL57831",
      "property_address": "9, 13, 15, 16, 17 Cookham Close, Southall (UB2 4PG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL59575",
      "property_address": "20 Hornbill Close, Cowley, Uxbridge (UB8 2HX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL59615",
      "property_address": "St Aidan's Court, St Aidans Road, London (W13 9RD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL59824",
      "property_address": "8-15 (inc), Humber Close, West Drayton (UB7 7AT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL60224",
      "property_address": "195 and 197 Bedfont Lane, Feltham (TW14 9NP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL60520",
      "property_address": "28 Eastmead Avenue, Greenford, (UB6 9RB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL62279",
      "property_address": "1 to 13 (inclusive) Shepherd Close, Hanworth, Feltham (TW13 6PG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL62715",
      "property_address": "9 Chesterfield Road, London (N3 1PR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL62717",
      "property_address": "32 Mays Lane, Barnet (EN5 2EE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL62719",
      "property_address": "24 Uplands Road, East Barnet",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL62720",
      "property_address": "69 Daneland",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL62721",
      "property_address": "8 Vale Drive, Barnet (EN5 2ED)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL6515",
      "property_address": "32 Beavers Lane",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL67169",
      "property_address": "20 Chesterfield Road, Barnet (EN5 2RG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL68157",
      "property_address": "parking space 11, 35-37 St Johns Road, Isleworth (TW7 6NY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL68404",
      "property_address": "1 -12 (inclusive) and 19 - 27 (inclusive) Littlewood Close, London and 1 - 43 (inclusive) Jefferson Close, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL68432",
      "property_address": "61A Brookhill Road, New Barnet (EN4 8SF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL68452",
      "property_address": "6 Glen Walk, Isleworth (TW7 7PT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL68775",
      "property_address": "21 Penard Road, Southall (UB2 4XN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL70575",
      "property_address": "26 Sutton Crescent",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL71806",
      "property_address": "121 to 143 (odd), Bray Road, Inglis Barracks, London and parking spaces (NW7 1SL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL72292",
      "property_address": "Land at Pageant Avenue, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL75711",
      "property_address": "3 and 3A Wordsworth Avenue, Greenford (UB6 9AA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL76527",
      "property_address": "8 Padbury Close, Bedfont, (TW14 8SW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL77889",
      "property_address": "12 and 17 Repens Way and 51 Ramulis Drive and Car Parking Spaces",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL78427",
      "property_address": "land on the south side of The Cygnets, Hanworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL78509",
      "property_address": "28, 38 and 38a Grove Crescent, Feltham (TW13 6LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL7962",
      "property_address": "90 Bear Road, Feltham (TW13 6RG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL82983",
      "property_address": "35 East Avenue, Southall, (UB1 2AQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL86557",
      "property_address": "19 Padbury Close, Grove Village, Bedfont, (TW14 8SP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL87808",
      "property_address": "21a, 23-25b Humes Avenue, London (W7 2LJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL89983",
      "property_address": "15 Squires Court, Abingdon Road, Finchley (N3 2RJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL9063",
      "property_address": "56, 57, 59, 61, 63 Crestwood Way, Hounslow Heath (TW4 5EQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL91141",
      "property_address": "129 Byron Way, Northolt (UB5 6BA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL928",
      "property_address": "17 Harte Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL9488",
      "property_address": "13 Bethany Waye, Bedfont",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL97983",
      "property_address": "2 Johnson Court, 285 Watford Way (NW4 4TT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "AGL98948",
      "property_address": "Block A, 273-287 Watford Way, Hendon, (NW4 4TB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "AGL99104",
      "property_address": "3, 4, 9, 10, 15, 16, 22 and 23, Woodgrange House, Uxbridge Road, Ealing (W5 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BD162184",
      "property_address": "298 West Street, Dunstable (LU6 1PA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL110006",
      "property_address": "Land on the north-west side of Bridgwater Road, Romford",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL122019",
      "property_address": "Flat 9, 15 Cornwall Crescent, London (W11 1PH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL12454",
      "property_address": "50 Melville Court, Goldhawk Road, London, (W12 9NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL12467",
      "property_address": "21D Overstone Road, (W6 0AA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL128157",
      "property_address": "Flat B, 42 Woodstock Grove, London (W12 8LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL128666",
      "property_address": "34D Lime Grove, London (W12 8EA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL13219",
      "property_address": "Flat E, 61 Oxford Gardens, (W10 5UJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL133936",
      "property_address": "5b North Pole Road, London (W10 6QH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL14014",
      "property_address": "Land on the north west side of Barlby Road, Kensington",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL141456",
      "property_address": "Flat B, 23 Bassein Park Road, London (W12 9RN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL141780",
      "property_address": "Flat 1, Waldo House, Trenmar Gardens, London (NW10 6BD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL1455",
      "property_address": "547 Hurstway Walk, London (W11 1WF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL146552",
      "property_address": "36c Lime Grove, London (W12 8EA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL14746",
      "property_address": "3 to 19 (odd), 20, and 21 to 33 (odd) Woodger Road, London (W12 8NW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL152418",
      "property_address": "Flat 8, Lyndhurst, Vera Road, London (SW6 6QL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL15501",
      "property_address": "Oliver House, Henry Dickens Court, St Anns Road, London (W11 4EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL15825",
      "property_address": "305 Hurstway Walk, London (W11 1WD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL16886",
      "property_address": "Flat 1, 61 Lancaster Road, Kensington, (W11 1QG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL17026",
      "property_address": "152, 152A, 152B, 152C, 154, 154A, 154B and 154C Goldhawk Road, Hammersmith, London (W12 8HJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL18356",
      "property_address": "Flat, 27 Clarendon Walk, London (W11 1SN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL18975",
      "property_address": "61 Earls Court Square, London (SW5 9DG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL20301",
      "property_address": "1-3 (inc) Mitre House, 100 Novello Street, Fulham, London, and parking spaces (SW6 4JB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL21563",
      "property_address": "106 Fitzneal Street (W12 0BB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL23045",
      "property_address": "11 Coronation Court, Brewster Gardens, Kensington (W10 6AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL24587",
      "property_address": "Shaftesbury Place, 135 Warwick Road, London and 100a West Cromwell Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL25032",
      "property_address": "2-24 (even) and 27-37 (odd), Elgin Avenue and land on the north east side of Leysfield Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL25611",
      "property_address": "1 Clematis Cottages, Clematis Street, London (W12 0QQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL26209",
      "property_address": "8a Letchford Gardens, London (NW10 6AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL27028",
      "property_address": "Drake Court, 2 Webb Close, London (W10 5QB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL28629",
      "property_address": "95 St Marks Road (W10 6JW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL29380",
      "property_address": "10 Bartle Road, London (W11 1RF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL34895",
      "property_address": "Flat 7, Browning House, 29 De Vere Gardens, Kensington, (W8 5AW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL3581",
      "property_address": "30 Orchard Close, London (W10 5RA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL36557",
      "property_address": "515 Barandon Walk, London (W11 1WL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL36752",
      "property_address": "Flat 17, 117a Lancaster Road, London (W11 1QT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL36753",
      "property_address": "Flat 14, 117a Lancaster Road, London (W11 1QT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL36837",
      "property_address": "236 to 294 (inclusive) Attwood House, Warwick Road, London (W14 8TX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL37230",
      "property_address": "Loft Space, 46 Bevington Road, (W10 5TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL39818",
      "property_address": "Flat 3, 41-43 Eardley Crescent, London (SW5 9JT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL4430",
      "property_address": "Flat 2, 7 Kensington Church Street, London (W8)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL44425",
      "property_address": "Flat 5, 2 St Quintin Avenue, London (W10 6NU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL5131",
      "property_address": "291 Portobello Road, London, (W10 5DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55",
      "property_address": "Ground Floor Flat, 56 Barons Court Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55806",
      "property_address": "Flat 6, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55807",
      "property_address": "Flat 7, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55808",
      "property_address": "Flat 8, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55810",
      "property_address": "Flat 10, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55811",
      "property_address": "Flat 11, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55813",
      "property_address": "Flat 13, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55814",
      "property_address": "Flat 14, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55815",
      "property_address": "Flat 15, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL55816",
      "property_address": "Flat 17, Helix Court, 7 Swanscombe Road, London (W11 4SU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL5654",
      "property_address": "104 Holland Road, London (W14 8BD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL61528",
      "property_address": "Flat 8, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61529",
      "property_address": "Flat 9, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61530",
      "property_address": "Flat 10, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61531",
      "property_address": "Flat 13, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61532",
      "property_address": "Flat 15, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61534",
      "property_address": "Flat 17, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61535",
      "property_address": "Flat 18, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61536",
      "property_address": "Flat 19, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61537",
      "property_address": "Flat 20, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61539",
      "property_address": "Flat 22, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61540",
      "property_address": "Flat 23, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61541",
      "property_address": "Flat 24, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61542",
      "property_address": "Flat 25, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61543",
      "property_address": "Flat 26, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61545",
      "property_address": "Flat 28, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61546",
      "property_address": "Flat 29, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL61547",
      "property_address": "Flat 30, Pippin House, 25 Bramley Road, London (W10 6SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL62136",
      "property_address": "land at Sawley Road, Bloemfontein Road and Bryony Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL6331",
      "property_address": "land and buildings lying to the east of Lime Grove, 1 to 38 (inclusive) Gainsborough Court, Lime Grove, 24 Scotts Road and 1 to 6 (inclusive) Southway Close, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL6477",
      "property_address": "Flat 7, 21 Sinclair Gardens, London (W14 0AU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL6766",
      "property_address": "33 Upper Clarendon Walk, London (W11 1SW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL7666",
      "property_address": "7 Woodstock Grove, London (W12 8LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL78375",
      "property_address": "Flat 3, 17 Lower Addison Gardens, London (W14 8BG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL79003",
      "property_address": "Flat 2, 53 Ledbury Road, London (W11 2AA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL83412",
      "property_address": "266 Ladbroke Grove, London (W10 5LP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL8586",
      "property_address": "2 to 24 (even) Batson Street, and 79 to 89 (odd) Westville Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL85974",
      "property_address": "Flat D, 8 Vera Road, London (SW6 6RN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL8769",
      "property_address": "64 St Ervans Road, London (W10 5QT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL9012",
      "property_address": "Clement House, 135 Dalgarno Gardens, London (W10 5JB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL9013",
      "property_address": "Flats A, B, C, D, E and F 1 Shrewsbury Street, Flats A, B, C, D, E and F 17 Shrewsbury Street and Flats A, B, C, D, E and F 31 Shrewsbury Street, 1A, 1B, 1C, 1D, 1E and 1F Hillman Drive and 20, 20A, 20B, 20C, 20D, 20E and 20F Dalgarno Way, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "BGL9583",
      "property_address": "59 Perham Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BGL9777",
      "property_address": "82a Goldhawk Road, Shepherds Bush (W12 8EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BK164545",
      "property_address": "9 Welland Close, Slough and Parking Spaces (SL3 8UZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK168137",
      "property_address": "153 Doddsfield Road, Slough, (SL2 2BA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK177348",
      "property_address": "227 Long Furlong Drive, Slough, (SL2 2LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK178995",
      "property_address": "61 Gosling Road, Slough, (SL3 7TP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK182484",
      "property_address": "18 Windermere Way, Slough, (SL1 6EL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK186126",
      "property_address": "26 Blandford Road South, Slough",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK194715",
      "property_address": "40 Mercian Way, Slough (SL1 5LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK197444",
      "property_address": "80 Nettlecombe, Crown Wood, Bracknell (RG12 0UQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK199540",
      "property_address": "310 Scafell Road, Slough (SL2 1TY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK246556",
      "property_address": "74 Scrivens Mead, Thatcham, (RG13 4FQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK264896",
      "property_address": "8 Scarborough Way, Slough (SL1 9JY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BK268427",
      "property_address": "49 HOLMLEA WALK, DATCHET, SLOUGH SL3 9EW",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BK283123",
      "property_address": "150 Derwent Drive, Slough and outbuilding (SL1 6HP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BK334170",
      "property_address": "17 Mallard Drive, Slough (SL1 5BW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BK339332",
      "property_address": "49 Windermere Way, Slough (SL1 6EJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK348949",
      "property_address": "23 Ingleton, Wildridings, Bracknell (RG12 7RN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BK388971",
      "property_address": "40 Wordsworth Road, Slough (SL2 2NY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM105600",
      "property_address": "43 Withycroft, George Green (SL3 6BH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM107081",
      "property_address": "21 Tilehouse Way, Denham and bin store (UB9 5HY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM107582",
      "property_address": "22 Laurels Road, Iver (SL0 0BY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM107816",
      "property_address": "2 Clonmel Way, Burnham, Slough (SL1 7DA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM113512",
      "property_address": "20 North Burnham Close, Burnham (SL1 8HT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM113713",
      "property_address": "4 Forge Place, Steeple Claydon, Buckingham (MK18 2QU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM124801",
      "property_address": "144 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM124802",
      "property_address": "152 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM124804",
      "property_address": "150 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM124806",
      "property_address": "148 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM125431",
      "property_address": "142 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM125433",
      "property_address": "134 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM125767",
      "property_address": "10 Brentwood Way, Bedgrove, Aylesbury (HP21 7ER)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM126670",
      "property_address": "4 Ellington Court, Ellington Road, Taplow (SL6 0AZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM128640",
      "property_address": "166 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM128641",
      "property_address": "164 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM128642",
      "property_address": "168 Maypole Road, Taplow (SL6 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM145486",
      "property_address": "49 Northern Road, Aylesbury (HP19 9QT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM151179",
      "property_address": "9 Heatherden Green, Iver Heath",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM151699",
      "property_address": "Flat 6, Burns Court, Milton Road, Aylesbury and parking space (HP21 7NN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM155278",
      "property_address": "Flat 4, 126 Pinewood Green, Iver (SL0 0QQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM159972",
      "property_address": "32 Lupin Walk, Aylesbury and parking space (HP21 8XL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM162895",
      "property_address": "12 Oxford Gardens, Denham, Uxbridge (UB9 4EA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM164259",
      "property_address": "8 Hawfinch, Aylesbury, and parking space (HP19 0WE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM166225",
      "property_address": "23 Bates Close, George Green, Slough (SL3 6SB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM167654",
      "property_address": "6 Shenstone Drive, Burnham (SL1 7HJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM173875",
      "property_address": "First Floor Flat, 18 Missenden Gardens, Burnham (SL1 6LB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM177707",
      "property_address": "19 Bates Close, George Green, (SL3 6SB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM179679",
      "property_address": "21 Missenden Gardens, Huntercombe Lane North, Burnham and parking space, (SL1 6LB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM190714",
      "property_address": "241 Bicester Road, Aylesbury",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM196863",
      "property_address": "80 Thorney Lane North, Iver (SL0 9LR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM197801",
      "property_address": "114 Hicks Farm Rise, High Wycombe (HP13 7SW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM202456",
      "property_address": "Land on the east side of 43 Marjoram Place, Conniburrow (MK14 7AQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM206835",
      "property_address": "1-15 (odd), Jarman Close, Buckingham (MK18 7AB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM213413",
      "property_address": "115 Maxwell Road, Beaconsfield, (HP9 1RF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM220837",
      "property_address": "5a Churchill Avenue, Aylesbury (HP21 8NF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM224783",
      "property_address": "40 Oakfield Road, Aylesbury, (HP20 1LL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM232220",
      "property_address": "39 Pennylets Green, Stoke Poges, Slough (SL2 4BX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM238498",
      "property_address": "Garage adjoining 66 Gladstone Road, Chesham",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM239680",
      "property_address": "66 Gladstone Road, Chesham (HP5 3AD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM248873",
      "property_address": "Meadow View, Bangors Road North, Iver and garage (SL0 0RY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM250322",
      "property_address": "land at the back of 12 Oxford Gardens, Denham",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM253605",
      "property_address": "35 Langley Park Road, Iver, (SL0 9QL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM264520",
      "property_address": "1 and 2 Gullicott Way, Pitstone, Leighton Buzzard and 1 - 5 (inclusive) Long Hedge, Pitstone, Leighton Buzzard",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM272421",
      "property_address": "Land adjoining 1 Long Hedge, Pitstone, Leighton Buzzard (LU7 9HQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM290810",
      "property_address": "Block B, Old Brewery Close, Aylesbury (HP21 7BB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM32843",
      "property_address": "465 Whaddon Way, Bletchley",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM36506",
      "property_address": "64 Hag Hill Rise, Taplow, Maidenhead (SL6 0LT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM44774",
      "property_address": "57 Vicarage Close, Steeple Claydon (MK18 2PU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM52571",
      "property_address": "18 Avon Place, Aylesbury, (HP21 9LR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM54061",
      "property_address": "17 Selkirk Avenue, Aylesbury (HP19 3QD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM55078",
      "property_address": "56 Leas Drive, Iver (SL0 9RD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM55421",
      "property_address": "23 Oxford Gardens, Denham (UB9 4EB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM62676",
      "property_address": "26 Barrie Close, Aylesbury",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM64724",
      "property_address": "40 Hemingway Road, Aylesbury (HP19 8SD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM66094",
      "property_address": "94 Maypole Road, Taplow",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM67414",
      "property_address": "21 Buffins, Taplow, Maidenhead (SL6 0HF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM67898",
      "property_address": "47 Larkings Lane, Stoke Poges (SL2 4JU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM69477",
      "property_address": "7d Leas Drive, Iver (SL0 9RB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM69644",
      "property_address": "2 St Margaret's Gate, Iver (SL0 0DP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM70414",
      "property_address": "105 Lowndes Way, Winslow (MK18 3EW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM70952",
      "property_address": "37 Buffins, Taplow, Maidenhead (SL6 0HF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM71155",
      "property_address": "5A Robin Parade, Farnham Common and Garage",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM73689",
      "property_address": "72 Churchill Avenue, Aylesbury (HP21 8NH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM74747",
      "property_address": "73 Devonshire Green, Farnham Royal (SL2 3DX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM80314",
      "property_address": "54 Penn Drive, Denham, Uxbridge (UB9 5JR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM81685",
      "property_address": "66 Chiltern Road, Burnham, (SL1 7NH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM81896",
      "property_address": "29 Barnfield, Iver (SL0 0AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM82016",
      "property_address": "42 Cobblers Close, Farnham Royal, Slough and garage 4 (SL2 3DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM82464",
      "property_address": "114 Heatherden Green, Iver Heath, (SL0 0QA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM83055",
      "property_address": "18 The Dell, The Coppice, Aylesbury",
      "tenure": "Leasehold"
    },
    {
      "title_number": "BM83330",
      "property_address": "72 Fremantle Road, Aylesbury (HP21 8EJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM89123",
      "property_address": "23 Bishops Orchard, Farnham Royal, Slough (SL2 3AB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM91537",
      "property_address": "161 High Street, Iver (SL0 9QB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "BM94155",
      "property_address": "45 Marjoram Place, Conniburrow, Milton Keynes (MK14 7AQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "CH185771",
      "property_address": "19 Grange Avenue, Latchford",
      "tenure": "Freehold"
    },
    {
      "title_number": "CL124943",
      "property_address": "6 Lemon Hill, Mylor Bridge (TR11 5NA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "CL78686",
      "property_address": "31 Biscombe Gardens, Saltash, (PL12 6EG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "DT214384",
      "property_address": "68 Endfield Road, Christchurch",
      "tenure": "Freehold"
    },
    {
      "title_number": "DT240966",
      "property_address": "48 Farcroft Road, Parkstone, Poole (BH12 3BQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "DT253706",
      "property_address": "18 Park Road, Swanage (BH19 2AD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "DT26002",
      "property_address": "14 Firsway, Upton, Poole and garage (BH16 5HU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL11586",
      "property_address": "153 Kempton Road, London (E6 2NF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL122151",
      "property_address": "1 Forest Street, Forest Gate, London (E7 0HP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL126636",
      "property_address": "53 Redclyffe Road, East Ham, London (E6 1DT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL127553",
      "property_address": "37 Jedburgh Road, London (E13 9LF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL140209",
      "property_address": "119 Sutton Court Road, London (E13 9NR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL146869",
      "property_address": "5 Alestan Beck Road, West Beckton, London, (E16 3TW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL15067",
      "property_address": "102 St Stephens Road, London (E6 1AT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL158300",
      "property_address": "59A Whittington Road, Wood Green",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL158800",
      "property_address": "49 Linton Gardens, London (E6 5SQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL159163",
      "property_address": "Ashley House, Ashley Road, London (N17 9LZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL182651",
      "property_address": "23 Dundee Road, Plaistow, (E13 0BQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL203837",
      "property_address": "283 Fulbourne Road, Walthamstow",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL213541",
      "property_address": "27 Kingfisher Street, Beckton, (E6 5JZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL235239",
      "property_address": "301 Tollgate Road, Beckton and parking space, (E6 4XW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL239830",
      "property_address": "54 Warrior Square, Manor Park, London, (E12 5RU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL244996",
      "property_address": "103 Balaam Street, London (E13 8EA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL246947",
      "property_address": "76 High Street, Plaistow, London and Store (E13 0AJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL252905",
      "property_address": "The Stag, Brooksby's Walk, Homerton",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL253510",
      "property_address": "79 Sycamore Close, London (E16 4QR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL256601",
      "property_address": "10 Knights Close, Hackney, London (E9 6EW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL267881",
      "property_address": "114 Morse Close, Plaistow, London (E13 0HJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL271741",
      "property_address": "14 Edmeston Close, Swinnerton Street, London (E9 5TJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL272318",
      "property_address": "99 Wellstead Road, London (E6 6DE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL272539",
      "property_address": "106 Snowshill Road, London (E12 6BB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL273228",
      "property_address": "19 Eric Close, Forest Gate, London, (E7 0AY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL284857",
      "property_address": "3 Bowes Road, London (N13 4UX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL292209",
      "property_address": "26 Gawsworth Close, Stratford, London, (E15 1RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL292219",
      "property_address": "24 Halidon Close, Jack Dunning Estate, Hackney, London, (E9 6EE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL297688",
      "property_address": "77 Fowler Road, London (E7 0AU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL303372",
      "property_address": "Flat 7, 78 St Stephens Road, London (E3 5JL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL318915",
      "property_address": "95 Snowshill Road, London (E12 6BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL318974",
      "property_address": "41 Chadwin Road, London (E13 8ND)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL321399",
      "property_address": "21 Greengate Street, Plaistow, London (E13 OBG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL322757",
      "property_address": "15 Tunstall Avenue, Ilford (IG6 3EG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL323835",
      "property_address": "2A Garnham Street, Stoke Newington, London (N16 7JB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL32815",
      "property_address": "15 Colchester Avenue, London (E12 5LF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL338297",
      "property_address": "Flat 107, Mission Building, 747 Commercial Road, London (E14 7LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL341031",
      "property_address": "Flats A, B, C, D, E, F and G, 6 Lee Conservancy Road, London (E9 5HW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL345628",
      "property_address": "50 Brock Road, London (E13 8LZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL350603",
      "property_address": "Flat 29, Albion Yard, Whitechapel Road (E1 1BW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL353431",
      "property_address": "25 Muir Street, London (E16 2HL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL356827",
      "property_address": "8 Sissulu Court and land at the rear of 51 Redclyffe Road, East Ham (E6 1DT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL378246",
      "property_address": "Flat 1, Fernhill House, Geldeston Road, London (E5 8RU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL378280",
      "property_address": "21 Mundford Road, London (E5 9PP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL380761",
      "property_address": "12 Silver Birch Gardens, London (E6 3SX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL381225",
      "property_address": "Flat 6, 2A Garnham Street, Stoke Newington, London (N16 7JB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL381227",
      "property_address": "Flat 4, 2a Garnham Street, London (N16 7JB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL38299",
      "property_address": "182 Hollybush Street, London (E13 9EB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL392395",
      "property_address": "116 Olive Road, London (E13 9PU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL395912",
      "property_address": "Flats 1-6, Razia Mews, 135 Church Road, London (E12 6AF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL397236",
      "property_address": "land on the south side of 35 Brooksby's Walk, London (E9 6DA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL402799",
      "property_address": "58 Eastway, London (E9 5JD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL403510",
      "property_address": "Flat 69, Spectacle Works, 1a Jedburgh Road, London (E13 9LX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL416273",
      "property_address": "7 Sissulu Court, Redclyffe Road, London (E6 1DW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL426486",
      "property_address": "Site B Trowbridge Estate, Eastway, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL428477",
      "property_address": "8 to 14 (even) Woolwich Manor Way, London (E16 2NJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL43391",
      "property_address": "7 Gresham Road, East Ham, London (E6 6DS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL437177",
      "property_address": "35 Eastway, Homerton, E9 5JB",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL438807",
      "property_address": "Flat 3, 38 Eastway, Hackney (E9 5HN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL439158",
      "property_address": "14 Lavington Close, Hackney, London (E9 5HF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL451360",
      "property_address": "15 Felstead Street, London (E9 5LZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL452601",
      "property_address": "part of 14-15 Hoxton Square, London (N1 6NT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL452624",
      "property_address": "21 Brinkworth Way, London (E9 5LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL452626",
      "property_address": "34 Daintry Way, London (E9 5JJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL452852",
      "property_address": "22 Brinkworth Way, Trowbridge Road, London (E9 5LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL453602",
      "property_address": "8 Gainsborough Street, London (E9 5GY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL454726",
      "property_address": "Flat 1, 47 Eastway, London, (E9 5JP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL455131",
      "property_address": "36 Wards Wharf Approach, London (E16 2EY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL455156",
      "property_address": "35 Wards Wharf Approach, London (E16 2EY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL456207",
      "property_address": "28 Brinkworth Way, Trowbridge Road, London (E9 5LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL457439",
      "property_address": "46 East Way, London, (E9 5JP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL457692",
      "property_address": "Flat 96, Wards Wharf Approach, London (E16 2EX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL457710",
      "property_address": "Flat 97, Wards Wharf Approach, London (E16 2EX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL469625",
      "property_address": "13 Merriam Avenue, London, (E9 5LS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL471280",
      "property_address": "Site C2, Trowbridge Estate, London (E9 9NE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL471624",
      "property_address": "Flat 4, 31B Eastway, Hackney, London (E9 5JQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL473464",
      "property_address": "1 Merriam Avenue, London (E9 5LS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL473586",
      "property_address": "15 Merriam Avenue, London (E9 5LS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL479889",
      "property_address": "27 Trowbridge Road, London (E9 5LD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL484951",
      "property_address": "Flat 3, 31C Eastway, London (E9 5JW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL489439",
      "property_address": "Flat 6, 31B Eastway, London (E9 5JQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL499184",
      "property_address": "Village Green, Eastway, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL524104",
      "property_address": "1 Carillon Court, 41 Greatorex Street, London (E1 5EN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL524108",
      "property_address": "3 Carillon Court, 41 Greatorex Street, London (E1 5EN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL524109",
      "property_address": "4 Carillon Court, 41 Greatorex Street, London (E1 5EN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL524111",
      "property_address": "9 Carillon Court, 41 Greatorex Street, London (E1 5EN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL544112",
      "property_address": "37 Eastway, London (E9 5JB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL551724",
      "property_address": "Land on the north side of Myddelton Street, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL555783",
      "property_address": "2A Garnham Street, London (N16 7JB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL576313",
      "property_address": "Flats 22, 23, 24, 25 and 26, Dao Court, Dacre Road, London (E13 0PG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL576614",
      "property_address": "Flats 5-13, 22-30, 41-49, 55-58, Fanshawe House, Gale Street, Dagenham and parking spaces (RM9 4UT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EGL62468",
      "property_address": "94 New City Road, London (E13 9NP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL67432",
      "property_address": "118 New City Road, Plaistow (E13 9PY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL77878",
      "property_address": "92 Kingsland Road, London (E13 9NU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EGL99663",
      "property_address": "7 Humberstone Road, London (E13 9NL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "ESX7125",
      "property_address": "150 Mile Oak Road, Portslade, Brighton (BN41 2PL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EX2357",
      "property_address": "3 Perth Road, London (E13 9DS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EX27328",
      "property_address": "12 Gooseley Lane, East Ham, London (E6 6AP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EX39619",
      "property_address": "20 Botha Road, London (E13 8PQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EX550154",
      "property_address": "28 Gate Street Mews, Gate Street, Maldon and parking space (CM9 5EF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EX611912",
      "property_address": "4 Rainbow Avenue, Canvey Island (SS8 8AF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "EX979844",
      "property_address": "Waterhouse Court, Burgess Springs, Chelmsford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EX979903",
      "property_address": "Block F, Burgess Springs, Chelmsford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "EX979904",
      "property_address": "Block G, Burgess Springs, Chelmsford (CM1 1QN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "GR119446",
      "property_address": "49 Peghouse Close, Stroud (GL5 1UP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD102182",
      "property_address": "764 St Albans Road, Watford (WD2 6NH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD104025",
      "property_address": "91 The Queens Drive, Mill End, Rickmansworth (WD3 8LS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD105596",
      "property_address": "10 Bramshaw Gardens, South Oxhey, (WD19 6XP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD110335",
      "property_address": "37 Appleton Fields, Thorley, Bishop's Stortford and garage (CM23 4DP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD112972",
      "property_address": "193 Leavesden Road, Watford (WD24 5EL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD117736",
      "property_address": "15 Kensington Avenue, Watford (WD18 7RZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD136757",
      "property_address": "13 Knebworth Court, Bishop's Stortford and Garage, (CM23 4HF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD137688",
      "property_address": "44 Cassiobridge Road, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD141133",
      "property_address": "40 Parker Street, Watford (WD24 5EZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD149887",
      "property_address": "35 Greyfriars, Ware",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD151888",
      "property_address": "140 The Harebreaks, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD154597",
      "property_address": "19 Brookside Road, Watford (WD19 4BW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD154981",
      "property_address": "141 Newhouse Crescent, Watford (WD25 7JA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD155456",
      "property_address": "101 Coates Way, Watford (WD25 9NX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD164118",
      "property_address": "45A Baldwins Lane, Croxley Green",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HD165446",
      "property_address": "11 Earls Close, Bishop's Stortford, (CM23 4HW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD165729",
      "property_address": "402 Jessop Road, Stevenage (SG1 5NE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD169296",
      "property_address": "36 Oak Green, Abbots Langley and Garage (WD5 0PG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD171110",
      "property_address": "13 Hamels Drive, Pine Hurst, Hertford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD179064",
      "property_address": "9 Capell Way, Chorleywood",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD186504",
      "property_address": "51 Romilly Drive, Carpenders Park",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD187024",
      "property_address": "28 Burnley Close, Watford (WD19 6YS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD198110",
      "property_address": "336 Croxley View, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD208628",
      "property_address": "6 Pemsel Court, Hemel Hempstead (HP3 9DY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD212530",
      "property_address": "21 Blackthorn Close, Watford (WD25 7EL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD213362",
      "property_address": "11 Folly Close, Hitchin",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD219276",
      "property_address": "7 Page Road, Hertford (SG13 7JN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD219621",
      "property_address": "12 Middle Way, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD226745",
      "property_address": "115 Downfield Road, Cheshunt, Waltham Cross (EN8 8SS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD232021",
      "property_address": "13 Page Hill, Ware (SG12 0RZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD233024",
      "property_address": "38 Harkness, Cheshunt",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD254661",
      "property_address": "9 Holly Croft, Hertford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD256316",
      "property_address": "87 Rushton Avenue, Watford (WD25 0AP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD262168",
      "property_address": "15 Broomfield Rise, Abbots Langley (WD5 0HJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD272114",
      "property_address": "72 Millacres, Station Road, Ware and parking space (SG12 9PU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HD274597",
      "property_address": "41 Bairstow Close, Borehamwood, (WD6 4TB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD278055",
      "property_address": "63 Benskin Road, Watford (WD18 0HN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD299508",
      "property_address": "21 Birchwood Way, Park Street, St Albans (AL2 2SE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD303284",
      "property_address": "77 Birdie Way, Hertford (SG13 7SY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD306019",
      "property_address": "63 West Street, Hertford (SG13 8EZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD306098",
      "property_address": "73 Dimsdale Crescent, Bishop's Stortford (CM23 5LW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD312639",
      "property_address": "110 Fourth Avenue, Watford (WD25 9QG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD323992",
      "property_address": "11 Gladesmere Court, 405 to 409 St Albans Road, Watford",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HD327765",
      "property_address": "22 Reedings Way, Sawbridgeworth, (CM21 9DX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD330222",
      "property_address": "28 The Meadows, Bishop's Stortford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD332756",
      "property_address": "40 Birchwood Way, Park Street, St Albans (AL2 2SQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD341048",
      "property_address": "19 Haweswater Drive, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD346848",
      "property_address": "36 Summerhouse Way, Abbots Langley (WD5 0DY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD367332",
      "property_address": "17 Lime Close, Stevenage and Garage (SG2 9QB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD393435",
      "property_address": "Flat 8, Apton Court, Apton Road, Bishop's Stortford and Garage 8 (CM23 3UA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HD414202",
      "property_address": "12 The Guildhouse, New Road, Croxley Green, Rickmansworth (WD3 3HD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HD48108",
      "property_address": "5 The Grey House, Alexandra Road, Watford, (WD17 4QU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD53842",
      "property_address": "7 Napier Drive, Bushey",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD542618",
      "property_address": "20b Woodford Road, Watford (WD17 1PA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HD60996",
      "property_address": "7 Stile Plantation, Royston (SG8 9HR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD61489",
      "property_address": "14 Peregrine Close, Watford (WD25 9AP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD66574",
      "property_address": "23 Pretoria Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD69160",
      "property_address": "295 Perrysfield Road, Cheshunt (EN8 0TP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD76885",
      "property_address": "28 Nicoll Way, Borehamwood (WD6 2PR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD84172",
      "property_address": "8 Bridge Road, Hunton Bridge, Kings Langley (WD4 8RE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD89317",
      "property_address": "45 Pretoria Road, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD92376",
      "property_address": "108 Judge Street, Watford",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD94844",
      "property_address": "33 Pynchbek, Bishop's Stortford (CM23 4DH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HD95702",
      "property_address": "22 Shaftesbury Way, Royston (SG8 9DE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HP206907",
      "property_address": "211 Passfield Avenue, Eastleigh (SO50 9NE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "HP347871",
      "property_address": "18 Hurst Road, Ringwood (BH24 1AX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "HP371407",
      "property_address": "land adjoining 8 Goodwood Place, Farnborough",
      "tenure": "Freehold"
    },
    {
      "title_number": "HP428745",
      "property_address": "6 Stroudley Way, Hedge End",
      "tenure": "Freehold"
    },
    {
      "title_number": "HP85498",
      "property_address": "8 Goodwood Place, Farnborough (GU14 7EA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "K243398",
      "property_address": "19 Mead Green, Chatham (ME5 8PB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN101184",
      "property_address": "128 Gassiot Road, Tooting, (SW17 8LE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN103202",
      "property_address": "35 Brewster Gardens, London (W10 6AQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN105086",
      "property_address": "5 Brewster Gardens, Kensington, (W10 6AG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN105809",
      "property_address": "185 Bravington Road, London (W9 3AR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN107161",
      "property_address": "225 North End Road, London (W14 9NP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN108294",
      "property_address": "182 Bravington Road, London (W9 3AP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN111767",
      "property_address": "3 Lindrop Street, Fulham, (SW6 2QU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN112076",
      "property_address": "13 Minster Road, London (NW2 3SE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN114455",
      "property_address": "136 Bravington Road, London (W9 3AL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN120235",
      "property_address": "112 Hammersmith Grove, London (W6 7HB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN120561",
      "property_address": "176 Trevelyan Road, Tooting, (SW17 9LW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN128227",
      "property_address": "29 Minford Gardens, London (W14 0AP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN129013",
      "property_address": "12 Cosway Street, London (NW1 5NR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN134665",
      "property_address": "214 Sellincourt Road, (SW17 9SB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN13470",
      "property_address": "230 Mitcham Road, London (SW17 9NN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN136212",
      "property_address": "5 and 7 Maybury Street, London (SW17 0SB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN136730",
      "property_address": "203 Bravington Road, (W9 3AR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN136904",
      "property_address": "Flats 1, 1A, 2-4 (inc), 2 Cornwall Crescent, Kensington (W11 1PP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN142545",
      "property_address": "178 Holland Park Avenue, London (W11 4UH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN143181",
      "property_address": "Flats 1-4 (inc) and 4A, 4 Cornwall Crescent, Kensington (W11 1PP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN146445",
      "property_address": "105 Bravington Road, London (W9 3AS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN14727",
      "property_address": "54 Westcote Road, London (SW16 6BW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN154108",
      "property_address": "36 St Mark's Road and 138 Chesterton Road, Kensington",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN159374",
      "property_address": "101 St Mark's Road, London (W10 6JW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN163079",
      "property_address": "Drill Hall and Parade Ground, Jamaica Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN167226",
      "property_address": "19 Great Western Road, London (W9 3NW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN168180",
      "property_address": "17 Great Western Road, London (W9 3NW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN178222",
      "property_address": "48 and 48A Collingbourne Road, London (W12 0JQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN18073",
      "property_address": "88 Ladbroke Grove, Kensington, London (W11 2HE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN185383",
      "property_address": "120 Coldharbour Lane, London (SE5 9PZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN191767",
      "property_address": "113 Bravington Road, London (W9 3AS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN192959",
      "property_address": "36 Powis Square, London (W11 2AY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN193797",
      "property_address": "Flat 4, Julian Court, Vant Road, Tooting and garden ground (SW17 8TG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "LN194215",
      "property_address": "45 Maygrove Road, (NW6 2EE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN19817",
      "property_address": "30 Ormeley Road, Balham, (SW12 9QE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN209461",
      "property_address": "237 Camden Road, (N7 0HR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN211794",
      "property_address": "53 Huntspill Street, (SW17 0AA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN222774",
      "property_address": "22 Micawber Street, London (N1 7EQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN229410",
      "property_address": "11 Leithcote Gardens, London (SW16 2UX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN230244",
      "property_address": "239 Camden Road (N7 0HR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN238143",
      "property_address": "1 Worslade Road, London (SW17 0BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN249898",
      "property_address": "16 Kempsford Gardens, Kensington",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN51891",
      "property_address": "13 Chesterton Road, London, (W10 5LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN65013",
      "property_address": "51 Norwood Park Road, West Norwood, London (SE27 9UB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN65376",
      "property_address": "87, 89, 91 and 93 Goldhawk Road, London (W12 8EG) and 246 and 248 Hammersmith Grove, London (W6 7EP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN7323",
      "property_address": "3 Spurstowe Terrace, London (E8 1HP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN74625",
      "property_address": "76 Philbeach Gardens, London (SW5 9EY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN77055",
      "property_address": "3 Kempsford Gardens, London (SW5 9LA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN82435",
      "property_address": "18 Arminger Road, Shepherds Bush (W12 7BB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN83183",
      "property_address": "24A-D (inc) St Stephen's Avenue, London (W12 8JH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN84627",
      "property_address": "76 Ashmore Road, London (W9 3DG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "LN85589",
      "property_address": "46 Lansdowne Drive, London (E8 3ER)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX10792",
      "property_address": "29 Francis Avenue, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX115705",
      "property_address": "36 Meadow Road, Feltham (TW13 5JA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX116261",
      "property_address": "69 Perimeade Road, Alperton",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX118388",
      "property_address": "130 Millet Road, Greenford",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX119943",
      "property_address": "35 Wakeman Road, Kensal Green",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX121690",
      "property_address": "66 Carlton Avenue",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX121959",
      "property_address": "46 Meadow Road, Hanworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX127476",
      "property_address": "land on the east side of Ashley Road, Tottenham",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX139341",
      "property_address": "85 Beeston Way, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX14097",
      "property_address": "107 Rochester Avenue, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX142832",
      "property_address": "534 Kenton Lane, Kenton",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX155078",
      "property_address": "1 Shaftesbury Avenue, Feltham (TW14 9LN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX155836",
      "property_address": "68 Westbrook Road, Heston",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX167072",
      "property_address": "20 Cardrew Avenue, North Finchley",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX176262",
      "property_address": "62 Gledwood Avenue, Hayes, (UB4 0AW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX17647",
      "property_address": "69 Durham Road, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX182750",
      "property_address": "83 Downhills Way, London (N17 6AL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX184107",
      "property_address": "41-42 Kew Bridge Road, Brentford (TW8 0DY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX188383",
      "property_address": "3 Priory Park Road, Wembley (HA0 2RY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX197",
      "property_address": "292 Bedfont Lane, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX201847",
      "property_address": "55 and 60 Redhill Drive, Kingsbury",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX212510",
      "property_address": "20 Holly Road, St Clare Business Park, Hampton Hill",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX21624",
      "property_address": "102 Walton Avenue, Harrow, (HA2 8QX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX216611",
      "property_address": "39 Oakhampton Road, Mill Hill, London (NW7 1NG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX219599",
      "property_address": "18 Gresham Road, Edgware (HA8 6NU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX25914",
      "property_address": "24 Reading Road, Ealing (UB5 4PG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX276634",
      "property_address": "8 Cecil Road, Colindale",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX276694",
      "property_address": "45 Sunbury Road, Feltham (TW13 4PE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX2858",
      "property_address": "3 Silkfield Road, London (NW9 6QT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX288001",
      "property_address": "38 Orchard Avenue, Feltham (TW14 9RE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX302494",
      "property_address": "3 Ravensworth Road, London (NW10 5NP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX304356",
      "property_address": "9 Windmill Road, St Clare Business Park, Hampton Hill",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX30752",
      "property_address": "260 Ash Grove, Heston (TW5 9DY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX318205",
      "property_address": "42 Earlsmead Road, London (NW10 5QB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX319439",
      "property_address": "11 Linkfield Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX320459",
      "property_address": "57 Crundale Avenue, London (NW9 9PJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX326973",
      "property_address": "218 Whitton Dene, Isleworth, (TW7 7LU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX327990",
      "property_address": "11 Windmill Road, Hampton Hill, Hampton",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX328564",
      "property_address": "105 Kingshill Drive, Kenton",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX329498",
      "property_address": "land associated with 190 Bowes Road, London (N11 2JH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX334610",
      "property_address": "150 St Stephen's Road, Hounslow",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX337357",
      "property_address": "68 Devon Avenue, (TW2 6PW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX34459",
      "property_address": "47 Lynmouth Drive, Ruislip",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX345660",
      "property_address": "87 Ravenor Park Road, Greenford (UB6 9QY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX355701",
      "property_address": "1 Worthing Road, Hounslow (TW5 0ER)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "MX363128",
      "property_address": "23 Woodgrange Avenue",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX363143",
      "property_address": "3 Booth Road, London (NW9 5JS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX37172",
      "property_address": "37 Devon Avenue, Twickenham (TW2 6PN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX372189",
      "property_address": "4 Yewfield Road, London (NW10 9TB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX37594",
      "property_address": "8 Court Farm Road, Northolt",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX377956",
      "property_address": "LAND LYING TO THE NORTH WEST OF BOWES ROAD, LONDON",
      "tenure": "Leasehold"
    },
    {
      "title_number": "MX392209",
      "property_address": "land on the north side of Pinner Road, Harrow",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX39489",
      "property_address": "195 Rochester Avenue, Feltham (TW13 4EH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX396628",
      "property_address": "73 Woodland Gardens, Isleworth (TW7 6LW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX405320",
      "property_address": "64 and, 64a Leghorn Road, London (NW10 4PH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX416309",
      "property_address": "45 Lily Gardens",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX421447",
      "property_address": "20 Mulgrave Road, Willesden",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX430138",
      "property_address": "11 Townsend Road, Southall, (UB1 1HA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX431021",
      "property_address": "8 Osborne Close, Hanworth (TW13 6SR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX432772",
      "property_address": "22 Armstrong Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX43807",
      "property_address": "1-35, 37-43, 45-47 and 49-52 Leverton Close, London (N22 7BT), an electricity sub-station and land at Leverton Close, London (N22 7BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX438491",
      "property_address": "78 Maybank Avenue, Wembley (HA0 2TJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX438960",
      "property_address": "194, 194a, 196 and 196a Bowes Road, New Southgate, and Garage No 1",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX438961",
      "property_address": "198, 198a and parts of 200 and 200a Bowes Road and Garages, No 2 and 3 New Southgate",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX439804",
      "property_address": "49 Cromwell Road, Feltham (TW13 5AS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX446964",
      "property_address": "76 Linkfield Road, Isleworth (TW7 6QH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX451",
      "property_address": "123 Fernside Avenue",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX45101",
      "property_address": "77 Riverdene",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX451706",
      "property_address": "65 Lea Crescent, Ruislip (HA4 6PW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX452344",
      "property_address": "625 London Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX466513",
      "property_address": "8 Turner Close, Hayes (UB4 8QF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX474950",
      "property_address": "84 North Street, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX5075",
      "property_address": "28 & 11, Dors Close and 28 & 30 Wood Lane",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX51696",
      "property_address": "7A Bridgwater Road, Ruislip (TW13 6BN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX52187",
      "property_address": "8 Lee Road, London (NW7 1LJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX57666",
      "property_address": "10 York Way, Hampton Road West, Hanworth (TW13 6BN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX67336",
      "property_address": "37 Lyndhurst Avenue, Southall",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX67852",
      "property_address": "42 Ribchester Avenue, Perivale",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX70992",
      "property_address": "71 Church Road, Hayes",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX73128",
      "property_address": "35 St John's Road, Isleworth (TW7 6NY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX76066",
      "property_address": "68 Pett's Hill (UB5 4NN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX81094",
      "property_address": "12 Brook Avenue, Edgware, (HA8 9XF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX90594",
      "property_address": "Land lying to the west of Watsons Road, London (N22 7TZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX98950",
      "property_address": "113 Jeymer Drive, Greenford (UB6 8NT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "MX9947",
      "property_address": "76 Southcote Avenue, Feltham (TW13 4EG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL103951",
      "property_address": "land on the south side of Oxford Gardens, Kensington",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL105862",
      "property_address": "1 Bentworth Road, Wormholt",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL105999",
      "property_address": "70 Hadyn Park Road, Hammersmith (W12 9QG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL111598",
      "property_address": "55 Upperton Road West, London (E13 9LT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL114338",
      "property_address": "92 Roman Road, London (E6 3SR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL118109",
      "property_address": "3 Rossindel Road (TW3 3QN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL126366",
      "property_address": "Bowes Road Garage, 188 Bowes Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL140631",
      "property_address": "62 Haig Road West, London (E13 9LH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL162536",
      "property_address": "43 DAVIS STREET, LONDON E13 9EE",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL179439",
      "property_address": "15 Dabbs Hill Lane, Northolt",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL181568",
      "property_address": "land lying to the south east side of London Road, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL185628",
      "property_address": "4 Harold Road, Acton (NW10 7BE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL187106",
      "property_address": "60 Hiley Road, Willesden, (NW10 5PS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL190566",
      "property_address": "65 Chertsey Road, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL196968",
      "property_address": "36 Nevern Square, London (SW5 9PE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL199880",
      "property_address": "2 St Andrews Road, Hammersmith, (W14 9SX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL200109",
      "property_address": "108 and 110 Hammersmith Grove, London (W6 7HB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL206072",
      "property_address": "101 Kilburn Park Road, London (NW6 5LB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL216341",
      "property_address": "32 Mall Chambers, Kensington Mall, London (W8 4DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL226718",
      "property_address": "54 Pursley Road, London (NW7 2BS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL237296",
      "property_address": "Flat 5 Danebury, 9 St Quintin Gardens, London, and Garage 6, (W10 6AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL238331",
      "property_address": "Westgate House, London Road, Isleworth (TW7 4AR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL239144",
      "property_address": "5 Keats House, 34 Faraday Road, London, (W10 5RS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL239831",
      "property_address": "Russell Court, 108-112 Hammersmith Grove, London (W6 7HB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL242022",
      "property_address": "21 Sycamore Close, Northolt",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL245187",
      "property_address": "39 Ellesmere Road, Greenford (UB6 9ET)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL245635",
      "property_address": "Greystoke, Hanger Lane, London (W5 1AS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL249580",
      "property_address": "18 Fernside Avenue, Hanworth, (TW13 7BL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL253811",
      "property_address": "Flat B, 22 Upper Addison Gardens, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL259784",
      "property_address": "58 Pinehurst Court, 1 to 3 Colville Gardens, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL261793",
      "property_address": "18 Fruen Road, Feltham, (TW14 9NR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL262114",
      "property_address": "22 to 78 (even) Tavistock Crescent and 52 to 58 (even) St Luke's Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL262637",
      "property_address": "11 Catherine Gardens (TW3 2PP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL263368",
      "property_address": "59 Great North Way, London (NW4 1PT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL265524",
      "property_address": "2 Cromwell Street, Hounslow (TW3 3LQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL266213",
      "property_address": "94 Beresford Avenue, Hanwell",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL266898",
      "property_address": "104 Pinehurst Court, Colville Gardens",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL267024",
      "property_address": "85 Pinehurst Court, Colville Gardens",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL269132",
      "property_address": "Flat 3, 42 Oxford Gardens",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL270042",
      "property_address": "89 Pinehurst Court, Colville Gardens",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL273574",
      "property_address": "183 Ladbroke Grove, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL274724",
      "property_address": "Flats 1 to 30 (inclusive), Lewis House, 85 Canonbury Road, Flats 1 to 15 (inclusive), Mustang House, 87 Canonbury Road and Flats 1 to 13 (inclusive), Parnelli House, 10 Compton Avenue, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL276407",
      "property_address": "27 Wood End Lane, Northolt",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL277947",
      "property_address": "44 Pinehurst Court, 1 to 3 Colville Gardens",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL280633",
      "property_address": "2 Lancaster Lodge, 85 Lancaster Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL282217",
      "property_address": "27 Leythe Road, Acton (W3 8AW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL286659",
      "property_address": "1-15 (inc) Harrier Court, Siddeley Drive, Hounslow (TW4 7DL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL289735",
      "property_address": "7 Pinehurst Court, 1 to 3 Colville Gardens",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL291769",
      "property_address": "Flat 2, Caroline Court, 28 St Lukes Road, London (W11 1DJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL292543",
      "property_address": "19 Lancaster Lodge, 83 and 85 Lancaster Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL294847",
      "property_address": "194 and 194A Bowes Road, New Southgate, London (N11 2JH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL301011",
      "property_address": "96/98 Crispen Road, Feltham (TW13 6QR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL302219",
      "property_address": "28 Gratton Road, London (W14 0JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL303685",
      "property_address": "137 and 139 Praed Street, London (W2 1RL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL304900",
      "property_address": "31 Pinehurst Court, 1 to 3 Colville Gardens, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL304902",
      "property_address": "60 Pinehurst Court, 1 to 3 Colville Gardens, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL313974",
      "property_address": "Flat 2, 40 Bramham Gardens, London, (SW5 0HG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL31402",
      "property_address": "122 New Road, Bedfont",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL314083",
      "property_address": "22 CARDREW CLOSE, LONDON N12 9LE",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL3162",
      "property_address": "93 Sutton Lane and Garage",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL318007",
      "property_address": "Flat 1, 103 Campden Hill Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL323053",
      "property_address": "27 The Chase, Edgware (HA8 5DW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL323143",
      "property_address": "326 Latimer Road, London, (W10 6QN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL325281",
      "property_address": "121 Beaufort Park, London (NW11 6BY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL325312",
      "property_address": "the ground level garage 59 Beaufort Park, Falloden Way, Finchley",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL332686",
      "property_address": "9 University Close, Hendon and Parking Place",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL333583",
      "property_address": "Flat 13, 2-3 Ladbroke Square, London (W11 3LX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL336583",
      "property_address": "56 Draycott Place, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL337275",
      "property_address": "19 University Close, London and Garage (NW7 2LD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL33743",
      "property_address": "7 Capel Road, East Barnet",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL341781",
      "property_address": "12 Redcliffe Street, Kensington, London (SW10 9DT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL342322",
      "property_address": "159 Finborough Road, Kensington (SW10 9AP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL342351",
      "property_address": "20 Pursley Road, Mill Hill, London (NW7 2BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL344376",
      "property_address": "Flat 4, 41 Bramham Gardens, London (SW5 0HG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL344715",
      "property_address": "39 Wardell Close, London (NW7 2LG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL347265",
      "property_address": "Flat 1, 72 Lancaster Road, London (W11 1QR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL351880",
      "property_address": "53 to 61 Garden Close, Northolt",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL355274",
      "property_address": "9 Mirabel Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL355940",
      "property_address": "48 Wardell Close, Hendon",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL359501",
      "property_address": "88 Chesterfield Road, Barnet (EN5 2RF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL359656",
      "property_address": "Flat 16A, 164 Holland Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL361390",
      "property_address": "162 John Aird Court, Porteus Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL361505",
      "property_address": "47 Reading Road, Northolt (UB5 4PQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL361520",
      "property_address": "15 Shobden Road, London (N17 7PG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL364169",
      "property_address": "Block A, Dorset Wharf, 132 to 157 Rainville Road, London (W6 0JL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL366038",
      "property_address": "268B Latimer Road, London (W10 6QY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL366824",
      "property_address": "Flat 2, 69 Oxford Gardens, London (W10 5UJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL367495",
      "property_address": "13 Mordern House, Harewood Avenue",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL369693",
      "property_address": "18B Gunter Grove, Chelsea",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL37056",
      "property_address": "1-9 Ratcliffe Cross Street, London (E1 0HS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL371892",
      "property_address": "5 Canterbury Road, Hanworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL376772",
      "property_address": "51 Drayton Green, London (W13 0JE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL379695",
      "property_address": "6 Buckingham Avenue, Perivale, Greenford (UB6 7RA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL380934",
      "property_address": "69 Elgin Avenue, London (W9 2DB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL384449",
      "property_address": "128 Hazelmere Road, Northolt (UB5 6UW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL385385",
      "property_address": "83 Haig Road, Uxbridge (UB8 3EQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL391205",
      "property_address": "First Floor Flat 3, 42 Chesterton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL39309",
      "property_address": "Flat 18, 28 Pembridge Square, London (W2 4DS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL394157",
      "property_address": "Flat 6, 16 Hatherley Grove, London (W2 5RB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL394314",
      "property_address": "22 Standard Road, Hounslow (TW4 7AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL394831",
      "property_address": "the second floor flat, 39 Chesterton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL394953",
      "property_address": "52 Eynham Road, Shepherds Bush, (W12)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL396737",
      "property_address": "69B Elsham Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL397649",
      "property_address": "33 Nupton Drive, Barnet (EN5 2QU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL398591",
      "property_address": "83, 85, 85a and 85b Crowland Road, London  (N15 6UL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL399112",
      "property_address": "179 Fairmead Crescent, Edgware (HA8 8YS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL399555",
      "property_address": "Flat 2, 38 Oxford Gardens, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL401453",
      "property_address": "Courtenay, Duncan Close, Plantagenet Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL405998",
      "property_address": "York House, York Avenue, London (W7 3HY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL406236",
      "property_address": "11a Harte Road, Hounslow (TW3 4LD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL406589",
      "property_address": "Flat 6, 10 Colville Road, London (W11 2BS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL409715",
      "property_address": "18B Vicarage Gate, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL410142",
      "property_address": "2 Corsley Way, London (E9 5PD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL413184",
      "property_address": "2 Crofters Close, Isleworth (TW7 7PH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL413518",
      "property_address": "Flat 15, 16 Nevern Square, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL414539",
      "property_address": "47-51 (Odd) Oxford Road and 9, 11, 15, 18, 22 and 24, 29-33 (Odd) Windsor Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL414597",
      "property_address": "Flat D, 240 Old Brompton Road, London (SW5 0DE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL414721",
      "property_address": "9 Thatchers Way, Whitton Croft Estate, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL416884",
      "property_address": "178 Colin Gardens, Hendon",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL417018",
      "property_address": "30 to 39 and 55 to 60 Aspen Close and parking spaces",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL417019",
      "property_address": "the block of flats and parking spaces known as plots 30 to 52 Rowan Close, Almond Avenue, Ealing and parking spaces",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL417057",
      "property_address": "32 Coronation Court, Brewster Gardens, London, (W10 6AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL417060",
      "property_address": "39 Coronation Court, Brewster Gardens, London, (W10 6AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL417228",
      "property_address": "Parking Space K, Flats 1 to 11 (inclusive) 42 Lime Grove and 1 to 59 (odd) Scott's Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL417874",
      "property_address": "72 Upper Sutton Lane, Heston",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL419472",
      "property_address": "103 Tudor Road, Hayes (UB3 2QE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL421251",
      "property_address": "Flat 6, 107 Warwick Road, Earls Court",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL421749",
      "property_address": "Flat 16, Courtleigh, 126 Earls Court Road, London (W8 6QL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL421768",
      "property_address": "22 Courtleigh, 126 Earl's Court Road, London, (W8 6QL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL421996",
      "property_address": "the first floor maisonette 536A Harrow Road, (W9 3QF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL423748",
      "property_address": "Flat C, 93 Ifield Road, Kensington, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL424916",
      "property_address": "Flats 1 to 12 (inclusive) and 14 to 25 (inclusive) Castlebar Court, Queens Walk, London (W5 1TP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL424917",
      "property_address": "William Court, Buckingham Close, London W5 1TU",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL42626",
      "property_address": "70 Orchard Grove, Kenton, Harrow (HA3 9QS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL426693",
      "property_address": "15 Thatchers Way, Whitton Croft Estate, Isleworth, (TW7 7PL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL429786",
      "property_address": "39 Grovestile Way, Bedfont",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL430668",
      "property_address": "3 Reapers Way, Hall Road, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL430831",
      "property_address": "68 Somerset Road, Acton, garden ground and shed (W4 5DN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL431806",
      "property_address": "Flat C, 18 Gunnersbury Avenue (W5 3QL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL43194",
      "property_address": "15 New Court, Lordship Road And Parking Space Hackney",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL436132",
      "property_address": "49 Sparrow Farm Drive, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL436862",
      "property_address": "10 Hillmarton Road, London (N7 9JW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL438041",
      "property_address": "536B Harrow Road, (W9 3QF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL438347",
      "property_address": "119 Whitton Avenue East, Greenford (UB6 0QE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL438366",
      "property_address": "14 Broomcroft Avenue, Northolt (UB5 6HZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL438775",
      "property_address": "30 Dacre Close, Greenford and car parking space (UB6 9UQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL439413",
      "property_address": "49A Barnsdale Road, (W9 3LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL441320",
      "property_address": "Flat 8, 1 Bassett Road, London, (W10 6LA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL443078",
      "property_address": "Ground Floor Flat, 95 Chesterton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL443492",
      "property_address": "40 to 46 (even) Waynflete Square, 61 to 79 (odd) Bramley Road and 23 to 31 (odd) Silchester Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL443708",
      "property_address": "21 Browngraves Road, Harlington, Hayes (UB3 5BN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL444734",
      "property_address": "14 Dacre Close, Greenford, and car parking space",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL445026",
      "property_address": "42 Harvesters Close, Hall Road, Isleworth (TW7 7PP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL445027",
      "property_address": "10 Lanata Walk, Hayes (UB4 9PY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL445048",
      "property_address": "Hurley Court, 57 Castlebar Road, Ealing",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL446582",
      "property_address": "28 Hewer Street, London (W10 6DU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL447225",
      "property_address": "27 Rowan Close, Almond Avenue, Ealing and Parking Space 17 (W5 4AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL447226",
      "property_address": "23 Rowan Close, Almond Avenue, Ealing and Parking Space 18 (W5 4AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL447314",
      "property_address": "79 Rowan Close, Almond Avenue, Ealing and Parking Space 46 (W5 4AY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL447647",
      "property_address": "50 Twybridge Way, London (NW10 0ST)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL448329",
      "property_address": "122 Barlby Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL449431",
      "property_address": "4 Pentelow Gardens, Bedfont, (TW14 9EE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL450200",
      "property_address": "28 Beagle Close",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL450642",
      "property_address": "Flat 1, 53 Truro Road, Wood Green, (N22 4EH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL450819",
      "property_address": "75 Rowan Close, Almond Avenue and Parking Space 41 (W5 4AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL450940",
      "property_address": "28 Meadfield, Edgware, (HA8 8XW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL451581",
      "property_address": "11 West End Lane, London (NW6 4NU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL452510",
      "property_address": "97 Rowan Close, Almond Avenue, Ealing and Parking Space 52 (W5 4AY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL453164",
      "property_address": "14 Lanata Walk, Hayes, (UB4 9PY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL454378",
      "property_address": "16 Blossom Close, Ealing (W5 4YF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL454618",
      "property_address": "21 Harvesters Close, Isleworth (TW7 7PP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL454753",
      "property_address": "Flat 3, 558 and 558A Harrow Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL454917",
      "property_address": "37, 38, 44, 45, 46, 47 Pippins Close, West Drayton",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL456503",
      "property_address": "2 The Lindens, Hartington Road, Chiswick",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL457308",
      "property_address": "being part of 33 Hadyn Park Road, (W12 9AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL458286",
      "property_address": "92 Barlby Road, London (W10 6AP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL458812",
      "property_address": "6 Trevor Gardens, Edgware (HA8 0EY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL459040",
      "property_address": "69 Tivoli Road, Hounslow (TW4 6AD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL459768",
      "property_address": "19 Repens Way, Hayes (UB4 9PR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL460855",
      "property_address": "24 Repens Way, Hayes (UB4 9PS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL461241",
      "property_address": "47 Hambledon Close, (UB8 3UD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL46200",
      "property_address": "16 Khartoum Road, London (E13 8RF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL466925",
      "property_address": "Land at the rear of 90 Grimsdyke Road, (HA5 4PW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL467428",
      "property_address": "Flat 6, 1 Bassett Road, London, (W10 6LA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL468282",
      "property_address": "117 Mogden Lane, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL472156",
      "property_address": "land lying between the former rear garden of 300 Church Road and the End of Garden Close, Northolt",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL474269",
      "property_address": "6 Gloucester Road, Hounslow (TW4 6AB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL476967",
      "property_address": "land at the back of 55 Redhill Drive, Edgware (HA8 5JL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL476996",
      "property_address": "51 Almond Avenue, (W5 4AB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL477106",
      "property_address": "10 Wainwright Grove, Whitton Croft, Isleworth (TW7 7PU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL477390",
      "property_address": "33 Pippins Close, West Drayton, (UB7 7XH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL478139",
      "property_address": "23 Wainwright Grove, Whitton Croft, Isleworth (TW7 7PU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL478380",
      "property_address": "22 Wainwright Grove, Whitton Croft, Isleworth (TW7 7PU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL478712",
      "property_address": "69 Makepeace Road, Northolt (UB5 5UG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL479048",
      "property_address": "land at the back of 150 St Stephen's Road, Hounslow (TW3 2BW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL479347",
      "property_address": "Churchill Court, 94 Ashbourne Road, London (W5 3DL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL483241",
      "property_address": "30 Vicarage Close, Northholt (UB5 5AD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL484679",
      "property_address": "Flat 3, 13 Longridge Road, London, (SW5 9SB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL485409",
      "property_address": "8 Wainwright Grove, Whitton Croft, Isleworth (TW7 7PU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL487005",
      "property_address": "44 George Crescent, Muswell Hill (N10 1AN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL487642",
      "property_address": "1 to 23 (inclusive) Addison Place, Southall (UB1 3QX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL488048",
      "property_address": "Flat 1, 184 Portobello Road (W11 2EB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL488207",
      "property_address": "16 Britannia Close, Northolt and Parking Space (UB5 6JY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL488597",
      "property_address": "184 Sparrow Farm Drive, Feltham, (TW14 0DQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL489158",
      "property_address": "29 Homefield Road, Burnt Oak, Edgware (HA8 0PT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL490453",
      "property_address": "119 Chaplin Road, Wembley, (HA0 4UN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL490863",
      "property_address": "6 Edinburgh House, 56 and 57 Courtfield Gardens, London (SW5 0NF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL491279",
      "property_address": "16 Chesterton Road, London (W10 5LX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL492461",
      "property_address": "Flat 2, 115 Bravington Road, (W9 3AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL493816",
      "property_address": "190 Noel Road, London (W3 0JR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL493846",
      "property_address": "Flat 5, 13 Longridge Road, London, (SW5 9SB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL496965",
      "property_address": "Flat 2, 35 Nevern Square (SW5 9PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL498097",
      "property_address": "Flat 4, 50 Clanricarde Gardens, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL498874",
      "property_address": "12 to 28 North End Road and 18 Southcombe Street, Hammersmith, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL499423",
      "property_address": "77A Wakeman Road, Willesden, London, (NW10 5BH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL505057",
      "property_address": "91A OXFORD GARDENS, LONDON W10 5UL",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL505198",
      "property_address": "2 East Walk, Hayes (UB3 3JJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL507449",
      "property_address": "38 Sandringham Road (NW2 5ER)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL507836",
      "property_address": "5 Coronation Court, Brewster Gardens, London (W10 6AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL509398",
      "property_address": "23B Askew Road, Shepherd's Bush, (W12 9AD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL510680",
      "property_address": "7 Merlin Close, Northolt",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL511756",
      "property_address": "Flat 13, 51 Earls Court Square, London (SW5 9DG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL513714",
      "property_address": "12 Grebe, Broadhead Strand, Grahame Park Estate, (NW9 5PS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL518325",
      "property_address": "Flat 2, 43 Gunter Grove",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL518592",
      "property_address": "Flat 5, 76 Cambridge Gardens, London, (W10 6HS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL520651",
      "property_address": "Flat 8, 43 Sutherland Avenue, (W9 2HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL521116",
      "property_address": "1 to 47 (odd) Holley Road, London (W3 7TR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL523167",
      "property_address": "Flat 9, 69 Earls Court Square, London (SW5 9DG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL524651",
      "property_address": "65 Weavers Close, Isleworth (TW7 6ET)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL524657",
      "property_address": "58 Weavers Close",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL529282",
      "property_address": "Flat E, 46 Fairhazel Gardens (NW6 3SJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL529287",
      "property_address": "Flat 4, Eardley Crescent, ((SW5 9JZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL529446",
      "property_address": "2 Cottage, 58 Ivy House Road, Ickenham, Uxbridge and Parking Space 2 (UB10 8LZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL530468",
      "property_address": "16 Dryfield Road, Burnt Oak, Edgware, (HA8 9JR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL530473",
      "property_address": "Flat 3, 23 Great Western Road (W9 3NW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL531475",
      "property_address": "57D Talgarth Road, Hammersmith (W14 9DD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL532331",
      "property_address": "32A St Charles Square, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL532944",
      "property_address": "17 Notting Barn Road, London (W10 5YW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL533001",
      "property_address": "1st Floor Flat, 93 Golborne Road, London (W10 5NL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL533417",
      "property_address": "193C Lanark Road, (W9 1NX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL533881",
      "property_address": "26 Beechwood Grove, East Acton Lane, (W3 7HX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL534216",
      "property_address": "5 Gold Hill, Burnt Oak, Edgware (HA8 9BY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL534524",
      "property_address": "Flat 6, 89 Cambridge Gardens, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL535338",
      "property_address": "53 Eardley Crescent, London, (SW5 9JT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL536234",
      "property_address": "9 Norseman Way, Greenford (UB6 8LR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL537026",
      "property_address": "42 Bevington Road, London (W10 5TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL537061",
      "property_address": "Flat 1, 5 Longridge Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL537477",
      "property_address": "4a Chesson Road, Fulham",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL539371",
      "property_address": "30 Avondale Park Road, London (W11 4HJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL539736",
      "property_address": "Flat 5, 73 Holland Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL539752",
      "property_address": "84 Edenham Way, London (W10 5XD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL541995",
      "property_address": "10b Thyra Grove, London (N12 8HB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL542446",
      "property_address": "14 Hill Farm Road, London (W10 6DN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL543291",
      "property_address": "Flats 1 to 9 (inclusive) Sunnymead Court 46 Oxford Road and 61 Western Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL543409",
      "property_address": "36 Cromwell Close, Acton and parking space 36",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL545378",
      "property_address": "land lying to the south east of London Road, Isleworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL546741",
      "property_address": "99 Orange Hill Road, Burnt Oak, Edgware, (HA8 0TJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL546868",
      "property_address": "3 Lily Gardens, Wembley (HA0 1DL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL547082",
      "property_address": "16 Barfield Avenue, Whetstone",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL547301",
      "property_address": "Flat 8, 82 Cambridge Gardens, London (W10 6HS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL547402",
      "property_address": "1 to 36 (inclusive) Walker Close and land at Walker Close, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL548856",
      "property_address": "Flat 17, 45 and 47 Courtfield Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL551521",
      "property_address": "44 Brownswell Road, London (N2 8LA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL552608",
      "property_address": "31 Ramillies Road, London (NW7 4LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL554463",
      "property_address": "50 to 58 (even) Glenthorne Road, London (W6 0LN).",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL555594",
      "property_address": "216 Southfield Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL556437",
      "property_address": "Flat B, 1 St Quintin Gardens, London (W10 6AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL556531",
      "property_address": "4 Barnes Avenue, Norwood Green, Southall",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL557242",
      "property_address": "34a Elsham Road, London (W14 8HB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL559206",
      "property_address": "54 Blessbury Road, Edgware (HA8 0SX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL559762",
      "property_address": "7b North Pole Road, London (W10 6QH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL561013",
      "property_address": "37,51,61 and 71 Kilross Road, 57,58,59,60 and 62 Loxwood Close, 6,9,10, 12 to 22 (inclusive) Sledmere Court and 2,4 and 6 Padbury Close, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL562453",
      "property_address": "16 Ambleside Drive, Feltham",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL562533",
      "property_address": "9 Kendal Close, Feltham and garage (TW14 9QG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL564636",
      "property_address": "62 Ringway, Southall",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL565961",
      "property_address": "172 Abbots Road, Edgware (HA8 0SA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL565980",
      "property_address": "159 Horsenden Lane South, Greenford",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL573622",
      "property_address": "60 Milson Road, London (W14 0LB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL574077",
      "property_address": "Flat B, 10 Stadium Street, Kensington and Chelsea, London (SW10 0PT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL575981",
      "property_address": "Flat 3, 345 Ladbroke Grove, London (W10 6HA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL576190",
      "property_address": "26 Fernhead Road (W9 3EZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL576622",
      "property_address": "26 Norwich Walk, Burnt Oak, Edgware (HA8 0UA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL577514",
      "property_address": "Flat 2, 56 Pembroke Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL578247",
      "property_address": "63 Tynemouth Street, London (SW6 2QS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL582618",
      "property_address": "34G Elsham Terrace, Holland Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL582748",
      "property_address": "First Floor Flat, 335 Portobello Road, London (W10 5SA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL583022",
      "property_address": "Flat 3, 198 Ladbroke Grove, London W10 5LZ",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL583282",
      "property_address": "Flat 1, 345 Ladbroke Grove, Kensington, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL584299",
      "property_address": "1-11 (inclusive), Charlotte Mews, London (W10 6UJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL585137",
      "property_address": "Flat D, 2 Coomassie Road, Paddington, (W9 3BW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL585535",
      "property_address": "1 - 12 (inclusive) Shilling Place, Grosvenor Road, London and Flat B and C, 78 Grosvenor Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL585713",
      "property_address": "1 to 6 Kerrington Court, 314 Ladbroke Grove, 7 to 12 Kerrington Court, 316 Ladbroke Grove, 14 to 20 Kerrington Court, 318 Ladbroke Grove and shop Units 312, 314A, 314B, 316A, 316B and 318A Ladbroke Grove, London (W10 5NQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL586311",
      "property_address": "5A St Ervan's Road (W10 5QX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL586477",
      "property_address": "First Floor Flat, 11 Saltram Crescent, Maida Vale, London (W9 3JR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL587721",
      "property_address": "Flat 4, 3 St Charles Square",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL588085",
      "property_address": "8 Verity Close, London (W11 4HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL588091",
      "property_address": "Flat 19, Frampton House, 58-74 Frampton Street, London (NW8 8LY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL588351",
      "property_address": "39 Rasper Road, Whetstone",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL588563",
      "property_address": "Flat 12, 196 Cromwell Road, London, (SW5 0SN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL588836",
      "property_address": "Flat 4, 212 Fulham Road, London (SW10 9PJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL58918",
      "property_address": "1 Bowes Road, London (N13 4UX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL590458",
      "property_address": "160 to 164 (even) Royal College Street, London (NW1 0TA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL591266",
      "property_address": "286 Ladbroke Grove, London (W10 5LP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL591618",
      "property_address": "Flat 60, Lapworth Court, Blomfield Villas, London (W2 6NN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL592011",
      "property_address": "90 Hazlebury Road, Fulham",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL592691",
      "property_address": "Flat 12, Dartington House, Senior Street, London (W2 5TE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL593793",
      "property_address": "Flat 3, 202 Ladbroke Grove, London (W10 5LZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL595322",
      "property_address": "124 Askew Road, London (W12 9BL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL595830",
      "property_address": "Flat 2, 286 and 288 Latimer Road, London, (W10 6QW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL596388",
      "property_address": "Flat 4, 286 and 288 Latimer Road, London (W10 6QW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL597615",
      "property_address": "79 Fallow Court Avenue, London (N12 0BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL599112",
      "property_address": "Flat 3, 31 Eardley Crescent",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL600071",
      "property_address": "150 Norwood Road, Southall, (UB2 4JS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL602051",
      "property_address": "81 Sirdar Road, London (W11 4EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL603000",
      "property_address": "35 Frensham Close, Southall (UB1 2YF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL6035",
      "property_address": "7 Bowes Road, London (N13 4UX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL605206",
      "property_address": "43 Chesterton Road, London, (W10 6ES)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL607172",
      "property_address": "Flat 5, 286 and 288 Latimer Road, London (W10 6QW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL608408",
      "property_address": "Tullis Works, Sussex Place",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL608923",
      "property_address": "Flat B, 148 Fernhead Road, Paddington (W9 3EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL609103",
      "property_address": "36B Ramillies Road, Bedford Park",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL609907",
      "property_address": "Flat 1, 11 Hogarth Road, London (SW5 0QH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL609991",
      "property_address": "36 Queens Avenue, London (N3 2NP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL610263",
      "property_address": "Gaudin Court, 1 Elland Close and Montbard Court, 2 Elland Close and Ridefort Court, 27a York Road and Tremelay Court, 3 Elland Close and 83 Gloucester Road, Barnet",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL612911",
      "property_address": "58 Chesterfield Road, Barnet (EN5 2RF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL613408",
      "property_address": "94 to 100 (even) Chepstow Road, London (W2 5QP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL614140",
      "property_address": "Flat 3, 182 Ladbroke Grove, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL614929",
      "property_address": "22 Gibbs Green",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL615375",
      "property_address": "116 Beaconsfield Road, London (N11 3AJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL620138",
      "property_address": "86 Hamilton Road, Hendon, London (NW11 9DY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL620146",
      "property_address": "172 Great Western Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL620427",
      "property_address": "22 Allom House, Clarendon Road, Kensington, (W11 4JJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL620527",
      "property_address": "10 Torrington Road, Perivale, Greenford (UB6 7EW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL621496",
      "property_address": "121a Kilburn Park Road, London (NW6 5LB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL624115",
      "property_address": "18 Thurso House, Randolph Gardens, (NW6 5EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL624313",
      "property_address": "Flat 29, Shottsford, 100 Talbot Road, London (W2 5LG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL626161",
      "property_address": "10 Swan Court, High Road, London (N20 0PS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL626462",
      "property_address": "Flat A, 16 Bollo Bridge Road, London (W3 8AT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL626973",
      "property_address": "173d Shirland Road, London (W9 2EU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL627922",
      "property_address": "Flat 13, Frith House, 46-56 Frampton Street, London (NW8 8LX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL628034",
      "property_address": "31 Atherstone Court, Delamere Terrace, London (W2 6PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL629438",
      "property_address": "21a Grove Road, Cockfosters, Barnet (EN4 9DH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL630689",
      "property_address": "Ground Floor Flat, 357 Portobello Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL631049",
      "property_address": "23 and 25 Cambridge Grove, Hammersmith (W6 0LA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL631843",
      "property_address": "155 Flora Gardens, Hammersmith, (W6 0HS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL632083",
      "property_address": "46 Shepherds Walk, London (NW2 7BS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL632424",
      "property_address": "186A Crescent Road, New Barnet, (EN4 8SB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL635134",
      "property_address": "7 Drayford Close, London (W9 3DJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL635739",
      "property_address": "18 Cranfield Drive, Hendon, London (NW9 5WH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL636186",
      "property_address": "Flat B, 54 Portnall Road (W9 3BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL637883",
      "property_address": "26 Pavilion Terrace, Wood Lane, Hammersmith",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL638282",
      "property_address": "Flat 9, Fairfield, Arlington Road, London (NW1 7LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL638976",
      "property_address": "33 Stoneleigh Street, (W11 4DU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL638984",
      "property_address": "24 Meadfield, Edgware",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL641117",
      "property_address": "Flat 7, Hanwell House, Great Western Road, London (W2 5UQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL641905",
      "property_address": "83 Robert Street, St Pancras, London (NW1 3JS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL642052",
      "property_address": "Flat 15, Pembroke House, Hallfield Estate, London (W2 6HG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL644553",
      "property_address": "Flat 12, Winchester House, Hallfield Estate, London (W2 6EA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL644709",
      "property_address": "99 Acklam Road, Swinbrook Estate, Kensington, (W10 5YU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL646207",
      "property_address": "21 Hawkins Close, West Harrow",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL646546",
      "property_address": "Flat D, 3 Elgin Avenue, Walterton Estate, (W9 3PR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL64707",
      "property_address": "21 Iverson Road, Kilburn, London (NW6 2QT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL647544",
      "property_address": "Alexandra Court and Lytten Court, Becklow Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL647696",
      "property_address": "Flat 24, Whitebeam House, Maitland Park Road, London (NW3 2HG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL648472",
      "property_address": "Flat 5, 5 Exmoor Street, London (W10 6BB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL648857",
      "property_address": "357, 359 and 361 Harrow Road, London (W9 3NA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL648901",
      "property_address": "Flat 15, Cooper House, Lyons Place, London (NW8 8NJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL650166",
      "property_address": "26 Wornington Road, Kensington, (W10 5YF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL650241",
      "property_address": "Flat 27, Harford House, 35 Tavistock Crescent, London (W11 1AY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL650363",
      "property_address": "32 Compton Close, Robert Street, (NW1 3QS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL650741",
      "property_address": "25 Wornington Road, (W10 5QJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL650852",
      "property_address": "28 Shalfleet Drive, Bramley Road, Kensington, (W10 6UB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL651723",
      "property_address": "Flat 1, Greenaway House, Boundary Road, London (NW8 0HT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL653129",
      "property_address": "46 Bevington Road, Kensington (W10 5TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL653372",
      "property_address": "150B Bravington Road (W9 3AP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL654074",
      "property_address": "16 Lambourn Close, Lady Margaret Road, (NW5 2NL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL654244",
      "property_address": "30 Drayford Close, London (W9 3DJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL65431",
      "property_address": "98 Wheatlands, Hounslow (TW5 0SB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL654935",
      "property_address": "8 Elsham Road, London (W14 8HA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL655388",
      "property_address": "38A Wendover Road, Willesden (NW10 4RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL65948",
      "property_address": "37 St John's Road, Isleworth (TW7 6NY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL665371",
      "property_address": "22 Studholme Court, Finchley Road, London (NW3 7AE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL665399",
      "property_address": "54 Brent Terrace, Cricklewood, London (NW2 1BY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL667222",
      "property_address": "Flat 21, Barlow House, Walmer Road, London (W11 4EU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL667696",
      "property_address": "Flat 26, Russell House, Cambridge Street, London (SW1V 4EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL669078",
      "property_address": "Flat 54, Harford House, 35 Tavistock Crescent, London (W11 1AY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL669628",
      "property_address": "80 Durdans House, Royal College Street, London (NW1 9RD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL670249",
      "property_address": "54 Wellesley Road, London (NW5 4PN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672200",
      "property_address": "Flat 30, 119 Highgate Road, London (NW5 1TR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672576",
      "property_address": "4 Kerrington Court, 314 Ladbroke Grove, Kensington, (W10 5NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672581",
      "property_address": "5 Kerrington Court, 314 Ladbroke Grove, Kensington, (W10 5NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672583",
      "property_address": "7 Kerrington Court, 316 Ladbroke Grove, Kensington, (W10 5NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672586",
      "property_address": "10 Kerrington Court, 316 Ladbroke Grove, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672591",
      "property_address": "16 Kerrington Court, 318 Ladbroke Grove, Kensington, (W10 5NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672592",
      "property_address": "17 Kerrington Court, 318 Ladbroke Grove, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL672600",
      "property_address": "20 Kerrington Court, 318 Ladbroke Grove, Kensington, (W10 5NQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL673088",
      "property_address": "77 Well Road, Barnet (EN5 3EA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL675439",
      "property_address": "27 Brassey Road, London (NW6 2BD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL676702",
      "property_address": "8 Becklow Gardens, Hammersmith, (W12 9HD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL677129",
      "property_address": "16 Lytten Court, 55 Becklow Road, Hammersmith, London, (W12 9HN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL678842",
      "property_address": "First Floor Flat, 80 Dyne Road, London (NW6 7DS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL679190",
      "property_address": "39c Uverdale Road, London (SW10 0SN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL679378",
      "property_address": "Flat 9, Kennet House, Church Street Estate, London (NW8 8HB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL680152",
      "property_address": "Flat 31, Chalton House, Chalton Street, London (NW1 1HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL680168",
      "property_address": "116B Clifford Gardens (NW10 5JB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL680207",
      "property_address": "17 Eresby Place, London (NW6 4JT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL682612",
      "property_address": "26 Durston, Grafton Road, London (NW5 4RH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL682635",
      "property_address": "2 - 14 (even) Beavor Lane, London and 1 - 34 (inclusive) Chambon Place, London and 1 - 33 (inclusive) Aiten Place, London and 1 - 19 (odd) Standish Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL682692",
      "property_address": "20 Matthew Close, London (W10 5YJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL683920",
      "property_address": "35A St Ervans Road, Kensington, (W10 5QX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL683945",
      "property_address": "54 Meadfield, Edgware",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL685400",
      "property_address": "Rufforth Court, 61 Pageant Avenue, Riccall Court, 62 Pageant Avenue and 37 to 60 Pageant Avenue, Colindale, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL685535",
      "property_address": "134 Cheesemans Terrace, London (W14 9XJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL685664",
      "property_address": "Flat 4, Charfield Court, 2 Shirland Road, London (W9 2JN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL686378",
      "property_address": "1-4 (inc) and 19-23 (inc), Blake Close and land at Blake Close, London (W10 6AY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL689236",
      "property_address": "37 Ravensbourne House, Broadley Street, London (NW8 8BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL689484",
      "property_address": "18 to 36 (inclusive) Pageant Avenue and 1 to 16 (inclusive) Driffield Court, 64 Pageant Avenue (NW9 5LQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL69212",
      "property_address": "Flat 3, 114 Holland Road, Kensington",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL695866",
      "property_address": "67 Wellesley Road, London (NW5 4PL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL697737",
      "property_address": "Lindholme Court, 63 Pageant Avenue, London (NW9 5LZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL699324",
      "property_address": "Flat 4, 58 Tufnell Park Road, London (N7 0DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL700011",
      "property_address": "79 Bravington Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL701044",
      "property_address": "30 Botany Close, Crescent Road, New Barnet and parking space 30, (EN4 9RF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL701237",
      "property_address": "16 Botany Close, Crescent Road, New Barnet and Parking Space 16, (EN4 9RX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL701430",
      "property_address": "17 Sovereign Grove, Wembley and parking space 17 (HA0 2DZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL701658",
      "property_address": "117 Maitland Park Road, London (NW3 2HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL701700",
      "property_address": "Flat 20, Ashburton House, 44 Fernhead Road, London (W9 3ER)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL702149",
      "property_address": "13 Nettlecombe, Agar Grove, (NW1 9SN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL70347",
      "property_address": "20 Lawrence Road, Plaistow, (E13 0QD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL703591",
      "property_address": "Moore Court, 2-10 Alexandra Road, London (NW8 0DR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL704087",
      "property_address": "Land on the North side of Alexandra Road, Hampstead",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL704608",
      "property_address": "four areas of land at Fulbeck Drive, Hendon, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL708852",
      "property_address": "22B Herbert Street, St Pancras, (NW5 4HD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL709056",
      "property_address": "9 Astley Avenue, Willesden",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL709214",
      "property_address": "110 Montrose Avenue, Edgware (HA8 0DR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL710708",
      "property_address": "23 Ancona Road, Willesden, (NW10 5YD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL71140",
      "property_address": "76 Askew Road, London (W12 9BJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL712720",
      "property_address": "Raised Ground Floor Flat, 70B Pyrland Road, London (N5 2JD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL713422",
      "property_address": "78 Beaufort Park, London (NW11 6BX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL714074",
      "property_address": "2 Frith House, Frampton Street, London (NW8 8LX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL714566",
      "property_address": "596 Harrow Road, London (W10 4NJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL714703",
      "property_address": "1 and 3 Alexandra Place and 36 Boundary Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL715593",
      "property_address": "Flat 2, Marshwood House, Kilburn Vale, London (NW6 4QP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL717808",
      "property_address": "Flats 1, 2, 3, 4, 5, 6 to 13 (inclusive), 14 to 18 (inclusive), 19, 20, 21 and 23 to 25 (inclusive), 17 Chapter Street and 19 Chapter Street, London (SW1P 4NF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL718844",
      "property_address": "235A Kilburn Lane",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL719062",
      "property_address": "2 Hornbeams Rise, London (N11 3PB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL720429",
      "property_address": "28 St Paul's Crescent, St Pancras, (NW1 9XL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL720436",
      "property_address": "137 Ashurst Road, London (N12 9AD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL722524",
      "property_address": "46 to 60 (all) Byron Mews, Hampstead, (NW3 2NQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL722630",
      "property_address": "216a Chamberlayne Road, Kensal Rise",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL722872",
      "property_address": "Flat 20, Ainsworth House, Boundary Road, London (NW8 0HY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL724005",
      "property_address": "59a Fernhead Road, London (W9 3EY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL724042",
      "property_address": "63b Croftdown Road, London (NW5 1EY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL726997",
      "property_address": "71 to 75 (odd) Fortess Road, London (NW5 1AG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL729017",
      "property_address": "19 to 30 (inclusive) Collard Place and land at Collard Place, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL730524",
      "property_address": "1 Grafton Crescent, London (NW1 8SL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL730755",
      "property_address": "Flat 5, Katrine Court, Shobroke Close, London (NW2 6YU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL737187",
      "property_address": "29 Campbell Gordon Way, London and parking space 29A (NW2 6RS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL737189",
      "property_address": "31 Campbell Gordon Way, London and parking space 31A (NW2 6RS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL737190",
      "property_address": "32 Campbell Gordon Way, London and parking space 32A (NW2 6RS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL737421",
      "property_address": "5 GREENS COURT, LONDON W1F 0HF",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL745246",
      "property_address": "48 Milford Gardens, Wembley (HA0 2AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL745805",
      "property_address": "Flat 9, Dulverton, Royal College Street, London (NW1 0SB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL746107",
      "property_address": "Flat 6, Oak House, Maitland Park Villas, London (NW3 2ED)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL749724",
      "property_address": "11a, 11b, 11c And, 11d Birchington Road, Kilburn, London (NW6 4LL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL750347",
      "property_address": "90C Portnall Road, London (W9 3BE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL754751",
      "property_address": "1 to 6 (inclusive) Worcester Close and land lying to the north of Dollis Hill Lane, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL757891",
      "property_address": "5 Cyprus Court, Cyprus Road, Finchley (N3 3RU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL759159",
      "property_address": "Flat 49, Durdans House, Farrier Street, London (NW1 9RB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL762588",
      "property_address": "206 Roundwood Road, Willesden, (NW10 3UG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL763897",
      "property_address": "59 to 65 (odd) Belsize Road, London (NW6 4BE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL767129",
      "property_address": "38A Warlock Road, (W9 3LP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL767133",
      "property_address": "3a Lydford Road, London (W9 3LU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL767134",
      "property_address": "35A Fernhead Road, (W9 3EX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL768825",
      "property_address": "Flat 14, Ash House, Heather Walk, London (W10 4RL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL768858",
      "property_address": "86 Kenbrook House, Leighton Road, London (NW5 2QW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL769143",
      "property_address": "10 Field Lodge, 37 Beaconsfield Road and parking space 10 (NW10 2JE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL772967",
      "property_address": "60 Sellons Avenue, London (NW10 4HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL773664",
      "property_address": "192b Shirland Road, London (W9 3JF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL774306",
      "property_address": "Flat 29, Durdans House, Farrier Street, London (NW1 9RB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL778903",
      "property_address": "49 Barnsdale Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL778904",
      "property_address": "3 Elgin Avenue, London (W9 3PR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL779859",
      "property_address": "Flat 72 Morris House, Salisbury Street, London (NW8 8QB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL781623",
      "property_address": "Flat 25, Ludham, Lismore Circus, London (NW5 4SE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL785235",
      "property_address": "11A King Henry's Walk (N1 4NW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL798210",
      "property_address": "Barrett Court, Jubilee Close, London (NW10 9DY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL798212",
      "property_address": "Futters Court, Jubilee Close, London (NW10 9DX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL809737",
      "property_address": "Williams House, Pearce House, Earle House, Tounson Court, Dolben Court, 82 Steward House, Horsley Court, Zachary Court, 4,6 and Andrews House 10 Montaigne Close and an electricity substation Vincent Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL809738",
      "property_address": "Pearce House, Montaigne Close more particularly described in the lease, (SW1P 4AY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL809739",
      "property_address": "Williams House, Montaigne Close, London (SW1P 4AZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL812254",
      "property_address": "Flat 24, 4 Mildmay Park, London, (N1 4PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL812255",
      "property_address": "Flat 23, 4 Mildmay Park, London, (N1 4PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL812259",
      "property_address": "Flat 21, 4 Mildmay Park, London, (N1 4PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL812266",
      "property_address": "Flat 13, 4 Mildmay Park, London, (N1 4PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL812270",
      "property_address": "Flat 7, 4 Mildmay Park, London, (N1 4PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL812271",
      "property_address": "Flat 6, 4 Mildmay Park, London, (N1 4PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL816911",
      "property_address": "Flat 7, Ellery Court, Jubilee Close, London, (NW10 9DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL816912",
      "property_address": "Flat 8, Ellery Court, Jubilee Close, London, (NW10 9DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL816913",
      "property_address": "Flat 9, Ellery Court, Jubilee Close, London, (NW10 9DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL816914",
      "property_address": "Flat 10, Ellery Court, Jubilee Close, London, (NW10 9DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL816915",
      "property_address": "Flat 11, Ellery Court, Jubilee Close, London, (NW10 9DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL816918",
      "property_address": "Flat 13, Ellery Court, Jubilee Close, London, (NW10 9DZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL8241",
      "property_address": "352 Kilburn Lane, Paddington, (W9 3EF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL830361",
      "property_address": "Flat M, 1 Ebury Bridge Road, London (SW1W 8PX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL830369",
      "property_address": "Flat R, 1 Ebury Bridge Road, London (SW1W 8PX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL830618",
      "property_address": "Flat N, 1 Ebury Bridge Road, London (SW1W 8PX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832978",
      "property_address": "Flat 4, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832987",
      "property_address": "Flat 8, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832992",
      "property_address": "Flat 9, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832993",
      "property_address": "Flat 10, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832996",
      "property_address": "Flat 11, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832998",
      "property_address": "Flat 12, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL832999",
      "property_address": "Flat 14, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833000",
      "property_address": "Flat 15, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833010",
      "property_address": "Flat 22, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833017",
      "property_address": "Flat 23, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833026",
      "property_address": "Flat 24, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833032",
      "property_address": "Flat 25, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833037",
      "property_address": "Apartment 26, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833048",
      "property_address": "Flat 28, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL833052",
      "property_address": "Flat 29, 27 Sheldon Square, London (W2 6DW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL839649",
      "property_address": "Isokon Flats, Lawn Road, London (NW3 2XD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL84085",
      "property_address": "18a Homefield Road, Wembley (HA0 2NJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL84374",
      "property_address": "5 Bowes Road, London (N13 4UX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL8476",
      "property_address": "29 Cobbold Road, Willesden",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL869372",
      "property_address": "Flats 1 to 10, 275 Alexandra Avenue, Harrow (HA2 9DX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL874017",
      "property_address": "4 Oxford Road and Flat B, London (NW6 5SL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL879402",
      "property_address": "11B King Henrys Walk, London (N1 4NW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL899442",
      "property_address": "Flat 15, 86 Warden Road, London (NW5 4NR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899447",
      "property_address": "Flat 8, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899448",
      "property_address": "Flat 9, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899449",
      "property_address": "Flat 13, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899451",
      "property_address": "Flat 11, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899452",
      "property_address": "Flat 16, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899453",
      "property_address": "Flat 15, 24 Athlone Street, London (NW5 4JL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899457",
      "property_address": "Flat 20, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899459",
      "property_address": "Flat 19, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899460",
      "property_address": "Flat 18, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899463",
      "property_address": "Flat 23, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899464",
      "property_address": "Flat 22, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL899465",
      "property_address": "Flat 25, 24 Athlone Street, London (NW5 4LJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL909519",
      "property_address": "Flat 14, Cubitt Court, 100 Park Village East, London (NW1 3DL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL909523",
      "property_address": "Flat 16, Cubitt Court, 100 Park Village East, London (NW1 3DL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL909524",
      "property_address": "Flat 17, Cubitt Court, 100 Park Village East, London (NW1 3DL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL909525",
      "property_address": "Flat 18, Cubitt Court, 100 Park Village East, London (NW1 3DL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL911165",
      "property_address": "Apartment HA10, 10 Rochester Row, London (SW1P 1AB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL911166",
      "property_address": "Apartment HA7, 10 Rochester Row, London (SW1P 1AB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL911170",
      "property_address": "Flat 14, 35 Greencoat Place, London (SW1P 1AB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL923937",
      "property_address": "Flat 204, Lyndhurst Court, 36-38 Finchley Road, London (NW8 6EU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL95463",
      "property_address": "76 All Souls Avenue, London (NW10 3BG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL956931",
      "property_address": "Flat 1, 49 Lowfield Road, London (NW6 2PP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL957066",
      "property_address": "Flat 2, 43 Sherriff Road, London (NW6 2AS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "NGL9612",
      "property_address": "Land lying to the north of Watsons Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "NGL968565",
      "property_address": "195d Portnall Road, London (W9 3BN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "ON56524",
      "property_address": "22 Chowns Close, Thame",
      "tenure": "Freehold"
    },
    {
      "title_number": "P23397",
      "property_address": "8 St Barnabas Road, Mitcham",
      "tenure": "Freehold"
    },
    {
      "title_number": "P59244",
      "property_address": "19 The Grove, Kingsbury",
      "tenure": "Freehold"
    },
    {
      "title_number": "P63807",
      "property_address": "Electricity Sub Station, Walpole Road, Croydon",
      "tenure": "Freehold"
    },
    {
      "title_number": "P77343",
      "property_address": "125 Cranborne Avenue, Tolworth",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL100175",
      "property_address": "15 Brierley Close, London and garage 15 (SE25 4LT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL117457",
      "property_address": "13 Eastwood Street, London (SW16 6PT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL122986",
      "property_address": "106 Silverleigh Road, Thornton Heath (CR7 6DW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL131727",
      "property_address": "45 Grove Road, Mitcham",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL141482",
      "property_address": "106 Elm Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL143001",
      "property_address": "31 Ladas Road, West Norwood, (SE27 0UP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL149791",
      "property_address": "7 Pascoe Road, Hither Green",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL167404",
      "property_address": "74 The Crescent, New Malden (KT3 3LH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL169773",
      "property_address": "St Clare Business Park, Holly Road, Hampton Hill",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL173245",
      "property_address": "98 Gracefield Gardens, London (SW16 2TT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL174290",
      "property_address": "22 Worslade Road, Tooting",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL177684",
      "property_address": "29 Hitherfield Road, Streatham (SW16 2LW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL183185",
      "property_address": "9 Salterford Road, (SW17 9TE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL184073",
      "property_address": "12 Wilson Road, Chessington",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL189535",
      "property_address": "4 Besley Street, London (SW16 6BD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL193202",
      "property_address": "94 Stoneleigh Avenue, Worcester Park",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL193895",
      "property_address": "6 Huntspill Street, (SW17 0AA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL195345",
      "property_address": "23B Barrow Road, Streatham",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL200111",
      "property_address": "18 Wendover Way, Orpington and garage 30, (BR6 0US)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL20337",
      "property_address": "90 Isham Road, London (SW16 4TF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL207439",
      "property_address": "9 Buckland Way, Worcester Park (KT4 8NT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL214589",
      "property_address": "51 Tolworth Rise North, Surbiton (KT5 9EN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL215074",
      "property_address": "55A Tranmere Road, Earlsfield",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL217031",
      "property_address": "70 and 72 Woodbury Street (SW17 9RR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL222213",
      "property_address": "101 Haydon's Road, Wimbledon",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL22804",
      "property_address": "11 Hilary Avenue, Mitcham, (CR4 2LA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL234669",
      "property_address": "8 Warwick Road, Sutton",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL236178",
      "property_address": "Flat 12 Lime Court, Gipsy Lane, London (SW15 5RJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL237388",
      "property_address": "235 Mitcham Lane, London (SW16 6PY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL250013",
      "property_address": "8a Ringford Road, Wandsworth, (SW18 1RS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL25066",
      "property_address": "99, 117 and 119 Nutfield Road, Thornton Heath (CR7 7DR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL257465",
      "property_address": "26 Holmbury Court, Upper Tooting Road, (SW17 7PA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL258001",
      "property_address": "the Ground Floor Flat at 9 Ruskin Avenue, Kew",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL259269",
      "property_address": "21 Worslade Road, London (SW17 0BT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL263357",
      "property_address": "112 St Agatha's Grove, Carshalton, (SM5 1DW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL273605",
      "property_address": "14 North Drive, (SW16 1RL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL287414",
      "property_address": "141 Tudor Drive, Morden, (SM4 4PL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL288567",
      "property_address": "21 Rectory Lane, Wallington, (SM6 8DX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL297517",
      "property_address": "41 Langroyd Road, London (SW17 7PL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL303532",
      "property_address": "Priory Court, Denmark Road, Kingston Upon Thames (KT1 2RT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL309147",
      "property_address": "11 Tiverton Way, Chessington (KT9 2QS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL318102",
      "property_address": "Flat 4, 96 Chelverton Road, Putney",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL333209",
      "property_address": "63 Bartholomew Close, East Hill",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL33460",
      "property_address": "1 to 66 Cheviot Gardens, Cheviot Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL334691",
      "property_address": "Flat 6, Langham Court, Wyke Road, London (SW20 8RP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL336569",
      "property_address": "LAND AND WHARF ON THE WEST SIDE OF Norman Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL344855",
      "property_address": "161D Sheen Road, Richmond (TW9 1YS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL348730",
      "property_address": "97 Stillingfleet Road, Barnes",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL363510",
      "property_address": "9-13 Landseer Close and 47-55 (odd) Brangwyn Crescent, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL372423",
      "property_address": "1-5 Rushworth Street, London (SE1 0RB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL376924",
      "property_address": "4 Bellamy Street, Balham, (SW12 8BU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL383910",
      "property_address": "28 Greenock Road, London (SW16 5XG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL399421",
      "property_address": "76 Mayford Road, (SW12 8SN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL400002",
      "property_address": "7 Windmill Road, Hampton Hill, Hampton (TW12 1RF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL401096",
      "property_address": "72 Topsham Road, London (SW17 8SP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL401630",
      "property_address": "Flat 2, 5 Pendle Road, Streatham (SW16 6RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL402992",
      "property_address": "10, 12, 13, 15, 16 and 18 Price Close, London (SW17 7EP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL403773",
      "property_address": "the ground floor flat at 5 Eardley Road (SW16 6DA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL406468",
      "property_address": "Flat 4, Sedgewick House, Limpsfield Avenue, London (SW19 6DJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL411319",
      "property_address": "Flat 1, 1 Handforth Road, London (SW9 0LL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL413136",
      "property_address": "24 Uplands Road, Orpington, (BR6 0RJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL418642",
      "property_address": "St Clare Works, St Clare Business Park, Holly Road, Hampton Hill",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL425652",
      "property_address": "Cambridge House 16-18 (even), Wellesley Road, Croydon (CR0 2DD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL425721",
      "property_address": "24 Whatley Avenue, London (SW20 9NZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL426637",
      "property_address": "187 Frensham Drive, London (SW15 3ED)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL429989",
      "property_address": "38 Thackeray Road, London (SW8 3TT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL442359",
      "property_address": "43 Glasford Street, (SW17 9HL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL442915",
      "property_address": "land lying to the South of Windmill Road, St Clare Business Park, Hampton Hill",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL454057",
      "property_address": "29 Boston Road, Croydon, (CR0 3EG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL458040",
      "property_address": "9A Atheldene Road, (SW18 3BN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL461224",
      "property_address": "Flat 1, 16 Dalberg Road (SW2 1AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL463388",
      "property_address": "149a Boundary Road, London (SW19 2DE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL463724",
      "property_address": "Flat 24, Stevenson House, Latchmere Road, Battersea, (SW11 2DU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL473742",
      "property_address": "Flats 1-12 Copse Court, Evenwood Close, London (SW15 2DE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL474844",
      "property_address": "16 Harling Court, Latchmere Road and Store 16, (SW11 5AA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL483929",
      "property_address": "26E Fontenoy Road, Balham, (SW12 9LU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL491279",
      "property_address": "1 Purbrook House, Petersfield Rise (SW15 4AQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL491901",
      "property_address": "20 Simon Lodge, Victoria Drive, Wimbledon (SW19 6HJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL492451",
      "property_address": "1 to 25 (odd) Malham Road, Lewisham",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL496254",
      "property_address": "60 Westcote Road, London (SW16 6BW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL499460",
      "property_address": "64 Rowditch Lane, (SW11 5BX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL500142",
      "property_address": "10 Faversham Road, Morden (SM4 6RE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL505469",
      "property_address": "33 Kingsway, Motspur Park, New Malden",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL512976",
      "property_address": "52 Veronica Gardens, London and parking space (SW16 5JS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL523445",
      "property_address": "4 Marian Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL600763",
      "property_address": "land at rear of 27 Manor Road, Mitcham",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL600764",
      "property_address": "27 Manor Road, Mitcham (CR4 1JG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL601898",
      "property_address": "54 Torrington Way, Morden (SM4 5QA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL602624",
      "property_address": "165 Seely Road (SW17 9QX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL611032",
      "property_address": "38 Lansdell Road, Mitcham (CR4 2JE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL611689",
      "property_address": "9 Ladywood Road, Surbiton (KT6 7PB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL699743",
      "property_address": "Land on the north west side of 54 Brigstock Road, Thornton Heath (CR7 8RX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL700320",
      "property_address": "Apartments 6 to 18 (inclusive), 41 and 121 to 148 (inclusive) Woodall Court, 7 Whitestone Way, Croydon",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL707210",
      "property_address": "Land at Windmill Trading Estate, 302-310 Commonside East, Mitcham (CR4 1HX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL715394",
      "property_address": "Flat 1, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715396",
      "property_address": "Flat 2, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715397",
      "property_address": "Flat 3, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715400",
      "property_address": "Flat 4, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715402",
      "property_address": "Flat 5, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715403",
      "property_address": "Flat 6, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715405",
      "property_address": "Flat 7, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715407",
      "property_address": "Flat 8, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715408",
      "property_address": "Flat 9, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715409",
      "property_address": "Flat 10, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715410",
      "property_address": "Flat 11, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715411",
      "property_address": "Flat 12, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715415",
      "property_address": "Flat 13, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715416",
      "property_address": "Flat 14, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715417",
      "property_address": "Flat 15, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715418",
      "property_address": "Flat 16, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715419",
      "property_address": "Flat 17, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715420",
      "property_address": "Flat 18, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715421",
      "property_address": "Flat 19, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715422",
      "property_address": "Flat 20, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715424",
      "property_address": "Flat 21, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715425",
      "property_address": "Flat 22, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715426",
      "property_address": "Flat 23, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715427",
      "property_address": "Flat 24, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715428",
      "property_address": "Flat 25, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715429",
      "property_address": "Flat 26, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715430",
      "property_address": "Flat 27, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715431",
      "property_address": "Flat 28, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715432",
      "property_address": "Flat 29, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715434",
      "property_address": "Flat 31, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715435",
      "property_address": "Flat 32, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715438",
      "property_address": "Flat 34, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL715441",
      "property_address": "Flat 37, Dowding House, 22 West Barnes Lane, London (SW20 0BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL718121",
      "property_address": "Flats 1 - 20, Sammi Court, 4 Parchmore Road, Thornton Heath (CR7 8LU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL718130",
      "property_address": "Flats 5 and 6, 17 Slade Way and Flats 4, 5 and 6, 19 Slade Way, Mitcham and parking spaces (CR4 2GA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL718238",
      "property_address": "9 and 9a Langley Road, London (SW19 3NZ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL718309",
      "property_address": "Flats 1-16, Greenview Drive, London (SW20 9DS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL719940",
      "property_address": "Flats 3 and 4, 17 Slade Way and Flat 3, 19 Slade Way, Sandy Lane, Mitcham and parking spaces (CR4 2GA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL730518",
      "property_address": "Flats 1-18 Jupiter House, Esquiline Lane, Mitcham (CR4 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL731586",
      "property_address": "Flats 7-12, Venice House, Aventine Avenue, Mitcham (CR4 1GB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL731587",
      "property_address": "Flats 19-24 Venice House, Aventine Avenue, Mitcham (CR4 1GB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL733445",
      "property_address": "Flats 31-36, Verona House, Aventine Avenue, Mitcham (CR4 1GD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL733446",
      "property_address": "Flats 7-12, Verona House, Aventine Avenue, Mitcham (CR4 1GD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL736435",
      "property_address": "Flats 24 to 29, Lear House, Aventine Avenue, Mitcham (CR4 1GE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL736437",
      "property_address": "Flats 12 to 17, Lear House, Aventine Avenue, Mitcham (CR4 1GE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL736438",
      "property_address": "Flats 1 to 5, Lear House, Aventine Avenue, Mitcham (CR4 1GE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL737014",
      "property_address": "Flats 6 to 10, Juliet House, Aventine Avenue, Mitcham (CR4 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL73755",
      "property_address": "41 Lincoln Avenue, Twickenham (TW2 6NH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SGL759664",
      "property_address": "Land on the north-east side of Purley Way and land on the south side of Denning Avenue, Croydon",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL761336",
      "property_address": "parking space at 17 Slade Way, Mitcham",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SGL773373",
      "property_address": "9d Manor Road, Beckenham (BR3 5JB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SY104788",
      "property_address": "74 Seymour Avenue, Morden, (SM4 4RD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY14771",
      "property_address": "92 Hillcross Avenue, Morden (SM4 4EG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY153201",
      "property_address": "4 Hallowell Close (CR4 2QD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY20747",
      "property_address": "8 Bradley Road, London (SE19 3NS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY207785",
      "property_address": "52 Hatton Gardens (CR4 4LG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY23055",
      "property_address": "23 Albany Park Road, Leatherhead, (KT22 7PA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY233400",
      "property_address": "the First and Second Floor Flat, 7 Belvedere Court, 14 Catherine Road, Surbiton",
      "tenure": "Leasehold"
    },
    {
      "title_number": "SY25173",
      "property_address": "72 Shaldon Drive",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY304960",
      "property_address": "22a Shrubland Grove, Worcester Park, Surrey",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY313562",
      "property_address": "60 Ravenscar Road, Surbiton (KT6 7PL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY373844",
      "property_address": "68a Woodham Lane, New Haw, Addlestone (KT15 3NA)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY37922",
      "property_address": "93 Windermere Road, Mitcham",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY393642",
      "property_address": "42 Bingley Road, Sunbury on Thames, and garage (TW16 7RB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY394100",
      "property_address": "2 Honeycrock Lane, Redhill (RH1 5DF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY40879",
      "property_address": "301 Park Road, Kingston Upon Thames (KT2 5LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY431316",
      "property_address": "43 Rothes Road, Dorking, (RH4 1LG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY467567",
      "property_address": "10 Sunnymede Avenue, West Ewell",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY509267",
      "property_address": "15 Relko Court, Epsom (KT19 9DJ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY517128",
      "property_address": "56 Goodwyns Road, Dorking (RH4 2LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY533964",
      "property_address": "16 Chart Downs, Dorking, (RH5 4DH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY562933",
      "property_address": "6 Chart Downs, Dorking (RH5 4DH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY599767",
      "property_address": "8 Nower Road, Dorking (RH4 3BS)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY600400",
      "property_address": "11 Leith Grove, Beare Green, Dorking (RH5 4RF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY610185",
      "property_address": "1 Home Close, Fetcham, Leatherhead (KT22 9JN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "SY7080",
      "property_address": "25 Meadow Hill, New Malden (KT3 5RQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL113361",
      "property_address": "Flat 25, Totham Lodge, Richmond Road, London (SW20 0PF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL115424",
      "property_address": "32 Barker Walk, Streatham, (SW16 1AT)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL11686",
      "property_address": "31 Maple Mews, London and Parking Space 38 (SW16 2AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL133440",
      "property_address": "Bronze House 4 Cleeve Way, Prime House 327 Danebury Avenue, Newport House 329 Danebury Avenue, and Newbury House 331 Danebury Avenue, and land on the south west side of Danebury Avenue, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL139374",
      "property_address": "60 Abbotts Road, Mitcham (CR4 1JU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL148492",
      "property_address": "3 Oliver House, Wyvil Road, (SW8 2SX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL156182",
      "property_address": "326-332 (Even) Balham High Road, (SW17 7AA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL1565",
      "property_address": "112 Godley Road, London (SW18 3HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL16071",
      "property_address": "43 Mirlees Court, Coldharbour Lane, London (SE5 9QW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL163095",
      "property_address": "75 Portland Grove, London (SW8 1JN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL16446",
      "property_address": "36 Tooting High Street, London (SW17 0RG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL166309",
      "property_address": "Land and buildings on the North West side of Clapham Road",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL167468",
      "property_address": "117 to 119 Plough Road, Battersea",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL168514",
      "property_address": "Block 4, 52 to 54 (even) Acre Lane, London (SW2 5TD)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL172950",
      "property_address": "LAND FORMING PART OF SAXON WHARF Norman Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL17899",
      "property_address": "153 Southcroft Road (SW17 9TN)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL186310",
      "property_address": "4-12 (even) and 12b, 14a, and 14b Union Road and 342-344 (even) Clapham Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL187442",
      "property_address": "Flat 1, 4A Station Parade, Balham High Road, (SW12 9AZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL188970",
      "property_address": "Saxon Wharf, 46-48 Norman Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL198643",
      "property_address": "232 Ferndale Road, London (SW9 8BW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL220052",
      "property_address": "Apartment 106, 24 Brewhouse Street, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220054",
      "property_address": "Apartment 108, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220055",
      "property_address": "Apartment 109, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220056",
      "property_address": "Apartment 110, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220059",
      "property_address": "Apartment 113, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220060",
      "property_address": "Apartment 114, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220067",
      "property_address": "Apartment 119, 24 Brewhouse Lane, London, (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220068",
      "property_address": "Apartment 120, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220070",
      "property_address": "Apartment 122, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL220072",
      "property_address": "Apartment 124, 24 Brewhouse Lane, London (SW15 2JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL231517",
      "property_address": "31 Curness Street, London (SE13 6JY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL231518",
      "property_address": "Flat 18, Block B, 256 Lewisham High Street, London (SE13 6JX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL231519",
      "property_address": "33 Curness Street, London (SE13 6JY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL23494",
      "property_address": "11 Rackham Mews, London (SW16 6BE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL24110",
      "property_address": "1 Credenhill Street, London (SW16 6PP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL24210",
      "property_address": "10 Rackham Mews, London (SW16 6BE)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL244420",
      "property_address": "Flat 32, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244425",
      "property_address": "Flat 33, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244427",
      "property_address": "Flat 31, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244448",
      "property_address": "Flat 44, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244449",
      "property_address": "Flat 10, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244450",
      "property_address": "Flat 9, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244451",
      "property_address": "Flat 43, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244454",
      "property_address": "Flat 5, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244456",
      "property_address": "Flat 1, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244457",
      "property_address": "Flat 36, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244459",
      "property_address": "Flat 21, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244460",
      "property_address": "Flat 22, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244463",
      "property_address": "Flat 17, 3 Salamanca Place, London (SE1 7HH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244465",
      "property_address": "Flat 22, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244467",
      "property_address": "Flat 8, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244471",
      "property_address": "Flat 20, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244478",
      "property_address": "Flat 42, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244483",
      "property_address": "Flat 9, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL244484",
      "property_address": "Flat 14, 1 Salamanca Place, London (SE1 7HE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL246372",
      "property_address": "Land at 293 Lower Richmond Road, Richmond (TW9 4LY)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL254915",
      "property_address": "Block H, St George Wharf, Wandsworth Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL259717",
      "property_address": "1-29 Phoenix Way, London (SW18 2PW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL262662",
      "property_address": "Flat 5 Sinclair Court, 2A Heathdene Road, London and parking space (SW16 3PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL262664",
      "property_address": "Flat 11 Sinclair Court, 2A Heathdene Road, London and parking space (SW16 3PE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL263207",
      "property_address": "1C Osiers Road and 18 Point Pleasant,  London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL271519",
      "property_address": "65 to 88 Stane Grove (inclusive), London (SW9 9AL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL276157",
      "property_address": "Car Parking Spaces, Garratt Lane, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL276403",
      "property_address": "Flats 85-122 (inclusive), Voltaire Buildings, 330 Garratt Lane, London (SW18 4FR)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL279956",
      "property_address": "Railway Arches 186 To 202, Manor Place Depot, Manor Place, London (SE17 3BD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL282381",
      "property_address": "4 Denning Mews, London (SW12 8QT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL282383",
      "property_address": "6 Denning Mews, London (SW12 8QT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL284927",
      "property_address": "Flat 13, Picture House, 7 Streatham High Road, London (SW16 1EH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL290444",
      "property_address": "Land lying to the east of Old Town, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL293536",
      "property_address": "Block K, St George Wharf, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL293907",
      "property_address": "Flats 31-49, Salamanca Tower, 6 Salamanca Place, London (SE1 7HB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294693",
      "property_address": "Flat 1, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294695",
      "property_address": "Flat 3, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294696",
      "property_address": "Flat 4, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294698",
      "property_address": "Flat 5, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294699",
      "property_address": "Flat 7, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294700",
      "property_address": "Flat 8, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294702",
      "property_address": "Flat 9, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294703",
      "property_address": "Flat 10, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294704",
      "property_address": "Flat 11, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL294706",
      "property_address": "Flat 13, 378 Clapham Road, London (SW9 9AF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL295383",
      "property_address": "Block A, Nightingale Mews, Temperley Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL300662",
      "property_address": "Block V1, John Milton School, Sleaford Street, London (SW8 5AH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302655",
      "property_address": "Apartment 414, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302672",
      "property_address": "Apartment 418, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302673",
      "property_address": "Apartment 419, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302674",
      "property_address": "Apartment 420, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302675",
      "property_address": "Apartment 421, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302677",
      "property_address": "Apartment 423, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302678",
      "property_address": "Apartment 424, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302679",
      "property_address": "Apartment 425, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302689",
      "property_address": "Apartment 432, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL302694",
      "property_address": "Apartment 433, Metro Central Heights, 119 Newington Causeway, London (SE1 6DT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL304194",
      "property_address": "Land on the west side of Salamanca Tower, 6 Salamanca Place, London (SE1 7HB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL305052",
      "property_address": "Land at the back of 49-67 (odd) Sudbourne Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL306713",
      "property_address": "6 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306716",
      "property_address": "8 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306717",
      "property_address": "10 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306724",
      "property_address": "11 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306725",
      "property_address": "12 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306726",
      "property_address": "13 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306729",
      "property_address": "14 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306730",
      "property_address": "15 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306733",
      "property_address": "17 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306734",
      "property_address": "18 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306735",
      "property_address": "19 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL306737",
      "property_address": "20 Vanquish Close, Twickenham (TW2 7AN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL311466",
      "property_address": "Palladio Court, Mapleton Road, London, SW18 4GB which lies within the area edged red at ground floor level and also comprises the parts at first, second, third, fourth, fifth, sixth, seventh, eighth and ninth floor levels shown tinted pink on the supplementary plans to the title plan",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315387",
      "property_address": "Plots 1040 - 1187 (inclusive) and common parts, Aquarius House, St George Wharf, Wandsworth Road, London lying within the area shown edged with red on the plan of the above title filed at Land Registry",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315715",
      "property_address": "Flat 1010, Aquarius House, St George Wharf, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315722",
      "property_address": "Flat 987, Aquarius House, St George Wharf, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315726",
      "property_address": "Flat 946, Aquarius House, St George Wharf, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315730",
      "property_address": "Flat 942, Aquarius House, St George Wharf, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315731",
      "property_address": "Flat 941, 15 St George Wharf, London (SW8 2LE)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL315734",
      "property_address": "Flat 931, Aquarius House, St George Wharf, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316174",
      "property_address": "Block B, 2-6 Hardwicks Square, London (SW18 4AJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316871",
      "property_address": "72 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316879",
      "property_address": "53 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316885",
      "property_address": "16 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316891",
      "property_address": "15 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316895",
      "property_address": "83 Orbis Wharf, Bridges Court Road, London (SW11 3GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316904",
      "property_address": "81 Orbis Wharf, Bridges Court Road, London (SW11 3GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316914",
      "property_address": "78 Orbis Wharf, Bridges Court Road, London (SW11 3GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316918",
      "property_address": "42 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316921",
      "property_address": "41 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316926",
      "property_address": "38 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316931",
      "property_address": "62 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316933",
      "property_address": "61 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316938",
      "property_address": "35 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316940",
      "property_address": "52 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316953",
      "property_address": "68 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316960",
      "property_address": "57 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316965",
      "property_address": "70 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316969",
      "property_address": "71 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316972",
      "property_address": "60 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316980",
      "property_address": "31 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316983",
      "property_address": "30 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316985",
      "property_address": "26 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL316989",
      "property_address": "46 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL317388",
      "property_address": "Block D, 6 Chapel Yard, London (SW18 4LX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320137",
      "property_address": "Flat 2, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320138",
      "property_address": "Flat 5, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320140",
      "property_address": "Flat 8, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320143",
      "property_address": "Flat 13, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320145",
      "property_address": "Flat 20, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320148",
      "property_address": "Flat 25, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320151",
      "property_address": "Parking Space 2, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL320154",
      "property_address": "Parking Space 5, Carter House, 33 Petergate, London (SW11 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL321441",
      "property_address": "Block D, 137-143 Clapham Road, London (SW9 0HP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL321585",
      "property_address": "Carew House, Leigham Court Road, London (SW16 2RL)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL322245",
      "property_address": "13 Cambalt Road, London (SW15 6EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL322259",
      "property_address": "15 Cambalt Road, London (SW15 6EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL322265",
      "property_address": "17 Cambalt Road, London (SW15 6EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL322287",
      "property_address": "25 Cambalt Road, London (SW15 6EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL322292",
      "property_address": "27 Cambalt Road, London (SW15 6EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL322296",
      "property_address": "29 Cambalt Road, London (SW15 6EL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL324986",
      "property_address": "4 Orbis Wharf, Bridges Court Road, London (SW11 3GW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL324988",
      "property_address": "77 Orbis Wharf, Bridges Court Road, London (SW11 3GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL325558",
      "property_address": "part of block J 131-141 Clapham Road, London as more particularly described in the lease",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL331533",
      "property_address": "195 To 272 (inclusive), Oak Square, London and basement parking spaces (SW9 9JW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL336030",
      "property_address": "Flats 1 to 26, Sarawak Court, Consort Road and, 51 Consort Road, London (SE15 3SS)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL336040",
      "property_address": "Batwa House, Varcoe Road, London (SE16 3BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL336219",
      "property_address": "1 to 8 (inclusive) Hartwell Close and 92a Challice Way, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL342889",
      "property_address": "98 Liberty Street, London (SW9 0EF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL342891",
      "property_address": "99 Liberty Street, London (SW9 0EF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL342893",
      "property_address": "101 Liberty Street, London (SW9 0EF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL342894",
      "property_address": "102 Liberty Street, London (SW9 0EF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL342895",
      "property_address": "103 Liberty Street, London (SW9 0EF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347035",
      "property_address": "Flat 36, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347036",
      "property_address": "Flat 30, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347037",
      "property_address": "Flat 24, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347038",
      "property_address": "Flat 47, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347039",
      "property_address": "Flat 41, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347041",
      "property_address": "Flat 16, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347043",
      "property_address": "Flat 19, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347046",
      "property_address": "Flat 44, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347050",
      "property_address": "Flat 31, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347052",
      "property_address": "Flat 32, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347057",
      "property_address": "Flat 18, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347059",
      "property_address": "Flat 20, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347060",
      "property_address": "Flat 21, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347063",
      "property_address": "Flat 25, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347067",
      "property_address": "Flat 7, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347073",
      "property_address": "Flat 26, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347075",
      "property_address": "Flat 23, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347076",
      "property_address": "Flat 29, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347079",
      "property_address": "Flat 35, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347080",
      "property_address": "Flat 34, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347081",
      "property_address": "Flat 28, Flotilla House, Juniper Drive, London (SW18 1FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL347795",
      "property_address": "land and buildings on the south side of Grange Walk, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL348497",
      "property_address": "Land at Clapham Leisure Centre, Clapham Manor Street, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL355162",
      "property_address": "Flat 15, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355166",
      "property_address": "Flat 12, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355167",
      "property_address": "Flat 11, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355168",
      "property_address": "Flat 10, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355169",
      "property_address": "Flat 9, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355170",
      "property_address": "Flat 8, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355171",
      "property_address": "Flat 7, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355178",
      "property_address": "Flat 16, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355181",
      "property_address": "Flat 2, 1 Rathbone Market, Barking Road, Canning Town, London (E16 1EH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355182",
      "property_address": "Flat 46, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355183",
      "property_address": "Flat 43, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355184",
      "property_address": "Flat 38, 30 Barking Road, Canning Town, London (E16 1GQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355185",
      "property_address": "Flat 35, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355187",
      "property_address": "Flat 30, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355188",
      "property_address": "Flat 27, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355190",
      "property_address": "Flat 4, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355191",
      "property_address": "Flat 3, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355193",
      "property_address": "Flat 1, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL355194",
      "property_address": "Flat 5, 30 Barking Road, Canning Town, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL35672",
      "property_address": "4 Groom Crescent, (SW18 3JB)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL365468",
      "property_address": "Apartment 1, Block A Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365470",
      "property_address": "Apartment 2, Block A Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365471",
      "property_address": "Flat 5, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365473",
      "property_address": "Apartment 61, Block B Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365475",
      "property_address": "Apartment 58, Block B Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365476",
      "property_address": "Apartment 67, Block B Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365477",
      "property_address": "Flat 4, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365478",
      "property_address": "Flat 11, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365479",
      "property_address": "Flat 1, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365480",
      "property_address": "Flat 10, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365483",
      "property_address": "Apartment 69, Block B Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365484",
      "property_address": "Flat 18, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365485",
      "property_address": "Flat 13, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365486",
      "property_address": "Flat 17, Rainsborough House, 5 Stamford Square, London (SW15 2BP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365487",
      "property_address": "Apartment 71, Block B Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365488",
      "property_address": "Apartment 3, Block A Langham Square, Upper Richmond Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365905",
      "property_address": "Flat 3, Somerset Court, 43 Somerset Road, Teddington (TW11 8RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365906",
      "property_address": "Flat 5, Somerset Court, 43 Somerset Road, Teddington (TW11 8RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365907",
      "property_address": "Flat 6, Somerset Court, 43 Somerset Road, Teddington (TW11 8GU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365909",
      "property_address": "Flat 8, Somerset Court, 43 Somerset Road, Teddington (TW11 8RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365910",
      "property_address": "Flat 9, Somerset Court, 43 Somerset Road, Teddington (TW11 8RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL365912",
      "property_address": "Flat 14, Somerset Court, 43 Somerset Road, Teddington (TW11 8RT)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL367020",
      "property_address": "Land at Edmund Street, London (SE5 7NP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369167",
      "property_address": "4, Horizon House, Juniper Drive, London (SW18 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369176",
      "property_address": "28, Horizon House, Juniper Drive, London (SW18 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369180",
      "property_address": "3, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369184",
      "property_address": "7, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369185",
      "property_address": "8, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369187",
      "property_address": "10, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369188",
      "property_address": "11, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369189",
      "property_address": "12, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369191",
      "property_address": "14, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369192",
      "property_address": "15, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369193",
      "property_address": "16, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369205",
      "property_address": "18 Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369206",
      "property_address": "19, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369207",
      "property_address": "20, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369214",
      "property_address": "24, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369219",
      "property_address": "29, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369225",
      "property_address": "33, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369227",
      "property_address": "34, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369228",
      "property_address": "35, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369229",
      "property_address": "36, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369324",
      "property_address": "4, Jasmine House, Juniper Drive, London (SW18 1GJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL369438",
      "property_address": "Site 16b, Akerman Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL373767",
      "property_address": "Land at 19 Spa Road, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL375155",
      "property_address": "Site 21, Myatts Field, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380220",
      "property_address": "Apartment 1, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380221",
      "property_address": "Apartment 2, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380222",
      "property_address": "Apartment 3, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380223",
      "property_address": "Apartment 4, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380226",
      "property_address": "Apartment 5, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380227",
      "property_address": "Apartment 6, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380230",
      "property_address": "Apartment 7, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380232",
      "property_address": "Apartment 9, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380234",
      "property_address": "Apartment 11, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380235",
      "property_address": "Apartment 12, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380237",
      "property_address": "Flat 13, 81 Black Prince Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380238",
      "property_address": "Apartment 14, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380240",
      "property_address": "Apartment 15, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380241",
      "property_address": "Apartment 16, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380245",
      "property_address": "Apartment 19, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380247",
      "property_address": "Apartment 21, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380248",
      "property_address": "Apartment 22, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380249",
      "property_address": "Apartment 23, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380250",
      "property_address": "Apartment 24, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380252",
      "property_address": "Apartment 26, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380253",
      "property_address": "Apartment 27, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380255",
      "property_address": "Apartment 28, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380257",
      "property_address": "Apartment 30, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL380258",
      "property_address": "Apartment 31, 81 Black Prince Road, London (SE1 7SZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381069",
      "property_address": "Flat 2, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381073",
      "property_address": "Flat 3, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381074",
      "property_address": "Flat 4, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381075",
      "property_address": "Flat 5, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381076",
      "property_address": "Flat 6, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381077",
      "property_address": "7 Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381081",
      "property_address": "Flat 8, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381088",
      "property_address": "Flat 11, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381089",
      "property_address": "Flat 12, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381092",
      "property_address": "Part of Block A, Debnams Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381097",
      "property_address": "Flat 1, Avebury Court, 12 Debnams Road, London (SE16 2AX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381298",
      "property_address": "Site 23c, Myatts Field, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL381300",
      "property_address": "Site 18a, Myatts Field, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386218",
      "property_address": "the first floor flat being Apartment 101, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386221",
      "property_address": "the first floor flat being Apartment 102, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386222",
      "property_address": "the first floor flat being Apartment 103, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386227",
      "property_address": "the first floor flat being Apartment 104, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386230",
      "property_address": "the second floor flat and adjoining balcony being Apartment 205, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386236",
      "property_address": "the second floor flat being Apartment 207, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386237",
      "property_address": "the second floor flat and adjoining balconies being Apartment 208, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL386238",
      "property_address": "the second floor flat and adjoining balcony being Apartment 209, 1 Eastfields Avenue, London (SW18 1FQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387656",
      "property_address": "1, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387657",
      "property_address": "2, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387658",
      "property_address": "3, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387659",
      "property_address": "4, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387661",
      "property_address": "5, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387668",
      "property_address": "9, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387670",
      "property_address": "10, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387672",
      "property_address": "16, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387673",
      "property_address": "17, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387675",
      "property_address": "23, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387677",
      "property_address": "24, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387679",
      "property_address": "30, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387681",
      "property_address": "31, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387684",
      "property_address": "49, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387687",
      "property_address": "52, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387689",
      "property_address": "53, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387691",
      "property_address": "56, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387692",
      "property_address": "57, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387694",
      "property_address": "61, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387695",
      "property_address": "62, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387696",
      "property_address": "66, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL387698",
      "property_address": "71, Quarter House, Juniper Drive, London (SW18 1GX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL390281",
      "property_address": "the first floor flat being Apartment 101, 3 Eastfields Avenue, London (SW18 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL390283",
      "property_address": "the first floor flat being Apartment 103, 3 Eastfields Avenue, London (SW18 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL390290",
      "property_address": "the second floor flat being Apartment 205, 3 Eastfields Avenue, London (SW18 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL390291",
      "property_address": "the second floor flat being Apartment 206, 3 Eastfields Avenue, London (SW18 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL390296",
      "property_address": "the second floor flat  being Apartment 208, 3 Eastfields Avenue, London (SW18 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL390298",
      "property_address": "the Second floor flat being Apartment 209, 3 Eastfields Avenue, London (SW18 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL392104",
      "property_address": "6 to 11 (inc), and Flats 1 to 16 Bowen Court, 13 Debnams Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394500",
      "property_address": "Flat 1, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394501",
      "property_address": "Flat 2, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394502",
      "property_address": "Flat 3, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394503",
      "property_address": "Flat 4, Building D/e Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394504",
      "property_address": "Flat 5, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394505",
      "property_address": "Flat 6, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394506",
      "property_address": "Flat 7, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394509",
      "property_address": "Flat 13, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394510",
      "property_address": "Flat 14, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394512",
      "property_address": "Flat 16, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394514",
      "property_address": "Flat 17, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394518",
      "property_address": "Flat 19, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394519",
      "property_address": "Flat 20, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394521",
      "property_address": "Flat 21, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394523",
      "property_address": "Flat 22, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394524",
      "property_address": "Flat 26, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394525",
      "property_address": "Flat 27, 12 Rathbone Market, Barking Road, London (E16 3PX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394526",
      "property_address": "Flat 28, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394528",
      "property_address": "Flat 29, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394530",
      "property_address": "Flat 30, 12 Rathbone Market, Barking Road, Canning Town, London (E16 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394532",
      "property_address": "Flat 36, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394533",
      "property_address": "Flat 40, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394535",
      "property_address": "Flat 42, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394536",
      "property_address": "Flat 50, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394538",
      "property_address": "Flat 54, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394539",
      "property_address": "Flat 56, Building D/E Phase 2 Rathbone Market, Barking Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394642",
      "property_address": "Flat 4, Dower Court, Silwood Street, London (SE16 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394643",
      "property_address": "41 Chamberlain Court, Silwood Street, London (SE16 2AZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394646",
      "property_address": "Flat 2, Dower Court, Silwood Street, London (SE16 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394647",
      "property_address": "Flat 3, Dower Court, Silwood Street, London (SE16 2BF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL394649",
      "property_address": "Flat 40, Chamberlain Court, Silwood Street, London (SE16 2AZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398639",
      "property_address": "2, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398640",
      "property_address": "3, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398641",
      "property_address": "4, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398642",
      "property_address": "5, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398644",
      "property_address": "7, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398645",
      "property_address": "1, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398646",
      "property_address": "10, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398647",
      "property_address": "11, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398648",
      "property_address": "12, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398649",
      "property_address": "13, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398650",
      "property_address": "14, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398651",
      "property_address": "15, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398652",
      "property_address": "Flat 8 Drummond House, 11 Plumstead Road, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398653",
      "property_address": "9, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398654",
      "property_address": "18, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398655",
      "property_address": "19, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398656",
      "property_address": "20, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398657",
      "property_address": "21, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398658",
      "property_address": "22, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398659",
      "property_address": "23, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398662",
      "property_address": "17, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398663",
      "property_address": "26, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398664",
      "property_address": "27, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398668",
      "property_address": "29, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398670",
      "property_address": "30, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398671",
      "property_address": "31, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398672",
      "property_address": "24, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398673",
      "property_address": "25, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398674",
      "property_address": "34, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398676",
      "property_address": "35, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398678",
      "property_address": "36, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398679",
      "property_address": "37, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398680",
      "property_address": "38, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398681",
      "property_address": "39, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398682",
      "property_address": "32, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398684",
      "property_address": "33, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398685",
      "property_address": "42, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398686",
      "property_address": "43, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398688",
      "property_address": "45, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398689",
      "property_address": "46, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398692",
      "property_address": "40, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398693",
      "property_address": "41, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398694",
      "property_address": "50, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398695",
      "property_address": "51, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398696",
      "property_address": "52, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398697",
      "property_address": "53, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398698",
      "property_address": "54, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398700",
      "property_address": "48, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398701",
      "property_address": "49, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398702",
      "property_address": "58 Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398703",
      "property_address": "59, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398705",
      "property_address": "61, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398706",
      "property_address": "62, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398708",
      "property_address": "56, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398710",
      "property_address": "66, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398711",
      "property_address": "67, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398712",
      "property_address": "68, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398713",
      "property_address": "69, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398714",
      "property_address": "64, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398715",
      "property_address": "65, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398717",
      "property_address": "72, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398718",
      "property_address": "73, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398719",
      "property_address": "74, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398720",
      "property_address": "75, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398721",
      "property_address": "70, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL398722",
      "property_address": "71, Drummond House, 11 Victory Parade, London (SE18 6FW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400005",
      "property_address": "33, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400008",
      "property_address": "82, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400009",
      "property_address": "81, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400010",
      "property_address": "57, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400012",
      "property_address": "59, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400013",
      "property_address": "19, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400014",
      "property_address": "26, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400019",
      "property_address": "25, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400020",
      "property_address": "67, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400021",
      "property_address": "1, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400023",
      "property_address": "43, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400024",
      "property_address": "8, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400025",
      "property_address": "7, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400028",
      "property_address": "41, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400029",
      "property_address": "42, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400030",
      "property_address": "3, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400031",
      "property_address": "2, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400032",
      "property_address": "40, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400034",
      "property_address": "5, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400035",
      "property_address": "38, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400036",
      "property_address": "72, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400037",
      "property_address": "73, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400039",
      "property_address": "Flat 75, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400040",
      "property_address": "32, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400042",
      "property_address": "31, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400044",
      "property_address": "20, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400046",
      "property_address": "61, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400047",
      "property_address": "56, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400048",
      "property_address": "53, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400049",
      "property_address": "17, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400051",
      "property_address": "15, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400052",
      "property_address": "14, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400053",
      "property_address": "13, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400054",
      "property_address": "51, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400062",
      "property_address": "48, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400064",
      "property_address": "11, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400065",
      "property_address": "58, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400066",
      "property_address": "45, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400067",
      "property_address": "9, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400068",
      "property_address": "77, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400074",
      "property_address": "21, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL400076",
      "property_address": "29, Trafalgar House, Juniper Drive, London (SW18 1GY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL402906",
      "property_address": "Flat 3, 1 Bywell Place, London (E16 1JW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL402907",
      "property_address": "Flat 4, Building F Phase 2 Rathbone Market, Barking Road, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL402915",
      "property_address": "Flat 19, Building F Phase 2 Rathbone Market, Barking Road, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL402916",
      "property_address": "Flat 20, Building F Phase 2 Rathbone Market, Barking Road, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL402920",
      "property_address": "Flat 33, Building F Phase 2 Rathbone Market, Barking Road, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL402922",
      "property_address": "Flat 34, Building F Phase 2 Rathbone Market, Barking Road, London (E16 1EQ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL404029",
      "property_address": "25 Manor Place and Manor Place Depot, 30-34 Penrose Street, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL40425",
      "property_address": "101 Barringer Square, London (SW17 8ED)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419099",
      "property_address": "6, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419101",
      "property_address": "7, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419102",
      "property_address": "8, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419104",
      "property_address": "9, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419106",
      "property_address": "10, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419107",
      "property_address": "16, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419108",
      "property_address": "17, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419109",
      "property_address": "18, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419110",
      "property_address": "19, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419111",
      "property_address": "20, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419183",
      "property_address": "26, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419185",
      "property_address": "27, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419188",
      "property_address": "28, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419189",
      "property_address": "29, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419190",
      "property_address": "30, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419194",
      "property_address": "36, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419196",
      "property_address": "37, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419198",
      "property_address": "38, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419199",
      "property_address": "39, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419200",
      "property_address": "40, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419201",
      "property_address": "46, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419206",
      "property_address": "48, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419208",
      "property_address": "49, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419212",
      "property_address": "50, Corsair House, 5 Starboard Way, London (E16 2NY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419279",
      "property_address": "89, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419282",
      "property_address": "90, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419284",
      "property_address": "91, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419287",
      "property_address": "92, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419291",
      "property_address": "93, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419303",
      "property_address": "Flat 06b.01.14, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419305",
      "property_address": "95, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419314",
      "property_address": "96, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419315",
      "property_address": "97, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419316",
      "property_address": "98, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419317",
      "property_address": "99, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419322",
      "property_address": "100, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419323",
      "property_address": "101, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419324",
      "property_address": "102, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419325",
      "property_address": "103, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419326",
      "property_address": "104, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419328",
      "property_address": "105, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419329",
      "property_address": "106, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419330",
      "property_address": "107, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419331",
      "property_address": "108, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419333",
      "property_address": "109, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419334",
      "property_address": "110, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419335",
      "property_address": "111, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419336",
      "property_address": "112, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419338",
      "property_address": "114, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL419339",
      "property_address": "115, Corsair House, 9 Starboard Way, London (E16 2NZ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL42368",
      "property_address": "46 Spring Grove, Mitcham (CR4 2NP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL4241",
      "property_address": "9 Classinghall House, Kersfield Road, Putney, (SW15 3HB)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL434968",
      "property_address": "Units 1-23, Martara Mews, London (SE17 3EG)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL439924",
      "property_address": "Flat 16, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439934",
      "property_address": "Flat 17, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439935",
      "property_address": "Flat 18, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439936",
      "property_address": "Flat 19, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439937",
      "property_address": "Flat 20, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439939",
      "property_address": "Flat 25, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439942",
      "property_address": "Flat H4.02, Block H, Rathbone Market, Barking Road, Canning Town, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439946",
      "property_address": "Flat 27, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439947",
      "property_address": "Flat 28, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439948",
      "property_address": "Flat 29, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439950",
      "property_address": "Flat 34, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439954",
      "property_address": "Flat 35, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439955",
      "property_address": "Flat 36, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439959",
      "property_address": "Flat 37, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439961",
      "property_address": "Flat 38, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439972",
      "property_address": "Flat 1, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439975",
      "property_address": "Flat 2, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439986",
      "property_address": "Flat 12, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL439990",
      "property_address": "Flat 13, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440010",
      "property_address": "Flat 14, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440013",
      "property_address": "Flat 15, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440015",
      "property_address": "Flat 21, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440017",
      "property_address": "Flat 22, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440020",
      "property_address": "Flat 23, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440023",
      "property_address": "Flat 24, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440024",
      "property_address": "Flat 30, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440025",
      "property_address": "Flat K5.02, Block K, Rathbone Market, Barking Road, Canning Town, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440029",
      "property_address": "Flat 32, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440031",
      "property_address": "Flat 33, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440032",
      "property_address": "Flat 39, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440035",
      "property_address": "Flat 40, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440040",
      "property_address": "Flat 42, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440043",
      "property_address": "Flat 43, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440046",
      "property_address": "Flat 44, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440054",
      "property_address": "Flat 46, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440065",
      "property_address": "Flat K8.03, Block K, Rathbone Market, Barking Road, Canning Town, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440068",
      "property_address": "Flat 50, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440071",
      "property_address": "Flat 51, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440074",
      "property_address": "Flat K9.02, Block K, Rathbone Market, Barking Road, Canning Town, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440075",
      "property_address": "Flat K9.03, Block K, Rathbone Market, Barking Road, Canning Town, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL440076",
      "property_address": "Flat 54, 17 Maud Street, London (E16 1YR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL443458",
      "property_address": "Site, 11a Myatts Field, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL443635",
      "property_address": "71 Akerman Road, London (SW9 6FX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL446681",
      "property_address": "2 to 8 (even) Frobisher Yard, 31 to 48 (inc) Boyd Building, 10 Frobisher Yard, 5 to 11 (odd) Hudson Way, 72 to 94 (inc) Boyd Building, 3 Hudson Way and 53 to 71 (inc) Boyd Building, 13 Hudson Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447432",
      "property_address": "100, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447433",
      "property_address": "Flat 01A.GF.02 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447435",
      "property_address": "101, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447436",
      "property_address": "Flat 98, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447437",
      "property_address": "Flat 01A.GF.05 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447438",
      "property_address": "97, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447439",
      "property_address": "Flat 01A.01.01 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447442",
      "property_address": "105, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447443",
      "property_address": "Flat 01A.01.03 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447445",
      "property_address": "Flat 01A.01.04 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447447",
      "property_address": "Flat 01A.01.05 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447449",
      "property_address": "103, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447450",
      "property_address": "Flat 01A.01.07 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447454",
      "property_address": "110, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447455",
      "property_address": "114, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447456",
      "property_address": "Flat 01A.02.02 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447458",
      "property_address": "Flat 01A.02.03 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447459",
      "property_address": "Flat 01A.02.04 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447460",
      "property_address": "Flat 01A.02.05 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447461",
      "property_address": "111, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447661",
      "property_address": "117, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447664",
      "property_address": "Flat 01A.02.08 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447668",
      "property_address": "Flat 01A.03.01 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447671",
      "property_address": "Flat 01A.03.02 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447673",
      "property_address": "Flat 01A.03.03, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447676",
      "property_address": "Flat 01A.03.05 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447677",
      "property_address": "Flat 01A.03.06 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447678",
      "property_address": "125, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447679",
      "property_address": "126, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447681",
      "property_address": "Flat 01A.04.01 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447685",
      "property_address": "Flat 129 Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447689",
      "property_address": "131, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447691",
      "property_address": "Flat 01A.04.04 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447693",
      "property_address": "Flat 01A.04.05 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447699",
      "property_address": "Flat 01A.04.06 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447701",
      "property_address": "133, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447704",
      "property_address": "134, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447705",
      "property_address": "136, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447706",
      "property_address": "Flat 135 Cape House, Royal Wharf, North Woolwich Road, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447708",
      "property_address": "Flat 01A.05.03 Cape House, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447709",
      "property_address": "138, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447712",
      "property_address": "140, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447720",
      "property_address": "141, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL447721",
      "property_address": "142, Cape House, 4 Cunningham Avenue, London (E16 2TN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458888",
      "property_address": "17 Forrester Way, London (E15 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458889",
      "property_address": "Apartment B.01, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458890",
      "property_address": "Apartment B.02, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458891",
      "property_address": "48 Leyton Road, London (E15 1GG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458892",
      "property_address": "Apartment C.02, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458893",
      "property_address": "26 Forrester Way, London (E15 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458894",
      "property_address": "Apartment C.04, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458896",
      "property_address": "52 Leyton Road, London (E15 1GG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458897",
      "property_address": "Apartment C.06, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458898",
      "property_address": "Apartment D.01, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458899",
      "property_address": "Apartment D.02, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458900",
      "property_address": "Apartment D.03, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458901",
      "property_address": "Apartment D.04, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458902",
      "property_address": "Apartment D.05, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458903",
      "property_address": "18 Forrester Way, London (E15 1GN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458904",
      "property_address": "Flat 101, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458905",
      "property_address": "Apartment F.1.2, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458906",
      "property_address": "Apartment F.1.5, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458907",
      "property_address": "Apartment F.2.1, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458917",
      "property_address": "Apartment F.2.2, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458918",
      "property_address": "Flat 203, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458919",
      "property_address": "Flat 204, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458921",
      "property_address": "Apartment F.2.6, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458922",
      "property_address": "Apartment F.3.3, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458923",
      "property_address": "Apartment F.3.4, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458924",
      "property_address": "Apartment F.3.6, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL458926",
      "property_address": "Parking Area And Podium, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL46135",
      "property_address": "96 Swinburne Road, London (SW15 5EH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL465845",
      "property_address": "40 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465849",
      "property_address": "38 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465852",
      "property_address": "Apartment F.1.3, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465853",
      "property_address": "Apartment F.1.4, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465855",
      "property_address": "Apartment F.1.6, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465858",
      "property_address": "Apartment F.2.5, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465862",
      "property_address": "Flat 207, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465863",
      "property_address": "Apartment F.3.1, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465864",
      "property_address": "Apartment F.3.2, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465865",
      "property_address": "Flat 305, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465867",
      "property_address": "Apartment F.3.7, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465869",
      "property_address": "Apartment F.4.1, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465871",
      "property_address": "Apartment F.4.2, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465874",
      "property_address": "Flat 404, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465876",
      "property_address": "Flat 405, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465882",
      "property_address": "Apartment F.5.1, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465884",
      "property_address": "Apartment F.5.2, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465885",
      "property_address": "Apartment F.5.3, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465886",
      "property_address": "Flat 504, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465888",
      "property_address": "Apartment F.5.6, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465890",
      "property_address": "Flat 601, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465891",
      "property_address": "Apartment F.6.2, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465893",
      "property_address": "Apartment F.6.3, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465894",
      "property_address": "Apartment F.6.4, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465917",
      "property_address": "Flat 507, Carriage House, 42 Leyton Road, London (E15 1GF)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465921",
      "property_address": "Apartment F.5.5, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465962",
      "property_address": "Apartment F.4.6, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL465968",
      "property_address": "Apartment F.4.3, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL46927",
      "property_address": "36 Brooklands Avenue, Wimbledon",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL472304",
      "property_address": "Flat 21c-00-01, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472313",
      "property_address": "Flat, 21c-00-02 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472314",
      "property_address": "190, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472322",
      "property_address": "191, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472350",
      "property_address": "Flat, 21c-01-01 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472355",
      "property_address": "193, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472357",
      "property_address": "Flat, 21c-01-03 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472361",
      "property_address": "Flat, 21c-01-04 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472364",
      "property_address": "Flat, 21c-01-13 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472366",
      "property_address": "Flat, 21c-01-14 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL472367",
      "property_address": "198, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473223",
      "property_address": "Flat, 21c-02-01 Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473226",
      "property_address": "Flat 21C-02-02, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473250",
      "property_address": "Flat 21C-02-03, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473276",
      "property_address": "Flat 21C-02-04, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473277",
      "property_address": "Flat 21C-02-13, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473280",
      "property_address": "204, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473283",
      "property_address": "Flat 21C-02-15, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473417",
      "property_address": "Flat 21C-03-01, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473422",
      "property_address": "Flat 21C-03-02, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473426",
      "property_address": "Flat 21C-03-03, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473429",
      "property_address": "Flat 21C-03-04, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473476",
      "property_address": "Flat 21C-03-13, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473493",
      "property_address": "Flat 21C-03-14, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473496",
      "property_address": "Flat 21C-03-15, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473604",
      "property_address": "220, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473606",
      "property_address": "Flat 21C-04-02, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473609",
      "property_address": "Flat 21C-04-03, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473610",
      "property_address": "Flat 21C-04-04, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473613",
      "property_address": "Flat 21C-04-13, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473621",
      "property_address": "Flat 21C-04-15, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473748",
      "property_address": "227, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473756",
      "property_address": "Flat 21C-05-02, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473759",
      "property_address": "222, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473761",
      "property_address": "Flat 21C-05-04, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473765",
      "property_address": "Flat 21C-05-13, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473775",
      "property_address": "Flat 21C-05-14, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473782",
      "property_address": "Flat 21C-05-15, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473876",
      "property_address": "Flat 21C-06-01, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473879",
      "property_address": "228, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473882",
      "property_address": "Flat 21C-06-03, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473885",
      "property_address": "Flat 21C-06-04, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473892",
      "property_address": "Flat 21C-06-13, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473911",
      "property_address": "Flat 21C-06-14, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473916",
      "property_address": "sixth floor flat, 233, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473960",
      "property_address": "Flat 21C-07-01, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473963",
      "property_address": "Flat 21C-07-02, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473964",
      "property_address": "Flat 21C-07-03, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473967",
      "property_address": "Flat 21C-07-04, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473971",
      "property_address": "Flat 21C-07-13, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473972",
      "property_address": "239, Banyan Court, 2 Regalia Close, London (E16 2TW)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL473978",
      "property_address": "Flat 21C-07-15, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481869",
      "property_address": "Flat 3, Somerset Place, 10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481880",
      "property_address": "Flat 103, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481881",
      "property_address": "Flat 5, Somerset Place, 10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481882",
      "property_address": "Flat 105, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481883",
      "property_address": "Flat 106, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481884",
      "property_address": "Flat 109, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481885",
      "property_address": "Flat 202, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481886",
      "property_address": "Flat 203, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481887",
      "property_address": "Flat 204, 11 Somerset Place, 10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481889",
      "property_address": "Flat 205, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481890",
      "property_address": "Flat 206, Hambrook Hill, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481894",
      "property_address": "Flat 304, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481898",
      "property_address": "Flat 12, Somerset Place, 10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL481899",
      "property_address": "Flat 312, Hambrook House, 6-10 Brixton Hill, London (SW2 1EG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492988",
      "property_address": "Flat 1, Block A, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492989",
      "property_address": "Flat 2, Block A, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492990",
      "property_address": "Flat 3, Block A, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492991",
      "property_address": "Flat 4, Block A, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492992",
      "property_address": "Flat 5, Block A, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492993",
      "property_address": "Flat 6, Block A, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492994",
      "property_address": "Flat 1, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492995",
      "property_address": "Flat 2, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492996",
      "property_address": "Flat 3, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL492997",
      "property_address": "Flat 4, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493007",
      "property_address": "Flat 5, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493009",
      "property_address": "Flat 9, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493011",
      "property_address": "Flat 10, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493012",
      "property_address": "Flat 11, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493013",
      "property_address": "Flat 12, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493014",
      "property_address": "Flat 16, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493015",
      "property_address": "Flat 17, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493016",
      "property_address": "Flat 18, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493017",
      "property_address": "Flat 19, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493019",
      "property_address": "Flat 20, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493020",
      "property_address": "Flat 21, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493021",
      "property_address": "Flat 22, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493023",
      "property_address": "Flat 23, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493025",
      "property_address": "Flat 24, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493027",
      "property_address": "Flat 25, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493028",
      "property_address": "Flat 26, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493029",
      "property_address": "Flat 27, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493031",
      "property_address": "Flat 28, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493033",
      "property_address": "Flat 29, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493034",
      "property_address": "Flat 30, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493036",
      "property_address": "Flat 31, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493037",
      "property_address": "Flat 32, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493039",
      "property_address": "Flat 33, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493040",
      "property_address": "Flat 34, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493041",
      "property_address": "Flat 35, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493042",
      "property_address": "Flat 36, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493043",
      "property_address": "Flat 1, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493044",
      "property_address": "Flat 2, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493045",
      "property_address": "Flat 3, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493048",
      "property_address": "Flat 4, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493050",
      "property_address": "Flat 5, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493051",
      "property_address": "Flat 6, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493053",
      "property_address": "Flat 7, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493054",
      "property_address": "Flat 8, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493055",
      "property_address": "Flat 9, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493057",
      "property_address": "Flat 10, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493058",
      "property_address": "Flat 11, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493059",
      "property_address": "Flat 12, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493060",
      "property_address": "Flat 13, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493062",
      "property_address": "Flat 14, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493063",
      "property_address": "Flat 15, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493065",
      "property_address": "Flat 16, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493066",
      "property_address": "Flat 17, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493068",
      "property_address": "Flat 18, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493069",
      "property_address": "Flat 19, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493071",
      "property_address": "Flat 20, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493072",
      "property_address": "Flat 21, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493073",
      "property_address": "Flat 22, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493074",
      "property_address": "Flat 23, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493075",
      "property_address": "Flat 24, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493076",
      "property_address": "Flat 25, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493082",
      "property_address": "Flat 6, Block C, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493083",
      "property_address": "Flat 26, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493084",
      "property_address": "Flat 27, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493085",
      "property_address": "Flat 28, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493087",
      "property_address": "Flat 29, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493088",
      "property_address": "Flat 30, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493089",
      "property_address": "Flat 31, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493092",
      "property_address": "Flat 32, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493093",
      "property_address": "Flat 33, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493094",
      "property_address": "Flat 34, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493095",
      "property_address": "Flat 35, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493096",
      "property_address": "Flat 36, Block F, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493228",
      "property_address": "Parking Space 29, Car Parking Area Zone 1 Upper, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493230",
      "property_address": "Parking Space 30, Car Parking Area Zone 1 Upper, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493236",
      "property_address": "Parking Space 31, Car Parking Area Zone 1 Upper, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493238",
      "property_address": "Parking Space 32, Car Parking Area Zone 1, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493239",
      "property_address": "Parking Space 41, Car Parking Area Zone 1, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493240",
      "property_address": "Parking Space 42, Car Parking Area Zone 1, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493241",
      "property_address": "Parking Space 52, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493242",
      "property_address": "Parking Space 53, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493245",
      "property_address": "Parking Space 54, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493247",
      "property_address": "Parking Space 55, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493253",
      "property_address": "Parking Space 56, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493255",
      "property_address": "Parking Space 57, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493257",
      "property_address": "Parking Space 58, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493259",
      "property_address": "Parking Space 71, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493288",
      "property_address": "Parking Space 72, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493290",
      "property_address": "Parking Space 73, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493292",
      "property_address": "Parking Space 74, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493294",
      "property_address": "Parking Space 75, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493296",
      "property_address": "Parking Space 76, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493303",
      "property_address": "Parking Space 77, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493304",
      "property_address": "Parking Space 78, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493305",
      "property_address": "Parking Space 79, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493308",
      "property_address": "Parking Space 80, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493309",
      "property_address": "Parking Space 81, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493311",
      "property_address": "Parking Space 82, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493313",
      "property_address": "Parking Space 83, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493322",
      "property_address": "Parking Space 84, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493323",
      "property_address": "Parking Space 85, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493325",
      "property_address": "Parking Space 86, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493327",
      "property_address": "Parking Space 87, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493329",
      "property_address": "Parking Space 89, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493330",
      "property_address": "Parking Space 90, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493332",
      "property_address": "Parking Space 91, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493333",
      "property_address": "Parking Space 92, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493337",
      "property_address": "Parking Space 93, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493341",
      "property_address": "Parking Space 94, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493344",
      "property_address": "Parking Space 95, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493347",
      "property_address": "Parking Space 96, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493351",
      "property_address": "Parking Space 97, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL493353",
      "property_address": "Parking Space 98, Car Park Area Zone 2, Armada Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL497853",
      "property_address": "12,14,18 and 20 Cavendish Square, London and 1 to 32 (inclusive) Mare Apartments, 16 Cavendish Square, London (E16 2XP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL497856",
      "property_address": "15, 17, 21 and 23 Shackleton Way and 1 to 32 (inclusive) Lyle Apartments, 19 Shackleton Way, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL497969",
      "property_address": "Apartment J0.01, Block J Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498023",
      "property_address": "301, Braithwaite House, 7 Forrester Way, London (E15 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498026",
      "property_address": "203, Braithwaite House, 7 Forrester Way, London (E15 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498028",
      "property_address": "Flat 101, Braithwaite House, 7 Forrester Way, London (E15 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498029",
      "property_address": "104, Braithwaite House, 7 Forrester Way, London (E15 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498030",
      "property_address": "Apartment 2.01, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498031",
      "property_address": "Apartment J3.05, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498034",
      "property_address": "403, Braithwaite House, 7 Forrester Way, London (E15 1GH)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498035",
      "property_address": "Apartment J3.03, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498036",
      "property_address": "Apartment J3.04, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498037",
      "property_address": "Apartment J3.02, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL498038",
      "property_address": "Apartment J 2.02, Chobham Farm, Leyton Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL513179",
      "property_address": "Plant Room, 334 Clapham Road, London (SW9 9AP)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL514914",
      "property_address": "Flat 21C-04-14, Royal Wharf, North Woolwich Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL519953",
      "property_address": "Flats 1 to 16 (inclusive), 18, 19, 22 and 23 George Court, 3 Shackleton Way, London (E16 2XL)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL519960",
      "property_address": "Flats 1, 7, 8, 11, 12, 15, 16, 19, 20 and 23 Guthrum Court, 1 Cavendish Square, London (E16 2XN)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL520298",
      "property_address": "Land on the south-west side of Southampton Way, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL52452",
      "property_address": "Flat 19, Jagger House, Rosenau Road, London (SW11 4QY)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL5329",
      "property_address": "4 Cottingham Road (SW8 1LQ)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL558519",
      "property_address": "Land on the North side of Peckham High Street, London",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL575015",
      "property_address": "1 to 3 Swinbridge Close, London (E16 2ZF) and 6, 11, 17, 23, 26, 29, 32, 33, 35 to 51, 53 to 57 and 59 to 72, 2 Pier Road, London (E16 2JJ)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL58232",
      "property_address": "162 Southcroft Road, London (SW17 9TP)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL76608",
      "property_address": "33 Acre Road, Kingston Upon Thames (KT2 6EF)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL77501",
      "property_address": "Flat 1, 22 Lambert Avenue, (TW9 4QR)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL80481",
      "property_address": "7 John Clyne Court, Woodborough Road (SW15 6PU)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL81728",
      "property_address": "155 Earlsfield Road, Earlsfield, (SW18 3DD)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL85816",
      "property_address": "140 and 142 Brook Drive, Flats 1 to 6, 144 Brook Drive, Flats 1 to 6, 1 Dante Road, 3 and 5 Dante Road, London",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL8633",
      "property_address": "63 Burntwood Lane, Earlsfield",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL86702",
      "property_address": "26 Parkview Court, Broomhill Road, (SW18 4JG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL8692",
      "property_address": "136 Lessingham Avenue, Tooting, London (SW17 8NH)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL86951",
      "property_address": "34 Parkview Court, Broomhill Road",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL8873",
      "property_address": "43B Shakespeare Road, London (SE24 0LA)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL89989",
      "property_address": "121 Pincott Place, and parking space, (SE4 2ES)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL92063",
      "property_address": "41 Oakmead Place, Mitcham, (CR4 3RU)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL92308",
      "property_address": "11 Norwood Close, Twickenham (TW2 5EX)",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL92392",
      "property_address": "42 Veals Mead, Mitcham",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL93388",
      "property_address": "38 Dinton Road, Colliers Wood, (SW19 9XX)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "TGL98511",
      "property_address": "52 Queens Road, New Malden",
      "tenure": "Freehold"
    },
    {
      "title_number": "TGL99348",
      "property_address": "37 Peartree Avenue, Tooting and Parking Space, (SW17 OJG)",
      "tenure": "Leasehold"
    },
    {
      "title_number": "WSX142377",
      "property_address": "32 Palmer Place, North Mundham, Chichester (PO20 1JW)",
      "tenure": "Freehold"
    },
    {
      "title_number": "WSX81564",
      "property_address": "3 Ross Close, Tilgate",
      "tenure": "Freehold"
    },
    {
      "title_number": "WSX84150",
      "property_address": "2 Windrush, 2 Granville Road, Littlehampton, Garden Ground and Parking Space",
      "tenure": "Leasehold"
    },
    {
      "title_number": "WYK157885",
      "property_address": "6 Clarendon Street, Haworth, Keighley",
      "tenure": "Freehold"
    }
  ]
}
```
