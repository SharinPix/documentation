# Sticker API API

## Listing all images in an sticker album

### GET /api/v1/stickers
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwidXNlcl9pZCI6IjJmMzM5MDlmLTY0YTItNDQyZC04MThiLWQ3Mjk1YzFiYjhmMCIsImFiaWxpdGllcyI6eyJtYWluX2FsYnVtIjp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImltYWdlX2xpc3QiOnRydWUsImltYWdlX2Fubm90YXRlIjp0cnVlfX19fQ.O_RjVTla1uUFHpybH2Tao1U-xOi1-YMgYxpfWuwqtmM&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/stickers</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjgsImlhdCI6MTU1NDc0NTEyOCwidXNlcl9pZCI6IjJmMzM5MDlmLTY0YTItNDQyZC04MThiLWQ3Mjk1YzFiYjhmMCIsImFiaWxpdGllcyI6eyJtYWluX2FsYnVtIjp7IkFjY2VzcyI6eyJzZWUiOnRydWUsImltYWdlX2xpc3QiOnRydWUsImltYWdlX2Fubm90YXRlIjp0cnVlfX19fQ.O_RjVTla1uUFHpybH2Tao1U-xOi1-YMgYxpfWuwqtmM
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: dc758b34-23c7-4390-9e9b-05783baed96a
X-Runtime: 0.038526
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 14526</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "34471e5d-20f7-4ef5-9139-483b91237eb1",
    "public_id": "34471e5d-20f7-4ef5-9139-483b91237eb1",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "_sharinpix_sticker"
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
    "created_at": "2019-04-08T19:38:48.708+02:00",
    "updated_at": "2019-04-08T19:38:48.708+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ShYCffC9--/fl_attachment/v123123/6d1c6d363bce.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ylYyM1OW--/c_fit,w_300/v123123/6d1c6d363bce.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--BJMERWab--/c_fit,h_2000,w_2000/v123123/6d1c6d363bce.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d7d5839&url=localhost/images/34471e5d-20f7-4ef5-9139-483b91237eb1/thumbnails/mini-a06cb4a823d.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0628090&url=localhost/images/34471e5d-20f7-4ef5-9139-483b91237eb1/thumbnails/thumbnail-eaddc1ab327.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f6e4bcb&url=localhost/images/34471e5d-20f7-4ef5-9139-483b91237eb1/thumbnails/full-7e22003e033.jpg"
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
    "album_id": "_sharinpix_sticker",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dsAs9X-U--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6d1c6d363bce.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--i5ZCJQWg--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6d1c6d363bce.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--i5ZCJQWg--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6d1c6d363bce.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OK8N7Ifm--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6d1c6d363bce.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--b4_gpPwl--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6d1c6d363bce.jpg"
    }
  },
  {
    "id": "9bfeac08-5653-47fe-b938-425b26a83b24",
    "public_id": "9bfeac08-5653-47fe-b938-425b26a83b24",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "_sharinpix_sticker"
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
    "created_at": "2019-04-08T19:38:48.720+02:00",
    "updated_at": "2019-04-08T19:38:48.720+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--bMZeW1gF--/fl_attachment/v123123/748c08e2663c.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Ka1-N8NC--/c_fit,w_300/v123123/748c08e2663c.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--gm65fN1J--/c_fit,h_2000,w_2000/v123123/748c08e2663c.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=ec95ade&url=localhost/images/9bfeac08-5653-47fe-b938-425b26a83b24/thumbnails/mini-1263acc8f21.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0ee6e1d&url=localhost/images/9bfeac08-5653-47fe-b938-425b26a83b24/thumbnails/thumbnail-ea25ddc36aa.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a94a33f&url=localhost/images/9bfeac08-5653-47fe-b938-425b26a83b24/thumbnails/full-31fb83b7a72.jpg"
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
    "album_id": "_sharinpix_sticker",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--AKJHX1PL--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/748c08e2663c.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3TfvLJKQ--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/748c08e2663c.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3TfvLJKQ--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/748c08e2663c.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jvpt7AEH--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/748c08e2663c.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RmmfAprz--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/748c08e2663c.jpg"
    }
  },
  {
    "id": "2ae729f8-c3b6-4a47-8098-5c97f50caeae",
    "public_id": "2ae729f8-c3b6-4a47-8098-5c97f50caeae",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "_sharinpix_sticker"
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
    "created_at": "2019-04-08T19:38:48.730+02:00",
    "updated_at": "2019-04-08T19:38:48.730+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0KRxScvY--/fl_attachment/v123123/873523bd026e.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--raF2ZEvs--/c_fit,w_300/v123123/873523bd026e.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--hCFjOUDl--/c_fit,h_2000,w_2000/v123123/873523bd026e.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7f68d84&url=localhost/images/2ae729f8-c3b6-4a47-8098-5c97f50caeae/thumbnails/mini-4cf1331f489.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1d13989&url=localhost/images/2ae729f8-c3b6-4a47-8098-5c97f50caeae/thumbnails/thumbnail-8ff8a7fdb30.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d509ff0&url=localhost/images/2ae729f8-c3b6-4a47-8098-5c97f50caeae/thumbnails/full-f321acc718e.jpg"
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
    "album_id": "_sharinpix_sticker",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ntMlx7q4--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/873523bd026e.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--I7aWnXmO--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/873523bd026e.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--I7aWnXmO--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/873523bd026e.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5kjTgO6e--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/873523bd026e.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--lCPXvF3a--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/873523bd026e.jpg"
    }
  },
  {
    "id": "a6cd499e-025e-4c2e-bb6b-49c7323c6fe0",
    "public_id": "a6cd499e-025e-4c2e-bb6b-49c7323c6fe0",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "_sharinpix_sticker"
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
    "created_at": "2019-04-08T19:38:48.747+02:00",
    "updated_at": "2019-04-08T19:38:48.747+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--E7pjk0K7--/fl_attachment/v123123/00918b1f2e1a.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--SqaF8Ta8--/c_fit,w_300/v123123/00918b1f2e1a.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--upBWcL6J--/c_fit,h_2000,w_2000/v123123/00918b1f2e1a.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e1153fd&url=localhost/images/a6cd499e-025e-4c2e-bb6b-49c7323c6fe0/thumbnails/mini-4e23a5de16e.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2a10c37&url=localhost/images/a6cd499e-025e-4c2e-bb6b-49c7323c6fe0/thumbnails/thumbnail-ce50a7943b6.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=5dd15be&url=localhost/images/a6cd499e-025e-4c2e-bb6b-49c7323c6fe0/thumbnails/full-f48295d5c5a.jpg"
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
    "album_id": "_sharinpix_sticker",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--IgaM3Ysh--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00918b1f2e1a.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Ud2leapt--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00918b1f2e1a.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Ud2leapt--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00918b1f2e1a.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--qPyeD-Ol--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00918b1f2e1a.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZKhkbDoK--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/00918b1f2e1a.jpg"
    }
  },
  {
    "id": "00627bb3-a035-4f41-be55-6b0fa17ef2d0",
    "public_id": "00627bb3-a035-4f41-be55-6b0fa17ef2d0",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "_sharinpix_sticker"
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
    "created_at": "2019-04-08T19:38:48.760+02:00",
    "updated_at": "2019-04-08T19:38:48.760+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--i3pIWoNZ--/fl_attachment/v123123/18d380a3d129.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--4ntIG7Am--/c_fit,w_300/v123123/18d380a3d129.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VL8f2KeC--/c_fit,h_2000,w_2000/v123123/18d380a3d129.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e4ce298&url=localhost/images/00627bb3-a035-4f41-be55-6b0fa17ef2d0/thumbnails/mini-30c904b195a.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7c584ec&url=localhost/images/00627bb3-a035-4f41-be55-6b0fa17ef2d0/thumbnails/thumbnail-f9a02237918.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a2aa795&url=localhost/images/00627bb3-a035-4f41-be55-6b0fa17ef2d0/thumbnails/full-6896a47fb33.jpg"
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
    "album_id": "_sharinpix_sticker",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZN4E7n_3--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18d380a3d129.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rx-XrPzv--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18d380a3d129.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rx-XrPzv--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18d380a3d129.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--nxyk-LoT--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18d380a3d129.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--XGGTCul6--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/18d380a3d129.jpg"
    }
  }
]</pre>
