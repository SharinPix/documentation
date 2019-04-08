# Image API API

## Retrieve an image embed code

### GET /api/v1/images/:id/embed
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6Ijg3YzFjOTQ0LWFlMWEtNDUwNy1iNzVjLTkwM2M2NWIwYjZjOCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTM0Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.wRFnuJCM5LcKNH0NgL_5_8tLxA7iQ5QuYNtCBvh6k8I&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/8c47b718-83c3-4670-b3bd-e73e86a7f1e3/embed</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6Ijg3YzFjOTQ0LWFlMWEtNDUwNy1iNzVjLTkwM2M2NWIwYjZjOCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTM0Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.wRFnuJCM5LcKNH0NgL_5_8tLxA7iQ5QuYNtCBvh6k8I
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 81c3d5d2-8e82-4cad-87bd-b80606f81654
X-Runtime: 0.012023
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 940</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "html": "<video autoplay=\"autoplay\" controls=\"controls\" poster=\"https://res.cloudinary.com/sadaasdasd/video/authenticated/s--zABEla6c--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.jpg\"><source src=\"https://res.cloudinary.com/sadaasdasd/video/authenticated/s--L9ofyCpV--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.webm\" type=\"video/webm\" /><source src=\"https://res.cloudinary.com/sadaasdasd/video/authenticated/s--m7UW5Xo9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.mp4\" type=\"video/mp4\" /><source src=\"https://res.cloudinary.com/sadaasdasd/video/authenticated/s--_-Y-uawl--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.ogv\" type=\"video/ogg\" /></video>"
}</pre>
