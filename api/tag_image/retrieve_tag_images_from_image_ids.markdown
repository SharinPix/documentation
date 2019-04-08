# Tag Image API

## Retrieve tag images from image ids

### GET api/v1/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_ids | Image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJxIjoiKiIsInRodW1ibmFpbF90YWdzIjp0cnVlLCJpc3MiOiIxZjJkZjExNC0wOTA3LTQ1NjktOTQ0Mi1mNjMxMTM5ZTBlMTYifQ.OtNfhtBzK8QR0DkGxM_GInG1XMUt-O7qVrh8N-IWZB0&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?image_ids[]=885999a5-58a5-406a-bc8e-2ac5420d60a3&amp;image_ids[]=1005f6ba-8f13-4e03-843d-5862df8a58d4&amp;image_ids[]=57671e09-8766-4852-8a3a-143efebe5d32</pre>

#### Query Parameters

<pre>image_ids: [&quot;885999a5-58a5-406a-bc8e-2ac5420d60a3&quot;, &quot;1005f6ba-8f13-4e03-843d-5862df8a58d4&quot;, &quot;57671e09-8766-4852-8a3a-143efebe5d32&quot;]</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjQsImlhdCI6MTU1NDc0NTEyNCwiaXNzIjoiMWYyZGYxMTQtMDkwNy00NTY5LTk0NDItZjYzMTEzOWUwZTE2IiwicSI6IioiLCJ0aHVtYm5haWxfdGFncyI6dHJ1ZX0.6Ej7Aa9G0PY1rdjMwb4KAhbzLhR8HmBIhXtzPx0fJMc
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8603fdf9-7523-416d-92b6-324675797a6e
X-Runtime: 0.062040
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
    "id": "195d3c09-4d5a-45c3-a665-226f951ab58c",
    "created_at": "2019-04-08T19:38:44.311+02:00",
    "user": "34a02484-0a05-441f-9397-5d50530fc2d4",
    "image": {
      "id": "885999a5-58a5-406a-bc8e-2ac5420d60a3",
      "public_id": "885999a5-58a5-406a-bc8e-2ac5420d60a3",
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
      "created_at": "2019-04-08T19:38:44.275+02:00",
      "updated_at": "2019-04-08T19:38:44.275+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ft761Nni--/fl_attachment/v123123/9167bafd0a92.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Xd8dcyVn--/c_fit,w_300/v123123/9167bafd0a92.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--veVW1kQx--/c_fit,h_2000,w_2000/v123123/9167bafd0a92.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=3de109a&url=localhost/images/885999a5-58a5-406a-bc8e-2ac5420d60a3/thumbnails/mini-dc90dc1e2ae.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=6c4953d&url=localhost/images/885999a5-58a5-406a-bc8e-2ac5420d60a3/thumbnails/thumbnail-ccd57b2e238.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=eaf930b&url=localhost/images/885999a5-58a5-406a-bc8e-2ac5420d60a3/thumbnails/full-ff3a3dc9b68.jpg"
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
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bxLHaYVn--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9167bafd0a92.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3Cx1FWTz--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9167bafd0a92.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3Cx1FWTz--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9167bafd0a92.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QaW-QqVI--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9167bafd0a92.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xaP1d3Fb--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9167bafd0a92.jpg"
      }
    },
    "tag": {
      "id": "7aab9384-1ed7-45f6-a166-afcde50f8c59",
      "created_at": "2019-04-08T19:38:44.298+02:00",
      "name": "MyTag",
      "label": "{\"en\":\"MyTag\",\"fr\":\"MyTag\"}",
      "url": "/public_tags/7aab9384-1ed7-45f6-a166-afcde50f8c59",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#009688",
      "color_contrast": "#ffffff",
      "allow_download": false,
      "label_en": "MyTag",
      "label_fr": "MyTag"
    }
  }
]</pre>
