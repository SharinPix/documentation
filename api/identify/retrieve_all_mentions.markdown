# Identify API

## Retrieve all mentions

### GET /api/v1/mentions

### Parameters

Name : id
Description : publication id

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkODU1ZjE4Ny01MmZjLTRjODQtOWEwNy1lZDE0MWY5Yjg3OTAifQ.4PdUp2oagZTMAimd992id-gZf0GKsMSDopREGKCB6Ps&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/mentions?id=97fa8753-d333-4d62-89bb-fb1c54e46831</pre>

#### Query Parameters

<pre>id: 97fa8753-d333-4d62-89bb-fb1c54e46831</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store, must-revalidate, private, max-age=0
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkODU1ZjE4Ny01MmZjLTRjODQtOWEwNy1lZDE0MWY5Yjg3OTAifQ.-JjHPsJP61UQJMzWlHspCDX4QcjAKnZaAjsMmtp6-dE
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d6063701-921d-4072-89f5-444ff588fbf7
X-Runtime: 0.026898
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
