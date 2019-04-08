# Publication API

## Create a publication

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjI2NjZhODhiLWMzN2ItNDY2Ny1hZTMxLWI5MjIxNTJiMGVmOCJ9.On77oJVhqm8kzvSJQwpSYNp8o3CuZZkl6rDVhnj--qg&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB245/publications</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjI2NjZhODhiLWMzN2ItNDY2Ny1hZTMxLWI5MjIxNTJiMGVmOCJ9.On77oJVhqm8kzvSJQwpSYNp8o3CuZZkl6rDVhnj--qg
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: faa73957-f944-4045-90dd-411e40cf3ae2
X-Runtime: 0.018503
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 323</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "public_id": "c663a187-1e66-4cbb-8782-e4a3eb49e766",
  "thumbnail": "https://localhost:5001/publications/c663a187-1e66-4cbb-8782-e4a3eb49e766/thumbnail",
  "title": "Album published on 2019-04-08",
  "description": "0 photos available\nPowered by SharinPix",
  "aux_text": "shared an album:",
  "entity_id": "",
  "views_count": 0,
  "opens_count": 0
}</pre>
