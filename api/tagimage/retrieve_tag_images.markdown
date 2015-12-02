# TagImage API

## retrieve tag images

### GET api/v1/tags/:tag_id/tag_images
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzEsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOnsiZW4iOiJDYXJ0b29ucyIsImZyIjoiRMOpc3NpbiBhbmltw6kifX0sIkFjY2VzcyI6eyJpbWFnZV90YWciOnRydWV9fX0sInVzZXJfaWQiOiIzZGUwMzlhMC01NmFjLTQzMjEtYmZjMi1iODU2ZmMzYWNjZGQifQ.GdrGZM3Gz48f7RaF8JsBV7fWsQaJYL40r938Gcb7R4A&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/tags/0fa52a27-6845-4373-b772-9ee8ad5ebe85/tag_images</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzEsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiVGFncyI6eyJ0YWciOnsiZW4iOiJDYXJ0b29ucyIsImZyIjoiRMOpc3NpbiBhbmltw6kifX0sIkFjY2VzcyI6eyJpbWFnZV90YWciOnRydWV9fX0sInVzZXJfaWQiOiIzZGUwMzlhMC01NmFjLTQzMjEtYmZjMi1iODU2ZmMzYWNjZGQifQ.GdrGZM3Gz48f7RaF8JsBV7fWsQaJYL40r938Gcb7R4A
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;f6cb5291067fd0f109af53e31007155e&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: cfaf0120-93a9-41ca-a9a6-692f2e01ffbd
X-Runtime: 0.027356
Content-Length: 1030</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"f87f4ca4-1055-47cf-bb06-27db94a0f860","created_at":"2015-12-02T11:14:31.054+01:00","user":"3de039a0-56ac-4321-bfc2-b856fc3accdd","image":{"public_id":"02292855-9f85-4d28-bb00-424d5f9b7b6b","infos":{"bytes":3604,"created_at":"2015-09-25T13:32:55Z","etag":"5a98d4d3e5d39024abf237be55e99b15","format":"png","height":48,"resource_type":"image","tags":["00324000004ijWS"],"type":"private","width":48,"location":{"accuracy":36,"latitude":48.861934399999996,"longitude":2.348967}},"exifs":{},"gps":[48.861934399999996,2.348967],"gps_ip":null,"gps_exifs":null,"gps_html":[48.861934399999996,2.348967],"created_at":"2015-12-02T11:14:31.019+01:00","width":48,"height":48,"rotation":0,"crop_x":0.0,"crop_y":0.0,"crop_w":0.0,"crop_h":0.0,"album_id":"00324000004ijWS","thumbnails":{"full":"/assets/blank.jpg","large":"/assets/blank.jpg","mini":"/assets/blank.jpg"}},"tag":{"id":"0fa52a27-6845-4373-b772-9ee8ad5ebe85","created_at":"2015-12-02T11:14:31.003+01:00","name":"tag","label":"{\"en\":\"Cartoons\",\"fr\":\"Déssin animé\"}"}}]</pre>
