# Tag API

## Create the tag

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

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjFhNTg4ZDViLTdlYjMtNGE1ZS1iMjQ0LWM5MjQ1YWFjMmE2MCIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImF1dG9fdGFnIjoic3VwZXItYXV0by10YWcifX19.I-ZWG4KbIlRNTWhHfPgaYIiRkleaimaKSCDik1dKnSM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/tags</pre>

#### Body

<pre>name=super-auto-tag&listed=true&public=false</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjFhNTg4ZDViLTdlYjMtNGE1ZS1iMjQ0LWM5MjQ1YWFjMmE2MCIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImF1dG9fdGFnIjoic3VwZXItYXV0by10YWcifX19.I-ZWG4KbIlRNTWhHfPgaYIiRkleaimaKSCDik1dKnSM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ac27f6fd-fdf1-4769-829d-d94d1ff9ea38
X-Runtime: 0.012237
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 429</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "24694aaa-c19e-4932-923c-e185872380ff",
  "created_at": "2019-04-08T19:38:50.745+02:00",
  "name": "super-auto-tag",
  "label": "{\"en\":\"super-auto-tag\",\"fr\":\"super-auto-tag\"}",
  "url": "/public_tags/24694aaa-c19e-4932-923c-e185872380ff",
  "public": false,
  "listed": true,
  "action": {
    "actions": [

    ]
  },
  "visible": false,
  "color": "#9C27B0",
  "color_contrast": "#ffffff",
  "allow_download": false,
  "label_en": "super-auto-tag",
  "label_fr": "super-auto-tag"
}</pre>
