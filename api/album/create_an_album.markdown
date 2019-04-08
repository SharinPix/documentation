# Album API

## Create an album

### POST /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwidXNlcl9pZCI6ImNjN2M3NzI4LWEwNmEtNDA4ZC1hZTg1LTJlY2U0N2Y1NWFmYyIsImFiaWxpdGllcyI6e319.cDW77NYfFOZEvHSr494KLf_-i9mfwyjAwy-hAVLzqQ0&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwidXNlcl9pZCI6ImNjN2M3NzI4LWEwNmEtNDA4ZC1hZTg1LTJlY2U0N2Y1NWFmYyIsImFiaWxpdGllcyI6e319.cDW77NYfFOZEvHSr494KLf_-i9mfwyjAwy-hAVLzqQ0
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: df7ca246-b231-4856-b424-982d146db92a
X-Runtime: 0.021104
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 1096</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "11824a8d-aed2-4a20-92a4-6c94f003a9f3",
  "public_id": "11824a8d-aed2-4a20-92a4-6c94f003a9f3",
  "images_count": 0,
  "views_count": 0,
  "upload_form": {
    "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
    "expires_at": 1555349928,
    "name": "11824a8d-aed2-4a20-92a4-6c94f003a9f3",
    "id": "d0875f7e-ba4d-4cec-9f22-2990acba8d1d-11824a8d-aed2-4a20-92a4-6c94f003a9f3",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwidXNlcl9pZCI6ImNjN2M3NzI4LWEwNmEtNDA4ZC1hZTg1LTJlY2U0N2Y1NWFmYyIsImFsYnVtX2lkIjoiMTE4MjRhOGQtYWVkMi00YTIwLTkyYTQtNmM5NGYwMDNhOWYzIiwib3JnYW5pemF0aW9uX2lkIjoiZDA4NzVmN2UtYmE0ZC00Y2VjLTlmMjItMjk5MGFjYmE4ZDFkIn0.-T90_QQ2_8-_A6ylVZUgvohul48AgicDYlu2zrph6H8",
      "phash": 1,
      "tags": "11824a8d-aed2-4a20-92a4-6c94f003a9f3",
      "timestamp": 1555349928,
      "type": "authenticated",
      "signature": "7a02e4f9f21ab22c868dcf9c679da68c463ce9c9",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "d0875f7e-ba4d-4cec-9f22-2990acba8d1d",
  "thumbnails": [

  ]
}</pre>
