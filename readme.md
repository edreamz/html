# Laravel 11 Compatible Fork of the LaravelCollective Forms Package

[![Backend Tests](https://img.shields.io/github/actions/workflow/status/artkonekt/html/tests.yml?branch=master&label=backend&style=flat-square)](https://github.com/artkonekt/html/actions?query=workflow%3Atests)
[![Packagist Stable Version](https://img.shields.io/packagist/v/konekt/html.svg?style=flat-square&label=stable)](https://packagist.org/packages/konekt/html)
[![Packagist downloads](https://img.shields.io/packagist/dt/konekt/html.svg?style=flat-square)](https://packagist.org/packages/konekt/html)
[![License](https://poser.pugx.org/LaravelCollective/html/license.svg)](https://packagist.org/packages/laravelcollective/html)

This is a fork of the original LaravelCollective HTML package.
It aims to serve as a drop-in replacement after the original package is no longer updated.

The only change this package brings is that it only support PHP 8.1+ and Laravel 10 & 11.

The rest of the functionality is identical with the original one.

## Installation

In your existing application's `composer.json` replace the reference of laravecollective/html to konekt/html:

**Before:**

```json
{
  "require": {
    "laravelcollective/html": "^6.4"
  }
}
```

**After:**

```json
{
  "require": {
    "konekt/html": "^6.5"
  }
}
```

After the change, run:

```bash
composer update laravelcollective/html konekt/html
``` 

See the [Documentation](https://laravelcollective.com/docs) for usage details.
