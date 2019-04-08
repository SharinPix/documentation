# Image External Url API

## Retrieve Cloudinary URL

### POST /api/v1/image_external_urls

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_external_urls | Images urls | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6ImI3MGNkZWIwLWU3ZWQtNDdmZS05M2EyLThkZGYyNDM1NWJmZiIsImFiaWxpdGllcyI6eyJpbWFnZV91cmxzIjp0cnVlfX0.-unpQawc1jqHQWxN8qnPe6q8KAvYWkAFmraSX1-S0sU&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/image_external_urls</pre>

#### Body

<pre>image_external_urls[][image_id]=a202b14a-a187-4858-b746-29476a8c48fa&&image_external_urls[][transformations][crop]=fit&image_external_urls[][transformations][height]=100&image_external_urls[][transformations][width]=100&image_external_urls[][image_id]=a669476c-473e-42ac-a681-dc64e109cb38&image_external_urls[][transformations][crop]=crop&image_external_urls[][transformations][height]=200&image_external_urls[][transformations][width]=200&image_external_urls[][image_id]=a202b14a-a187-4858-b746-29476a8c48fa&image_external_urls[][sharinpix][original]=true&image_external_urls[][transformations][crop]=fill&image_external_urls[][transformations][height]=300&image_external_urls[][transformations][width]=300&image_external_urls[][image_id]=a202b14a-a187-4858-b746-29476a8c48fa&image_external_urls[][sharinpix][download]=false&image_external_urls[][transformations][][crop]=fit&image_external_urls[][transformations][][height]=500&image_external_urls[][transformations][][width]=500&image_external_urls[][transformations][][crop]=fill&image_external_urls[][transformations][][height]=200&image_external_urls[][transformations][][width]=200</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDQsImlhdCI6MTU1NDc0NTE0NCwidXNlcl9pZCI6ImI3MGNkZWIwLWU3ZWQtNDdmZS05M2EyLThkZGYyNDM1NWJmZiIsImFiaWxpdGllcyI6eyJpbWFnZV91cmxzIjp0cnVlfX0.-unpQawc1jqHQWxN8qnPe6q8KAvYWkAFmraSX1-S0sU
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 1d9bd504-a02c-4492-ac68-5c133da86175
X-Runtime: 0.027144
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 3218</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "4fc0d899-8e7e-48df-b437-bee5e1d90c6f",
    "image_id": "a202b14a-a187-4858-b746-29476a8c48fa",
    "infos": {
      "image_id": "a202b14a-a187-4858-b746-29476a8c48fa",
      "transformations": {
        "crop": "fit",
        "height": "100",
        "width": "100"
      }
    },
    "url": "https://sharinpix-proxy-dev.herokuapp.com/4fc0d899-8e7e-48df-b437-bee5e1d90c6f.jpg?s=9431cac&url=localhost/image_external_urls/4fc0d899-8e7e-48df-b437-bee5e1d90c6f",
    "source_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--kTKJSgWy--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_100,w_100/v123123/5b3cbbf031c8.jpg",
    "resource_url": "https://sharinpix-proxy-dev.herokuapp.com/4fc0d899-8e7e-48df-b437-bee5e1d90c6f.jpg?s=9431cac&url=localhost/image_external_urls/4fc0d899-8e7e-48df-b437-bee5e1d90c6f"
  },
  {
    "id": "1bfa1c0a-dcfc-4271-9a50-0131dd766f27",
    "image_id": "a669476c-473e-42ac-a681-dc64e109cb38",
    "infos": {
      "image_id": "a669476c-473e-42ac-a681-dc64e109cb38",
      "transformations": {
        "crop": "crop",
        "height": "200",
        "width": "200"
      }
    },
    "url": "https://sharinpix-proxy-dev.herokuapp.com/1bfa1c0a-dcfc-4271-9a50-0131dd766f27.jpg?s=7f5917e&url=localhost/image_external_urls/1bfa1c0a-dcfc-4271-9a50-0131dd766f27",
    "source_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jKfUS4-g--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_crop,h_200,w_200/v123123/0d7417775229.jpg",
    "resource_url": "https://sharinpix-proxy-dev.herokuapp.com/1bfa1c0a-dcfc-4271-9a50-0131dd766f27.jpg?s=7f5917e&url=localhost/image_external_urls/1bfa1c0a-dcfc-4271-9a50-0131dd766f27"
  },
  {
    "id": "21418ed9-9097-474f-b676-2d192518df66",
    "image_id": "a202b14a-a187-4858-b746-29476a8c48fa",
    "infos": {
      "image_id": "a202b14a-a187-4858-b746-29476a8c48fa",
      "sharinpix": {
        "original": "true"
      },
      "transformations": {
        "crop": "fill",
        "height": "300",
        "width": "300"
      }
    },
    "url": "https://sharinpix-proxy-dev.herokuapp.com/21418ed9-9097-474f-b676-2d192518df66.jpg?s=a373969&url=localhost/image_external_urls/21418ed9-9097-474f-b676-2d192518df66",
    "source_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--T05cWy_Z--/fl_attachment/v123123/5b3cbbf031c8.jpg",
    "resource_url": "https://sharinpix-proxy-dev.herokuapp.com/21418ed9-9097-474f-b676-2d192518df66.jpg?s=a373969&url=localhost/image_external_urls/21418ed9-9097-474f-b676-2d192518df66"
  },
  {
    "id": "e28e0570-27ff-4cf4-94a2-d3022e9f5a74",
    "image_id": "a202b14a-a187-4858-b746-29476a8c48fa",
    "infos": {
      "image_id": "a202b14a-a187-4858-b746-29476a8c48fa",
      "sharinpix": {
        "download": "false"
      },
      "transformations": [
        {
          "crop": "fit",
          "height": "500",
          "width": "500"
        },
        {
          "crop": "fill",
          "height": "200",
          "width": "200"
        }
      ]
    },
    "url": "https://sharinpix-proxy-dev.herokuapp.com/e28e0570-27ff-4cf4-94a2-d3022e9f5a74.jpg?s=0abfdb3&url=localhost/image_external_urls/e28e0570-27ff-4cf4-94a2-d3022e9f5a74",
    "source_url": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ljtbr8_k--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,h_500,w_500/c_fill,h_200,w_200/v123123/5b3cbbf031c8.jpg",
    "resource_url": "https://sharinpix-proxy-dev.herokuapp.com/e28e0570-27ff-4cf4-94a2-d3022e9f5a74.jpg?s=0abfdb3&url=localhost/image_external_urls/e28e0570-27ff-4cf4-94a2-d3022e9f5a74"
  }
]</pre>
