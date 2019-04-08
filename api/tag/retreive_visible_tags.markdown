# Tag API

## Retreive visible tags

### GET api/v1/tags

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| visible | Should we filter visible tags | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6IjY1NjIxYTU5LThjZWYtNGJhMC04NDg0LTU1NDc2MjI3MTUyYyIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImNyZWF0ZSI6InRydWUifX19.DIHoNr1p14XOGS6k_5ygBfDLqWdvdw5QrZfGOjwU0H4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags?visible=true</pre>

#### Query Parameters

<pre>visible: true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6IjY1NjIxYTU5LThjZWYtNGJhMC04NDg0LTU1NDc2MjI3MTUyYyIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImNyZWF0ZSI6InRydWUifX19.DIHoNr1p14XOGS6k_5ygBfDLqWdvdw5QrZfGOjwU0H4
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2a49cb80-bcb8-4d10-b57d-16251316b4f2
X-Runtime: 0.009737
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 829</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "c8273df8-60bc-4a37-b934-a7796ce83035",
    "created_at": "2019-04-08T19:38:51.521+02:00",
    "name": "Super Tag 3",
    "label": "{\"en\":\"Super Tag 3\",\"fr\":\"Super Tag 3\"}",
    "url": "/public_tags/c8273df8-60bc-4a37-b934-a7796ce83035",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": true,
    "color": "#00BCD4",
    "color_contrast": "#000000",
    "allow_download": false,
    "label_en": "Super Tag 3",
    "label_fr": "Super Tag 3"
  },
  {
    "id": "f8b78db6-7ea9-4e4d-81da-6814ba0a59e9",
    "created_at": "2019-04-08T19:38:51.524+02:00",
    "name": "Super Tag 4",
    "label": "{\"en\":\"Super Tag 4\",\"fr\":\"Super Tag 4\"}",
    "url": "/public_tags/f8b78db6-7ea9-4e4d-81da-6814ba0a59e9",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": true,
    "color": "#FF5722",
    "color_contrast": "#000000",
    "allow_download": false,
    "label_en": "Super Tag 4",
    "label_fr": "Super Tag 4"
  }
]</pre>
