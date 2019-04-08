# Image API

## Retrieve image with angle parameter

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

<pre>GET /images/da1f44e3-d5ac-4ef5-b072-a92a678af67d?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJmZTNjZTViMC1hNGQwLTQ2NjMtYjIxMy0yN2E1OTFkOWI3ODYiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7Im92ZXJsYXkiOiJ0ZXh0OnNhbXBsZV90ZXh0X3N0eWxlOlN0eWxpc2glMjB0ZXh0IiwiZ3Jhdml0eSI6InNvdXRoIn1dfQ.mPa8MBkoHF-T1CfJWeQks1qIchVDLdFCB4A2NYCfD5Y</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJmZTNjZTViMC1hNGQwLTQ2NjMtYjIxMy0yN2E1OTFkOWI3ODYiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7Im92ZXJsYXkiOiJ0ZXh0OnNhbXBsZV90ZXh0X3N0eWxlOlN0eWxpc2glMjB0ZXh0IiwiZ3Jhdml0eSI6InNvdXRoIn1dfQ.mPa8MBkoHF-T1CfJWeQks1qIchVDLdFCB4A2NYCfD5Y</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--h_AMdblx--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/g_south,l_text:sample_text_style:Stylish%20text/v123123/df64184709b9.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 481e6658-3bd2-46dd-aa01-2945bd861176
X-Runtime: 0.008669
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 303</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--h_AMdblx--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/g_south,l_text:sample_text_style:Stylish%20text/v123123/df64184709b9.jpg">redirected</a>.</body></html></pre>
