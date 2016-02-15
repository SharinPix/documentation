# Image API

## Retreive and image

### GET /api/v1/images/:id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyI5MTk2ZDFlYy02NTQyLTQ2NjItYmFjZS01NjljYTU0OTE1MDkiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiI5NWI5ZGUwNi03ZTIzLTQ0N2ItYTFlMi00NzkyMDdjYzk1YTEifQ.uYpO0XtXvIqcCaNEin7pEtqG4zsipF0fAFnfklw5J9E&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/72412189-1cb2-4ae7-a2f0-f1ce55e9009c</pre>

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
X-access-crop: false
X-access-rotate: false
X-access-duplicate: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyI5MTk2ZDFlYy02NTQyLTQ2NjItYmFjZS01NjljYTU0OTE1MDkiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiI5NWI5ZGUwNi03ZTIzLTQ0N2ItYTFlMi00NzkyMDdjYzk1YTEifQ.uYpO0XtXvIqcCaNEin7pEtqG4zsipF0fAFnfklw5J9E
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f8a7be4f-368c-450f-a47b-eb0d62f692f5
X-Runtime: 0.046458
Content-Length: 757</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"72412189-1cb2-4ae7-a2f0-f1ce55e9009c","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["9196d1ec-6542-4662-bace-569ca5491509"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:58.731+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"9196d1ec-6542-4662-bace-569ca5491509","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}</pre>
