# Awesome PHP AST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome tools, articles and books about abstract syntax tree in PHP world. From parsing PHP, through traversing templates and configs through automated upgrades.

<br>

Do you miss a project, tool or article, that you consider useful to the broader AST PHP community? Send a pull-request, so we can check it.

<br>

## Native PHP

### Parsing

* https://github.com/nikic/PHP-Parser - A PHP parser written in PHP
* https://github.com/microsoft/tolerant-php-parser - PHP parser designed for IDE usage scenarios
* https://github.com/phplrt - Tools for writing parsers for PHP

### Analyzing

* https://github.com/phpstan/phpstan - PHP Static Analysis Tool based on php-parser
* https://leanpub.com/recipes-for-decoupling - Book about PHPStan & AST-based analysis

### Modifying
 
* https://github.com/rectorphp/rector - Instant Upgrades and Automated Refactoring tool based on php-parser and PHPStan
* https://github.com/ajthinking/archetype - Edit PHP files programmatically with Fluent API and Abstract Syntax Tree QueryBuilder
* https://leanpub.com/rector-the-power-of-automated-refactoring - Book about Rector and AST-based manipulation

<br>

## Templates

### TWIG

* https://github.com/revealphp/reveal-twig - TWIG static analysis, that compiles TWIG template to PHP and run PHPStan on the result
* https://github.com/matthiasnoback/phpstan-twig-analysis - Twig static analysis based on Twig Node traversing

### Latte

* https://github.com/revealphp/reveal-latte - Latte static analysis, that compiles Latte template to PHP and runs PHPStan on the result
* https://github.com/TomasVotruba/barista - "A PHPStan for Latte", traversing Latte files with native Latte 3 AST

### Blade

* https://github.com/canvural/phpstan-blade-rule - Blade static analysis, that compiles Blade template to PHP and run PHPStan on the result

### HTML

* https://github.com/TomasVotruba/html-parser - Simple HTML AST traverser based on Dom

<br>

## Databases

* https://github.com/staabm/phpstan-dba - PHPStan static analysis and type inference for the database access layer
* https://github.com/phpmyadmin/sql-parser - A validating SQL lexer and parser with a focus on MySQL dialect

<br>

### License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Tomas Votruba](https://www.tomasvotruba.com) has waived all copyright and related or neighboring rights to this work.
