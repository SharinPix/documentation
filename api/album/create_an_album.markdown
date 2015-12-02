# Album API

## Create an album

### POST /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlZDA1MWFkNS1lYmIxLTQ4ODctOTZlOC1mMmRjZDU3NjY4NTQifQ.ISK-xgnAhKG0PFJcjtau8TBAdlUy6kz1mVljA88Si7I&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlZDA1MWFkNS1lYmIxLTQ4ODctOTZlOC1mMmRjZDU3NjY4NTQifQ.ISK-xgnAhKG0PFJcjtau8TBAdlUy6kz1mVljA88Si7I
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;57fd1edc17a7b98f2a6b9adf8dd803f6&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 55d367e0-8c23-47ce-b299-5c8659af7824
X-Runtime: 0.099833
Content-Length: 437</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"8a523aa6-6de5-4b6c-97bf-04e446e9541b","upload_form":{"url":"https://api.cloudinary.com/v1_1/hwja6b0dx/auto/upload","params":{"timestamp":1449051274,"transformation":"a_exif","callback":"https://localhost/cloudinary_cors.html","type":"private","tags":"8a523aa6-6de5-4b6c-97bf-04e446e9541b","signature":"eeb0778948fe326c2924a5d43865cd83e52363d3","api_key":"744524991939777"}},"images_count":0,"views_count":0,"thumbnails":[]}</pre>
