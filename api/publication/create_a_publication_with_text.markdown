# Publication API

## Create a publication with text

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI0NTkzOWRkZi1kMGFjLTQ4NGItYjkxYS0wZDE0MTVjYTIxZmYifQ.iX88HlgLld2zkh9rxXVoB2K_pqKGTZ300bCg3a5sXdk&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/86e17c9a-5f93-42f4-876d-52ccd3684625/publications</pre>

#### Body

<pre>infos[text]=I+am+sharing+this+amazing+album</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI0NTkzOWRkZi1kMGFjLTQ4NGItYjkxYS0wZDE0MTVjYTIxZmYifQ.iX88HlgLld2zkh9rxXVoB2K_pqKGTZ300bCg3a5sXdk
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;cd4fcfdc2a7e359aaab207a59d4233d4&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: dce1d209-b7cf-4e6e-8f64-022ea026f99b
X-Runtime: 0.030224
Content-Length: 292</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"6bd26630-f3dc-4230-9851-2774583dc928","thumbnail":"https://localhost/publications/6bd26630-f3dc-4230-9851-2774583dc928/thumbnail","title":"Album du 02/12/2015","description":"1 photo disponible\nPowered by SharinPix","aux_text":"","entity_id":"","views_count":0,"opens_count":0}</pre>
