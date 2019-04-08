# Image API API

## match the image by a part of the filename

### GET /api/v1/search

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| q | ElasticSearch query string: https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-query-string-query.html | false |  |
| version | The version of the search you are using, in order to have filename you need to be in version 2 | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6ImIyZmM0NDAxLTMyMWUtNGRkZi1hMjgwLWNiNzc1MzcxNDA5ZSJ9.aaLwtgsn2qgd7Ys-pXnQOx3wpWNCfjAcJwts0c_pIlY&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/search?q=plop&amp;version=2</pre>

#### Query Parameters

<pre>q: plop
version: 2</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6ImIyZmM0NDAxLTMyMWUtNGRkZi1hMjgwLWNiNzc1MzcxNDA5ZSJ9.aaLwtgsn2qgd7Ys-pXnQOx3wpWNCfjAcJwts0c_pIlY
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 12605403-e0ab-4470-9dfd-3aa82583d20b
X-Runtime: 0.024570
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2471</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "78597545-e183-4ee2-bbd7-17cfd00a6cfe",
    "public_id": "78597545-e183-4ee2-bbd7-17cfd00a6cfe",
    "infos": {
      "original_filename": "superplophey",
      "format": "jpg"
    },
    "exifs": {
    },
    "gps": [
      40.7143528,
      -74.0059731
    ],
    "gps_ip": [
      40.7143528,
      -74.0059731
    ],
    "gps_exifs": null,
    "gps_html": null,
    "created_at": "2019-04-08T19:38:55.505+02:00",
    "updated_at": "2019-04-08T19:38:55.514+02:00",
    "taken_at": null,
    "width": 3000,
    "height": 3000,
    "rotation": 0,
    "crop_x": 0.0,
    "crop_y": 0.0,
    "crop_w": 0.0,
    "crop_h": 0.0,
    "metadatas": {
    },
    "original_url": "https://res.cloudinary.com/sadaasdasd/image/private/s--P5P3VViA--/fl_attachment/v123123/c59db5e8fee2.jpg",
    "original_width": 3000,
    "original_height": 3000,
    "external_urls": {
      "fill100": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--yHjaSjf0--/c_fit,w_300/raw_placeholder.jpg",
      "fit2000": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--vY1va9tF--/c_fit,h_2000,w_2000/raw_placeholder.jpg",
      "mini": "https://sharinpix-proxy-dev.herokuapp.com/superplophey.jpg?s=49a0668&url=localhost/images/78597545-e183-4ee2-bbd7-17cfd00a6cfe/thumbnails/mini-2a3e69024a9.jpg",
      "large": "https://sharinpix-proxy-dev.herokuapp.com/superplophey.jpg?s=d1b7562&url=localhost/images/78597545-e183-4ee2-bbd7-17cfd00a6cfe/thumbnails/thumbnail-aa8cbc5b084.jpg",
      "full": "https://sharinpix-proxy-dev.herokuapp.com/superplophey.jpg?s=d5b91bf&url=localhost/images/78597545-e183-4ee2-bbd7-17cfd00a6cfe/thumbnails/full-b085dd87374.jpg"
    },
    "filename": "superplophey",
    "format": "jpg",
    "title": null,
    "description": null,
    "page": 1,
    "group_id": null,
    "color": "#7D7D7D",
    "size": null,
    "processed": false,
    "processing_error": null,
    "album_id": "00100000123BB168",
    "thumbnails": {
      "original": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--0KCZNF0J--/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "full_no_sharinpix": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xBErTufU--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "full": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--xBErTufU--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "large": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--c5-w2fj8--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg",
      "mini": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--EmjULx71--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/raw_placeholder.jpg"
    }
  }
]</pre>
