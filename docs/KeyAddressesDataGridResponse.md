# KeyAddressesDataGridResponse
## Properties
- records_count (String)

   
- ordinal_number (String)

   
- signature_hpid (String)

   
- address_hpid (String)

   
- source_name (String)

   
- key (String)

   
- uprn (String)

   
- organisation (String)

   
- address (String)

   
- postcode (String)

   
- url_query ([KeyValueLink](KeyValueLink.md) for [object](object.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "records_count" : "string",
       "ordinal_number" : "string",
       "signature_hpid" : "string",
       "address_hpid" : "string",
       "source_name" : "string",
       "key" : "string",
       "uprn" : "string",
       "organisation" : "string",
       "address" : "string",
       "postcode" : "string",
       "url_query" : {"$ref" : "/schemas/keyvaluelink"}
    }
}
```

