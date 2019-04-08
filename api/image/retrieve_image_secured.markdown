# Image API

## Retrieve image secured

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

<pre>GET /images/b3d4dc82-0ec9-486e-b7fd-db4a88106bf9?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiIyMDk3M2Q2YS02NGYxLTRlOWUtYmQ1NC00ZjBlYTcxOWUxYWIiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiIyNjBhMmMyNy02OWViLTQ3NWItYTFhNi1mZmZlMzQyZmE0NWEiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7fX0.DQRSvs8Y35Rg8r-lX6Z4_9bPBCDF3uyMsb_rzkYhTy0</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiIyMDk3M2Q2YS02NGYxLTRlOWUtYmQ1NC00ZjBlYTcxOWUxYWIiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiIyNjBhMmMyNy02OWViLTQ3NWItYTFhNi1mZmZlMzQyZmE0NWEiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7fX0.DQRSvs8Y35Rg8r-lX6Z4_9bPBCDF3uyMsb_rzkYhTy0</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RNtvEwsL--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/fl_tiled,l_authenticated:6e38507e19c5,w_200/c_fit,h_102,w_101/v123123/2ced53451a65.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ffa34857-4e25-4eb6-b077-f6d40bf1afbd
X-Runtime: 0.011191
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 317</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RNtvEwsL--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/fl_tiled,l_authenticated:6e38507e19c5,w_200/c_fit,h_102,w_101/v123123/2ced53451a65.jpg">redirected</a>.</body></html></pre>
