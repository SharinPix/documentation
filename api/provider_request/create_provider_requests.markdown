# Provider request API

## create provider requests

### POST /api/v1/providers/:provider_id/provider_requests

### Parameters

Name : image_ids
Description : id of images

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiOTI1ZmJhNzMtOTg0NC00NDkzLWIwMWQtZDE0NWVkZDAwMTNjIn0.ynjOD9j9LuZqGIYbGDSGpMvHAq-sF9A7BzOoM4DVUGI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/providers/fdbfeba4-48e3-4c25-b665-be10e40d789d/provider_requests</pre>

#### Body

<pre>image_ids[]=04d91303-41d4-4d10-99e3-4daabcf1a56e&image_ids[]=4e8cee9d-441a-47e0-b176-d00685f0df1a&image_ids[]=19ac4097-f1a2-45b8-a3d5-5c8c21e6e62c</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzMsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiOTI1ZmJhNzMtOTg0NC00NDkzLWIwMWQtZDE0NWVkZDAwMTNjIn0.ynjOD9j9LuZqGIYbGDSGpMvHAq-sF9A7BzOoM4DVUGI
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;07de63ea55a47cb859b5ed1ae06c0a9d&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: c355b41e-94b2-4be0-b077-254f492b644f
X-Runtime: 0.182196
Content-Length: 754</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"image_id":"04d91303-41d4-4d10-99e3-4daabcf1a56e","provider_id":"fdbfeba4-48e3-4c25-b665-be10e40d789d","organization_id":"c0a7d008-b3fb-464f-95eb-f1cc290fe6f2","created_at":"2015-12-02T11:14:33.483+01:00","id":"6588243a-8e7d-481b-97e6-af08a513b26b"},{"image_id":"4e8cee9d-441a-47e0-b176-d00685f0df1a","provider_id":"fdbfeba4-48e3-4c25-b665-be10e40d789d","organization_id":"c0a7d008-b3fb-464f-95eb-f1cc290fe6f2","created_at":"2015-12-02T11:14:33.502+01:00","id":"5baddb05-9ab8-44d8-8eda-1fd6490ca777"},{"image_id":"19ac4097-f1a2-45b8-a3d5-5c8c21e6e62c","provider_id":"fdbfeba4-48e3-4c25-b665-be10e40d789d","organization_id":"c0a7d008-b3fb-464f-95eb-f1cc290fe6f2","created_at":"2015-12-02T11:14:33.552+01:00","id":"a93040b0-8931-44f6-8816-359082709cf5"}]</pre>
