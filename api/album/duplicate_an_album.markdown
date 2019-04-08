# Album API

## Duplicate an album

### POST /api/v1/albums/:id/duplicate

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| destination_id | Destination album id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6IjllZDI2MjgzLTMyOTktNGEwNS1iOWQ2LWUzNDI3OGZiZDQxNiIsImFiaWxpdGllcyI6e319.nf92J5toIf0s2ZP55MP_ndRN3lz9zpyUzmO0PkD19q4&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB44/duplicate</pre>

#### Body

<pre>destination_id=new_id</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6IjllZDI2MjgzLTMyOTktNGEwNS1iOWQ2LWUzNDI3OGZiZDQxNiIsImFiaWxpdGllcyI6e319.nf92J5toIf0s2ZP55MP_ndRN3lz9zpyUzmO0PkD19q4
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8fa1751b-cc0f-48ef-ae3b-e021e0cf903f
X-Runtime: 0.203286
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 12677</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "new_id",
  "public_id": "new_id",
  "images_count": 5,
  "views_count": 0,
  "upload_form": {
    "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
    "expires_at": 1555349926,
    "name": "new_id",
    "id": "a89b5b70-d820-4911-8c6d-25ab6181e9be-new_id",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjYsImlhdCI6MTU1NDc0NTEyNiwidXNlcl9pZCI6IjllZDI2MjgzLTMyOTktNGEwNS1iOWQ2LWUzNDI3OGZiZDQxNiIsImFsYnVtX2lkIjoibmV3X2lkIiwib3JnYW5pemF0aW9uX2lkIjoiYTg5YjViNzAtZDgyMC00OTExLThjNmQtMjVhYjYxODFlOWJlIn0.hSP7puZuDgK5Njb_QcuT9tYJhFzZ_bul7pPhvSQqytg",
      "phash": 1,
      "tags": "new_id",
      "timestamp": 1555349926,
      "type": "authenticated",
      "signature": "3e1ab8ddd1885c2faad4b4631e2c4ab53139014a",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "a89b5b70-d820-4911-8c6d-25ab6181e9be",
  "thumbnails": [
    {
      "id": "891fca0d-fad6-4e2a-88b0-e1f8f9ee7089",
      "public_id": "891fca0d-fad6-4e2a-88b0-e1f8f9ee7089",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB44"
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
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.797+02:00",
      "updated_at": "2019-04-08T19:38:46.807+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NxOhqjt3--/fl_attachment/v123123/2016b12123c7.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--GFzhOC4J--/c_fit,w_300/v123123/2016b12123c7.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--aeH4jLFj--/c_fit,h_2000,w_2000/v123123/2016b12123c7.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=015fda4&url=localhost/images/891fca0d-fad6-4e2a-88b0-e1f8f9ee7089/thumbnails/mini-b9139b6d4b3.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=58215d3&url=localhost/images/891fca0d-fad6-4e2a-88b0-e1f8f9ee7089/thumbnails/thumbnail-8c923fcb53e.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=754bb26&url=localhost/images/891fca0d-fad6-4e2a-88b0-e1f8f9ee7089/thumbnails/full-bfdc7ceb7c8.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "4472e354-ba15-4152-ac00-5f37979b780a",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---TI_llfL--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2016b12123c7.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yYDvtzb6--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2016b12123c7.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yYDvtzb6--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2016b12123c7.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--W7rqP-l_--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2016b12123c7.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ATqWdTn7--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2016b12123c7.jpg"
      }
    },
    {
      "id": "70fb75d0-20de-4cdc-b871-aa676a8bafbe",
      "public_id": "70fb75d0-20de-4cdc-b871-aa676a8bafbe",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB44"
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
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.758+02:00",
      "updated_at": "2019-04-08T19:38:46.770+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--h8OsAxtf--/fl_attachment/v123123/1b0cad6d6d2a.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--G2vUo0tM--/c_fit,w_300/v123123/1b0cad6d6d2a.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VeJzbs7Y--/c_fit,h_2000,w_2000/v123123/1b0cad6d6d2a.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=fb052cd&url=localhost/images/70fb75d0-20de-4cdc-b871-aa676a8bafbe/thumbnails/mini-6eb508f9f3a.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=533f6ff&url=localhost/images/70fb75d0-20de-4cdc-b871-aa676a8bafbe/thumbnails/thumbnail-90edb66420a.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=8a59f94&url=localhost/images/70fb75d0-20de-4cdc-b871-aa676a8bafbe/thumbnails/full-4991ad5b13c.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "bd01a8d1-db86-4fdc-a7a4-3876e92adcf3",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--abXU-TmC--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1b0cad6d6d2a.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PYWoPbvw--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1b0cad6d6d2a.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PYWoPbvw--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1b0cad6d6d2a.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VX7AN-q2--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1b0cad6d6d2a.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--lC05IK59--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1b0cad6d6d2a.jpg"
      }
    },
    {
      "id": "78ea73c6-7bbf-4f6e-8055-1a324c879aff",
      "public_id": "78ea73c6-7bbf-4f6e-8055-1a324c879aff",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB44"
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
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.727+02:00",
      "updated_at": "2019-04-08T19:38:46.737+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--4yki6Dfj--/fl_attachment/v123123/2cb34ef6f2b2.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--UpkWryan--/c_fit,w_300/v123123/2cb34ef6f2b2.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--FQf7T_XZ--/c_fit,h_2000,w_2000/v123123/2cb34ef6f2b2.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=49d8cc5&url=localhost/images/78ea73c6-7bbf-4f6e-8055-1a324c879aff/thumbnails/mini-d0b69cd942f.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=d0101f5&url=localhost/images/78ea73c6-7bbf-4f6e-8055-1a324c879aff/thumbnails/thumbnail-ad73a729e17.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=62772f3&url=localhost/images/78ea73c6-7bbf-4f6e-8055-1a324c879aff/thumbnails/full-0033dfb32dd.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "faaaaafc-419d-4470-9c94-403a634cc82f",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--lN_HpWm7--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2cb34ef6f2b2.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--_kqelplq--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2cb34ef6f2b2.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--_kqelplq--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2cb34ef6f2b2.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--8v8-oof8--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2cb34ef6f2b2.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xP1nW8Ya--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/2cb34ef6f2b2.jpg"
      }
    },
    {
      "id": "194af2b3-4d7b-407b-a089-c65f7d9111ec",
      "public_id": "194af2b3-4d7b-407b-a089-c65f7d9111ec",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB44"
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
      "gps_ip": [
        40.7143528,
        -74.0059731
      ],
      "gps_exifs": null,
      "gps_html": [
        48.861934399999996,
        2.348967
      ],
      "created_at": "2019-04-08T19:38:46.700+02:00",
      "updated_at": "2019-04-08T19:38:46.710+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--W0GqYltV--/fl_attachment/v123123/1dad2f25723d.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--tjowqiku--/c_fit,w_300/v123123/1dad2f25723d.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--CTtHHCjm--/c_fit,h_2000,w_2000/v123123/1dad2f25723d.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f20332c&url=localhost/images/194af2b3-4d7b-407b-a089-c65f7d9111ec/thumbnails/mini-e6ce2039d91.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9422350&url=localhost/images/194af2b3-4d7b-407b-a089-c65f7d9111ec/thumbnails/thumbnail-b6e37421d36.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=5cceccf&url=localhost/images/194af2b3-4d7b-407b-a089-c65f7d9111ec/thumbnails/full-778479f364d.jpg"
      },
      "filename": "Super Image",
      "format": "png",
      "title": null,
      "description": null,
      "page": 1,
      "group_id": "9257e0b9-6259-49b2-8b0e-30dc81d8dc56",
      "color": "#7D7D7D",
      "size": 3604,
      "processed": true,
      "processing_error": null,
      "album_id": "new_id",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--DeyxMji---/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1dad2f25723d.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--04rZjYEx--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1dad2f25723d.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--04rZjYEx--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1dad2f25723d.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ipT38l4G--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1dad2f25723d.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5_HMfpts--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/1dad2f25723d.jpg"
      }
    }
  ]
}</pre>
