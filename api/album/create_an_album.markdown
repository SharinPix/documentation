# Album API

## Create an album

### POST /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5ZGRkMjg3NC01MzM1LTQwZGUtOTI0OS02ZmY4NWZkYjc3OGQifQ.fcsn8dMRIqI5TIfNMCWgq7UN17hGF1aM_kmQqZBEj6o&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5ZGRkMjg3NC01MzM1LTQwZGUtOTI0OS02ZmY4NWZkYjc3OGQifQ.fcsn8dMRIqI5TIfNMCWgq7UN17hGF1aM_kmQqZBEj6o
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 39f0f00e-976d-4a33-90e0-21811f0768b2
X-Runtime: 0.074847
Content-Length: 388</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"ef4dc96c-0bd9-44dd-8c02-53c7825060a4","upload_form":{"url":"https://api-de.cloudinary.com/v1_1/hwja6b0dx/auto/upload","params":{"timestamp":1455537777,"transformation":"a_exif","type":"private","tags":"ef4dc96c-0bd9-44dd-8c02-53c7825060a4","signature":"455152e98b884cf0197db0baddd159c50955dcb6","api_key":"744524991939777"}},"images_count":0,"views_count":0,"thumbnails":[]}</pre>
