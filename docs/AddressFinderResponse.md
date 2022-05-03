# AddressFinderResponse
## Properties
- hpid (String)

   
- address (String)

   
- hpid ([ValueLink](ValueLink.md) for [MultiSignatureResponse](MultiSignatureResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "hpid" : "string",
       "address" : "string",
       "hpid" : {"$ref" : "/schemas/valuelink"}
    }
}
```

