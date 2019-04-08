# EinsteinBox API

## Update an existing box

### PUT /api/v1/einstein_box/:id

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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6ImEwZTM2MGI1LWE5ZWUtNGIyMi1iODYxLWMwZTc3MzNjMmMxYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjg0Ijp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.OOataPMQtQmGkVvPo6Ovgc_9LgjHCjZJiP7294O9qAI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/einstein_box/31ae6402-0cea-498e-b576-7e64a8d01e1f</pre>

#### Body

<pre>label=door&left=10&top=20&width=25&height=40</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6ImEwZTM2MGI1LWE5ZWUtNGIyMi1iODYxLWMwZTc3MzNjMmMxYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjg0Ijp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.OOataPMQtQmGkVvPo6Ovgc_9LgjHCjZJiP7294O9qAI
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 55fe5c8a-0e2d-4f44-ad9e-fea9c3832048
X-Runtime: 0.020446
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
  "id": "31ae6402-0cea-498e-b576-7e64a8d01e1f",
  "label": "door",
  "width": "25.0",
  "height": "40.0",
  "left": "10.0",
  "top": "20.0",
  "tag_id": "e98fb500-fc30-4cf2-b352-fd9da346d109",
  "image_id": "2036c08c-67b2-44e4-ad4f-bd1554829d5d",
  "probability": null
}</pre>
