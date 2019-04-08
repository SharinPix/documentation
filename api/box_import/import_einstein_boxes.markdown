# Box Import API

## Import einstein boxes

### POST /api/v1/box_imports

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| payload | Einstein boxes payload | false |  |
| image_id | Image Id | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjMsImlhdCI6MTU1NDc0NTEyMywidXNlcl9pZCI6IjM5YjM1MWE5LWE2MmMtNDA5Yi1iNzk3LWRjMTU2YmQ4Mzk0ZiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCNSI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZSwiZWluc3RlaW5fYm94Ijp0cnVlfX19fQ.e9JLrO5ya-e5V1gcgH9L6EaxP8uviWKj9ceeHPn7NjI&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/box_imports</pre>

#### Body

<pre>payload=%5B%7B+%22probability%22%3A+0.9891305%2C+%22label%22%3A+%22700MLX6IT%22%2C+%22boundingBox%22%3A+%7B+%22minY%22%3A+2059%2C+%22minX%22%3A+2248%2C+%22maxY%22%3A+2571%2C+%22maxX%22%3A+2456+%7D+%7D%2C%0A++++++++%7B+%22probability%22%3A+0.90%2C+%22label%22%3A+%22800YUT%22%2C+%22boundingBox%22%3A+%7B+%22minY%22%3A+2059%2C+%22minX%22%3A+2248%2C+%22maxY%22%3A+2571%2C+%22maxX%22%3A+2456+%7D+%7D%5D&image_id=d858303f-0fba-414e-b52b-3d56d38f0638</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MjQsImlhdCI6MTU1NDc0NTEyNCwidXNlcl9pZCI6IjM5YjM1MWE5LWE2MmMtNDA5Yi1iNzk3LWRjMTU2YmQ4Mzk0ZiIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCNSI6eyJBY2Nlc3MiOnsiaW1hZ2VfbGlzdCI6dHJ1ZSwiZWluc3RlaW5fYm94Ijp0cnVlfX19fQ.WA1ZK_SjyJ7sdkotRp8GCfR8cf9eO37pNe5QlUytdoU
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: f2b4a011-b009-4a95-b330-ed4885f9a03c
X-Runtime: 0.068478
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 485</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "6fa804ae-7401-41f5-a155-ee87f895a950",
  "image_id": "d858303f-0fba-414e-b52b-3d56d38f0638",
  "organization_id": "f950bf22-4f93-469b-836d-3766c2f02f1f",
  "processed_at": null,
  "payload": [
    {
      "probability": 0.9891305,
      "label": "700MLX6IT",
      "boundingBox": {
        "minY": 2059,
        "minX": 2248,
        "maxY": 2571,
        "maxX": 2456
      }
    },
    {
      "probability": 0.9,
      "label": "800YUT",
      "boundingBox": {
        "minY": 2059,
        "minX": 2248,
        "maxY": 2571,
        "maxX": 2456
      }
    }
  ],
  "created_at": "2019-04-08T19:38:44.016+02:00",
  "updated_at": "2019-04-08T19:38:44.016+02:00"
}</pre>
