# Statistics API

## Retreive album activity

### GET /api/v1/albums/:id/events/activity

### Parameters

Name : events *- required -*
Description : Events names

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTIsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlZTZmZmE5Mi05MDc2LTRjYmMtOTJmYi1hYjdlZGEwMDZiZWEifQ.RX2me6vK4JHTjcOGMdZ3Gb2VAm4xQK__rNDp3-5DhLw&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/ae5c0465-aee7-4ade-bb61-74601df80719/events/activity?events[]=Viewed+Image&amp;events[]=Viewed+Album&amp;events[]=Viewed+Publication&amp;events[]=Viewed+Thumbnail</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTMsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJlZTZmZmE5Mi05MDc2LTRjYmMtOTJmYi1hYjdlZGEwMDZiZWEifQ.m8RHTwxEiCfhPDFRrqZXOYd0Pjw3O_M-_hYBbIJgBVU
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 1605f710-0847-4b02-88db-81280716e70c
X-Runtime: 0.126060
Content-Length: 616</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"name":"Viewed Publication","data":[["12/01/2016",2],["13/01/2016",0],["14/01/2016",1],["15/01/2016",0],["16/01/2016",2],["17/01/2016",1],["18/01/2016",1],["19/01/2016",1],["20/01/2016",0],["21/01/2016",2]]},{"name":"Viewed Album","data":[["12/01/2016",1],["13/01/2016",0],["14/01/2016",1],["15/01/2016",1],["16/01/2016",0],["17/01/2016",1],["18/01/2016",0],["19/01/2016",0],["20/01/2016",1],["21/01/2016",0]]},{"name":"Viewed Image","data":[["12/01/2016",1],["13/01/2016",2],["14/01/2016",0],["15/01/2016",1],["16/01/2016",1],["17/01/2016",2],["18/01/2016",0],["19/01/2016",1],["20/01/2016",1],["21/01/2016",1]]}]</pre>
