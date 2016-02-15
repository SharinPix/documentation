# Album API

## Retreive an album

### GET /api/v1/albums/:id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlZTliNzY3Ny01YzNmLTQzYjQtYmE2My03ZGE3ZGQ2YTk4NzQifQ.FHb5TuETTx06Q-Deot6nPp536GtjJ0lmzZRjmwl_dSg&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/8823bfd0-e08b-43d6-b9f4-44505b2661ca</pre>

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
X-access-image_delete: true
X-access-image_upload: true
X-access-image_share: false
X-access-image_rotate: true
X-access-image_crop: true
X-access-stats: true
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlZTliNzY3Ny01YzNmLTQzYjQtYmE2My03ZGE3ZGQ2YTk4NzQifQ.FHb5TuETTx06Q-Deot6nPp536GtjJ0lmzZRjmwl_dSg
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f345c4aa-3cac-4531-949b-f157a78d3a12
X-Runtime: 0.057123
Content-Length: 1145</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"8823bfd0-e08b-43d6-b9f4-44505b2661ca","upload_form":{"url":"https://api-de.cloudinary.com/v1_1/hwja6b0dx/auto/upload","params":{"timestamp":1455537777,"transformation":"a_exif","type":"private","tags":"8823bfd0-e08b-43d6-b9f4-44505b2661ca","signature":"7aa73191586265df2d91f54c042ef08fe03229a8","api_key":"744524991939777"}},"images_count":1,"views_count":0,"thumbnails":[{"public_id":"1377de20-184c-4e29-a0c3-f1fcad596dc5","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["8823bfd0-e08b-43d6-b9f4-44505b2661ca"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:57.700+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"8823bfd0-e08b-43d6-b9f4-44505b2661ca","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]}</pre>
