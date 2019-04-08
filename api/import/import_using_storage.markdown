# Import API

## import using storage

### POST /api/v1/imports

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album_id | Album name | false |  |
| filename | Image filename | false |  |
| metadatas | Image metadata | false |  |
| url | Url of the image to import | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzgsImlhdCI6MTU1NDc0NTEzOCwiaXNzIjoiMzgwMGJlMjktYjVkMy00MDY0LWFkNzAtZGY5ZDNiY2NiODRmIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.npf99AlomSl1KAVESYkHdRdEg1-2LxCZVt4OT9i3aV8&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/imports</pre>

#### Body

<pre>album_id=imported_album&filename=image123_asdasd.JpG&metadatas[attachmentId]=00P24000003vSXsEAM&url=http%3A%2F%2Florempixel.com%2F100%2F100%2F</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzgsImlhdCI6MTU1NDc0NTEzOCwiaXNzIjoiMzgwMGJlMjktYjVkMy00MDY0LWFkNzAtZGY5ZDNiY2NiODRmIiwic3RvcmFnZSI6ImFtYXppbmctc3RvcmFnZSIsImFiaWxpdGllcyI6eyJzdG9yYWdlIjoiYW1hemluZy1zdG9yYWdlIiwiaW1wb3J0ZWRfYWxidW0iOnsic3RvcmFnZSI6ImFtYXppbmctc3RvcmFnZSIsIkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.QiMKgCiCAvQJ2fQNOlovhHB4fM1NCPPaG4RKwNqL9uQ
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 36735d0d-5090-4d6a-9745-7c93b5c988a8
X-Runtime: 0.094339
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 464</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "27381a7b-fd61-4577-b004-67372057299d",
  "organization_id": "6a270d78-5659-464e-9905-6daa7b29e911",
  "image_id": null,
  "import_type": null,
  "album_id": "imported_album",
  "params": {
    "album_id": "imported_album",
    "filename": "image123_asdasd.JpG",
    "metadatas": {
      "attachmentId": "00P24000003vSXsEAM"
    },
    "url": "http://lorempixel.com/100/100/",
    "controller": "api/v1/imports",
    "action": "create"
  },
  "created_at": "2019-04-08T19:38:58.402+02:00",
  "updated_at": "2019-04-08T19:38:58.402+02:00"
}</pre>
