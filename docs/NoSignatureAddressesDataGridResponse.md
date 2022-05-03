# NoSignatureAddressesDataGridResponse
## Properties
- source_name (String)

   
- row_key (String)

   
- row_key_subfix (String)

   
- organisation (String)

   
- address (String)

   
- usrn (String)

   
- street (String)

   
- postcode (String)

   
- building (String)

   
- url_query ([KeyValueLink](KeyValueLink.md) for [object](object.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "source_name" : "string",
       "row_key" : "string",
       "row_key_subfix" : "string",
       "organisation" : "string",
       "address" : "string",
       "usrn" : "string",
       "street" : "string",
       "postcode" : "string",
       "building" : "string",
       "url_query" : {"$ref" : "/schemas/keyvaluelink"}
    }
}
```

