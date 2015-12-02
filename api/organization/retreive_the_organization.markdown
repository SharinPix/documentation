# Organization API

## Retreive the organization

### GET /api/v1/organization
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzEsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlYjIzNmI4Zi1jY2IxLTRiYTEtOWFiMC0zZmM0YzkzNDE3OGUifQ.M5Rlp-ACVXlkpM2otlMC7OKo27E9WFZw2n004JSgu2w&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/organization</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-access-stats: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzEsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlYjIzNmI4Zi1jY2IxLTRiYTEtOWFiMC0zZmM0YzkzNDE3OGUifQ.M5Rlp-ACVXlkpM2otlMC7OKo27E9WFZw2n004JSgu2w
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;da0043d82dda3f7c8181e2e437d2ccd5&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 77efd4e8-2975-4b27-af36-079850706b32
X-Runtime: 0.019017
Content-Length: 64</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"a2fe486f-c71e-4892-a8e5-069936576d26","name":"SharinPix"}</pre>
