# Awesome Flake8 Extensions [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of awesome flake8 extensions.

Inspired after reading a [post](https://web.archive.org/web/20230322220629/https://julien.danjou.info/the-best-flake8-extensions/).

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
- [Formatters](#formatters)

## All-in-one

Extensions with more than 20 rules inside.

- [dlint](https://github.com/dlint-py/dlint) - Tool for encouraging best coding practices and helping ensure Python code is secure.
- [flake8-bugbear](https://github.com/PyCQA/flake8-bugbear) - Finding likely bugs and design problems in your program.
- [flake8-pie](https://github.com/sbdchd/flake8-pie) - Extension that implements misc. lints.
- [flake8-simplify](https://github.com/MartinThoma/flake8-simplify) - Plugin that helps you to simplify code.
- [hacking](https://github.com/openstack/hacking) - Set of flake8 plugins that test and enforce the [OpenStack StyleGuide](https://docs.openstack.org/hacking/latest/user/hacking.html#styleguide).
- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated Python linter ever.
- [flake8-tergeo](https://github.com/SAP/flake8-tergeo) - Adds many new rules to improve your code quality and brings a curated and actively maintained list of other plugins including flake8-bugbear.

## Bugs

Extensions for finding possible bugs.

- [flake8-2020](https://github.com/asottile/flake8-2020) - Plugin which checks for misuse of `sys.version` or `sys.version_info`.
- [flake8-alfred](https://github.com/datatheorem/flake8-alfred) - Alfred is a flake8 plugin to warn on unsafe/obsolete symbols.
- [flake8-async](https://github.com/cooperlees/flake8-async) - A flake8 plugin that checks for bad async / asyncio practices.
- [flake8-dunder-all](https://github.com/python-formate/flake8-dunder-all) - Ensures that modules have defined `__all__`.
- [flake8-encodings](https://github.com/python-formate/flake8-encodings) - Identify incorrect use of encodings.
- [flake8-mutable](https://github.com/ebeweber/flake8-mutable) - Detect usage of mutable objects as default values for arguments.
- [flake8-qt-tr](https://github.com/ostr00000/flake8-qt-tr) - Detect incorrectly wrapped Qt translation text.
- [flake8-requirements](https://github.com/Arkq/flake8-requirements) - Package requirements checker.
- [flake8-secure-coding-standard](https://github.com/Takishima/flake8-secure-coding-standard) - Enforce some secure coding standards for Python. <!-- TODO(@orsinium): move into 'All-in-one' when grows -->
- [flake8-slots](https://github.com/python-formate/flake8-slots) - Require `__slots__` to be defined for subclasses of immutable types.
- [flake8-strftime](https://github.com/python-formate/flake8_strftime) - Checks for use of platform-specific strftime codes.
- [flake8-string-format](https://github.com/xZise/flake8-string-format) - Check that indexed parameters are used in strings.
- [flake8-unused-arguments](https://github.com/nhoad/flake8-unused-arguments) - Warn against unused arguments in functions.
- [flake8-useless-assert](https://github.com/decorator-factory/flake8-useless-assert) - Detect useless `assert` statements.
- [flake8-warnings](https://github.com/orsinium-labs/flake8-warnings) - Detect usage of deprecated modules, classes, and functions.

## Clean code

Extensions for finding stylistic issues and enforcing consistent codestyle.

- [flake8-all-not-strings](https://github.com/ggupta2005/flake8-all-not-strings) - Checks that if modules under `__all__` are defined as strings.
- [flake8-class-attributes-order](https://github.com/best-doctor/flake8-class-attributes-order) - Checks classes attributes order.
- [flake8-clean-block](https://github.com/cyyc1/flake8-clean-block) - Plugin to enforce a blank line after if/for/while/with/try blocks.
- [flake8-commas](https://github.com/PyCQA/flake8-commas) - Enforcing trailing commas in Python.
- [flake8-comprehensions](https://github.com/adamchainz/flake8-comprehensions) - Helps you write better list/set/dict comprehensions.
- [flake8-datetime-utcnow-plugin](https://github.com/expobrain/flake8-datetime-utcnow-plugin) -  Plugin to warn the developer of the usage of `datetime.utcnow()`.
- [flake8-datetimez](https://github.com/pjknkda/flake8-datetimez) - A plugin for flake8 to ban the usage of unsafe naive datetime class.
- [flake8-implicit-str-concat](https://github.com/flake8-implicit-str-concat/flake8-implicit-str-concat) - Plugin to encourage correct string literal concatenation.
- [flake8-indent-in-def](https://github.com/cyyc1/flake8-indent-in-def) - Plugin to enforce 8-space indentation in function and class definitions.
- [flake8-literal](https://github.com/plinss/flake8-literal) - Enforces consistent styling of string literals.
- [flake8-multiline-containers](https://github.com/jsfehler/flake8-multiline-containers) - Plugin to ensure a consistent format for multiline containers.
- [flake8-newspaper-style](https://github.com/mobility-university/flake8-newspaper-style) - Ensures the function definition goes below its usage.
- [flake8-obey-import-goat](https://github.com/Melevir/flake8-obey-import-goat) - Allows to forbid specific imports.
<!--lint ignore awesome-spell-check-->
- [flake8-picky-parentheses](https://github.com/robsdedude/flake8-picky-parentheses) - Checks for redundant parentheses and alignment of parentheses and brackets.
- [flake8-quotes](https://github.com/zheller/flake8-quotes) - Extension for checking quotes in Python.
- [flake8-return](https://github.com/afonasev/flake8-return) - Plugin that checks return values.
- [flake8-scream](https://github.com/MartinThoma/flake8-scream) - Rules which do have known false-positives but might still be useful for a one-time run.
- [flake8-sql](https://github.com/pgjones/flake8-sql) - Plugin that checks SQL code against opinionated style rules.
- [flake8-strict](https://github.com/smarkets/flake8-strict) - Checks Python code against a set of opinionated style rules.
- [flake8-too-many](https://github.com/queensferryme/flake8-too-many) - Plugin that prevents you from writing 'too many' bad codes.
- [tryceratops](https://github.com/guilatrova/tryceratops) - Prevent exception handling antipatterns.

## Limitations

Extensions banning specific Python features.

- [flake8-broken-line](https://github.com/wemake-services/flake8-broken-line) - Report line break with backslash (`\`).
- [flake8-debugger](https://github.com/JBKahn/flake8-debugger) - Report debug statements (`pdb`, `ipdb`).
- [flake8-forbidden-func](https://github.com/tripcher/flake8-forbidden-func) - Forbid some functions in some modules.
- [flake8-logging](https://github.com/adamchainz/flake8-logging) - Reports issues in using the standard library logging module.  
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

- [flake8-builtins](https://github.com/gforcada/flake8-builtins) - Check for Python builtins being used as variables or parameters.
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

- [flake8-ado](https://github.com/DanielKusyDev/flake8-ado) - Check that all Azure DevOps IDs mentioned in the comments are in the correct format and have the corresponding ADO item.
- [flake8-author](https://github.com/jparise/flake8-author) - Checks Python modules for `__author__` attributes.
- [flake8-coding](https://github.com/tk0miya/flake8-coding) - Adds coding magic comment checks (coding:) to flake8.
- [flake8-comments](https://github.com/orsinium-labs/flake8-comments) - Reports redundant comments.
- [flake8-copyright](https://github.com/savoirfairelinux/flake8-copyright) - Adds copyright checks to flake8.
- [flake8-eradicate](https://github.com/wemake-services/flake8-eradicate) - Plugin to find commented out or dead code.
- [flake8-executable](https://github.com/xuhdev/flake8-executable) - Plugin for checking executable permissions and shebangs.
- [flake8-fixme](https://github.com/tommilligan/flake8-fixme) - Check for FIXME, TODO and other temporary developer notes.
- [flake8-jira-todo-checker](https://github.com/simonstjg/flake8-jira-todo-checker) - Check that every TODO comment has a valid JIRA issue ID next to it.
- [flake8-noqa](https://github.com/plinss/flake8-noqa) - Validate `# noqa` comments.
- [flake8-ownership](https://github.com/decafjoe/flake8-ownership) - Checker for assuring that author, copyright, and license are specified in source files.
- [flake8-todo](https://github.com/schlamar/flake8-todo) - Check for TODO notes.
- [flake8-todos](https://github.com/orsinium-labs/flake8-todos) - Lint TODO comments to be consistent and have an issue linked.

## Docstrings

Extensions for checking docstrings.

- [flake8-docstring-checker](https://gitlab.com/JakobDev/flake8-docstring-checker) - Checks if everything has a docstring.
- [flake8-docstrings](https://github.com/pycqa/flake8-docstrings) - Include checks provided by pep257.
- [flake8-docstrings-complete](https://github.com/jdkandersson/flake8-docstrings-complete) - Linter that checks docstrings of functions, methods and classes.
- [flake8-rst-docstrings](https://github.com/peterjc/flake8-rst-docstrings) - Validate Python docstrings as reStructuredText (RST).
- [flake8-spellcheck](https://github.com/MichaelAquilina/flake8-spellcheck) - Spellcheck variables, classnames, comments, docstrings etc.
- [flake8-sphinx-links](https://github.com/python-formate/flake8-sphinx-links) - Check docstrings for double backticked strings which should be links to the Python documentation.
- [pydoclint](https://github.com/jsh9/pydoclint) - A Python docstring linter that checks arguments, returns, yields, and raises sections.

## Tools

Tools empowering flake8.

- [flake8-codes](https://github.com/orsinium-labs/flake8-codes) - CLI tool to introspect flake8 plugins and their codes.
- [flake8-pyproject](https://github.com/john-hen/Flake8-pyproject) - Flake8 plug-in loading the configuration from pyproject.toml.
- [flake8-pyprojecttoml](https://gitlab.com/durko/flake8-pyprojecttoml) - Adds support for reading flake8 config from pyproject.toml.
- [flake8-ruler](https://github.com/orsinium-labs/flake8-ruler) - More powerful configs for flake8.
- [flakehell](https://github.com/flakehell/flakehell) - Wrapper to make it nice, legacy-friendly, and configurable.
- [flakes](https://flakes.orsinium.dev/) - Web list of flake8 plugins and their codes, a wrapper around flake8-codes.
- [nitpick](https://github.com/andreoliwa/nitpick) - Enforce the same lint configuration (flake8, isort, mypy, pylint) across multiple Python projects.
- [wps-playground](https://github.com/orsinium-labs/wps-playground) - Online playground for wemake-python-styleguide.
- [yesqa](https://github.com/asottile/yesqa) - A tool to automatically remove unnecessary `# noqa` comments.
- [flake8-in-file-ignores](https://github.com/bagerard/flake8-in-file-ignores) - Allow in file ignore e.g. `# flake8-in-file-ignores: noqa: E731`.


## Imports

Extensions for checking import statements.

- [flake8-absolute-import](https://github.com/bskinn/flake8-absolute-import) - Plugin to require absolute imports.
- [flake8-alphabetize](https://github.com/tlocke/flake8-alphabetize) - Checking the order of `import` statements and the `__all__` list.
- [flake8-datetime-import](https://github.com/marcgibbons/flake8-datetime-import) - Enforce importing `datetime as dt` and `time as tm`.
- [flake8-future-import](https://github.com/xZise/flake8-future-import) - Extension to check imports.
- [flake8-import-conventions](https://github.com/joaopalmeiro/flake8-import-conventions) - How certain packages should be imported or aliased.
- [flake8-import-order-spoqa](https://github.com/spoqa/flake8-import-order-spoqa) - Spoqa's import order style for flake8-import-order.
- [flake8-import-order](https://github.com/PyCQA/flake8-import-order) - Include checks import order against various Python Style Guides.
- [flake8-import-style](https://github.com/sfstpala/flake8-import-style) - Plugin to ensure explicit module imports.
- [flake8-internal-name-import](https://github.com/rows-s/flake8_internal_name_import) - Plugin that reports imports of protected names.
- [flake8-tidy-imports](https://github.com/adamchainz/flake8-tidy-imports) - Extension that helps you write tidier imports.
- [flake8-type-checking](https://github.com/snok/flake8-type-checking) - Plugin lets you know which imports to move in or out of type-checking blocks.

## Testing

Extensions for testing.

- [flake8-aaa](https://github.com/jamescooke/flake8-aaa) - Lints tests against the Arrange Act Assert pattern.
- [flake8-assertive](https://github.com/jparise/flake8-assertive) - Unittest assert method checker.
- [flake8-mock](https://github.com/zupo/flake8-mock) - Provides checking mock non-existent methods.
- [flake8-mock-spec](https://github.com/jdkandersson/flake8-mock-spec) - Enforce the use of the spec argument on mocks ensuring that your use of mocks is compliant with the interface of the object being mocked.
- [flake8-pytest-style](https://github.com/m-burst/flake8-pytest-style) - Checks for common style issues or inconsistencies with pytest-based tests.
- [flake8-pytest](https://github.com/vikingco/flake8-pytest) - Enforces to use `pytest`-style assertions.
- [flake8-pytestrail](https://github.com/and-semakin/flake8-pytestrail) - Checks TestRail test case IDs.

## Type annotations

Extensions for type annotations.

- [flake8-annotations-coverage](https://github.com/best-doctor/flake8-annotations-coverage) - Plugin to validate annotations coverage.
- [flake8-annotations](https://github.com/sco1/flake8-annotations) - Plugin for flake8 to check for presence of type annotations in function definitions.
- [flake8-future-annotations](https://github.com/tyleryep/flake8-future-annotations) - Verifies Python 3.7+ files use `from __future__ import annotations`.
- [flake8-new-union-types](https://github.com/xome4ok/flake8-new-union-types) - Plugin to enforce new Union/Optional syntax `Foo | Bar | None` defined in [PEP 604][pep604].
- [flake8-pep585](https://github.com/decorator-factory/flake8-pep585) - Enforce new style annotations from [PEP585](https://peps.python.org/pep-0585/) such as `list[int]` instead of `typing.List[int]`.
- [flake8-pep604](https://gitlab.com/matthewhughes/flake-pep604) - Forbids use of `typing.Union` (in favour of `|`), per [PEP 604][pep604].
- [flake8-typing-imports](https://github.com/asottile/flake8-typing-imports) - Plugin which checks that typing imports are properly guarded.

## Library-specific checks

Extensions for linting usage of specific libraries.

- [flake8-django-migrations](https://github.com/browniebroke/flake8-django-migrations) - Plugin to lint for backwards incompatible database migrations in Django.
- [flake8-django](https://github.com/rocioar/flake8-django) - Plugin for Django projects.
- [flake8-fastapi](https://github.com/Kludex/flake8-fastapi) - Checks FastAPI code against opinionated style rules.
- [flake8-numba](https://github.com/mflova/flake8-numba) - Plugin that facilitates code development with `numba` package.
- [flake8-scrapy](https://github.com/stummjr/flake8-scrapy) - Plugin to catch common issues on Scrapy spiders.
- [pandas-vet](https://github.com/deppen8/pandas-vet) - Plugin that provides opinionated linting for Pandas code.
- [TorchFix](https://github.com/pytorch-labs/torchfix) - Plugin for code that uses PyTorch.

## Integrations

Extensions for running flake8 not only on Python files.

- [flake8-markdown](https://github.com/johnfraney/flake8-markdown) - Lints Python code blocks in Markdown files using flake8.
- [flake8-nb](https://github.com/s-weigand/flake8-nb) - Runs flake8 on `*.ipynb` (Jupyter Notebook) files.
- [flake8-pyi](https://github.com/PyCQA/flake8-pyi) - Plugin for Flake8 that provides specializations for type hinting stub files.
- [flake8-rst](https://github.com/flake8-docs/flake8-rst) - Checks on code in `*.rst` files or in docstrings.
- [jupyterlab-flake8](https://github.com/mlshapiro/jupyterlab-flake8) - Jupyterlab Python linter for notebooks and text files using flake8.

## Wrappers

Wrappers around other tools making it possible to use them with flake8.

- [flake8-bandit](https://github.com/tylerwince/flake8-bandit) - Wrapper around [bandit](https://github.com/PyCQA/bandit).
- [flake8-black](https://github.com/peterjc/flake8-black) - Wrapper around [black](https://github.com/psf/black).
- [flake8-isort](https://github.com/gforcada/flake8-isort) - Wrapper around [isort](https://github.com/PyCQA/isort).
- [flake8-pylint](https://github.com/orsinium-labs/flake8-pylint) - Wrapper around [pylint](https://github.com/pylint-dev/pylint).

## Formatters

Extensions for formatting flake8 output.

- [flake8-dashboard](https://github.com/aperezhortal/flake8-dashboard) - Generates an HTML dashboard.
- [flake8-for-pycharm](https://gitlab.com/ramast/flake8-for-pycharm) - Generates pylint-style JSON output.
- [flake8-github](https://github.com/maxkrivich/flake8-github) - Generates GitHub annotation for PR's.
- [flake8-gl-codeclimate](https://github.com/awelzel/flake8-gl-codeclimate) - Generates GitLab Code Quality artifacts.
- [flake8-html](https://github.com/lordmauve/flake8-html) - Generates an HTML report.
- [flake8-json](https://github.com/PyCQA/flake8-json) - Generates JSON output.

[pep604]: https://peps.python.org/pep-0604/ 'PEP 604'
