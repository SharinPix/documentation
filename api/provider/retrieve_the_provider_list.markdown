# Provider API

## Retrieve the provider list

### GET /api/v1/albums/:album_id/providers
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiZDUxNmJlYTUtZGU3Ni00MmU3LWIwYzAtNWY5Y2Q4YzA1NDM4In0.FwYdTGlvZL6xt2-M_QX-QJfLEtMJuHyd0PcQPW91V5A&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiZDUxNmJlYTUtZGU3Ni00MmU3LWIwYzAtNWY5Y2Q4YzA1NDM4In0.FwYdTGlvZL6xt2-M_QX-QJfLEtMJuHyd0PcQPW91V5A
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 440fac1f-bacd-45ef-9292-86073d0e430b
X-Runtime: 0.043060
Content-Length: 70</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"name":"test provider","id":"05af6978-a94e-4666-9dc5-1323ff1b776a"}]</pre>
