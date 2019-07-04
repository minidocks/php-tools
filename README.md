PHP Tools image (minidocks/php-tools)
=====================================

PHP is a popular general-purpose scripting language that is especially suited to web development.
Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world.

Installed tools
---------------

* composer - [Dependency Manager for PHP](https://getcomposer.org/)
* composer-bin-plugin - [Composer plugin to install bin vendors in isolated locations](https://github.com/bamarni/composer-bin-plugin)
* box - [An application for building and managing Phars](https://box-project.github.io/box2/)
* analyze - [Visualizes metrics and source code](https://github.com/Qafoo/QualityAnalyzer)
* behat - [Helps to test business expectations](http://behat.org/)
* churn - [Discovers good candidates for refactoring](https://github.com/bmitch/churn-php)
* composer-normalize - [Composer plugin to normalize composer.json files](https://github.com/localheinz/composer-normalize)
* dephpend - [Detect flaws in your architecture](https://dephpend.com/)
* deprecation-detector - [Finds usages of deprecated code](https://github.com/sensiolabs-de/deprecation-detector)
* deptrac - [Enforces dependency rules between software layers](https://github.com/sensiolabs-de/deptrac)
* design-pattern - [Detects design patterns](https://github.com/Halleck45/DesignPatternDetector)
* diffFilter - [Applies QA tools to run on a single pull request](https://github.com/exussum12/coverageChecker)
* ecs - [Sets up and runs coding standard checks](https://github.com/Symplify/EasyCodingStandard)
* infection - [AST based PHP Mutation Testing Framework](https://infection.github.io/)
* parallel-lint - [Checks PHP file syntax](https://github.com/JakubOnderka/PHP-Parallel-Lint)
* paratest - [Parallel testing for PHPUnit](https://github.com/paratestphp/paratest)
* pdepend - [Static Analysis Tool](https://pdepend.org/)
* phan - [Static Analysis Tool](https://github.com/phan/phan)
* php-coupling-detector - [Detects code coupling issues](https://akeneo.github.io/php-coupling-detector/)
* php-cs-fixer - [PHP Coding Standards Fixer](http://cs.sensiolabs.org/)
* php-formatter - [Custom coding standards fixer](https://github.com/mmoreram/php-formatter)
* php-semver-checker - [Suggests a next version according to semantic versioning](https://github.com/tomzx/php-semver-checker)
* phpDocumentor - [Documentation generator](https://www.phpdoc.org/)
* phpbench - [PHP Benchmarking framework](https://github.com/phpbench/phpbench)
* phpa - [Checks for weak assumptions](https://github.com/rskuipers/php-assumptions)
* phpca - [Finds usage of non-built-in extensions](https://github.com/wapmorgan/PhpCodeAnalyzer)
* phpcb - [PHP Code Browser](https://github.com/mayflower/PHP_CodeBrowser)
* phpcbf - [Automatically corrects coding standard violations](https://github.com/squizlabs/PHP_CodeSniffer)
* phpcf - [Finds usage of deprecated features](http://wapmorgan.github.io/PhpCodeFixer/)
* phpcov - [a command-line frontend for the PHP_CodeCoverage library](https://github.com/sebastianbergmann/phpcov)
* phpcpd - [Copy/Paste Detector](https://github.com/sebastianbergmann/phpcpd)
* phpcs - [Detects coding standard violations](https://github.com/squizlabs/PHP_CodeSniffer)
* phpda - [Generates dependency graphs](https://mamuz.github.io/PhpDependencyAnalysis/)
* phpdoc-to-typehint - [Automatically adds type hints and return types based on PHPDocs](https://github.com/dunglas/phpdoc-to-typehint)
* phplint - [Lints php files in parallel](https://github.com/overtrue/phplint)
* phploc - [A tool for quickly measuring the size of a PHP project](https://github.com/sebastianbergmann/phploc)
* phpmd - [A tool for finding problems in PHP code](https://phpmd.org/)
* phpmetrics - [Static Analysis Tool](http://www.phpmetrics.org/)
* phpmnd - [Helps to detect magic numbers](https://github.com/povils/phpmnd)
* phpspec - [SpecBDD Framework](http://www.phpspec.net/)
* phpstan - [Static Analysis Tool](https://github.com/phpstan/phpstan)
* phpstan-deprecation-rules - [PHPStan rules for detecting deprecated code](https://github.com/phpstan/phpstan-deprecation-rules)
* phpstan-localheinz-rules - [Additional rules for PHPstan](https://github.com/localheinz/phpstan-rules)
* phpstan-strict-rules - [Extra strict and opinionated rules for PHPStan](https://github.com/phpstan/phpstan-strict-rules)
* phpstan-doctrine - [Doctrine extensions for PHPStan](https://github.com/phpstan/phpstan-doctrine)
* phpstan-phpunit - [PHPUnit extensions and rules for PHPStan](https://github.com/phpstan/phpstan-phpunit)
* phpstan-symfony - [Symfony extension for PHPStan](https://github.com/phpstan/phpstan-symfony)
* phpstan-beberlei-assert - [PHPStan extension for beberlei/assert](https://github.com/phpstan/phpstan-beberlei-assert)
* phpstan-webmozart-assert - [PHPStan extension for webmozart/assert](https://github.com/phpstan/phpstan-webmozart-assert)
* phpstan-exception-rules - [PHPStan rules for checked and unchecked exceptions](https://github.com/pepakriz/phpstan-exception-rules)
* phpunit - [The PHP testing framework](https://phpunit.de/)
* phpunit-7 - [The PHP testing framework (7.x version)](https://phpunit.de/)
* psalm - [Finds errors in PHP applications](https://getpsalm.org/)
* psecio-parse - [Scans code for potential security-related issues](https://github.com/psecio/parse)
* rector - [Tool for instant code upgrades and refactoring](https://github.com/rectorphp/rector)
* roave-backward-compatibility-check - [Tool to compare two revisions of a class API to check for BC breaks](https://github.com/Roave/BackwardCompatibilityCheck)
* security-checker - [Checks composer dependencies for known security vulnerabilities](https://github.com/sensiolabs/security-checker)
* simple-phpunit - [Provides utilities to report legacy tests and usage of deprecated code](https://symfony.com/doc/current/components/phpunit_bridge.html)
* testability - [Analyses and reports testability issues of a php codebase](https://github.com/edsonmedina/php_testability)


Usage
-----

Run interactive REPL:
```bash
docker run --rm -it -v `pwd`:`pwd` -w `pwd` minidocks/php-tools
```

Tags
----

 Tag         | Size
 ---         | ----
 latest, 7.3 | [![](https://images.microbadger.com/badges/image/minidocks/php-tools.svg)](https://microbadger.com/images/minidocks/php-tools)
 7.3         | [![](https://images.microbadger.com/badges/image/minidocks/php-tools:7.3.svg)](https://microbadger.com/images/minidocks/php-tools:7.3)
 7.2         | [![](https://images.microbadger.com/badges/image/minidocks/php-tools:7.2.svg)](https://microbadger.com/images/minidocks/php-tools:7.2)

Alternatives
------------

- https://github.com/jakzal/phpqa
