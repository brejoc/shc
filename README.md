# Sechead
Inspect your head!

Sechead is a library enabling you to inspect HTTP headers.

## Usage

`$ python3 sechead.py http://example.com`

You'll then see an output like this:

```
http://heise.de
---------------
Server                                       nginx
Content-Type                                 text/html; charset=UTF-8
Last-Modified                                Fri, 27 Oct 2017 21:43:25 GMT
Expires                                      Fri, 27 Oct 2017 21:43:57 GMT
Cache-Control                                public, max-age=32
Transfer-Encoding                            chunked
Date                                         Fri, 27 Oct 2017 21:43:54 GMT
Age                                          29
Connection                                   close
Content-Security-Policy-Report-Only          default-src 'self' data: 'unsafe-inline' 'unsafe-eval' https:; report-uri https://heise.report-uri.io/r/default/csp/reportOnly https://heise.de/csp/
Vary                                         Accept-Encoding,X-Forwarded-Proto,User-Agent,X-Export-Format,X-Export-Agent
```

## Requirements
Python 3 or higher
Crayons