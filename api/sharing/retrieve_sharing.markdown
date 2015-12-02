# Sharing API

## retrieve sharing

### GET /api/v1/sharings/:id
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/sharings/22f4a582-24ff-4ccf-af87-57079275ab4f</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;9d84293e417adfcc70e61051377cadb1&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: aeae4f81-3c36-4f4a-ad9d-65c98d58257d
X-Runtime: 0.005824
Content-Length: 223</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"22f4a582-24ff-4ccf-af87-57079275ab4f","created_at":"2015-12-02T11:14:30.562+01:00","name":"sharing","label":"{\"en\": \"Homepage\", \"fr\": \"Page d'acceuil\"}","url":"/sharings/22f4a582-24ff-4ccf-af87-57079275ab4f"}</pre>
