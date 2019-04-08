# Image External Url API

## Retrieve external URL

### POST /api/v1/image_external_urls

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_external_url | images external url | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6IjgwMDAxZTllLWUwMzgtNDVkYy05YmI4LTAyZTczMGNiNWI1MiIsImFiaWxpdGllcyI6eyJpbWFnZV91cmxzIjp0cnVlfX0.NL0i15C8Pio_PbnnXTzEI91Oh5Tp0_90tFfgVk1NYrU&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/image_external_urls</pre>

#### Body

<pre>image_external_url[image_id]=d0209dc2-3545-478a-ad55-f62ebc41ea08&&image_external_url[transformations][crop]=fit&image_external_url[transformations][width]=100</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6IjgwMDAxZTllLWUwMzgtNDVkYy05YmI4LTAyZTczMGNiNWI1MiIsImFiaWxpdGllcyI6eyJpbWFnZV91cmxzIjp0cnVlfX0.NL0i15C8Pio_PbnnXTzEI91Oh5Tp0_90tFfgVk1NYrU
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 259c5e1a-ddd1-45a5-9a36-be6e33c5b01e
X-Runtime: 0.014622
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 764</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "125dff14-28af-404a-a8ee-869e6fc4bbcc",
  "image_id": "d0209dc2-3545-478a-ad55-f62ebc41ea08",
  "infos": {
    "image_id": "d0209dc2-3545-478a-ad55-f62ebc41ea08",
    "transformations": {
      "crop": "fit",
      "width": "100"
    }
  },
  "url": "https://sharinpix-proxy-dev.herokuapp.com/125dff14-28af-404a-a8ee-869e6fc4bbcc.jpg?s=a3d5951&url=localhost/image_external_urls/125dff14-28af-404a-a8ee-869e6fc4bbcc",
  "source_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8eb5rOKi--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,w_100/v123123/22125cdf64a1.jpg",
  "resource_url": "https://sharinpix-proxy-dev.herokuapp.com/125dff14-28af-404a-a8ee-869e6fc4bbcc.jpg?s=a3d5951&url=localhost/image_external_urls/125dff14-28af-404a-a8ee-869e6fc4bbcc"
}</pre>
