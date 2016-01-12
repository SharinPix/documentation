# Organization API

## Retreive the organization

### GET /api/v1/organization
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI3ZTU0YWYxZS1mMjg1LTQ1NjktOTQxNC1hMDFiNmFhMTYwN2YifQ.N83FiPzKZXAOvhYm-rc9m3jPs18aNhlWa9QOwTlzXa4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/organization</pre>

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
X-access-stats: false
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTQsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI3ZTU0YWYxZS1mMjg1LTQ1NjktOTQxNC1hMDFiNmFhMTYwN2YifQ.N83FiPzKZXAOvhYm-rc9m3jPs18aNhlWa9QOwTlzXa4
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 3fe889c8-934b-49d6-9cc3-0144bc2bfa87
X-Runtime: 0.022019
Content-Length: 64</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"774f1897-bc47-4e97-acc0-a141bb7ad642","name":"SharinPix"}</pre>
