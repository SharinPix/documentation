# Publication API

## Create a publication with text from salesforce1

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxODAsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkMDE4N2UxYi1hNWFkLTQ4MWYtOTU3MS05NDFjYzRiNjQxMTcifQ.x-wAnvCADve9I9PBTtKoqXpxDxxdD02ieH0Xhpju5PM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/aeee0cfb-bf2f-4e96-9ebf-3b29e76d46e6/publications</pre>

#### Body

<pre>infos[messageSegments][][type]=text&infos[messageSegments][][text]=Can+you+all+join+me+to+congratulate&infos[messageSegments][][type]=mention&infos[messageSegments][][id]=00524000000FzDkAAK&infos[messageSegments][][type]=text&infos[messageSegments][][text]=+and+all+his+team+on+this+one.</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxODAsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkMDE4N2UxYi1hNWFkLTQ4MWYtOTU3MS05NDFjYzRiNjQxMTcifQ.x-wAnvCADve9I9PBTtKoqXpxDxxdD02ieH0Xhpju5PM
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 6f136c9a-2bea-4b71-baf2-e1b1facbaca3
X-Runtime: 0.058732
Content-Length: 292</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"d09ffaa2-5359-4cda-b630-d3fe6d020cdc","thumbnail":"https://localhost/publications/d09ffaa2-5359-4cda-b630-d3fe6d020cdc/thumbnail","title":"Album du 15/02/2016","description":"1 photo disponible\nPowered by SharinPix","aux_text":"","entity_id":"","views_count":0,"opens_count":0}</pre>
