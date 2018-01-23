# HHI Definitions For PSR15, HTTP Handlers

[![Packagist](https://img.shields.io/badge/HHVM-%3E=3.19-orange.svg)](https://packagist.org/packages/ytake/psr-http-handlers-hhi)
[![Packagist](https://img.shields.io/packagist/l/ytake/psr-http-handlers-hhi.svg?style=flat-square)](https://packagist.org/packages/ytake/psr-http-handlers-hhi)
[![Packagist](https://img.shields.io/packagist/dt/ytake/psr-http-handlers-hhi.svg?style=flat-square)](https://packagist.org/packages/ytake/psr-http-handlers-hhi)
[![Packagist](https://img.shields.io/packagist/v/ytake/psr-http-handlers-hhi.svg?style=flat-square)](https://packagist.org/packages/ytake/psr-http-handlers-hhi)

It is based on the PHP interface definitions and comments available here:

[psr/http-server-handler](https://github.com/php-fig/http-server-handler)

[psr/http-server-middleware](https://github.com/php-fig/http-server-middleware)

## install
```bash
$ hhvm -d xdebug.enable=0 -d hhvm.jit=0 -d hhvm.php7.all=1 -d hhvm.hack.lang.auto_typecheck=0 $(which composer) require ytake/psr-http-handlers-hhi
```
