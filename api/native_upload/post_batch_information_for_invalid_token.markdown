# Native Upload API

## Post batch information for invalid token

### POST api/v1/native_upload/batch

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| params | JSON file | false |  |

### Request

#### Headers

<pre>Host: example.org
Content-Type: multipart/form-data; boundary=----------XnJLe9ZIbbGUYtzPQJ16u1
Cookie: </pre>

#### Route

<pre>POST api/v1/native_upload/batch</pre>

#### Body

<pre>------------XnJLe9ZIbbGUYtzPQJ16u1
Content-Disposition: form-data; name="file"; filename="test20190408-252-2djavh.json"
Content-Type: application/json
Content-Length: 524

[uploaded data]
------------XnJLe9ZIbbGUYtzPQJ16u1--</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: text/html
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 347216a7-247f-461b-bd75-fadbda4ae315
X-Runtime: 0.014893
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>200 OK</pre>

