# SharingImage API

## retreive sharing images

### GET api/v1/sharings/:sharing_id/sharing_images
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/sharings/af400126-1cfa-48e9-9d9e-086dd8fcc09f/sharing_images</pre>

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
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 5e173224-51fb-40dc-9d3a-643389993d7f
X-Runtime: 0.066679
Content-Length: 616</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"519f8cf1-ce0d-4255-aa5b-9b5648839e9a","created_at":"2016-01-12T15:05:18.892+01:00","url":"/sharing_images/519f8cf1-ce0d-4255-aa5b-9b5648839e9a/image","user":"16414764-add0-4ba0-bc3c-2e0dcd312bcb","image":{"infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"public_id":"323d60b9-b6ea-4378-b70f-2b01254dcf78","width":48,"height":48,"rotation":0,"album_id":"00324000004ijWS"}}]</pre>
