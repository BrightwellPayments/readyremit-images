Below is a comparison between a SwaggerHub request that works and a readme request that does not work. 

Both platforms use proxy servers. Swagger uses https://app.swaggerhub.com/proxy and readme uses https://try.readme.io.

SWAGGERHUB

Request URL: https://app.swaggerhub.com/proxy?proxy-token=64kxamf&url=https%3A%2F%2Fdev-api.readyremit.com%2Fv1%2Foauth%2Ftoken
Request Method: POST
Status Code: 200 
Remote Address: 107.22.88.47:443
Referrer Policy: same-origin

Request Data:

{
  "client_id": "***",
  "client_secret": "***",
  "audience": "***",
  "grant_type": "***"
}

Response Data:

{
  "access_token":"***",
  "scope":"***",
  "expires_in":1800,
  "token_type":"Bearer"
}

README

Request URL: https://try.readme.io/https://dev-api.readyremit.com/v1/oauth/token
Request Method: POST
Status Code: 200 OK
Remote Address: 3.226.182.14:443
Referrer Policy: strict-origin-when-cross-origin

Request Data:

{
  "client_id":"***",
  "client_secret":"***",
  "audience":"***",
  "grant_type":"***"
}

Response Data:

None.