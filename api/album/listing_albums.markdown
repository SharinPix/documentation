# Album API

## Listing albums

### GET /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyY2QyNjc0Zi1jMzk5LTQzNDUtOTNkNi05ZGRkNjdjY2JlMzkifQ.Z-v7q0oyTkZ1zcC5J6uDtZyx7V3KgEwzCog2RodibyA&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIyY2QyNjc0Zi1jMzk5LTQzNDUtOTNkNi05ZGRkNjdjY2JlMzkifQ.Z-v7q0oyTkZ1zcC5J6uDtZyx7V3KgEwzCog2RodibyA
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 94bf9f4d-6879-4e57-b49d-52184a782d0d
X-Runtime: 0.031819
Content-Length: 4216</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"b7287ea6-c3fd-405e-84a3-6ba5a203777e","images_count":1,"thumbnails":[{"public_id":"2671091d-b57e-4980-82a2-668cb51f604b","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["b7287ea6-c3fd-405e-84a3-6ba5a203777e"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:57.595+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"b7287ea6-c3fd-405e-84a3-6ba5a203777e","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"6132098c-089b-4849-8285-1eb13b57e7bd","images_count":1,"thumbnails":[{"public_id":"c341b5a1-4cd1-4076-a183-19cf7d6c2152","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["6132098c-089b-4849-8285-1eb13b57e7bd"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:57.587+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"6132098c-089b-4849-8285-1eb13b57e7bd","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"65eebb74-1b20-435e-bbf6-bc4d3229f3e8","images_count":1,"thumbnails":[{"public_id":"19a77606-89f5-4382-8998-9e59b37f164b","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["65eebb74-1b20-435e-bbf6-bc4d3229f3e8"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:57.577+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"65eebb74-1b20-435e-bbf6-bc4d3229f3e8","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"39df2abc-d30c-487c-956a-b36b14d0a7db","images_count":1,"thumbnails":[{"public_id":"90731efb-6490-4e02-b075-d36f61ee10a2","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["39df2abc-d30c-487c-956a-b36b14d0a7db"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:57.561+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"39df2abc-d30c-487c-956a-b36b14d0a7db","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"571cf1b2-3a12-4ebd-9e99-f16bf067f451","images_count":1,"thumbnails":[{"public_id":"4e981de6-90f1-46d7-a1ae-d8f4eda9e64f","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["571cf1b2-3a12-4ebd-9e99-f16bf067f451"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:57.546+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"571cf1b2-3a12-4ebd-9e99-f16bf067f451","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]}]</pre>
