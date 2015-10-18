# Contributing
QA-Tools / PHPUnit Extension is an open source, community-driven project. If you'd like to contribute, feel free to do this, but remember to follow these few simple rules:

## Asking Questions
Feel free to ask any questions and share your experiences in the [Chat Room](https://gitter.im/qa-tools/qa-tools) and help to improve the documentation.

## Submitting an issues
- A reproducible example is required for every bug report, otherwise it will most probably be __closed without warning__.
- If you are going to make a big, substantial change, let's discuss it first.

## Working with Pull Requests
1. Create your feature addition or a bug fix branch based on __`master`__ branch in your repository's fork.
2. Make necessary changes, but __don't mix__ code reformatting with code changes on topic.
3. Check your code using "Coding Standard" (see below).
4. Commit your code.
5. Squash your commits by topic to preserve a clean and readable log.
6. Create Pull Request.

## Checking coding standard violations

This library uses [Coding Standard](https://github.com/aik099/CodingStandard) to ensure consistent formatting across the code base. Make sure you haven't introduced any Coding Standard violations by running following command in the root folder of the library:

```bash
$> phpcs --standard="vendor/aik099/coding-standard/CodingStandard" src
```

or by making your IDE ([instructions for PhpStorm](http://www.jetbrains.com/phpstorm/webhelp/using-php-code-sniffer-tool.html)) to check them automatically.

## Contributor Code of Conduct

Please note that this project is released with a [Contributor Code of
Conduct](http://contributor-covenant.org/). By participating in this project
you agree to abide by its terms. See [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) file.
