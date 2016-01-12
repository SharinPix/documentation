# Statistics API

## Retreive album platform user usage

### GET /api/v1/publications/:publication_id/events/users_count

### Parameters

Name : group
Description : Group clause

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlYTAwNjVhNi1hMzE2LTQyYTAtYTRlNy0xYWZmZTU5N2E2NWEifQ.rsPw8edzaollGYDFuNFVRxzRnBQeyEzn4bkmtB8Wz8I&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/publications/82ec40c4-e2b5-4efa-94ee-4f37cd137939/events/users_count?group=platform</pre>

#### Query Parameters

<pre>group: platform</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlYTAwNjVhNi1hMzE2LTQyYTAtYTRlNy0xYWZmZTU5N2E2NWEifQ.rsPw8edzaollGYDFuNFVRxzRnBQeyEzn4bkmtB8Wz8I
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: a5ff43cd-19f4-4ed1-8d9a-c2f60c86741f
X-Runtime: 0.043338
Content-Length: 88</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"count":{"salesforce":1,"salesforce1":2,"unknown":1},"total":2,"unidentified_events":1}</pre>
