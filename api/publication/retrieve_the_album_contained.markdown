# Publication API

## Retrieve the album contained

### GET /api/v1/publications/:publication_id/album
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjkwMWVlMzFlLTYzYjUtNDUxMy05ZGFmLWU1Y2FlODVmNGU3OSJ9.DlIam-tsQfM8tqvHZb2HfwqpxurbXOn9T4yj5lnR2c4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/publications/e0380999-bfca-4aee-90d9-065e2297d7cf/album</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-access-image_delete: true
X-access-image_upload: true
X-access-image_share: false
X-access-image_rotate: true
X-access-image_crop: true
X-access-stats: true
X-access-image_copy: false
X-access-paste: false
X-access-share: false
X-access-image_duplicate: false
X-access-create_tag: false
X-access-image_download: true
X-access-image_annotate: false
X-access-fullscreen: 
X-access-einstein_box: 
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjkwMWVlMzFlLTYzYjUtNDUxMy05ZGFmLWU1Y2FlODVmNGU3OSJ9.DlIam-tsQfM8tqvHZb2HfwqpxurbXOn9T4yj5lnR2c4
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8d5e01ce-22ae-4f93-8fef-f46b6e2e397f
X-Runtime: 0.052451
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 969</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "00100000123BB253",
  "public_id": "00100000123BB253",
  "images_count": 0,
  "views_count": 0,
  "upload_form": {
    "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
    "expires_at": 1555349943,
    "name": "00100000123BB253",
    "id": "78494409-c657-41c9-8c7e-843080388477-00100000123BB253",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjkwMWVlMzFlLTYzYjUtNDUxMy05ZGFmLWU1Y2FlODVmNGU3OSIsImFsYnVtX2lkIjoiMDAxMDAwMDAxMjNCQjI1MyIsIm9yZ2FuaXphdGlvbl9pZCI6Ijc4NDk0NDA5LWM2NTctNDFjOS04YzdlLTg0MzA4MDM4ODQ3NyJ9.EgkqZcAeHDtm_Bsab9ukRjO-uy6RBOB3enh543dPtPU",
      "phash": 1,
      "tags": "00100000123BB253",
      "timestamp": 1555349943,
      "type": "authenticated",
      "signature": "3537a7fd95b65d00696e18f72fe388aae83014dc",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "78494409-c657-41c9-8c7e-843080388477",
  "thumbnails": [

  ]
}</pre>
