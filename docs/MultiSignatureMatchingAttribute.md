# MultiSignatureMatchingAttribute


## GET /multisignaturematchingattribute/{parameterHPIDs}
- Response 200 (application/json)

[MultiSignatureMatchingAttributeResponse](MultiSignatureMatchingAttributeResponse.md)
    ```
   /MultiSignatureMatchingAttribute/87fb49ea-9964-4612-bf91-9796ea75247e/Level/BST
    ```
    ```json
   {
  "hpids": "87fb49ea-9964-4612-bf91-9796ea75247e",
  "attribute_name": "Level",
  "attribute_value": "BST",
  "matching_attribute_addresses": [
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
    }
  ]
}
    ```
