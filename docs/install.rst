.. include:: references.txt

.. _gary-install:

============
Installation
============

Cloning, Building, Installing
=============================

The latest development version of gary can be cloned from
`GitHub <https://github.com/>`_ using ``git``::

   git clone git://github.com/adrn/gary.git

To build the project (from the root of the source tree, e.g., inside
the cloned ``gary`` directory)::

    python setup.py build

To install the project::

    python setup.py install


Dependencies
============

This packages has the following dependencies:

- `Python`_ >= 2.7

- `Numpy`_ >= 1.8

- `Cython <http://www.cython.org/>`_: >= 0.23

- `Astropy`_ >= 1.1

- `PyYAML`_ >= 3.10

You can use ``pip`` or ``conda`` to install these automatically.

Optional
--------

- `Sympy`_ for creating `~gary.potential.PotentialBase` objects from a
    mathematical expression using `~gary.potential.from_equation()`.
