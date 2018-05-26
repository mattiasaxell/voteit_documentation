.. _readme:

README: building VoteIT project user documentation
==================================================


This is instructions for building the documentation. If you're a regular user and just want to read the manual,
go back to the `VoteIT manual on ReadTheDocs <https://voteit.readthedocs.io/en/latest/>`_.

How to install and build a local environment.
You'll need python 2.7 or similar and have setuptools + virtualenv installed.
You'll also need make, or run the sphinx commands by hand.


1. Use virtualenv to create a local python within this directory and install sphinx

.. code-block:: bash

    virtualenv .
    bin/easy_install Sphinx


2. Build the documentation you'd like to work with. Each is located in it's respective directory.
There will be a Makefile present in the one you'll use.

The root of this repository is the manual main page. Check under languages for each specific language.

Simply run:

.. code-block:: bash

    make html


3. Locate the build documentation - it will be in a directory called _build.
