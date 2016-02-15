# Statistics API

## Retreive album platform user usage

### GET /api/v1/publications/:publication_id/events/users_count

### Parameters

Name : group
Description : Group clause

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkOTMyNTI5Ny1kNjhmLTRhOGUtYmQwNi1iZTNhNTNhNzAwNGMifQ.Df9IpnS2iQ8KfLFD04FyeQX6GAE2BIGnb1T4RCjd8Bg&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/publications/c9c28e4d-7a8b-4604-8411-598422d099b0/events/users_count?group=platform</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJkOTMyNTI5Ny1kNjhmLTRhOGUtYmQwNi1iZTNhNTNhNzAwNGMifQ.Df9IpnS2iQ8KfLFD04FyeQX6GAE2BIGnb1T4RCjd8Bg
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: da501cc0-9f36-432d-8ef4-7f138c023396
X-Runtime: 0.024985
Content-Length: 88</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"count":{"salesforce":1,"salesforce1":2,"unknown":1},"total":2,"unidentified_events":1}</pre>
