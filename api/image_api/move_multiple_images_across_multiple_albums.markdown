# Image API API

## Move multiple images across multiple albums

### POST api/v1/images/move

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| move_operations |  move operations | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzMsImlhdCI6MTU1NDc0NTEzMywidXNlcl9pZCI6Ijg3MTc1MTM5LTc1YzctNDA5OC05NWVmLTI2YTc4MjA1ODYxZiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTM4Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.-cMETU0Y09ThEkpP3RuKVQx31pIGcqUxtJSeZu19JW8&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/images/move</pre>

#### Body

<pre>move_operations[0ac224ff-8147-4f11-8c21-c86a92cd9276]=00100000123BB140&move_operations[d91c7f6a-3e72-4f4f-af11-0259d3016c1b]=00100000123BB140&move_operations[5643d050-2e5d-47cc-a381-0d911a8ab7e9]=00100000123BB141&move_operations[c33035bd-d812-4f8c-924e-4d856b47d921]=custom_id</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzMsImlhdCI6MTU1NDc0NTEzMywidXNlcl9pZCI6Ijg3MTc1MTM5LTc1YzctNDA5OC05NWVmLTI2YTc4MjA1ODYxZiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTM4Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.-cMETU0Y09ThEkpP3RuKVQx31pIGcqUxtJSeZu19JW8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 78eb0434-6c4c-487f-8967-6a5c73f06b83
X-Runtime: 0.166340
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 157</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  "c33035bd-d812-4f8c-924e-4d856b47d921",
  "5643d050-2e5d-47cc-a381-0d911a8ab7e9",
  "d91c7f6a-3e72-4f4f-af11-0259d3016c1b",
  "0ac224ff-8147-4f11-8c21-c86a92cd9276"
]</pre>
