# Storage file API

## Return the storage_file with a image

### PUT /api/v1/storage_files/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| infos | Infos returned by the endoint | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6Ijk4ZTBhYzZmLTFjZmYtNDcyMS04MGU4LTM5NjA5ZjU0Yjc1NSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjY1Ijp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.Qua_vXmaaj9y8ZVXWwN_Eob2_IDgDjM0PdpNC-YPtII&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/storage_files/6ac3ff51-0ab6-441c-abbc-0dfba47e38a8</pre>

#### Body

<pre>infos=%3C%3Fxml+version%3D%221.0%22+encoding%3D%22UTF-8%22%3F%3E%0A%3CPostResponse%3E%3CLocation%3Ehttps%3A%2F%2Fsharinpix-pix-dev.s3-accelerate.dualstack.amazonaws.com%2Fombr-ngrok-io%252Fstorage_files%252Fdb%252F79%252Fdb79b3d8-9d06-4100-9e4a-43b0348d9b21%252Fimg.jpg%3C%2FLocation%3E%3CBucket%3Esharinpix-pix-dev%3C%2FBucket%3E%3CKey%3Eombr-ngrok-io%2Fstorage_files%2Fdb%2F79%2Fdb79b3d8-9d06-4100-9e4a-43b0348d9b21%2Fimg.jpg%3C%2FKey%3E%3CETag%3E%22e987cefa00eee258bf9367cc25983724%22%3C%2FETag%3E%3C%2FPostResponse%3E%0A</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6Ijk4ZTBhYzZmLTFjZmYtNDcyMS04MGU4LTM5NjA5ZjU0Yjc1NSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjY1Ijp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.Qua_vXmaaj9y8ZVXWwN_Eob2_IDgDjM0PdpNC-YPtII
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d79a1b80-7ab7-421c-86fe-ce95ac304b20
X-Runtime: 0.028183
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2824</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "6ac3ff51-0ab6-441c-abbc-0dfba47e38a8",
  "organization_id": "ede9affc-7987-4b38-ba9b-2d8ae553952f",
  "image": {
    "id": "560804ab-88bd-431e-bd62-502d87eaf041",
    "public_id": "560804ab-88bd-431e-bd62-502d87eaf041",
    "infos": {
      "bytes": 3145728,
      "color": "#6c401b",
      "exifs": {
        "Model": "NIKON D2H"
      },
      "original_filename": "This is an è à Amazing file",
      "format": "jpg",
      "md5": "e987cefa00eee258bf9367cc25983724"
    },
    "exifs": {
      "Model": "NIKON D2H"
    },
    "gps": null,
    "gps_ip": null,
    "gps_exifs": null,
    "gps_html": null,
    "created_at": "2019-04-08T19:39:03.950+02:00",
    "updated_at": "2019-04-08T19:39:03.950+02:00",
    "taken_at": null,
    "width": 3000,
    "height": 3000,
    "rotation": 0,
    "crop_x": 0.0,
    "crop_y": 0.0,
    "crop_w": 0.0,
    "crop_h": 0.0,
    "metadatas": {
    },
    "original_url": "https://sharinpix-proxy-dev.herokuapp.com/this-is-an-e-a-amazing-file.jpg?s=4b55450&url=localhost/images/560804ab-88bd-431e-bd62-502d87eaf041/thumbnails/original-5f5ccf19ef3.jpg",
    "original_width": 3000,
    "original_height": 3000,
    "external_urls": {
      "fill100": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yHjaSjf0--/c_fit,w_300/raw_placeholder.jpg",
      "fit2000": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--vY1va9tF--/c_fit,h_2000,w_2000/raw_placeholder.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/this-is-an-e-a-amazing-file.jpg?s=41973b0&url=localhost/images/560804ab-88bd-431e-bd62-502d87eaf041/thumbnails/mini-a4af55d95e0.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/this-is-an-e-a-amazing-file.jpg?s=8191763&url=localhost/images/560804ab-88bd-431e-bd62-502d87eaf041/thumbnails/thumbnail-27c81a477fe.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/this-is-an-e-a-amazing-file.jpg?s=cc9c187&url=localhost/images/560804ab-88bd-431e-bd62-502d87eaf041/thumbnails/full-78613ac3566.jpg"
    },
    "filename": "This is an è à Amazing file",
    "format": "jpg",
    "title": null,
    "description": null,
    "page": 1,
    "group_id": null,
    "color": "#6c401b",
    "size": 3145728,
    "processed": false,
    "processing_error": null,
    "album_id": "00100000123BB265",
    "thumbnails": {
      "original": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0KCZNF0J--/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "full_no_sharinpix": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xBErTufU--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "full": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xBErTufU--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "large": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--c5-w2fj8--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "mini": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EmjULx71--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg"
    }
  }
}</pre>
