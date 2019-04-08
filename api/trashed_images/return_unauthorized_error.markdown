# Trashed images API

## Return unauthorized error

### GET api/v1/trashed_images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhYmlsaXRpZXMiOnt9LCJpc3MiOiI3NDZhZTAwNS1hM2NiLTQ0YjYtODI3YS1hMjNiZjM4N2IxMzcifQ.prJ9zSk-cVwCZXC_2CBYN8MrR6yaBfONiChvDFHgrrs&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/trashed_images</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-message: Access denied
Content-Type: text/html
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e253d360-88a5-4f90-b885-1814e9e6aa1f
X-Runtime: 0.004468
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>401 Unauthorized</pre>

