# Provider API

## Retrieve the list of Providers

### GET /api/v1/albums/:album_id/providers
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjI4ZmM3NjYwLWM5NDAtNDlkZC1hNmVhLWY3ZDEzMjYyMWQ3ZCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19fQ.W8VwkTn4R5mSSr0UIYFzfpsBjPWuCMVHKMaJcznK0cM&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00324000004ijWS/providers</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjI4ZmM3NjYwLWM5NDAtNDlkZC1hNmVhLWY3ZDEzMjYyMWQ3ZCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19fQ.W8VwkTn4R5mSSr0UIYFzfpsBjPWuCMVHKMaJcznK0cM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 9b82b340-9f7a-4477-b03c-031b2e00e7f2
X-Runtime: 0.015300
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 70</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "name": "test provider",
    "id": "e9b4014d-2d91-4882-b314-fc4626a3fce6"
  }
]</pre>
