# Image API

## Retrieve image secured without fl_attachment

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

<pre>GET /images/c26d70c2-370e-41dc-8352-606e3d3dd8b6?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiIzNzEzM2FlZi00NGE4LTRkYjAtYjM1OS00M2E1YzdlODIxOWUiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiI0YjVmM2ZhMi1hNTU1LTRkN2QtYjE2Mi1lZjkyMzEyODUzNjEiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7ImRvd25sb2FkIjpmYWxzZX19.0DCx2jyvO5ZryihEGy_pbgAcSEFyriC2UDYnz9vWmVQ</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiIzNzEzM2FlZi00NGE4LTRkYjAtYjM1OS00M2E1YzdlODIxOWUiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7IndpZHRoIjoyMDAsIm92ZXJsYXkiOiI0YjVmM2ZhMi1hNTU1LTRkN2QtYjE2Mi1lZjkyMzEyODUzNjEiLCJmbGFncyI6InRpbGVkIiwibWlhaW0iOiJoZXkgaGV5ICEiLCJzdXBlcl9wbG9wIjoidGVzdD8ifSx7IndpZHRoIjoxMDEsImZsYWdzIjoidGlsZWQiLCJoZWlnaHQiOjEwMiwiY3JvcCI6ImZpdCJ9XSwic2hhcmlucGl4Ijp7ImRvd25sb2FkIjpmYWxzZX19.0DCx2jyvO5ZryihEGy_pbgAcSEFyriC2UDYnz9vWmVQ</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Nz8hecyV--/c_fit,h_1920,w_1920/dpr_auto,q_auto,f_auto/fl_tiled,l_authenticated:172982d0c04e,w_200/c_fit,h_102,w_101/v123123/12116b7f533f.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d552e3d5-20e8-4910-bca4-d261669958ac
X-Runtime: 0.010255
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 303</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Nz8hecyV--/c_fit,h_1920,w_1920/dpr_auto,q_auto,f_auto/fl_tiled,l_authenticated:172982d0c04e,w_200/c_fit,h_102,w_101/v123123/12116b7f533f.jpg">redirected</a>.</body></html></pre>
