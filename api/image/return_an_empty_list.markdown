# Image API

## return an empty list

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyMGZkMWRiYy01NzNlLTRhZDAtYjNmZC04NmE2MjY0ODZjMjMifQ.HzAkkNRr4jg2kGQG7xrg0-nO_WcCGaNf9OWqt9DV3-Y&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyMGZkMWRiYy01NzNlLTRhZDAtYjNmZC04NmE2MjY0ODZjMjMifQ.HzAkkNRr4jg2kGQG7xrg0-nO_WcCGaNf9OWqt9DV3-Y
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f3a5b19f-0cf2-4bd7-bb1d-9ab4a7b2c335
X-Runtime: 0.015461
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
