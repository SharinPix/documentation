# Image API

## Listing images

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6eyJlZWQxNTgzOS0wYWRlLTQ5YjItOTA4OS1kYjc5NzY4NmFlMzkiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJmMjc3YmVhMy1hOGJjLTRlODQtYWJhNS02MzkwZTJjNWUwNTYifQ.bH1wqri4nWPEvCQutFZhzZrf3x1H6qcoJ2J2-hGeDm4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/eed15839-0ade-49b2-9089-db797686ae39/images</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6eyJlZWQxNTgzOS0wYWRlLTQ5YjItOTA4OS1kYjc5NzY4NmFlMzkiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJmMjc3YmVhMy1hOGJjLTRlODQtYWJhNS02MzkwZTJjNWUwNTYifQ.bH1wqri4nWPEvCQutFZhzZrf3x1H6qcoJ2J2-hGeDm4
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 6f51ae02-bab3-47dd-b072-bcf566827959
X-Runtime: 0.031798
Content-Length: 3791</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"2ed222b7-9739-47e3-8764-e4fefcac9481","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["eed15839-0ade-49b2-9089-db797686ae39"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:59.128+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"eed15839-0ade-49b2-9089-db797686ae39","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"42a29bb5-cb51-4018-b958-8cb61b29a3a2","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["eed15839-0ade-49b2-9089-db797686ae39"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:59.119+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"eed15839-0ade-49b2-9089-db797686ae39","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"88d580bf-3c9c-49db-b786-fe82c0f739d6","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["eed15839-0ade-49b2-9089-db797686ae39"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:59.101+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"eed15839-0ade-49b2-9089-db797686ae39","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"50a14bce-05b2-4fd2-a9e8-83ad1ddcd0df","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["eed15839-0ade-49b2-9089-db797686ae39"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:59.085+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"eed15839-0ade-49b2-9089-db797686ae39","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"16f04280-5d84-4c15-837d-97418fd56703","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["eed15839-0ade-49b2-9089-db797686ae39"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:59.063+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"eed15839-0ade-49b2-9089-db797686ae39","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]</pre>
