# Tips and Tricks

## Dealing with records

`curl -I <domain>`

Example response:

```
HTTP/1.1 301 Moved Permanently
x-amz-id-2: GhbglnY4TMT7NQy4HEFfBbrYo1L6OgepT1130/R80lZm6yDUCH8Ok
x-amz-request-id: C72E7BA4D7A6DEB8
Date: Thu, 31 Aug 2017 22:51:42 GMT
Location: https://www.domain.com/
Content-Length: 0
Server: AmazonS3
```

`dig afxr gitgood.club` - gives back record data.

