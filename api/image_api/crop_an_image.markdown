# Image API API

## Crop an image

### PUT /api/v1/images/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| rotation | Image rotation | false |  |
| crop_x | Image crop coordinate x | false |  |
| crop_y | Image crop coordinate y | false |  |
| crop_w | Image crop coordinate w | false |  |
| crop_h | Image crop coordinate h | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6ImUxMzUwZmNlLTdiMWUtNGNhMi1hNTgwLTBmMjcxOWFhN2JlNSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTM2Ijp7IkFjY2VzcyI6eyJpbWFnZV9jcm9wIjp0cnVlfX19fQ.bV1nKfG7wHWWorfn3WQRKm6kwhI037u1eWpnxmnuozk&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/7c13e836-c3ad-46de-be65-202e27498347</pre>

#### Body

<pre>rotation=0&crop_x=3&crop_y=2&crop_w=10&crop_h=11</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzMsImlhdCI6MTU1NDc0NTEzMywidXNlcl9pZCI6ImUxMzUwZmNlLTdiMWUtNGNhMi1hNTgwLTBmMjcxOWFhN2JlNSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTM2Ijp7IkFjY2VzcyI6eyJpbWFnZV9jcm9wIjp0cnVlfX19fQ.a-7d9NMMehl17Acxg9Hqr4ALlKITwldWpN3rXFnLeIc
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 0c56e630-1d15-4df1-b4fb-b17309e5abd4
X-Runtime: 0.017418
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 3027</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "7c13e836-c3ad-46de-be65-202e27498347",
  "public_id": "7c13e836-c3ad-46de-be65-202e27498347",
  "infos": {
    "bytes": 3604,
    "created_at": "2015-09-25T13:32:55Z",
    "etag": "5a98d4d3e5d39024abf237be55e99b15",
    "format": "png",
    "height": 48,
    "resource_type": "image",
    "tags": [
      "00100000123BB136"
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
  "created_at": "2019-04-08T19:38:52.987+02:00",
  "updated_at": "2019-04-08T19:38:53.001+02:00",
  "taken_at": null,
  "width": 10,
  "height": 11,
  "rotation": 0,
  "crop_x": 3.0,
  "crop_y": 2.0,
  "crop_w": 10.0,
  "crop_h": 11.0,
  "metadatas": {
  },
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--YW4jKx3a--/fl_attachment/v123123/297f850d3d7c.jpg",
  "original_width": 48,
  "original_height": 48,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--IH9ZbEYD--/c_crop,h_11,w_10,x_3,y_2/c_fit,w_300/v123123/297f850d3d7c.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2jvg8gu5--/c_crop,h_11,w_10,x_3,y_2/c_fit,h_2000,w_2000/v123123/297f850d3d7c.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=bb0a40b&url=localhost/images/7c13e836-c3ad-46de-be65-202e27498347/thumbnails/mini-922eb75a979.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=05b7162&url=localhost/images/7c13e836-c3ad-46de-be65-202e27498347/thumbnails/thumbnail-d4009a8bea4.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=dab0c30&url=localhost/images/7c13e836-c3ad-46de-be65-202e27498347/thumbnails/full-09c9cbb9d9c.jpg"
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
  "album_id": "00100000123BB136",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--H1Hr2-2---/fl_attachment/dpr_auto,q_auto,f_auto/v123123/297f850d3d7c.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--G6pFnC16--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/297f850d3d7c.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--_qztmKZw--/c_crop,h_11,w_10,x_3,y_2/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/297f850d3d7c.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--G2-BuPKM--/c_crop,h_11,w_10,x_3,y_2/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/297f850d3d7c.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--aEshVGgT--/c_crop,h_11,w_10,x_3,y_2/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/297f850d3d7c.jpg"
  }
}</pre>
