# Image API

## Retrieve image secured with private overlay

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

<pre>GET /images/161400d0-c894-42fd-8100-262361ea91ff?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJjZmQzYjQ3Mi1kYmJhLTQwODktYmNlNy1mNWMxZTQxM2I1YzEiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiIzZDYxNmI0ZS1hNTk3LTRiMjMtYWEzZC1kN2RlNjc4ZjBiYTYiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7fX0.aCiLVC0isvH-EOgN3ctHI3J2cqYi07Rgb7OxEVlxON4</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJjZmQzYjQ3Mi1kYmJhLTQwODktYmNlNy1mNWMxZTQxM2I1YzEiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiIzZDYxNmI0ZS1hNTk3LTRiMjMtYWEzZC1kN2RlNjc4ZjBiYTYiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7fX0.aCiLVC0isvH-EOgN3ctHI3J2cqYi07Rgb7OxEVlxON4</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--sx5QdeQ8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/fl_tiled,l_private:d47e609177b4,w_200/c_fit,h_102,w_101/v123123/ba5a440dbe3d.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 930db68b-b413-46f8-a697-a5851bcb80e5
X-Runtime: 0.010672
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 311</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--sx5QdeQ8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/fl_tiled,l_private:d47e609177b4,w_200/c_fit,h_102,w_101/v123123/ba5a440dbe3d.jpg">redirected</a>.</body></html></pre>
