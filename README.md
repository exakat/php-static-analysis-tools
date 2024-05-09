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

Tools to report issues in code that are or lead to bugs.

* [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) - static analysis tool for finding bugs, weaknesses and vulnerabilities in source code
* [Code insight](https://github.com/console-helpers/code-insight) - A tool for analysing other project code bases.
* [Churn-PHP](https://github.com/bmitch/churn-php.git) - Discover files in need of refactoring.
* [Composer-Unused](https://github.com/composer-unused/composer-unused.git) - A Composer tool to show unused Composer dependencies by scanning your code.
* [Eir](https://github.com/Lixody/Eir) - A static vulnerability analysis tool written in C#.
* [Exakat](http://www.exakat.io/) - Smart static analysis.
* [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for programming source code. 
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [name-collision-detector](https://github.com/shipmonk-rnd/name-collision-detector) - Detects symbol duplicates (class name collissions).
* [noverify](https://github.com/VKCOM/noverify) - Pretty fast linter (code static analysis utility) for PHP.
* [Pfff](https://github.com/facebook/pfff) - Tools for code analysis, visualizations, or style-preserving source transformation.
* [phanalist](https://github.com/denzyldick/phanalist.git) - A static analyzer for PHP. It helps you catch common mistakes in your PHP code.
* [PHP Analysis](https://github.com/cwi-swat/php-analysis) - A library for analysing and modifying PHP Source Code in Rascal (PHP AiR).
* [PHParch](https://github.com/j6s/phparch.git) - PHPArch is a work in progress architectural testing library for PHP projects. 
* [PHP Assumption](https://github.com/rskuipers/php-assumptions.git) - Finds <a href="http://rskuipers.com/entry/from-assumptions-to-assertions">weak assumptions</a> in the code, suggest to turn them into stronger validations.
* [PhpCodeAnalyzer](https://github.com/wapmorgan/PhpCodeAnalyzer.git) - Finds usage of non-built-in extensions.
* [PHPCodeFixer](https://github.com/wapmorgan/PhpCodeFixer) -  Finds usage of deprecated functions, variables and ini directives.
* [php-compat-info](https://github.com/llaville/php-compat-info) - Find out the minimum version and the extensions required for a piece of code to run.
* [php7mar](https://github.com/Alexia/php7mar) - PHP 7 Migration Assistant Report.
* [phpcallgraph](http://phpcallgraph.sourceforge.net/) - Generate static call graphs. Such a graph visualizes the call dependencies among methods or functions of an application..
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - Spots copy/pasted code, and help enforcing DRY rule.
* [PHPDoctor](https://github.com/voku/PHPDoctor) - Check PHP files or directories for missing types.
* [Phan](https://github.com/etsy/phan) - The static analyzer by Rasmus, PHP Creator.
* [Phinder](https://github.com/sider/phinder.git) - PHP code piece finder
* [Phortress](https://github.com/lowjoel/phortress) - A PHP static code analyser for potential vulnerabilities.
* [PHP Compatibility](https://github.com/PHPCompatibility/PHPCompatibility/) - Find code which is incompatible with a specified range of PHP versions.
* [PHP Deprecation Detector](https://github.com/wapmorgan/PhpDeprecationDetector) - PhpDeprecationDetector - analyzer of PHP code to search usages of deprecated functionality in newer interpreter versions.
* [PHP Code Static Analysis](https://github.com/joaaoleite/code-static-analysis) - PHP Code static analysis program made in nodeJS.
* [PHP Inspection](https://plugins.jetbrains.com/plugin/7622?pr=idea) - Static analysis plugin for PHPStorm.
* [PHP Integrator](https://github.com/php-integrator) - Indexes PHP code and performs static analysis for Atom editor.
* [Phlint](https://gitlab.com/phlint/phlint) - Phlint is a tool with an aim to help maintain quality of php code by analyzing code and pointing out potential code issues.
* [PHP lint](http://php.net/manual/en/features.commandline.options.php) - PHP itself, able to detect syntax error from command line.
* [PHPlint](http://www.icosaedro.it/phplint/) - A validator and documentator for PHP 5 programs.
* [PHP-Parallel-Lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) - A parallel php linting tool for PHP 5.4 or newer
* [PHP Magic Number Detector](https://github.com/povils/phpmnd) - PHP Magic Number Detector
* [PHP-malware-finder](https://github.com/nbs-system/php-malware-finder) - Detect potentially malicious PHP files
* [PHP Mess Detector](http://phpmd.org/) - Look for several potential problems within source code.
* [PHP Reaper](https://github.com/emanuil/php-reaper.git) - Scan ADOdb code for SQL Injections.
* [PHP SA](https://github.com/ovr/phpsa) - A development tool aimed at bringing complex analysis for PHP applications and libraries.
* [PHP Stan](https://github.com/phpstan/phpstan) - Focuses on finding errors in code without actually running it.
* [PHP Unlocker](http://emanuilslavov.com/php-unlocker/) - Detect potential, unintended DB table locks for PHP applications using ADOdb. Uses static analysis methods.
* [PHP testability](https://github.com/edsonmedina/php_testability) - Analyses and produces a report with testability issues of a php codebase.
* [PHP vuln hunter](https://github.com/OneSourceCat/phpvulhunter) - Scan PHP vulnerabilities automatically using static analysis methods.
* [Progpilot](https://github.com/designsecurity/progpilot) - A static analysis tool for security purposes.
* [Psalm](https://getpsalm.org/) - A static analysis tool for finding errors in PHP applications.
* [psecio:parse](https://github.com/psecio/parse.git) - Parse : A PHP Security Scanner.
* [Qodana PHP by JetBrains](https://www.jetbrains.com/help/qodana/qodana-php.html) – A static analysis tool for PHP projects based on PhpStorm.
* [SonarQube](http://www.sonarqube.org/) - An open platform to manage code quality. It covers PHP code.
* [Side Channel Analyzer](https://github.com/olivo/side-channel-analyzer) - Search for side-channel vulnerable code.
* [TaintPHP](https://github.com/olivo/TaintPHP.git) - Static Taint Analyzer.
* [Taint'em All](http://taint.spro.ink/) - A taint analysis tool for the PHP language, it makes use of Static Taint Analysis + Symbolic Execution.
* [Tuli](https://github.com/ircmaxell/Tuli) - A static analysis engine.
* [Unused-scanner](https://github.com/Insolita/unused-scanner.git) - Detect unused composer dependencies
* [WAP](https://www.owasp.org/index.php/OWASP_WAP-Web_Application_Protection) - Tool to detect and correct input validation vulnerabilities in PHP (4.0 or higher) web applications and predicts false positives. 
* [PHP VarDump Check](https://github.com/php-parallel-lint/PHP-Var-Dump-Check) - PHP console application for finding forgotten variable dump.
* [17eyes](https://github.com/17eyes/17eyes) - PHP static analyzer written in Haskell.
* [CakeFuzzer](https://zigrin.com/tools/cake-fuzzer) - Ultimate web application security testing tool for CakePHP based web applications.

### Coding standards

Tools to review the way PHP code was written and more.

* [Pahout](https://github.com/wata727/pahout) - A pair programming partner for writing better PHP.
* [EasyCodingStandard](https://github.com/Symplify/EasyCodingStandard) - An easy to use tool, that allows to use CodeSniffer and PHP-CS-Fixer in simple way.
* [PHPas](https://github.com/BaseMax/PHPAS.git) - A tool for format and beautify the style of PHP code with my style.
* [PHPArkitect](https://github.com/phparkitect/arkitect) - PHPArkitect helps you to keep your PHP codebase coherent and solid, by permitting to add some architectural constraint check to your workflow. 
* [PHP Code Sniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer) - PHPCS checks and auto-fixes the code for a large range of coding standard.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
* [PHP Doc Check](https://github.com/NielsdeBlaauw/php-doc-check) - Uses complexity metrics to enforce documentation conventions on non-trivial functions.
* [PHP formatter](https://github.com/mmoreram/php-formatter) - This PHP formatter aims to provide you some bulk actions for you PHP projects to ensure their consistency.
* [TLint](https://github.com/tighten/tlint) - This is an opinionated code linter (with growing support for auto-formatting!) for Tighten flavored code conventions for Laravel and PHP.

### DIY

Libraries that may be the base for a home-made static analyzer.

* [Deptrac](https://github.com/sensiolabs-de/deptrac.git) - A static code analysis tool to enforce rules for dependencies between software layers.
* [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy to use architecture testing tool for PHP
* [PHPArkitect](https://github.com/phparkitect/arkitect) - A static code analysis tool to enforce architectural rules in your codebase
* [PHP-cfg](https://github.com/ircmaxell/php-cfg) - A Control Flow Graph implementation in PHP. Written by IrcMaxwell.
* [PHP coupling detector](https://github.com/akeneo/php-coupling-detector) - Check that code has no unwanted coupled classes.
* [PHP Parser](https://github.com/nikic/PHP-Parser) - Written in PHP by Nikita Popov and based on actual grammar of PHP.
* [PHP Token Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) - Library emulating the PHP internal reflection using just the tokenized source code.
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - A full-scale PHP 5.3.2+ sandbox class that utilizes PHPParser to prevent sandboxed code from running unsafe code.
* [Reflection](https://github.com/phpDocumentor/Reflection.git) - Reflection library to do Static Analysis for PHP Projects.
* [Better Reflection](https://github.com/Roave/BetterReflection) - Reflection library with additional features such as parsing docblock type hints, uses nikic's PHP Parser under the hood.

### Fixers

Tools to automatically fix the code they are provided with.

* [Rector](https://github.com/rectorphp/rector) - AST-based Instant Upgrades of PHP Applications
* [FunctionFQNReplacer](https://github.com/Roave/FunctionFQNReplacer) - provides a way to replace relative references of functions in function calls with absolute references.
* [Phpactor](https://github.com/phpactor/phpactor) - This project aims to provide heavy-lifting refactoring and introspection tools.
* [PHP BackSlasher](https://github.com/nilportugues/php-backslasher) - Tool to add all PHP internal functions and constants to its namespace by adding backslash to them.
* [php-refactoring-browser](https://github.com/QafooLabs/php-refactoring-browser) - CLI refactoring tool.
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - Analyzes and tries to fix coding standards issues (PSR-1 and PSR-2 compatible).
* [phpdoc to typehint](https://github.com/dunglas/phpdoc-to-typehint) - Turn phpdocs comments to actual Typehint (arguments and return).
* [php-scoper](https://github.com/humbug/php-scoper) -  Prefixes all PHP namespaces in a file/directory to isolate the code bundled in PHARs.
* [Transphpile](https://github.com/jaytaph/Transphpile) - Write PHP 7, run PHP 5.6, with feature backport.
* [PHP Weaver](https://github.com/troelskn/phpweaver) - Analysing parameter types at runtime and generate the appropriate phpdocs.

### Metrics

Tools to measure the code complexity, line of codes, etc.

* [churn-php](https://github.com/bmitch/churn-php) - Helps discover good candidates for refactoring.
* [Design Pattern Detector](https://github.com/Halleck45/DesignPatternDetector.git) - detection of design patterns in PHP code.
* [dePHPend](https://github.com/mihaeu/dephpend) - dePHPend helps analyze dependencies & architecture and allows you to define constraints for both.
* [Dissect](https://github.com/jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [php-arguments-detector](https://github.com/DeGraciaMathieu/php-arguments-detector) - Keep control over the complexity of your methods by checking that they do not have too many arguments.
* [php-smelly-code-detector](https://github.com/DeGraciaMathieu/php-smelly-code-detector) - PHP code smell detector.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - Utility to measures PHP application size and count various structures.
* [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - Calculates all sorts of metrics, and display them in a gorgeous interface.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - Compares two source sets and determines the appropriate semantic versioning to apply.
* [PhpStats](https://github.com/i582/phpstats) - Tool for collecting statistics, metrics, dependencies, and building various graphs for large projects to find bottlenecks.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - Static code analysis to provide and verify a dependency graph against a defined architecture.
* [php-wording-detector](https://github.com/DeGraciaMathieu/php-wording-detector) - Simple tool to analyze and split the words contained in your code to check your DDD approach.
* [Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer.git) - Quality Analyzer is a tool to visualize metrics and source code.

### Visualization

Tools that display PHP code in graphical way

* [PHPcity](https://github.com/adrianhuna/PHPCity) - PHPCity is an implementation of city metaphor visualization and provides visualization of PHP projects which are implemented in the object-oriented fashion.

### SaaS

Online services for PHP code, provide dashboards. They may use the previous tools or offer their own.


* [Bliss](https://blissai.com/index.html) - Automatically reviews code in real-time and shows how much it's worth in lines of code.
* [Checkmarx](http://lp.checkmarx.com/php-code-analysis/) - Get a full PHP  static security code analysis and prevent security vulnerabilities.
* [Codacy](https://www.codacy.com/) - Codacy: Automated Code Review.
* [CodeBeaat](https://codebeat.co/) - Decrease technical debt. Find refactoring opportunities.
* [Code Climate](https://codeclimate.com) - Hosted static analysis for Ruby, PHP and JavaScript source code.
* [CodeScene](https://codescene.io/) - Prioritize technical debt in PHP, JavaScript, etc.
* [Codegrip](https://www.codegrip.tech/) - Smarter & Secure way to Code Review 
* [Deepsource](https://deepsource.io/) - DeepSource is a modern static analysis platform, built for engineering teams who move fast and don’t break things.
* [Insight](https://insight.sensiolabs.com/) - A SensioLabs tool to analyzes source code to find problems that degrade the overall quality of your projects.
* [Insphpect](https://insphpect.com/) - Insphpect is an automated code review tool which identifies inflexibilities in PHP code and helps you write better software.
* [RIPS](https://www.ripstech.com/) - The superior security software for PHP applications. Source code static analyser for vulnerabilities.
* [Scrutinizer](https://scrutinizer-ci.com/) - Improve code quality and find bugs before they hit production with our continuous inspection platform.
* [Sourcegraph](https://about.sourcegraph.com/) - Understand and search across your entire codebase
* [SideCI](https://sideci.com/) - CI for automated code review by code analysis.
* [Laravelshift](https://laravelshift.com/) - the automated way to upgrade Laravel applications. Upgrade Laravel applications all the way from Laravel 4.2 to the latest version of Laravel.

## Misc

* [HHVM](http://hhvm.com/) - Hack Language from Facebook. Add a SCA until version 3.3.8, newer version doesn't have anymore.
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.
* [PHP Parser](https://github.com/glayzzle/php-parser) - A NodeJS library for parsing PHP and extracting tokens and AST.
* [PHPQA](https://edgedesigncz.github.io/phpqa/) - A Wrapper to a lot of PHP tools reported into a single HTML file.
* [Fixtro](https://github.com/karlosagudo/fixtro) - A wrapper that allow to run in each precommit. It install itself all the dependencies for the runners with a lot of them (phpunit, phpmd, php-cs-fixer, etc..)
* [Coverage Checker](https://github.com/exussum12/coverageChecker) - A tool which allows some of the tools here to be enforced on changed code only. Good for moving towards new standards
* [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) - A CLI tool to check whether a specific composer package uses imported symbols that aren't part of its direct composer dependencies
* [phpstaticanalysis.com](https://phpstaticanalysis.com/demo) - A website that lets you try some PHP static analysis command-line tools online
* [Static Analysis Results Baseliner](https://github.com/DaveLiddament/sarb) - A tool for generating a baseline from static analysis tools. 
