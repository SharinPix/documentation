# EinsteinBox API

## Create a new box

### POST /api/v1/images/:image_id/einstein_box

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| label | Label of the box | false |  |
| left | x coordinate of the box in percentage | false |  |
| top | y coordinate of the box in percentage | false |  |
| width | Width of the box in percentage | false |  |
| height | Height of the box in percentage | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6Ijk4MDcwZDNmLWRjN2UtNGFhNC1iYjNkLTYyYTFmNzUzMjE0ZiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjg4Ijp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.gYSUVzdkNZ6W_IGZbIxuoU3xWtWnwKIVC51JXck3NWo&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/images/9c2cb45b-3226-4344-aece-e03c9def5975/einstein_box</pre>

#### Body

<pre>label=door&left=10&top=20&width=25&height=40</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6Ijk4MDcwZDNmLWRjN2UtNGFhNC1iYjNkLTYyYTFmNzUzMjE0ZiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjg4Ijp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.gYSUVzdkNZ6W_IGZbIxuoU3xWtWnwKIVC51JXck3NWo
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 09c27db3-f333-4f46-908a-08dca037ad5c
X-Runtime: 0.022105
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 235</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "3c9a1d8a-d6b1-45d7-8dd3-2cd785e1102d",
  "label": "door",
  "width": "25.0",
  "height": "40.0",
  "left": "10.0",
  "top": "20.0",
  "tag_id": "91e1d3fa-c099-492c-98d7-b4c5693bc3b7",
  "image_id": "9c2cb45b-3226-4344-aece-e03c9def5975",
  "probability": null
}</pre>
