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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMjQ3YWNlOGMtNDY5Ni00MmFkLWJkMDgtYTJiYWJhN2Q1ZWViIn0.HMT99OZBUZczV1ssAHoHRaQ3p7Hl4XeAXhuHkP8B984&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/tags/9512bb80-9603-43fc-9f49-47dd94e135b0/tag_images</pre>

#### Body

<pre>image_ids[]=9a78255b-2dc2-4849-837f-273ea5e3af67&image_ids[]=78ca6aa8-9578-45d9-be45-a8015cd484f5&image_ids[]=5ab7f857-1809-4237-8ca0-179ec75bd959</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMjQ3YWNlOGMtNDY5Ni00MmFkLWJkMDgtYTJiYWJhN2Q1ZWViIn0.HMT99OZBUZczV1ssAHoHRaQ3p7Hl4XeAXhuHkP8B984
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 5275c4cb-1f4d-4b73-b604-30edb0021f4e
X-Runtime: 0.149931
Content-Length: 3094</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"39e5529d-de01-4b43-ab2a-baa1ea334deb","created_at":"2016-01-12T15:05:18.456+01:00","user":"247ace8c-4696-42ad-bd08-a2baba7d5eeb","image":{"public_id":"9a78255b-2dc2-4849-837f-273ea5e3af67","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:18.300+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"9512bb80-9603-43fc-9f49-47dd94e135b0","created_at":"2016-01-12T15:05:18.277+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}},{"id":"93905919-ffb4-4149-90bd-4546afdcfe5d","created_at":"2016-01-12T15:05:18.467+01:00","user":"247ace8c-4696-42ad-bd08-a2baba7d5eeb","image":{"public_id":"78ca6aa8-9578-45d9-be45-a8015cd484f5","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:18.338+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"9512bb80-9603-43fc-9f49-47dd94e135b0","created_at":"2016-01-12T15:05:18.277+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}},{"id":"04611dce-5216-4e52-8525-197aa3722cda","created_at":"2016-01-12T15:05:18.476+01:00","user":"247ace8c-4696-42ad-bd08-a2baba7d5eeb","image":{"public_id":"5ab7f857-1809-4237-8ca0-179ec75bd959","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:18.356+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"9512bb80-9603-43fc-9f49-47dd94e135b0","created_at":"2016-01-12T15:05:18.277+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
