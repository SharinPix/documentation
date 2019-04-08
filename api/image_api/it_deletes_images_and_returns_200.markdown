# Image API API

## it deletes images and returns 200

### DELETE /api/v1/images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_ids | List of images ids to be deleted | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImRjODUwNjM1LTljZGEtNGM3Yy04MTAyLWJlZDI1ZjM5MDU1ZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTIxIjp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.MWphZjO450rRxkyJGcdlLGMHJZz_jwAh28rRBYX7TPY&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>DELETE /api/v1/images</pre>

#### Body

<pre>image_ids[]=7dca41d5-d76a-4ebb-9e00-dd13c13fc238&image_ids[]=dcd964c3-f54e-413c-ab2e-41c8608f5d16&image_ids[]=8c35c2bf-318b-4657-a06c-68c8a012f757&image_ids[]=295ec432-fcb7-4eae-b881-7ab2f5126a23&image_ids[]=2f05ca7d-3347-4add-9959-41aac32eaf26&image_ids[]=4ff0f180-e325-4478-a001-406856255f31&image_ids[]=d9f1a5cf-b871-4d67-8a2a-88bf37760ae8&image_ids[]=6942945b-87fa-42d6-831b-8db4bc3d2f51&image_ids[]=cb61c3ed-6418-4d89-83e7-64f12fb9cfac</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6ImRjODUwNjM1LTljZGEtNGM3Yy04MTAyLWJlZDI1ZjM5MDU1ZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTIxIjp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.DMTdxu3fxDbXPiBKSFtdsaUTbbq9DRvcSM0SKS7tmWk
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 3cdcadc9-532d-4f5e-8826-8584694cf195
X-Runtime: 0.171775
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 352</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  "cb61c3ed-6418-4d89-83e7-64f12fb9cfac",
  "6942945b-87fa-42d6-831b-8db4bc3d2f51",
  "d9f1a5cf-b871-4d67-8a2a-88bf37760ae8",
  "4ff0f180-e325-4478-a001-406856255f31",
  "2f05ca7d-3347-4add-9959-41aac32eaf26",
  "295ec432-fcb7-4eae-b881-7ab2f5126a23",
  "8c35c2bf-318b-4657-a06c-68c8a012f757",
  "dcd964c3-f54e-413c-ab2e-41c8608f5d16",
  "7dca41d5-d76a-4ebb-9e00-dd13c13fc238"
]</pre>
