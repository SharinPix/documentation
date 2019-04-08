# Publication API

## Create a publication with text

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjgyZDZiNWIzLTFhZWYtNDQzZi05ZTQyLWE3YmIxMDcxMGFjZCJ9.niAUzIwRt7Z7huNT7i9uBYYsmm3Xvul2EcHLjT78LU8&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB251/publications</pre>

#### Body

<pre>infos[text]=I+am+sharing+this+amazing+album</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjgyZDZiNWIzLTFhZWYtNDQzZi05ZTQyLWE3YmIxMDcxMGFjZCJ9.niAUzIwRt7Z7huNT7i9uBYYsmm3Xvul2EcHLjT78LU8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 852ac6cb-d146-47e0-8359-661b5db2e59e
X-Runtime: 0.015460
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 307</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "public_id": "4c6a79c2-3406-4af6-b27d-108c5f23943d",
  "thumbnail": "https://localhost:5001/publications/4c6a79c2-3406-4af6-b27d-108c5f23943d/thumbnail",
  "title": "Album published on 2019-04-08",
  "description": "0 photos available\nPowered by SharinPix",
  "aux_text": "",
  "entity_id": "",
  "views_count": 0,
  "opens_count": 0
}</pre>
