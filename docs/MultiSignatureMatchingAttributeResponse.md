# MultiSignatureMatchingAttributeResponse
## Properties
- hpids (String)

   
- attribute_name (String)

   
- attribute_value (String)

   
- matching_attribute_addresses (Array of [MatchingAttributeAddressesDataGridResponse](MatchingAttributeAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "hpids" : ["string", "null"],
       "attribute_name" : ["string", "null"],
       "attribute_value" : ["string", "null"],
       "matching_attribute_addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/MatchingAttributeAddressesDataGrid"}
}
```

