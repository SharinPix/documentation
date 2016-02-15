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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyJjNjI3ZDA0NS05Mzc3LTRiMTQtYTIzMS00MmFlYzZiYTg5ZjkiOnsiQWNjZXNzIjp7ImltYWdlX2Nyb3AiOnRydWV9fX0sInVzZXJfaWQiOiIyMzA5ZjgxMi00MjgyLTQ1MjctYjk2ZC0xOTVhY2Y0ZTFkNzEifQ.Cr86721UDM-PyLuQZ4JOzM9ohT6WXycQnO0TkqOUvas&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/877ae5ec-f365-4afb-b17c-107ae087199a</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyJjNjI3ZDA0NS05Mzc3LTRiMTQtYTIzMS00MmFlYzZiYTg5ZjkiOnsiQWNjZXNzIjp7ImltYWdlX2Nyb3AiOnRydWV9fX0sInVzZXJfaWQiOiIyMzA5ZjgxMi00MjgyLTQ1MjctYjk2ZC0xOTVhY2Y0ZTFkNzEifQ.Cr86721UDM-PyLuQZ4JOzM9ohT6WXycQnO0TkqOUvas
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ac8b9353-6c6e-46c1-9b56-640e20fd3fda
X-Runtime: 0.020390
Content-Length: 759</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"877ae5ec-f365-4afb-b17c-107ae087199a","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["c627d045-9377-4b14-a231-42aec6ba89f9"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:58.401+01:00","width":10,"height":11,"rotation":0,"crop_x":3.0,"crop_y":2.0,"crop_w":10.0,"crop_h":11.0,"album_id":"c627d045-9377-4b14-a231-42aec6ba89f9","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
