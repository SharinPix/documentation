# Tag Image API

## return subset of tag images

### GET api/v1/tag_images

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_ids | Image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJxIjoiS2V2YW4iLCJ0aHVtYm5haWxfdGFncyI6dHJ1ZSwiaXNzIjoiOWI0MDc3ZjItNzQxYS00MjNlLTgzZjgtZWU0Y2MyYzZjNWU3In0.Wgq00Lw5nQpLVPvROMcd9xy_BarVVB1w2w6aUV-9ANs&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tag_images?image_ids[]=bb8f5d5a-ff08-4655-9c68-c568e23883ee</pre>

#### Query Parameters

<pre>image_ids: [&quot;bb8f5d5a-ff08-4655-9c68-c568e23883ee&quot;]</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjUsImlhdCI6MTU1NDc0NTEyNSwiaXNzIjoiOWI0MDc3ZjItNzQxYS00MjNlLTgzZjgtZWU0Y2MyYzZjNWU3IiwicSI6IktldmFuIiwidGh1bWJuYWlsX3RhZ3MiOnRydWV9.fB9O0nFlkbfrrter6YyVrNe7ABcrf2jTuCLY9EU0nhE
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 4a02c5c7-47d5-42db-af26-75261295fb41
X-Runtime: 0.062895
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 3436</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "97513f2b-5715-4e14-973f-3de184286503",
    "created_at": "2019-04-08T19:38:44.803+02:00",
    "user": "92bf1c7e-9779-468b-a3c6-3d9121a76432",
    "image": {
      "id": "bb8f5d5a-ff08-4655-9c68-c568e23883ee",
      "public_id": "bb8f5d5a-ff08-4655-9c68-c568e23883ee",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00324000004ijWS"
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
      "created_at": "2019-04-08T19:38:44.732+02:00",
      "updated_at": "2019-04-08T19:38:44.732+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZSp_hfl0--/fl_attachment/v123123/c549b909343d.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2U7rmXxj--/c_fit,w_300/v123123/c549b909343d.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--3ODCWHdz--/c_fit,h_2000,w_2000/v123123/c549b909343d.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=eaf5149&url=localhost/images/bb8f5d5a-ff08-4655-9c68-c568e23883ee/thumbnails/mini-774ce0dd252.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=25f691d&url=localhost/images/bb8f5d5a-ff08-4655-9c68-c568e23883ee/thumbnails/thumbnail-1c76978ca87.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=61acf21&url=localhost/images/bb8f5d5a-ff08-4655-9c68-c568e23883ee/thumbnails/full-1a1ff441c4d.jpg"
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
      "album_id": "00324000004ijWS",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--GqakcO1b--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c549b909343d.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OJucpnTL--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c549b909343d.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--OJucpnTL--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c549b909343d.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--o_b-MV75--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c549b909343d.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--pDXbkQPT--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/c549b909343d.jpg"
      }
    },
    "tag": {
      "id": "7df68042-cb9c-46a0-852c-35a3b3eb0023",
      "created_at": "2019-04-08T19:38:44.799+02:00",
      "name": "Kevan",
      "label": "{\"en\":\"Kevan\",\"fr\":\"Kevan\"}",
      "url": "/public_tags/7df68042-cb9c-46a0-852c-35a3b3eb0023",
      "public": false,
      "listed": true,
      "action": {
        "actions": [

        ]
      },
      "visible": false,
      "color": "#00BCD4",
      "color_contrast": "#000000",
      "allow_download": false,
      "label_en": "Kevan",
      "label_fr": "Kevan"
    }
  }
]</pre>
