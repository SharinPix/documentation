# Clipboard API

## Create a existing clipboard

### POST /api/v1/clipboards

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| id | Id of clipboard | false |  |
| image_ids | List of image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhYmlsaXRpZXMiOnsiMDAxMDAwMDAxMjNCQjIzNiI6eyJBY2Nlc3MiOnsiaW1hZ2VfY29weSI6dHJ1ZX19fSwiaXNzIjoiNTU5ODA3NTgtZTcyOC00MTM4LWFlNDUtNzI0ZGY3NTA3MGY2In0.TwIT4MSUhmDFkGO1RjNLfP4_r2WdrNEtkefD7RQIE7w&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/clipboards</pre>

#### Body

<pre>id=4d595b76-a3a8-437a-95ca-6ebc1a244d69&image_ids[]=e71de0cc-fee9-41f7-a300-c9aa07448402&image_ids[]=94f5afc7-6715-4860-acd6-c226500f459f&image_ids[]=8cbac8ee-ae1a-4ecb-862f-9d8682621381</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDIsImlhdCI6MTU1NDc0NTE0MiwiaXNzIjoiNTU5ODA3NTgtZTcyOC00MTM4LWFlNDUtNzI0ZGY3NTA3MGY2IiwiYWJpbGl0aWVzIjp7IjAwMTAwMDAwMTIzQkIyMzYiOnsiQWNjZXNzIjp7ImltYWdlX2NvcHkiOnRydWV9fX19.Yi4OTDMlojXBu6eD6SK-SQOO2coT9UFjnq29PFUGwXY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 15f339c8-8cc5-4acb-bbbd-99fb762a5937
X-Runtime: 0.011029
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 162</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "4d595b76-a3a8-437a-95ca-6ebc1a244d69",
  "user_id": null,
  "organization_id": "4d69a649-135c-44c7-a918-31dc119513cb",
  "created_at": "2019-04-08T19:39:02.815+02:00"
}</pre>
