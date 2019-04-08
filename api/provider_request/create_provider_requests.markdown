# Provider request API

## Create provider requests

### POST /api/v1/providers/:provider_id/provider_requests

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| image_ids | List of image ids | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6ImNlNTk3YWRiLWU3ZjEtNGU5Yi1hYTVhLTk1ZTJiZjgyOTcxNCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19fQ.-HgJWE0ZcIfzOzxtxY5IcqevEL47PJlVXBqUuLtPZT4&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/providers/b870990d-396b-46ca-a92e-ba6a63bacc61/provider_requests</pre>

#### Body

<pre>image_ids[]=0d8611a7-be32-4924-b7c4-12a82ea78af8&image_ids[]=5d780faf-8bb1-4858-92cc-e92fe2cbe971&image_ids[]=ea839caa-719d-4320-a982-08cfd703f396</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzYsImlhdCI6MTU1NDc0NTEzNiwidXNlcl9pZCI6ImNlNTk3YWRiLWU3ZjEtNGU5Yi1hYTVhLTk1ZTJiZjgyOTcxNCIsImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiUHJvdmlkZXJzIjpbInRlc3QgcHJvdmlkZXIiXX19fQ.-HgJWE0ZcIfzOzxtxY5IcqevEL47PJlVXBqUuLtPZT4
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 8140f0e1-75de-4d10-a0af-6da79648a38c
X-Runtime: 0.061733
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 754</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[
  {
    "image_id": "ea839caa-719d-4320-a982-08cfd703f396",
    "provider_id": "b870990d-396b-46ca-a92e-ba6a63bacc61",
    "organization_id": "f1fc97e3-35ce-482c-8c3a-d95f2aaf5581",
    "created_at": "2019-04-08T19:38:56.613+02:00",
    "id": "cae9fa9e-cc08-4a53-8007-00e5ece96743"
  },
  {
    "image_id": "5d780faf-8bb1-4858-92cc-e92fe2cbe971",
    "provider_id": "b870990d-396b-46ca-a92e-ba6a63bacc61",
    "organization_id": "f1fc97e3-35ce-482c-8c3a-d95f2aaf5581",
    "created_at": "2019-04-08T19:38:56.620+02:00",
    "id": "e947c238-c528-4b6d-953b-bfcc1fb1aa56"
  },
  {
    "image_id": "0d8611a7-be32-4924-b7c4-12a82ea78af8",
    "provider_id": "b870990d-396b-46ca-a92e-ba6a63bacc61",
    "organization_id": "f1fc97e3-35ce-482c-8c3a-d95f2aaf5581",
    "created_at": "2019-04-08T19:38:56.629+02:00",
    "id": "828fbcd0-d41c-4642-ada6-9ed017abec46"
  }
]</pre>
