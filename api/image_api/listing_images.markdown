# Image API API

## Listing images

### GET /api/v1/albums/:album_id/images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzQsImlhdCI6MTU1NDc0NTEzNCwidXNlcl9pZCI6ImU4NzgyNGFkLWQ0MGYtNGUwNy1iODMxLTIyY2FkOGZhNmExZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTUxIjp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.GWjA7KCxiW8p0ab7-F2OrF63NeUr0gUsWcsgyS1fsh4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00100000123BB151/images</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzQsImlhdCI6MTU1NDc0NTEzNCwidXNlcl9pZCI6ImU4NzgyNGFkLWQ0MGYtNGUwNy1iODMxLTIyY2FkOGZhNmExZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTUxIjp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.GWjA7KCxiW8p0ab7-F2OrF63NeUr0gUsWcsgyS1fsh4
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: ae46d4ac-79ea-451b-968a-a2c6885ec6dc
X-Runtime: 0.028778
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 14506</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "2143e2e8-caaa-46b2-a8bd-1978e734ce32",
    "public_id": "2143e2e8-caaa-46b2-a8bd-1978e734ce32",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB151"
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
    "created_at": "2019-04-08T19:38:54.812+02:00",
    "updated_at": "2019-04-08T19:38:54.812+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8G__Jh9G--/fl_attachment/v123123/f63aa5f39977.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--igqziDH7--/c_fit,w_300/v123123/f63aa5f39977.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--zINdmnwp--/c_fit,h_2000,w_2000/v123123/f63aa5f39977.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=222ecc8&url=localhost/images/2143e2e8-caaa-46b2-a8bd-1978e734ce32/thumbnails/mini-8eb4ff41b28.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4bf57f8&url=localhost/images/2143e2e8-caaa-46b2-a8bd-1978e734ce32/thumbnails/thumbnail-ca5b368f787.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a0508fc&url=localhost/images/2143e2e8-caaa-46b2-a8bd-1978e734ce32/thumbnails/full-7783909418d.jpg"
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
    "album_id": "00100000123BB151",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NGFfDVJA--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f63aa5f39977.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Mj7SvrwX--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f63aa5f39977.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Mj7SvrwX--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f63aa5f39977.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--BSzQtTT4--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f63aa5f39977.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--FOVVU_VT--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f63aa5f39977.jpg"
    }
  },
  {
    "id": "e3e09e7b-ed5c-4307-bf08-6b9e2a9f4cb6",
    "public_id": "e3e09e7b-ed5c-4307-bf08-6b9e2a9f4cb6",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB151"
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
    "created_at": "2019-04-08T19:38:54.819+02:00",
    "updated_at": "2019-04-08T19:38:54.819+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--arubWAbm--/fl_attachment/v123123/7658b6df01bb.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Bqp7FTO_--/c_fit,w_300/v123123/7658b6df01bb.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EohucPUH--/c_fit,h_2000,w_2000/v123123/7658b6df01bb.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f271282&url=localhost/images/e3e09e7b-ed5c-4307-bf08-6b9e2a9f4cb6/thumbnails/mini-f2100b0a659.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=bd0c5ca&url=localhost/images/e3e09e7b-ed5c-4307-bf08-6b9e2a9f4cb6/thumbnails/thumbnail-8dad8d42428.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=8d84121&url=localhost/images/e3e09e7b-ed5c-4307-bf08-6b9e2a9f4cb6/thumbnails/full-a8d33bead28.jpg"
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
    "album_id": "00100000123BB151",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0Dpgc8qo--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7658b6df01bb.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--YlrlH5YL--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7658b6df01bb.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--YlrlH5YL--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7658b6df01bb.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bvlki5dF--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7658b6df01bb.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--parikvw1--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7658b6df01bb.jpg"
    }
  },
  {
    "id": "5bc78207-4095-4e0a-a246-a7c800b6ca94",
    "public_id": "5bc78207-4095-4e0a-a246-a7c800b6ca94",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB151"
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
    "created_at": "2019-04-08T19:38:54.826+02:00",
    "updated_at": "2019-04-08T19:38:54.826+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xYgf-Qba--/fl_attachment/v123123/6b51160ce2c1.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ptpVxXyw--/c_fit,w_300/v123123/6b51160ce2c1.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--vuZ6_y3S--/c_fit,h_2000,w_2000/v123123/6b51160ce2c1.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=113ff3a&url=localhost/images/5bc78207-4095-4e0a-a246-a7c800b6ca94/thumbnails/mini-1626e0cccc3.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=06f3891&url=localhost/images/5bc78207-4095-4e0a-a246-a7c800b6ca94/thumbnails/thumbnail-4970d921648.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7456f26&url=localhost/images/5bc78207-4095-4e0a-a246-a7c800b6ca94/thumbnails/full-1f526388bad.jpg"
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
    "album_id": "00100000123BB151",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--DTHu3Z0t--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6b51160ce2c1.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--YNuJt8Ll--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6b51160ce2c1.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--YNuJt8Ll--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6b51160ce2c1.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--k_j93_vI--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6b51160ce2c1.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HwUmTR22--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6b51160ce2c1.jpg"
    }
  },
  {
    "id": "7cb94010-010b-48cc-902b-c6dc0bd7ea25",
    "public_id": "7cb94010-010b-48cc-902b-c6dc0bd7ea25",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB151"
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
    "created_at": "2019-04-08T19:38:54.832+02:00",
    "updated_at": "2019-04-08T19:38:54.832+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--gQrsgIRr--/fl_attachment/v123123/7f4a4678031f.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--FkX8ahZF--/c_fit,w_300/v123123/7f4a4678031f.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Xk94jWk7--/c_fit,h_2000,w_2000/v123123/7f4a4678031f.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2621972&url=localhost/images/7cb94010-010b-48cc-902b-c6dc0bd7ea25/thumbnails/mini-fa23e06b102.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9a0a3f5&url=localhost/images/7cb94010-010b-48cc-902b-c6dc0bd7ea25/thumbnails/thumbnail-51e63a0a21f.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=20a8161&url=localhost/images/7cb94010-010b-48cc-902b-c6dc0bd7ea25/thumbnails/full-ed27a57e6a6.jpg"
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
    "album_id": "00100000123BB151",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--qBL1XN_T--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7f4a4678031f.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rSuTqLlt--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7f4a4678031f.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rSuTqLlt--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7f4a4678031f.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--QUpWAPFE--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7f4a4678031f.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3OetQF_D--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7f4a4678031f.jpg"
    }
  },
  {
    "id": "9ef1825a-6f92-4b3d-b197-5ed7b9be1baa",
    "public_id": "9ef1825a-6f92-4b3d-b197-5ed7b9be1baa",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB151"
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
    "created_at": "2019-04-08T19:38:54.839+02:00",
    "updated_at": "2019-04-08T19:38:54.839+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--KzKC-8tg--/fl_attachment/v123123/9a4ff9c98a05.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--K58BCkLD--/c_fit,w_300/v123123/9a4ff9c98a05.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--897HOR31--/c_fit,h_2000,w_2000/v123123/9a4ff9c98a05.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0802384&url=localhost/images/9ef1825a-6f92-4b3d-b197-5ed7b9be1baa/thumbnails/mini-4957b3ad0b9.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=dda1d2e&url=localhost/images/9ef1825a-6f92-4b3d-b197-5ed7b9be1baa/thumbnails/thumbnail-142084ae6cd.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=974b9d1&url=localhost/images/9ef1825a-6f92-4b3d-b197-5ed7b9be1baa/thumbnails/full-4009906202c.jpg"
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
    "album_id": "00100000123BB151",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0DBJc7pe--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9a4ff9c98a05.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ETk3zbJ2--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9a4ff9c98a05.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ETk3zbJ2--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9a4ff9c98a05.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--gozRub0s--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9a4ff9c98a05.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--H6gFK_tR--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9a4ff9c98a05.jpg"
    }
  }
]</pre>
