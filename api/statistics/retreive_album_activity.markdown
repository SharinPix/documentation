# Statistics API

## Retreive album activity

### GET /api/v1/albums/:id/events/count

### Parameters

Name : group *- required -*
Description : Group clause

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJjNjkwYjFmNS1hMzEzLTRhNDktYjExZi0zZjMzMjA2MTBjNTAifQ.l-1lZbSo2EAosn89JVKbqDcLPn8gir89vR6DAlbKqP8&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/233fbe7a-a4bf-46d7-babd-eba12b2af13c/events/count?group=name</pre>

#### Query Parameters

<pre>group: name</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJjNjkwYjFmNS1hMzEzLTRhNDktYjExZi0zZjMzMjA2MTBjNTAifQ.l-1lZbSo2EAosn89JVKbqDcLPn8gir89vR6DAlbKqP8
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;317f7b5cb2e37f8133f24407da967114&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: af26babf-c992-4160-a7a5-b20cca964115
X-Runtime: 0.008383
Content-Length: 35</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"Viewed Album":3,"Viewed Image":1}</pre>
