# Sharing API

## retrieve sharings

### GET api/v1/albums/:album_id/sharings
### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MDksImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiU2hhcmluZ3MiOnsic2hhcmluZyI6InNoYXJpbmcifX19LCJ1c2VyX2lkIjoiZmY0MzM2MGQtN2U4Ni00Y2NiLTg5NGUtYTI2Yjc1ODhhODhkIn0.WuXbnxFRSq-Fj_SH_0-b_ORPRS2pn7RsinqAr1gmMg4&quot;
Host: example.org
Cookie: </pre>

#### Route

<pre>GET api/v1/albums/00324000004ijWS/sharings</pre>

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
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTI2MjE5MDksImFiaWxpdGllcyI6eyIwMDMyNDAwMDAwNGlqV1MiOnsiU2hhcmluZ3MiOnsic2hhcmluZyI6InNoYXJpbmcifX19LCJ1c2VyX2lkIjoiZmY0MzM2MGQtN2U4Ni00Y2NiLTg5NGUtYTI2Yjc1ODhhODhkIn0.WuXbnxFRSq-Fj_SH_0-b_ORPRS2pn7RsinqAr1gmMg4
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: 214900d6-cbda-4202-a26a-b905a887b52f
X-Runtime: 0.076459
Content-Length: 225</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>[{"id":"49f34537-4a1c-43b9-b276-881c62767213","created_at":"2016-01-12T15:05:09.669+01:00","name":"sharing","label":"{\"en\": \"Homepage\", \"fr\": \"Page d'acceuil\"}","url":"/sharings/49f34537-4a1c-43b9-b276-881c62767213"}]</pre>
