# Image API API

## Search an image as plain query

### GET /api/v1/search

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| q | ElasticSearch query string: https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-query-string-query.html | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjY5ZTI5NjUxLWQ2NTItNDdmZS04MDg2LTVhODViMDA2MWYyMSJ9.spgvVH6vTIt3y5Oe4G8HKRaiVGuz-kUwRmY0gQp9_mQ&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/search?q=*</pre>

#### Query Parameters

<pre>q: *</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjY5ZTI5NjUxLWQ2NTItNDdmZS04MDg2LTVhODViMDA2MWYyMSJ9.spgvVH6vTIt3y5Oe4G8HKRaiVGuz-kUwRmY0gQp9_mQ
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: bd1dafc5-ebc1-4e80-9272-0a71ae088633
X-Runtime: 0.039850
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
    "id": "196dc2bd-d5ca-444f-92d4-f120f9814373",
    "public_id": "196dc2bd-d5ca-444f-92d4-f120f9814373",
    "infos": {
      "bytes": 3604,
      "created_at": "2015-09-25T13:32:55Z",
      "etag": "5a98d4d3e5d39024abf237be55e99b15",
      "format": "png",
      "height": 48,
      "resource_type": "image",
      "tags": [
        "00100000123BB166"
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
    "created_at": "2019-04-08T19:38:55.298+02:00",
    "updated_at": "2019-04-08T19:38:55.306+02:00",
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
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xxujMdKt--/fl_attachment/v123123/e66d3583e781.jpg",
    "original_width": 48,
    "original_height": 48,
    "external_urls": {
      "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--VTcENKkM--/c_fit,w_300/v123123/e66d3583e781.jpg",
      "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JDPKRR4y--/c_fit,h_2000,w_2000/v123123/e66d3583e781.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=3e780ee&url=localhost/images/196dc2bd-d5ca-444f-92d4-f120f9814373/thumbnails/mini-80501b70c3b.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=19fd2a8&url=localhost/images/196dc2bd-d5ca-444f-92d4-f120f9814373/thumbnails/thumbnail-8a165c09dd2.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=b3031cd&url=localhost/images/196dc2bd-d5ca-444f-92d4-f120f9814373/thumbnails/full-f0c3c6e936c.jpg"
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
    "album_id": "00100000123BB166",
    "thumbnails": {
      "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--WLO3fgx8--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e66d3583e781.jpg",
      "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--j0aM3_B9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e66d3583e781.jpg",
      "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--j0aM3_B9--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e66d3583e781.jpg",
      "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EkvahM7C--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e66d3583e781.jpg",
      "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--MORxuZut--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e66d3583e781.jpg"
    }
  }
]</pre>
