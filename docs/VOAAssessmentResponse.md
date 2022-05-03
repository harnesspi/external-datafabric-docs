# VOAAssessmentResponse
## Properties
- assessment_reference (String)

   
- list_year (String)

   
- uarn (String)

   
- scheme_reference (String)

   
- primary_description_text (String)

   
- total_area (String)

   
- sub_total (String)

   
- total_value (String)

   
- adopted_rv (String)

   
- ba_name (String)

   
- from_date (String)

   
- to_date (String)

   
- scat_code_only (String)

   
- unit_of_measurement (String)

   
- unadjusted_price (String)

   
- cp_spaces (String)

   
- cp_spaces_value (String)

   
- cp_area (String)

   
- cp_area_value (String)

   
- cp_total (String)

   
- pm_value (String)

   
- total_before_adj (String)

   
- total_adj (String)

   
- voa_assessment_details (Array of [VOAAssessmentDetailsGridResponse](VOAAssessmentDetailsGridResponse.md))

   

## Schema
```json
{
    "type":"object",
    "properties": {
       "assessment_reference" : ["string", "null"],
       "list_year" : ["string", "null"],
       "uarn" : ["string", "null"],
       "scheme_reference" : ["string", "null"],
       "primary_description_text" : ["string", "null"],
       "total_area" : ["string", "null"],
       "sub_total" : ["string", "null"],
       "total_value" : ["string", "null"],
       "adopted_rv" : ["string", "null"],
       "ba_name" : ["string", "null"],
       "from_date" : ["string", "null"],
       "to_date" : ["string", "null"],
       "scat_code_only" : ["string", "null"],
       "unit_of_measurement" : ["string", "null"],
       "unadjusted_price" : ["string", "null"],
       "cp_spaces" : ["string", "null"],
       "cp_spaces_value" : ["string", "null"],
       "cp_area" : ["string", "null"],
       "cp_area_value" : ["string", "null"],
       "cp_total" : ["string", "null"],
       "pm_value" : ["string", "null"],
       "total_before_adj" : ["string", "null"],
       "total_adj" : ["string", "null"],
       "voa_assessment_details" : {"type" : "array", "items" : {"$ref" : "/schemas/VOAAssessmentDetailsGrid"}
}
```

