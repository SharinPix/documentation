# Image API

## Response has header Access-Control-Allow-Origin

### GET /images/:image_id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| token | Token to secure the transformation | false |  |

### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET /images/58c524f2-5b14-4ae3-ab4f-a5e1b05f90eb?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJkODg5MTAxMS03MTJlLTRlZWItOTVjNC02YzcyYTMyNmEzNjMiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiI4MTQ5OWQyMy1jNzY1LTQxNGUtOGFjMS01OWY5OTY1NGNiZDUiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7fX0.cMuVKXCuQXmhVYRBLdE-IB7bKIl5x9KD4s4jr01IVD0</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJkODg5MTAxMS03MTJlLTRlZWItOTVjNC02YzcyYTMyNmEzNjMiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiI4MTQ5OWQyMy1jNzY1LTQxNGUtOGFjMS01OWY5OTY1NGNiZDUiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7fX0.cMuVKXCuQXmhVYRBLdE-IB7bKIl5x9KD4s4jr01IVD0</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--M_1TgkGm--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/fl_tiled,l_authenticated:085494a9a403,w_200/c_fit,h_102,w_101/v123123/dffc0901833e.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4225c3f3-1282-444e-acfb-b8a8d969fbee
X-Runtime: 0.010328
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 317</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--M_1TgkGm--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/fl_tiled,l_authenticated:085494a9a403,w_200/c_fit,h_102,w_101/v123123/dffc0901833e.jpg">redirected</a>.</body></html></pre>
