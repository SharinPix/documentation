# TokenGenerator API

## generate token from abilities

### POST api/v1/token

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| permission | permission | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImY1NTFhMWNiLTkzMGUtNDUwMS04N2E5LWY1MWEwNzE4ZGEzZSJ9.KjujWpRJg0qy5ELjixs_3MW_rHjp77U9LuncVexJIO4&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/token</pre>

#### Body

<pre>permission=%7B%22abilities%22%3A%7B%22album_id%22%3A%7B%22Access%22%3A%7B%22see%22%3Atrue%2C%22image_list%22%3Atrue%2C%22image_upload%22%3Atrue%2C%22image_delete%22%3Atrue%2C%22fullscreen%22%3Atrue%2C%22image_caption%22%3Atrue%7D%7D%2C%22tags%22%3A%7B%22auto_tag%22%3A%22test%22%7D%7D%2C%22Id%22%3A%22album_id%22%7D</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImY1NTFhMWNiLTkzMGUtNDUwMS04N2E5LWY1MWEwNzE4ZGEzZSJ9.KjujWpRJg0qy5ELjixs_3MW_rHjp77U9LuncVexJIO4
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 59b75418-bbf5-4c52-b8f9-970fed25e456
X-Runtime: 0.007622
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 485</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImY1NTFhMWNiLTkzMGUtNDUwMS04N2E5LWY1MWEwNzE4ZGEzZSIsImFiaWxpdGllcyI6eyJhbGJ1bV9pZCI6eyJBY2Nlc3MiOnsic2VlIjp0cnVlLCJpbWFnZV9saXN0Ijp0cnVlLCJpbWFnZV91cGxvYWQiOnRydWUsImltYWdlX2RlbGV0ZSI6dHJ1ZSwiZnVsbHNjcmVlbiI6dHJ1ZSwiaW1hZ2VfY2FwdGlvbiI6dHJ1ZX19LCJ0YWdzIjp7ImF1dG9fdGFnIjoidGVzdCJ9fSwiSWQiOiJhbGJ1bV9pZCJ9.LYLpDGpnGZkq1Cyx90dmOnYsEpWdGf5EvPOFdFuyvQc",
  "endpoint": "localhost:5001"
}</pre>
