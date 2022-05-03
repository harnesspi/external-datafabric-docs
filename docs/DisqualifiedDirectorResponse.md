# DisqualifiedDirectorResponse
## Properties
- person_number (String)

   
- country_registration (String)

   
- person_hpid (String)

   
- corporate_number (String)

   
- person_date_of_birth (String)

   
- title (String)

   
- forenames (String)

   
- surname (String)

   
- honours (String)

   
- nationality (String)

   
- address_line1 (String)

   
- address_line2 (String)

   
- post_town (String)

   
- person_postcode (String)

   
- country (String)

   
- disqualified_director_details_grid (Array of [DisqualifiedDirectorDetailsGridResponse](DisqualifiedDirectorDetailsGridResponse.md))

   

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

