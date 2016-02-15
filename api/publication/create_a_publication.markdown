# Publication API

## Create a publication

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI3MzFkZDRhYS1jZTM5LTQyZGUtYTYwOS0wMDc4YzRkM2FiOWUifQ.DdXhSPyqnCiIDKTmYVSvAbCMGOaol7u655W7X3nJ0YQ&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/f7245380-b930-4f21-aeaf-50f5cd1cf53a/publications</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI3MzFkZDRhYS1jZTM5LTQyZGUtYTYwOS0wMDc4YzRkM2FiOWUifQ.DdXhSPyqnCiIDKTmYVSvAbCMGOaol7u655W7X3nJ0YQ
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ac8544c9-d64a-4732-8754-7706171fd679
X-Runtime: 0.048814
Content-Length: 313</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"4edb990e-e6c9-4c71-9a15-77035efdc1ec","thumbnail":"https://localhost/publications/4edb990e-e6c9-4c71-9a15-77035efdc1ec/thumbnail","title":"Album du 15/02/2016","description":"1 photo disponible\nPowered by SharinPix","aux_text":"a partagé un album: ","entity_id":"","views_count":0,"opens_count":0}</pre>
