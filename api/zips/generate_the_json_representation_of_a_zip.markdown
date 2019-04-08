# Zips API

## generate the json representation of a zip

### GET /api/v1/organizations/:organization_id/albums/:album_id/zip

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| timestamp | The timestamp used to expire the url | false |  |

### Request

#### Headers

<pre>X-Zipper-Signature: 
X-Zipper-Timestamp: 
X-Zipper-Request-Id: 
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/organizations/f012de45-20a7-4041-99bc-a087b21e96e9/albums/00100000123BB212/zip?timestamp=1554745138</pre>

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
X-Request-Id: ece3c8b9-0691-4412-baf2-29413f0b3fc0
X-Runtime: 0.002611
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 18</pre>

#### Status

<pre>401 Unauthorized</pre>

#### Body

<pre>Signature is empty</pre>
