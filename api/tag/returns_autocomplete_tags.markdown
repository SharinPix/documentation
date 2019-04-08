# Tag API

## Returns autocomplete tags

### GET api/v1/tags/autocomplete

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| q | Search request for tags | false |  |
| filters | tag attribute | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImRjYWZjYzkzLTQ2NTktNGVmZS04YzgzLTUwNGE0MDU2NmM2ZSIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImNyZWF0ZSI6dHJ1ZX19fQ.B9rKA4ehYckbCHBf4q-yvN5dwpdFG89hggbiGi_TOnU&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags/autocomplete?q=uper&amp;filters=%7B+%22listed%22%3A+true+%7D</pre>

#### Query Parameters

<pre>q: uper
filters: { &quot;listed&quot;: true }</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImRjYWZjYzkzLTQ2NTktNGVmZS04YzgzLTUwNGE0MDU2NmM2ZSIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImNyZWF0ZSI6dHJ1ZX19fQ.B9rKA4ehYckbCHBf4q-yvN5dwpdFG89hggbiGi_TOnU
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 83f393ee-3298-40b4-b9c7-1c057d6c25ef
X-Runtime: 0.017722
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 157</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "e9f8b58c-0d25-48d6-ae82-d3faeb6a3a82",
    "name": "Super tag",
    "color": "#FFC107",
    "color_contrast": "#000000",
    "label_en": "Super tag",
    "label_fr": "Super tag"
  }
]</pre>
