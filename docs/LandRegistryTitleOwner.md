# LandRegistryTitleOwner

```
/landregistrytitleowner/{parameterAddressId}/{parameterCompanyId}
```
returns [LandRegistryTitleOwnerResponse](LandRegistryTitleOwnerResponse.md)
## Example Responses
```
/LandRegistryTitleOwner/9F0459F0-6702-55C4-9888-E30028D3821E/5B1E336F-761F-296D-781F-00004071C41F
```
```json
{"address":"Sixth Floor, 25 Farringdon Street, London EC4A 4AB","postcode":"EC4A 4AB","companies":[{"registration_no":"02206329","company":"02206329","name":"ROSSMOREGATE LIMITED","country":"UK","description":"Limited Company or Public Limited Company","titles":"5b1e336f-761f-296d-781f-00004071c41f"}],"signatures":[{"signature_hpid":{"value":"5e3b6180-0bf8-8691-889c-828b119a68e0","link":"/SignatureHPID/5e3b6180-0bf8-8691-889c-828b119a68e0"},"building_name":null,"start_number":"25","end_number":null,"usrn":{"value":"8100194","link":"/Street/8100194"},"street":"FARRINGDON ST","keys":[{"key":"BuildingPolygon","value":"107643525","link":"/SignatureKey/BuildingPolygon/107643525"},{"key":"Ext.Toid","value":"osgb1000001802798548","link":"/SignatureKey/Ext.Toid/osgb1000001802798548"},{"key":"LandRegistryFreehold","value":"148900","link":"/SignatureKey/LandRegistryFreehold/148900"},{"key":"Postcode","value":"EC1A 4AB","link":"/SignatureKey/Postcode/EC1A 4AB"},{"key":"Postcode","value":"EC4 4AB","link":"/SignatureKey/Postcode/EC4 4AB"},{"key":"Postcode","value":"EC4A 2BU","link":"/SignatureKey/Postcode/EC4A 2BU"},{"key":"Postcode","value":"EC4A 4AB","link":"/SignatureKey/Postcode/EC4A 4AB"},{"key":"Postcode","value":"EC4A 4AD","link":"/SignatureKey/Postcode/EC4A 4AD"},{"key":"Postcode","value":"EC4A 4AF","link":"/SignatureKey/Postcode/EC4A 4AF"},{"key":"Postcode","value":"EC4A 4BD","link":"/SignatureKey/Postcode/EC4A 4BD"},{"key":"Postcode","value":"EC4A 4JA","link":"/SignatureKey/Postcode/EC4A 4JA"},{"key":"Postcode","value":"GU1 1UN","link":"/SignatureKey/Postcode/GU1 1UN"},{"key":"Postcode","value":"SW18 5DP","link":"/SignatureKey/Postcode/SW18 5DP"},{"key":"TopUPRN","value":"100022935980","link":"/SignatureKey/TopUPRN/100022935980"}]}],"internals":[{"signature_hpid":"5e3b6180-0bf8-8691-889c-828b119a68e0","internal_hpid":"d840f77b-239b-d02e-d9f6-551c3cbbf9b3","organisation":"ROSSMOREGATE LTD","land":null,"plot":null,"block":null,"level":"6","arch":null,"unit":null,"flat":null,"room":null,"parking":null,"description":null,"object_type":null,"keys":"CompanyNumber:02206329,CompanyNumber:2206329","signature":" 25 FARRINGDON ST"}],"no_signatures":[]}
```
