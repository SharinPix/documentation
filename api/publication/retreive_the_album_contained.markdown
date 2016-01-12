# Publication API

## Retreive the album contained

### GET /api/v1/publications/:publication_id/album
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIxZjQzMzgzMC0xN2Q5LTQyOTMtOGZlZi00MGMzYzNlMmU3MWYifQ.AgjbWhpBriwFqlF8wKWzYUKvT6No45V3Xsfcnw_JWdI&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/publications/ae26b8a7-e460-44ce-86f0-089a34beff45/album</pre>

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
X-access-image_delete: true
X-access-image_upload: true
X-access-image_share: false
X-access-image_rotate: true
X-access-image_crop: true
X-access-stats: true
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIxZjQzMzgzMC0xN2Q5LTQyOTMtOGZlZi00MGMzYzNlMmU3MWYifQ.AgjbWhpBriwFqlF8wKWzYUKvT6No45V3Xsfcnw_JWdI
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: b3e7f7e8-362c-4e54-9762-45af5c6ea9aa
X-Runtime: 0.078037
Content-Length: 437</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"cac1b8d8-1b93-4ea0-b271-a5f08f754160","upload_form":{"url":"https://api.cloudinary.com/v1_1/hwja6b0dx/auto/upload","params":{"timestamp":1452607514,"transformation":"a_exif","callback":"https://localhost/cloudinary_cors.html","type":"private","tags":"cac1b8d8-1b93-4ea0-b271-a5f08f754160","signature":"e9ed25810046b59986bf79b5cb3a9ed72d35d17c","api_key":"744524991939777"}},"images_count":0,"views_count":0,"thumbnails":[]}</pre>
