# Album API

## moving images from source album to destination album

### PUT /api/v1/albums/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album | Album attributes | false |  |
| merge | Flag for merging album | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImE0YjYxNTJhLTVlOGUtNDQwZC05MmQ3LTgwYjc3Y2Q5YTllNCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMzYiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.HkQKc1D751Cv30gu1yBY0q07CuMKT0VRc2w0tHPlyEs&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/00100000123BB36</pre>

#### Body

<pre>album[public_id]=00100000123BB38&merge=true</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6ImE0YjYxNTJhLTVlOGUtNDQwZC05MmQ3LTgwYjc3Y2Q5YTllNCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMzYiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fX0.HkQKc1D751Cv30gu1yBY0q07CuMKT0VRc2w0tHPlyEs
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 57e17746-bc13-4a4a-bb16-2b468c8cc534
X-Runtime: 0.268582
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 11775</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "00100000123BB38",
  "public_id": "00100000123BB38",
  "images_count": 10,
  "views_count": 0,
  "upload_form": null,
  "organization_id": "9c511639-8066-4d6f-8dc0-49257ca27a96",
  "thumbnails": [
    {
      "id": "237b2fda-4db3-41a8-9044-737e57491897",
      "public_id": "237b2fda-4db3-41a8-9044-737e57491897",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB36"
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
      "gps_ip": null,
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.196+02:00",
      "updated_at": "2019-04-08T19:38:46.393+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Lzpm6og6--/fl_attachment/v123123/ccc0ddb6de7d.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mOo5-8U8--/c_fit,w_300/v123123/ccc0ddb6de7d.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--sSxspR6h--/c_fit,h_2000,w_2000/v123123/ccc0ddb6de7d.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=40710c7&url=localhost/images/237b2fda-4db3-41a8-9044-737e57491897/thumbnails/mini-a015970f3c9.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=5c13c2c&url=localhost/images/237b2fda-4db3-41a8-9044-737e57491897/thumbnails/thumbnail-c73b86be1a4.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1420fa4&url=localhost/images/237b2fda-4db3-41a8-9044-737e57491897/thumbnails/full-43fe6dc03f6.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": null,
      "color": "#7D7D7D",
      "size": 3604,
      "processed": false,
      "processing_error": null,
      "album_id": "00100000123BB38",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dwMTG1wN--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ccc0ddb6de7d.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OeBDHp2H--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ccc0ddb6de7d.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OeBDHp2H--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ccc0ddb6de7d.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--6NdqpRle--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ccc0ddb6de7d.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Emk1PUrI--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ccc0ddb6de7d.jpg"
      }
    },
    {
      "id": "c150783d-bd3d-45e3-b5e8-7246ca7bbffa",
      "public_id": "c150783d-bd3d-45e3-b5e8-7246ca7bbffa",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB36"
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
      "gps_ip": null,
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.190+02:00",
      "updated_at": "2019-04-08T19:38:46.321+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PIojlJKR--/fl_attachment/v123123/566220666b60.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3dqgQG60--/c_fit,w_300/v123123/566220666b60.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HjKmM4m6--/c_fit,h_2000,w_2000/v123123/566220666b60.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=216b1ec&url=localhost/images/c150783d-bd3d-45e3-b5e8-7246ca7bbffa/thumbnails/mini-e3aa9c089d7.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=76f31b7&url=localhost/images/c150783d-bd3d-45e3-b5e8-7246ca7bbffa/thumbnails/thumbnail-5ceb83f054a.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d01e4ba&url=localhost/images/c150783d-bd3d-45e3-b5e8-7246ca7bbffa/thumbnails/full-999923a6e32.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": null,
      "color": "#7D7D7D",
      "size": 3604,
      "processed": false,
      "processing_error": null,
      "album_id": "00100000123BB38",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QEw2hurf--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/566220666b60.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QGFh5FyG--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/566220666b60.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QGFh5FyG--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/566220666b60.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--KmrZAEhU--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/566220666b60.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bL1tJB6m--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/566220666b60.jpg"
      }
    },
    {
      "id": "0f8d5be7-1e14-4b2f-9236-d6e660d0c995",
      "public_id": "0f8d5be7-1e14-4b2f-9236-d6e660d0c995",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB36"
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
      "gps_ip": null,
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.183+02:00",
      "updated_at": "2019-04-08T19:38:46.287+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--T3I-AM7h--/fl_attachment/v123123/3c1b7bced9dc.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--6DUeWTtv--/c_fit,w_300/v123123/3c1b7bced9dc.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--6IKLFk35--/c_fit,h_2000,w_2000/v123123/3c1b7bced9dc.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2aa6802&url=localhost/images/0f8d5be7-1e14-4b2f-9236-d6e660d0c995/thumbnails/mini-18773a23c5d.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=de9eea5&url=localhost/images/0f8d5be7-1e14-4b2f-9236-d6e660d0c995/thumbnails/thumbnail-70ec1d70ed9.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=b8e8f32&url=localhost/images/0f8d5be7-1e14-4b2f-9236-d6e660d0c995/thumbnails/full-6cb34dc9624.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": null,
      "color": "#7D7D7D",
      "size": 3604,
      "processed": false,
      "processing_error": null,
      "album_id": "00100000123BB38",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--kuUbtMDJ--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3c1b7bced9dc.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rC-La8Aa--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3c1b7bced9dc.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rC-La8Aa--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3c1b7bced9dc.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--_0Y6UFnX--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3c1b7bced9dc.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bhN_Tl9f--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3c1b7bced9dc.jpg"
      }
    },
    {
      "id": "d07ade6c-9ebc-4ec7-afce-88232bc315a9",
      "public_id": "d07ade6c-9ebc-4ec7-afce-88232bc315a9",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB36"
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
      "gps_ip": null,
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.202+02:00",
      "updated_at": "2019-04-08T19:38:46.426+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--4q-CFQhp--/fl_attachment/v123123/adcec426aa24.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JJR-iegG--/c_fit,w_300/v123123/adcec426aa24.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--AtvwhiDa--/c_fit,h_2000,w_2000/v123123/adcec426aa24.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=94a7180&url=localhost/images/d07ade6c-9ebc-4ec7-afce-88232bc315a9/thumbnails/mini-c33c94f4ebd.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4705bb1&url=localhost/images/d07ade6c-9ebc-4ec7-afce-88232bc315a9/thumbnails/thumbnail-77136cf1ad6.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=28f3dce&url=localhost/images/d07ade6c-9ebc-4ec7-afce-88232bc315a9/thumbnails/full-fa3dae6e19a.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": null,
      "color": "#7D7D7D",
      "size": 3604,
      "processed": false,
      "processing_error": null,
      "album_id": "00100000123BB38",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---dW8KHuJ--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/adcec426aa24.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--qf1SvEfY--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/adcec426aa24.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--qf1SvEfY--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/adcec426aa24.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JrnOawd_--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/adcec426aa24.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--GxjQQYuF--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/adcec426aa24.jpg"
      }
    }
  ]
}</pre>
