# Image API

## Rotate an image

### PUT /api/v1/images/:id

### Parameters

Name : rotation
Description : Image payload

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyJmNTRiZTJjMC1hMzYwLTQzNGUtOGZlOC1iNjVhZmRhMzZiZDMiOnsiQWNjZXNzIjp7ImltYWdlX3JvdGF0ZSI6dHJ1ZX19fSwidXNlcl9pZCI6IjEwYTA2NDIxLTRiMWItNGZhNC1iN2E5LTllMWJjZjA4YTlhZSJ9.0wA0j8KXGiSJUK1J7Nbn2NEGxwWBefkIB5YCaxkaDd8&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/4d39dbe4-b24b-4a0c-a21d-b6fcf83b336a</pre>

#### Body

<pre>rotation=90</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyJmNTRiZTJjMC1hMzYwLTQzNGUtOGZlOC1iNjVhZmRhMzZiZDMiOnsiQWNjZXNzIjp7ImltYWdlX3JvdGF0ZSI6dHJ1ZX19fSwidXNlcl9pZCI6IjEwYTA2NDIxLTRiMWItNGZhNC1iN2E5LTllMWJjZjA4YTlhZSJ9.0wA0j8KXGiSJUK1J7Nbn2NEGxwWBefkIB5YCaxkaDd8
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;5ca212b3f039a4dc7e35b12a6ce216c3&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8056b0e6-ecef-4b4e-baba-fa3cd4a82ed7
X-Runtime: 0.012917
Content-Length: 758</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"4d39dbe4-b24b-4a0c-a21d-b6fcf83b336a","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["f54be2c0-a360-434e-8fe8-b65afda36bd3"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:34.959+01:00","width":48,"height":48,"rotation":90,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"f54be2c0-a360-434e-8fe8-b65afda36bd3","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
