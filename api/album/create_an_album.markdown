# Album API

## Create an album

### POST /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5YTBiNmUwZi1mOGIxLTQ3ZjktOTU5Mi1jOTdlMDI0Zjg3ZmIifQ.Rhwhqa4DZnKKrSYsAWgeGBoammRyxLQMRIfUiOcXpBM&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5YTBiNmUwZi1mOGIxLTQ3ZjktOTU5Mi1jOTdlMDI0Zjg3ZmIifQ.Rhwhqa4DZnKKrSYsAWgeGBoammRyxLQMRIfUiOcXpBM
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 6e25f424-8e5b-467d-9e57-0f73c3e65849
X-Runtime: 0.049003
Content-Length: 437</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"1877d36e-ded5-4282-873f-4b21cb8e2184","upload_form":{"url":"https://api.cloudinary.com/v1_1/hwja6b0dx/auto/upload","params":{"timestamp":1452607519,"transformation":"a_exif","callback":"https://localhost/cloudinary_cors.html","type":"private","tags":"1877d36e-ded5-4282-873f-4b21cb8e2184","signature":"f0a80c739f160e6a5d41d1967b250982737f8772","api_key":"744524991939777"}},"images_count":0,"views_count":0,"thumbnails":[]}</pre>
