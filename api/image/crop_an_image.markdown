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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyI2YzA4Y2U0Ni00NWZkLTRhOTYtYjU0Mi0xYWU1ZDIzNmY4MTgiOnsiQWNjZXNzIjp7ImltYWdlX2Nyb3AiOnRydWV9fX0sInVzZXJfaWQiOiJmZmQ3N2Q2ZC0xZGYwLTQ2MjMtYTY4ZC00NzA4OWUwZmUwOGEifQ.e263F_-rKJ9RJjK-3QbN5CaccjJkZ3C31In1MxLwtME&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/eea38232-8017-458d-8e3c-1c218dedeb36</pre>

#### Body

<pre>rotation=0&crop_x=3&crop_y=2&crop_w=10&crop_h=11</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyI2YzA4Y2U0Ni00NWZkLTRhOTYtYjU0Mi0xYWU1ZDIzNmY4MTgiOnsiQWNjZXNzIjp7ImltYWdlX2Nyb3AiOnRydWV9fX0sInVzZXJfaWQiOiJmZmQ3N2Q2ZC0xZGYwLTQ2MjMtYTY4ZC00NzA4OWUwZmUwOGEifQ.e263F_-rKJ9RJjK-3QbN5CaccjJkZ3C31In1MxLwtME
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;d8af263708a0ec0b21b52823f85ff7ee&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 887299ba-97bf-4425-ad53-5df710c19e59
X-Runtime: 0.019460
Content-Length: 759</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"eea38232-8017-458d-8e3c-1c218dedeb36","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["6c08ce46-45fd-4a96-b542-1ae5d236f818"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:34.410+01:00","width":10,"height":11,"rotation":0,"crop_x":3.0,"crop_y":2.0,"crop_w":10.0,"crop_h":11.0,"album_id":"6c08ce46-45fd-4a96-b542-1ae5d236f818","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
