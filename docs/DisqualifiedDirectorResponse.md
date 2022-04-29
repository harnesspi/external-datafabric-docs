# DisqualifiedDirectorResponse
## Description

## Properties
### person_number


Type Description: String
### country_registration


Type Description: String
### person_hpid


Type Description: String
### corporate_number


Type Description: String
### person_date_of_birth


Type Description: String
### title


Type Description: String
### forenames


Type Description: String
### surname


Type Description: String
### honours


Type Description: String
### nationality


Type Description: String
### address_line1


Type Description: String
### address_line2


Type Description: String
### post_town


Type Description: String
### person_postcode


Type Description: String
### country


Type Description: String
### disqualified_director_details_grid


Type Description: Array of DisqualifiedDirectorDetailsGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "person_number" : ["string", "null"],
       "country_registration" : ["string", "null"],
       "person_hpid" : ["string", "null"],
       "corporate_number" : ["string", "null"],
       "person_date_of_birth" : ["string", "null"],
       "title" : ["string", "null"],
       "forenames" : ["string", "null"],
       "surname" : ["string", "null"],
       "honours" : ["string", "null"],
       "nationality" : ["string", "null"],
       "address_line1" : ["string", "null"],
       "address_line2" : ["string", "null"],
       "post_town" : ["string", "null"],
       "person_postcode" : ["string", "null"],
       "country" : ["string", "null"],
       "disqualified_director_details_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/DisqualifiedDirectorDetailsGrid"}
}
```

## Related Entities
- [DisqualifiedDirectorDetailsGridResponse](DisqualifiedDirectorDetailsGridResponse.md)

