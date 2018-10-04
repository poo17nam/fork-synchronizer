========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/fork-synchronizer/badge/?style=flat
    :target: https://readthedocs.org/projects/fork-synchronizer
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/RatanShreshtha/fork-synchronizer.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/RatanShreshtha/fork-synchronizer

.. |codecov| image:: https://codecov.io/github/RatanShreshtha/fork-synchronizer/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/RatanShreshtha/fork-synchronizer

.. |version| image:: https://img.shields.io/pypi/v/fork-synchronizer.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/fork-synchronizer

.. |commits-since| image:: https://img.shields.io/github/commits-since/RatanShreshtha/fork-synchronizer/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/RatanShreshtha/fork-synchronizer/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/fork-synchronizer.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/fork-synchronizer

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/fork-synchronizer.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/fork-synchronizer

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/fork-synchronizer.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/fork-synchronizer


.. end-badges

A simple python util to synchronize your fork with it's parent repository.

* Free software: MIT license

Installation
============

::

    pip install fork-synchronizer

Documentation
=============


https://fork-synchronizer.readthedocs.io/


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
