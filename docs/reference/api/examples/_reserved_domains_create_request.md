
###### Example Request
```curl \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"name":"myapp.mydomain.com","region":"us","certificate_id":"cert_2E8b1kFAMvEiyadu68JDbjakz4G"}' \
https://api.ngrok.com/reserved_domains