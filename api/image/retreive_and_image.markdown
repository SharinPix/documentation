# Image API

## Retreive and image

### GET /api/v1/images/:id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTUsImFiaWxpdGllcyI6eyI2YmZiODY0Yy04OTI3LTQ4ZDQtYTI4Ni05N2JhODU4M2Y3YWUiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiI5MGNmYjUzOC0wMjg0LTRlOTktODg4ZS1hM2NkYjQ3NzgxMDEifQ.kxTogWho77qHSykYuIVUVwakWF88qFx9NV3o8lNIG1c&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/5cf8c06d-83fa-4ede-b995-5efd3133b6e5</pre>

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
X-access-crop: false
X-access-rotate: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTUsImFiaWxpdGllcyI6eyI2YmZiODY0Yy04OTI3LTQ4ZDQtYTI4Ni05N2JhODU4M2Y3YWUiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiI5MGNmYjUzOC0wMjg0LTRlOTktODg4ZS1hM2NkYjQ3NzgxMDEifQ.kxTogWho77qHSykYuIVUVwakWF88qFx9NV3o8lNIG1c
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 0157b7b3-564c-4dce-916c-bbb5c05b77ce
X-Runtime: 0.039901
Content-Length: 757</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"5cf8c06d-83fa-4ede-b995-5efd3133b6e5","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["6bfb864c-8927-48d4-a286-97ba8583f7ae"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:15.692+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"6bfb864c-8927-48d4-a286-97ba8583f7ae","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
