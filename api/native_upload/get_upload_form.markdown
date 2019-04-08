# Native Upload API

## Get upload form

### GET api/v1/native_upload?app_version=2
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/native_upload?app_version=2</pre>

#### Query Parameters

<pre>app_version: 2</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 3eea97b2-3c49-4b6a-9de2-9c87cbb71319
X-Runtime: 0.005668
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 383</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
  "expires_at": 1557337145,
  "params": {
    "colors": 1,
    "faces": 1,
    "image_metadata": 1,
    "notification_url": "https://localhost:5001/api/v1/native_upload/image",
    "phash": 1,
    "tags": "sharinpix_mobile_app_images",
    "timestamp": 1557337145,
    "type": "authenticated",
    "signature": "cad190be6bda4047e380c3fd646bb38204e231c7",
    "api_key": "123123123123"
  }
}</pre>
