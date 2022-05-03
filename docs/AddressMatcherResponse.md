# AddressMatcherResponse
## Properties
- hpid (String)

   
- address (String)

   
- hpids (String)

   
- street (String)

   
- usrn (String)

   
- postcode (String)

   
- hpid ([ValueLink](ValueLink.md) for [MultiSignatureResponse](MultiSignatureResponse.md))

   
- usrn ([ValueLink](ValueLink.md) for [StreetResponse](StreetResponse.md))

   
- postcode ([ValueLink](ValueLink.md) for [SignatureKeyResponse](SignatureKeyResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "hpid" : "string",
       "address" : "string",
       "hpids" : "string",
       "street" : "string",
       "usrn" : "string",
       "postcode" : "string",
       "hpid" : {"$ref" : "/schemas/valuelink"},
       "usrn" : {"$ref" : "/schemas/valuelink"},
       "postcode" : {"$ref" : "/schemas/valuelink"}
    }
}
```

