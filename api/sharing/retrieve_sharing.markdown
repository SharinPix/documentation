# Sharing API

## retrieve sharing

### GET /api/v1/sharings/:id
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/sharings/9bc6ed7b-0705-4495-878a-a98d3a2eb886</pre>

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
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 6c0bdd49-40b2-4c98-8ba8-448ffe882deb
X-Runtime: 0.075973
Content-Length: 223</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"9bc6ed7b-0705-4495-878a-a98d3a2eb886","created_at":"2016-01-12T15:05:09.376+01:00","name":"sharing","label":"{\"en\": \"Homepage\", \"fr\": \"Page d'acceuil\"}","url":"/sharings/9bc6ed7b-0705-4495-878a-a98d3a2eb886"}</pre>
