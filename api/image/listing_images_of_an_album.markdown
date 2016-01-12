# Image API

## Listing images of an album

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTYsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIxZjE3MTlkNi1jMGNlLTQ3NDgtYjIzMS1jZGI5YjE5ZTZiNTAifQ.xgcAh8i-byyxkijhDlpTi02HCHk50mvcv-ftHmkQi2Y&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/37bd8672-65f0-483e-812a-c5ce95c1706c/images</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTYsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIxZjE3MTlkNi1jMGNlLTQ3NDgtYjIzMS1jZGI5YjE5ZTZiNTAifQ.xgcAh8i-byyxkijhDlpTi02HCHk50mvcv-ftHmkQi2Y
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 9b422050-6bbb-4777-8a5f-81b28975ad11
X-Runtime: 0.026944
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
