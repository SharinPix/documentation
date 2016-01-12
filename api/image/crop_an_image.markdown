# Image API

## Crop an image

### PUT /api/v1/images/:id

### Parameters

Name : rotation
Description : Image rotation

Name : crop_x
Description : Image crop x

Name : crop_y
Description : Image crop y

Name : crop_w
Description : Image crop w

Name : crop_h
Description : Image crop h

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6eyJlODU1MjhkNS04MzA0LTRiNGYtYWUwYS01MWUxNGIxNmYxOTciOnsiQWNjZXNzIjp7ImltYWdlX2Nyb3AiOnRydWV9fX0sInVzZXJfaWQiOiJmZjNlOThhMC1kNzFlLTQyNDMtYmY2MS1hNTE1MjMwODkwYWIifQ.iVAstMeGqgMl2B6Ei2g40ux6QoOutps_6w-LsABPglk&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/437212ba-4727-4995-8377-5e85d94542fb</pre>

#### Body

<pre>rotation=0&crop_x=3&crop_y=2&crop_w=10&crop_h=11</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6eyJlODU1MjhkNS04MzA0LTRiNGYtYWUwYS01MWUxNGIxNmYxOTciOnsiQWNjZXNzIjp7ImltYWdlX2Nyb3AiOnRydWV9fX0sInVzZXJfaWQiOiJmZjNlOThhMC1kNzFlLTQyNDMtYmY2MS1hNTE1MjMwODkwYWIifQ.iVAstMeGqgMl2B6Ei2g40ux6QoOutps_6w-LsABPglk
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 779f50c0-c5a1-44af-86a9-3a5646da2c30
X-Runtime: 0.042566
Content-Length: 759</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"437212ba-4727-4995-8377-5e85d94542fb","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e85528d5-8304-4b4f-ae0a-51e14b16f197"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:14.709+01:00","width":10,"height":11,"rotation":0,"crop_x":3.0,"crop_y":2.0,"crop_w":10.0,"crop_h":11.0,"album_id":"e85528d5-8304-4b4f-ae0a-51e14b16f197","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
