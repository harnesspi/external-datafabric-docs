# AddressMatcher
```
/addressmatcher/{parameterAddress}
```
returns [Array of AddressMatcherResponse](AddressMatcherResponse.md)
## Example Responses
```
/AddressMatcher/2 townshend road richmond
```
```json
[{"hpid":{"value":"87fb49ea-9964-4612-bf91-9796ea75247e","link":"/MultiSignature/87fb49ea-9964-4612-bf91-9796ea75247e"},"address":"2 TOWNSHEND RD TW9 1XH"}]
```
```
/AddressMatcher/townshend road richmond
```
```json
[{"hpids":"","street":"TOWNSHEND RD","usrn":{"value":"22406023","link":"/Street/22406023"},"postcode":{"value":"TW9 1XH","link":"/SignatureKey/Postcode/TW9 1XH"}}]
```
