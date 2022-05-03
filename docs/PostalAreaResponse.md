# PostalAreaResponse
## Properties
- streets (Array of [PostalAreaStreetsDataGridResponse](PostalAreaStreetsDataGridResponse.md))

   
- category_d (String)

   
- category_s (String)

   
- category_t (String)

   
- category_f (String)

   
- category_o (String)

   

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

