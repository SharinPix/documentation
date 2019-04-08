# Native Upload API

## Get upload form (obsolete)

### GET api/v1/native_upload
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/native_upload</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 708fb0d2-45a9-490c-8fbe-1ba9ccde1abe
X-Runtime: 0.002713
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 377</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
  "expires_at": 1557337146,
  "params": {
    "colors": 1,
    "faces": 1,
    "image_metadata": 1,
    "notification_url": "https://localhost:5001/api/v1/native_upload",
    "phash": 1,
    "tags": "sharinpix_mobile_app_images",
    "timestamp": 1557337146,
    "type": "authenticated",
    "signature": "756896a434a0e56edc5328de8e5493e52fae4176",
    "api_key": "123123123123"
  }
}</pre>
