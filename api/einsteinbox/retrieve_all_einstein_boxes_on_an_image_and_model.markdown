# EinsteinBox API

## Retrieve all einstein boxes on an image and model

### GET /api/v1/images/:image_id/einstein_box

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_id | Image id | false |  |
| model_id | Model Id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6IjM2NzllZTAzLTljZjktNGViNC05M2Q2LTMyOTlkMjA1ODhhYyIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjgwIjp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.n3AHgnF9cd2v_uiSFELBPgiEGPnwjS6NZXglslS4ITM&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/90c6dffb-439f-473a-b993-d58bb25571e4/einstein_box?model_id=xxx</pre>

#### Query Parameters

<pre>model_id: xxx</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6IjM2NzllZTAzLTljZjktNGViNC05M2Q2LTMyOTlkMjA1ODhhYyIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjgwIjp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.n3AHgnF9cd2v_uiSFELBPgiEGPnwjS6NZXglslS4ITM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 1901b4a6-763c-4f91-9b07-f1f564a273dd
X-Runtime: 0.014963
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 945</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "3ea82444-9a80-492a-b5a5-9fef41abcf7a",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "1c4bad8b-1d7f-477e-8cf7-78523bb8cff0",
    "image_id": "90c6dffb-439f-473a-b993-d58bb25571e4",
    "probability": null
  },
  {
    "id": "31decbbf-c575-4d5c-89b3-ed3ab3d59d16",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "1c4bad8b-1d7f-477e-8cf7-78523bb8cff0",
    "image_id": "90c6dffb-439f-473a-b993-d58bb25571e4",
    "probability": null
  },
  {
    "id": "8f904fa3-0d21-45a6-8aed-1f5ee8358495",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "1c4bad8b-1d7f-477e-8cf7-78523bb8cff0",
    "image_id": "90c6dffb-439f-473a-b993-d58bb25571e4",
    "probability": null
  },
  {
    "id": "e4e9240f-f2bf-47b4-a215-f4843141e77e",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "1c4bad8b-1d7f-477e-8cf7-78523bb8cff0",
    "image_id": "90c6dffb-439f-473a-b993-d58bb25571e4",
    "probability": null
  }
]</pre>
