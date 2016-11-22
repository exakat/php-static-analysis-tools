# Static analysis tools for PHP 

A curated list of static analysis tools for PHP.

## Contributing
See [CONTRIBUTING](https://github.com/exakat/php-static-analysis-tools/blob/master/CONTRIBUTING.md).

## Table of Contents

* [Bugs finders](#bugs-finders)
* [Coding standards](#coding-standards)
* [DIY](#diy)
* [Fixers](#fixers)
* [Metrics](#metrics)
* [SaaS](#saas)
* [Misc](#misc)


### Bugs finders
Tools that reports issues in the code that are or lead to bugs. 

* [Eir](https://github.com/Lixody/Eir) - Eir is a static vulnerability analysis tool for PHP applications written in C#
* [Exakat](http://www.exakat.io/) - Smart static analysis for PHP
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [php-analysis](https://github.com/cwi-swat/php-analysis) - PHP Analysis in Rascal (PHP AiR).
* [PHP Assumption](https://github.com/rskuipers/php-assumptions.git) - Finds <a href="http://rskuipers.com/entry/from-assumptions-to-assertions">weak assumptions</a> in the code, suggest to turn them into stronger validations.
* [PhpCodeAnalyzer](https://github.com/wapmorgan/PhpCodeAnalyzer.git) - finds usage of non-built-in extensions in your php code.
* [PHPCodeFixer](https://github.com/wapmorgan/PhpCodeFixer) -  finds usage of deprecated functions, variables and ini directives in your php code.
* [php7mar](https://github.com/Alexia/php7mar) - PHP 7 Migration Assistant Report.
* [phpcallgraph](http://phpcallgraph.sourceforge.net/) - PHP 7 Migration Assistant Report.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - phpcpd spots copy/pasted code, and help enforcing DRY rule.
* [Phan](https://github.com/etsy/phan) - The static analyzer by Rasmus. 
* [PHP Inspection](https://plugins.jetbrains.com/plugin/7622?pr=idea) - Static analysis for phpstorm. 
* [PHP lint](http://php.net/manual/en/features.commandline.options.php) - PHP itself, able to detect syntax error from command line. 
* [PHPlint](http://www.icosaedro.it/phplint/) - PHPLint is a validator and documentator for PHP 5 programs
* [PHP Mess Detector](http://phpmd.org/) - PHPMD takes a given PHP source code base and look for several potential problems within that source.
* [PHP Reaper](https://github.com/emanuil/php-reaper.git) - PHP tool to scan ADOdb code for SQL Injections
* [PHP SA](https://github.com/ovr/phpsa) - PHPSA is a development tool aimed at bringing complex analysis for PHP applications and libraries.
* [PHP Stan](https://github.com/phpstan/phpstan) - "PHPStan focuses on finding errors in your code without actually running it. "
* [PHP Unlocker](http://emanuilslavov.com/php-unlocker/) - "PHP-Unlocker is a static analysis tool that detects potential, unintended DB table locks for PHP applications using ADOdb."
* [PHP vuln hunter](https://github.com/OneSourceCat/phpvulhunter) - A tool that can scan php vulnerabilities automatically using static analysis methods
* [RIPS](http://rips-scanner.sourceforge.net/) - A static source code analyser for vulnerabilities in PHP scripts
* [psecio:parse](https://github.com/psecio/parse.git) - Parse : A PHP Security Scanner
* [SonarQube](http://www.sonarqube.org/) - An open platform to manage code quality. It covers PHP code.
* [Side Channel Analyzer](https://github.com/olivo/side-channel-analyzer) - Search for <a href="https://en.wikipedia.org/wiki/Side-channel_attack">side-channel vulnerable code</a>.
* [TaintPHP](https://github.com/olivo/TaintPHP.git) - Static Taint Analysis for PHP web applications. 
* [Tuli](https://github.com/ircmaxell/Tuli) - A static analysis engine
* [17eyes](https://github.com/17eyes/17eyes) - "PHP static analyzer written in Haskell"

### Coding standards 

Tools that review the way PHP code was written and more. 

* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - PHPCS checks the code for a large range of coding standard.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.

### DIY

Libraries that may be the base for a home-made static analyzer

* [Deptrac](https://github.com/sensiolabs-de/deptrac.git) - Deptrac is a static code analysis tool that helps to enforce rules for dependencies between software layers.
* [PHP-cfg](https://github.com/ircmaxell/php-cfg) - A Control Flow Graph implementation in PHP. Written by IrcMaxwell. 
* [PHP coupling detector](https://github.com/akeneo/php-coupling-detector) - Check that your code has no unwanted coupled classes
* [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP. Written by Nikita Popov, and based on the actual grammar of PHP.
* [PHP Token Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) - Library emulating the PHP internal reflection using just the tokenized source code. 
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - A full-scale PHP 5.3.2+ sandbox class that utilizes PHPParser to prevent sandboxed code from running unsafe code.
* [Reflection](https://github.com/phpDocumentor/Reflection.git) - Reflection library to do Static Analysis for PHP Projects


### Fixers

Tools that automatically fix the code they are provided with. 

* [php-refactoring-browser](https://github.com/QafooLabs/php-refactoring-browser) - A command line refactoring tool for PHP. 
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - Analyzes some PHP source code and tries to fix coding standards issues (PSR-1 and PSR-2 compatible)
* [phpdoc to typehint](https://github.com/dunglas/phpdoc-to-typehint) - Turn your phpdocs comments to actual Typehint (arguments and return)
* [Transphpile](https://github.com/jaytaph/Transphpile) - Write PHP 7, run PHP 5.6, with feature backport. 

### Metrics

Tools that measures the code : complexity, line of codes, etc. 

* [Design Pattern Detector](https://github.com/Halleck45/DesignPatternDetector.git) - detection of design patterns in PHP code
* [Dissect](https://github.com/jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - Utility that measures the size of a PHP application, and count various structures.
* [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - PHP Metrics calculates all sorts of metrics, and display them in a gorgeous interface.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - Utility that check the semantic version of a given code.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - Static code analysis to provide and verify a dependency graph against a defined architecture.
* [PHP semver checker](https://github.com/tomzx/php-semver-checker) - Compares two source sets and determines the appropriate semantic versioning to apply.
* [Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer.git) - Quality Analyzer is a tool to visualize metrics and source code. 

### SaaS

Online services that review PHP code, provide dashboards. They may use the previous tools or offer their own.

* [Bliss](https://blissai.com/index.html) - "Bliss automatically reviews your code in real-time and shows you how much it's worth in lines of code".
* [Checkmarx](http://lp.checkmarx.com/php-code-analysis/) - "Get a full PHP  static security code analysis and prevent security vulnerabilities"
* [Codacy](https://www.codacy.com/) - "Codacy: Automated Code Review"
* [Code Climate](https://codeclimate.com) - "Hosted static analysis for Ruby, PHP and JavaScript source code."
* [Insight](https://insight.sensiolabs.com/) - "SensioLabsInsight is a quality assurance tool that analyzes your source code to find problems that degrade the overall quality of your projects."
* [Ripstech](https://www.ripstech.com/) - "The superior security software for PHP applications."
* [Scrutinizer](https://scrutinizer-ci.com/) - "Improve code quality and find bugs before they hit production with our continuous inspection platform."

## Misc

* [devbug](http://www.devbug.co.uk/) - Ongoing work on PHP Analysis in Rascal (PHP AiR).
* [HHVM](http://hhvm.com/) - Hack Language from Facebook. Add a SCA until version 3.3.8, newer version doesn't have anymore.
* [PHP Analysis](https://github.com/cwi-swat/php-analysis) - A library for analysing and modifying PHP Source Code.
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.
* [PHP Parser](https://github.com/glayzzle/php-parser) - A NodeJS library for parsing PHP and extracting tokens and AST.
