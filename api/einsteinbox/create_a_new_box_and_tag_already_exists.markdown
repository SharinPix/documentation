# EinsteinBox API

## Create a new box and tag already exists

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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6IjhlNjg1ZmM5LTRlYTQtNDY1OS05MzdhLTk1ODYyOGY2MjJlYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjg2Ijp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.LxhLx5yuE9aOppuJACgOex_1h-tVtT2U-RPMMN79-CI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/images/a834db4c-8d12-48f4-a83e-755e4e1a0284/einstein_box</pre>

#### Body

<pre>label=door&left=10&top=20&width=25&height=40</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6IjhlNjg1ZmM5LTRlYTQtNDY1OS05MzdhLTk1ODYyOGY2MjJlYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjg2Ijp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.LxhLx5yuE9aOppuJACgOex_1h-tVtT2U-RPMMN79-CI
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: da2a9e62-b9d8-40cf-ba7d-452a7f67cc79
X-Runtime: 0.021337
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 239</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "a4051fce-88de-4e29-91cc-c66876890eb2",
  "label": "doorbell",
  "width": "25.0",
  "height": "40.0",
  "left": "10.0",
  "top": "20.0",
  "tag_id": "15e08fb5-f491-4e6b-9d79-e9bc70cef204",
  "image_id": "a834db4c-8d12-48f4-a83e-755e4e1a0284",
  "probability": null
}</pre>
