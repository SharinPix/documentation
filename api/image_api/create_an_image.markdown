# Image API API

## Create an image

### POST /api/v1/albums/:album_id/images/

### Parameters

| Name | Description | Required | Scope |
|------|-------------|----------|-------|
| album_id | Album Id | false |  |
| cloudinary | Result from cloudinary direct upload | false |  |
| metadatas | Metadatas you want to add to the image. | false |  |

### Request

#### Headers

<pre>Authorization: Token token=&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzQsImlhdCI6MTU1NDc0NTEzNCwidXNlcl9pZCI6IjBmMmE1YmQxLTEwNDUtNDdjNy1hZWJlLWQ3OWQ5ZGQwZWU5ZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTQ2Ijp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.VuXWW0r189qY2g5hMnVQ3ETGIt2MY4IWbkJ4IBxiPeQ&quot;
Host: example.org
Content-Type: application/x-www-form-urlencoded
Cookie: </pre>

#### Route

<pre>POST /api/v1/albums/00100000123BB146/images/</pre>

#### Body

<pre>cloudinary[public_id]=c6y8knpw2ywwwfc6cykj&cloudinary[version]=1484586860&cloudinary[signature]=8ae13af1294831022d2af7fd71f1e9ab063c673c&cloudinary[width]=295&cloudinary[height]=171&cloudinary[format]=jpg&cloudinary[resource_type]=image&cloudinary[created_at]=2017-01-16T17%3A14%3A20Z&cloudinary[tags][]=a0Ab000000u975pEAA&cloudinary[bytes]=10668&cloudinary[type]=authenticated&cloudinary[etag]=acf8af3e54c78cbf24a53a93c93bab43&cloudinary[url]=http%3A%2F%2Fres.cloudinary.com%2Fhdtp0enrj%2Fimage%2Fauthenticated%2Fs--N4U79Bcw--%2Fv1484586860%2Fc6y8knpw2ywwwfc6cykj.jpg&cloudinary[secure_url]=https%3A%2F%2Fres.cloudinary.com%2Fhdtp0enrj%2Fimage%2Fauthenticated%2Fs--N4U79Bcw--%2Fv1484586860%2Fc6y8knpw2ywwwfc6cykj.jpg&cloudinary[image_metadata][JFIFVersion]=1.01&cloudinary[image_metadata][ResolutionUnit]=None&cloudinary[image_metadata][XResolution]=1&cloudinary[image_metadata][YResolution]=1&cloudinary[image_metadata][Colorspace]=RGB&cloudinary[image_metadata][DateTimeOriginal]=2018%3A01%3A01+08%3A00%3A00&cloudinary[colors][]=%23EBF1F9&cloudinary[colors][]=13.2&cloudinary[colors][]=%23D9E5F5&cloudinary[colors][]=8.8&cloudinary[colors][]=%23CAD7EC&cloudinary[colors][]=7.2&cloudinary[colors][]=%23CDCECD&cloudinary[colors][]=6.1&cloudinary[colors][]=%238DA9CB&cloudinary[colors][]=4.7&cloudinary[colors][]=%23A9BAD2&cloudinary[colors][]=4.7&cloudinary[colors][]=%23B9CBE5&cloudinary[colors][]=4&cloudinary[colors][]=%23C8B6AB&cloudinary[colors][]=3.9&cloudinary[colors][]=%23B2B2AE&cloudinary[colors][]=3.6&cloudinary[colors][]=%23E4E5D7&cloudinary[colors][]=3.2&cloudinary[colors][]=%2391928E&cloudinary[colors][]=3&cloudinary[colors][]=%239BA19E&cloudinary[colors][]=2.9&cloudinary[colors][]=%23676B5C&cloudinary[colors][]=2.4&cloudinary[colors][]=%23929A6C&cloudinary[colors][]=2.3&cloudinary[colors][]=%237D9CC3&cloudinary[colors][]=2.3&cloudinary[colors][]=%237FA1C5&cloudinary[colors][]=2.2&cloudinary[colors][]=%2378895D&cloudinary[colors][]=2.1&cloudinary[colors][]=%23DAC653&cloudinary[colors][]=2.1&cloudinary[colors][]=%237D7A88&cloudinary[colors][]=2.1&cloudinary[colors][]=%236F8737&cloudinary[colors][]=1.9&cloudinary[colors][]=%23AAAC95&cloudinary[colors][]=1.9&cloudinary[colors][]=%2384A1C6&cloudinary[colors][]=1.9&cloudinary[colors][]=%23B5C5D7&cloudinary[colors][]=1.7&cloudinary[colors][]=%233F4225&cloudinary[colors][]=1.6&cloudinary[colors][]=%23BBC5AA&cloudinary[colors][]=1.6&cloudinary[colors][]=%23C7C8B7&cloudinary[colors][]=1.6&cloudinary[colors][]=%23B65F59&cloudinary[colors][]=1.4&cloudinary[colors][]=%23A5CCE6&cloudinary[colors][]=1.3&cloudinary[colors][]=%23565D2E&cloudinary[colors][]=1.2&cloudinary[colors][]=%23252818&cloudinary[colors][]=1.1&cloudinary[colors][]=%23DCD99C&cloudinary[colors][]=1&cloudinary[colors][]=%23798EA3&cloudinary[colors][]=0.8&cloudinary[predominant][google][]=blue&cloudinary[predominant][google][]=51.5&cloudinary[predominant][google][]=yellow&cloudinary[predominant][google][]=30.6&cloudinary[predominant][google][]=green&cloudinary[predominant][google][]=9&cloudinary[predominant][google][]=gray&cloudinary[predominant][google][]=5.3&cloudinary[predominant][google][]=purple&cloudinary[predominant][google][]=2.1&cloudinary[predominant][google][]=teal&cloudinary[predominant][google][]=1.3&cloudinary[phash]=d8c926d5c28b6c67&cloudinary[coordinates][faces][]=&cloudinary[illustration_score]=0.30062443017959595&cloudinary[semi_transparent]=false&cloudinary[grayscale]=false&cloudinary[original_filename]=download&metadatas[meta]=data</pre>

