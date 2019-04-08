# Organization API

## Retrieve the organization

### GET /api/v1/organization
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDUsImlhdCI6MTU1NDc0NTE0NSwidXNlcl9pZCI6ImI2MDhkNjMzLWU1MjUtNDMxZi05NzFhLTI4ZGY1Y2MyZTQ5NCJ9.SKgoxUTfgbUyeSRrdrNqDRpDB4rdFgK80KKNP_lYaso&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/organization</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-access-stats: false
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDUsImlhdCI6MTU1NDc0NTE0NSwidXNlcl9pZCI6ImI2MDhkNjMzLWU1MjUtNDMxZi05NzFhLTI4ZGY1Y2MyZTQ5NCJ9.SKgoxUTfgbUyeSRrdrNqDRpDB4rdFgK80KKNP_lYaso
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 380b6c46-61e0-47cd-a3ea-d9dd87dd69a0
X-Runtime: 0.004924
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 138</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "06236c35-218f-4b8b-a2ed-5838fe193380",
  "name": "SharinPix-00D24000000IycKQWE (06236c35)",
  "sandbox": false,
  "sfid": "00D24000000IycKQWE"
}</pre>
