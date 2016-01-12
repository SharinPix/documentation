# Image API

## return an empty list

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTYsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI2OTQ1OGY3ZS1mZjg0LTRjZjYtYmYzMC01ZjVjZGI2M2MwMWIifQ.IQ79ESZ_Jcrbo2EUZ2KkptgyDMFNsTIbOWMifiO9N2Q&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/super-id/images</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTYsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI2OTQ1OGY3ZS1mZjg0LTRjZjYtYmYzMC01ZjVjZGI2M2MwMWIifQ.IQ79ESZ_Jcrbo2EUZ2KkptgyDMFNsTIbOWMifiO9N2Q
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4445fb0d-26b1-4ae2-8c65-5041441814e5
X-Runtime: 0.039987
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
