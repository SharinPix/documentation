# Album API

## Duplicate an album with tags

### POST /api/v1/albums/:id/duplicate

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| destination_id | Destination album id | false |  |
| tags | Copy image with tags | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImU2ZDQ4NWU0LWQxOTAtNGM0Ni04ZTljLWU1MzgzM2Y5OGRkYyIsImFiaWxpdGllcyI6e319.XumiCVn8YQJChX2fg4r3kECTbruAsP9WrOJCqYQb9cQ&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB48/duplicate</pre>

#### Body

<pre>destination_id=new_id&tags=true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImU2ZDQ4NWU0LWQxOTAtNGM0Ni04ZTljLWU1MzgzM2Y5OGRkYyIsImFiaWxpdGllcyI6e319.XumiCVn8YQJChX2fg4r3kECTbruAsP9WrOJCqYQb9cQ
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 9b12e4ba-a3d2-4670-bc40-c1afcf23a11c
X-Runtime: 0.327989
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 12677</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "new_id",
  "public_id": "new_id",
  "images_count": 5,
  "views_count": 0,
  "upload_form": {
    "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
    "expires_at": 1555349927,
    "name": "new_id",
    "id": "816e3ae4-a768-4a18-a125-ec3febddf416-new_id",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImU2ZDQ4NWU0LWQxOTAtNGM0Ni04ZTljLWU1MzgzM2Y5OGRkYyIsImFsYnVtX2lkIjoibmV3X2lkIiwib3JnYW5pemF0aW9uX2lkIjoiODE2ZTNhZTQtYTc2OC00YTE4LWExMjUtZWMzZmViZGRmNDE2In0.guAlIqnJ9mJqhF-40X5HHMVJsoXthHqpwDnDs4oUZNo",
      "phash": 1,
      "tags": "new_id",
      "timestamp": 1555349927,
      "type": "authenticated",
      "signature": "d83385de7e491c434612ef3d31c7a22fbce0ac7f",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "816e3ae4-a768-4a18-a125-ec3febddf416",
  "thumbnails": [
    {
      "id": "b0539d8a-fdff-42f2-9338-02f232c7d754",
      "public_id": "b0539d8a-fdff-42f2-9338-02f232c7d754",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB48"
        ],
        "type": "authenticated",
        "width": 48,
        "original_filename": "Super Image",
        "location": {
          "accuracy": 36,
          "latitude": 48.861934399999996,
          "longitude": 2.348967
        }
      },
      "exifs": {
      },
      "gps": [
        48.861934399999996,
        2.348967
      ],
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:47.648+02:00",
      "updated_at": "2019-04-08T19:38:47.658+02:00",
      "taken_at": null,
      "width": 48,
      "height": 48,
      "rotation": 0,
      "crop_x": 0.0,
      "crop_y": 0.0,
      "crop_w": 0.0,
      "crop_h": 0.0,
      "metadatas": {
      },
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--BmbgmFSH--/fl_attachment/v123123/7ee76959ca49.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--b7cM5YXD--/c_fit,w_300/v123123/7ee76959ca49.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--f-GaxTcJ--/c_fit,h_2000,w_2000/v123123/7ee76959ca49.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=89c5367&url=localhost/images/b0539d8a-fdff-42f2-9338-02f232c7d754/thumbnails/mini-92100ac1215.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7fcce27&url=localhost/images/b0539d8a-fdff-42f2-9338-02f232c7d754/thumbnails/thumbnail-050c10ef1da.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2ad3b73&url=localhost/images/b0539d8a-fdff-42f2-9338-02f232c7d754/thumbnails/full-a6875bc996c.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "8a74dc66-79d8-4e04-b66e-9f3f6375b51b",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--1RzdfIm6--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7ee76959ca49.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--f2rdTNf1--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7ee76959ca49.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--f2rdTNf1--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7ee76959ca49.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---xUpwVt---/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7ee76959ca49.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--X1oPhyPi--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7ee76959ca49.jpg"
      }
    },
    {
      "id": "befdfcb9-89d0-436b-af46-d86193912ef3",
      "public_id": "befdfcb9-89d0-436b-af46-d86193912ef3",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB48"
        ],
        "type": "authenticated",
        "width": 48,
        "original_filename": "Super Image",
        "location": {
          "accuracy": 36,
          "latitude": 48.861934399999996,
          "longitude": 2.348967
        }
      },
      "exifs": {
      },
      "gps": [
        48.861934399999996,
        2.348967
      ],
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:47.618+02:00",
      "updated_at": "2019-04-08T19:38:47.628+02:00",
      "taken_at": null,
      "width": 48,
      "height": 48,
      "rotation": 0,
      "crop_x": 0.0,
      "crop_y": 0.0,
      "crop_w": 0.0,
      "crop_h": 0.0,
      "metadatas": {
      },
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--nlmNe6dO--/fl_attachment/v123123/6a895de7abb1.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--L9FxKr9f--/c_fit,w_300/v123123/6a895de7abb1.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--lbFsqAOs--/c_fit,h_2000,w_2000/v123123/6a895de7abb1.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9be4666&url=localhost/images/befdfcb9-89d0-436b-af46-d86193912ef3/thumbnails/mini-bd198365fd7.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=6e28cdb&url=localhost/images/befdfcb9-89d0-436b-af46-d86193912ef3/thumbnails/thumbnail-051f648a24d.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=152878f&url=localhost/images/befdfcb9-89d0-436b-af46-d86193912ef3/thumbnails/full-fb5fa6d4fbd.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "813d637a-325c-4f6d-be54-f124d9c5ea3f",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Aem38M4j--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6a895de7abb1.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--T87Mfyl1--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6a895de7abb1.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--T87Mfyl1--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6a895de7abb1.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--IBOSpt-W--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6a895de7abb1.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--05hVgPa_--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6a895de7abb1.jpg"
      }
    },
    {
      "id": "dc6d9a9e-b414-46da-aef7-e9be8b7c5ed1",
      "public_id": "dc6d9a9e-b414-46da-aef7-e9be8b7c5ed1",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB48"
        ],
        "type": "authenticated",
        "width": 48,
        "original_filename": "Super Image",
        "location": {
          "accuracy": 36,
          "latitude": 48.861934399999996,
          "longitude": 2.348967
        }
      },
      "exifs": {
      },
      "gps": [
        48.861934399999996,
        2.348967
      ],
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:47.585+02:00",
      "updated_at": "2019-04-08T19:38:47.598+02:00",
      "taken_at": null,
      "width": 48,
      "height": 48,
      "rotation": 0,
      "crop_x": 0.0,
      "crop_y": 0.0,
      "crop_w": 0.0,
      "crop_h": 0.0,
      "metadatas": {
      },
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--illKSFbU--/fl_attachment/v123123/2b7c24950470.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NtDE7JZM--/c_fit,w_300/v123123/2b7c24950470.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ns6Xblo8--/c_fit,h_2000,w_2000/v123123/2b7c24950470.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=93ef11c&url=localhost/images/dc6d9a9e-b414-46da-aef7-e9be8b7c5ed1/thumbnails/mini-24c821765e7.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0e9fb9a&url=localhost/images/dc6d9a9e-b414-46da-aef7-e9be8b7c5ed1/thumbnails/thumbnail-720a4771ed2.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=58a033d&url=localhost/images/dc6d9a9e-b414-46da-aef7-e9be8b7c5ed1/thumbnails/full-71f2ca4b052.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "7b23bf8f-f315-477f-9db6-edd7d0200480",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--p8cF7nnm--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2b7c24950470.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xBnuajK4--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2b7c24950470.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xBnuajK4--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2b7c24950470.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZU92I0hr--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2b7c24950470.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--38R9Rx0r--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2b7c24950470.jpg"
      }
    },
    {
      "id": "d4fa0380-aaa6-4734-b5b5-54e15b9e630c",
      "public_id": "d4fa0380-aaa6-4734-b5b5-54e15b9e630c",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB48"
        ],
        "type": "authenticated",
        "width": 48,
        "original_filename": "Super Image",
        "location": {
          "accuracy": 36,
          "latitude": 48.861934399999996,
          "longitude": 2.348967
        }
      },
      "exifs": {
      },
      "gps": [
        48.861934399999996,
        2.348967
      ],
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:47.509+02:00",
      "updated_at": "2019-04-08T19:38:47.520+02:00",
      "taken_at": null,
      "width": 48,
      "height": 48,
      "rotation": 0,
      "crop_x": 0.0,
      "crop_y": 0.0,
      "crop_w": 0.0,
      "crop_h": 0.0,
      "metadatas": {
      },
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--cOjUovtt--/fl_attachment/v123123/b80b6041ecd5.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NWr1Zs0---/c_fit,w_300/v123123/b80b6041ecd5.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--XYYF4rVv--/c_fit,h_2000,w_2000/v123123/b80b6041ecd5.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d919f42&url=localhost/images/d4fa0380-aaa6-4734-b5b5-54e15b9e630c/thumbnails/mini-1a47ea5e918.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=c916001&url=localhost/images/d4fa0380-aaa6-4734-b5b5-54e15b9e630c/thumbnails/thumbnail-fd60a15690b.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7015e70&url=localhost/images/d4fa0380-aaa6-4734-b5b5-54e15b9e630c/thumbnails/full-ccc7da9b118.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "efbb1e83-e0ad-4979-a7c5-901eb48d9f3e",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HO6S9jGT--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b80b6041ecd5.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ap0p7umg--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b80b6041ecd5.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ap0p7umg--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b80b6041ecd5.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dQTQ71R3--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b80b6041ecd5.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--X2xSW2v2--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b80b6041ecd5.jpg"
      }
    }
  ]
}</pre>
