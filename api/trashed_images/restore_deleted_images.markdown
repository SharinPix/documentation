# Trashed images API

## Restore deleted images

### DELETE api/v1/trashed_images/:image_id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhYmlsaXRpZXMiOnsiMDAxMDAwMDAxMjNCQjE4NiI6eyJBY2Nlc3MiOnsidHJhc2giOnRydWV9fX0sImlzcyI6IjE4ZTg4MzdhLWNhMGYtNGM1OC04MWM0LTgyOTFhZTBiYzA4ZiJ9.ft1nIqG3uZz0DPF7zuO0nLIp7PjJsbMyUnDxNGD8pYI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>DELETE api/v1/trashed_images/1ccbf0e2-658b-429c-bd39-f983a2d6c74d</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwiaXNzIjoiMThlODgzN2EtY2EwZi00YzU4LTgxYzQtODI5MWFlMGJjMDhmIiwiYWJpbGl0aWVzIjp7IjAwMTAwMDAwMTIzQkIxODYiOnsiQWNjZXNzIjp7InRyYXNoIjp0cnVlfX19fQ.e-qfPRI8iQnQ7QI3tyuGbK98iMJv0DxDKZlBtpufIvo
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 10d351a7-fccd-4cd0-8c81-de43749fcc38
X-Runtime: 0.018293
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2900</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "1ccbf0e2-658b-429c-bd39-f983a2d6c74d",
  "public_id": "1ccbf0e2-658b-429c-bd39-f983a2d6c74d",
  "infos": {
    "bytes": 3604,
    "created_at": "2015-09-25T13:32:55Z",
    "etag": "5a98d4d3e5d39024abf237be55e99b15",
    "format": "png",
    "height": 48,
    "resource_type": "image",
    "tags": [
      "00100000123BB186"
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
  "created_at": "2019-04-08T19:38:56.865+02:00",
  "updated_at": "2019-04-08T19:38:56.884+02:00",
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
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--IK4WUcnB--/fl_attachment/v123123/412a32c60f94.jpg",
  "original_width": 48,
  "original_height": 48,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--r9HOA8vG--/c_fit,w_300/v123123/412a32c60f94.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--oaVMA1gf--/c_fit,h_2000,w_2000/v123123/412a32c60f94.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=3a1eb77&url=localhost/images/1ccbf0e2-658b-429c-bd39-f983a2d6c74d/thumbnails/mini-3e229fec0ef.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d27f867&url=localhost/images/1ccbf0e2-658b-429c-bd39-f983a2d6c74d/thumbnails/thumbnail-123317e4ecf.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d8ab911&url=localhost/images/1ccbf0e2-658b-429c-bd39-f983a2d6c74d/thumbnails/full-c721bdfcb97.jpg"
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
  "album_id": "00100000123BB186",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--s1p40uMH--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/412a32c60f94.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZKkISjNl--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/412a32c60f94.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZKkISjNl--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/412a32c60f94.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--4EuU-oyr--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/412a32c60f94.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--wuYaaoXr--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/412a32c60f94.jpg"
  }
}</pre>
