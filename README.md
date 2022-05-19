# Awesome Flake8 Extensions [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of awesome flake8 extensions.

Inspired after reading a [post](https://julien.danjou.info/the-best-flake8-extensions/).

## Contents

- [All-in-one](#all-in-one)
- [Bugs](#bugs)
- [Clean code](#clean-code)
- [Limitations](#limitations)
- [Naming](#naming)
- [Complexity](#complexity)
- [Comments](#comments)
- [Docstrings](#docstrings)
- [Tools](#tools)
- [Imports](#imports)
- [Testing](#testing)
- [Type annotations](#type-annotations)
- [Library-specific checks](#library-specific-checks)
- [Integrations](#integrations)
- [Wrappers](#wrappers)

## All-in-one

Extensions with more than 20 rules inside.

- [dlint](https://github.com/dlint-py/dlint) - Tool for encouraging best coding practices and helping ensure Python code is secure.
- [flake8-bugbear](https://github.com/PyCQA/flake8-bugbear) - Finding likely bugs and design problems in your program.
- [flake8-pie](https://github.com/sbdchd/flake8-pie) - Extension that implements misc. lints.
- [flake8-simplify](https://github.com/MartinThoma/flake8-simplify) - Plugin that helps you to simplify code.
- [hacking](https://github.com/openstack/hacking) - Set of flake8 plugins that test and enforce the [OpenStack StyleGuide](https://docs.openstack.org/hacking/latest/user/hacking.html#styleguide).
- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated python linter ever.

## Bugs

Extensions for finding possible bugs.

- [flake8-2020](https://github.com/asottile/flake8-2020) - Plugin which checks for misuse of `sys.version` or `sys.version_info`.
- [flake8-alfred](https://github.com/datatheorem/flake8-alfred) - Alfred is a flake8 plugin to warn on unsafe/obsolete symbols.
- [flake8-dunder-all](https://github.com/python-formate/flake8-dunder-all) - Ensures that modules have defined `__all__`.
- [flake8-encodings](https://github.com/python-formate/flake8-encodings) - Identify incorrect use of encodings.
- [flake8-requirements](https://github.com/Arkq/flake8-requirements) - Package requirements checker.
- [flake8-secure-coding-standard](https://github.com/Takishima/flake8-secure-coding-standard) - Enforce some secure coding standards for Python. <!-- TODO(@orsinium): move into "All-in-one" when grows -->
- [flake8-slots](https://github.com/python-formate/flake8-slots) - Require `__slots__` to be defined for subclasses of immutable types.
- [flake8-strftime](https://github.com/python-formate/flake8_strftime) - Checks for use of platform-specific strftime codes.
- [flake8-string-format](https://github.com/xZise/flake8-string-format) - Check that indexed parameters are used in strings.
- [flake8-unused-arguments](https://github.com/nhoad/flake8-unused-arguments) - Warn against unused arguments in functions.
- [flake8-useless-assert](https://github.com/decorator-factory/flake8-useless-assert) - Detect useless `assert` statements.
- [flake8-warnings](https://github.com/orsinium-labs/flake8-warnings) - Detect usage of deprecated modules, classes, and functions.

## Clean code

Extensions for finding stylistic issues and enforcing consistent codestyle.

- [flake8-commas](https://github.com/PyCQA/flake8-commas) - Enforcing trailing commas in python.
- [flake8-comprehensions](https://github.com/adamchainz/flake8-comprehensions) - Helps you write better list/set/dict comprehensions.
- [flake8-implicit-str-concat](https://github.com/keisheiled/flake8-implicit-str-concat) - Plugin to encourage correct string literal concatenation.
- [flake8-multiline-containers](https://github.com/jsfehler/flake8-multiline-containers) - Plugin to ensure a consistent format for multiline containers.
- [flake8-newspaper-style](https://github.com/mobility-university/flake8-newspaper-style) - Ensures the function definition goes below its usage.
- [flake8-quotes](https://github.com/zheller/flake8-quotes) - Extension for checking quotes in python.
- [flake8-return](https://github.com/afonasev/flake8-return) - Plugin that checks return values.
- [flake8-scream](https://github.com/MartinThoma/flake8-scream) - Rules which do have known false-positives but might still be useful for a one-time run.
- [flake8-sql](https://github.com/pgjones/flake8-sql) - Plugin that checks SQL code against opinionated style rules.
- [flake8-strict](https://github.com/smarkets/flake8-strict) - Checks Python code against a set of opinionated style rules.

## Limitations

Extensions banning specific Python features.

- [flake8-broken-line](https://github.com/sobolevn/flake8-broken-line) - Report line break with backslash (`\`).
- [flake8-debugger](https://github.com/JBKahn/flake8-debugger) - Report debug statements (`pdb`, `ipdb`).
- [flake8-logging-format](https://github.com/globality-corp/flake8-logging-format) - Report string formatting inside logging.
- [flake8-match](https://github.com/asottile/flake8-match) - Report `match` statement.
- [flake8-no-implicit-concat](https://github.com/10sr/flake8-no-implicit-concat) - Report implicit string concatenation.
- [flake8-no-pep420](https://github.com/adamchainz/flake8-no-pep420) - Report implicit namespace packages.
- [flake8-pep3101](https://github.com/gforcada/flake8-pep3101) - Report `%`-formatting.
- [flake8-print](https://github.com/JBKahn/flake8-print) - Report `print` statement.
- [flake8-printf-formatting](https://github.com/atugushev/flake8-printf-formatting) - Report `%`-formatting.
- [flake8-use-fstring](https://github.com/MichaelKim0407/flake8-use-fstring) - Report `%`-formatting and `str.format`.
- [flake8-use-pathlib](https://gitlab.com/RoPP/flake8-use-pathlib) - Report `os.path`.
- [flake8-walrus](https://github.com/asottile/flake8-walrus) - Report walrus operator (`:=`).

## Naming

Extensions for checking names of variables, functions, etc.

- [flake8-builtins](https://github.com/gforcada/flake8-builtins) - Check for python builtins being used as variables or parameters.
- [flake8-functions-names](https://github.com/Melevir/flake8-functions-names) - Validate functions names, decomposition and conformity with annotations.
- [flake8-test-name](https://github.com/bagerard/flake8-test-name) - Checks that test functions names follow a given convention.
- [flake8-variables-names](https://github.com/best-doctor/flake8-variables-names) - Extension that helps to make more readable variables names.
- [pep8-naming](https://github.com/PyCQA/pep8-naming) - Check the PEP-8 naming conventions.

## Complexity

Extensions for ensuring low code complexity.

- [cohesion](https://github.com/mschwager/cohesion#flake8-support) - Extension for measuring Python class cohesion.
- [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) - Plugin to validate annotations complexity.
- [flake8-cognitive-complexity](https://github.com/Melevir/flake8-cognitive-complexity) - Extension for flake8 that validates cognitive functions complexity.
- [flake8-expression-complexity](https://github.com/best-doctor/flake8-expression-complexity) - Plugin to validate expressions complexity.
- [flake8-functions](https://github.com/best-doctor/flake8-functions) - Plugin for validation of function parameters (length, complexity, etc).
- [flake8-length](https://github.com/orsinium-labs/flake8-length) - Smart line length validation.

## Comments

Extensions for checking comments.

- [flake8-coding](https://github.com/tk0miya/flake8-coding) - Adds coding magic comment checks (coding:) to flake8.
- [flake8-comments](https://github.com/orsinium-labs/flake8-comments) - Reports redundant comments.
- [flake8-copyright](https://github.com/savoirfairelinux/flake8-copyright) - Adds copyright checks to flake8.
- [flake8-eradicate](https://github.com/sobolevn/flake8-eradicate) - Plugin to find commented out or dead code.
- [flake8-executable](https://github.com/xuhdev/flake8-executable) - Plugin for checking executable permissions and shebangs.
- [flake8-fixme](https://github.com/tommilligan/flake8-fixme) - Check for FIXME, TODO and other temporary developer notes.
- [flake8-jira-todo-checker](https://github.com/simonstjg/flake8-jira-todo-checker) - Check that every TODO comment has a valid JIRA issue ID next to it.
- [flake8-noqa](https://github.com/plinss/flake8-noqa) - Validate `# noqa` comments.
- [flake8-ownership](https://github.com/decafjoe/flake8-ownership) - Checker for assuring that author, copyright, and license are specified in source files.
- [flake8-todo](https://github.com/schlamar/flake8-todo) - Check for TODO notes.
- [flake8-todos](https://github.com/orsinium-labs/flake8-todos) - Lint TODO comments to be consistent and have an issue linked.

## Docstrings

Extensions for checking docstrings.

- [darglint](https://github.com/terrencepreilly/darglint) - Check that the docstring description matches the definition.
- [flake8-docstrings](https://github.com/pycqa/flake8-docstrings) - Include checks provided by pep257.
- [flake8-rst-docstrings](https://github.com/peterjc/flake8-rst-docstrings) - Validate Python docstrings as reStructuredText (RST).
- [flake8-spellcheck](https://github.com/MichaelAquilina/flake8-spellcheck) - Spellcheck variables, classnames, comments, docstrings etc.

## Tools

Tools empowering flake8.

- [flake8-codes](https://github.com/orsinium-labs/flake8-codes) - CLI tool to introspect flake8 plugins and their codes.
- [flake8-dashboard](https://github.com/aperezhortal/flake8-dashboard) - Plugin to generate an HTML dashboard with reporting the flake8 violations found.
- [flake8-ruler](https://github.com/orsinium-labs/flake8-ruler) - More powerful configs for flake8.
- [flakehell](https://github.com/flakehell/flakehell) - Wrapper to make it nice, legacy-friendly, and configurable.
- [nitpick](https://github.com/andreoliwa/nitpick) - Enforce the same lint configuration (flake8, isort, mypy, pylint) across multiple Python projects.
- [yesqa](https://github.com/asottile/yesqa) - A tool to automatically remove unnecessary `# noqa` comments.

## Imports

Extensions for checking import statements.

- [flake8-absolute-import](https://github.com/bskinn/flake8-absolute-import) - Plugin to require absolute imports.
- [flake8-alphabetize](https://github.com/tlocke/flake8-alphabetize) - Checking the order of `import` statements and the `__all__` list.
- [flake8-future-import](https://github.com/xZise/flake8-future-import) - Extension to check imports.
- [flake8-import-order-spoqa](https://github.com/spoqa/flake8-import-order-spoqa) - Spoqa's import order style for flake8-import-order.
- [flake8-import-order](https://github.com/PyCQA/flake8-import-order) - Include checks import order against various Python Style Guides.
- [flake8-import-style](https://github.com/sfstpala/flake8-import-style) - Plugin to ensure explicit module imports.
- [flake8-tidy-imports](https://github.com/adamchainz/flake8-tidy-imports) - Extension that helps you write tidier imports.
- [flake8-type-checking](https://github.com/sondrelg/flake8-type-checking) - Plugin for managing type-checking imports & forward references.

## Testing

Extensions for testing.

- [flake8-aaa](https://github.com/jamescooke/flake8-aaa) - Lints tests against the Arrange Act Assert pattern.
- [flake8-assertive](https://github.com/jparise/flake8-assertive) - Unittest assert method checker.
- [flake8-mock](https://github.com/aleGpereira/flake8-mock) - Provides checking mock non-existent methods.
- [flake8-pytest](https://github.com/vikingco/flake8-pytest) - Enforces to use `pytest`-style assertions.
- [flake8-pytestrail](https://github.com/and-semakin/flake8-pytestrail) - Checks TestRail test case IDs.

## Type annotations

Extensions for type annotations.

- [flake8-annotations-coverage](https://github.com/best-doctor/flake8-annotations-coverage) - Plugin to validate annotations coverage.
- [flake8-annotations](https://github.com/sco1/flake8-annotations) - Plugin for flake8 to check for presence of type annotations in function definitions.
- [flake8-future-annotations](https://github.com/tyleryep/flake8-future-annotations) - Verifies Python 3.7+ files use `from __future__ import annotations`.
- [flake8-new-union-types](https://github.com/xome4ok/flake8-new-union-types) - Plugin to enforce new Union/Optional syntax `Foo | Bar | None` defined in PEP406.
- [flake8-no-types](https://github.com/adamchainz/flake8-no-types) - Plugin to ban type hints.
- [flake8-pep585](https://github.com/decorator-factory/flake8-pep585) - Enforce new style annotations from [PEP585](https://peps.python.org/pep-0585/) such as `list[int]` instead of `typing.List[int]`.
- [flake8-type-checking](https://github.com/snok/flake8-type-checking) - flake8 plugin that helps identify which imports to put into type-checking blocks, and how to adjust your type annotations once imports are moved.
- [flake8-typing-imports](https://github.com/asottile/flake8-typing-imports) - Plugin which checks that typing imports are properly guarded.

## Library-specific checks

Extensions for linting usage of specific libraries.

- [flake8-django](https://github.com/rocioar/flake8-django) - Plugin for Django projects.
- [flake8-fastapi](https://github.com/Kludex/flake8-fastapi) - Checks FastAPI code against opinionated style rules.
- [flake8-pytest-style](https://github.com/m-burst/flake8-pytest-style) - Plugin checking common style issues or inconsistencies with `pytest`-based tests.
- [flake8-scrapy](https://github.com/stummjr/flake8-scrapy) - Plugin to catch common issues on Scrapy spiders.
- [pandas-vet](https://github.com/deppen8/pandas-vet) - Plugin that provides opinionated linting for pandas code.

## Integrations

Extensions for running flake8 not only on Python files.

- [flake8-markdown](https://github.com/johnfraney/flake8-markdown) - Lints Python code blocks in Markdown files using flake8.
- [flake8-pyi](https://github.com/ambv/flake8-pyi) - Plugin for Flake8 that provides specializations for type hinting stub files.
- [flake8-rst](https://github.com/kataev/flake8-rst) - Checks on code in *.rst files or in docstrings.
- [jupyterlab-flake8](https://github.com/mlshapiro/jupyterlab-flake8) - Jupyterlab python linter for notebooks and text files using flake8.

## Wrappers

Wrappers around other tools making it possible to use them with flake8.

- [flake8-bandit](https://github.com/tylerwince/flake8-bandit) - Wrapper around [bandit](https://github.com/PyCQA/bandit).
- [flake8-black](https://github.com/peterjc/flake8-black) - Wrapper around [black](https://github.com/psf/black).
- [flake8-isort](https://github.com/gforcada/flake8-isort) - Wrapper around [isort](https://github.com/PyCQA/isort).
