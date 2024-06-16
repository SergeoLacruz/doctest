Welcome to Lumache's documentation!
===================================

**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

---
title: Stock Ownership
---

## Stock Ownership

ose stock locations and items.
The stock ownership feature is disabled by default, and must be enabled via the settings menu:

!!! warning "Existing Stock Locations and Items"
        Enabling the ownership feature will automatically remove the edit permissions to all users for stock locations and items which **do not have** any owner set. Only a user with admin permissions will be able to set the owner for those locations and items.

### Owner: Group vs User

* If a group is selected as owner, **all** users linked to the specified group will be able to edit the stock location or item.
* If a user is selected as owner, only the specified user will be able to edit the stock location or item.



Contents
--------

.. toctree::

   usage
   api
   qay
   bla
