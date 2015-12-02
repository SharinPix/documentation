# Identify API

## Identify users

### POST /api/v1/images/:image_id/identify

### Parameters

Name : infos
Description : details of tagging

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NjksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI1YTdmN2QyMi01ZDYzLTRlOTItODM1MS04Yjk4NjNhODcyMjcifQ.PM0jwQLJSG3zipnwocSvcm80Tymc1pf-Noin7T643e8&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/images/b07d7eeb-dab1-41eb-978d-ea603592c617/identify</pre>

#### Body

<pre>infos[][user][additionalLabel]&infos[][user][description]&infos[][user][name]=1+Admin&infos[][user][photoUrl]=https%3A%2F%2Fc.eu5.content.force.com%2Fprofilephoto%2F005%2FT&infos[][user][recordId]=00524000001BB6HAAW&infos[][user][userType]=Internal&infos[][xCoord]=49.87146529562982&infos[][yCoord]=37.67123287671233&infos[][user][additionalLabel]&infos[][user][description]&infos[][user][name]=1+Admin&infos[][user][photoUrl]=https%3A%2F%2Fc.eu5.content.force.com%2Fprofilephoto%2F005%2FT&infos[][user][recordId]=00524000001BB6HAAW&infos[][user][userType]=Internal&infos[][xCoord]=49.87146529562982&infos[][yCoord]=37.67123287671233</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NjksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiI1YTdmN2QyMi01ZDYzLTRlOTItODM1MS04Yjk4NjNhODcyMjcifQ.PM0jwQLJSG3zipnwocSvcm80Tymc1pf-Noin7T643e8
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;61204cb54f95a680fee69e0781a918b4&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 0c8a47f5-0bf8-41db-b378-05aac2b7e0cb
X-Runtime: 0.086897
Content-Length: 930</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"id":"920772f9-6a81-489b-ad5b-8d6ef71be6a1","created_at":"2015-12-02T11:14:29.943+01:00","url":"https://localhost/identifies/920772f9-6a81-489b-ad5b-8d6ef71be6a1","image":{"public_id":"b07d7eeb-dab1-41eb-978d-ea603592c617","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["e2a176eb-724d-4ecc-8a3c-52d181580a2a"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:29.848+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"e2a176eb-724d-4ecc-8a3c-52d181580a2a","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}}}</pre>
