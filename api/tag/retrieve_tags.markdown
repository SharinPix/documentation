# Tag API

## Retrieve tags

### GET api/v1/tags
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImM3ZWQxMmJmLWZkNTItNDVlMS04ZTk4LTg1MjMxMDM2MTBlNCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19fQ.BYHja_Dp5P3rWliBR8iFVlxLGCY8r3hIEPqzfLqgkiQ&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImM3ZWQxMmJmLWZkNTItNDVlMS04ZTk4LTg1MjMxMDM2MTBlNCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19fQ.BYHja_Dp5P3rWliBR8iFVlxLGCY8r3hIEPqzfLqgkiQ
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 41f06412-0ec9-453c-98c1-9f372a7ca4d2
X-Runtime: 0.011724
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 376</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "1e52ae0e-ae4d-4ac3-a3a9-d587a5bd4e52",
    "created_at": "2019-04-08T19:38:51.427+02:00",
    "name": "tag",
    "label": "{\"en\":\"tag\",\"fr\":\"tag\"}",
    "url": "/public_tags/1e52ae0e-ae4d-4ac3-a3a9-d587a5bd4e52",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": false,
    "color": "#03A9F4",
    "color_contrast": "#000000",
    "allow_download": false,
    "label_en": "tag",
    "label_fr": "tag"
  }
]</pre>
