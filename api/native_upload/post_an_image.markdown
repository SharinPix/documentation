# Native Upload API

## Post an image

### POST api/v1/native_upload/image

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| raw_post | JSON as body. | false |  |

### Request

#### Headers

<pre>X-Cld-Timestamp: 1554745146
X-Cld-Signature: 2f0fc1acb3f3d377dc2aa3b642b625de7aa4cb6e
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/native_upload/image</pre>

#### Body

<pre>{"version":1507784418,"format":"jpg","resource_type":"image","type":"authenticated","original_filename":"SharinPixM1","public_id":"twio1"}</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: text/html
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 19b34e6e-1767-44a9-9187-554911e1719f
X-Runtime: 0.009409
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>201 Created</pre>

