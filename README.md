# Dispatch Laravel jobs via Artisan

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/laravel-artisan-dispatchable.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-artisan-dispatchable)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/spatie/laravel-artisan-dispatchable/run-tests?label=tests)](https://github.com/spatie/laravel-artisan-dispatchable/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/spatie/laravel-artisan-dispatchable/Check%20&%20fix%20styling?label=code%20style)](https://github.com/spatie/laravel-artisan-dispatchable/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/laravel-artisan-dispatchable.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-artisan-dispatchable)

---
This repo can be used as to scaffold a Laravel package. Follow these steps to get started:

1. Press the "Use template" button at the top of this repo to create a new repo with the contents of this laravel-artisan-dispatchable
2. Run "./configure-laravel-artisan-dispatchable.sh" to run a script that will replace all placeholders throughout all the files
3. Remove this block of text.
4. Have fun creating your package.
5. If you need help creating a package, consider picking up our <a href="https://laravelpackage.training">Laravel Package Training</a> video course.
---

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Support us

[<img src="https://github-ads.s3.eu-central-1.amazonaws.com/laravel-artisan-dispatchable.jpg?t=1" width="419px" />](https://spatie.be/github-ad-click/laravel-artisan-dispatchable)

We invest a lot of resources into creating [best in class open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://spatie.be/about-us). We publish all received postcards on [our virtual postcard wall](https://spatie.be/open-source/postcards).

## Installation

You can install the package via composer:

```bash
composer require spatie/laravel-artisan-dispatchable
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --provider="Spatie\ArtisanDispatchable\ArtisanDispatchableServiceProvider" --tag="laravel-artisan-dispatchable-migrations"
php artisan migrate
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="Spatie\ArtisanDispatchable\ArtisanDispatchableServiceProvider" --tag="laravel-artisan-dispatchable-config"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

```php
$laravel-artisan-dispatchable = new Spatie\ArtisanDispatchable();
echo $laravel-artisan-dispatchable->echoPhrase('Hello, Spatie!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
