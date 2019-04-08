# Einstein Prediction API

## Create Einstein Prediction failed

### POST /api/v1/einstein_prediction

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| imageId | Image id | false |  |
| modelId | Einstein Model Salesforce Id (18 chars) | false |  |
| imageId | Image id | false |  |
| modelId | Einstein Model Salesforce Id (18 chars) | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjAwZGU1YjYyLWZjMDEtNDEwYy1iNzlmLWYwNjc2NTQwM2VjYyIsImFiaWxpdGllcyI6e319.PWNj1rPds9d2MrRldbrxFhA9UykFCxcymyN6DeGCzQc&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/einstein_prediction</pre>

#### Body

<pre>imageId=a4311328-d6d7-4f1c-8fb2-a10a7262b4df&modelId=modelid</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjAwZGU1YjYyLWZjMDEtNDEwYy1iNzlmLWYwNjc2NTQwM2VjYyIsImFiaWxpdGllcyI6e319.PWNj1rPds9d2MrRldbrxFhA9UykFCxcymyN6DeGCzQc
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: fd784c7c-513c-490e-8d64-54ef90ba0c2d
X-Runtime: 0.025773
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 204</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "einstein_model_id": "878f6554-80ac-4994-99ab-52910dbd0fbe",
  "probability": null,
  "status": null,
  "image_id": "a4311328-d6d7-4f1c-8fb2-a10a7262b4df",
  "model_id": "modelid",
  "type": "image-detection",
  "message": null
}</pre>
