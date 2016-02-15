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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzYsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiZGZiZGQzN2QtZWY0Mi00NjhlLWJhNjktZmJjMzQ2N2JlMWRmIn0.MC6kvTeQP7bGfuiiVZjLkzG_NHqmxmr0dB4tHXBtmvM&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?tag_name=MyTag&amp;image_id=d8a5ed41-300c-4f99-8621-ca4c4b73fd73&amp;album_id=00324000004ijWS</pre>

#### Query Parameters

<pre>tag_name: MyTag
image_id: d8a5ed41-300c-4f99-8621-ca4c4b73fd73
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzYsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6IkNhcnRvb25zIiwiZnIiOiJEw6lzc2luIGFuaW3DqSJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19LCJ1c2VyX2lkIjoiZGZiZGQzN2QtZWY0Mi00NjhlLWJhNjktZmJjMzQ2N2JlMWRmIn0.MC6kvTeQP7bGfuiiVZjLkzG_NHqmxmr0dB4tHXBtmvM
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 35ef01d5-0c92-443c-8b3a-9ddc6994f14a
X-Runtime: 0.024691
Content-Length: 1032</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"eb81b7c8-2b20-4762-a4af-f0d952bd4dfb","created_at":"2016-02-15T13:02:56.233+01:00","user":"dfbdd37d-ef42-468e-ba69-fbc3467be1df","image":{"public_id":"d8a5ed41-300c-4f99-8621-ca4c4b73fd73","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:56.190+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"6892e79f-6463-46c3-b3f6-17aeef7ce614","created_at":"2016-02-15T13:02:56.182+01:00","name":"MyTag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
