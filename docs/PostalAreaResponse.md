# PostalAreaResponse
## Description

## Properties
### streets


Type Description: Array of PostalAreaStreetsDataGridResponse
### category_d


Type Description: String
### category_s


Type Description: String
### category_t


Type Description: String
### category_f


Type Description: String
### category_o


Type Description: String

## Schema
```json
{
    "type":"object",
    "properties": {
       "streets" : {"type" : "array", "items" : {"$ref" : "/schemas/PostalAreaStreetsDataGrid"},
       "category_d" : ["string", "null"],
       "category_s" : ["string", "null"],
       "category_t" : ["string", "null"],
       "category_f" : ["string", "null"],
       "category_o" : ["string", "null"],
}
```

## Related Entities
- [PostalAreaStreetsDataGridResponse](PostalAreaStreetsDataGridResponse.md)

