# Image Url API

## Retrieve an url for the image

### GET /api/v1/images/:image_id/image_url
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjMsImlhdCI6MTU1NDc0NTEyMywidXNlcl9pZCI6ImUwMTI4NWJmLTZlMGItNDkxYS04MDQ5LWE2OGE1YmQ4YjcxNiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMSI6eyJBY2Nlc3MiOnsiaW1hZ2VfdHJhbnNmb3JtIjp0cnVlfX19fQ.lpu--X9rSHgG3jKoMthOOyyz39bxPAh_LhyA3l1Gc_A&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/a71d1cd9-7feb-4751-aae9-55f7d925af6e/image_url</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjMsImlhdCI6MTU1NDc0NTEyMywidXNlcl9pZCI6ImUwMTI4NWJmLTZlMGItNDkxYS04MDQ5LWE2OGE1YmQ4YjcxNiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMSI6eyJBY2Nlc3MiOnsiaW1hZ2VfdHJhbnNmb3JtIjp0cnVlfX19fQ.lpu--X9rSHgG3jKoMthOOyyz39bxPAh_LhyA3l1Gc_A
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ab4965b4-f029-48e3-b314-1b7e44e56ce9
X-Runtime: 0.046535
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 231</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xRP1wYBz--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/901937c0e4de.jpg",
  "image_id": "a71d1cd9-7feb-4751-aae9-55f7d925af6e"
}</pre>
