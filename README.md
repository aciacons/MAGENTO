# Smaex: Module 

A template for custom [Magento 2 modules][1].

## How to install 

[Require the package][2] via Composer.

```sh
$ composer require smaex/module ^1.0
```

[Enable the module][3] via Magento’s CLI.

```sh 
$ magento module:enable Smaex_Module
```

[Update the project][4] via Magento’s CLI.

```sh 
$ magento setup:upgrade
$ magento setup:di:compile
```

## How to update

[Update the package][5] via Composer.

```sh
$ composer update smaex/module
```

[Update the project][4] via Magento’s CLI.

```sh 
$ magento setup:upgrade
$ magento setup:di:compile
```

## How to test

The module includes [PHPStan][6] for static code analysis, and covers all relevant classes with [unit tests][7].

[Install dependencies][8] via Composer.

```sh
$ composer install
```
[Run the tests][9] via Composer.

```sh
$ composer test
```

## We’re hiring!

We’re currently looking for passionate ~~masochists~~ **PHP & Magento developers** to join our e-commerce team **in Munich**. Sounds interesting? Just drop me a line via [j.scherbl@techdivision.com][10].

 [1]: https://devdocs.magento.com/guides/v2.3/architecture/archi_perspectives/components/modules/mod_intro.html
 [2]: https://getcomposer.org/doc/03-cli.md#require
 [3]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-enable.html#instgde-cli-subcommands-enable-disable 
 [4]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-db-upgr.html
 [5]: https://getcomposer.org/doc/03-cli.md#update-u
 [6]: https://github.com/phpstan/phpstan
 [7]: https://phpunit.de
 [8]: https://getcomposer.org/doc/03-cli.md#install-i
 [9]: https://getcomposer.org/doc/articles/scripts.md#writing-custom-commands
[10]: mailto:j.scherbl@techdivision.com
