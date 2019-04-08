# Album API

## Duplicate an album with einstein_boxes

### POST /api/v1/albums/:id/duplicate

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| destination_id | Destination album id | false |  |
| einstein_boxes | Copy image with einstein_boxes | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6IjMyMGM5M2IyLWJiYTEtNDExNS04YzQ4LTM5NGViNTU4OTg4OCIsImFiaWxpdGllcyI6e319.LPyOh2Qc_CORAhDq_2SqnYFvB14pMKcCNrMCDIeA35w&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB46/duplicate</pre>

#### Body

<pre>destination_id=new_id&einstein_boxes=true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6IjMyMGM5M2IyLWJiYTEtNDExNS04YzQ4LTM5NGViNTU4OTg4OCIsImFiaWxpdGllcyI6e319.ach3-mFJ-7e3uaPf5-l8eIhJm2bhmm97d_N_9Mnbysk
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: afe4da72-5a83-45aa-bf1f-364287ccc13a
X-Runtime: 0.265116
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
    "id": "447209cc-b70b-4a24-a79d-296f7170e1a6-new_id",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6IjMyMGM5M2IyLWJiYTEtNDExNS04YzQ4LTM5NGViNTU4OTg4OCIsImFsYnVtX2lkIjoibmV3X2lkIiwib3JnYW5pemF0aW9uX2lkIjoiNDQ3MjA5Y2MtYjcwYi00YTI0LWE3OWQtMjk2ZjcxNzBlMWE2In0.Aa0WY4NsB3Kz1WFMV0wXef6G2eESc8IuVcwLrfLQo44",
      "phash": 1,
      "tags": "new_id",
      "timestamp": 1555349927,
      "type": "authenticated",
      "signature": "b06e88e0c384ea2e0be57c2ed586008a5994aa66",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "447209cc-b70b-4a24-a79d-296f7170e1a6",
  "thumbnails": [
    {
      "id": "e6ce0cb1-fe7e-4115-9a8d-1caeacf7ee48",
      "public_id": "e6ce0cb1-fe7e-4115-9a8d-1caeacf7ee48",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB46"
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
      "created_at": "2019-04-08T19:38:47.147+02:00",
      "updated_at": "2019-04-08T19:38:47.157+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JIodwhaf--/fl_attachment/v123123/00ffef3973b9.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--znvjhm0K--/c_fit,w_300/v123123/00ffef3973b9.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bIQxsKXa--/c_fit,h_2000,w_2000/v123123/00ffef3973b9.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=546c07e&url=localhost/images/e6ce0cb1-fe7e-4115-9a8d-1caeacf7ee48/thumbnails/mini-6ef92183007.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e9c6a48&url=localhost/images/e6ce0cb1-fe7e-4115-9a8d-1caeacf7ee48/thumbnails/thumbnail-1d1494bb6fa.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=cb049da&url=localhost/images/e6ce0cb1-fe7e-4115-9a8d-1caeacf7ee48/thumbnails/full-c57d621e553.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "f1a7c604-0047-4235-840b-7748926bc2fa",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0ydtJz0m--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00ffef3973b9.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ugUNSbEn--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00ffef3973b9.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ugUNSbEn--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00ffef3973b9.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rHlEEq2m--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00ffef3973b9.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mDalOFq---/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00ffef3973b9.jpg"
      }
    },
    {
      "id": "f6205cd4-59b0-4b33-b4f3-a451c03c5835",
      "public_id": "f6205cd4-59b0-4b33-b4f3-a451c03c5835",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB46"
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
      "created_at": "2019-04-08T19:38:47.112+02:00",
      "updated_at": "2019-04-08T19:38:47.122+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Dxc2vfGR--/fl_attachment/v123123/da73bf769c22.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Y_jtDoPi--/c_fit,w_300/v123123/da73bf769c22.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EBBbtgPA--/c_fit,h_2000,w_2000/v123123/da73bf769c22.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9e0252c&url=localhost/images/f6205cd4-59b0-4b33-b4f3-a451c03c5835/thumbnails/mini-982eb417e12.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e4fc330&url=localhost/images/f6205cd4-59b0-4b33-b4f3-a451c03c5835/thumbnails/thumbnail-9cd13ca0dc8.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a722244&url=localhost/images/f6205cd4-59b0-4b33-b4f3-a451c03c5835/thumbnails/full-207128df41b.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "e12c7a1f-142c-4d90-81cc-052e1a780f70",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--LQrpgt5q--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/da73bf769c22.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NmmQbWw8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/da73bf769c22.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NmmQbWw8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/da73bf769c22.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--kJA5Cpup--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/da73bf769c22.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--AWCimqQy--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/da73bf769c22.jpg"
      }
    },
    {
      "id": "cbb9d576-f6e1-4437-a7d6-d3598122feb3",
      "public_id": "cbb9d576-f6e1-4437-a7d6-d3598122feb3",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB46"
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
      "created_at": "2019-04-08T19:38:47.077+02:00",
      "updated_at": "2019-04-08T19:38:47.088+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--KGX9T0N4--/fl_attachment/v123123/4216db923fbe.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--WvUhMz2L--/c_fit,w_300/v123123/4216db923fbe.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--82wpx9Vq--/c_fit,h_2000,w_2000/v123123/4216db923fbe.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=fedd5c7&url=localhost/images/cbb9d576-f6e1-4437-a7d6-d3598122feb3/thumbnails/mini-c290791983e.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=600365f&url=localhost/images/cbb9d576-f6e1-4437-a7d6-d3598122feb3/thumbnails/thumbnail-66cfbf4b736.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=ace83b7&url=localhost/images/cbb9d576-f6e1-4437-a7d6-d3598122feb3/thumbnails/full-799d290bce0.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "89657d5f-e90e-48da-ae7c-ff24ded8c7b4",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--gsPgDVyl--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/4216db923fbe.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--eK6-xiL1--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/4216db923fbe.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--eK6-xiL1--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/4216db923fbe.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PnBpi9YH--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/4216db923fbe.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--vCzGbRTZ--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/4216db923fbe.jpg"
      }
    },
    {
      "id": "c38574de-a603-49d3-8be9-79468ed5f7f7",
      "public_id": "c38574de-a603-49d3-8be9-79468ed5f7f7",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB46"
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
      "created_at": "2019-04-08T19:38:47.037+02:00",
      "updated_at": "2019-04-08T19:38:47.047+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--tDvayVKV--/fl_attachment/v123123/5e302d1526f4.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dFAtDcaH--/c_fit,w_300/v123123/5e302d1526f4.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Es4tPDu6--/c_fit,h_2000,w_2000/v123123/5e302d1526f4.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=10e6a83&url=localhost/images/c38574de-a603-49d3-8be9-79468ed5f7f7/thumbnails/mini-7d4beb3e1b2.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4c897ec&url=localhost/images/c38574de-a603-49d3-8be9-79468ed5f7f7/thumbnails/thumbnail-f82db88bb46.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=8c127e0&url=localhost/images/c38574de-a603-49d3-8be9-79468ed5f7f7/thumbnails/full-4ad50579cf0.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "3558cbb2-6653-4e10-b2ad-67bd0f4f9a92",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--1vUhBJOR--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/5e302d1526f4.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Py6dDwUi--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/5e302d1526f4.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Py6dDwUi--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/5e302d1526f4.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--sLDrLoAh--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/5e302d1526f4.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--wtVRWOzQ--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/5e302d1526f4.jpg"
      }
    }
  ]
}</pre>
