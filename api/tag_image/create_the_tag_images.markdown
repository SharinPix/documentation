# Tag Image API

## create the tag_images

### POST /api/v1/tags/:tag_id/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| tag_id | Id or Name of tag | false |  |
| image_ids | Id of images | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6IjY5ZDljMDM1LTQ3ZDgtNDQwNy04YjY3LTFiNDg4MTI1NzljNSIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiQWNjZXNzIjp7InNoYXJlIjp0cnVlfX19fQ.-FyV4ZdUwjE9bRLiokxty7S1ZYXeI_LK7F9fmCBQUeY&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/tags/0c7363fd-70c3-4f34-bafc-0f76414d8376/tag_images</pre>

#### Body

<pre>image_ids[]=8be0ceed-feaa-4ba8-85b8-fdd9d94efd92&image_ids[]=407281d5-4e0e-4278-8503-4a6cfd3ee64b&image_ids[]=c80fa050-dcf2-4896-a113-39857ecb1aaf</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6IjY5ZDljMDM1LTQ3ZDgtNDQwNy04YjY3LTFiNDg4MTI1NzljNSIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiQWNjZXNzIjp7InNoYXJlIjp0cnVlfX19fQ.-FyV4ZdUwjE9bRLiokxty7S1ZYXeI_LK7F9fmCBQUeY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d5d05402-8b21-43a8-ac45-942639d8988c
X-Runtime: 0.052190
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 10351</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "dde5206a-04d4-47bf-9e2e-fba90ce186c0",
    "created_at": "2019-04-08T19:38:45.483+02:00",
    "user": "69d9c035-47d8-4407-8b67-1b48812579c5",
    "image": {
      "id": "c80fa050-dcf2-4896-a113-39857ecb1aaf",
      "public_id": "c80fa050-dcf2-4896-a113-39857ecb1aaf",
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
      "created_at": "2019-04-08T19:38:45.468+02:00",
      "updated_at": "2019-04-08T19:38:45.468+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JqE92mMY--/fl_attachment/v123123/25340fa02be8.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--4YZWHu6y--/c_fit,w_300/v123123/25340fa02be8.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--iRgev7fY--/c_fit,h_2000,w_2000/v123123/25340fa02be8.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2f3f1bc&url=localhost/images/c80fa050-dcf2-4896-a113-39857ecb1aaf/thumbnails/mini-c404faef09d.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e580398&url=localhost/images/c80fa050-dcf2-4896-a113-39857ecb1aaf/thumbnails/thumbnail-0d3a82ab577.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1ef64be&url=localhost/images/c80fa050-dcf2-4896-a113-39857ecb1aaf/thumbnails/full-649aa434de4.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--AAiOfsIt--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/25340fa02be8.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QfrNpL0w--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/25340fa02be8.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QfrNpL0w--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/25340fa02be8.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ocLU0lSf--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/25340fa02be8.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--YGkA7TQl--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/25340fa02be8.jpg"
      }
    },
    "tag": {
      "id": "0c7363fd-70c3-4f34-bafc-0f76414d8376",
      "created_at": "2019-04-08T19:38:45.449+02:00",
      "name": "My tag 1",
      "label": "{\"en\":\"My tag 1\",\"fr\":\"My tag 1\"}",
      "url": "/public_tags/0c7363fd-70c3-4f34-bafc-0f76414d8376",
      "public": true,
      "listed": false,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#FFC107",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "My tag 1",
      "label_fr": "My tag 1"
    }
  },
  {
    "id": "db596490-083c-47d9-9dbf-0e38f4eb8eb2",
    "created_at": "2019-04-08T19:38:45.488+02:00",
    "user": "69d9c035-47d8-4407-8b67-1b48812579c5",
    "image": {
      "id": "407281d5-4e0e-4278-8503-4a6cfd3ee64b",
      "public_id": "407281d5-4e0e-4278-8503-4a6cfd3ee64b",
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
      "created_at": "2019-04-08T19:38:45.462+02:00",
      "updated_at": "2019-04-08T19:38:45.462+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--uSFwG3GT--/fl_attachment/v123123/8c3cbf64fb1b.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--owetJ9ZK--/c_fit,w_300/v123123/8c3cbf64fb1b.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--LYlaSHd9--/c_fit,h_2000,w_2000/v123123/8c3cbf64fb1b.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=52b0376&url=localhost/images/407281d5-4e0e-4278-8503-4a6cfd3ee64b/thumbnails/mini-23536334891.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4512a70&url=localhost/images/407281d5-4e0e-4278-8503-4a6cfd3ee64b/thumbnails/thumbnail-7be0f311eba.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=3e5c7c2&url=localhost/images/407281d5-4e0e-4278-8503-4a6cfd3ee64b/thumbnails/full-76aa8763b02.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZIXrRdJQ--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/8c3cbf64fb1b.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HQ_eK8KW--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/8c3cbf64fb1b.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HQ_eK8KW--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/8c3cbf64fb1b.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--u8LPaIwG--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/8c3cbf64fb1b.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Z0EsG5ls--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/8c3cbf64fb1b.jpg"
      }
    },
    "tag": {
      "id": "0c7363fd-70c3-4f34-bafc-0f76414d8376",
      "created_at": "2019-04-08T19:38:45.449+02:00",
      "name": "My tag 1",
      "label": "{\"en\":\"My tag 1\",\"fr\":\"My tag 1\"}",
      "url": "/public_tags/0c7363fd-70c3-4f34-bafc-0f76414d8376",
      "public": true,
      "listed": false,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#FFC107",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "My tag 1",
      "label_fr": "My tag 1"
    }
  },
  {
    "id": "105c039d-0f80-4d3a-aa10-9a773f301eac",
    "created_at": "2019-04-08T19:38:45.493+02:00",
    "user": "69d9c035-47d8-4407-8b67-1b48812579c5",
    "image": {
      "id": "8be0ceed-feaa-4ba8-85b8-fdd9d94efd92",
      "public_id": "8be0ceed-feaa-4ba8-85b8-fdd9d94efd92",
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
      "created_at": "2019-04-08T19:38:45.456+02:00",
      "updated_at": "2019-04-08T19:38:45.456+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--KV8F1EAq--/fl_attachment/v123123/c25ed0449faf.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--vJ4j9mP---/c_fit,w_300/v123123/c25ed0449faf.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--J6zHUFUA--/c_fit,h_2000,w_2000/v123123/c25ed0449faf.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=40632da&url=localhost/images/8be0ceed-feaa-4ba8-85b8-fdd9d94efd92/thumbnails/mini-1a0e370a047.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=22f0130&url=localhost/images/8be0ceed-feaa-4ba8-85b8-fdd9d94efd92/thumbnails/thumbnail-9f79aeb2cd7.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=859e487&url=localhost/images/8be0ceed-feaa-4ba8-85b8-fdd9d94efd92/thumbnails/full-ee412a77285.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jDfgfmwR--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c25ed0449faf.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QDOnlpEj--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c25ed0449faf.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QDOnlpEj--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c25ed0449faf.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--triXSD5E--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c25ed0449faf.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yts71qj4--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c25ed0449faf.jpg"
      }
    },
    "tag": {
      "id": "0c7363fd-70c3-4f34-bafc-0f76414d8376",
      "created_at": "2019-04-08T19:38:45.449+02:00",
      "name": "My tag 1",
      "label": "{\"en\":\"My tag 1\",\"fr\":\"My tag 1\"}",
      "url": "/public_tags/0c7363fd-70c3-4f34-bafc-0f76414d8376",
      "public": true,
      "listed": false,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#FFC107",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "My tag 1",
      "label_fr": "My tag 1"
    }
  }
]</pre>
