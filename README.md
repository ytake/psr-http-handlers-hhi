# HHI Definitions For PSR15, HTTP Handlers

It is based on the PHP interface definitions and comments available here:

[http-interop/http-server-handler](https://github.com/http-interop/http-server-handler)

[http-interop/http-server-middleware](https://github.com/http-interop/http-server-middleware)

## install
```bash
$ hhvm -c php7.ini $(which composer) require ytake/psr-http-handlers-hhi
```

### example php7.ini

```
[hhvm]
hhvm.jit=false
hhvm.php7.all=1
hhvm.hack.lang.auto_typecheck=0
```
