# Tag Image API

## Create tag images from tag id

### POST /api/v1/tags/:tag_id/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| tag_id | Id or Name of tag | false |  |
| image_ids | Id of images | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImI2YmY3Y2JhLWRiNGMtNGUwMC04OGM4LTA2ZGFhODkzY2FhOCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6Ik15VGFnIiwiZnIiOiJNeVRhZyJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19fQ.dI73wjxmvGfvYrN4kuxh2AG2zP9yvTU4GG0j0u0HCSg&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/tags/21bec422-691c-412a-9ec2-06c39b34547d/tag_images</pre>

#### Body

<pre>image_ids[]=d1530e91-b0fc-4ad3-b0b1-4a7ab8e8d380&image_ids[]=85d7046b-5487-4874-a89a-62a299af2bc5&image_ids[]=3011a1ed-5a9a-4ecc-8921-3b1a2d0f7cd0</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6ImI2YmY3Y2JhLWRiNGMtNGUwMC04OGM4LTA2ZGFhODkzY2FhOCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6Ik15VGFnIiwiZnIiOiJNeVRhZyJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19fQ.dI73wjxmvGfvYrN4kuxh2AG2zP9yvTU4GG0j0u0HCSg
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 406c39a2-fb09-4df6-a791-49fada4372cb
X-Runtime: 0.056012
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 10306</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "bb698588-2b06-4cac-8760-6d8ace9e0055",
    "created_at": "2019-04-08T19:38:45.361+02:00",
    "user": "b6bf7cba-db4c-4e00-88c8-06daa893caa8",
    "image": {
      "id": "3011a1ed-5a9a-4ecc-8921-3b1a2d0f7cd0",
      "public_id": "3011a1ed-5a9a-4ecc-8921-3b1a2d0f7cd0",
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
      "created_at": "2019-04-08T19:38:45.345+02:00",
      "updated_at": "2019-04-08T19:38:45.345+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s---489qNA9--/fl_attachment/v123123/466a910d848e.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EGjeBuor--/c_fit,w_300/v123123/466a910d848e.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8a0K9Lgc--/c_fit,h_2000,w_2000/v123123/466a910d848e.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=790e3d7&url=localhost/images/3011a1ed-5a9a-4ecc-8921-3b1a2d0f7cd0/thumbnails/mini-b5365be0a8e.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=555a304&url=localhost/images/3011a1ed-5a9a-4ecc-8921-3b1a2d0f7cd0/thumbnails/thumbnail-32ff8dd908a.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0bc8193&url=localhost/images/3011a1ed-5a9a-4ecc-8921-3b1a2d0f7cd0/thumbnails/full-eccccf2a73b.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bqzlT4g4--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/466a910d848e.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QMgMRTLT--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/466a910d848e.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QMgMRTLT--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/466a910d848e.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mYCnjEJ1--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/466a910d848e.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8pGWpYe7--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/466a910d848e.jpg"
      }
    },
    "tag": {
      "id": "21bec422-691c-412a-9ec2-06c39b34547d",
      "created_at": "2019-04-08T19:38:45.322+02:00",
      "name": "MyTag",
      "label": "{\"en\":\"MyTag\",\"fr\":\"MyTag\"}",
      "url": "/public_tags/21bec422-691c-412a-9ec2-06c39b34547d",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#FF9800",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "MyTag",
      "label_fr": "MyTag"
    }
  },
  {
    "id": "7c0e9ed6-88ae-4cea-8435-8048635405dd",
    "created_at": "2019-04-08T19:38:45.366+02:00",
    "user": "b6bf7cba-db4c-4e00-88c8-06daa893caa8",
    "image": {
      "id": "85d7046b-5487-4874-a89a-62a299af2bc5",
      "public_id": "85d7046b-5487-4874-a89a-62a299af2bc5",
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
      "created_at": "2019-04-08T19:38:45.339+02:00",
      "updated_at": "2019-04-08T19:38:45.339+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5Q9VwC5C--/fl_attachment/v123123/32324c9c8f33.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--uQdtNErg--/c_fit,w_300/v123123/32324c9c8f33.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--D4-ncQ79--/c_fit,h_2000,w_2000/v123123/32324c9c8f33.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=206ab5b&url=localhost/images/85d7046b-5487-4874-a89a-62a299af2bc5/thumbnails/mini-4ea5f551410.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=6f054e4&url=localhost/images/85d7046b-5487-4874-a89a-62a299af2bc5/thumbnails/thumbnail-932392c827a.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a33cdea&url=localhost/images/85d7046b-5487-4874-a89a-62a299af2bc5/thumbnails/full-35bc4cb6218.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3AWQloEJ--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32324c9c8f33.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--7ZBFQqhH--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32324c9c8f33.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--7ZBFQqhH--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32324c9c8f33.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--j50x7PrY--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32324c9c8f33.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--f1kC43Kr--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32324c9c8f33.jpg"
      }
    },
    "tag": {
      "id": "21bec422-691c-412a-9ec2-06c39b34547d",
      "created_at": "2019-04-08T19:38:45.322+02:00",
      "name": "MyTag",
      "label": "{\"en\":\"MyTag\",\"fr\":\"MyTag\"}",
      "url": "/public_tags/21bec422-691c-412a-9ec2-06c39b34547d",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#FF9800",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "MyTag",
      "label_fr": "MyTag"
    }
  },
  {
    "id": "6b22b818-a4a3-4077-ab3e-17262e8fc8b9",
    "created_at": "2019-04-08T19:38:45.371+02:00",
    "user": "b6bf7cba-db4c-4e00-88c8-06daa893caa8",
    "image": {
      "id": "d1530e91-b0fc-4ad3-b0b1-4a7ab8e8d380",
      "public_id": "d1530e91-b0fc-4ad3-b0b1-4a7ab8e8d380",
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
      "created_at": "2019-04-08T19:38:45.332+02:00",
      "updated_at": "2019-04-08T19:38:45.332+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ABqyznn---/fl_attachment/v123123/18c34f9b7d62.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--odiLGnOY--/c_fit,w_300/v123123/18c34f9b7d62.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Kl9kAd7K--/c_fit,h_2000,w_2000/v123123/18c34f9b7d62.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=60d4cf9&url=localhost/images/d1530e91-b0fc-4ad3-b0b1-4a7ab8e8d380/thumbnails/mini-917e0f82358.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=52e9329&url=localhost/images/d1530e91-b0fc-4ad3-b0b1-4a7ab8e8d380/thumbnails/thumbnail-da7d3faa937.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7cf382b&url=localhost/images/d1530e91-b0fc-4ad3-b0b1-4a7ab8e8d380/thumbnails/full-ede64f5781c.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--DhMtv1M5--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18c34f9b7d62.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NxJ7wIN4--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18c34f9b7d62.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NxJ7wIN4--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18c34f9b7d62.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--GIHNK0Bq--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18c34f9b7d62.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mBo0lrYx--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18c34f9b7d62.jpg"
      }
    },
    "tag": {
      "id": "21bec422-691c-412a-9ec2-06c39b34547d",
      "created_at": "2019-04-08T19:38:45.322+02:00",
      "name": "MyTag",
      "label": "{\"en\":\"MyTag\",\"fr\":\"MyTag\"}",
      "url": "/public_tags/21bec422-691c-412a-9ec2-06c39b34547d",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#FF9800",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "MyTag",
      "label_fr": "MyTag"
    }
  }
]</pre>
