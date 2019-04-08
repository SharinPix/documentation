# Clipboard API

## Paste clipboard

### POST /api/v1/clipboards/:id/paste

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| id | Clipboard id | false |  |
| album_id | Album id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDIsImlhdCI6MTU1NDc0NTE0MiwidXNlcl9pZCI6ImZhZmU2ODZiLWQ3M2YtNDc1ZS1hMWU2LWUyMmIwMjFiYzcyNiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjM0Ijp7IkFjY2VzcyI6eyJwYXN0ZSI6dHJ1ZX19fX0.7GpGrrcfO6BIYV4RHUyNh27-d0JGD2TSaeiXWcXeA4I&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/clipboards/63f661c2-efc8-4aa1-9168-de5a421e367c/paste</pre>

#### Body

<pre>album_id=00100000123BB234</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDIsImlhdCI6MTU1NDc0NTE0MiwidXNlcl9pZCI6ImZhZmU2ODZiLWQ3M2YtNDc1ZS1hMWU2LWUyMmIwMjFiYzcyNiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjM0Ijp7IkFjY2VzcyI6eyJwYXN0ZSI6dHJ1ZX19fX0.7GpGrrcfO6BIYV4RHUyNh27-d0JGD2TSaeiXWcXeA4I
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e9c3d28f-d6d9-45d7-ba9b-62ec9ba43137
X-Runtime: 0.063421
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 8806</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "43a691eb-c938-43a5-b8ea-2e137397c324",
    "public_id": "43a691eb-c938-43a5-b8ea-2e137397c324",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB234"
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
    "created_at": "2019-04-08T19:39:02.728+02:00",
    "updated_at": "2019-04-08T19:39:02.728+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--pDtP6Smy--/fl_attachment/v123123/13b791a59e47.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Ri18oUFy--/c_fit,w_300/v123123/13b791a59e47.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--w67FAuY6--/c_fit,h_2000,w_2000/v123123/13b791a59e47.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7cf536b&url=localhost/images/43a691eb-c938-43a5-b8ea-2e137397c324/thumbnails/mini-8f6b45ea3dc.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f7884e0&url=localhost/images/43a691eb-c938-43a5-b8ea-2e137397c324/thumbnails/thumbnail-ca77431ab18.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a3c3a58&url=localhost/images/43a691eb-c938-43a5-b8ea-2e137397c324/thumbnails/full-48da1d9a02e.jpg"
    },
    "filename": "Super Image",
    "format": "png",
    "title": null,
    "description": null,
    "page": 1,
    "group_id": "2b1c6250-de86-4e2d-b69c-eff0d8095481",
    "color": "#7D7D7D",
    "size": 3604,
    "processed": false,
    "processing_error": null,
    "album_id": "00100000123BB234",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Zs9xDm4Y--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/13b791a59e47.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HsS44HJ9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/13b791a59e47.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HsS44HJ9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/13b791a59e47.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--6nDDWT9j--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/13b791a59e47.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---uyX3-QY--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/13b791a59e47.jpg"
    }
  },
  {
    "id": "df339372-7024-42c7-ad1a-dd6731927688",
    "public_id": "df339372-7024-42c7-ad1a-dd6731927688",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB234"
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
    "created_at": "2019-04-08T19:39:02.738+02:00",
    "updated_at": "2019-04-08T19:39:02.738+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--pATa9pNe--/fl_attachment/v123123/9105085666fc.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JJwraXfD--/c_fit,w_300/v123123/9105085666fc.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--FMcAPkMf--/c_fit,h_2000,w_2000/v123123/9105085666fc.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=95098e1&url=localhost/images/df339372-7024-42c7-ad1a-dd6731927688/thumbnails/mini-197393b0baf.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=df182c1&url=localhost/images/df339372-7024-42c7-ad1a-dd6731927688/thumbnails/thumbnail-d151e725d87.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=fe23f37&url=localhost/images/df339372-7024-42c7-ad1a-dd6731927688/thumbnails/full-50a7b34ca79.jpg"
    },
    "filename": "Super Image",
    "format": "png",
    "title": null,
    "description": null,
    "page": 1,
    "group_id": "e8011a2d-7fb6-4b32-9aa9-330ee1f1e527",
    "color": "#7D7D7D",
    "size": 3604,
    "processed": false,
    "processing_error": null,
    "album_id": "00100000123BB234",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Y8zMe-Xz--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9105085666fc.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PMvEBRAP--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9105085666fc.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PMvEBRAP--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9105085666fc.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--DbSEDiZS--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9105085666fc.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--d3cVmj_V--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/9105085666fc.jpg"
    }
  },
  {
    "id": "bee64398-861e-47d5-93cd-bd665d524ae7",
    "public_id": "bee64398-861e-47d5-93cd-bd665d524ae7",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB234"
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
    "created_at": "2019-04-08T19:39:02.748+02:00",
    "updated_at": "2019-04-08T19:39:02.748+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--KUow94Uc--/fl_attachment/v123123/32cb0210fa78.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--kRjah-U8--/c_fit,w_300/v123123/32cb0210fa78.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--WSssvT1c--/c_fit,h_2000,w_2000/v123123/32cb0210fa78.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=b4aa31e&url=localhost/images/bee64398-861e-47d5-93cd-bd665d524ae7/thumbnails/mini-1b05fad4d54.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e1c4cef&url=localhost/images/bee64398-861e-47d5-93cd-bd665d524ae7/thumbnails/thumbnail-24ea9899b8e.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4df815a&url=localhost/images/bee64398-861e-47d5-93cd-bd665d524ae7/thumbnails/full-4a0de4df806.jpg"
    },
    "filename": "Super Image",
    "format": "png",
    "title": null,
    "description": null,
    "page": 1,
    "group_id": "abfe2173-2715-44ef-8d92-0d9c041fac86",
    "color": "#7D7D7D",
    "size": 3604,
    "processed": false,
    "processing_error": null,
    "album_id": "00100000123BB234",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--fy8uLXI3--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32cb0210fa78.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2m6o6dkT--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32cb0210fa78.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2m6o6dkT--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32cb0210fa78.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Nz_4rl8y--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32cb0210fa78.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ARbewcPB--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/32cb0210fa78.jpg"
    }
  }
]</pre>
