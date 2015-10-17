# QA-Tools / PHPUnit Extension

[![Latest Stable Version](https://poser.pugx.org/qa-tools/phpunit-extension/v/stable)](https://packagist.org/packages/qa-tools/phpunit-extension)
[![Total Downloads](https://poser.pugx.org/qa-tools/phpunit-extension/downloads)](https://packagist.org/packages/qa-tools/phpunit-extension)
[![License](https://poser.pugx.org/qa-tools/phpunit-extension/license)](https://packagist.org/packages/qa-tools/phpunit-extension)

Extension to use [QA-Tools library](http://www.qa-tools.io) with [PHPUnit](https://phpunit.de/).

## Asking Questions

Feel free to ask any questions and share your experiences in the [Chat Room](https://gitter.im/qa-tools/qa-tools) and help to improve the documentation.

## Usage

1. when creating unit test class sub-class the base test case class (see [Installation](#installation))
2. use `$this->pageFactory` to get page factory instance associated with current Mink session

## Installation

1. run this command to add Composer dependencies: `php composer.phar require qa-tools/phpunit-extension --dev`
2. create base class for all unit tests by sub-classing `\QATools\PHPUnitExtension\AbstractQAToolsTestCase`
3. take a look at provided `\QATools\PHPUnitExtension\AbstractQAToolsTestCase::getBrowserAliases` method (change in sub-class if needed) to find out what default browser is used

## Requirements

* [Composer](https://getcomposer.org/download/)

## License

QA-Tools / PHPUnit Extension is released under the BSD-3-Clause License. See the bundled [LICENSE](LICENSE) file for details.
