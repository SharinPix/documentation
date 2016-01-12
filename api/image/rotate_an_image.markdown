# Image API

## Rotate an image

### PUT /api/v1/images/:id

### Parameters

Name : rotation
Description : Image payload

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6eyJjMzAwYWEyNC01YzYzLTRmNmItYjExMS1kZmExMGNiNDdiOGYiOnsiQWNjZXNzIjp7ImltYWdlX3JvdGF0ZSI6dHJ1ZX19fSwidXNlcl9pZCI6ImJkNzY1OTUxLTYwZTktNDBhNi05MDhkLTdmZTY1ODNkYzQ1MiJ9.uLXpdClqQYIXSUH50HM5iNRPYq-wpRJDS-DG9nAZoFI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/52c01312-320c-404a-a19c-0fae235ccf49</pre>

#### Body

<pre>rotation=90</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTUsImFiaWxpdGllcyI6eyJjMzAwYWEyNC01YzYzLTRmNmItYjExMS1kZmExMGNiNDdiOGYiOnsiQWNjZXNzIjp7ImltYWdlX3JvdGF0ZSI6dHJ1ZX19fSwidXNlcl9pZCI6ImJkNzY1OTUxLTYwZTktNDBhNi05MDhkLTdmZTY1ODNkYzQ1MiJ9.Oen9tUj7W_x2Aqmj7RIE4BQ19XBbjr5qhZM3uabGMUs
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4cdc3162-1258-4a13-9329-149fd4e8bc5d
X-Runtime: 0.062404
Content-Length: 758</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"52c01312-320c-404a-a19c-0fae235ccf49","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["c300aa24-5c63-4f6b-b111-dfa10cb47b8f"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-01-12T15:05:15.000+01:00","width":48,"height":48,"rotation":90,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"c300aa24-5c63-4f6b-b111-dfa10cb47b8f","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
