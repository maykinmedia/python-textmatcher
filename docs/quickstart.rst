==========
Quickstart
==========

Installation
============

Install from PyPI with pip:

.. code-block:: bash

    pip install TextMatcher


Usage
=====

.. code-block:: python

    from TextMatcher.program import match

    find = 'Python enabled us to create EVE Online, a massive multiplayer game, in record time.'
    ratio = match('https://www.python.org/about/quotes/', find)

    print(ratio)
