# SharingImage API

## create sharing images

### POST /api/v1/sharings/:sharing_id/sharing_images

### Parameters

Name : image_ids
Description : id of images

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiU2hhcmluZ3MiOnsic2hhcmluZyI6IntcImVuXCI6IFwiSG9tZXBhZ2VcIiwgXCJmclwiOiBcIlBhZ2UgZCdhY2NldWlsXCJ9In19fSwidXNlcl9pZCI6IjM1NWI1ZjExLWYxYWUtNDIxMi04MjRhLWFmNzdkYzhmNGJiZiJ9.LmKa9Pw5ByOSWvL4i7-EjYtyG4enXJSy2YfAT9t20yI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/sharings/b30d7017-d303-48e0-bee8-7cd95711996c/sharing_images</pre>

#### Body

<pre>image_ids[]=6203cd9f-557d-4a50-ae0d-a6e5fcd7a274&image_ids[]=4de66731-b35b-435c-8d41-c1d9d680a183&image_ids[]=499cd954-722a-4877-be8e-24d8ec4bd171</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzUsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiU2hhcmluZ3MiOnsic2hhcmluZyI6IntcImVuXCI6IFwiSG9tZXBhZ2VcIiwgXCJmclwiOiBcIlBhZ2UgZCdhY2NldWlsXCJ9In19fSwidXNlcl9pZCI6IjM1NWI1ZjExLWYxYWUtNDIxMi04MjRhLWFmNzdkYzhmNGJiZiJ9.LmKa9Pw5ByOSWvL4i7-EjYtyG4enXJSy2YfAT9t20yI
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;ce2e8743d59fea45070952024f9864ad&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d9d331af-cb03-4396-93c8-30fc4bf7b737
X-Runtime: 0.080203
Content-Length: 1846</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"0e97c59e-0c09-40c2-b23b-05ba65d43ec1","created_at":"2015-12-02T11:14:35.324+01:00","url":"/sharing_images/0e97c59e-0c09-40c2-b23b-05ba65d43ec1/image","user":"355b5f11-f1ae-4212-824a-af77dc8f4bbf","image":{"infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"public_id":"6203cd9f-557d-4a50-ae0d-a6e5fcd7a274","width":48,"height":48,"rotation":0,"album_id":"00324000004ijWS"}},{"id":"fe6a9195-3147-4f73-a579-404df9c0bbcf","created_at":"2015-12-02T11:14:35.333+01:00","url":"/sharing_images/fe6a9195-3147-4f73-a579-404df9c0bbcf/image","user":"355b5f11-f1ae-4212-824a-af77dc8f4bbf","image":{"infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"public_id":"4de66731-b35b-435c-8d41-c1d9d680a183","width":48,"height":48,"rotation":0,"album_id":"00324000004ijWS"}},{"id":"10e08a8b-19b6-4975-80b6-584333c47d8c","created_at":"2015-12-02T11:14:35.342+01:00","url":"/sharing_images/10e08a8b-19b6-4975-80b6-584333c47d8c/image","user":"355b5f11-f1ae-4212-824a-af77dc8f4bbf","image":{"infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"public_id":"499cd954-722a-4877-be8e-24d8ec4bd171","width":48,"height":48,"rotation":0,"album_id":"00324000004ijWS"}}]</pre>
