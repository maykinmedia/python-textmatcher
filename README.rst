

.. TextMatcher documentation master file, created by startproject.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to TextMatcher's documentation!
=================================================

:Version: 0.1.0
:Source: https://github.com/maykinmedia/python-textmatcher
:Keywords: ``textmatcher``
:PythonVersion: 3.6

|build-status| |requirements| |coverage|

|python-versions| |pypi-version|

Extract data from an web-page or PDF-document and match it with the given text parameter

.. contents::

.. section-numbering::

Installation
============

Requirements
------------

* Python 3.6 or above
* setuptools 30.3.0 or above


Install
-------

.. code-block:: bash

    pip install textmatcher


Usage
=====

.. code-block:: python

    from textmatcher import match

    find = 'Python enabled us to create EVE Online, a massive multiplayer game, in record time.'
    ratio = match('https://www.python.org/about/quotes/', find)

    print(ratio)



.. |build-status| image:: https://travis-ci.org/maykinmedia/TextMatcher.svg?branch=develop
    :target: https://travis-ci.org/maykinmedia/TextMatcher

.. |requirements| image:: https://requires.io/github/maykinmedia/TextMatcher/requirements.svg?branch=develop
    :target: https://requires.io/github/maykinmedia/TextMatcher/requirements/?branch=develop
    :alt: Requirements status

.. |coverage| image:: https://codecov.io/gh/maykinmedia/TextMatcher/branch/develop/graph/badge.svg
    :target: https://codecov.io/gh/maykinmedia/TextMatcher
    :alt: Coverage status

.. |python-versions| image:: https://img.shields.io/pypi/pyversions/TextMatcher.svg

.. |pypi-version| image:: https://img.shields.io/pypi/v/TextMatcher.svg
    :target: https://pypi.org/project/TextMatcher/
