# Image API

## Retreive an image embed code

### GET /api/v1/images/:id/embed
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTUsImFiaWxpdGllcyI6eyI3ZTQ2MDhmNC03NmRmLTQ0NzUtYWRkOS02YTAyMzU5NTM5ZWUiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJmNjY3NTU1Ny0xMTA2LTQ5ZGUtOGQxYS0xMzM1YmJlZjdmZmQifQ.2jDfZ1f76kiV50mfJnFOAufqKIcMOWRbK82ozlRCFBA&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET /api/v1/images/6e817a48-540d-4ab5-bbee-953a353ed76e/embed</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store, must-revalidate, private, max-age=0
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MTUsImFiaWxpdGllcyI6eyI3ZTQ2MDhmNC03NmRmLTQ0NzUtYWRkOS02YTAyMzU5NTM5ZWUiOnsiQWNjZXNzIjp7ImltYWdlX2xpc3QiOnRydWV9fX0sInVzZXJfaWQiOiJmNjY3NTU1Ny0xMTA2LTQ5ZGUtOGQxYS0xMzM1YmJlZjdmZmQifQ.2jDfZ1f76kiV50mfJnFOAufqKIcMOWRbK82ozlRCFBA
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: c531acd7-7dd2-4e69-9dd6-0a34e74dc7ef
X-Runtime: 0.056850
Content-Length: 684</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"html":"\u003cvideo autoplay=\"autoplay\" controls=\"controls\" poster=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--p674B2BU--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.jpg\"\u003e\u003csource src=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--0wXzLh0r--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.webm\" type=\"video/webm\" /\u003e\u003csource src=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--UxGtQ7i2--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.mp4\" type=\"video/mp4\" /\u003e\u003csource src=\"https://res.cloudinary.com/hwja6b0dx/video/private/s--LPhVi-4B--/c_fit,h_1000,w_1000/iplggwtcsi2gjybsjg4q.ogv\" type=\"video/ogg\" /\u003e\u003c/video\u003e"}</pre>
