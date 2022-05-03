# SignatureKeyMatchingAttributeResponse
## Properties
- key_type (String)

   
- key_value (String)

   
- attribute_name (String)

   
- attribute_value (String)

   
- matching_attribute_addresses (Array of [MatchingAttributeAddressesDataGridResponse](MatchingAttributeAddressesDataGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "key_type" : ["string", "null"],
       "key_value" : ["string", "null"],
       "attribute_name" : ["string", "null"],
       "attribute_value" : ["string", "null"],
       "matching_attribute_addresses" : {"type" : "array", "items" : {"$ref" : "/schemas/MatchingAttributeAddressesDataGrid"}
}
```

