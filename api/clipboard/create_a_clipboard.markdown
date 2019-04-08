# Clipboard API

## Create a clipboard

### POST /api/v1/clipboards

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| id | Id of clipboard | false |  |
| image_ids | List of image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjA3Y2Q4Yjg3LTVkNDAtNDgzMC05YThjLWMwNjM3MTM4Yjg4ZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjM4Ijp7IkFjY2VzcyI6eyJpbWFnZV9jb3B5Ijp0cnVlfX19fQ.Oznnv3R9_C-3A4rpw7TAfhghbr4XKxdjHZzdN6AocfM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/clipboards</pre>

#### Body

<pre>id=4d595b76-a3a8-437a-95ca-6ebc1a244d69&image_ids[]=81d1f8f0-0e44-4a4f-b347-f0d6c8049d3d&image_ids[]=bcf7c2ee-d27c-416a-8bfa-0592eb51f976&image_ids[]=deb377ba-7c22-49d7-8164-9affd2ede1ac</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6IjA3Y2Q4Yjg3LTVkNDAtNDgzMC05YThjLWMwNjM3MTM4Yjg4ZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjM4Ijp7IkFjY2VzcyI6eyJpbWFnZV9jb3B5Ijp0cnVlfX19fQ.Oznnv3R9_C-3A4rpw7TAfhghbr4XKxdjHZzdN6AocfM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8503be5a-eb22-47b5-a00e-95c23d476b2c
X-Runtime: 0.028411
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 196</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "4d595b76-a3a8-437a-95ca-6ebc1a244d69",
  "user_id": "07cd8b87-5d40-4830-9a8c-c0637138b88d",
  "organization_id": "c6ecce03-09d3-431c-af6b-177340add98d",
  "created_at": "2019-04-08T19:39:03.040+02:00"
}</pre>
