# AddressMatcherResponse
## Description

## Properties
### hpid


Type Description: String
### address


Type Description: String
### hpids


Type Description: String
### street


Type Description: String
### usrn


Type Description: String
### postcode


Type Description: String
### hpid


Type Description: ValueLink for MultiSignatureResponse
### usrn


Type Description: ValueLink for StreetResponse
### postcode


Type Description: ValueLink for SignatureKeyResponse

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

## Related Entities
- [MultiSignatureResponse](MultiSignatureResponse.md)
- [ValueLink](ValueLink.md)
- [StreetResponse](StreetResponse.md)
- [SignatureKeyResponse](SignatureKeyResponse.md)

