# Trashed images API

## Retrieve all deleted images

### GET api/v1/trashed_images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6ImIwZTkzNzJjLThkYTEtNDI5Mi05MWQyLTdmNzU3Mzg3YTM5YiJ9.pE5gvQ0nkWwPL6ciCWiCrzg8ZVE4NHQOFigm1LPDO-Y&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/trashed_images</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6ImIwZTkzNzJjLThkYTEtNDI5Mi05MWQyLTdmNzU3Mzg3YTM5YiJ9.4cADzTv5lmY-l7WaKbdm3l0c3ilDfzDoDjVHDM3vL9w
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 3be8df81-4a3a-446e-a481-f9c94d402525
X-Runtime: 0.010036
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 601</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "4fd3e95c-330b-4ccb-b7fb-532dd13b8be1",
    "deleted_at": "2019-04-08T19:38:57.002+02:00",
    "thumbnail_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RQ1PclAc--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/76ba23fb6aed.jpg"
  },
  {
    "id": "b2bfb91a-c9f6-48d7-a7f4-2fec4d242424",
    "deleted_at": "2019-04-08T19:38:56.998+02:00",
    "thumbnail_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3joVur64--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7d737e232ace.jpg"
  }
]</pre>
