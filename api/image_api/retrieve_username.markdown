# Image API API

## Retrieve username

### GET /api/v1/images/:id/user
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjJjMWVhYzA3LWJiZGItNDI4Ni04ZGE5LTEwZWZjMmIyMTU0YiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTY0Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.j70klo8HBE4IW_ijD0D5qYTTFIK3LH2XWtD-52IVvpU&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/1e9387d1-56f4-44d0-ae8a-c6c29300262e/user</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjJjMWVhYzA3LWJiZGItNDI4Ni04ZGE5LTEwZWZjMmIyMTU0YiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTY0Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.j70klo8HBE4IW_ijD0D5qYTTFIK3LH2XWtD-52IVvpU
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 0e5a63e9-e2f1-4541-bc6f-691d7f199b30
X-Runtime: 0.011069
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
}</pre>
