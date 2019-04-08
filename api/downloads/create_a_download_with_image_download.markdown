# Downloads API

## Create a download with image_download

### POST /api/v1/downloads

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_ids | A list of image public_ids to be added in the zip. | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyX2lkIjoiNTRkMzdhODMtMDQxZC00YWIwLWJjOTYtNzE2MmYzYzU3ZmM4IiwiYWJpbGl0aWVzIjp7IjAwMTAwMDAwMTIzQkI2NiI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZX19fSwiZG93bmxvYWQiOnRydWUsImlzcyI6Ijk3ZWZkMTE5LTU0NzAtNDIwMi05YjQyLTU2NzI3ZWU2NjgyMiJ9.Msem0FCLGFckNdjrz35LWwyNOgHAsFbvKcMtJ38A3VM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/downloads</pre>

#### Body

<pre>image_ids[]=4a911b9d-2650-4b67-87b2-d9f8850839f7&image_ids[]=b79bd7d7-b620-45b1-b892-ceeb72e41643&image_ids[]=6401ee88-f189-44f7-87e1-ada46ab0348e&image_ids[]=f0195ce4-4b8d-472e-a333-c9bc2674233c&image_ids[]=68a7fd8a-bf47-4fc6-8a51-e30642f33afe</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwidXNlcl9pZCI6IjU0ZDM3YTgzLTA0MWQtNGFiMC1iYzk2LTcxNjJmM2M1N2ZjOCIsImlzcyI6Ijk3ZWZkMTE5LTU0NzAtNDIwMi05YjQyLTU2NzI3ZWU2NjgyMiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCNjYiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sImRvd25sb2FkIjp0cnVlfQ.80OD6FQtYedIlBfSfy3PL3eizElpJfhor8i4aJu8aG0
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: c3fe257d-8647-4aa9-96c0-4dea86edb679
X-Runtime: 0.027842
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 246</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "6a9c3fd5-dc41-4ac1-a8f1-5f6b80a6359f",
  "zip_url": "https://zipper-dev.herokuapp.com:443/0/https%3A%2F%2Flocalhost%3A5001%2Fapi%2Fv1%2Fdownloads%2F6a9c3fd5%2Ddc41%2D4ac1%2Da8f1%2D5f6b80a6359f%2Fzip%3Ftimestamp%3D1554674400/4ea695964/zip.zip"
}</pre>
