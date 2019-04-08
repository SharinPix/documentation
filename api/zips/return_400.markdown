# Zips API

## return 400

### GET /api/v1/organizations/:organization_id/albums/:album_id/zip

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| timestamp | The timestamp used to expire the url | false |  |

### Request

#### Headers

<pre>X-Zipper-Signature: ouups
X-Zipper-Timestamp: 1554745138000
X-Zipper-Request-Id: 9fa3e615145200eea746b1bb6c4770af
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/organizations/07249aa9-d8b5-45eb-ab97-8012597b1cc0/albums/00100000123BB214/zip?timestamp=1554745138</pre>

#### Query Parameters

<pre>timestamp: 1554745138</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: text/plain; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8f61b829-8c92-46cd-8011-25f5c42aeca3
X-Runtime: 0.002834
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 22</pre>

#### Status

<pre>401 Unauthorized</pre>

#### Body

<pre>Signature is not valid</pre>
