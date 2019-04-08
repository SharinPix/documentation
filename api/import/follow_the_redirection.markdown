# Import API

## follow the redirection

### POST /api/v1/imports

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album_id | Album name | false |  |
| filename | Image filename | false |  |
| metadata | Image metadata | false |  |
| url | Url of the image to import | false |  |
| headers | The headers to use to when making the get request | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiMGZjMmFhZTctMzZlNi00NzgxLWIwZDktOTc3OGQxMWI0MGRlIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.EEPhtY0Ectmul56PGVJfJjEOuSlRtl5qZVkyBZCmunA&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/imports</pre>

#### Body

<pre>album_id=imported_album&filename=image123_asdasd.JpG&metadata[attachmentId]=00P24000003vSXsEAM&url=http%3A%2F%2Florempixel.com%2F100%2F100%2F&headers[Authorization]=Token+token%3D%22eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiMGZjMmFhZTctMzZlNi00NzgxLWIwZDktOTc3OGQxMWI0MGRlIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.EEPhtY0Ectmul56PGVJfJjEOuSlRtl5qZVkyBZCmunA%22</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiMGZjMmFhZTctMzZlNi00NzgxLWIwZDktOTc3OGQxMWI0MGRlIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.EEPhtY0Ectmul56PGVJfJjEOuSlRtl5qZVkyBZCmunA
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 3ac57e29-1dfd-44b9-b9e8-d2f7a33158d6
X-Runtime: 0.016304
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 783</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "4c77bb52-1caf-47ce-a73a-3bad2d6ccd6c",
  "organization_id": "04432836-ea1f-426d-a98d-1334d68e56ed",
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
    "headers": {
      "Authorization": "Token token=\"eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiMGZjMmFhZTctMzZlNi00NzgxLWIwZDktOTc3OGQxMWI0MGRlIiwiYWJpbGl0aWVzIjp7ImltcG9ydGVkX2FsYnVtIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.EEPhtY0Ectmul56PGVJfJjEOuSlRtl5qZVkyBZCmunA\""
    },
    "controller": "api/v1/imports",
    "action": "create"
  },
  "created_at": "2019-04-08T19:38:57.430+02:00",
  "updated_at": "2019-04-08T19:38:57.430+02:00"
}</pre>
