# Psalm plugin for ReactPHP Promise package
A [Psalm](https://github.com/vimeo/psalm) plugin for [friends-of-reactphp/mysql](https://github.com/friends-of-reactphp/mysql).
## Overview
This package so far only adds stubs for template parameters recognition in `ConnectionInterface`.

## Prerequisites
You should have [Psalm](https://github.com/vimeo/psalm) and [ReactPHP Promise psalm plugin](https://github.com/Bocmah/psalm-reactphp-promise-plugin) installed.

## Installation
Install plugin as a dev dependency via composer:

`composer require --dev bocmah/psalm-reactphp-mysql-plugin`

Then enable the plugin:

`./vendor/bin/psalm-plugin enable bocmah/psalm-reactphp-mysql-plugin`
