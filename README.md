# Static analysis tools for PHP 

A curated list of static analysis tools for PHP.

## Contributing
See [CONTRIBUTING](https://github.com/exakat/php-static-analysis-tools/blob/master/CONTRIBUTING.md).

## Table of Contents

* [Bugs finders](#bugs-finders)
* [Coding standards](#coding-standards)
* [DIY](#dyi)
* [Fixers](#fixers)
* [Metrics](#metrics)
* [Saas](#saas)
* [Misc](#misc)


### Bugs finders
Tools to reports issues in code that are or lead to bugs. 

* [Eir](https://github.com/Lixody/Eir) - A static vulnerability analysis tool written in C#.
* [Exakat](http://www.exakat.io/) - Smart static analysis.
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [php-analysis](https://github.com/cwi-swat/php-analysis) - PHP Analysis in Rascal (PHP AiR).
* [PHP Assumption](https://github.com/rskuipers/php-assumptions.git) - Finds <a href="http://rskuipers.com/entry/from-assumptions-to-assertions">weak assumptions</a> in the code, suggest to turn them into stronger validations.
* [PhpCodeAnalyzer](https://github.com/wapmorgan/PhpCodeAnalyzer.git) - Finds usage of non-built-in extensions.
* [PHPCodeFixer](https://github.com/wapmorgan/PhpCodeFixer) -  Finds usage of deprecated functions, variables and ini directives.
* [php7mar](https://github.com/Alexia/php7mar) - PHP 7 Migration Assistant Report.
* [phpcallgraph](http://phpcallgraph.sourceforge.net/) - Generate static call graphs. Such a graph visualizes the call dependencies among methods or functions of an application..
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - Spots copy/pasted code, and help enforcing DRY rule.
* [Phan](https://github.com/etsy/phan) - The static analyzer by Rasmus, PHP Creator.
* [PHP Inspection](https://plugins.jetbrains.com/plugin/7622?pr=idea) - Static analysis plugin for PHPStorm. 
* [PHP lint](http://php.net/manual/en/features.commandline.options.php) - PHP itself, able to detect syntax error from command line. 
* [PHPlint](http://www.icosaedro.it/phplint/) - A validator and documentator for PHP 5 programs.
* [PHP Mess Detector](http://phpmd.org/) - Look for several potential problems within source code.
* [PHP Reaper](https://github.com/emanuil/php-reaper.git) - Scan ADOdb code for SQL Injections.
* [PHP SA](https://github.com/ovr/phpsa) - A development tool aimed at bringing complex analysis for PHP applications and libraries.
* [PHP Stan](https://github.com/phpstan/phpstan) - Focuses on finding errors in code without actually running it.
* [PHP Unlocker](http://emanuilslavov.com/php-unlocker/) - Detect potential, unintended DB table locks for PHP applications using ADOdb. Uses static analysis methods.
* [PHP vuln hunter](https://github.com/OneSourceCat/phpvulhunter) - Scan PHP vulnerabilities automatically using static analysis methods.
* [RIPS](http://rips-scanner.sourceforge.net/) - Source code static analyser for vulnerabilities. Newer version is mixed model, free and paid.
* [psecio:parse](https://github.com/psecio/parse.git) - Parse : A PHP Security Scanner
* [SonarQube](http://www.sonarqube.org/) - An open platform to manage code quality. It covers PHP code.
* [Side Channel Analyzer](https://github.com/olivo/side-channel-analyzer) - Search for <a href="https://en.wikipedia.org/wiki/Side-channel_attack">side-channel vulnerable code</a>.
* [TaintPHP](https://github.com/olivo/TaintPHP.git) - Static Taint Analyzer. 
* [Tuli](https://github.com/ircmaxell/Tuli) - A static analysis engine.
* [17eyes](https://github.com/17eyes/17eyes) - PHP static analyzer written in Haskell.

### Coding standards 

Tools to review the way PHP code was written and more. 

* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - PHPCS checks the code for a large range of coding standard.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.

### DIY

Libraries that may be the base for a home-made static analyzer

* [Deptrac](https://github.com/sensiolabs-de/deptrac.git) - A static code analysis tool to enforce rules for dependencies between software layers.
* [PHP-cfg](https://github.com/ircmaxell/php-cfg) - A Control Flow Graph implementation in PHP. Written by IrcMaxwell. 
* [PHP coupling detector](https://github.com/akeneo/php-coupling-detector) - Check that code has no unwanted coupled classes.
* [PHP Parser](https://github.com/nikic/PHP-Parser) - Written in PHP by Nikita Popov and based on actual grammar of PHP.
* [PHP Token Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) - Library emulating the PHP internal reflection using just the tokenized source code. 
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - A full-scale PHP 5.3.2+ sandbox class that utilizes PHPParser to prevent sandboxed code from running unsafe code.
* [Reflection](https://github.com/phpDocumentor/Reflection.git) - Reflection library to do Static Analysis for PHP Projects.


### Fixers

Tools to automatically fix the code they are provided with. 

* [php-refactoring-browser](https://github.com/QafooLabs/php-refactoring-browser) - CLI refactoring tool. 
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - Analyzes and tries to fix coding standards issues (PSR-1 and PSR-2 compatible).
* [phpdoc to typehint](https://github.com/dunglas/phpdoc-to-typehint) - Turn phpdocs comments to actual Typehint (arguments and return)
* [Transphpile](https://github.com/jaytaph/Transphpile) - Write PHP 7, run PHP 5.6, with feature backport. 

### Metrics

Tools to measures the code : complexity, line of codes, etc. 

* [Dissect](https://github.com/jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - Utility to measures PHP application size and count various structures.
* [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - Calculates all sorts of metrics, and display them in a gorgeous interface.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - Utility to check semantic version of a given code.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - Static code analysis to provide and verify a dependency graph against a defined architecture.
* [PHP semver checker](https://github.com/tomzx/php-semver-checker) - Compares two source sets and determines the appropriate semantic versioning to apply.
* [Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer.git) - Visualize metrics and source code. 

### Saas

Online services to PHP code, provide dashboards. They may use the previous tools or offer their own.

* [Bliss](https://blissai.com/index.html) - Automatically reviews code in real-time and shows how much it's worth in lines of code.
* [Checkmarx](http://lp.checkmarx.com/php-code-analysis/) - Get a full PHP  static security code analysis and prevent security vulnerabilities.
* [Codacy](https://www.codacy.com/) - Codacy: Automated Code Review.
* [Code Climate](https://codeclimate.com) - Hosted static analysis for Ruby, PHP and JavaScript source code.
* [Insight](https://insight.sensiolabs.com/) - A SensioLabs tool to analyzes source code to find problems that degrade the overall quality of your projects.
* [Ripstech](https://www.ripstech.com/) - The superior security software for PHP applications.
* [Scrutinizer](https://scrutinizer-ci.com/) - Improve code quality and find bugs before they hit production with our continuous inspection platform.

## Misc

* [HHVM](http://hhvm.com/) - Hack Language from Facebook. Add a SCA until version 3.3.8, newer version doesn't have anymore.
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.

