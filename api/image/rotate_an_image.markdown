# Image API

## Rotate an image

### PUT /api/v1/images/:id

### Parameters

Name : rotation
Description : Image payload

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6eyJhZmZhNjBkNi03MmI2LTQ1ZGQtYTk0Ny02OTkxMGZiMTk5M2QiOnsiQWNjZXNzIjp7ImltYWdlX3JvdGF0ZSI6dHJ1ZX19fSwidXNlcl9pZCI6IjY0NjRiYzczLTU3MjUtNDYyMi05OGI2LTM1N2Q0ZTRkMTI5OSJ9.2rI4EHq7O6BC_NWsYQFWcn3kSDDtw58cHnclKAa0PnE&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/81240a45-bce4-4cb5-9606-6a132ea3d153</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6eyJhZmZhNjBkNi03MmI2LTQ1ZGQtYTk0Ny02OTkxMGZiMTk5M2QiOnsiQWNjZXNzIjp7ImltYWdlX3JvdGF0ZSI6dHJ1ZX19fSwidXNlcl9pZCI6IjY0NjRiYzczLTU3MjUtNDYyMi05OGI2LTM1N2Q0ZTRkMTI5OSJ9.2rI4EHq7O6BC_NWsYQFWcn3kSDDtw58cHnclKAa0PnE
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: def03bfc-8fe3-4bf1-8278-aab3352e800e
X-Runtime: 0.019744
Content-Length: 758</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"81240a45-bce4-4cb5-9606-6a132ea3d153","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["affa60d6-72b6-45dd-a947-69910fb1993d"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:59.415+01:00","width":48,"height":48,"rotation":90,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"affa60d6-72b6-45dd-a947-69910fb1993d","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
