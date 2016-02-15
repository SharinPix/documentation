# Publication API

## Retreive the album contained

### GET /api/v1/publications/:publication_id/album
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJjZmQ4MzcxNC0xNDIxLTQyM2MtOTU4Mi1iYTNhNzExY2Y0ZWIifQ.x9E8yKDMIrGjenYSmIYiNeH-mHKbcMd70_ZFnzJEwAE&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/publications/d825a92b-c522-49fe-94df-85d0f6b0720a/album</pre>

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
X-access-image_delete: true
X-access-image_upload: true
X-access-image_share: false
X-access-image_rotate: true
X-access-image_crop: true
X-access-stats: true
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzksImFiaWxpdGllcyI6e30sInVzZXJfaWQiOiJjZmQ4MzcxNC0xNDIxLTQyM2MtOTU4Mi1iYTNhNzExY2Y0ZWIifQ.x9E8yKDMIrGjenYSmIYiNeH-mHKbcMd70_ZFnzJEwAE
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 3eeb38a2-8cc6-4ae0-9278-aeee44a62eeb
X-Runtime: 0.045140
Content-Length: 388</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"912ecdc2-9f11-49ea-83dc-02afafe45d70","upload_form":{"url":"https://api-de.cloudinary.com/v1_1/hwja6b0dx/auto/upload","params":{"timestamp":1455537779,"transformation":"a_exif","type":"private","tags":"912ecdc2-9f11-49ea-83dc-02afafe45d70","signature":"822e6f087815a96fdbc3d99b0b3319a7750bd236","api_key":"744524991939777"}},"images_count":0,"views_count":0,"thumbnails":[]}</pre>
