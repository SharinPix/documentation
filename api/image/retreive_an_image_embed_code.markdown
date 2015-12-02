# Image API

## Retreive an image embed code

### GET /api/v1/images/:id/embed
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyIxY2VkZTVjZS1jYzExLTQ4YTMtYjAzMC02MWZhZWIzMGEzOGQiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJiOWJlZjE3NS0xNTZiLTQ0ZTMtYjJlNS1mMjIxYzFlM2NmYzUifQ.A-9nn_7C0OUkTxHH8iYs_9sxtbYgPoY9PgtWoJ0k1Io&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/3c9afc84-0f46-4b85-a7d4-0fb8f596d45c/embed</pre>

### Response

#### Headers

<pre>X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NDkwNjU2NzQsImFiaWxpdGllcyI6eyIxY2VkZTVjZS1jYzExLTQ4YTMtYjAzMC02MWZhZWIzMGEzOGQiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJiOWJlZjE3NS0xNTZiLTQ0ZTMtYjJlNS1mMjIxYzFlM2NmYzUifQ.A-9nn_7C0OUkTxHH8iYs_9sxtbYgPoY9PgtWoJ0k1Io
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
ETag: W/&quot;ed3014e7f66392030e70cd149bea50e9&quot;
Cache-Control: max-age=0, private, must-revalidate
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 5bc56bd4-f77b-4f59-94e8-19932663b506
X-Runtime: 0.055078
Content-Length: 684</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"html":"\u003cvideo autoplay=\"autoplay\" controls=\"controls\" poster=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--p674B2BU--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.jpg\"\u003e\u003csource src=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--0wXzLh0r--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.webm\" type=\"video/webm\" /\u003e\u003csource src=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--UxGtQ7i2--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.mp4\" type=\"video/mp4\" /\u003e\u003csource src=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--LPhVi-4B--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.ogv\" type=\"video/ogg\" /\u003e\u003c/video\u003e"}</pre>
