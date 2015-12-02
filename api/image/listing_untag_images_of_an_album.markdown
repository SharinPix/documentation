# Image API

## Listing untag images of an album

### GET /api/v1/albums/:id/images/untag
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNVRYaklBQVciOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIwNWY4MWJjYi00MWE5LTRmMTctYmU1Ni03M2ZlMjg5ZDY1ZGEifQ.1QY7NrxhBJoGMaK_di7Iow8Qlps0Kq2yjJ5KjajL98U&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00324000005TXjIAAW/images/untag</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNVRYaklBQVciOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIwNWY4MWJjYi00MWE5LTRmMTctYmU1Ni03M2ZlMjg5ZDY1ZGEifQ.1QY7NrxhBJoGMaK_di7Iow8Qlps0Kq2yjJ5KjajL98U
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;577c602ba94affb480c7cade583f399c&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: a05f73ea-8be1-4349-8601-b28c12f021d7
X-Runtime: 0.015540
Content-Length: 723</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"f669efb5-df49-4de0-86ee-a25d63cc1715","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000005TXjIAAW"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:34.680+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000005TXjIAAW","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]</pre>
