# Laravel-Swoole

This package provides a high performance HTTP server to speed up your Laravel/Lumen application based on [Swoole](http://www.swoole.com/).

## Version Compatibility

| PHP     | Laravel | Lumen | Swoole  |
|:-------:|:-------:|:-----:|:-------:|
| >=7.1 | ~5.1    | ~5.1  | >=4.0.0 |

##install lumen

lumen in bootstrap/app.php

$app->configure('swoole_http');
$app->configure('swoole_websocket');

$app->register(SwooleTW\Http\LumenServiceProvider::class);

in config/:
copy swoole_http.php
copy swoole_websocket.php

start server:
/usr/local/php728/bin/php artisan swoole:http start

## License

The Laravel-Swoole package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Support on Beerpay
Hey dude! Help me out for a couple of :beers:!