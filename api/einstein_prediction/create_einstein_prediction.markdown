# Einstein Prediction API

## Create Einstein Prediction

### POST /api/v1/einstein_prediction

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| imageId | Image id | false |  |
| modelId | Einstein Model Salesforce Id (18 chars) | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6ImQ4Yjg5NGE2LThmYTktNGExZi04MzE4LTgwZDljMjNiOWVmNSIsImFiaWxpdGllcyI6e319.ZYO7D_IFQNazgt_LtTmEqSlpKksKNxVJzqE2AL_qYDg&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/einstein_prediction</pre>

#### Body

<pre>imageId=02aaa59a-94ef-4788-bf27-1c8819dc529b&modelId=modelid</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6ImQ4Yjg5NGE2LThmYTktNGExZi04MzE4LTgwZDljMjNiOWVmNSIsImFiaWxpdGllcyI6e319.ZYO7D_IFQNazgt_LtTmEqSlpKksKNxVJzqE2AL_qYDg
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: b4dcf3e0-2f56-4dd6-be79-7d71c920fa93
X-Runtime: 0.048468
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
  "einstein_model_id": "0347de92-32c2-4516-8200-be6831bc7433",
  "probability": null,
  "status": null,
  "image_id": "02aaa59a-94ef-4788-bf27-1c8819dc529b",
  "model_id": "modelid",
  "type": "image-detection",
  "message": null
}</pre>