### Response

#### Headers

<pre>Cache-Control: no-cache, no-store
Pragma: no-cache
Expires: Fri, 01 Jan 1990 00:00:00 GMT
Content-Type: application/json; charset=utf-8
X-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE1NTQ3NTk1MzQsImlhdCI6MTU1NDc0NTEzNCwidXNlcl9pZCI6IjBmMmE1YmQxLTEwNDUtNDdjNy1hZWJlLWQ3OWQ5ZGQwZWU5ZCIsImFiaWxpdGllcyI6eyIwMDEwMDAwMDEyM0JCMTQ2Ijp7IkFjY2VzcyI6eyJpbWFnZV91cGxvYWQiOnRydWV9fX19.VuXWW0r189qY2g5hMnVQ3ETGIt2MY4IWbkJ4IBxiPeQ
Vary: Accept-Encoding
P3P: CP=&quot;NOI ADM DEV PSAi COM NAV OUR OTRo STP IND DEM&quot;
X-Request-Id: afeefd5c-481d-4b3b-a756-74fe4441095a
X-Runtime: 0.035250
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
X-Download-Options: noopen
X-Permitted-Cross-Domain-Policies: none
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Length: 4330</pre>

#### Status

<pre>200 OK</pre>

#### Body

<pre>{
  "id": "afeb0ef9-fe32-4b2d-81c3-f92b3f6990a1",
  "public_id": "afeb0ef9-fe32-4b2d-81c3-f92b3f6990a1",
  "infos": {
    "public_id": "c6y8knpw2ywwwfc6cykj",
    "version": "1484586860",
    "signature": "8ae13af1294831022d2af7fd71f1e9ab063c673c",
    "width": "295",
    "height": "171",
    "format": "jpg",
    "resource_type": "image",
    "created_at": "2017-01-16T17:14:20Z",
    "tags": [
      "a0Ab000000u975pEAA"
    ],
    "bytes": "10668",
    "type": "authenticated",
    "etag": "acf8af3e54c78cbf24a53a93c93bab43",
    "url": "http://res.cloudinary.com/hdtp0enrj/image/authenticated/s--N4U79Bcw--/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "secure_url": "https://res.cloudinary.com/hdtp0enrj/image/authenticated/s--N4U79Bcw--/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "image_metadata": {
      "JFIFVersion": "1.01",
      "ResolutionUnit": "None",
      "XResolution": "1",
      "YResolution": "1",
      "Colorspace": "RGB",
      "DateTimeOriginal": "2018:01:01 08:00:00"
    },
    "colors": [
      "#EBF1F9",
      "13.2",
      "#D9E5F5",
      "8.8",
      "#CAD7EC",
      "7.2",
      "#CDCECD",
      "6.1",
      "#8DA9CB",
      "4.7",
      "#A9BAD2",
      "4.7",
      "#B9CBE5",
      "4",
      "#C8B6AB",
      "3.9",
      "#B2B2AE",
      "3.6",
      "#E4E5D7",
      "3.2",
      "#91928E",
      "3",
      "#9BA19E",
      "2.9",
      "#676B5C",
      "2.4",
      "#929A6C",
      "2.3",
      "#7D9CC3",
      "2.3",
      "#7FA1C5",
      "2.2",
      "#78895D",
      "2.1",
      "#DAC653",
      "2.1",
      "#7D7A88",
      "2.1",
      "#6F8737",
      "1.9",
      "#AAAC95",
      "1.9",
      "#84A1C6",
      "1.9",
      "#B5C5D7",
      "1.7",
      "#3F4225",
      "1.6",
      "#BBC5AA",
      "1.6",
      "#C7C8B7",
      "1.6",
      "#B65F59",
      "1.4",
      "#A5CCE6",
      "1.3",
      "#565D2E",
      "1.2",
      "#252818",
      "1.1",
      "#DCD99C",
      "1",
      "#798EA3",
      "0.8"
    ],
    "predominant": {
      "google": [
        "blue",
        "51.5",
        "yellow",
        "30.6",
        "green",
        "9",
        "gray",
        "5.3",
        "purple",
        "2.1",
        "teal",
        "1.3"
      ]
    },
    "phash": "d8c926d5c28b6c67",
    "coordinates": {
      "faces": [
        ""
      ]
    },
    "illustration_score": "0.30062443017959595",
    "semi_transparent": "false",
    "grayscale": "false",
    "original_filename": "download"
  },
  "exifs": {
    "JFIFVersion": "1.01",
    "ResolutionUnit": "None",
    "XResolution": "1",
    "YResolution": "1",
    "Colorspace": "RGB",
    "DateTimeOriginal": "2018:01:01 08:00:00"
  },
  "gps": null,
  "gps_ip": null,
  "gps_exifs": null,
  "gps_html": null,
  "created_at": "2019-04-08T19:38:54.558+02:00",
  "updated_at": "2019-04-08T19:38:54.558+02:00",
  "taken_at": "2018-01-01T08:00:00.000+00:00",
  "width": 295,
  "height": 171,
  "rotation": 0,
  "crop_x": 0.0,
  "crop_y": 0.0,
  "crop_w": 0.0,
  "crop_h": 0.0,
  "metadatas": {
    "meta": "data"
  },
  "original_url": "https://res.cloudinary.com/sadaasdasd/image/authenticated/s--Q6DgqH5q--/fl_attachment/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
  "original_width": 295,
  "original_height": 171,
  "external_urls": {
    "fill100": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s---fYBFoyF--/c_fit,w_300/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "fit2000": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--iKmIBuBi--/c_fit,h_2000,w_2000/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "mini": "https://sharinpix-proxy-dev.herokuapp.com/download.jpg?s=a2f1a17&url=localhost/images/afeb0ef9-fe32-4b2d-81c3-f92b3f6990a1/thumbnails/mini-71414a3a863.jpg",
    "large": "https://sharinpix-proxy-dev.herokuapp.com/download.jpg?s=42053f1&url=localhost/images/afeb0ef9-fe32-4b2d-81c3-f92b3f6990a1/thumbnails/thumbnail-8507ddedca8.jpg",
    "full": "https://sharinpix-proxy-dev.herokuapp.com/download.jpg?s=b23550c&url=localhost/images/afeb0ef9-fe32-4b2d-81c3-f92b3f6990a1/thumbnails/full-7ca144cd69c.jpg"
  },
  "filename": "download",
  "format": "jpg",
  "title": null,
  "description": null,
  "page": 1,
  "group_id": null,
  "color": "#",
  "size": "10668",
  "processed": false,
  "processing_error": null,
  "album_id": "00100000123BB146",
  "thumbnails": {
    "original": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--ikQAoRWa--/fl_attachment/dpr_auto,q_auto,f_auto/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "full_no_sharinpix": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--fwSaqi-h--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "full": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--fwSaqi-h--/c_fit,h_1920,w_1920/fl_attachment/dpr_auto,q_auto,f_auto/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "large": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--jZNZzW9W--/c_fit,h_1920,w_1920/c_fill,h_200,w_200/fl_attachment/dpr_auto,q_auto,f_auto/v1484586860/c6y8knpw2ywwwfc6cykj.jpg",
    "mini": "/assets/blank.jpg#https://res.cloudinary.com/sadaasdasd/image/authenticated/s--IXbYMoDd--/c_fit,h_1920,w_1920/c_fill,h_100,w_100/fl_attachment/dpr_auto,q_auto,f_auto/v1484586860/c6y8knpw2ywwwfc6cykj.jpg"
  }
}</pre>
