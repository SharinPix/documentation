# Image Public External Url API

## Redirect to image_external_url

### GET /image_external_urls/:id
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET /image_external_urls/713dc663-7e10-49aa-b196-2f23530a70b7</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OiEsztz7--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c56b0e38c663.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 5ef03a15-9616-46d4-bd65-c136d8e160ac
X-Runtime: 0.009634
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 255</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OiEsztz7--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c56b0e38c663.jpg">redirected</a>.</body></html></pre>
