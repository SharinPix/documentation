# Image Sync API

## retrieve all images sync payload

### GET /api/v1/image_syncs

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| ids | Image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6IjQwYjdmMzZhLTFlNGItNDk4Ny05MzFmLTg4OTEwYTM3YzQ1MSJ9.F7OWGJTpS3z2c2U9dHI7gUnjzlHMacQjDl-GQCAaZCM&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/image_syncs?ids[]=14364f29-c30d-4bbb-992c-19e6031244f7&amp;ids[]=89d5c88f-bb34-4d95-babc-0f17d44e52db&amp;ids[]=efb6075d-2624-4441-ae56-97a2cb0472df&amp;ids[]=14126dd5-efd5-42d5-9bc3-faab45cf9bbf</pre>

#### Query Parameters

<pre>ids: [&quot;14364f29-c30d-4bbb-992c-19e6031244f7&quot;, &quot;89d5c88f-bb34-4d95-babc-0f17d44e52db&quot;, &quot;efb6075d-2624-4441-ae56-97a2cb0472df&quot;, &quot;14126dd5-efd5-42d5-9bc3-faab45cf9bbf&quot;]</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6IjQwYjdmMzZhLTFlNGItNDk4Ny05MzFmLTg4OTEwYTM3YzQ1MSJ9.F7OWGJTpS3z2c2U9dHI7gUnjzlHMacQjDl-GQCAaZCM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 54ea8b98-0d67-4e1a-a1d4-e71f79217394
X-Runtime: 0.036653
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 11775</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "14364f29-c30d-4bbb-992c-19e6031244f7",
    "public_id": "14364f29-c30d-4bbb-992c-19e6031244f7",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB175"
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
    "created_at": "2019-04-08T19:38:56.021+02:00",
    "updated_at": "2019-04-08T19:38:56.021+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--J8S_ZhSu--/fl_attachment/v123123/0b7e148bbd7c.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8Lazwr39--/c_fit,w_300/v123123/0b7e148bbd7c.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--32DnAk7C--/c_fit,h_2000,w_2000/v123123/0b7e148bbd7c.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a463311&url=localhost/images/14364f29-c30d-4bbb-992c-19e6031244f7/thumbnails/mini-b7f270247ab.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9d8f164&url=localhost/images/14364f29-c30d-4bbb-992c-19e6031244f7/thumbnails/thumbnail-0709b93e606.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=64f3095&url=localhost/images/14364f29-c30d-4bbb-992c-19e6031244f7/thumbnails/full-e1f99d59b80.jpg"
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
    "album_id": "00100000123BB175",
    "tag_names": [
      "test_1",
      "test_2"
    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--M0Shg406--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0b7e148bbd7c.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--C79RDmq9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0b7e148bbd7c.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--C79RDmq9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0b7e148bbd7c.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EPLzLoa1--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0b7e148bbd7c.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Go0RazPf--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0b7e148bbd7c.jpg"
    }
  },
  {
    "id": "89d5c88f-bb34-4d95-babc-0f17d44e52db",
    "public_id": "89d5c88f-bb34-4d95-babc-0f17d44e52db",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB175"
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
    "created_at": "2019-04-08T19:38:56.027+02:00",
    "updated_at": "2019-04-08T19:38:56.027+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--nuvyJDBO--/fl_attachment/v123123/a0edf094f09d.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RnkaBQwd--/c_fit,w_300/v123123/a0edf094f09d.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VGsKtKL8--/c_fit,h_2000,w_2000/v123123/a0edf094f09d.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=3c61634&url=localhost/images/89d5c88f-bb34-4d95-babc-0f17d44e52db/thumbnails/mini-d1b8739237e.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a675464&url=localhost/images/89d5c88f-bb34-4d95-babc-0f17d44e52db/thumbnails/thumbnail-18194246cc6.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=05c3c9b&url=localhost/images/89d5c88f-bb34-4d95-babc-0f17d44e52db/thumbnails/full-50964ea2eed.jpg"
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
    "album_id": "00100000123BB175",
    "tag_names": [
      "test_2",
      "test_3"
    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--MaQChEKs--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a0edf094f09d.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8-jKpNXk--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a0edf094f09d.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8-jKpNXk--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a0edf094f09d.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--r_945jbO--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a0edf094f09d.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---xyWy9S8--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a0edf094f09d.jpg"
    }
  },
  {
    "id": "efb6075d-2624-4441-ae56-97a2cb0472df",
    "public_id": "efb6075d-2624-4441-ae56-97a2cb0472df",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB175"
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
    "created_at": "2019-04-08T19:38:56.034+02:00",
    "updated_at": "2019-04-08T19:38:56.034+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--m5J9AiY1--/fl_attachment/v123123/00e65594a9e0.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--TgpRrkFo--/c_fit,w_300/v123123/00e65594a9e0.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HWNmKRcL--/c_fit,h_2000,w_2000/v123123/00e65594a9e0.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=5ac2865&url=localhost/images/efb6075d-2624-4441-ae56-97a2cb0472df/thumbnails/mini-636d71f051e.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=01af13a&url=localhost/images/efb6075d-2624-4441-ae56-97a2cb0472df/thumbnails/thumbnail-e4b15233d65.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=5f0799f&url=localhost/images/efb6075d-2624-4441-ae56-97a2cb0472df/thumbnails/full-ad7bfa8fba7.jpg"
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
    "album_id": "00100000123BB175",
    "tag_names": [
      "test_3"
    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8hjEc2ie--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00e65594a9e0.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--akwmwThE--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00e65594a9e0.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--akwmwThE--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00e65594a9e0.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--KqOvHvMn--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00e65594a9e0.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5pb8oJ-_--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00e65594a9e0.jpg"
    }
  },
  {
    "id": "14126dd5-efd5-42d5-9bc3-faab45cf9bbf",
    "public_id": "14126dd5-efd5-42d5-9bc3-faab45cf9bbf",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB175"
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
    "created_at": "2019-04-08T19:38:56.040+02:00",
    "updated_at": "2019-04-08T19:38:56.040+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Vi44ffZg--/fl_attachment/v123123/b1554075eeb7.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--oUSIdB3S--/c_fit,w_300/v123123/b1554075eeb7.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RGjv0ZGM--/c_fit,h_2000,w_2000/v123123/b1554075eeb7.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=12ad8e4&url=localhost/images/14126dd5-efd5-42d5-9bc3-faab45cf9bbf/thumbnails/mini-f4688e3d00f.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=6511465&url=localhost/images/14126dd5-efd5-42d5-9bc3-faab45cf9bbf/thumbnails/thumbnail-bd5a54676a2.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7c13450&url=localhost/images/14126dd5-efd5-42d5-9bc3-faab45cf9bbf/thumbnails/full-d3e227e63a9.jpg"
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
    "album_id": "00100000123BB175",
    "tag_names": [

    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VPRbPI0Z--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b1554075eeb7.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--E8HcnhN8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b1554075eeb7.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--E8HcnhN8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b1554075eeb7.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rS1_-gCl--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b1554075eeb7.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Rist6ftF--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b1554075eeb7.jpg"
    }
  }
]</pre>
