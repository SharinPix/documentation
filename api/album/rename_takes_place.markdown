# Album API

## rename takes place

### PUT /api/v1/albums/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album | Album attributes | false |  |
| merge | Flag for merging album | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImM3OWNjYmI3LTMzYzEtNGIyMC04NjMyLTJmNmZmMDQzODMwZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMzEiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.Lkh2aINgjATaIaC7CMGET7CbMHfokGyloAIXdgXl9Dk&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/00100000123BB31</pre>

#### Body

<pre>album[public_id]=new_id</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImM3OWNjYmI3LTMzYzEtNGIyMC04NjMyLTJmNmZmMDQzODMwZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMzEiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.Lkh2aINgjATaIaC7CMGET7CbMHfokGyloAIXdgXl9Dk
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8f317a8f-4283-4c96-9dab-8ece64469a09
X-Runtime: 0.013643
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 161</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "new_id",
  "public_id": "new_id",
  "images_count": 0,
  "views_count": 0,
  "upload_form": null,
  "organization_id": "dcc77b9d-956c-439f-b75b-bcd44dad4753",
  "thumbnails": [

  ]
}</pre>
