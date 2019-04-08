# Image API API

## Set image caption

### PUT /api/v1/images/:id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| title | Image caption - title | false |  |
| description | Image caption - description | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6ImRmNGNiNThmLWI4YTgtNDA4OC1iMWE1LTdkMWViYTI4ZWE4NSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTMyIjp7IkFjY2VzcyI6eyJpbWFnZV9jYXB0aW9uIjp0cnVlfX19fQ.JPkSb4c-PcPy42asQ0QAaBObV07-z06tDcbh9cpEYXs&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/images/daebdfca-4ffd-4569-b620-655c99d7e165</pre>

#### Body

<pre>title=A+title%21&description=A+description...</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzIsImlhdCI6MTU1NDc0NTEzMiwidXNlcl9pZCI6ImRmNGNiNThmLWI4YTgtNDA4OC1iMWE1LTdkMWViYTI4ZWE4NSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTMyIjp7IkFjY2VzcyI6eyJpbWFnZV9jYXB0aW9uIjp0cnVlfX19fQ.JPkSb4c-PcPy42asQ0QAaBObV07-z06tDcbh9cpEYXs
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 7a9623bc-72cd-40aa-b86f-08500c6fa3df
X-Runtime: 0.017666
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2920</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "daebdfca-4ffd-4569-b620-655c99d7e165",
  "public_id": "daebdfca-4ffd-4569-b620-655c99d7e165",
  "infos": {
    "bytes": 3604,
    "created_at": "2015-09-25T13:32:55Z",
    "etag": "5a98d4d3e5d39024abf237be55e99b15",
    "format": "png",
    "height": 48,
    "resource_type": "image",
    "tags": [
      "00100000123BB132"
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
  "created_at": "2019-04-08T19:38:52.870+02:00",
  "updated_at": "2019-04-08T19:38:52.884+02:00",
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
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ZU3chIEZ--/fl_attachment/v123123/f15a07774f78.jpg",
  "original_width": 48,
  "original_height": 48,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--B6m4OfAJ--/c_fit,w_300/v123123/f15a07774f78.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--V4DhlHCh--/c_fit,h_2000,w_2000/v123123/f15a07774f78.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f81b9f6&url=localhost/images/daebdfca-4ffd-4569-b620-655c99d7e165/thumbnails/mini-95243bd2c67.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=a91d611&url=localhost/images/daebdfca-4ffd-4569-b620-655c99d7e165/thumbnails/thumbnail-38890b83a86.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=05f04c7&url=localhost/images/daebdfca-4ffd-4569-b620-655c99d7e165/thumbnails/full-33912595625.jpg"
  },
  "filename": "Super Image",
  "format": "png",
  "title": "A title!",
  "description": "A description...",
  "page": 1,
  "group_id": null,
  "color": "#7D7D7D",
  "size": 3604,
  "processed": false,
  "processing_error": null,
  "album_id": "00100000123BB132",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--2fUZjuFL--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f15a07774f78.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JZHY0cSm--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f15a07774f78.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JZHY0cSm--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f15a07774f78.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--l3fAtwWt--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f15a07774f78.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--JaiYzR5W--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/f15a07774f78.jpg"
  }
}</pre>
