click-use-empty-env
===================

This is a very small addon package to `click`_ that restores the ability to use empty values from
env variables.

.. _click: https://palletsproject.com/p/click

What does this do?
------------------

...


Usage
-----

Before importing click (ideally in your project root `__init__.py` file) add:

.. code-block:: python
    from click_use_empty_env import install_patch

    install_patch()

