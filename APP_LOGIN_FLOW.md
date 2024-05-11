## Simple Login Flow
Credits to: @soulweaver. on Discord


The app flow is:
- GET `/kick-token-provider` for the fields to use in `/mobile/login`
- POST `/mobile/login` and get the response of `{"2fa_required":true}`
- GET `/kick-token-provider` again, I'm not sure if this is required or the fields from the first one can be reused, but this is what the app does (edit: this isn't required apparently)
- POST  `/mobile/login` but include `"one_time_password": "xxxxxx"` in the JSON body

Example body:
```json
{
  "email": "",
  "password": "",
  "one_time_password": "xxxxxx",
  "_kick_token_xxxxxxxxxx": "",
  "_kick_token_valid_from": "",
  "isMobileRequest": true
}
```
Other information
`/api/v1/signup/verify/login-code` is only used for the webapp auth flow, which is all sorts of funky anyway
