# Trashed images API

## Retrieve deleted images in album

### GET api/v1/trashed_images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhYmlsaXRpZXMiOnsiMDAxMDAwMDAxMjNCQjE5MiI6eyJBY2Nlc3MiOnsidHJhc2giOnRydWV9fX0sImlzcyI6ImJkMWNmZTBjLTMwZDAtNDY2Yi1hYzFmLWRmNDJjZWNkYjQzMyJ9.YJb3gQUBKC9CWewfT4RchQIVcTgvJCYbWuvHzoKal0I&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/trashed_images</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzcsImlhdCI6MTU1NDc0NTEzNywiaXNzIjoiYmQxY2ZlMGMtMzBkMC00NjZiLWFjMWYtZGY0MmNlY2RiNDMzIiwiYWJpbGl0aWVzIjp7IjAwMTAwMDAwMTIzQkIxOTIiOnsiQWNjZXNzIjp7InRyYXNoIjp0cnVlfX19fQ.MexCWk7ILMzJT3vJvSZoe7I-IUD99ZvMuFRU0c4r514
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 56c2b366-c8e7-495d-9831-b2b82c105676
X-Runtime: 0.013903
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 301</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "fcf09eb0-cfd2-49d8-ab44-4c61f426dfa4",
    "deleted_at": "2019-04-08T19:38:57.116+02:00",
    "thumbnail_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--f2R8AlJp--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/cd11056defab.jpg"
  }
]</pre>
