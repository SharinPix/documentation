# Tag API

## Create public tag

### POST api/v1/tags

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| name | Name of the tag | false |  |
| label | Label of the tag | false |  |
| listed | Allow tag to be listed - Boolean value | false |  |
| public | Allow tag to be available publicly - Boolean value | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjE1NjkxMjA5LWU3YWMtNDEyOS05YTcyLWM4OTBlNDIyOWFmNiIsImFiaWxpdGllcyI6eyJhbWF6aW5nX2lkIjp7IkFjY2VzcyI6eyJzaGFyZSI6dHJ1ZX19fX0.izOZ9nvkVeHxrCx0klKXP0zwT9LikMaDwK59gPn4oDM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/tags</pre>

#### Body

<pre>name=Super+Tag&listed=false&public=true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjE1NjkxMjA5LWU3YWMtNDEyOS05YTcyLWM4OTBlNDIyOWFmNiIsImFiaWxpdGllcyI6eyJhbWF6aW5nX2lkIjp7IkFjY2VzcyI6eyJzaGFyZSI6dHJ1ZX19fX0.izOZ9nvkVeHxrCx0klKXP0zwT9LikMaDwK59gPn4oDM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 60e84870-ffd4-4fea-824c-6eb331d1b351
X-Runtime: 0.013327
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 404</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "b5ab0712-3e8f-4cd1-a3f2-aa100001345a",
  "created_at": "2019-04-08T19:38:50.698+02:00",
  "name": "super-tag",
  "label": "{\"en\":\"Super Tag\",\"fr\":\"Super Tag\"}",
  "url": "/public_tags/b5ab0712-3e8f-4cd1-a3f2-aa100001345a",
  "public": true,
  "listed": false,
  "action": {
    "actions": [

    ]
  },
  "visible": false,
  "color": "#2196F3",
  "color_contrast": "#ffffff",
  "allow_download": false,
  "label_en": "Super Tag",
  "label_fr": "Super Tag"
}</pre>
