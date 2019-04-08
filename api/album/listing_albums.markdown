# Album API

## Listing albums

### GET /api/v1/albums
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImJlNTk3YzZmLWIxNmQtNDVhMy1hMGE5LTI3YTBmYjYxYWMyMCIsImFiaWxpdGllcyI6e319.rTKKNsHcmmXMG3wl0_5HzL5jy-7W340nVHdjPUvG3o8&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImJlNTk3YzZmLWIxNmQtNDVhMy1hMGE5LTI3YTBmYjYxYWMyMCIsImFiaWxpdGllcyI6e319.rTKKNsHcmmXMG3wl0_5HzL5jy-7W340nVHdjPUvG3o8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: eba10117-6eee-4c39-a800-dbabe752e6b8
X-Runtime: 0.038790
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 14931</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "00100000123BB54",
    "public_id": "00100000123BB54",
    "images_count": 1,
    "thumbnails": [
      {
        "id": "989373ab-67f7-4756-878f-da93d234ccd0",
        "public_id": "989373ab-67f7-4756-878f-da93d234ccd0",
        "infos": {
          "bytes": 3604,
          "created_at": "2015-09-25T13:32:55Z",
          "etag": "5a98d4d3e5d39024abf237be55e99b15",
          "format": "png",
          "height": 48,
          "resource_type": "image",
          "tags": [
            "00100000123BB54"
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
        "created_at": "2019-04-08T19:38:47.804+02:00",
        "updated_at": "2019-04-08T19:38:47.804+02:00",
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
        "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--akaRVkA3--/fl_attachment/v123123/6786cf7d6e31.jpg",
        "original_width": 48,
        "original_height": 48,
        "external_urls": {
          "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Cmwq-BO_--/c_fit,w_300/v123123/6786cf7d6e31.jpg",
          "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--he5GToCZ--/c_fit,h_2000,w_2000/v123123/6786cf7d6e31.jpg",
          "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=ef1051c&url=localhost/images/989373ab-67f7-4756-878f-da93d234ccd0/thumbnails/mini-dc09bf03960.jpg",
          "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=c647eab&url=localhost/images/989373ab-67f7-4756-878f-da93d234ccd0/thumbnails/thumbnail-67ac76db435.jpg",
          "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4db804f&url=localhost/images/989373ab-67f7-4756-878f-da93d234ccd0/thumbnails/full-d90208e4e62.jpg"
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
        "album_id": "00100000123BB54",
        "thumbnails": {
          "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--nun2rSdh--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6786cf7d6e31.jpg",
          "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--83yiVbJh--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6786cf7d6e31.jpg",
          "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--83yiVbJh--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6786cf7d6e31.jpg",
          "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VZgreYDx--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6786cf7d6e31.jpg",
          "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--meG0XgBW--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/6786cf7d6e31.jpg"
        }
      }
    ]
  },
  {
    "id": "00100000123BB53",
    "public_id": "00100000123BB53",
    "images_count": 1,
    "thumbnails": [
      {
        "id": "3b9491ff-1cbc-42c6-9c28-d26b5cb6688a",
        "public_id": "3b9491ff-1cbc-42c6-9c28-d26b5cb6688a",
        "infos": {
          "bytes": 3604,
          "created_at": "2015-09-25T13:32:55Z",
          "etag": "5a98d4d3e5d39024abf237be55e99b15",
          "format": "png",
          "height": 48,
          "resource_type": "image",
          "tags": [
            "00100000123BB53"
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
        "created_at": "2019-04-08T19:38:47.797+02:00",
        "updated_at": "2019-04-08T19:38:47.797+02:00",
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
        "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--E5XzeJSW--/fl_attachment/v123123/7a0ac2660b75.jpg",
        "original_width": 48,
        "original_height": 48,
        "external_urls": {
          "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--nWKYEWyi--/c_fit,w_300/v123123/7a0ac2660b75.jpg",
          "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jSV4fTSX--/c_fit,h_2000,w_2000/v123123/7a0ac2660b75.jpg",
          "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=c2ec5d3&url=localhost/images/3b9491ff-1cbc-42c6-9c28-d26b5cb6688a/thumbnails/mini-0fef5e81edd.jpg",
          "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=86ff9cd&url=localhost/images/3b9491ff-1cbc-42c6-9c28-d26b5cb6688a/thumbnails/thumbnail-0955a19c2eb.jpg",
          "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=674acde&url=localhost/images/3b9491ff-1cbc-42c6-9c28-d26b5cb6688a/thumbnails/full-8eb0e94af68.jpg"
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
        "album_id": "00100000123BB53",
        "thumbnails": {
          "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VyTFGcCN--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7a0ac2660b75.jpg",
          "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--X2KFMEWh--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7a0ac2660b75.jpg",
          "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--X2KFMEWh--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7a0ac2660b75.jpg",
          "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--XWxvZSQa--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7a0ac2660b75.jpg",
          "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dy7ZSDuE--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/7a0ac2660b75.jpg"
        }
      }
    ]
  },
  {
    "id": "00100000123BB52",
    "public_id": "00100000123BB52",
    "images_count": 1,
    "thumbnails": [
      {
        "id": "cfbfec2f-076e-4356-8939-516282929691",
        "public_id": "cfbfec2f-076e-4356-8939-516282929691",
        "infos": {
          "bytes": 3604,
          "created_at": "2015-09-25T13:32:55Z",
          "etag": "5a98d4d3e5d39024abf237be55e99b15",
          "format": "png",
          "height": 48,
          "resource_type": "image",
          "tags": [
            "00100000123BB52"
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
        "created_at": "2019-04-08T19:38:47.791+02:00",
        "updated_at": "2019-04-08T19:38:47.791+02:00",
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
        "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--psn6McnG--/fl_attachment/v123123/38ed6906e41b.jpg",
        "original_width": 48,
        "original_height": 48,
        "external_urls": {
          "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--o8TQdQLZ--/c_fit,w_300/v123123/38ed6906e41b.jpg",
          "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--j2OyJC7l--/c_fit,h_2000,w_2000/v123123/38ed6906e41b.jpg",
          "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=6820cf6&url=localhost/images/cfbfec2f-076e-4356-8939-516282929691/thumbnails/mini-4bccc202593.jpg",
          "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=8303ff6&url=localhost/images/cfbfec2f-076e-4356-8939-516282929691/thumbnails/thumbnail-5697a3b01fd.jpg",
          "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=4ab8f8e&url=localhost/images/cfbfec2f-076e-4356-8939-516282929691/thumbnails/full-c5ede7cf544.jpg"
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
        "album_id": "00100000123BB52",
        "thumbnails": {
          "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--CfRz1o3Y--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/38ed6906e41b.jpg",
          "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yMHLYSC_--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/38ed6906e41b.jpg",
          "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yMHLYSC_--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/38ed6906e41b.jpg",
          "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--_701WN3z--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/38ed6906e41b.jpg",
          "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--MzKFzEGY--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/38ed6906e41b.jpg"
        }
      }
    ]
  },
  {
    "id": "00100000123BB51",
    "public_id": "00100000123BB51",
    "images_count": 1,
    "thumbnails": [
      {
        "id": "64981e48-1e27-498d-9ef6-ae91d4081e25",
        "public_id": "64981e48-1e27-498d-9ef6-ae91d4081e25",
        "infos": {
          "bytes": 3604,
          "created_at": "2015-09-25T13:32:55Z",
          "etag": "5a98d4d3e5d39024abf237be55e99b15",
          "format": "png",
          "height": 48,
          "resource_type": "image",
          "tags": [
            "00100000123BB51"
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
        "created_at": "2019-04-08T19:38:47.784+02:00",
        "updated_at": "2019-04-08T19:38:47.784+02:00",
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
        "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Nz8WEcIb--/fl_attachment/v123123/c1edc2208c1b.jpg",
        "original_width": 48,
        "original_height": 48,
        "external_urls": {
          "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HX-b9z9S--/c_fit,w_300/v123123/c1edc2208c1b.jpg",
          "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--SY8KfLEj--/c_fit,h_2000,w_2000/v123123/c1edc2208c1b.jpg",
          "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=8868b25&url=localhost/images/64981e48-1e27-498d-9ef6-ae91d4081e25/thumbnails/mini-9d01531faa4.jpg",
          "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=e20146e&url=localhost/images/64981e48-1e27-498d-9ef6-ae91d4081e25/thumbnails/thumbnail-cbfcca28f24.jpg",
          "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=8d323bf&url=localhost/images/64981e48-1e27-498d-9ef6-ae91d4081e25/thumbnails/full-375b24cad69.jpg"
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
        "album_id": "00100000123BB51",
        "thumbnails": {
          "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--FONtRzzd--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c1edc2208c1b.jpg",
          "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--C6VlD_6u--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c1edc2208c1b.jpg",
          "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--C6VlD_6u--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c1edc2208c1b.jpg",
          "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xVvVEJdt--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c1edc2208c1b.jpg",
          "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--26dZItsX--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c1edc2208c1b.jpg"
        }
      }
    ]
  },
  {
    "id": "00100000123BB50",
    "public_id": "00100000123BB50",
    "images_count": 1,
    "thumbnails": [
      {
        "id": "4f76c89b-e114-4b2a-b0b2-97fc2bb6f663",
        "public_id": "4f76c89b-e114-4b2a-b0b2-97fc2bb6f663",
        "infos": {
          "bytes": 3604,
          "created_at": "2015-09-25T13:32:55Z",
          "etag": "5a98d4d3e5d39024abf237be55e99b15",
          "format": "png",
          "height": 48,
          "resource_type": "image",
          "tags": [
            "00100000123BB50"
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
        "created_at": "2019-04-08T19:38:47.777+02:00",
        "updated_at": "2019-04-08T19:38:47.777+02:00",
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
        "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--r2sIHcHP--/fl_attachment/v123123/397976ca97fc.jpg",
        "original_width": 48,
        "original_height": 48,
        "external_urls": {
          "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---n4j8jK3--/c_fit,w_300/v123123/397976ca97fc.jpg",
          "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jzEVq-VT--/c_fit,h_2000,w_2000/v123123/397976ca97fc.jpg",
          "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7bf215e&url=localhost/images/4f76c89b-e114-4b2a-b0b2-97fc2bb6f663/thumbnails/mini-118d694eb13.jpg",
          "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9cabecf&url=localhost/images/4f76c89b-e114-4b2a-b0b2-97fc2bb6f663/thumbnails/thumbnail-07c04908025.jpg",
          "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=91d9109&url=localhost/images/4f76c89b-e114-4b2a-b0b2-97fc2bb6f663/thumbnails/full-6a853880679.jpg"
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
        "album_id": "00100000123BB50",
        "thumbnails": {
          "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--6feoAqTy--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/397976ca97fc.jpg",
          "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--K5JuNCA6--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/397976ca97fc.jpg",
          "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--K5JuNCA6--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/397976ca97fc.jpg",
          "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--XNJJuxys--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/397976ca97fc.jpg",
          "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--__nDtmFx--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/397976ca97fc.jpg"
        }
      }
    ]
  }
]</pre>
