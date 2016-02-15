# TagImage API

## retrieve tag images

### GET api/v1/tag_images

### Parameters

Name : tag_name
Description : name of the tag

Name : album_id
Description : id de l&#39;album

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMjIzNzI5OWQtZDBhYi00MWYxLTk5N2YtNDRmOGNlYjQwMTc1In0.gab7nCT-i-SQH-hTsAovvAjQxyP_eOttRU8RkznSxPA&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?tag_name=MyTag&amp;album_id=00324000004ijWS</pre>

#### Query Parameters

<pre>tag_name: MyTag
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMjIzNzI5OWQtZDBhYi00MWYxLTk5N2YtNDRmOGNlYjQwMTc1In0.gab7nCT-i-SQH-hTsAovvAjQxyP_eOttRU8RkznSxPA
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d34fe05a-82bf-448b-abc5-dffcf105abea
X-Runtime: 0.060052
Content-Length: 1032</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"cfeab5c7-14ac-4624-8a12-e2d11a81b6bd","created_at":"2016-02-15T13:02:55.887+01:00","user":"2237299d-d0ab-41f1-997f-44f8ceb40175","image":{"public_id":"025d75eb-2f90-4485-9c94-7d2d6a408241","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:55.833+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"dd9f9d66-0cf2-4ec9-9165-c034215f9974","created_at":"2016-02-15T13:02:55.827+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
