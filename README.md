# fusonic/seed

[![Build Status](https://travis-ci.org/fusonic/seed.png)](https://travis-ci.org/fusonic/seed)
[![Total Downloads](https://poser.pugx.org/fusonic/seed/downloads.png)](https://packagist.org/packages/fusonic/seed)

A blank repository to use as stub for PHP libraries.

## Requirements

* PHP 5.4 and up

## Installation

The easiest installation method is using Composer: Simply create a ```composer.json``` file in the root of your project:
``` json
{
    "require": {
        "fusonic/opengraph": "@dev"
    }
}
```

Install composer and run install command:
``` bash
curl -s http://getcomposer.org/installer | php
php composer.phar install
```

Once installed, include vendor/autoload.php in your script.

``` php
require "vendor/autoload.php";
```

## Usage

_Put some examples here._

## Running tests

You can run the test suite with the following command:

``` bash
phpunit --bootstrap tests/bootstrap.php .
```

## License

This library is licensed under the MIT license.
