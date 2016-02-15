# Organization API

## Retreive the organization

### GET /api/v1/organization
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJiYWYyYjRjZi0xYjkzLTQ4MzAtOWFhNi1kZWJjNGUxOTJhNDUifQ.1IIKEoPVzQzWVd0IF4tPBwYnA9C635N-EnwCDI2fBBw&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/organization</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store, must-revalidate, private, max-age=0
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
X-access-stats: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJiYWYyYjRjZi0xYjkzLTQ4MzAtOWFhNi1kZWJjNGUxOTJhNDUifQ.1IIKEoPVzQzWVd0IF4tPBwYnA9C635N-EnwCDI2fBBw
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 068fea7c-ab13-4c5c-8ef2-3de901773170
X-Runtime: 0.024234
Content-Length: 64</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"a556ca58-8a6a-4862-816d-cc8926e5d5a0","name":"SharinPix"}</pre>
