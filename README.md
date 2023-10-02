# Grupo Peris Icons

[![Tests](https://github.com/grupoperis/icons/actions/workflows/tests.yml/badge.svg)](https://github.com/grupoperis/icons/actions/workflows/tests.yml)
[![Coding Standards](https://github.com/grupoperis/icons/actions/workflows/coding-standards.yml/badge.svg)](https://github.com/grupoperis/icons/actions/workflows/coding-standards.yml)

## Requirements

- PHP 8.2 or higher
- Laravel 10.0 or higher

## Installation

```bash
composer require grupoperis/icons
```

## Blade Icons

Grupo Peris Icons uses Blade Icons under the hood. Please refer to [the Blade Icons readme](https://github.com/blade-ui-kit/blade-icons) for additional functionality. We also recommend to [enable icon caching](https://github.com/blade-ui-kit/blade-icons#caching) with this library.

## Configuration

Grupo Peris Icons also offers the ability to use features from Blade Icons like default classes, default attributes, etc. If you'd like to configure these, publish the `icons.php` config file:

```bash
php artisan vendor:publish --tag=icons-config
```

## Usage

Icons can be used as self-closing Blade components which will be compiled to SVG icons:

```blade
<x-icon-home/>
```

You can also pass classes to your icon components:

```blade
<x-icon-home class="w-6 h-6 text-gray-500"/>
```

And even use inline styles:

```blade
<x-icon-home style="color: #555"/>
```

The solid icons can be referenced like this:

```blade
<x-icon-home/>
```

## License

This project is under Copyright (c) 2023 PERISHOLD S.L.U.

Any unauthorized copying, distribution, reproduction or modification of this content by any person or entity is strictly prohibited.
