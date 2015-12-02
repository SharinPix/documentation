# Statistics API

## Retreive album platform user usage

### GET /api/v1/albums/:album_id/events/users_count

### Parameters

Name : group
Description : Group clause

Name : name
Description : Group clause

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJhOTQ1ZjRjYy1kZTc4LTQ0MjEtODQ1YS0zMDFjMDczYmI4MDYifQ.CmG5_57h2wS008E5BE_68oHQrRUfxjpfxokn7_T_I2c&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/8d987d01-4844-4871-88b2-c094fa5877bf/events/users_count?group=platform&amp;name=Viewed+Thumbnail</pre>

#### Query Parameters

<pre>group: platform
name: Viewed Thumbnail</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJhOTQ1ZjRjYy1kZTc4LTQ0MjEtODQ1YS0zMDFjMDczYmI4MDYifQ.CmG5_57h2wS008E5BE_68oHQrRUfxjpfxokn7_T_I2c
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;269b1dbf2a1f5add577b3c258bf7eef1&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f0b5a8f2-232d-40e0-968f-56a3ed4ba7e1
X-Runtime: 0.012172
Content-Length: 88</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"count":{"salesforce":1,"salesforce1":2,"unknown":1},"total":2,"unidentified_events":1}</pre>
