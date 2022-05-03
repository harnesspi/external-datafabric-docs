# Description


## GET /description/{parameterDescription}
- Response 200 (application/json)
[Array of DescriptionResponse](DescriptionResponse.md)

    ```
   /Key/cf2e37f7-fde4-cb2b-951b-dab63872db39
    ```
    ```json
   [
  {
    "key_type": "Signature",
    "key_value": "CF2E37F7-FDE4-CB2B-951B-DAB63872DB39",
    "description": null,
    "row_link": {
      "key": "Signature",
      "value": "CF2E37F7-FDE4-CB2B-951B-DAB63872DB39",
      "link": "/MultiSignature/CF2E37F7-FDE4-CB2B-951B-DAB63872DB39"
    }
  }
]
    ```
    ```
   /Description/guy's%20hospital
    ```
    ```json
   [
  {
    "key_type": "Estate",
    "key_value": "707322577",
    "description": "Guy's Hospital",
    "row_link": {
      "key": "Estate",
      "value": "707322577",
      "link": "/SignatureKey/Estate/707322577"
    },
    "order_rank": "99"
  },
  {
    "key_type": "Organisation",
    "key_value": "DB3B0FA3-7D3F-4E48-C835-3691C1B4E0C4",
    "description": "GUYS HOSPITAL",
    "row_link": {
      "key": "Organisation",
      "value": "DB3B0FA3-7D3F-4E48-C835-3691C1B4E0C4",
      "link": "/Organisation/DB3B0FA3-7D3F-4E48-C835-3691C1B4E0C4"
    },
    "order_rank": "99"
  },
  {
    "key_type": "Organisation",
    "key_value": "D08FCF5C-EB36-85FC-BD91-748C5E944167",
    "description": "GUYS HOSPITAL MEDICAL SCHOOL",
    "row_link": {
      "key": "Organisation",
      "value": "D08FCF5C-EB36-85FC-BD91-748C5E944167",
      "link": "/Organisation/D08FCF5C-EB36-85FC-BD91-748C5E944167"
    },
    "order_rank": "99"
  },
  {
    "key_type": "Organisation",
    "key_value": "2E830780-26BC-B6CE-7EE2-4DD0ED90A966",
    "description": "GUYS HOSPITAL STAFF DAY NURSERY",
    "row_link": {
      "key": "Organisation",
      "value": "2E830780-26BC-B6CE-7EE2-4DD0ED90A966",
      "link": "/Organisation/2E830780-26BC-B6CE-7EE2-4DD0ED90A966"
    },
    "order_rank": "99"
  }
]
    ```
