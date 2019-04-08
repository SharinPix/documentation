# Publication API

## Create a publication with text from salesforce1

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjEyYTM3N2YyLTA2NDUtNDM3MC05ZmRkLTExYjJhNGI2Njc4YSJ9.yRrICAY7UmdsKq1bM-uG_kJf6kxLdOoTMYoru-fpHF8&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB248/publications</pre>

#### Body

<pre>infos[messageSegments][][type]=text&infos[messageSegments][][text]=Can+you+all+join+me+to+congratulate&infos[messageSegments][][type]=mention&infos[messageSegments][][id]=00524000000FzDkAAK&infos[messageSegments][][type]=text&infos[messageSegments][][text]=+and+all+his+team+on+this+one.</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjEyYTM3N2YyLTA2NDUtNDM3MC05ZmRkLTExYjJhNGI2Njc4YSJ9.yRrICAY7UmdsKq1bM-uG_kJf6kxLdOoTMYoru-fpHF8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: a327271a-a453-4a43-b558-56c2bfd5f036
X-Runtime: 0.018420
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
  "public_id": "6224f31a-9c2b-4a19-87c4-677f020a294c",
  "thumbnail": "https://localhost:5001/publications/6224f31a-9c2b-4a19-87c4-677f020a294c/thumbnail",
  "title": "Album published on 2019-04-08",
  "description": "0 photos available\nPowered by SharinPix",
  "aux_text": "",
  "entity_id": "",
  "views_count": 0,
  "opens_count": 0
}</pre>
