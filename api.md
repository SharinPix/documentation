# Documentation

### Authentication

SharinPix use [JSON Web Tokens](http://jwt.io/) to authenticate requests.

Here are the steps to generate a SharinPix token.

- Create a SharinPix secret on [SharinPix admin interface](https://app.sharinpix.com/admin)
(if your are not admin, please contact SharinPix support) Note the secret id and
secret secret. In our example :

```
id : secretid-0000-0000-0000-secretid0000
secret : secretsecretsecretsecretscret000
```

- Create a JWT token, set the iss parameter to the secret id and use the secret
  to sign the JWT token. It is recommended to define the expiration date of your token. Example :

```ruby
payload = {
  exp: (Time.zone.now.to_i + 12.hours.to_i),
  iss: 'secretid-0000-0000-0000-secretid0000',
  abilities: {
    'an-album-id' => {
      Access: {
        see: true,
        image_list: true,
        image_upload: true
      },
    }
  }
}
JWT.encode(payload, 'secretsecretsecretsecretscret000')
```

In this example we are generating a token with the ability to see, list images
and add images to the album with id : "an-album-id".


With this token, you can make requests against [SharinPix API](api/index.markdown) or display albums to
users with an iframe like this :


```html
<iframe style="border: 0;width: 100%;height: 400px;"
src="https://app.sharinpix.com/pagelayout/an-album-id?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE0NTY5NTM0NTcsImlzcyI6InNlY3JldGlkLTAwMDAtMDAwMC0wMDAwLXNlY3JldGlkMDAwMCIsImFiaWxpdGllcyI6eyJhbi1hbGJ1bS1pZCI6eyJBY2Nlc3MiOnsic2VlIjp0cnVlLCJpbWFnZV9saXN0Ijp0cnVlLCJpbWFnZV91cGxvYWQiOnRydWV9fX19.f1_S49veaevYji-xTtDKVFhFNATdd2QarisHxew_aCQ"/>
```


You should always generate the token on a server. If somebody access your
SharinPix secret he can generate any token and access all datas stored on
SharinPix.


### Api reference

[API reference](api/index.markdown)
