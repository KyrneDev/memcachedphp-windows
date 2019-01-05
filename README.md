# Memcached emulator

[![License](https://poser.pugx.org/avantarm/memcached-emulator/license)](https://packagist.org/packages/avantarm/memcached-emulator)

Memcached PHP extension emulator for Windows environment. 

Emulates Memcached extension for PHP.

## Installation via Composer

Add `"CDK2020/memcachedphp-windows": "~1.0"` to the require block in your composer.json and then run `composer install`.

```json
{
	"require": {
		"CDK2020/memcachedphp-windows": "~1.0"
	}
}
```

Alternatively, you can simply run the following from the command line:

```sh
composer require CDK2020/memcachedphp-windows
```

Unsupported methods because I don't have time to make them work:

```php
Memcached::setSaslAuthData()
Memcached::fetch()
Memcached::fetchAll()
Memcached::getDelayed()
Memcached::getDelayedByKey()
```

`$time` parameter is not supported for `Memcached::delete()` and `Memcached::deleteByKey()`.