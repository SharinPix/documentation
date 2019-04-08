# Import API

## Import from content document

### POST /api/v1/imports

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album_id | Album name | false |  |
| filename | Image filename | false |  |
| import_type | Import type | false |  |
| metadatas | Image metadata | false |  |
| content_document_id | Salesforce ContentDocument id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzgsImlhdCI6MTU1NDc0NTEzOCwidXNlcl9pZCI6ImYxOTAwYmJhLWUzMzktNGRjOS04N2RmLTlkYzg2NjVhZGVhZCJ9.HAPJrWiZS7loLXuxCM-WzoFwAqSsyup58EyLBVtAflA&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/imports</pre>

#### Body

<pre>album_id=5005800000HEXCtAAP&filename=Image456.jpg&import_type=salesforce&metadatas[contentDocumentId]=0694I000008HV8MQAW&content_document_id=0694I000008HV8MQAW</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzgsImlhdCI6MTU1NDc0NTEzOCwidXNlcl9pZCI6ImYxOTAwYmJhLWUzMzktNGRjOS04N2RmLTlkYzg2NjVhZGVhZCJ9.HAPJrWiZS7loLXuxCM-WzoFwAqSsyup58EyLBVtAflA
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: fa057bb6-d3cf-4427-8b65-b4d14d83bcb8
X-Runtime: 0.287917
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 509</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "3d172b54-f40f-4df9-9342-0b042fac5382",
  "organization_id": "2cb9eb0f-038c-4fa9-a4e8-aba57b177a83",
  "image_id": null,
  "import_type": "salesforce",
  "album_id": "5005800000HEXCtAAP",
  "params": {
    "album_id": "5005800000HEXCtAAP",
    "filename": "Image456.jpg",
    "import_type": "salesforce",
    "metadatas": {
      "contentDocumentId": "0694I000008HV8MQAW"
    },
    "content_document_id": "0694I000008HV8MQAW",
    "controller": "api/v1/imports",
    "action": "create"
  },
  "created_at": "2019-04-08T19:38:58.041+02:00",
  "updated_at": "2019-04-08T19:38:58.041+02:00"
}</pre>
