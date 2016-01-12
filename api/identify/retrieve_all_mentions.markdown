# Identify API

## Retrieve all mentions

### GET /api/v1/mentions

### Parameters

Name : id
Description : publication id

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTYsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI4MzJjNWVhMC1iMzQ4LTQ3NDktODhhZS1jOGIwOGExZjg3MTAifQ.wxQ_y3mf0jApsLQGczaBMUH_jp50Lp0TVNiCHC_6NDo&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/mentions?id=7dfdc589-bbd8-48d7-8507-a08b190ea082</pre>

#### Query Parameters

<pre>id: 7dfdc589-bbd8-48d7-8507-a08b190ea082</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTcsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI4MzJjNWVhMC1iMzQ4LTQ3NDktODhhZS1jOGIwOGExZjg3MTAifQ.lEnrnUAiRNcBjZJmgMfQe3x-7htmGJYHsowcYav54wk
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 60b69499-e4bc-4a33-8de2-1db4971f72bb
X-Runtime: 0.034695
Content-Length: 2</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[]</pre>
