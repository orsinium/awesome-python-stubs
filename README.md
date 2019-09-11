<img src="http://mypy-lang.org/static/mypy_light.svg" alt="mypy logo" width="300px"/>

# awesome-python-stubs

[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)
[![Gitter](https://badges.gitter.im/mypy-django/Lobby.svg)](https://gitter.im/mypy-django/Lobby)

Collection of awesome Python stubs and tools to work with them.


## Contents

- [Stub packages](#stub-packages)
- [Tools](#tools)
- [Articles](#articles)


## Stub packages

- [Typeshed](https://github.com/python/typeshed) - Collection of library stubs for Python, with static types.
- [django-stubs](https://github.com/typeddjango/django-stubs) - stubs for [Django](https://github.com/django/django).
- [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) - stubs for [DRF](https://github.com/encode/django-rest-framework).
- [numpy-stubs](https://github.com/rominf/ordered-set-stubs) - stubs for [NumPy](http://github.com/numpy/numpy).
- [dry-python/returns](https://github.com/dry-python/returns) - stubs for [returns](https://github.com/dry-python/returns).
- [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) - stubs for [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy).
- [grpc-stubs](https://pypi.org/project/grpc-stubs/) - stubs for [grpc](https://github.com/grpc/grpc).
- [ordered-set-stubs](https://github.com/rominf/ordered-set-stubs) - stubs for [OrderedSet](https://github.com/LuminosoInsight/ordered-set).


## Mypy plugins

- [pynamodb-mypy](https://github.com/lyft/pynamodb-mypy) - Plugin for [PynamoDB](https://github.com/pynamodb/PynamoDB) support.
- [mypy-zope](https://github.com/Shoobx/mypy-zope) - Plugin for [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) support.
- [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) - some plugins already integrated into mypy.

## Tools

- [MonkeyType](https://github.com/instagram/MonkeyType) - MonkeyType collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your Python code based on the types collected at runtime.
- [pytest-mypy](https://github.com/dbader/pytest-mypy) - Mypy static type checker plugin for Pytest.
- [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) - pytest plugin for testing mypy types, stubs, and plugins.
- [flake8-mypy](https://github.com/ambv/flake8-mypy) - A plugin for flake8 integrating mypy.
- [flake8-pyi](https://github.com/ambv/flake8-pyi) - A plugin for Flake8 that provides specializations for type hinting stub files.
- [pytype](https://github.com/google/pytype/) - A static type analyzer, alternative to mypy. Can do static type inference, and generate stub files with infered types.
- [merge_pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) - part of pytype toolchain, applies stub files onto source code.

## Integrations

- [mypy-PyCharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) - mypy integration for PyCharm.
- [vim-mypy](https://github.com/Integralist/vim-mypy) - mypy integration for Vim.
- [linter-mypy](https://atom.io/packages/linter-mypy) - mypy intagration for Atom.
- [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) - mypy intagration for Emacs.

## Articles

- [PEP-484](https://www.python.org/dev/peps/pep-0484/) about type annotations.
- [PEP-561](https://www.python.org/dev/peps/pep-0561/) about distributing and packaging type information.
- [MyPy docs](https://mypy.readthedocs.io/en/latest/stubs.html) about stubs.
- [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) - full tutorial.


## License

[MIT](https://github.com/typeddjango/awesome-python-stubs/blob/master/LICENSE)
