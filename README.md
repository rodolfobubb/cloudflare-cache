grunt-cloudflare
================

CloudFlare Grunt Task talking to the CloudFlare API.
The default action is to purge the CloudFlare cache.
This package This package is a modification of grunt-cloudflare.
Credits for strathausen.

Options
-------

``` js
cloudflare: {
  /* Action, default is to purge the cache */
  a: 'fpurge_ts',
  /* CloudFlare credentials */
  /* API key */
  tkn: process.env.CLOUDFLARE_API_KEY,
  /* CloudFlare e-mail */
  email: process.env.CLOUDFLARE_EMAIL,
  /* Domain */
  z: process.env.CLOUDFLARE_DOMAIN  
  /* Files to purge the cache */
  url: ['http://www.example.com/style.css', 'http://www.example.com/app.js']
}
```

For more options, see the
 [CloudFlare API Docs](http://www.cloudflare.com/docs/client-api.html#s2.1).

Modifying this plug-in to support more CloudFlare actions
should be straight forward.
Don't hesitate sending in a pull request.
if you need another feature.
Purge CloudFlare Cache Grunt Task. This package is a modification of strathausen/grunt-cloudflare
