# Image API API

## Search image with encoded parameters in authentication token

### GET /api/v1/search

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| q | ElasticSearch query string signed with a secret (JWT token): https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-query-string-query.html | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJxIjoiKiIsImlzcyI6ImYzMWM3OTFkLTNkNmEtNDY3ZC1hYzQxLTg0YzUwYzBkZjkwMSJ9.k-QoBSRZePeglYe7b2PXbp2txi9GrntTsX9aRaL7WEQ&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/search?q</pre>

#### Query Parameters

<pre>q: </pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwiaXNzIjoiZjMxYzc5MWQtM2Q2YS00NjdkLWFjNDEtODRjNTBjMGRmOTAxIiwicSI6IioifQ.VM4aRxiU8yFyojjECAdyoL_jtc4de18F2Nb789mYF9w
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: d7797c44-c100-4a81-aa7e-6b2086665b5e
X-Runtime: 0.038446
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2921</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "ade5dc67-9ee3-414f-85e5-985882f5c300",
    "public_id": "ade5dc67-9ee3-414f-85e5-985882f5c300",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB130"
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
    "created_at": "2019-04-08T19:38:52.671+02:00",
    "updated_at": "2019-04-08T19:38:52.679+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--aQ-38Bb2--/fl_attachment/v123123/e3650d42c991.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--fS2fsRaV--/c_fit,w_300/v123123/e3650d42c991.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--_WOrp9Vb--/c_fit,h_2000,w_2000/v123123/e3650d42c991.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1eb4175&url=localhost/images/ade5dc67-9ee3-414f-85e5-985882f5c300/thumbnails/mini-e8024ec158f.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9278d18&url=localhost/images/ade5dc67-9ee3-414f-85e5-985882f5c300/thumbnails/thumbnail-55b5ce45e13.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=fe6d030&url=localhost/images/ade5dc67-9ee3-414f-85e5-985882f5c300/thumbnails/full-b5affb7531c.jpg"
    },
    "filename": "Super Image",
    "format": "png",
    "title": null,
    "description": null,
    "page": 1,
    "group_id": null,
    "color": "#7D7D7D",
    "size": 3604,
    "processed": true,
    "processing_error": null,
    "album_id": "00100000123BB130",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--1Ifd8SZs--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e3650d42c991.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--zIlO1oCu--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e3650d42c991.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--zIlO1oCu--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e3650d42c991.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--1h7l-wai--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e3650d42c991.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--qPlC4lni--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e3650d42c991.jpg"
    }
  }
]</pre>
