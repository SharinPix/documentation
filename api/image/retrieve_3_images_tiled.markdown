# Image API

## Retrieve 3 images tiled

### GET /images/:image_id

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| token | Token to secure the transformation | false |  |

### Request

#### Headers

<pre>Host: example.org
Cookie: </pre>

#### Route

<pre>GET /images/133398b5-c4e1-4488-bbe1-81afd70546ae?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI2YjZmZGI3Yi02NWNiLTRhY2YtOTdiOS1kMjVlZmY3OTUzNDgiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7ImNyb3AiOiJmaXQiLCJ3aWR0aCI6ODAwfSx7Im92ZXJsYXkiOiJiNDhmZmY3MS1hNjQ5LTQxZGMtOGYzNS02NzIyOWIzZmQ1ODQiLCJjcm9wIjoiZml0Iiwid2lkdGgiOjgwMCwieCI6ODAwfSx7Im92ZXJsYXkiOiIzNzIwODNkOS04MTc5LTQxNjEtYWY4Yy02Y2JmZWNkOTIxOWEiLCJjcm9wIjoiZml0Iiwid2lkdGgiOjgwMCwieCI6MTIwMH1dfQ.wuNHAAHVwfCqif64WSFTL_dNxOiSZ3BEnsjczDnJ1Ao</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI2YjZmZGI3Yi02NWNiLTRhY2YtOTdiOS1kMjVlZmY3OTUzNDgiLCJ0cmFuc2Zvcm1hdGlvbnMiOlt7ImNyb3AiOiJmaXQiLCJ3aWR0aCI6ODAwfSx7Im92ZXJsYXkiOiJiNDhmZmY3MS1hNjQ5LTQxZGMtOGYzNS02NzIyOWIzZmQ1ODQiLCJjcm9wIjoiZml0Iiwid2lkdGgiOjgwMCwieCI6ODAwfSx7Im92ZXJsYXkiOiIzNzIwODNkOS04MTc5LTQxNjEtYWY4Yy02Y2JmZWNkOTIxOWEiLCJjcm9wIjoiZml0Iiwid2lkdGgiOjgwMCwieCI6MTIwMH1dfQ.wuNHAAHVwfCqif64WSFTL_dNxOiSZ3BEnsjczDnJ1Ao</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Access-Control-Allow-Origin: *
Location: http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--zuASupj8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,w_800/c_fit,l_authenticated:3bc669b21d8e,w_800,x_800/c_fit,l_authenticated:e199b75435bf,w_800,x_1200/v123123/f7332109c6c5.jpg
Content-Type: text/html; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 93ae03b2-d652-40ad-87d6-34082b2531b3
X-Runtime: 0.014624
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 362</pre>

#### Status

<pre>302 Found</pre>

#### Body

<pre><html><body>You are being <a href="http://example.org/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--zuASupj8--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/c_fit,w_800/c_fit,l_authenticated:3bc669b21d8e,w_800,x_800/c_fit,l_authenticated:e199b75435bf,w_800,x_1200/v123123/f7332109c6c5.jpg">redirected</a>.</body></html></pre>
