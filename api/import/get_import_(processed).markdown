# Import API

## get import (processed)

### GET /api/v1/imports/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| id | import id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6Ijk0NWFiOTFmLWFlNzUtNDk2My05YjY4LTE2MjE2YjhmNDkxNyIsImFiaWxpdGllcyI6eyJpbXBvcnRlZF9hbGJ1bSI6eyJBY2Nlc3MiOnsiaW1hZ2VfdXBsb2FkIjp0cnVlfX19fQ.gAaiG0fq1dBC_X0tlSN6UG80j0j1A3Zju5YZkrAVkaY&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/imports/1e908c13-c77e-43b2-b471-b474c2e00a78</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6Ijk0NWFiOTFmLWFlNzUtNDk2My05YjY4LTE2MjE2YjhmNDkxNyIsImFiaWxpdGllcyI6eyJpbXBvcnRlZF9hbGJ1bSI6eyJBY2Nlc3MiOnsiaW1hZ2VfdXBsb2FkIjp0cnVlfX19fQ.gAaiG0fq1dBC_X0tlSN6UG80j0j1A3Zju5YZkrAVkaY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: dce230ba-46c4-46c2-89db-bad374dc2dd9
X-Runtime: 0.013290
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 329</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "1e908c13-c77e-43b2-b471-b474c2e00a78",
  "organization_id": "e229b632-2492-49f5-b15e-d5bfd4422c9b",
  "image_id": "15b19abc-7d1b-4c9d-ad98-6d12d8ee4078",
  "import_type": "url",
  "album_id": "00100000123BB199",
  "params": {
    "url": "https://exa.com/q"
  },
  "created_at": "2019-04-08T19:38:57.548+02:00",
  "updated_at": "2019-04-08T19:38:57.560+02:00"
}</pre>
