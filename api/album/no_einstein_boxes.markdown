# Album API

## No einstein boxes

### GET /api/v1/albums/:id/einstein_box_stats
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJlaW5zdGVpbiI6dHJ1ZSwiaXNzIjoiODQyNjM4YzAtOWZjZC00MDJiLWE2MjgtMWQwZmYyOTk5MzZhIn0.SFUK2gNENY9EklJuWphVV3MB42ods8lIDgMXSj81_6U&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/datasetsfid/einstein_box_stats</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwiaXNzIjoiODQyNjM4YzAtOWZjZC00MDJiLWE2MjgtMWQwZmYyOTk5MzZhIiwiZWluc3RlaW4iOnRydWV9.Jo9zrcK5IFQpXxxH0gGBsLqiBQXabfucX2RfSBscZpw
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2d576041-dd9d-4cbb-aa09-42aa78b9f9b4
X-Runtime: 0.009658
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 19</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "completed": false
}</pre>
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJlaW5zdGVpbiI6dHJ1ZSwiaXNzIjoiODQyNjM4YzAtOWZjZC00MDJiLWE2MjgtMWQwZmYyOTk5MzZhIn0.SFUK2gNENY9EklJuWphVV3MB42ods8lIDgMXSj81_6U&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/datasetsfid/einstein_box_stats</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwiaXNzIjoiODQyNjM4YzAtOWZjZC00MDJiLWE2MjgtMWQwZmYyOTk5MzZhIiwiZWluc3RlaW4iOnRydWV9.Jo9zrcK5IFQpXxxH0gGBsLqiBQXabfucX2RfSBscZpw
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 95298ba2-48e7-4272-ad6b-5e23a6c91c73
X-Runtime: 0.006818
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 29</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "completed": true,
  "stats": [

  ]
}</pre>
