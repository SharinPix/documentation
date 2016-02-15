# Provider request API

## create provider requests

### POST /api/v1/providers/:provider_id/provider_requests

### Parameters

Name : image_ids
Description : id of images

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzYsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiODFhOTMzMDktY2UyNS00MTM0LWI0NGEtZGIxYjM1OTkwOWJlIn0.eaAbEmRhJeanm9iMNLD5dlmEHQVdcQHKeLGL88WMUBQ&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/providers/0ce6c80a-c766-4918-8f2a-53b64bd9c90f/provider_requests</pre>

#### Body

<pre>image_ids[]=1d704918-ba52-412a-af15-9ef7bb8cd8b2&image_ids[]=a070ab80-9c13-4810-8a95-7620668e75b3&image_ids[]=5f321baa-710f-482b-ab9a-024e9ffc5008</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzYsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19LCJ1c2VyX2lkIjoiODFhOTMzMDktY2UyNS00MTM0LWI0NGEtZGIxYjM1OTkwOWJlIn0.eaAbEmRhJeanm9iMNLD5dlmEHQVdcQHKeLGL88WMUBQ
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d9baa741-7cd3-4989-812e-7f7213748096
X-Runtime: 0.088866
Content-Length: 754</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"image_id":"1d704918-ba52-412a-af15-9ef7bb8cd8b2","provider_id":"0ce6c80a-c766-4918-8f2a-53b64bd9c90f","organization_id":"90db5c44-370e-44b0-b2bf-9a00010ec694","created_at":"2016-02-15T13:02:56.422+01:00","id":"99de584d-f86a-41e8-a8cb-105a9ade058c"},{"image_id":"a070ab80-9c13-4810-8a95-7620668e75b3","provider_id":"0ce6c80a-c766-4918-8f2a-53b64bd9c90f","organization_id":"90db5c44-370e-44b0-b2bf-9a00010ec694","created_at":"2016-02-15T13:02:56.431+01:00","id":"455665d1-44e1-4d03-8a65-19a1f14cd14e"},{"image_id":"5f321baa-710f-482b-ab9a-024e9ffc5008","provider_id":"0ce6c80a-c766-4918-8f2a-53b64bd9c90f","organization_id":"90db5c44-370e-44b0-b2bf-9a00010ec694","created_at":"2016-02-15T13:02:56.448+01:00","id":"bab5620d-4114-4654-8b5a-0db30fabab1a"}]</pre>
