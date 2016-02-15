# User API

## Retreive current user

### GET /api/v1/user
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyNmQ0ZThlNy1kZWUyLTRkNTctOTIwOC0zNWFkNDVmYzE3ZjAifQ.tZKoxljz32VaFf0y2ppcLiV8jB-vbLJpHMBvWPitDlk&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/user</pre>

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
X-access-admin: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyNmQ0ZThlNy1kZWUyLTRkNTctOTIwOC0zNWFkNDVmYzE3ZjAifQ.tZKoxljz32VaFf0y2ppcLiV8jB-vbLJpHMBvWPitDlk
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 0555d1cb-be50-4627-9de0-458a5e65d53d
X-Runtime: 0.042345
Content-Length: 133</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"26d4e8e7-dee2-4d57-9208-35ad45fc17f0","fullname":"translation missing: fr.unknown_user","email":"luc+14@sharinpix.com"}</pre>
