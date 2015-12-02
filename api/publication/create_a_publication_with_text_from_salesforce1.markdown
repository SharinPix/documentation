# Publication API

## Create a publication with text from salesforce1

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJiMTQyMTA5YS1jNTY0LTQ0NjctYTU1NS1iMDJlNGU2OTk4MmMifQ.RvP97CkAcz_7-dXwZzp-Y5EHe-nFzllIlPFDer3KFbY&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/b44afd4a-ca45-416e-b697-81ffe04feb5e/publications</pre>

#### Body

<pre>infos[messageSegments][][type]=text&infos[messageSegments][][text]=Can+you+all+join+me+to+congratulate&infos[messageSegments][][type]=mention&infos[messageSegments][][id]=00524000000FzDkAAK&infos[messageSegments][][type]=text&infos[messageSegments][][text]=+and+all+his+team+on+this+one.</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJiMTQyMTA5YS1jNTY0LTQ0NjctYTU1NS1iMDJlNGU2OTk4MmMifQ.RvP97CkAcz_7-dXwZzp-Y5EHe-nFzllIlPFDer3KFbY
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;07c1afda7ce94c9b9f04d1e2f3a6f394&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 75019cd6-c640-44e8-942d-d3ac855fb639
X-Runtime: 0.029839
Content-Length: 292</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"47a3856f-9133-4eeb-bf69-e45c59cb839d","thumbnail":"https://localhost/publications/47a3856f-9133-4eeb-bf69-e45c59cb839d/thumbnail","title":"Album du 02/12/2015","description":"1 photo disponible\nPowered by SharinPix","aux_text":"","entity_id":"","views_count":0,"opens_count":0}</pre>
