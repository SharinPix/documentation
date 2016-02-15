# Image API

## Listing untag images of an album

### GET /api/v1/albums/:id/images/untag
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNVRYaklBQVciOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIyMGFiNDJmNC05MzA4LTQyOTctYTVmMC1jMGMwN2QxZDE4OWIifQ.gVxoPg0RPytz4L_lyH6zSCPLrNo68vXVBiHdoBUGPW0&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNVRYaklBQVciOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiIyMGFiNDJmNC05MzA4LTQyOTctYTVmMC1jMGMwN2QxZDE4OWIifQ.gVxoPg0RPytz4L_lyH6zSCPLrNo68vXVBiHdoBUGPW0
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: b7f7faf2-ab83-4f0c-9f49-dba22362e911
X-Runtime: 0.015579
Content-Length: 723</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"public_id":"078fafdc-f05a-44c4-94df-c04244c7cda4","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000005TXjIAAW"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:58.531+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000005TXjIAAW","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}]</pre>
