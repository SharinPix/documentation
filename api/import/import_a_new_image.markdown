# Import API

## Import a new image

### POST /api/v1/imports

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album_id | Album name | false |  |
| filename | Image filename | false |  |
| metadata | Image metadata | false |  |
| url | Url of the image to import | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiZmEzNTViNWUtZDFlNC00MTU1LWFkZmEtMGIwMGRlNTA2MjlkIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.BeY4JS1l5kegBlcCgCvUzWKZ72Y488Lt05eS8AKSXnY&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/imports</pre>

#### Body

<pre>album_id=imported_album&filename=image123_asdasd.JpG&metadata[attachmentId]=00P24000003vSXsEAM&url=http%3A%2F%2Florempixel.com%2F100%2F100%2F</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiZmEzNTViNWUtZDFlNC00MTU1LWFkZmEtMGIwMGRlNTA2MjlkIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.BeY4JS1l5kegBlcCgCvUzWKZ72Y488Lt05eS8AKSXnY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: a44d1eee-08a2-4de8-ac8b-425299e6e83f
X-Runtime: 0.014255
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 463</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "f60ae96b-2681-4885-8437-356e9fae9f6e",
  "organization_id": "194c51fb-fef1-4bdf-ab27-fed1b67cf6f1",
  "image_id": null,
  "import_type": null,
  "album_id": "imported_album",
  "params": {
    "album_id": "imported_album",
    "filename": "image123_asdasd.JpG",
    "metadata": {
      "attachmentId": "00P24000003vSXsEAM"
    },
    "url": "http://lorempixel.com/100/100/",
    "controller": "api/v1/imports",
    "action": "create"
  },
  "created_at": "2019-04-08T19:38:57.714+02:00",
  "updated_at": "2019-04-08T19:38:57.714+02:00"
}</pre>
