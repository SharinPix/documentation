# Statistics API

## Retreive album activity

### GET /api/v1/albums/:id/events/activity

### Parameters

Name : events *- required -*
Description : Events names

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIxY2ZkYzE0OC01ODljLTQyNmMtYmE4ZS05MzkwM2JjZjMwNzgifQ.r9gXcZHhc8Vc02QcSOfaFyWDVAhw6NYRlW0Yonh8MRg&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/b9959759-0726-41c2-a186-7ff7ba7615c0/events/activity?events[]=Viewed+Image&amp;events[]=Viewed+Album&amp;events[]=Viewed+Publication&amp;events[]=Viewed+Thumbnail</pre>

#### Query Parameters

<pre>events: [&quot;Viewed Image&quot;, &quot;Viewed Album&quot;, &quot;Viewed Publication&quot;, &quot;Viewed Thumbnail&quot;]</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzUsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiIxY2ZkYzE0OC01ODljLTQyNmMtYmE4ZS05MzkwM2JjZjMwNzgifQ.r9gXcZHhc8Vc02QcSOfaFyWDVAhw6NYRlW0Yonh8MRg
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 37de7ac9-2a1f-4415-99e0-0ed8f709c634
X-Runtime: 0.029638
Content-Length: 616</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"name":"Viewed Publication","data":[["15/02/2016",2],["16/02/2016",0],["17/02/2016",2],["18/02/2016",0],["19/02/2016",0],["20/02/2016",0],["21/02/2016",1],["22/02/2016",3],["23/02/2016",1],["24/02/2016",1]]},{"name":"Viewed Image","data":[["15/02/2016",1],["16/02/2016",1],["17/02/2016",0],["18/02/2016",0],["19/02/2016",1],["20/02/2016",2],["21/02/2016",1],["22/02/2016",0],["23/02/2016",3],["24/02/2016",1]]},{"name":"Viewed Album","data":[["15/02/2016",1],["16/02/2016",0],["17/02/2016",0],["18/02/2016",2],["19/02/2016",0],["20/02/2016",1],["21/02/2016",1],["22/02/2016",0],["23/02/2016",0],["24/02/2016",0]]}]</pre>
