# MultiSignatureMatchingAttributeResponse
## Description

## Properties
### hpids


Type Description: String
### attribute_name


Type Description: String
### attribute_value


Type Description: String
### matching_attribute_addresses


Type Description: Array of MatchingAttributeAddressesDataGridResponse

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

## Related Entities
- [MatchingAttributeAddressesDataGridResponse](MatchingAttributeAddressesDataGridResponse.md)

