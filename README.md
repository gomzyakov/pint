# Code-style configuration for Laravel Pint

This package allows sharing identical [Laravel Pint](https://laravel.com/docs/12.x/pint) formatting rules across all of your projects without copy-and-pasting configuration files.

## Quickstart

### Step 1 of 2

Install [Laravel Pint](https://github.com/laravel/pint) & this package via Composer:

```sh
composer require --dev laravel/pint gomzyakov/pint
```

### Step 2 of 2

**And that's it!** You can now find code style violations with following command:

```sh
./vendor/bin/pint --config vendor/gomzyakov/pint/pint.json
```

## Support

If you find any package errors, please, [make an issue](https://github.com/gomzyakov/pint/issues) in current repository.

## License

This is open-sourced software licensed under the [MIT License](https://github.com/gomzyakov/pint/blob/main/LICENSE).
