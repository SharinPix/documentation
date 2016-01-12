# Image API

## Listing images

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTUsImFiaWxpdGllcyI6eyJlNDRjOWQxMC01NmMwLTRkMjYtYWQzMS00ZjZhZTYzZDc4OGYiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIzYWEzZjBlMS1iNDRjLTQyZjktOWM5Yy0zNzhmYWJlMDU5MDEifQ.G_YulCK1JGzqoHXUAe56z_uaeekeJzG8tx4-gpmA4dg&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/e44c9d10-56c0-4d26-ad31-4f6ae63d788f/images</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTYsImFiaWxpdGllcyI6eyJlNDRjOWQxMC01NmMwLTRkMjYtYWQzMS00ZjZhZTYzZDc4OGYiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIzYWEzZjBlMS1iNDRjLTQyZjktOWM5Yy0zNzhmYWJlMDU5MDEifQ.I2Tl1kCqO13ob2LvLO0p04V2IEyG11ci71fLV6XxwB8
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: c412f2a1-537c-4004-a5ec-9d48699026ff
X-Runtime: 0.039716
Content-Length: 3791</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"c9afcd0a-231d-4926-a110-204e94892af8","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e44c9d10-56c0-4d26-ad31-4f6ae63d788f"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:16.190+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e44c9d10-56c0-4d26-ad31-4f6ae63d788f","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"c71002e0-52bc-46eb-b1ac-d719bf0f1cd4","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e44c9d10-56c0-4d26-ad31-4f6ae63d788f"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:16.113+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e44c9d10-56c0-4d26-ad31-4f6ae63d788f","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"8d27506f-3d53-4a8e-9919-2aa716acc1d3","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e44c9d10-56c0-4d26-ad31-4f6ae63d788f"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:16.014+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e44c9d10-56c0-4d26-ad31-4f6ae63d788f","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"514abe33-349e-4128-b3e7-a62f54490742","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e44c9d10-56c0-4d26-ad31-4f6ae63d788f"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:15.981+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e44c9d10-56c0-4d26-ad31-4f6ae63d788f","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},{"public_id":"6f81ff2a-92c6-461f-89c8-02b0615a53c4","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e44c9d10-56c0-4d26-ad31-4f6ae63d788f"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:15.914+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e44c9d10-56c0-4d26-ad31-4f6ae63d788f","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]</pre>
