# fedex-notes

## How to run against prod from home

- in /etc/hosts there need to be an entry
  127.0.0.1 local.fedex.com
- checkout PR branche for FE
- to run agains prod BE (main): `npm run start:prod`
- Delete domain security policies local.fedex.com
- Switch proxy to WFH and go to [local.fedex.com](http://local.fedex.com)
- Switch proxy to Direct and go to [fedex.com](https://www.fedex.com/shippingplus/en-gb/login) to login
- Delete domain security policies [local.fedex.com](http://local.fedex.com)
- Switch proxy to WFH and go to [local.fedex.com](http://local.fedex.com)
