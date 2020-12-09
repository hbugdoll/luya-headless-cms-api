<p align="center">
  <img src="https://raw.githubusercontent.com/luyadev/luya/master/docs/logo/luya-logo-0.2x.png" alt="LUYA Logo"/>
</p>

# LUYA HEADLESS CMS BRIDGE

[![LUYA](https://img.shields.io/badge/Powered%20by-LUYA-brightgreen.svg)](https://luya.io)

This module provides and out of the box ready API in order to consume the CMS informations from a PUBLIC, CORS-ready, Read-Only API.

## Installation

Install the extension through composer:

```sh
composer require luyadev/luya-headless-cms
```

Add the module to the config

```php
'modules' => [
    'api' => [
        'class' => 'luya\headless\cms\Module',
    ]
]
```

## Usage

*Usage description*
