# HHI Definitions For PSR15, HTTP Handlers

It is based on the PHP interface definitions and comments available here:

[psr/http-server-handler](https://github.com/php-fig/http-server-handler)

[psr/http-server-middleware](https://github.com/php-fig/http-server-middleware)

## install
```bash
$ hhvm -d xdebug.enable=0 -d hhvm.jit=0 -d hhvm.php7.all=1 -d hhvm.hack.lang.auto_typecheck=0 $(which composer) require ytake/psr-http-handlers-hhi
```

### example php7.ini

```
[hhvm]
hhvm.jit=false
hhvm.php7.all=1
hhvm.hack.lang.auto_typecheck=0
```
