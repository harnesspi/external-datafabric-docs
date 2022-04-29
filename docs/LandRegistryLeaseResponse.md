# LandRegistryLeaseResponse
## Description

## Properties
### id


Type Description: String
### description


Type Description: String
### county


Type Description: String
### region


Type Description: String
### tenure


Type Description: String
### price_paid


Type Description: String
### alienation_clause_indicator


Type Description: String
### land_registry_lease_entries_data_grid


Type Description: Array of LandRegistryLeaseEntriesDataGridResponse

## Schema
```json
{
    "type":"object",
    "properties": {
       "id" : ["string", "null"],
       "description" : ["string", "null"],
       "county" : ["string", "null"],
       "region" : ["string", "null"],
       "tenure" : ["string", "null"],
       "price_paid" : ["string", "null"],
       "alienation_clause_indicator" : ["string", "null"],
       "land_registry_lease_entries_data_grid" : {"type" : "array", "items" : {"$ref" : "/schemas/LandRegistryLeaseEntriesDataGrid"}
}
```

## Related Entities
- [LandRegistryLeaseEntriesDataGridResponse](LandRegistryLeaseEntriesDataGridResponse.md)

