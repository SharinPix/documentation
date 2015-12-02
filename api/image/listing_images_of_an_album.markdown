# Image API

## Listing images of an album

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI2MWQ4MjdiNy04MDY2LTRiOGYtYjdhMi03NmM0YTFiYWFiODgifQ.v7TvyFcUDEvfBEUy9eaaKjsG1QA5rY89iKkZ_ETnj_0&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/0a37d440-c19c-4c89-90cd-1980706e3626/images</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI2MWQ4MjdiNy04MDY2LTRiOGYtYjdhMi03NmM0YTFiYWFiODgifQ.v7TvyFcUDEvfBEUy9eaaKjsG1QA5rY89iKkZ_ETnj_0
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;d751713988987e9331980363e24189ce&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 211b9971-4024-4ae9-af70-1011902dd56d
X-Runtime: 0.010337
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
