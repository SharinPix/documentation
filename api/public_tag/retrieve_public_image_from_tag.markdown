# Public Tag API

## Retrieve public image from tag

### GET api/v1/tags/:tag_id/public_tags
### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags/d6555b67-c91b-46af-a285-3269803fd1a3/public_tags</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: e0609bba-4e9e-4bd4-8bec-fb55f62db5a1
X-Runtime: 0.014252
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 1047</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "b1f5f89f-1cdf-42bb-b4f1-6a2e0ec4a578",
    "created_at": "2019-04-08T19:38:56.501+02:00",
    "image": {
      "id": "bdbad8bb-8033-496b-bf01-8d9484733c07",
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
      "public_id": "bdbad8bb-8033-496b-bf01-8d9484733c07",
      "width": 48,
      "height": 48,
      "rotation": 0,
      "public_url": "/images/bdbad8bb-8033-496b-bf01-8d9484733c07",
      "original_width": 48,
      "original_height": 48,
      "crop_x": 0.0,
      "crop_y": 0.0,
      "crop_w": 0.0,
      "crop_h": 0.0,
      "color": "#7D7D7D",
      "created_at": "2019-04-08T19:38:56.480+02:00",
      "taken_at": null,
      "album_id": "00324000004ijWS"
    },
    "tag": {
      "id": "d6555b67-c91b-46af-a285-3269803fd1a3",
      "created_at": "2019-04-08T19:38:56.471+02:00",
      "name": "My tag 5",
      "url": "/public_tags/d6555b67-c91b-46af-a285-3269803fd1a3",
      "public": true,
      "color": "#FFEB3B",
      "allow_download": false
    }
  }
]</pre>
