# Image API API

## Duplicate an image

### POST /api/v1/images/:id/duplicate
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6IjRlZDY3MzdiLWZkZWMtNDk5YS1hMWUyLTkyYTAyN2MwNzlmNiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTI0Ijp7IkFjY2VzcyI6eyJpbWFnZV9kdXBsaWNhdGUiOnRydWV9fX19.-etoTcVqMMFU8tjsUuCx1QHl-30CMtRZ7u-h2bmsoJQ&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/images/4c4401c9-9cb1-4c50-b15e-b171de99af5e/duplicate</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6IjRlZDY3MzdiLWZkZWMtNDk5YS1hMWUyLTkyYTAyN2MwNzlmNiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTI0Ijp7IkFjY2VzcyI6eyJpbWFnZV9kdXBsaWNhdGUiOnRydWV9fX19.-etoTcVqMMFU8tjsUuCx1QHl-30CMtRZ7u-h2bmsoJQ
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e25c86d9-4804-4ffa-9185-cd8897824add
X-Runtime: 0.024607
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2934</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "bb9a3d1a-ebfc-4a29-9b22-aeb1fb57ef3b",
  "public_id": "bb9a3d1a-ebfc-4a29-9b22-aeb1fb57ef3b",
  "infos": {
    "bytes": 3604,
    "created_at": "2015-09-25T13:32:55Z",
    "etag": "5a98d4d3e5d39024abf237be55e99b15",
    "format": "png",
    "height": 48,
    "resource_type": "image",
    "tags": [
      "00100000123BB124"
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
  "created_at": "2019-04-08T19:38:52.108+02:00",
  "updated_at": "2019-04-08T19:38:52.108+02:00",
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
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--fYHykjSt--/fl_attachment/v123123/2e141b7be502.jpg",
  "original_width": 48,
  "original_height": 48,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--oZ53j9Ho--/c_fit,w_300/v123123/2e141b7be502.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--1msOk8pv--/c_fit,h_2000,w_2000/v123123/2e141b7be502.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e18463c&url=localhost/images/bb9a3d1a-ebfc-4a29-9b22-aeb1fb57ef3b/thumbnails/mini-efd2d1923ad.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2109a65&url=localhost/images/bb9a3d1a-ebfc-4a29-9b22-aeb1fb57ef3b/thumbnails/thumbnail-bfc4977f71b.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9f5e2a6&url=localhost/images/bb9a3d1a-ebfc-4a29-9b22-aeb1fb57ef3b/thumbnails/full-5f4e5d876b4.jpg"
  },
  "filename": "Super Image",
  "format": "png",
  "title": null,
  "description": null,
  "page": 1,
  "group_id": "4c4401c9-9cb1-4c50-b15e-b171de99af5e",
  "color": "#7D7D7D",
  "size": 3604,
  "processed": false,
  "processing_error": null,
  "album_id": "00100000123BB124",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HqRAFc_p--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2e141b7be502.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jRN92YUf--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2e141b7be502.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jRN92YUf--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2e141b7be502.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--WEAxTACF--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2e141b7be502.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--aMh8i8Ii--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2e141b7be502.jpg"
  }
}</pre>
