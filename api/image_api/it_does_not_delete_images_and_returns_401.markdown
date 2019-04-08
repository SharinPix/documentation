# Image API API

## it does not delete images and returns 401

### DELETE /api/v1/images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_ids | List of images ids to be deleted | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzEsImlhdCI6MTU1NDc0NTEzMSwidXNlcl9pZCI6ImQxMjUyNTY3LTg5MTMtNGNhYi05MmRkLTVmMTQzYjVmNmFmZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTE4Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ._ke8KmcgevukXTDT-_pS6Vr_WM7-lBegki_57L0kSRw&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>DELETE /api/v1/images</pre>

#### Body

<pre>image_ids[]=2f8dd2dc-2abb-4975-8796-2e2df3a8c555&image_ids[]=de5c9bff-2e4c-4a00-a337-cd6cd0eaf2df&image_ids[]=dfbc1893-db09-4346-8da6-93fa87caca7a&image_ids[]=621518d8-df23-46ff-b148-cca7a3df7b6c&image_ids[]=d77070fe-3eeb-449c-8468-0cba5ffdce91&image_ids[]=9aa8b490-7d5d-477b-ab52-e04db866475c&image_ids[]=27a8b3d8-2117-416c-9823-762067811f98&image_ids[]=f09d0189-2ae3-4425-8312-a3ffdc7ce8af&image_ids[]=27e6a464-6208-483b-9974-04f39358d30c</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-message: Access denied
Content-Type: text/html
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4bea8a25-eaa7-42b5-b626-31b7b22f1b7e
X-Runtime: 0.006822
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>401 Unauthorized</pre>

