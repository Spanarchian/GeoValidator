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
        | |coveralls| |codecov|
        | |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/Geovalidator/badge/?style=flat
    :target: https://readthedocs.org/projects/Geovalidator
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/spanarchian/Geovalidator.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/spanarchian/Geovalidator

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/spanarchian/Geovalidator?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/spanarchian/Geovalidator

.. |requires| image:: https://requires.io/github/spanarchian/Geovalidator/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/spanarchian/Geovalidator/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/spanarchian/Geovalidator/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/spanarchian/Geovalidator

.. |codecov| image:: https://codecov.io/gh/spanarchian/Geovalidator/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/spanarchian/Geovalidator

.. |codacy| image:: https://img.shields.io/codacy/grade/GeoValidator.svg
    :target: https://www.codacy.com/app/spanarchian/Geovalidator
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/spanarchian/Geovalidator/badges/gpa.svg
   :target: https://codeclimate.com/github/spanarchian/Geovalidator
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/geovalidator.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/geovalidator

.. |wheel| image:: https://img.shields.io/pypi/wheel/geovalidator.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/geovalidator

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/geovalidator.svg
    :alt: Supported versions
    :target: https://pypi.org/project/geovalidator

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/geovalidator.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/geovalidator

.. |commits-since| image:: https://img.shields.io/github/commits-since/spanarchian/Geovalidator/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/spanarchian/Geovalidator/compare/v0.0.1...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install geovalidator

You can also install the in-development version with::

    pip install https://github.com/spanarchian/Geovalidator/archive/master.zip


Documentation
=============


https://Geovalidator.readthedocs.io/


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
