# Annotation API

## Upload annotations

### PUT /api/v1/images/:image_id/annotation

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| annotation | annotation svg | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjQsImlhdCI6MTU1NDc0NTEyNCwidXNlcl9pZCI6ImU3NzZjMDc3LTVlZjktNGIzMi04ZGRiLWU2ZjBmYzI2ZjE1OCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCOSI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZSwiaW1hZ2VfYW5ub3RhdGUiOnRydWV9fX19.jtQ2AWwYIa0FcPLOfGBLplfrmGlEQZoy_-R39yHZSwA&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/6461f01c-8691-4962-bd67-1e347944d8e9/annotation</pre>

#### Body

<pre>annotation=%3Csvg%3Eblank%3C%2Fsvg%3E</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjQsImlhdCI6MTU1NDc0NTEyNCwidXNlcl9pZCI6ImU3NzZjMDc3LTVlZjktNGIzMi04ZGRiLWU2ZjBmYzI2ZjE1OCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCOSI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZSwiaW1hZ2VfYW5ub3RhdGUiOnRydWV9fX19.jtQ2AWwYIa0FcPLOfGBLplfrmGlEQZoy_-R39yHZSwA
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d5f92387-fc2c-4396-addf-339e88a1f965
X-Runtime: 0.013825
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 60</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "svg": "<svg>blank</svg>",
  "object": null
}</pre>
