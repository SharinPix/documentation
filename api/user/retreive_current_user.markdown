# User API

## Retreive current user

### GET /api/v1/user
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJhMzgwNjFiMS04MTgwLTRhM2UtYjdmMC0wOWNhOThjYTQ5YjkifQ.qTMS5sNsnJHK4LjsW45TaBGgXYB_nglF2M4XbakzmL8&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/user</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-access-admin: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJhMzgwNjFiMS04MTgwLTRhM2UtYjdmMC0wOWNhOThjYTQ5YjkifQ.qTMS5sNsnJHK4LjsW45TaBGgXYB_nglF2M4XbakzmL8
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;5f4c620a5735993ac3d995cae82086c8&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2bbd5c80-f407-4205-a0bb-f98410d4d920
X-Runtime: 0.029103
Content-Length: 133</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"a38061b1-8180-4a3e-b7f0-09ca98ca49b9","fullname":"translation missing: fr.unknown_user","email":"luc+23@sharinpix.com"}</pre>
