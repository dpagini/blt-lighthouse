BLT Lighthouse integration
====

This is an [Acquia BLT](https://github.com/acquia/blt) plugin providing [Lighthouse](https://developers.google.com/web/tools/lighthouse/) integration.

## Installation and usage

### Pre-requisites
* `lighthouse` npm module installed
* Drupal project using BLT > 10

In your project, require the plugin with Composer:

`composer require dpagini/blt-lighthouse`

Initialize the Lighthouse integration by calling `recipes:ci:lighthouse:init`, which is provided by this plugin:

`$ blt recipes:ci:lighthouse:init`
