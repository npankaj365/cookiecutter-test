========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-testproject/badge/?style=flat
    :target: https://readthedocs.org/projects/python-testproject
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/npankaj365/python-testproject.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/npankaj365/python-testproject

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/npankaj365/python-testproject?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/npankaj365/python-testproject

.. |requires| image:: https://requires.io/github/npankaj365/python-testproject/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/npankaj365/python-testproject/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/npankaj365/python-testproject/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/npankaj365/python-testproject

.. |version| image:: https://img.shields.io/pypi/v/testproject.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/testproject

.. |commits-since| image:: https://img.shields.io/github/commits-since/npankaj365/python-testproject/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/npankaj365/python-testproject/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/testproject.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/testproject

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/testproject.svg
    :alt: Supported versions
    :target: https://pypi.org/project/testproject

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/testproject.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/testproject


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install testproject

Documentation
=============


https://python-testproject.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
