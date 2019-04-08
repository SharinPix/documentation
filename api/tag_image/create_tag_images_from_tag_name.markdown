# Tag Image API

## Create tag images from tag name

### POST /api/v1/tags/:tag_id/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| tag_id | Id or Name of tag | false |  |
| image_ids | Id of images | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6Ijg1NWFmYjI3LTY3ODctNDY4YS1hNzMyLTUxN2RmYWZhYzhiYiIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeSBUYWciOiJ7fSJ9LCJBY2Nlc3MiOnsic2VlIjp0cnVlLCJpbWFnZV90YWciOnRydWV9fX19.gehOd-UM_OKGkYGzG2T66mFoEY3JRW5HnwqipjyBvxM&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/tags/My%2520Tag/tag_images</pre>

#### Body

<pre>image_ids[]=62a6a72e-04d7-4a22-92ac-e0679591d2bd&image_ids[]=40b01c9b-1266-4df9-badc-449104bcb8c2&image_ids[]=67620455-0fc3-4141-871b-4c36792bc6e6</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6Ijg1NWFmYjI3LTY3ODctNDY4YS1hNzMyLTUxN2RmYWZhYzhiYiIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeSBUYWciOiJ7fSJ9LCJBY2Nlc3MiOnsic2VlIjp0cnVlLCJpbWFnZV90YWciOnRydWV9fX19.gehOd-UM_OKGkYGzG2T66mFoEY3JRW5HnwqipjyBvxM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 315e1c20-442f-4f38-a633-1c8eecd844bf
X-Runtime: 0.068489
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 10321</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "11bf4a31-b613-4085-8429-eaead57c1b22",
    "created_at": "2019-04-08T19:38:45.641+02:00",
    "user": "855afb27-6787-468a-a732-517dfafac8bb",
    "image": {
      "id": "67620455-0fc3-4141-871b-4c36792bc6e6",
      "public_id": "67620455-0fc3-4141-871b-4c36792bc6e6",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00324000004ijWS"
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
      "created_at": "2019-04-08T19:38:45.619+02:00",
      "updated_at": "2019-04-08T19:38:45.619+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Zu5DZuSo--/fl_attachment/v123123/239af9586966.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5Kz6zlod--/c_fit,w_300/v123123/239af9586966.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--CBPrE1F1--/c_fit,h_2000,w_2000/v123123/239af9586966.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1c3b9fa&url=localhost/images/67620455-0fc3-4141-871b-4c36792bc6e6/thumbnails/mini-4e10179af80.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=50b4332&url=localhost/images/67620455-0fc3-4141-871b-4c36792bc6e6/thumbnails/thumbnail-d11d3234ceb.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=781526b&url=localhost/images/67620455-0fc3-4141-871b-4c36792bc6e6/thumbnails/full-2f14f610a38.jpg"
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
      "album_id": "00324000004ijWS",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5DcDwuM4--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/239af9586966.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--L2O7kgOe--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/239af9586966.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--L2O7kgOe--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/239af9586966.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--28ljdhxa--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/239af9586966.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--6Hkq1Bfk--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/239af9586966.jpg"
      }
    },
    "tag": {
      "id": "1533be21-690a-4c3c-ad0b-0472d00804a3",
      "created_at": "2019-04-08T19:38:45.634+02:00",
      "name": "My Tag",
      "label": "{\"en\":\"My Tag\",\"fr\":\"My Tag\"}",
      "url": "/public_tags/1533be21-690a-4c3c-ad0b-0472d00804a3",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#3F51B5",
      "color_contrast": "#ffffff",
      "allow_download": false,
      "label_en": "My Tag",
      "label_fr": "My Tag"
    }
  },
  {
    "id": "0d85fb3f-8117-40d7-bf79-c2f566ded01c",
    "created_at": "2019-04-08T19:38:45.647+02:00",
    "user": "855afb27-6787-468a-a732-517dfafac8bb",
    "image": {
      "id": "40b01c9b-1266-4df9-badc-449104bcb8c2",
      "public_id": "40b01c9b-1266-4df9-badc-449104bcb8c2",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00324000004ijWS"
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
      "created_at": "2019-04-08T19:38:45.612+02:00",
      "updated_at": "2019-04-08T19:38:45.612+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s---4DkrJEB--/fl_attachment/v123123/d385c5eaadcd.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---CKzCiUU--/c_fit,w_300/v123123/d385c5eaadcd.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dP1o16nD--/c_fit,h_2000,w_2000/v123123/d385c5eaadcd.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=aaa2079&url=localhost/images/40b01c9b-1266-4df9-badc-449104bcb8c2/thumbnails/mini-9b686368513.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=aaf4e2e&url=localhost/images/40b01c9b-1266-4df9-badc-449104bcb8c2/thumbnails/thumbnail-a6f1918d46e.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f4fc3e3&url=localhost/images/40b01c9b-1266-4df9-badc-449104bcb8c2/thumbnails/full-a26fe955762.jpg"
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
      "album_id": "00324000004ijWS",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HISv9rPo--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d385c5eaadcd.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ifY4Qyl9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d385c5eaadcd.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ifY4Qyl9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d385c5eaadcd.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VxsqVPho--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d385c5eaadcd.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dgZJcZbx--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d385c5eaadcd.jpg"
      }
    },
    "tag": {
      "id": "1533be21-690a-4c3c-ad0b-0472d00804a3",
      "created_at": "2019-04-08T19:38:45.634+02:00",
      "name": "My Tag",
      "label": "{\"en\":\"My Tag\",\"fr\":\"My Tag\"}",
      "url": "/public_tags/1533be21-690a-4c3c-ad0b-0472d00804a3",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#3F51B5",
      "color_contrast": "#ffffff",
      "allow_download": false,
      "label_en": "My Tag",
      "label_fr": "My Tag"
    }
  },
  {
    "id": "2fae3404-4ce1-4776-8182-b995ef5f14c2",
    "created_at": "2019-04-08T19:38:45.652+02:00",
    "user": "855afb27-6787-468a-a732-517dfafac8bb",
    "image": {
      "id": "62a6a72e-04d7-4a22-92ac-e0679591d2bd",
      "public_id": "62a6a72e-04d7-4a22-92ac-e0679591d2bd",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00324000004ijWS"
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
      "created_at": "2019-04-08T19:38:45.605+02:00",
      "updated_at": "2019-04-08T19:38:45.605+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--hEseNV54--/fl_attachment/v123123/fb2d9945c256.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ObstKHyh--/c_fit,w_300/v123123/fb2d9945c256.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5R_auGaZ--/c_fit,h_2000,w_2000/v123123/fb2d9945c256.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=efa9aa2&url=localhost/images/62a6a72e-04d7-4a22-92ac-e0679591d2bd/thumbnails/mini-d869ae28b3b.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=c56b041&url=localhost/images/62a6a72e-04d7-4a22-92ac-e0679591d2bd/thumbnails/thumbnail-fe7769159d2.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0d3979e&url=localhost/images/62a6a72e-04d7-4a22-92ac-e0679591d2bd/thumbnails/full-d19e98de380.jpg"
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
      "album_id": "00324000004ijWS",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--01OzzpOs--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/fb2d9945c256.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0SH-GMa3--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/fb2d9945c256.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0SH-GMa3--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/fb2d9945c256.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--7gDDG50K--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/fb2d9945c256.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--XVz0ejN5--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/fb2d9945c256.jpg"
      }
    },
    "tag": {
      "id": "1533be21-690a-4c3c-ad0b-0472d00804a3",
      "created_at": "2019-04-08T19:38:45.634+02:00",
      "name": "My Tag",
      "label": "{\"en\":\"My Tag\",\"fr\":\"My Tag\"}",
      "url": "/public_tags/1533be21-690a-4c3c-ad0b-0472d00804a3",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#3F51B5",
      "color_contrast": "#ffffff",
      "allow_download": false,
      "label_en": "My Tag",
      "label_fr": "My Tag"
    }
  }
]</pre>
