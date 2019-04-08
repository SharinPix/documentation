# Album API

## Rename an album

### PUT /api/v1/albums/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album | Album attributes | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6IjE3NjMwM2Y0LTlmZDMtNGUwOS04Y2NkLWI2OTI4MjAzNzg1MSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjMiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.HYeqyJBvFpRV1fk9GOykioPt1wdQAd3Qy--_-14p3dc&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/00100000123BB23</pre>

#### Body

<pre>album[public_id]=new_id</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6IjE3NjMwM2Y0LTlmZDMtNGUwOS04Y2NkLWI2OTI4MjAzNzg1MSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjMiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.HYeqyJBvFpRV1fk9GOykioPt1wdQAd3Qy--_-14p3dc
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 7710c5fc-03e9-4572-aa9f-ea7c5a16ac0d
X-Runtime: 0.030476
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 161</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "new_id",
  "public_id": "new_id",
  "images_count": 0,
  "views_count": 0,
  "upload_form": null,
  "organization_id": "00c51633-216e-4435-8a51-eef1b108b10c",
  "thumbnails": [

  ]
}</pre>
