# Tag API

## retrieve tags

### GET api/v1/albums/:album_id/tags
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzEsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19LCJ1c2VyX2lkIjoiNzJhMjkyMzItOGJiMi00ODJhLWFlN2UtMzkyNzIyMTJkOWI4In0.qK1gs9pRu_d3xAfAe8Wb0XSKKihVy1c0no3ar9TowUs&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/albums/00324000004ijWS/tags</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzEsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19LCJ1c2VyX2lkIjoiNzJhMjkyMzItOGJiMi00ODJhLWFlN2UtMzkyNzIyMTJkOWI4In0.qK1gs9pRu_d3xAfAe8Wb0XSKKihVy1c0no3ar9TowUs
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;212a3c0fa70e97a8aa67468596a6d7d8&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2b93b69f-23a5-41d0-8ae1-e367c180ffd0
X-Runtime: 0.042624
Content-Length: 163</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"be1a4a59-43f5-4870-ae78-faaf5be7bf2d","created_at":"2015-12-02T11:14:31.268+01:00","name":"tag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}]</pre>
