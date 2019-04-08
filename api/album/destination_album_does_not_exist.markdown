# Album API

## destination album does not exist

### PUT /api/v1/albums/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album | Album attributes | false |  |
| merge | Flag for merging album | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImNjYjFkODVhLTlmMjMtNDliNS1iN2E3LTEzOWIxOTg1YjkyMSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMzQiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.ckfQTj7j0OeuDNlgxPM7-R3AyrqhbRAMAJQ7jsDg-aA&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/00100000123BB34</pre>

#### Body

<pre>album[public_id]=inexistent_id&merge=true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImNjYjFkODVhLTlmMjMtNDliNS1iN2E3LTEzOWIxOTg1YjkyMSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMzQiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.ckfQTj7j0OeuDNlgxPM7-R3AyrqhbRAMAJQ7jsDg-aA
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 83b700f6-a22d-46ad-a4ec-0d7fb41ca9b3
X-Runtime: 0.016567
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 175</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "inexistent_id",
  "public_id": "inexistent_id",
  "images_count": 0,
  "views_count": 0,
  "upload_form": null,
  "organization_id": "822a96db-3a55-49ad-9e1f-d9557d60bca4",
  "thumbnails": [

  ]
}</pre>
