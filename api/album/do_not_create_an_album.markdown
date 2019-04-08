# Album API

## do not create an album

### PUT /api/v1/albums/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album | Album attributes | false |  |
| merge | Flag for merging album | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImI4MGQxNzEyLTdiYjEtNDMwNy04ODdhLTY0NWM0Yjk5Y2I2NSIsImFiaWxpdGllcyI6e319.ZheCOZPhKxx9aPZ4xT2ahflyNwxuwRp5TKOzQVdGf9I&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/idonotexists</pre>

#### Body

<pre>album[public_id]=new_id</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: text/html
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImI4MGQxNzEyLTdiYjEtNDMwNy04ODdhLTY0NWM0Yjk5Y2I2NSIsImFiaWxpdGllcyI6e319.ZheCOZPhKxx9aPZ4xT2ahflyNwxuwRp5TKOzQVdGf9I
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d7dc4165-43e9-49a6-8c32-a8c4ead2a85c
X-Runtime: 0.006010
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>200 OK</pre>

