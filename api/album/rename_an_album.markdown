# Album API

## Rename an album

### PUT /api/v1/albums/:id

### Parameters

Name : album
Description : new album attributes

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTksImFiaWxpdGllcyI6eyJkMGExNDkyMC01ZDIxLTQ5ZmItYWEwNy05M2U3NTlhN2NiMWIiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fSwidXNlcl9pZCI6Ijc5MmU2M2ZlLThiYTgtNDEwYi1iNmFlLTI2OWQzYjk2ZDBlZiJ9.tIeiCfNeIlT4BUjsCIMsHPGTapLjxV2PZg0IxRm8PHM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/d0a14920-5d21-49fb-aa07-93e759a7cb1b</pre>

#### Body

<pre>album[public_id]=newid</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store, must-revalidate, private, max-age=0
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTksImFiaWxpdGllcyI6eyJkMGExNDkyMC01ZDIxLTQ5ZmItYWEwNy05M2U3NTlhN2NiMWIiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fSwidXNlcl9pZCI6Ijc5MmU2M2ZlLThiYTgtNDEwYi1iNmFlLTI2OWQzYjk2ZDBlZiJ9.tIeiCfNeIlT4BUjsCIMsHPGTapLjxV2PZg0IxRm8PHM
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 14a86545-076e-42f0-a9ee-a09548ea6b2b
X-Runtime: 0.047629
Content-Length: 89</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"newid","upload_form":null,"images_count":0,"views_count":0,"thumbnails":[]}</pre>
