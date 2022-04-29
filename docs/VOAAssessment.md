# VOAAssessment

```
/voaassessment/{parameterAssessmentReference}
```
returns [VOAAssessmentResponse](VOAAssessmentResponse.md)
## Example Responses
```
/VOAAssessment/10000005000
```
```json
{"assessment_reference":"10000005000","list_year":"2010","uarn":"49110033","scheme_reference":"97416","primary_description_text":"Shop And Premises","total_area":"103.15","sub_total":"3674","total_value":"3674","adopted_rv":"3650","ba_name":"Ashfield","from_date":"2010-04-01T00:00:00","to_date":null,"scat_code_only":"249","unit_of_measurement":"NIA","unadjusted_price":"70.00","cp_spaces":null,"cp_spaces_value":null,"cp_area":null,"cp_area_value":null,"cp_total":null,"pm_value":null,"total_before_adj":null,"total_adj":null,"voa_assessment_details":[{"detail_source":"LineItems","floor":"Ground","description":"Retail Zone A","area":"47.40","price":"70.00","value":"3318.00","percentage":null},{"detail_source":"LineItems","floor":"Ground","description":"Retail Zone B","area":"5.72","price":"35.00","value":"200.00","percentage":null},{"detail_source":"LineItems","floor":"First","description":"Internal Storage","area":"36.11","price":"3.50","value":"126.00","percentage":null},{"detail_source":"LineItems","floor":"First","description":"Kitchen","area":"8.46","price":"3.50","value":"30.00","percentage":null},{"detail_source":"LineItems","floor":"First","description":"Staff Toilets","area":null,"price":"0.00","value":"0.00","percentage":null}]}
```
