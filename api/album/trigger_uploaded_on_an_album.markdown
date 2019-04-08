# Album API

## Trigger uploaded on an album

### POST /api/v1/albums/:id/upload_done
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImJjYTVlYTEwLTZlMDYtNDZiYi1hMTYwLWQ1ZmI2NjlhMjc3NCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjUiOnsiQWNjZXNzIjp7ImltYWdlX3VwbG9hZCI6dHJ1ZX19fX0.guKk5l1ISUrpcWz2Q4VI4RDBqgP8oJ6TukHMmE1X9IM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB25/upload_done</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImJjYTVlYTEwLTZlMDYtNDZiYi1hMTYwLWQ1ZmI2NjlhMjc3NCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjUiOnsiQWNjZXNzIjp7ImltYWdlX3VwbG9hZCI6dHJ1ZX19fX0.guKk5l1ISUrpcWz2Q4VI4RDBqgP8oJ6TukHMmE1X9IM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 56d3bf60-90bf-4436-bb4d-fc77b589cb26
X-Runtime: 0.026387
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 963</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "00100000123BB25",
  "public_id": "00100000123BB25",
  "images_count": 0,
  "views_count": 0,
  "upload_form": {
    "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
    "expires_at": 1555349925,
    "name": "00100000123BB25",
    "id": "232678ca-60c7-4bae-a9b2-88e55d4aecdc-00100000123BB25",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImJjYTVlYTEwLTZlMDYtNDZiYi1hMTYwLWQ1ZmI2NjlhMjc3NCIsImFsYnVtX2lkIjoiMDAxMDAwMDAxMjNCQjI1Iiwib3JnYW5pemF0aW9uX2lkIjoiMjMyNjc4Y2EtNjBjNy00YmFlLWE5YjItODhlNTVkNGFlY2RjIn0.A9v0CAMAVWPMUIc1Vfoye2F-oRxuFQvpUISjvoQgc60",
      "phash": 1,
      "tags": "00100000123BB25",
      "timestamp": 1555349925,
      "type": "authenticated",
      "signature": "be2e6ad309dfd26b130e6d92e472e498114b752c",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "232678ca-60c7-4bae-a9b2-88e55d4aecdc",
  "thumbnails": [

  ]
}</pre>
