# Provider API

## Retrieve the provider list

### GET /api/v1/albums/:album_id/providers
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTksImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiNDc5ZGNhZjktMGIyZi00MTRmLWExZWItZWI0M2IwMjU4MTVhIn0.gFRfNZ9aTqyElDizEZOwQLhbmlKmo_0tvnJsa8ciqmE&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00324000004ijWS/providers</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTksImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiNDc5ZGNhZjktMGIyZi00MTRmLWExZWItZWI0M2IwMjU4MTVhIn0.gFRfNZ9aTqyElDizEZOwQLhbmlKmo_0tvnJsa8ciqmE
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f9bdb7a8-d67d-43dc-bfbd-3e886e15869d
X-Runtime: 0.055792
Content-Length: 70</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"name":"test provider","id":"5d984a4c-1703-41a9-b641-25085a2baa71"}]</pre>
