# Image API API

## Listing images of an album

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzQsImlhdCI6MTU1NDc0NTEzNCwidXNlcl9pZCI6IjZjMWI0ZDFiLWZkYzEtNGNkZi1hZDg0LWNmMGUyNmIxZjA5MiIsImFiaWxpdGllcyI6e319.yCgYkneJPNZI98CYPreFn4ktzLU9FFLO9FCdh41xwEo&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00100000123BB150/images</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzQsImlhdCI6MTU1NDc0NTEzNCwidXNlcl9pZCI6IjZjMWI0ZDFiLWZkYzEtNGNkZi1hZDg0LWNmMGUyNmIxZjA5MiIsImFiaWxpdGllcyI6e319.yCgYkneJPNZI98CYPreFn4ktzLU9FFLO9FCdh41xwEo
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 6aca38e5-03d0-4171-b564-a9e08a6bd9c9
X-Runtime: 0.009016
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

<pre>[

]</pre>
