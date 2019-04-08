# Image Sync API

## album resync return images from ids with position

### GET /api/v1/image_syncs

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| ids | Image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6ImUxYWZkMTk1LWI1NzItNGVkNy1hZWIyLTFlYjg2OTAzNTM4NiJ9.MnFo9kXFGgfuVjrMHlLotwma757Q-UkkLqMoUN6MxLI&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/image_syncs?ids[]=907c9f10-d4ae-406d-9cb5-f836fd9e7c80&amp;ids[]=d89d0681-7bb8-4798-a329-9434d751fa0c&amp;ids[]=3bafd689-308a-47c2-a945-b71c0f7a6361&amp;ids[]=4926e5f7-0ee9-4680-9f4b-61c1827f04d0</pre>

#### Query Parameters

<pre>ids: [&quot;907c9f10-d4ae-406d-9cb5-f836fd9e7c80&quot;, &quot;d89d0681-7bb8-4798-a329-9434d751fa0c&quot;, &quot;3bafd689-308a-47c2-a945-b71c0f7a6361&quot;, &quot;4926e5f7-0ee9-4680-9f4b-61c1827f04d0&quot;]</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6ImUxYWZkMTk1LWI1NzItNGVkNy1hZWIyLTFlYjg2OTAzNTM4NiJ9.MnFo9kXFGgfuVjrMHlLotwma757Q-UkkLqMoUN6MxLI
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4f6af8d1-4aa4-46c0-8fa3-381a57d33450
X-Runtime: 0.032363
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 11733</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "3bafd689-308a-47c2-a945-b71c0f7a6361",
    "public_id": "3bafd689-308a-47c2-a945-b71c0f7a6361",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB177"
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
    "created_at": "2019-04-08T19:38:56.184+02:00",
    "updated_at": "2019-04-08T19:38:56.184+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HeH1kiTv--/fl_attachment/v123123/b13fdd07a86b.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rC80wqVK--/c_fit,w_300/v123123/b13fdd07a86b.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--SIuY0-od--/c_fit,h_2000,w_2000/v123123/b13fdd07a86b.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7da432d&url=localhost/images/3bafd689-308a-47c2-a945-b71c0f7a6361/thumbnails/mini-a880de5b396.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=cd0c974&url=localhost/images/3bafd689-308a-47c2-a945-b71c0f7a6361/thumbnails/thumbnail-c82e08b035e.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=39d1bba&url=localhost/images/3bafd689-308a-47c2-a945-b71c0f7a6361/thumbnails/full-a4ca1a7b290.jpg"
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
    "album_id": "00100000123BB177",
    "tag_names": [

    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--lao9EcJZ--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b13fdd07a86b.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--s2-9-W43--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b13fdd07a86b.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--s2-9-W43--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b13fdd07a86b.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--MjJaGoD2--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b13fdd07a86b.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--iVYw5kRz--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/b13fdd07a86b.jpg"
    }
  },
  {
    "id": "d89d0681-7bb8-4798-a329-9434d751fa0c",
    "public_id": "d89d0681-7bb8-4798-a329-9434d751fa0c",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB177"
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
    "created_at": "2019-04-08T19:38:56.177+02:00",
    "updated_at": "2019-04-08T19:38:56.177+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--07roXBGi--/fl_attachment/v123123/c40364f2a974.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NQqjoi_z--/c_fit,w_300/v123123/c40364f2a974.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--UEl13nS---/c_fit,h_2000,w_2000/v123123/c40364f2a974.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=c88b5cf&url=localhost/images/d89d0681-7bb8-4798-a329-9434d751fa0c/thumbnails/mini-b81644cf799.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=b6e46d3&url=localhost/images/d89d0681-7bb8-4798-a329-9434d751fa0c/thumbnails/thumbnail-e0da78fc65b.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=0b2991a&url=localhost/images/d89d0681-7bb8-4798-a329-9434d751fa0c/thumbnails/full-53da06c2e59.jpg"
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
    "album_id": "00100000123BB177",
    "tag_names": [

    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--58F6hMLB--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c40364f2a974.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--wPMSRbfr--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c40364f2a974.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--wPMSRbfr--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c40364f2a974.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Uue_bnox--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c40364f2a974.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8z5aoHZm--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c40364f2a974.jpg"
    }
  },
  {
    "id": "4926e5f7-0ee9-4680-9f4b-61c1827f04d0",
    "public_id": "4926e5f7-0ee9-4680-9f4b-61c1827f04d0",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB177"
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
    "created_at": "2019-04-08T19:38:56.190+02:00",
    "updated_at": "2019-04-08T19:38:56.190+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Ip8QCKBl--/fl_attachment/v123123/07db96930ced.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--UMmcjPvC--/c_fit,w_300/v123123/07db96930ced.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rHrqNBP0--/c_fit,h_2000,w_2000/v123123/07db96930ced.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7d0aabb&url=localhost/images/4926e5f7-0ee9-4680-9f4b-61c1827f04d0/thumbnails/mini-96468069116.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1d382b4&url=localhost/images/4926e5f7-0ee9-4680-9f4b-61c1827f04d0/thumbnails/thumbnail-0109e3f9efc.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=201f1c2&url=localhost/images/4926e5f7-0ee9-4680-9f4b-61c1827f04d0/thumbnails/full-644e8b0bb9d.jpg"
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
    "album_id": "00100000123BB177",
    "tag_names": [

    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--REuyupIz--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/07db96930ced.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--sW9Z73Hn--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/07db96930ced.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--sW9Z73Hn--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/07db96930ced.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--y26dxWc2--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/07db96930ced.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZwvIKc_F--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/07db96930ced.jpg"
    }
  },
  {
    "id": "907c9f10-d4ae-406d-9cb5-f836fd9e7c80",
    "public_id": "907c9f10-d4ae-406d-9cb5-f836fd9e7c80",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB177"
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
    "created_at": "2019-04-08T19:38:56.171+02:00",
    "updated_at": "2019-04-08T19:38:56.171+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Cg4mcBuq--/fl_attachment/v123123/a73f8043fae9.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Z76BFRu0--/c_fit,w_300/v123123/a73f8043fae9.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZhgnaseB--/c_fit,h_2000,w_2000/v123123/a73f8043fae9.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=075ad13&url=localhost/images/907c9f10-d4ae-406d-9cb5-f836fd9e7c80/thumbnails/mini-7cdeed78641.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=53d4618&url=localhost/images/907c9f10-d4ae-406d-9cb5-f836fd9e7c80/thumbnails/thumbnail-c0aa82ca32a.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=b48878a&url=localhost/images/907c9f10-d4ae-406d-9cb5-f836fd9e7c80/thumbnails/full-f6a5d0985fe.jpg"
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
    "album_id": "00100000123BB177",
    "tag_names": [

    ],
    "user_sfid": null,
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yKpYsal1--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a73f8043fae9.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--76W5361q--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a73f8043fae9.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--76W5361q--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a73f8043fae9.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--d34_aS6Y--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a73f8043fae9.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PmLYVAJ4--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/a73f8043fae9.jpg"
    }
  }
]</pre>
