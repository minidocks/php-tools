PHP Tools image ([minidocks/php-tools](https://hub.docker.com/r/minidocks/php-tools))
=====================================================================================

Tools for PHP. The list of available tools and the installer are actually
managed in the [jakzal/toolbox](https://github.com/jakzal/toolbox) repository.

Installed tools
---------------

| Name                               | Description                                                                                                                              | PHP 7.4 | PHP 8.0 | PHP 8.1 |
|:-----------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------|:--------|:--------|:--------|
| analyze                            | [Visualizes metrics and source code](https://github.com/Qafoo/QualityAnalyzer)                                                           | ✓       | –       | –       |
| behat                              | [Helps to test business expectations](http://behat.org/)                                                                                 | ✓       | ✓       | ✓       |
| box                                | [Fast, zero config application bundler with PHARs](https://github.com/humbug/box)                                                        | ✓       | ✓       | ✓       |
| churn                              | [Discovers good candidates for refactoring](https://github.com/bmitch/churn-php)                                                         | ✓       | ✓       | ✓       |
| codeception                        | [Codeception is a BDD-styled PHP testing framework](https://codeception.com/)                                                            | ✓       | ✓       | ✓       |
| composer                           | [Dependency Manager for PHP](https://getcomposer.org/)                                                                                   | ✓       | ✓       | ✓       |
| composer-bin-plugin                | [Composer plugin to install bin vendors in isolated locations](https://github.com/bamarni/composer-bin-plugin)                           | ✓       | ✓       | ✓       |
| composer-normalize                 | [Composer plugin to normalize composer.json files](https://github.com/ergebnis/composer-normalize)                                       | ✓       | ✓       | ✓       |
| composer-require-checker           | [Verify that no unknown symbols are used in the sources of a package.](https://github.com/maglnet/ComposerRequireChecker)                | –       | ✓       | ✓       |
| composer-require-checker-3         | [Verify that no unknown symbols are used in the sources of a package.](https://github.com/maglnet/ComposerRequireChecker)                | ✓       | ✓       | ✓       |
| composer-unused                    | [Show unused packages by scanning your code](https://github.com/icanhazstring/composer-unused)                                           | ✓       | ✓       | ✓       |
| dephpend                           | [Detect flaws in your architecture](https://dephpend.com/)                                                                               | ✓       | ✓       | ✓       |
| deprecation-detector               | [Finds usages of deprecated code](https://github.com/sensiolabs-de/deprecation-detector)                                                 | ✓       | ✓       | ✓       |
| deptrac                            | [Enforces dependency rules between software layers](https://github.com/qossmic/deptrac)                                                  | ✓       | ✓       | ✓       |
| diffFilter                         | [Applies QA tools to run on a single pull request](https://github.com/exussum12/coverageChecker)                                         | ✓       | ✓       | ✓       |
| ecs                                | [Sets up and runs coding standard checks](https://github.com/Symplify/EasyCodingStandard)                                                | ✓       | ✓       | ✓       |
| infection                          | [AST based PHP Mutation Testing Framework](https://infection.github.io/)                                                                 | –       | ✓       | ✓       |
| larastan                           | [PHPStan extension for Laravel](https://github.com/nunomaduro/larastan)                                                                  | ✓       | ✓       | ✓       |
| local-php-security-checker         | [Checks composer dependencies for known security vulnerabilities](https://github.com/fabpot/local-php-security-checker)                  | ✓       | ✓       | ✓       |
| parallel-lint                      | [Checks PHP file syntax](https://github.com/php-parallel-lint/PHP-Parallel-Lint)                                                         | ✓       | ✓       | ✓       |
| paratest                           | [Parallel testing for PHPUnit](https://github.com/paratestphp/paratest)                                                                  | ✓       | ✓       | ✓       |
| pdepend                            | [Static Analysis Tool](https://pdepend.org/)                                                                                             | ✓       | ✓       | ✓       |
| phan                               | [Static Analysis Tool](https://github.com/phan/phan)                                                                                     | ✓       | ✓       | ✓       |
| phive                              | [PHAR Installation and Verification Environment](https://phar.io/)                                                                       | ✓       | ✓       | ✓       |
| php-coupling-detector              | [Detects code coupling issues](https://akeneo.github.io/php-coupling-detector/)                                                          | ✓       | ✓       | ✓       |
| php-cs-fixer                       | [PHP Coding Standards Fixer](http://cs.symfony.com/)                                                                                     | ✓       | ✓       | ✓       |
| php-fuzzer                         | [A fuzzer for PHP, which can be used to find bugs in libraries by feeding them ‘random’ inputs](https://github.com/nikic/PHP-Fuzzer)     | ✓       | ✓       | ✓       |
| php-semver-checker                 | [Suggests a next version according to semantic versioning](https://github.com/tomzx/php-semver-checker)                                  | ✓       | ✓       | ✓       |
| phpa                               | [Checks for weak assumptions](https://github.com/rskuipers/php-assumptions)                                                              | ✓       | ✓       | ✓       |
| phpat                              | [Easy to use architecture testing tool](https://github.com/carlosas/phpat)                                                               | ✓       | ✓       | ✓       |
| phpbench                           | [PHP Benchmarking framework](https://github.com/phpbench/phpbench)                                                                       | ✓       | ✓       | ✓       |
| phpca                              | [Finds usage of non-built-in extensions](https://github.com/wapmorgan/PhpCodeAnalyzer)                                                   | ✓       | ✓       | ✓       |
| phpcb                              | [PHP Code Browser](https://github.com/mayflower/PHP_CodeBrowser)                                                                         | ✓       | ✓       | ✓       |
| phpcbf                             | [Automatically corrects coding standard violations](https://github.com/squizlabs/PHP_CodeSniffer)                                        | ✓       | ✓       | ✓       |
| phpcodesniffer-composer-install    | [Easy installation of PHP_CodeSniffer coding standards (rulesets).](https://github.com/Dealerdirect/phpcodesniffer-composer-installer)   | ✓       | ✓       | ✓       |
| phpcov                             | [a command-line frontend for the PHP_CodeCoverage library](https://github.com/sebastianbergmann/phpcov)                                  | ✓       | ✓       | ✓       |
| phpcpd                             | [Copy/Paste Detector](https://github.com/sebastianbergmann/phpcpd)                                                                       | ✓       | ✓       | ✓       |
| phpcs                              | [Detects coding standard violations](https://github.com/squizlabs/PHP_CodeSniffer)                                                       | ✓       | ✓       | ✓       |
| phpcs-security-audit               | [Finds vulnerabilities and weaknesses related to security in PHP code](https://github.com/FloeDesignTechnologies/phpcs-security-audit)   | ✓       | ✓       | ✓       |
| phpda                              | [Generates dependency graphs](https://mamuz.github.io/PhpDependencyAnalysis/)                                                            | ✓       | ✓       | –       |
| phpdd                              | [Finds usage of deprecated features](http://wapmorgan.github.io/PhpDeprecationDetector)                                                  | ✓       | ✓       | ✓       |
| phpDocumentor                      | [Documentation generator](https://www.phpdoc.org/)                                                                                       | ✓       | ✓       | ✓       |
| phpinsights                        | [Analyses code quality, style, architecture and complexity](https://phpinsights.com/)                                                    | ✓       | ✓       | ✓       |
| phplint                            | [Lints php files in parallel](https://github.com/overtrue/phplint)                                                                       | ✓       | ✓       | ✓       |
| phploc                             | [A tool for quickly measuring the size of a PHP project](https://github.com/sebastianbergmann/phploc)                                    | ✓       | ✓       | ✓       |
| phpmd                              | [A tool for finding problems in PHP code](https://phpmd.org/)                                                                            | ✓       | ✓       | ✓       |
| phpmetrics                         | [Static Analysis Tool](http://www.phpmetrics.org/)                                                                                       | ✓       | ✓       | ✓       |
| phpmnd                             | [Helps to detect magic numbers](https://github.com/povils/phpmnd)                                                                        | ✓       | ✓       | ✓       |
| phpspec                            | [SpecBDD Framework](http://www.phpspec.net/)                                                                                             | ✓       | ✓       | ✓       |
| phpstan                            | [Static Analysis Tool](https://github.com/phpstan/phpstan)                                                                               | ✓       | ✓       | ✓       |
| phpstan-beberlei-assert            | [PHPStan extension for beberlei/assert](https://github.com/phpstan/phpstan-beberlei-assert)                                              | ✓       | ✓       | ✓       |
| phpstan-deprecation-rules          | [PHPStan rules for detecting deprecated code](https://github.com/phpstan/phpstan-deprecation-rules)                                      | ✓       | ✓       | ✓       |
| phpstan-doctrine                   | [Doctrine extensions for PHPStan](https://github.com/phpstan/phpstan-doctrine)                                                           | ✓       | ✓       | ✓       |
| phpstan-ergebnis-rules             | [Additional rules for PHPstan](https://github.com/ergebnis/phpstan-rules)                                                                | ✓       | ✓       | ✓       |
| phpstan-exception-rules            | [PHPStan rules for checked and unchecked exceptions](https://github.com/pepakriz/phpstan-exception-rules)                                | ✓       | ✓       | ✓       |
| phpstan-larastan                   | [Separate installation of phpstan for larastan](https://github.com/phpstan/phpstan)                                                      | ✓       | ✓       | ✓       |
| phpstan-phpunit                    | [PHPUnit extensions and rules for PHPStan](https://github.com/phpstan/phpstan-phpunit)                                                   | ✓       | ✓       | ✓       |
| phpstan-strict-rules               | [Extra strict and opinionated rules for PHPStan](https://github.com/phpstan/phpstan-strict-rules)                                        | ✓       | ✓       | ✓       |
| phpstan-symfony                    | [Symfony extension for PHPStan](https://github.com/phpstan/phpstan-symfony)                                                              | ✓       | ✓       | ✓       |
| phpstan-webmozart-assert           | [PHPStan extension for webmozart/assert](https://github.com/phpstan/phpstan-webmozart-assert)                                            | ✓       | ✓       | ✓       |
| phpunit                            | [The PHP testing framework](https://phpunit.de/)                                                                                         | ✓       | ✓       | ✓       |
| phpunit-5                          | [The PHP testing framework (5.x version)](https://phpunit.de/)                                                                           | ✓       | –       | –       |
| phpunit-7                          | [The PHP testing framework (7.x version)](https://phpunit.de/)                                                                           | ✓       | –       | –       |
| phpunit-8                          | [The PHP testing framework (8.x version)](https://phpunit.de/)                                                                           | ✓       | ✓       | ✓       |
| psalm                              | [Finds errors in PHP applications](https://psalm.dev/)                                                                                   | ✓       | ✓       | ✓       |
| psalm-plugin-doctrine              | [Stubs to let Psalm understand Doctrine better](https://github.com/weirdan/doctrine-psalm-plugin)                                        | ✓       | ✓       | ✓       |
| psalm-plugin-phpunit               | [Psalm plugin for PHPUnit](https://github.com/psalm/psalm-plugin-phpunit)                                                                | ✓       | ✓       | ✓       |
| psalm-plugin-symfony               | [Psalm Plugin for Symfony](https://github.com/psalm/psalm-plugin-symfony)                                                                | ✓       | ✓       | ✓       |
| psecio-parse                       | [Scans code for potential security-related issues](https://github.com/psecio/parse)                                                      | ✓       | ✓       | ✓       |
| rector                             | [Tool for instant code upgrades and refactoring](https://github.com/rectorphp/rector)                                                    | ✓       | ✓       | ✓       |
| roave-backward-compatibility-check | [Tool to compare two revisions of a class API to check for BC breaks](https://github.com/Roave/BackwardCompatibilityCheck)               | ✓       | ✓       | ✓       |
| simple-phpunit                     | [Provides utilities to report legacy tests and usage of deprecated code](https://symfony.com/doc/current/components/phpunit_bridge.html) | ✓       | ✓       | ✓       |
| twig-lint                          | [Standalone cli twig 1.X linter](https://github.com/asm89/twig-lint)                                                                     | ✓       | ✓       | ✓       |
| twig-linter                        | [Standalone cli twig 3.X linter](https://github.com/sserbin/twig-linter)                                                                 | ✓       | ✓       | ✓       |
| twigcs                             | [The missing checkstyle for twig!](https://github.com/friendsoftwig/twigcs)                                                              | ✓       | ✓       | ✓       |
| yaml-lint                          | [Compact command line utility for checking YAML file syntax](https://github.com/j13k/yaml-lint)                                          | ✓       | ✓       | ✓       |

Usage
-----

Run interactive REPL:

```bash
docker run --rm -it -v `pwd`:`pwd` -w `pwd` minidocks/php-tools
```

Tags
----

| Tag         | Size                                                                                                              |
|-------------|-------------------------------------------------------------------------------------------------------------------|
| latest, 8.1 | ![](https://img.shields.io/docker/image-size/minidocks/php-tools/latest?style=flat-square&logo=docker&label=size) |
| 8.1         | ![](https://img.shields.io/docker/image-size/minidocks/php-tools/8.1?style=flat-square&logo=docker&label=size)    |
| 8.0         | ![](https://img.shields.io/docker/image-size/minidocks/php-tools/8.0?style=flat-square&logo=docker&label=size)    |
| 7.4         | ![](https://img.shields.io/docker/image-size/minidocks/php-tools/7.4?style=flat-square&logo=docker&label=size)    |

Alternatives
------------

-   https://github.com/jakzal/phpqa
