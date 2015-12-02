# Provider API

## Retrieve the provider list

### GET /api/v1/albums/:album_id/providers
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiN2I2NWI0YmEtYjQ4My00YjU3LWJhMzktNTljNTE3YzljY2VhIn0.kWiN0ybk_GMK2Wetr0aygCFV0W8hiYzDkddZym2ko-A&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00324000004ijWS/providers</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiN2I2NWI0YmEtYjQ4My00YjU3LWJhMzktNTljNTE3YzljY2VhIn0.kWiN0ybk_GMK2Wetr0aygCFV0W8hiYzDkddZym2ko-A
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;a8adc369e53cc7ff980ff0cbf9d69d93&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4ca4f5fd-1a8d-41fb-82ef-aa965f0a28b6
X-Runtime: 0.020220
Content-Length: 70</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"name":"test provider","id":"e6b0d0ad-3950-4f7c-a2b6-a341a5610dbe"}]</pre>
