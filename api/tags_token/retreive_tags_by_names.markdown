# Tags Token API

## Retreive tags by names

### GET api/v1/tags_token
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjNiMDA1ZmM0LWIxZGYtNDI1YS05NmU3LTc5ZjZiZTI1YWUzYSIsImFiaWxpdGllcyI6eyJ0ZXN0LWx1YzIiOnt9LCJ0ZXN0LWx1YyI6eyJUYWdzIjp7Imx1YyI6eyJlbiI6Ikx1YyIsImZyIjoiTHVjIn19fSwiMDAzMjQwMDAwMDRpaldTIjp7IlRhZ3MiOnsia2V2YW4iOnsiZW4iOiJLZXZhbiIsImZyIjoiS2V2YW4ifSwiYXpoYXIiOnsiZW4iOiJBemhhciIsImZyIjoiQXpoYXIifSwia2hlcmluIjp7ImVuIjoiS2hlcmluIiwiZnIiOiJLaGVyaW4ifSwid3JvbmctbGFiZWxzIjpudWxsfX19fQ.OaG5-l6jXxJ-qJmeGb-mahIg7aNgUJcIH6QNGD-66ZU&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags_token</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzUsImlhdCI6MTU1NDc0NTEzNSwidXNlcl9pZCI6IjNiMDA1ZmM0LWIxZGYtNDI1YS05NmU3LTc5ZjZiZTI1YWUzYSIsImFiaWxpdGllcyI6eyJ0ZXN0LWx1YzIiOnt9LCJ0ZXN0LWx1YyI6eyJUYWdzIjp7Imx1YyI6eyJlbiI6Ikx1YyIsImZyIjoiTHVjIn19fSwiMDAzMjQwMDAwMDRpaldTIjp7IlRhZ3MiOnsia2V2YW4iOnsiZW4iOiJLZXZhbiIsImZyIjoiS2V2YW4ifSwiYXpoYXIiOnsiZW4iOiJBemhhciIsImZyIjoiQXpoYXIifSwia2hlcmluIjp7ImVuIjoiS2hlcmluIiwiZnIiOiJLaGVyaW4ifSwid3JvbmctbGFiZWxzIjpudWxsfX19fQ.OaG5-l6jXxJ-qJmeGb-mahIg7aNgUJcIH6QNGD-66ZU
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: b3fc400a-73cc-4f97-821a-b0296ecb230c
X-Runtime: 0.031833
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 1956</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "id": "4f9ce835-d45f-44b1-82bf-cb55839b79ac",
    "created_at": "2019-04-08T19:38:55.886+02:00",
    "name": "luc",
    "label": "{\"en\":\"Luc\",\"fr\":\"Luc\"}",
    "url": "/public_tags/4f9ce835-d45f-44b1-82bf-cb55839b79ac",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": false,
    "color": "#673AB7",
    "color_contrast": "#ffffff",
    "allow_download": false,
    "label_en": "Luc",
    "label_fr": "Luc"
  },
  {
    "id": "ec7882e4-7b6e-47a4-a6c5-246a0f2a0610",
    "created_at": "2019-04-08T19:38:55.889+02:00",
    "name": "kevan",
    "label": "{\"en\":\"Kevan\",\"fr\":\"Kevan\"}",
    "url": "/public_tags/ec7882e4-7b6e-47a4-a6c5-246a0f2a0610",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": false,
    "color": "#FF9800",
    "color_contrast": "#000000",
    "allow_download": false,
    "label_en": "Kevan",
    "label_fr": "Kevan"
  },
  {
    "id": "454b6342-1208-4077-9fe4-f1f303c9bbd9",
    "created_at": "2019-04-08T19:38:55.893+02:00",
    "name": "azhar",
    "label": "{\"en\":\"Azhar\",\"fr\":\"Azhar\"}",
    "url": "/public_tags/454b6342-1208-4077-9fe4-f1f303c9bbd9",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": false,
    "color": "#CDDC39",
    "color_contrast": "#000000",
    "allow_download": false,
    "label_en": "Azhar",
    "label_fr": "Azhar"
  },
  {
    "id": "073254a3-5a8c-48bc-8804-8fee5a288b93",
    "created_at": "2019-04-08T19:38:55.896+02:00",
    "name": "kherin",
    "label": "{\"en\":\"Kherin\",\"fr\":\"Kherin\"}",
    "url": "/public_tags/073254a3-5a8c-48bc-8804-8fee5a288b93",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": false,
    "color": "#8BC34A",
    "color_contrast": "#000000",
    "allow_download": false,
    "label_en": "Kherin",
    "label_fr": "Kherin"
  },
  {
    "id": "a75eedaa-268d-4b3d-bf0d-308cd049b959",
    "created_at": "2019-04-08T19:38:55.899+02:00",
    "name": "wrong-labels",
    "label": "{\"en\":\"wrong-labels\",\"fr\":\"wrong-labels\"}",
    "url": "/public_tags/a75eedaa-268d-4b3d-bf0d-308cd049b959",
    "public": false,
    "listed": true,
    "action": {
      "actions": [

      ]
    },
    "visible": false,
    "color": "#2196F3",
    "color_contrast": "#ffffff",
    "allow_download": false,
    "label_en": "wrong-labels",
    "label_fr": "wrong-labels"
  }
]</pre>
