# Laravel Google Contact

[![Latest Version on Packagist](https://img.shields.io/packagist/v/reubenwedson/laravel-google-contacts.svg?style=flat-square)](https://packagist.org/packages/reubenwedson/laravel-google-contacts)
[![Build Status](https://img.shields.io/travis/reubenwedson/laravel-google-contacts/master.svg?style=flat-square)](https://travis-ci.org/reubenwedson/laravel-google-contacts)
[![Quality Score](https://img.shields.io/scrutinizer/g/reubenwedson/laravel-google-contacts.svg?style=flat-square)](https://scrutinizer-ci.com/g/reubenwedson/laravel-google-contacts)
[![Total Downloads](https://img.shields.io/packagist/dt/reubenwedson/laravel-google-contacts.svg?style=flat-square)](https://packagist.org/packages/reubenwedson/laravel-google-contacts)

Allow easy acces to Google Contacts in Laravel Application

## Installation

You can install the package via composer:

```bash
composer require reubenwedson/laravel-google-contacts
```

## Usage

``` php
// simple usage
$contacts = manager()->getContacts();
```

### Testing

``` bash
composer test
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email reubenwedson@gmail.com instead of using the issue tracker.

## Credits

- [Reuben Wedson](https://github.com/reubenwedson)
- [Alpha Olomi](https://github.com/alphaolomi)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## PHP Package Boilerplate

This package was generated using the [PHP Package Boilerplate](https://laravelpackageboilerplate.com).
