# Cloudinary API

## Post an image

### POST api/v1/cloudinary?token=:token

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| raw_post | JSON as body. | false |  |

### Request

#### Headers

<pre>X-Cld-Timestamp: 1554745138
X-Cld-Signature: e6f7384f2901b3f625e8b895ff4625ce8cd2f370
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJmYjlhODllYy00YzUxLTQ5ZGYtYTEzNy0yNmI3OTVhMTZjNmIiLCJvcmdhbml6YXRpb25faWQiOiJjOWNiMjEyMi1hOGZiLTRkZDQtOWEwNy1hZTk1N2E0NmYzMjkiLCJhbGJ1bV9pZCI6IjEyMzQ1Njc4OSJ9.smC330c2Ww3JGxjCCLLhvWsPLeMXA3ND9uFsE7g3DS8</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJmYjlhODllYy00YzUxLTQ5ZGYtYTEzNy0yNmI3OTVhMTZjNmIiLCJvcmdhbml6YXRpb25faWQiOiJjOWNiMjEyMi1hOGZiLTRkZDQtOWEwNy1hZTk1N2E0NmYzMjkiLCJhbGJ1bV9pZCI6IjEyMzQ1Njc4OSJ9.smC330c2Ww3JGxjCCLLhvWsPLeMXA3ND9uFsE7g3DS8</pre>

#### Body

<pre>{"version":1507784418,"format":"jpg","resource_type":"image","type":"authenticated","original_filename":"Image","public_id":"twio1"}</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: text/html
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzksImlhdCI6MTU1NDc0NTEzOSwiaXNzIjoiZmI5YTg5ZWMtNGM1MS00OWRmLWExMzctMjZiNzk1YTE2YzZiIiwib3JnYW5pemF0aW9uX2lkIjoiYzljYjIxMjItYThmYi00ZGQ0LTlhMDctYWU5NTdhNDZmMzI5IiwiYWxidW1faWQiOiIxMjM0NTY3ODkifQ.NCUR-hCQhTyf5GIqcjhgRxbvZbJcJt_BmfOfeJa9zZk
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2d50af64-4f18-4405-b26e-697501c90f9f
X-Runtime: 0.031744
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>201 Created</pre>

