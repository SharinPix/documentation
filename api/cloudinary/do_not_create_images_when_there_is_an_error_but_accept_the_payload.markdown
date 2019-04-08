# Cloudinary API

## do not create images when there is an error but accept the payload

### POST api/v1/cloudinary?token=:token

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| raw_post | JSON as body. | false |  |

### Request

#### Headers

<pre>X-Cld-Timestamp: 1554745139
X-Cld-Signature: e221a22c233361cd4c4e5c3ac093dabae2fd1669
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI1MTQxMWRmZS0xOGJlLTQ5OTUtODNlZS0zZTA4OWQ5ZTM2NDgiLCJvcmdhbml6YXRpb25faWQiOiI1YzJkZWQxNC0wYWQwLTRiZjYtYWFhYy1lMWYyYjVkZDM2OWMiLCJhbGJ1bV9pZCI6IjEyMzQ1Njc4OSJ9.ahmxeQLdJkFf2oVMXSY9j8bkXTdSdSvMS4e7ddfHy-k</pre>

#### Query Parameters

<pre>token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiI1MTQxMWRmZS0xOGJlLTQ5OTUtODNlZS0zZTA4OWQ5ZTM2NDgiLCJvcmdhbml6YXRpb25faWQiOiI1YzJkZWQxNC0wYWQwLTRiZjYtYWFhYy1lMWYyYjVkZDM2OWMiLCJhbGJ1bV9pZCI6IjEyMzQ1Njc4OSJ9.ahmxeQLdJkFf2oVMXSY9j8bkXTdSdSvMS4e7ddfHy-k</pre>

#### Body

<pre>{
  "error": {
    "message": "Empty file",
    "status": 400,
    "request_id": "ed63e916763fcc99"
  },
  "notification_type": "error",
  "params": {
    "faces": "1",
    "colors": "1",
    "image_metadata": "1",
    "phash": "1",
    "type": "authenticated",
    "tags": "empty",
    "notification_url": "https://ombr.ngrok.io/api/v1/cloudinary?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1MjM0NzUyMjAsImlhdCI6MTUyMzQ2MDgyMCwidXNlcl9pZCI6IjZhMmJhMDU3LTAyOGYtNDEzYy1iZGZkLTk5ZDFmNTM5ZTM0NSIsImFsYnVtX2lkIjoiZW1wdHkiLCJvcmdhbml6YXRpb25faWQiOiIxYThjY2ZlNi1iZDg4LTQzYzItOWNkZi00ZjI5YTNiYWEwNDMifQ.8AxJzoN5OIIIL7buwSlfQ3tEP2L9EUCynaYvsl8z2h4"
  }
}
</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: text/html
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 44777942-f5f3-452f-ad13-ecbbab4c19b0
X-Runtime: 0.007407
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 0</pre>

#### Status

<pre>201 Created</pre>

