# Album API

## Retrieve stats

### GET /api/v1/albums/:id/einstein_box_stats
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJlaW5zdGVpbiI6dHJ1ZSwiaXNzIjoiZDAzNjk0YWMtZTQ3Yy00ZWYyLTg3MzMtOTlmMTRhOTgzYWNmIn0.uXIgu9160s-_tIpmLABVPpW84GYEogKkASL_116_-DY&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/datasetsfid/einstein_box_stats</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwiaXNzIjoiZDAzNjk0YWMtZTQ3Yy00ZWYyLTg3MzMtOTlmMTRhOTgzYWNmIiwiZWluc3RlaW4iOnRydWV9.Vy3OmMTIK4v-SdaZVcYqFk6KuWpClbwNrhCqDLGAjWY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 70575eda-8354-4f56-a851-22f883911a10
X-Runtime: 0.006740
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 19</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "completed": false
}</pre>
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJlaW5zdGVpbiI6dHJ1ZSwiaXNzIjoiZDAzNjk0YWMtZTQ3Yy00ZWYyLTg3MzMtOTlmMTRhOTgzYWNmIn0.uXIgu9160s-_tIpmLABVPpW84GYEogKkASL_116_-DY&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/datasetsfid/einstein_box_stats</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwiaXNzIjoiZDAzNjk0YWMtZTQ3Yy00ZWYyLTg3MzMtOTlmMTRhOTgzYWNmIiwiZWluc3RlaW4iOnRydWV9.Vy3OmMTIK4v-SdaZVcYqFk6KuWpClbwNrhCqDLGAjWY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: fd4bdda0-713c-4be9-863e-5233b2c12240
X-Runtime: 0.006076
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 89</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "completed": true,
  "stats": [
    {
      "label": "Building",
      "count": 4
    },
    {
      "label": "Cartoon",
      "count": 6
    }
  ]
}</pre>
