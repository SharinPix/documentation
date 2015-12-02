# Album API

## Listing albums

### GET /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJiZTJlZDMzNy04YmFlLTRkOTYtYTRkYS00ZmYyNWVjYjNmNmIifQ.-VsyVC7G_2-Dhx7D1sYqOHLg-fNYMTqd-c3WAt1VvdI&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJiZTJlZDMzNy04YmFlLTRkOTYtYTRkYS00ZmYyNWVjYjNmNmIifQ.-VsyVC7G_2-Dhx7D1sYqOHLg-fNYMTqd-c3WAt1VvdI
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;e9e740804048c1826d10eed9a1e9ebd7&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 7ed75ccd-a02a-46b2-8a65-b91a0c6ab389
X-Runtime: 0.040344
Content-Length: 4216</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"af91a1d2-3acc-40a1-9cbb-5283057651be","images_count":1,"thumbnails":[{"public_id":"de7072da-9a46-4cc4-8d50-3d002b238818","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["af91a1d2-3acc-40a1-9cbb-5283057651be"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:33.899+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"af91a1d2-3acc-40a1-9cbb-5283057651be","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"db6891d6-2f22-4945-9f1b-7867eaae53b8","images_count":1,"thumbnails":[{"public_id":"653e6666-330f-463c-97de-0063d0cab57b","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["db6891d6-2f22-4945-9f1b-7867eaae53b8"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:33.889+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"db6891d6-2f22-4945-9f1b-7867eaae53b8","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"66d20e6e-4e22-4e1a-bdbf-06769b0c23de","images_count":1,"thumbnails":[{"public_id":"77123391-570a-4278-ab5d-8e333642c6f5","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["66d20e6e-4e22-4e1a-bdbf-06769b0c23de"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:33.881+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"66d20e6e-4e22-4e1a-bdbf-06769b0c23de","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"81345522-dbc4-4a18-b7f8-681cafa9b4c2","images_count":1,"thumbnails":[{"public_id":"2a085f06-eafd-441d-8179-9c7b6b4015a0","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["81345522-dbc4-4a18-b7f8-681cafa9b4c2"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:33.872+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"81345522-dbc4-4a18-b7f8-681cafa9b4c2","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]},{"public_id":"a133afc6-a1bb-4606-ab01-bf40b8b49490","images_count":1,"thumbnails":[{"public_id":"6d621f47-2df1-40be-8448-5774e7c8c28c","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["a133afc6-a1bb-4606-ab01-bf40b8b49490"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:33.863+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"a133afc6-a1bb-4606-ab01-bf40b8b49490","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]}]</pre>