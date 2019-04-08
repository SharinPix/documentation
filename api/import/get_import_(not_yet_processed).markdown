# Import API

## get import (not yet processed)

### GET /api/v1/imports/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| id | import id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6ImE4ZDA4MDRhLTlhNmMtNGQ3MS05NjViLWI4Zjc0Y2QyNGU1ZCIsImFiaWxpdGllcyI6eyJpbXBvcnRlZF9hbGJ1bSI6eyJBY2Nlc3MiOnsiaW1hZ2VfdXBsb2FkIjp0cnVlfX19fQ.6VaxCy7uKIxS-ZZ8aZk-Mgr_1_Xv98HvwHK0PZo_tuw&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/imports/335187bd-86f2-49a2-80f7-d86f231b7ce1</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6ImE4ZDA4MDRhLTlhNmMtNGQ3MS05NjViLWI4Zjc0Y2QyNGU1ZCIsImFiaWxpdGllcyI6eyJpbXBvcnRlZF9hbGJ1bSI6eyJBY2Nlc3MiOnsiaW1hZ2VfdXBsb2FkIjp0cnVlfX19fQ.6VaxCy7uKIxS-ZZ8aZk-Mgr_1_Xv98HvwHK0PZo_tuw
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e2603e1b-a69b-4ba7-9741-b775019bfd7a
X-Runtime: 0.005987
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 295</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "335187bd-86f2-49a2-80f7-d86f231b7ce1",
  "organization_id": "dd97d290-ddff-4c46-9e28-e4ea0cbb95ea",
  "image_id": null,
  "import_type": "url",
  "album_id": "00100000123BB201",
  "params": {
    "url": "https://exa.com/q"
  },
  "created_at": "2019-04-08T19:38:57.614+02:00",
  "updated_at": "2019-04-08T19:38:57.614+02:00"
}</pre>
