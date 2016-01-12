# Publication API

## Create a publication with text

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI0OTViNWZiOS0zNDAwLTRiMTYtOTE2Zi1hNzVmYTQyMzgwOTYifQ.T1qy0ZJ0f0Wb92VsLnEFlshBMVS2k6YUELRoclSbsms&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/3457c503-5728-4398-9307-ffafe08b5ec9/publications</pre>

#### Body

<pre>infos[text]=I+am+sharing+this+amazing+album</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI0OTViNWZiOS0zNDAwLTRiMTYtOTE2Zi1hNzVmYTQyMzgwOTYifQ.LMF5VenojzQ3wOCusMrvQdIwYSvbhjavIPoAHeSg9LA
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: cf79d002-abd2-468a-ab5b-278f12ea5db1
X-Runtime: 0.041632
Content-Length: 292</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"b120a650-61f9-48a3-9072-a122c945847d","thumbnail":"https://localhost/publications/b120a650-61f9-48a3-9072-a122c945847d/thumbnail","title":"Album du 12/01/2016","description":"1 photo disponible\nPowered by SharinPix","aux_text":"","entity_id":"","views_count":0,"opens_count":0}</pre>
