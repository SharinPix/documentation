# Storage file API

## Create a new storage_file

### POST /api/v1/storages/:storage_id/storage_files

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| storage_id | The storage id | false |  |
| album_id | The destination album | false |  |
| name | The filename | false |  |
| type | The file type | false |  |
| size | The file size | false |  |
| metas | The file metas (color, exifs) | false |  |
| image_metadatas | Image metadatas | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6ImMxYWM4ZDI4LTRiNjUtNGE4Yy1hNTdhLWJiMDk2ZGNhOGFkZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjYxIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19._fnNX7Kp8D6bPX7_UrgcpiyY8AAwNv5uYKfcY1XZ6Ak&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/storages/amazing-storage/storage_files</pre>

#### Body

<pre>album_id=00100000123BB261&name=%C3%A8+%C3%A0+Amazing+file.jpg&type=image%2Fjpeg&size=3145728&metas[color]=%236c401b&metas[exifs][Model]=NIKON+D2H&image_metadatas[super_key]=Super+Value+%21</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1NDMsImlhdCI6MTU1NDc0NTE0MywidXNlcl9pZCI6ImMxYWM4ZDI4LTRiNjUtNGE4Yy1hNTdhLWJiMDk2ZGNhOGFkZSIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMjYxIjp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19._fnNX7Kp8D6bPX7_UrgcpiyY8AAwNv5uYKfcY1XZ6Ak
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 7a58ece2-e746-43a2-be2d-4110a9c97866
X-Runtime: 0.015311
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 2003</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "9f816054-2881-4ada-acf7-7eb7a886aa60",
  "organization_id": "64ab69fa-b1c1-4eb9-995e-f3ee4bf4d24e",
  "upload_parameters": {
    "method": "POST",
    "url": "https://sharinpix-pix-dev.s3.eu-west-2.amazonaws.com",
    "fields": {
      "key": "localhost-5001/storage_files/9f/81/9f816054-2881-4ada-acf7-7eb7a886aa60/e-a-amazing-file.jpg",
      "Content-Disposition": "attachment; filename=\"e-a-amazing-file.jpg\"; filename*=UTF-8''%C3%A8%20%C3%A0%20Amazing%20file.jpg",
      "Content-Type": "image/jpeg",
      "Cache-Control": "public, max-age=2592000",
      "Expires": "Sun, 08 Apr 2029 17:39:03 GMT",
      "x-amz-meta-file_id": "9f816054-2881-4ada-acf7-7eb7a886aa60",
      "x-amz-meta-organization_id": "9f816054-2881-4ada-acf7-7eb7a886aa60",
      "success_action_status": "201",
      "policy": "eyJleHBpcmF0aW9uIjoiMjAxOS0wNC0wOVQxNzozOTowM1oiLCJjb25kaXRpb25zIjpbeyJidWNrZXQiOiJzaGFyaW5waXgtcGl4LWRldiJ9LHsia2V5IjoibG9jYWxob3N0LTUwMDEvc3RvcmFnZV9maWxlcy85Zi84MS85ZjgxNjA1NC0yODgxLTRhZGEtYWNmNy03ZWI3YTg4NmFhNjAvZS1hLWFtYXppbmctZmlsZS5qcGcifSx7IkNvbnRlbnQtRGlzcG9zaXRpb24iOiJhdHRhY2htZW50OyBmaWxlbmFtZT1cImUtYS1hbWF6aW5nLWZpbGUuanBnXCI7IGZpbGVuYW1lKj1VVEYtOCcnJUMzJUE4JTIwJUMzJUEwJTIwQW1hemluZyUyMGZpbGUuanBnIn0seyJDb250ZW50LVR5cGUiOiJpbWFnZS9qcGVnIn0seyJDYWNoZS1Db250cm9sIjoicHVibGljLCBtYXgtYWdlPTI1OTIwMDAifSx7IkV4cGlyZXMiOiJTdW4sIDA4IEFwciAyMDI5IDE3OjM5OjAzIEdNVCJ9LHsieC1hbXotbWV0YS1maWxlX2lkIjoiOWY4MTYwNTQtMjg4MS00YWRhLWFjZjctN2ViN2E4ODZhYTYwIn0seyJ4LWFtei1tZXRhLW9yZ2FuaXphdGlvbl9pZCI6IjlmODE2MDU0LTI4ODEtNGFkYS1hY2Y3LTdlYjdhODg2YWE2MCJ9LFsiY29udGVudC1sZW5ndGgtcmFuZ2UiLDMxNDU3MjgsMzE0NTcyOF0seyJzdWNjZXNzX2FjdGlvbl9zdGF0dXMiOiIyMDEifSx7IngtYW16LWNyZWRlbnRpYWwiOiJBS0lBSUNHS0xJVFlUVlA0N0U2US8yMDE5MDQwOC9ldS13ZXN0LTIvczMvYXdzNF9yZXF1ZXN0In0seyJ4LWFtei1hbGdvcml0aG0iOiJBV1M0LUhNQUMtU0hBMjU2In0seyJ4LWFtei1kYXRlIjoiMjAxOTA0MDhUMTczOTAzWiJ9XX0=",
      "x-amz-credential": "AKIAICGKLITYTVP47E6Q/20190408/eu-west-2/s3/aws4_request",
      "x-amz-algorithm": "AWS4-HMAC-SHA256",
      "x-amz-date": "20190408T173903Z",
      "x-amz-signature": "cecfa3a4d9c1677f3fb99bb5f3ba991196d6857ce746f271c9768f0d74c35055"
    }
  }
}</pre>
