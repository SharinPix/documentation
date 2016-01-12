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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTcsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMjhjMTVlZGItYzEyNS00ZWZiLWFiODMtN2EzNDczMzYwNmM3In0.QIttA545PFc8gJMvK-wroDZl4J3PueYeBZwAhu43GfQ&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiMjhjMTVlZGItYzEyNS00ZWZiLWFiODMtN2EzNDczMzYwNmM3In0.ie-gWSlkhmCv1yG2Rjdlp7uWUpBTXL3JxMxu9sFm8Dw
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4e22da7d-7447-4803-8707-0676b6a88b1d
X-Runtime: 0.054466
Content-Length: 1032</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"c22463ce-cda7-49c3-857c-2bdb1dca2343","created_at":"2016-01-12T15:05:18.031+01:00","user":"28c15edb-c125-4efb-ab83-7a34733606c7","image":{"public_id":"342078e1-9849-42ea-983c-073b444a6f01","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:17.969+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"417da649-1dfc-43ab-8538-4db9f37e9725","created_at":"2016-01-12T15:05:17.954+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
