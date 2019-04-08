# Import API

## Import from attachment

### POST /api/v1/imports

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album_id | Album name | false |  |
| filename | Image filename | false |  |
| import_type | Import type | false |  |
| metadatas | Image metadata | false |  |
| attachment_id | Salesforce attachment id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6ImY3NmNkOWQ3LTg1OWQtNGQzYi1iNjVlLWQ0ODE3ZGM5NmY1OCJ9.lGdKEApIZJj2cjQ7KYLtokP3cOkE18o-TEG5Tg7E3-0&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/imports</pre>

#### Body

<pre>album_id=5005800000HEXCtAAP&filename=Image123.jpg&import_type=salesforce&metadatas[attachmentId]=00P4I00000zyw3eUAA&attachment_id=00P4I00000zyw3eUAA</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywidXNlcl9pZCI6ImY3NmNkOWQ3LTg1OWQtNGQzYi1iNjVlLWQ0ODE3ZGM5NmY1OCJ9.lGdKEApIZJj2cjQ7KYLtokP3cOkE18o-TEG5Tg7E3-0
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 20e11784-6c4f-4f81-a530-4dcebe62cf4a
X-Runtime: 0.208305
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 498</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "ab445ced-80a2-4659-beaa-e1e9b28edee5",
  "organization_id": "91e4e020-bd76-4615-baf0-63263c5f3416",
  "image_id": null,
  "import_type": "salesforce",
  "album_id": "5005800000HEXCtAAP",
  "params": {
    "album_id": "5005800000HEXCtAAP",
    "filename": "Image123.jpg",
    "import_type": "salesforce",
    "metadatas": {
      "attachmentId": "00P4I00000zyw3eUAA"
    },
    "attachment_id": "00P4I00000zyw3eUAA",
    "controller": "api/v1/imports",
    "action": "create"
  },
  "created_at": "2019-04-08T19:38:57.787+02:00",
  "updated_at": "2019-04-08T19:38:57.787+02:00"
}</pre>
