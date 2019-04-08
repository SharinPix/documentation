# Image API API

## Rotate an image

### PUT /api/v1/images/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| rotation | Image payload | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6ImZiMDc5NzAwLTQ2YjQtNGU2MS05NjdmLTI3OGU5ZjMwMjg3ZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTYyIjp7IkFjY2VzcyI6eyJpbWFnZV9yb3RhdGUiOnRydWV9fX19.I14y7I1vnb10O2DE9ZD0udhB8ECB2sR8ujJnCrBf7jg&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/d0043a3e-f1ec-4eff-9af3-75eadc4b907e</pre>

#### Body

<pre>rotation=90</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6ImZiMDc5NzAwLTQ2YjQtNGU2MS05NjdmLTI3OGU5ZjMwMjg3ZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTYyIjp7IkFjY2VzcyI6eyJpbWFnZV9yb3RhdGUiOnRydWV9fX19.I14y7I1vnb10O2DE9ZD0udhB8ECB2sR8ujJnCrBf7jg
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 1347a1a9-1475-4b48-96ea-9c996067da10
X-Runtime: 0.017627
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2926</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "d0043a3e-f1ec-4eff-9af3-75eadc4b907e",
  "public_id": "d0043a3e-f1ec-4eff-9af3-75eadc4b907e",
  "infos": {
    "bytes": 3604,
    "created_at": "2015-09-25T13:32:55Z",
    "etag": "5a98d4d3e5d39024abf237be55e99b15",
    "format": "png",
    "height": 48,
    "resource_type": "image",
    "tags": [
      "00100000123BB162"
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
  "created_at": "2019-04-08T19:38:55.200+02:00",
  "updated_at": "2019-04-08T19:38:55.214+02:00",
  "taken_at": null,
  "width": 48,
  "height": 48,
  "rotation": 90,
  "crop_x": 0.0,
  "crop_y": 0.0,
  "crop_w": 0.0,
  "crop_h": 0.0,
  "metadatas": {
  },
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--wgjzWqhG--/fl_attachment/v123123/ec25b1dec00d.jpg",
  "original_width": 48,
  "original_height": 48,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--NweGRXbQ--/a_90/c_fit,w_300/v123123/ec25b1dec00d.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--d0eoeAZQ--/a_90/c_fit,h_2000,w_2000/v123123/ec25b1dec00d.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=2886e8e&url=localhost/images/d0043a3e-f1ec-4eff-9af3-75eadc4b907e/thumbnails/mini-9ddf6f84ef0.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=ab965c8&url=localhost/images/d0043a3e-f1ec-4eff-9af3-75eadc4b907e/thumbnails/thumbnail-2f26626e395.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a35250d&url=localhost/images/d0043a3e-f1ec-4eff-9af3-75eadc4b907e/thumbnails/full-87bfb0dd322.jpg"
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
  "album_id": "00100000123BB162",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ebIzEgEJ--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ec25b1dec00d.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PqQLcVgF--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ec25b1dec00d.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2B6S47T---/c_fit,h_1920,w_1920/a_90/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ec25b1dec00d.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--hzyd_rtl--/c_fit,h_1920,w_1920/a_90/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ec25b1dec00d.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--IGzReKKS--/c_fit,h_1920,w_1920/a_90/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/ec25b1dec00d.jpg"
  }
}</pre>
