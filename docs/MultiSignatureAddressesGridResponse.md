# MultiSignatureAddressesGridResponse
## Description

## Properties
### signature_hpid


Type Description: String
### address_hpid


Type Description: String
### source_name


Type Description: String
### key


Type Description: String
### uprn


Type Description: String
### organisation


Type Description: String
### address


Type Description: String
### postcode


Type Description: String
### url_query


Type Description: KeyValueLink for object

## Schema
```json
{
    "type":"object",
    "properties": {
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

## Related Entities
- [KeyValueLink](KeyValueLink.md)

