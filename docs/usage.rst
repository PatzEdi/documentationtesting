Usage
=====

.. _installation:

Installation
------------

To install:

.. code-block:: console

   (.venv) $ pip install testdocumentation

Creating stuff
----------------

To retrieve a list of random ingredients,
you can use the ``commandhere`` function:

.. autofunction:: docs.testing

The ``docs`` parameter should be either ``"test"``, ``"testing"``,
or ``"tested"``. Otherwise, :py:func:`docs.testing`
will raise an exception.

.. autoexception:: docs.testingerror

For example:

>>> import docstesting
>>> print(docs.testing)
['testing', 'tested', 'test']
