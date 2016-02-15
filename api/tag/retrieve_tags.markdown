# Tag API

## retrieve tags

### GET api/v1/albums/:album_id/tags
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19LCJ1c2VyX2lkIjoiMDJjNGFiZWEtNDNiMC00NzQ0LWExNDUtNGY2MGZkYmU2OWJkIn0.DTazx5_oVLYuLelfTPvGaK_zejz1lqXIIsNeP3lQ4AE&quot;
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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOiJ7XCJlblwiOiBcInRhZ3NcIiwgXCJmclwiOiBcInRhZ3MgZnJcIn0ifX19LCJ1c2VyX2lkIjoiMDJjNGFiZWEtNDNiMC00NzQ0LWExNDUtNGY2MGZkYmU2OWJkIn0.DTazx5_oVLYuLelfTPvGaK_zejz1lqXIIsNeP3lQ4AE
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 69b2e533-fcb0-4c00-92be-ac7ba301f5d1
X-Runtime: 0.061566
Content-Length: 163</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"6acd7bff-2ace-42d0-9e6e-e24fe3d75197","created_at":"2016-02-15T13:02:58.299+01:00","name":"tag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}]</pre>
