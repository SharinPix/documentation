# Image API

## Retreive and image

### GET /api/v1/images/:id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzUsImFiaWxpdGllcyI6eyJiZTkxNGJiNy02ZjY0LTQ3NGItOTVkYi04ZDhhODNhMmVmMTYiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJjYmQ4ZDQwMC00ZTQwLTQ4MjYtYmU3NS1lOWY1MWY0ZDIzOWIifQ.L3Vzf6KsoQL5ipj3pD6tkGB7UZfIlfWwjH4LrzNh3T4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/b9206f8b-92b1-48f2-a0b4-2ee9bdfdd6bf</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-access-crop: false
X-access-rotate: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzUsImFiaWxpdGllcyI6eyJiZTkxNGJiNy02ZjY0LTQ3NGItOTVkYi04ZDhhODNhMmVmMTYiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJjYmQ4ZDQwMC00ZTQwLTQ4MjYtYmU3NS1lOWY1MWY0ZDIzOWIifQ.L3Vzf6KsoQL5ipj3pD6tkGB7UZfIlfWwjH4LrzNh3T4
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;779fb762ab0330a404601cbeb347d709&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 34308fc5-e184-4c3d-a947-c4113ed381ef
X-Runtime: 0.009630
Content-Length: 757</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"b9206f8b-92b1-48f2-a0b4-2ee9bdfdd6bf","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["be914bb7-6f64-474b-95db-8d8a83a2ef16"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:35.010+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"be914bb7-6f64-474b-95db-8d8a83a2ef16","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
