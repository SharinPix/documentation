# Publication API

## Create a publication

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJmZmY2NjJmNC04ZGQ3LTQ2MjQtYjZmNS04NDEyZjAwMGJlODcifQ.WQoKRQ-1JIgP-vyuMmQlRGFd60yqpmM8vrNEovqWWhM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/2f8be17f-a98e-4294-8c6f-c192f93b7bd5/publications</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJmZmY2NjJmNC04ZGQ3LTQ2MjQtYjZmNS04NDEyZjAwMGJlODcifQ.6cUUX_p2dlrQfzLUYkcvEGamSZZLg3FMQWnYRyq6PLI
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;0bccc29e5e9bd501df626cc66a28d6da&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 278bf80e-ad1b-4cc0-9232-cdcb19a8bec6
X-Runtime: 0.053329
Content-Length: 313</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"d4266ff0-c669-4c2e-bb77-d3f9b6596be0","thumbnail":"https://localhost/publications/d4266ff0-c669-4c2e-bb77-d3f9b6596be0/thumbnail","title":"Album du 02/12/2015","description":"1 photo disponible\nPowered by SharinPix","aux_text":"a partagé un album: ","entity_id":"","views_count":0,"opens_count":0}</pre>
