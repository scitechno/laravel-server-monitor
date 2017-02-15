# Very short description of the package

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/laravel-server-monitor.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-server-monitor)
[![Build Status](https://img.shields.io/travis/spatie/laravel-server-monitor/master.svg?style=flat-square)](https://travis-ci.org/spatie/laravel-server-monitor)
[![SensioLabsInsight](https://img.shields.io/sensiolabs/i/xxxxxxxxx.svg?style=flat-square)](https://insight.sensiolabs.com/projects/xxxxxxxxx)
[![Quality Score](https://img.shields.io/scrutinizer/g/spatie/laravel-server-monitor.svg?style=flat-square)](https://scrutinizer-ci.com/g/spatie/laravel-server-monitor)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/laravel-server-monitor.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-server-monitor)

**Note:** Replace ```Freek Van der Herten``` ```freekmurze``` ```freek@spatie.be``` ```laravel-server-monitor``` ```Monitor servers``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what PSRs you support to avoid any confusion with users and contributors.

## Postcardware

You're free to use this package (it's [MIT-licensed](LICENSE.md)), but if it makes it to your production environment we highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using.

Our address is: Spatie, Samberstraat 69D, 2060 Antwerp, Belgium.

The best postcards will get published on the open source page on our website.

## Installation

**Note:** Remove this paragraph if you are building a public package  
This package is custom built for [Spatie](https://spatie.be) projects and is therefore not registered on packagist. In order to install it via composer you must specify this extra repository in `composer.json`:

```json
"repositories": [ { "type": "composer", "url": "https://satis.spatie.be/" } ]
```

You can install the package via composer:

``` bash
composer require spatie/laravel-server-monitor
```

## Usage

``` php
$ServerMonitor = new Spatie\ServerMonitor();
echo $ServerMonitor->echoPhrase('Hello, Spatie!');
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email freek@spatie.be instead of using the issue tracker.

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## About Spatie

Spatie is a webdesign agency based in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.