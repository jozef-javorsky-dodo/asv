airspeed velocity
=================

**airspeed velocity** (``asv``) is a tool for benchmarking Python
packages over their lifetime.

It is primarily designed to benchmark a single project over its
lifetime using a given suite of benchmarks.  The results are displayed
in an interactive web frontend that requires only a basic static
webserver to host.

See an `example airspeed velocity site <https://pv.github.io/numpy-bench/>`__.

See the `full documentation <https://asv.readthedocs.io/>`__
for more information.

The latest release can be installed from PyPI using::

    pip install asv

Are you using ``asv``?  Consider adding a badge to your project's
README like this:

.. image:: https://img.shields.io/badge/benchmarked%20by-asv-blue.svg?style=flat

By using the following markdown::

  [![asv](https://img.shields.io/badge/benchmarked%20by-asv-blue.svg?style=flat)](https://your-url-here/)

License: `BSD three-clause license
<https://opensource.org/license/BSD-3-Clause>`__.

Authors: Michael Droettboom, Pauli Virtanen, asv Developers
