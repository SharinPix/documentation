# Publication API

## Create a publication with text

### POST /api/v1/albums/:album_id/publications
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkYmJkYjJjYy1kZTRkLTQ0ZjItYjllYi00ZGY0ZTNkNDY2OWMifQ.G4jaBQDVRqGGxCzxXbMIn38S5uiVu4qfK4ImNSXtbzQ&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/fa7fd79b-ef9c-4774-9043-eb42e7d480c2/publications</pre>

#### Body

<pre>infos[text]=I+am+sharing+this+amazing+album</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkYmJkYjJjYy1kZTRkLTQ0ZjItYjllYi00ZGY0ZTNkNDY2OWMifQ.G4jaBQDVRqGGxCzxXbMIn38S5uiVu4qfK4ImNSXtbzQ
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e4088814-8715-47d8-8fc8-9d3f7e7adb08
X-Runtime: 0.030917
Content-Length: 292</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"d9c423a5-adc1-4fdf-9ca0-88925452358d","thumbnail":"https://localhost/publications/d9c423a5-adc1-4fdf-9ca0-88925452358d/thumbnail","title":"Album du 15/02/2016","description":"1 photo disponible\nPowered by SharinPix","aux_text":"","entity_id":"","views_count":0,"opens_count":0}</pre>
