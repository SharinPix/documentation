# Album API

## Listing albums

### GET /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MjAsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5MGEzYTA5MS02ZTFmLTRjZTAtYTFhYi0yZjk0ZjgzMDBmMjEifQ.VAmNp97s47zxcTTmrkCBOQOZ2tjXYue6rz6VvvPUN-g&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MjAsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5MGEzYTA5MS02ZTFmLTRjZTAtYTFhYi0yZjk0ZjgzMDBmMjEifQ.VAmNp97s47zxcTTmrkCBOQOZ2tjXYue6rz6VvvPUN-g
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 217598d6-a319-4c8f-9ef5-3bc6a381965b
X-Runtime: 0.039101
Content-Length: 4216</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"3ed58747-724c-4d86-9f17-39565a993d51","images_count":1,"thumbnails":[{"public_id":"f06761bd-25aa-48e6-9954-4d6eea16aad1","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["3ed58747-724c-4d86-9f17-39565a993d51"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:20.225+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"3ed58747-724c-4d86-9f17-39565a993d51","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"0da61386-649a-4537-86cc-2366d3096bbd","images_count":1,"thumbnails":[{"public_id":"9ceea710-c7d1-4d05-ac60-a29bf8062bd7","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["0da61386-649a-4537-86cc-2366d3096bbd"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:20.200+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"0da61386-649a-4537-86cc-2366d3096bbd","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"79fb1368-7bc3-4c17-884c-da4a44ddcb97","images_count":1,"thumbnails":[{"public_id":"817fd336-2da0-4b93-8cce-5bb1f24d2efe","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["79fb1368-7bc3-4c17-884c-da4a44ddcb97"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:20.168+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"79fb1368-7bc3-4c17-884c-da4a44ddcb97","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"3895a7f0-c6f0-425b-a04a-a79c0ae0ce69","images_count":1,"thumbnails":[{"public_id":"797df02d-8c64-4c84-b0a5-61c3d3df2919","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["3895a7f0-c6f0-425b-a04a-a79c0ae0ce69"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:20.157+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"3895a7f0-c6f0-425b-a04a-a79c0ae0ce69","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"e3201f4d-ae94-463c-a5a8-5ca16f92afd0","images_count":1,"thumbnails":[{"public_id":"b608a75a-fcda-4abd-a8f7-3b82bd106f58","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e3201f4d-ae94-463c-a5a8-5ca16f92afd0"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:20.145+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e3201f4d-ae94-463c-a5a8-5ca16f92afd0","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]}]</pre>
