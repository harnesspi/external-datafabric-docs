# KeyResponse
## Properties
- key_type (String)

   
- key_value (String)

   
- description (String)

   
- row_link (String)

   
- order_rank (String)

   
- row_link ([ValueLink](ValueLink.md) for [object](object.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "key_type" : "string",
       "key_value" : "string",
       "description" : "string",
       "row_link" : "string",
       "order_rank" : "string",
       "row_link" : {"$ref" : "/schemas/valuelink"}
    }
}
```

