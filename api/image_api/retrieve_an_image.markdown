# Image API API

## Retrieve an image

### GET /api/v1/images/:id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6ImE3YjNiY2JkLWNjOWEtNDk5Ny04N2ZjLTQzNDA0NzlhYmQzYiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTU2Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.yTG4rhFyGZn34qhfg9eHlEcK_5_4TvzsCjx59ZX1TeE&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/b5ca76ee-3c2a-4be0-8870-39eff02d6e4b</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-access-crop: false
X-access-rotate: false
X-access-duplicate: false
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6ImE3YjNiY2JkLWNjOWEtNDk5Ny04N2ZjLTQzNDA0NzlhYmQzYiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTU2Ijp7IkFjY2VzcyI6eyJpbWFnZV9saXN0Ijp0cnVlfX19fQ.yTG4rhFyGZn34qhfg9eHlEcK_5_4TvzsCjx59ZX1TeE
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 81ce19d9-4de0-47ba-aadf-943ba162164f
X-Runtime: 0.012054
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2900</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "b5ca76ee-3c2a-4be0-8870-39eff02d6e4b",
  "public_id": "b5ca76ee-3c2a-4be0-8870-39eff02d6e4b",
  "infos": {
    "bytes": 3604,
    "created_at": "2015-09-25T13:32:55Z",
    "etag": "5a98d4d3e5d39024abf237be55e99b15",
    "format": "png",
    "height": 48,
    "resource_type": "image",
    "tags": [
      "00100000123BB156"
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
  "created_at": "2019-04-08T19:38:55.028+02:00",
  "updated_at": "2019-04-08T19:38:55.028+02:00",
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
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--DwUZVcnp--/fl_attachment/v123123/0ed6573dba6a.jpg",
  "original_width": 48,
  "original_height": 48,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--rFlyUr-X--/c_fit,w_300/v123123/0ed6573dba6a.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--UR7qO2Jo--/c_fit,h_2000,w_2000/v123123/0ed6573dba6a.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=58dfaa4&url=localhost/images/b5ca76ee-3c2a-4be0-8870-39eff02d6e4b/thumbnails/mini-289431a50de.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=9ab929e&url=localhost/images/b5ca76ee-3c2a-4be0-8870-39eff02d6e4b/thumbnails/thumbnail-c23bfb88fe9.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=b5f5324&url=localhost/images/b5ca76ee-3c2a-4be0-8870-39eff02d6e4b/thumbnails/full-ebc0136cc7b.jpg"
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
  "album_id": "00100000123BB156",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--skGt4f1r--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0ed6573dba6a.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--D-E811RT--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0ed6573dba6a.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--D-E811RT--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0ed6573dba6a.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--aH1XCmOG--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0ed6573dba6a.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---fbHOiz9--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/0ed6573dba6a.jpg"
  }
}</pre>
