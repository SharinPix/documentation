# Einstein Prediction API

## Create Einstein Prediction with large image format

### POST /api/v1/einstein_prediction

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| imageId | Image id | false |  |
| modelId | Einstein Model Salesforce Id (18 chars) | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6ImM3MDNjNThlLWRiODUtNDAzNC05ZDdmLTk0NTYzMjMwZjNiMCIsImFiaWxpdGllcyI6e319.0WgStspGTbQzcstGV_qb1sW_tKpB7o9c5slrjdvLf3Y&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/einstein_prediction</pre>

#### Body

<pre>imageId=30a21c56-a3ee-4a0e-8302-8816b03c4788&modelId=modelid</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6ImM3MDNjNThlLWRiODUtNDAzNC05ZDdmLTk0NTYzMjMwZjNiMCIsImFiaWxpdGllcyI6e319.0WgStspGTbQzcstGV_qb1sW_tKpB7o9c5slrjdvLf3Y
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: c6197a00-5e08-4bb1-a477-83b99638d55a
X-Runtime: 0.032367
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
  "einstein_model_id": "57b6dcad-f7d9-4404-8154-5ae7cea3c819",
  "probability": null,
  "status": null,
  "image_id": "30a21c56-a3ee-4a0e-8302-8816b03c4788",
  "model_id": "modelid",
  "type": "image-detection",
  "message": null
}</pre>
