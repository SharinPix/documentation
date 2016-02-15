# TagImage API

## create tag images

### POST /api/v1/tags/:tag_id/tag_images

### Parameters

Name : tag_id
Description : Id du tag

Name : image_ids
Description : id of images

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMTY5NjY4NjAtY2FiYS00ZGI2LTkwZDAtYmFmYWQ3YTEyNjBkIn0.5eK8CgKoc05Q_7shEGmVDubJAb6yTy7eAeoAG16ew-c&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/tags/d2caedf3-4367-4f3b-a0ec-d5d03b30927a/tag_images</pre>

#### Body

<pre>image_ids[]=92109f76-12e5-4155-81f8-90aae0157600&image_ids[]=6a8b6518-8b6c-4cbb-ae04-2a9d5ffd3800&image_ids[]=534ce9e8-f3ee-44c4-94c5-798f61819697</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzYsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMTY5NjY4NjAtY2FiYS00ZGI2LTkwZDAtYmFmYWQ3YTEyNjBkIn0.uWzd5R7QY6HI8C_vLRKF8O4cjZJafGuRQR7FuYEzQe0
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: a23d1a0b-6fce-43d7-8bd0-db1b98d6b2da
X-Runtime: 0.090464
Content-Length: 3094</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"b005ca9f-74dc-4381-a716-7123dc431a8f","created_at":"2016-02-15T13:02:56.087+01:00","user":"16966860-caba-4db6-90d0-bafad7a1260d","image":{"public_id":"92109f76-12e5-4155-81f8-90aae0157600","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:56.002+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"d2caedf3-4367-4f3b-a0ec-d5d03b30927a","created_at":"2016-02-15T13:02:55.991+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}},{"id":"dbb08169-1429-460a-903d-32bf9a1a79ea","created_at":"2016-02-15T13:02:56.093+01:00","user":"16966860-caba-4db6-90d0-bafad7a1260d","image":{"public_id":"6a8b6518-8b6c-4cbb-ae04-2a9d5ffd3800","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:56.009+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"d2caedf3-4367-4f3b-a0ec-d5d03b30927a","created_at":"2016-02-15T13:02:55.991+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}},{"id":"279016cd-1ef3-4fb8-9c4d-91db0935c346","created_at":"2016-02-15T13:02:56.098+01:00","user":"16966860-caba-4db6-90d0-bafad7a1260d","image":{"public_id":"534ce9e8-f3ee-44c4-94c5-798f61819697","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:56.019+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"d2caedf3-4367-4f3b-a0ec-d5d03b30927a","created_at":"2016-02-15T13:02:55.991+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
