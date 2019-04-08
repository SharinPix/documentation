# Tag API

## update public tag with download allowed

### PUT api/v1/tags/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| allow_download | boolean value | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6IjMwOTZlNWI5LWMzNmQtNDU0Yy1hN2U4LTllNDM2ZTdiMzA4ZCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiQWNjZXNzIjp7InNoYXJlIjp0cnVlfX19fQ.ONp010MXCEFBjx06aHxnXLoLOf3q4t16AXb0r5LEXzI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT api/v1/tags/841d26f9-ea66-4be7-a61c-415703571dce</pre>

#### Body

<pre>allow_download=true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6IjMwOTZlNWI5LWMzNmQtNDU0Yy1hN2U4LTllNDM2ZTdiMzA4ZCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiQWNjZXNzIjp7InNoYXJlIjp0cnVlfX19fQ.ONp010MXCEFBjx06aHxnXLoLOf3q4t16AXb0r5LEXzI
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e262f40f-0d05-4b6d-b064-440ce00ad10a
X-Runtime: 0.010907
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 373</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "841d26f9-ea66-4be7-a61c-415703571dce",
  "created_at": "2019-04-08T19:38:51.572+02:00",
  "name": "tag",
  "label": "{\"en\":\"tag\",\"fr\":\"tag\"}",
  "url": "/public_tags/841d26f9-ea66-4be7-a61c-415703571dce",
  "public": true,
  "listed": false,
  "action": {
    "actions": [

    ]
  },
  "visible": false,
  "color": "#00BCD4",
  "color_contrast": "#000000",
  "allow_download": true,
  "label_en": "tag",
  "label_fr": "tag"
}</pre>
