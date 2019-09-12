FrontApp: Python wrapper for `Front <https://frontapp.com>`_ API
================================================================
.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
.. image:: https://img.shields.io/pypi/v/frontapp   :alt: PyPI

.. warning:: This project is in very early stage of development and is not recommended for usage in production.

Installation
********************************
.. code-block:: bash

    pip install frontapp


Quickstart
********************************

.. code-block:: python3

    from frontapp import Front

    front = Front.from_environment()

