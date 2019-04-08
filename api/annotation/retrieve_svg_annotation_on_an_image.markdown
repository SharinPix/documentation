# Annotation API

## Retrieve svg annotation on an image

### GET /api/v1/images/:image_id/annotation
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjQsImlhdCI6MTU1NDc0NTEyNCwidXNlcl9pZCI6ImYxY2M1Y2E0LTk3ZDgtNDNmNi1iMDUzLTA4YjJmNDRkYWIxYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCNyI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZX19fX0.w4AlF3vg9moFCDbykXqvXKdWJBMm_r17_M8k8un19e8&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/49cc5014-e223-4f7a-a8d5-ebbd969af4eb/annotation</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjQsImlhdCI6MTU1NDc0NTEyNCwidXNlcl9pZCI6ImYxY2M1Y2E0LTk3ZDgtNDNmNi1iMDUzLTA4YjJmNDRkYWIxYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCNyI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZX19fX0.w4AlF3vg9moFCDbykXqvXKdWJBMm_r17_M8k8un19e8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d9c15858-2478-4c36-a7a5-6c0941902859
X-Runtime: 0.012183
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 26</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "svg": null,
  "object": null
}</pre>
