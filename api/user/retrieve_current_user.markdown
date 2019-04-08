# User API

## Retrieve current user

### GET /api/v1/user
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzgsImlhdCI6MTU1NDc0NTEzOCwidXNlcl9pZCI6IjhjYTA3YjBkLTQyNDAtNDllOC05YzA4LTA4MDkzZWQ5OTYyMiJ9.-Ycf0JAWWOzgbw0-AWile8cG3FRlRcHaCCFWTUdNGGo&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/user</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-access-admin: false
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzgsImlhdCI6MTU1NDc0NTEzOCwidXNlcl9pZCI6IjhjYTA3YjBkLTQyNDAtNDllOC05YzA4LTA4MDkzZWQ5OTYyMiJ9.-Ycf0JAWWOzgbw0-AWile8cG3FRlRcHaCCFWTUdNGGo
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2cbddbd0-fde9-4d6a-a830-a1cd071b93c1
X-Runtime: 0.006693
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 183</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "public_id": "8ca07b0d-4240-49e8-9c08-08093ed99622",
  "fullname": "translation missing: en.unknown_user",
  "email": "luc+101@sharinpix.com",
  "admin": false,
  "username": "luc+101@sharinpix.com"
}</pre>
