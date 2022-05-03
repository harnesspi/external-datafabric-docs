# LandRegistryLeaseResponse
## Properties
- id (String)

   
- description (String)

   
- county (String)

   
- region (String)

   
- tenure (String)

   
- price_paid (String)

   
- alienation_clause_indicator (String)

   
- land_registry_lease_entries_data_grid (Array of [LandRegistryLeaseEntriesDataGridResponse](LandRegistryLeaseEntriesDataGridResponse.md))

   

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

