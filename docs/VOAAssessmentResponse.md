# VOAAssessmentResponse
## Description

## Properties
### assessment_reference


Type Description: String
### list_year


Type Description: String
### uarn


Type Description: String
### scheme_reference


Type Description: String
### primary_description_text


Type Description: String
### total_area


Type Description: String
### sub_total


Type Description: String
### total_value


Type Description: String
### adopted_rv


Type Description: String
### ba_name


Type Description: String
### from_date


Type Description: String
### to_date


Type Description: String
### scat_code_only


Type Description: String
### unit_of_measurement


Type Description: String
### unadjusted_price


Type Description: String
### cp_spaces


Type Description: String
### cp_spaces_value


Type Description: String
### cp_area


Type Description: String
### cp_area_value


Type Description: String
### cp_total


Type Description: String
### pm_value


Type Description: String
### total_before_adj


Type Description: String
### total_adj


Type Description: String
### voa_assessment_details


Type Description: Array of VOAAssessmentDetailsGridResponse

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

## Related Entities
- [VOAAssessmentDetailsGridResponse](VOAAssessmentDetailsGridResponse.md)

