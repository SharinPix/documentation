# Tag Image API

## Retrieve tag images

### GET api/v1/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| tag_name | Name of the tag | false |  |
| album_id | Id of album | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6IjMwMzg4NTYxLTRiZTAtNDcxZS1iOGMyLWJkN2ZhOTZjYzhjMCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6Ik15VGFnIiwiZnIiOiJNeVRhZyJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19fQ.L4fG6tyeG0T_XbWtS-IfZjLpnLChWKQdwtVDrPOARk0&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?tag_name=MyTag&amp;album_id=00324000004ijWS</pre>

#### Query Parameters

<pre>tag_name: MyTag
album_id: 00324000004ijWS</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwidXNlcl9pZCI6IjMwMzg4NTYxLTRiZTAtNDcxZS1iOGMyLWJkN2ZhOTZjYzhjMCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJNeVRhZyI6eyJlbiI6Ik15VGFnIiwiZnIiOiJNeVRhZyJ9fSwiQWNjZXNzIjp7InNlZSI6dHJ1ZSwiaW1hZ2VfdGFnIjp0cnVlfX19fQ.L4fG6tyeG0T_XbWtS-IfZjLpnLChWKQdwtVDrPOARk0
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 647dcf1b-b098-4ebe-a880-69f218876484
X-Runtime: 0.030881
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
    "id": "0eabb6d2-93bc-4430-b7a6-ba71011091ec",
    "created_at": "2019-04-08T19:38:45.773+02:00",
    "user": "30388561-4be0-471e-b8c2-bd7fa96cc8c0",
    "image": {
      "id": "893e3dc1-dfc0-4243-a6e2-393285feb6ed",
      "public_id": "893e3dc1-dfc0-4243-a6e2-393285feb6ed",
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
      "created_at": "2019-04-08T19:38:45.752+02:00",
      "updated_at": "2019-04-08T19:38:45.752+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--p8F9ADnZ--/fl_attachment/v123123/d9488ecaf0c2.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--LZCnlZNr--/c_fit,w_300/v123123/d9488ecaf0c2.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Mm147Iiw--/c_fit,h_2000,w_2000/v123123/d9488ecaf0c2.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=04e5334&url=localhost/images/893e3dc1-dfc0-4243-a6e2-393285feb6ed/thumbnails/mini-204d309b4fc.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2363e65&url=localhost/images/893e3dc1-dfc0-4243-a6e2-393285feb6ed/thumbnails/thumbnail-9bc7c0ff692.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=10fc330&url=localhost/images/893e3dc1-dfc0-4243-a6e2-393285feb6ed/thumbnails/full-7ac60fb2f13.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--26sgJm1t--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d9488ecaf0c2.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--eaYHXPno--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d9488ecaf0c2.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--eaYHXPno--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d9488ecaf0c2.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--LqvRkBJi--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d9488ecaf0c2.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2JDvZIrf--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/d9488ecaf0c2.jpg"
      }
    },
    "tag": {
      "id": "65648b79-dbca-4f37-9bbe-16c5e3c4a169",
      "created_at": "2019-04-08T19:38:45.743+02:00",
      "name": "MyTag",
      "label": "{\"en\":\"MyTag\",\"fr\":\"MyTag\"}",
      "url": "/public_tags/65648b79-dbca-4f37-9bbe-16c5e3c4a169",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#795548",
      "color_contrast": "#ffffff",
      "allow_download": false,
      "label_en": "MyTag",
      "label_fr": "MyTag"
    }
  }
]</pre>
