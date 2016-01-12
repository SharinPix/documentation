# Tag API

## retrieve tags

### GET api/v1/albums/:album_id/tags
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTMsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19LCJ1c2VyX2lkIjoiYmIxZDg4NTgtMDcxOS00YjZiLWIwNzAtZTJmY2RlNGI0Mzc4In0.hX3TrFCZseMk0KER8dBfStAWj7moVsUhhVTacd00Slw&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/albums/00324000004ijWS/tags</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store, must-revalidate, private, max-age=0
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTMsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19LCJ1c2VyX2lkIjoiYmIxZDg4NTgtMDcxOS00YjZiLWIwNzAtZTJmY2RlNGI0Mzc4In0.hX3TrFCZseMk0KER8dBfStAWj7moVsUhhVTacd00Slw
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 0022d74e-2207-4dab-8903-500010790338
X-Runtime: 0.049119
Content-Length: 163</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"9126e145-f1cc-494a-b66d-86eca0bfa47a","created_at":"2016-01-12T15:05:13.752+01:00","name":"tag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}]</pre>
