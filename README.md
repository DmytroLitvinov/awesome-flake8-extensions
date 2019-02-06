# Awesome flake8 extensions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome flake8 extensions.

Inspired after reading a [post](https://julien.danjou.info/the-best-flake8-extensions/).

Table of Contents
-----------------

- [Awesome flake8 extensions](#awesome-flake8-extensions)
    - [Clean code](#clean-code)
    - [Testing](#testing)
    - [Security](#security)
    - [Documentations](#documentations)
    - [Enhancement for flake8](#enhancement-for-flake8)
    - [Copyrights](#copyrights)
    - [Flake8 frameworks](#flake8-frameworks)
    
- - -

## Clean code

*Extensions for clean code at your project.*

- [flake8-bugbear](https://github.com/PyCQA/flake8-bugbear) - Finding likely bugs and design problems in your program
- [flake8-commas](https://github.com/PyCQA/flake8-commas) - Enforcing trailing commas in python
- [flake8-import-order](https://github.com/PyCQA/flake8-import-order) - Include checks import order against various Python Style Guides
- [flake8-isort](https://github.com/gforcada/flake8-isort) - Plugin that integrates [isort](https://pypi.org/project/isort/)
- [flake8-quotes](https://github.com/zheller/flake8-quotes) - Extension for checking quotes in python
- [flake8-blind-except](https://github.com/elijahandrews/flake8-blind-except) - Include checks for blind, catch-all except statements 
- [flake8-logging-format](https://github.com/globality-corp/flake8-logging-format) - Validate (lack of) logging format strings
- [flake8-pep3101](https://github.com/gforcada/flake8-pep3101) - Checks for old string formatting. 
- [flake8-builtins](https://github.com/gforcada/flake8-builtins) - Check for python builtins being used as variables or parameters
- [flake8-comprehensions](https://github.com/adamchainz/flake8-comprehensions) - It helps you write better list/set/dict comprehensions.
- [flake8-string-format](https://github.com/xZise/flake8-string-format) - Check that indexed parameters are used in strings
- [flake8-eradicate](https://github.com/sobolevn/flake8-eradicate) - Flake8 plugin to find commented out or dead code
- [flake8-broken-line](https://github.com/sobolevn/flake8-broken-line) - Flake8 plugin to forbid backslashes (`\`) for line breaks
- [flake8-print](https://github.com/JBKahn/flake8-print) - Check for Print statements in python files.
- [flake8-todo](https://github.com/schlamar/flake8-todo) - Check for TODO notes.
- [flake8-mutable](https://github.com/ebeweber/flake8-mutable) - Flake8 extension for mutable default arguments
- [cohesion](https://github.com/mschwager/cohesion#flake8-support) - Flake8 extension for measuring Python class cohesion.
- [flake8-tidy-imports](https://github.com/adamchainz/flake8-tidy-imports) - Flake8 extension that helps you write tidier imports.
- [flake8-spellcheck](https://github.com/MichaelAquilina/flake8-spellcheck) - Spellcheck variables, classnames, comments, docstrings etc
- [flake8-strict](https://github.com/smarkets/flake8-strict) - Checks Python code against a set of opinionated style rules.
- [flake8-django](https://github.com/rocioar/flake8-django) - Flake8 plugin for Django projects.
- [flake8-alfred](https://github.com/datatheorem/flake8-alfred) - Alfred is a flake8 plugin to warn on unsafe/obsolete symbols.
- [flake8-future-import](https://github.com/xZise/flake8-future-import) - Flake8 extension to check imports
- [flake8-coding](https://github.com/tk0miya/flake8-coding) - Adds coding magic comment checks (coding:) to flake8.
- [flake8-debugger](https://github.com/JBKahn/flake8-debugger) - Flake8 debug statement checker
- [flake8-pyi](https://github.com/ambv/flake8-pyi) - A plugin for Flake8 that provides specializations for type hinting stub files.
- [flake8-type-annotations](https://github.com/sobolevn/flake8-type-annotations) - Flake8 plugin to enforce consistent type annotation styles
- [flake8-mypy](https://github.com/ambv/flake8-mypy) - A plugin for flake8 integrating Mypy.
- [pep8-naming](https://github.com/PyCQA/pep8-naming) - Check the PEP-8 naming conventions.
- [flake8-annotations-coverage](https://github.com/best-doctor/flake8-annotations-coverage) - flake8 plugin to validate annotations coverage


## Testing

*Extensions for testing at your project.*

- [flake8-assertive](https://github.com/jparise/flake8-assertive) - Flake8 unittest assert method checker
- [flake8-mock](https://github.com/aleGpereira/flake8-mock) - Provides checking mock non-existent methods
- [flake8-pytest](https://github.com/vikingco/flake8-pytest) - Enforces to use `pytest`-style assertions


## Security

*Extensions for security of your code.*

- [flake8-bandit](https://github.com/tylerwince/flake8-bandit)


## Documentations

*Extensions for documentations at your project.*

- [flake8-docstrings](https://gitlab.com/pycqa/flake8-docstrings) - Include checks provided by pep257
- [flake8-rst-docstrings](https://github.com/peterjc/flake8-rst-docstrings) - Validate Python docstrings as reStructuredText (RST)
- [flake8-rst](https://github.com/kataev/flake8-rst) - Run flake8 checks on code in *.rst files or in docstrings


## Enhancement for flake8

*Extensions for flake8 plugin*

- [flake8-polyfill](https://gitlab.com/pycqa/flake8-polyfill) - A tiny package that provides the poly fill for Flake8 plugins trying to support Flake8 2.x and Flake8 3.x
- [flake8-per-file-ignores](https://github.com/snoack/flake8-per-file-ignores) - Ignore individual error codes per file with flake8
- [flake8-putty](https://github.com/jayvdb/flake8-putty) - Flake8 plugin to control reporting per file and line


## Copyrights

*Extensions for copyright at your project*

- [flake8-copyright](https://github.com/savoirfairelinux/flake8-copyright) - Adds copyright checks to flake8
- [flake8-ownership](https://github.com/decafjoe/flake8-ownership) - Checker for assuring that author, copyright, and license are specified in source files.


## Flake8 frameworks

*Frameworks for flake8 at your project*

- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated python linter ever
