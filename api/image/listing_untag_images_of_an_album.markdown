# Image API

## Listing untag images of an album

### GET /api/v1/albums/:id/images/untag
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNVRYaklBQVciOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIyODc2Mzg3Yi00ZmJiLTRmYzQtOGE1OS00NTk3ZjA4MzRjZWUifQ.mnwI7K_lGPFRNTdcB8MhRGuOSrvCR1mQq84tU4mJCOE&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00324000005TXjIAAW/images/untag</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNVRYaklBQVciOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIyODc2Mzg3Yi00ZmJiLTRmYzQtOGE1OS00NTk3ZjA4MzRjZWUifQ.mnwI7K_lGPFRNTdcB8MhRGuOSrvCR1mQq84tU4mJCOE
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 733a08d2-6a7a-45dd-8105-a5fcba42c058
X-Runtime: 0.044874
Content-Length: 723</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"b0e70413-fc59-4684-b120-da7043bbafc1","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000005TXjIAAW"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:14.857+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000005TXjIAAW","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]</pre>
