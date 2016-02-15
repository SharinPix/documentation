# Image API

## Listing images of an album

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyYzNhMGUwNy01Y2QyLTQ4MjgtYTVkOC1mYjE5ZTMwZGQ0NzMifQ.JkxP1g0kjjbhWcig7E2p6HcoLaT8RB3X8KghyTxIZF8&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/15635709-4b50-4d42-a7cc-8f36133cef41/images</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyYzNhMGUwNy01Y2QyLTQ4MjgtYTVkOC1mYjE5ZTMwZGQ0NzMifQ.JkxP1g0kjjbhWcig7E2p6HcoLaT8RB3X8KghyTxIZF8
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f45420bc-c287-491c-8191-4e1787431f6e
X-Runtime: 0.009450
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
