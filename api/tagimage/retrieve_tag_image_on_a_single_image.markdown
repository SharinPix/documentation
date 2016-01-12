# TagImage API

## retrieve tag image on a single image

### GET api/v1/tag_images

### Parameters

Name : tag_name
Description : name of the tag

Name : image_id
Description : Id of the image

Name : album_id
Description : id de l&#39;album

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTcsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiZjEyYjhjODktZmYzNS00YmVhLThmZGQtZjNiMDFkMDRhNTdiIn0.FBCFbh8zuy8eWf4QhT_uam_tSS7t24blG6z-Z9Xd7H4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?tag_name=MyTag&amp;image_id=687f25a5-c7ae-4f4b-8ba7-3419d7b7573a&amp;album_id=00324000004ijWS</pre>

#### Query Parameters

<pre>tag_name: MyTag
image_id: 687f25a5-c7ae-4f4b-8ba7-3419d7b7573a
album_id: 00324000004ijWS</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTcsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiZjEyYjhjODktZmYzNS00YmVhLThmZGQtZjNiMDFkMDRhNTdiIn0.FBCFbh8zuy8eWf4QhT_uam_tSS7t24blG6z-Z9Xd7H4
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4dbff9c6-b353-41fc-8731-cd11634e31d1
X-Runtime: 0.218143
Content-Length: 1032</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"26c8676d-23a3-46ba-a99b-3799706b99d8","created_at":"2016-01-12T15:05:17.635+01:00","user":"f12b8c89-ff35-4bea-8fdd-f3b01d04a57b","image":{"public_id":"687f25a5-c7ae-4f4b-8ba7-3419d7b7573a","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:17.526+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"ddf997a6-4008-47e6-a403-51e53bb6e4f9","created_at":"2016-01-12T15:05:17.500+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
