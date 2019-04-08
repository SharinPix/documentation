# Image API

## Take image_id in token

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

<pre>GET /images/22d62e99-aff9-4c20-90c7-bcfd737a0081?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI4NTNmNTZiNS0yNGMzLTQxZDEtYmRkNC01Nzc0MWRhZDYzYjkiLCJpbWFnZV9pZCI6IjZhZjk4YWYyLTMwNzctNGY1Yy05ZjgwLTEyZDdjYjI5YmZjNiIsInRyYW5zZm9ybWF0aW9ucyI6W3siYW5nbGUiOjkwfV19.NWF9l5Uit3XuM_QIJvryovH8RM-j3eIDpYnbUijDIzM</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI4NTNmNTZiNS0yNGMzLTQxZDEtYmRkNC01Nzc0MWRhZDYzYjkiLCJpbWFnZV9pZCI6IjZhZjk4YWYyLTMwNzctNGY1Yy05ZjgwLTEyZDdjYjI5YmZjNiIsInRyYW5zZm9ybWF0aW9ucyI6W3siYW5nbGUiOjkwfV19.NWF9l5Uit3XuM_QIJvryovH8RM-j3eIDpYnbUijDIzM</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--kvIrV76H--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/a_90/v44444/azhar.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e40a658f-1317-44e8-bebe-f6c5b2e424a8
X-Runtime: 0.008792
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 252</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--kvIrV76H--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/a_90/v44444/azhar.jpg">redirected</a>.</body></html></pre>
