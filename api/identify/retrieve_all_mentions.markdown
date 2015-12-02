# Identify API

## Retrieve all mentions

### GET /api/v1/mentions

### Parameters

Name : id
Description : publication id

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzAsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJmMTVlYjNmMS05MzQ1LTRmY2ItYTNmZS1mZjgyOTQ4ZThkZmIifQ._R_9rw5HPDEOJGwTBvmkrOrXcSeuDxVMmijg6h60-Eo&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/mentions?id=0b08da03-4528-4db0-a872-27b19db2ccb3</pre>

#### Query Parameters

<pre>id: 0b08da03-4528-4db0-a872-27b19db2ccb3</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzAsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJmMTVlYjNmMS05MzQ1LTRmY2ItYTNmZS1mZjgyOTQ4ZThkZmIifQ._R_9rw5HPDEOJGwTBvmkrOrXcSeuDxVMmijg6h60-Eo
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;d751713988987e9331980363e24189ce&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 29014e88-486a-4d40-a78f-6b0d872ff9d0
X-Runtime: 0.030768
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
