# Image API

## Pass image url

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

<pre>GET /images/image.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI0MTQ1ZDJhZC00YTczLTRkY2EtYmVjNy0zYWRkZTM4MWQxOWMiLCJpbWFnZV9pZCI6Ijk4YjhmZWI5LWJlODAtNGJhZS1hYWE4LTljMjUxNWFlMzVhMSIsInRyYW5zZm9ybWF0aW9ucyI6W3siYW5nbGUiOjkwfV19.6Bu3IfYtxSDQLCkGNUdRjwttNB2h_8cHoFoxkGx_XxY</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI0MTQ1ZDJhZC00YTczLTRkY2EtYmVjNy0zYWRkZTM4MWQxOWMiLCJpbWFnZV9pZCI6Ijk4YjhmZWI5LWJlODAtNGJhZS1hYWE4LTljMjUxNWFlMzVhMSIsInRyYW5zZm9ybWF0aW9ucyI6W3siYW5nbGUiOjkwfV19.6Bu3IfYtxSDQLCkGNUdRjwttNB2h_8cHoFoxkGx_XxY</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ioavEy55--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/a_90/v123123/107e2d08fd11.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 519bd8b2-13cb-460d-9ec2-ac13b89f8c3c
X-Runtime: 0.008769
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 260</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ioavEy55--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/a_90/v123123/107e2d08fd11.jpg">redirected</a>.</body></html></pre>
