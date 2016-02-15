# Identify API

## Identify users

### POST /api/v1/images/:image_id/identify

### Parameters

Name : infos
Description : details of tagging

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5YWJlOTU5YS01OWU5LTQ1MzctYjM4Ni1jY2U5MjdmNzZiZGUifQ.V29uzFjvWTPW66BWQ5L_ga1BCmeVuqDz43QjGbPoqVk&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/images/6a0fac79-a632-4895-a1b5-2f8f61e377f0/identify</pre>

#### Body

<pre>infos[][user][additionalLabel]&infos[][user][description]&infos[][user][name]=1+Admin&infos[][user][photoUrl]=https%3A%2F%2Fc.eu5.content.force.com%2Fprofilephoto%2F005%2FT&infos[][user][recordId]=00524000001BB6HAAW&infos[][user][userType]=Internal&infos[][xCoord]=49.87146529562982&infos[][yCoord]=37.67123287671233&infos[][user][additionalLabel]&infos[][user][description]&infos[][user][name]=1+Admin&infos[][user][photoUrl]=https%3A%2F%2Fc.eu5.content.force.com%2Fprofilephoto%2F005%2FT&infos[][user][recordId]=00524000001BB6HAAW&infos[][user][userType]=Internal&infos[][xCoord]=49.87146529562982&infos[][yCoord]=37.67123287671233</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzgsImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI5YWJlOTU5YS01OWU5LTQ1MzctYjM4Ni1jY2U5MjdmNzZiZGUifQ.V29uzFjvWTPW66BWQ5L_ga1BCmeVuqDz43QjGbPoqVk
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 227e4b76-ddce-467b-96ac-b1deb0f7a01a
X-Runtime: 0.078808
Content-Length: 930</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"4c0e61f2-b48a-419e-bf6f-27cd7b350599","created_at":"2016-02-15T13:02:58.130+01:00","url":"https://localhost/identifies/4c0e61f2-b48a-419e-bf6f-27cd7b350599","image":{"public_id":"6a0fac79-a632-4895-a1b5-2f8f61e377f0","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["bcbbe986-d8e8-4cb7-bbdd-d45961519cf4"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2016-02-15T13:02:58.080+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"bcbbe986-d8e8-4cb7-bbdd-d45961519cf4","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}}</pre>
