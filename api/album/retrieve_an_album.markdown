# Album API

## Retrieve an album

### GET /api/v1/albums/:id
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImU3YTRmMTFjLTc5N2QtNDY3MS1iNDZlLWQ3OGI0YTEzNjExNiIsImFiaWxpdGllcyI6e319.EGGoIWpeQhIMD0I6V0fhKFlZV6uBq5HBvgHC6XgqDi0&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/albums/00100000123BB56</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-access-image_delete: true
X-access-image_upload: true
X-access-image_share: false
X-access-image_rotate: true
X-access-image_crop: true
X-access-stats: true
X-access-image_copy: false
X-access-paste: false
X-access-share: false
X-access-image_duplicate: false
X-access-create_tag: false
X-access-image_download: true
X-access-image_annotate: false
X-access-fullscreen: 
X-access-einstein_box: 
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImU3YTRmMTFjLTc5N2QtNDY3MS1iNDZlLWQ3OGI0YTEzNjExNiIsImFiaWxpdGllcyI6e319.EGGoIWpeQhIMD0I6V0fhKFlZV6uBq5HBvgHC6XgqDi0
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: df97e99c-62ac-43c0-a4b6-eb8b14716d74
X-Runtime: 0.021430
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 3861</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "00100000123BB56",
  "public_id": "00100000123BB56",
  "images_count": 1,
  "views_count": 0,
  "upload_form": {
    "url": "https://api.cloudinary.com/v1_1/sadaasdasd/auto/upload",
    "expires_at": 1555349927,
    "name": "00100000123BB56",
    "id": "b7a1c348-3f81-479e-a30f-d8430f57d679-00100000123BB56",
    "params": {
      "colors": 1,
      "faces": 1,
      "image_metadata": 1,
      "notification_url": "https://localhost:5001/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjcsImlhdCI6MTU1NDc0NTEyNywidXNlcl9pZCI6ImU3YTRmMTFjLTc5N2QtNDY3MS1iNDZlLWQ3OGI0YTEzNjExNiIsImFsYnVtX2lkIjoiMDAxMDAwMDAxMjNCQjU2Iiwib3JnYW5pemF0aW9uX2lkIjoiYjdhMWMzNDgtM2Y4MS00NzllLWEzMGYtZDg0MzBmNTdkNjc5In0.cGOcmRvW3B3gQzFEtWYaBv9sXTw4D1h89GrWmcIcOyo",
      "phash": 1,
      "tags": "00100000123BB56",
      "timestamp": 1555349927,
      "type": "authenticated",
      "signature": "34094ac20a3dcc20ff6a9bf4fa9490293d648495",
      "api_key": "123123123123"
    },
    "test_url": "/upload_test"
  },
  "organization_id": "b7a1c348-3f81-479e-a30f-d8430f57d679",
  "thumbnails": [
    {
      "id": "0d196b35-1e7f-459f-ac80-b3e704528c90",
      "public_id": "0d196b35-1e7f-459f-ac80-b3e704528c90",
      "infos": {
        "bytes": 3604,
        "created_at": "2015-09-25T13:32:55Z",
        "etag": "5a98d4d3e5d39024abf237be55e99b15",
        "format": "png",
        "height": 48,
        "resource_type": "image",
        "tags": [
          "00100000123BB56"
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
      "created_at": "2019-04-08T19:38:47.906+02:00",
      "updated_at": "2019-04-08T19:38:47.906+02:00",
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
      "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--PozO8tAm--/fl_attachment/v123123/e514ce2a76aa.jpg",
      "original_width": 48,
      "original_height": 48,
      "external_urls": {
        "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--dHoq6QIy--/c_fit,w_300/v123123/e514ce2a76aa.jpg",
        "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--HEIiy1R7--/c_fit,h_2000,w_2000/v123123/e514ce2a76aa.jpg",
        "mini": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=1336e8f&url=localhost/images/0d196b35-1e7f-459f-ac80-b3e704528c90/thumbnails/mini-829acac0d09.jpg",
        "large": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=f02976f&url=localhost/images/0d196b35-1e7f-459f-ac80-b3e704528c90/thumbnails/thumbnail-f2f12b2d110.jpg",
        "full": "https://sharinpix-proxy-dev.herokuapp.com/super-image.png?s=7a4d717&url=localhost/images/0d196b35-1e7f-459f-ac80-b3e704528c90/thumbnails/full-76867a05ab7.jpg"
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
      "album_id": "00100000123BB56",
      "thumbnails": {
        "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--B84lQ-6r--/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e514ce2a76aa.jpg",
        "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mTS7JHb2--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e514ce2a76aa.jpg",
        "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--mTS7JHb2--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e514ce2a76aa.jpg",
        "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--5b3IqTk8--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e514ce2a76aa.jpg",
        "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--RoZ0FUvB--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v123123/e514ce2a76aa.jpg"
      }
    }
  ]
}</pre>
