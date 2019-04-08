# EinsteinBox API

## Retrieve all einstein boxes on an image

### GET /api/v1/images/:image_id/einstein_box
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6ImVmNzYwMWYyLTBjMzAtNDEwMy04MTYxLTA3NmM2MDc2YmU0ZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjkwIjp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.qU42eoHLras-iwcU4oZVKLRUUexjj2LNTSciNnqKSHs&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/b9b13e9b-df50-4a38-8c8e-92e3b75fffe8/einstein_box</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6ImVmNzYwMWYyLTBjMzAtNDEwMy04MTYxLTA3NmM2MDc2YmU0ZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjkwIjp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImVpbnN0ZWluX2JveCI6dHJ1ZX19fX0.qU42eoHLras-iwcU4oZVKLRUUexjj2LNTSciNnqKSHs
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 1550bc3e-fd0c-4c47-a5c3-b840a469cbe4
X-Runtime: 0.008295
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
    "id": "dac6fb96-3425-4211-bc01-4101064bb0a1",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "13bd4ff9-c628-469c-8452-7d06dc3cbe0e",
    "image_id": "b9b13e9b-df50-4a38-8c8e-92e3b75fffe8",
    "probability": null
  },
  {
    "id": "a5b4fe51-9698-4c47-a4f5-eb8246fab8f5",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "13bd4ff9-c628-469c-8452-7d06dc3cbe0e",
    "image_id": "b9b13e9b-df50-4a38-8c8e-92e3b75fffe8",
    "probability": null
  },
  {
    "id": "95fc5a8b-df7b-4211-a962-9ca0e26d7e70",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "13bd4ff9-c628-469c-8452-7d06dc3cbe0e",
    "image_id": "b9b13e9b-df50-4a38-8c8e-92e3b75fffe8",
    "probability": null
  },
  {
    "id": "d97b7fd7-973e-445e-9aed-444177fcad61",
    "label": "door",
    "width": "10.0",
    "height": "20.0",
    "left": "30.0",
    "top": "40.0",
    "tag_id": "13bd4ff9-c628-469c-8452-7d06dc3cbe0e",
    "image_id": "b9b13e9b-df50-4a38-8c8e-92e3b75fffe8",
    "probability": null
  }
]</pre>
