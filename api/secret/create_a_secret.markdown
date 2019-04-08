# Secret API

## Create a secret

### POST /api/v1/secret

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| name | Name of secret | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6IjIzZDEzNWIyLTJlMWQtNGUxYS1hZTc2LThlYzQxMzAwZDI0MSJ9.L_Pg70rxBR7_kpOYUOGEBDBu0eiRW2P5TiWfSNH9i78&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/secret</pre>

#### Body

<pre>name=Test+Secret</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6IjIzZDEzNWIyLTJlMWQtNGUxYS1hZTc2LThlYzQxMzAwZDI0MSJ9.L_Pg70rxBR7_kpOYUOGEBDBu0eiRW2P5TiWfSNH9i78
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f7ad29ea-4094-4a42-bba4-a9a600013127
X-Runtime: 0.012097
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 326</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "80275755-e620-43cc-9533-c7f46adb1e1c",
  "url": "sharinpix://80275755-e620-43cc-9533-c7f46adb1e1c:zLYOYTKOTUPfSbIYEp2QPGLlOj8BEsLtIDVJ4Q7UY41lcRA@localhost:5001/api/v1",
  "organization": {
    "id": "077203d9-3ffb-4391-b1e4-cfe161767e72",
    "name": "SharinPix-00D24000000IycKQWE (077203d9)",
    "sandbox": false,
    "sfid": "00D24000000IycKQWE"
  }
}</pre>
