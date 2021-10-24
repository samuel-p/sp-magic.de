# sp-magic.de

Website for sp-magic.de

[GitHub](https://github.com/samuel-p/sp-magic.de)
[GitLab](https://gitlab.com/samuel-p/sp-magic.de)

## Additional Header Parameters

The following Parameters are set directly on the Web-Server.

```
Content-Security-Policy: default-src 'none'; script-src 'self' https://umami.sp-codes.de; object-src 'none'; style-src 'self'; img-src 'self'; media-src 'none'; frame-src 'none'; font-src 'self'; connect-src 'self' https://umami.sp-codes.de
Referrer-Policy: strict-origin-when-cross-origin
Feature-Policy: sync-xhr 'self'
Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
X-Content-Type-Options: nosniff
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
```

There is also a `301` Redirect from http to https.
