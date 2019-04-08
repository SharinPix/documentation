# Image API

## Return the image transformed

### GET /images/:image_id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| width | Width of image. | false |  |
| height | Height of image. | false |  |
| crop | Crop function (fill, fit, scale, pad) of the image. | false |  |

### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET /images/64171752-36dd-42aa-b3d3-d769a410b6bb?width=201&amp;height=202&amp;crop=fit</pre>

#### Query Parameters

<pre>width: 201
height: 202
crop: fit</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mnPq_Igx--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_202,w_201/v123123/deeb63e7d71e.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ba4108f9-f503-48d0-9e13-571ae0b632bb
X-Runtime: 0.006617
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 273</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mnPq_Igx--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_202,w_201/v123123/deeb63e7d71e.jpg">redirected</a>.</body></html></pre>
