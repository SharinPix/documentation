# Tag API

## Returns autocomplete tags for einstein tags

### GET api/v1/tags/autocomplete

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| q | Search request for tags where listed false for einstein | false |  |
| filters | tag attribute | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzAsImlhdCI6MTU1NDc0NTEzMCwidXNlcl9pZCI6IjVmMjQxMGEzLTRlNTYtNDBlOS1iZWFlLTIwMTM4YTRkZDFiMCIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImNyZWF0ZSI6dHJ1ZX19fQ.NYPYaBnzWEbr5t15_Zc11WT4eIhPhmycZYBja-B5BQs&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags/autocomplete?q=uper&amp;filters=%7B+%22listed%22%3A+false+%7D</pre>

#### Query Parameters

<pre>q: uper
filters: { &quot;listed&quot;: false }</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6IjVmMjQxMGEzLTRlNTYtNDBlOS1iZWFlLTIwMTM4YTRkZDFiMCIsImFiaWxpdGllcyI6eyJ0YWdzIjp7ImNyZWF0ZSI6dHJ1ZX19fQ.r_WxSxAewfrOfbZUO1x_gzE1jwJZtN6Xmym5lLb_ij8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 7820c850-51a4-4553-b0ac-18d22e1044d3
X-Runtime: 0.021228
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
    "id": "44cddfcc-83fe-42f4-82aa-813d3e20a093",
    "name": "Super tag",
    "color": "#2196F3",
    "color_contrast": "#ffffff",
    "label_en": "Super tag",
    "label_fr": "Super tag"
  }
]</pre>
