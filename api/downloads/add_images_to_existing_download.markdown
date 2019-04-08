# Downloads API

## Add images to existing download

### POST /api/v1/downloads

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| id | Download UUID | false |  |
| image_ids | A list of image public_ids to be added in the zip. | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyX2lkIjoiZjgxMTU0ZDAtMjhhMC00ZDE3LTllNTQtNzQ5MGEwYTA4M2VkIiwiYWJpbGl0aWVzIjp7IjAwMTAwMDAwMTIzQkI3MCI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZX19fSwiZG93bmxvYWQiOnRydWUsImlzcyI6IjU2MTg0MTU0LWQ4YTAtNDkwNy1iNDFhLTZkNzFlNjYwYTYzYSJ9.I5ixwgaMnmQ4CWVBfhQj5Ct9tXns1-M53ESLVWVLSVg&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/downloads</pre>

#### Body

<pre>id=92870627-ed07-4a13-a020-51e9c0a9f3e1&image_ids[]=af45229c-22e8-4598-987f-aabef66b5556&image_ids[]=c1d5d26d-8b6d-456b-baa1-743e63ed3c58&image_ids[]=cdf87eae-6f5a-425b-9e12-3fdd7127c700&image_ids[]=0aef8cff-560b-4a08-b23c-be7dba4ba66f&image_ids[]=303d1ee8-12f5-4b9f-817d-e9452b573267</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjksImlhdCI6MTU1NDc0NTEyOSwidXNlcl9pZCI6ImY4MTE1NGQwLTI4YTAtNGQxNy05ZTU0LTc0OTBhMGEwODNlZCIsImlzcyI6IjU2MTg0MTU0LWQ4YTAtNDkwNy1iNDFhLTZkNzFlNjYwYTYzYSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCNzAiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sImRvd25sb2FkIjp0cnVlfQ.jJDHeYrnIUas8y4Rq6rfN0g-qlz-LLpvlSQjuhni1eM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 2cc5ce81-a388-4042-8e7d-db3fa5d96dcc
X-Runtime: 0.015903
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 246</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "92870627-ed07-4a13-a020-51e9c0a9f3e1",
  "zip_url": "https://zipper-dev.herokuapp.com:443/0/https%3A%2F%2Flocalhost%3A5001%2Fapi%2Fv1%2Fdownloads%2F92870627%2Ded07%2D4a13%2Da020%2D51e9c0a9f3e1%2Fzip%3Ftimestamp%3D1554674400/6e9e61301/zip.zip"
}</pre>
