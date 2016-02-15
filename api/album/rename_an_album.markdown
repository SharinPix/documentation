# Album API

## Rename an album

### PUT /api/v1/albums/:id

### Parameters

Name : album
Description : new album attributes

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6eyIzMTQxYTI0NS00MGFjLTRiNWMtYTBkMi1jYWE5YjIyZGQ0OGQiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fSwidXNlcl9pZCI6IjJkZDE5NDYyLTVjOGYtNGI4ZC1hNjJhLWE4NDczMzQyMjE4OCJ9.U2qC_AEFfqeaFIzNpN1sIivzvsise8qngnFhRAkLnTo&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>PUT /api/v1/albums/3141a245-40ac-4b5c-a0d2-caa9b22dd48d</pre>

#### Body

<pre>album[public_id]=newid</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTU1NTIxNzcsImFiaWxpdGllcyI6eyIzMTQxYTI0NS00MGFjLTRiNWMtYTBkMi1jYWE5YjIyZGQ0OGQiOnsiQWNjZXNzIjp7InJlbmFtZSI6dHJ1ZX19fSwidXNlcl9pZCI6IjJkZDE5NDYyLTVjOGYtNGI4ZC1hNjJhLWE4NDczMzQyMjE4OCJ9.U2qC_AEFfqeaFIzNpN1sIivzvsise8qngnFhRAkLnTo
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f6053798-6f6e-42ec-870e-3d71e0096ce6
X-Runtime: 0.049458
Content-Length: 89</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{"public_id":"newid","upload_form":null,"images_count":0,"views_count":0,"thumbnails":[]}</pre>
