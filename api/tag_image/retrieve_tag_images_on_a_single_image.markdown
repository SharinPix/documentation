# Tag Image API

## Retrieve tag images on a single image

### GET api/v1/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| tag_name | Name of the tag | false |  |
| image_id | Id of image | false |  |
| album_id | Id of album | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImI4MWQ4MjIwLWVjMjUtNDMxOC1iOTEwLWQ1NDExMGUwYmJjZSIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6Ik15VGFnIiwiZnIiOiJNeVRhZyJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19fQ.gvK3jbreSpd0MKNJm3iMdvZobxs9F0qMSQc0sXaGU7Q&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?tag_name=MyTag&amp;image_id=7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e&amp;album_id=00324000004ijWS</pre>

#### Query Parameters

<pre>tag_name: MyTag
image_id: 7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e
album_id: 00324000004ijWS</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImI4MWQ4MjIwLWVjMjUtNDMxOC1iOTEwLWQ1NDExMGUwYmJjZSIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6Ik15VGFnIiwiZnIiOiJNeVRhZyJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19fQ.gvK3jbreSpd0MKNJm3iMdvZobxs9F0qMSQc0sXaGU7Q
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: b7da020f-90c2-48ee-9307-58f405613eba
X-Runtime: 0.029093
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 3436</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "858ce861-4487-4847-9f59-a04f9dac0f30",
    "created_at": "2019-04-08T19:38:45.186+02:00",
    "user": "b81d8220-ec25-4318-b910-d54110e0bbce",
    "image": {
      "id": "7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e",
      "public_id": "7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e",
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
      "created_at": "2019-04-08T19:38:45.168+02:00",
      "updated_at": "2019-04-08T19:38:45.168+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--uVNc3bha--/fl_attachment/v123123/3f8612de3669.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--hKPCVlG3--/c_fit,w_300/v123123/3f8612de3669.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2Gv1ggls--/c_fit,h_2000,w_2000/v123123/3f8612de3669.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=53c780d&url=localhost/images/7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e/thumbnails/mini-5a0dad2a2cc.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=c3b6eab&url=localhost/images/7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e/thumbnails/thumbnail-9b02124e225.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=02bd4a2&url=localhost/images/7d4cd3a3-21af-47e3-ac15-1eb3cfac5c8e/thumbnails/full-a59915ee0ad.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--9EyEF6N2--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3f8612de3669.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--7CRCj0GE--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3f8612de3669.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--7CRCj0GE--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3f8612de3669.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--64KIMtxd--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3f8612de3669.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--r2uG5Lze--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/3f8612de3669.jpg"
      }
    },
    "tag": {
      "id": "bf11d531-b20a-474f-808e-bcafaa7f85df",
      "created_at": "2019-04-08T19:38:45.159+02:00",
      "name": "MyTag",
      "label": "{\"en\":\"MyTag\",\"fr\":\"MyTag\"}",
      "url": "/public_tags/bf11d531-b20a-474f-808e-bcafaa7f85df",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#03A9F4",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "MyTag",
      "label_fr": "MyTag"
    }
  }
]</pre>
