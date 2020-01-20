Introduction
============

.. image:: https://travis-ci.org/guillotinaweb/guillotina_pgfield.svg?branch=master
   :target: https://travis-ci.org/guillotinaweb/guillotina_pgfield

.. image:: https://codecov.io/gh/guillotinaweb/guillotina_pfgield/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/guillotinaweb/guillotina_pgfield/branch/master
   :alt: Test Coverage

.. image:: https://img.shields.io/pypi/pyversions/guillotina_pgfield.svg
   :target: https://pypi.python.org/pypi/guillotina_pgfield/
   :alt: Python Versions

.. image:: https://img.shields.io/pypi/v/guillotina_pgfield.svg
   :target: https://pypi.python.org/pypi/guillotina_pgfield

.. image:: https://img.shields.io/pypi/l/guillotina_pgfield.svg
   :target: https://pypi.python.org/pypi/guillotina_pgfield/
   :alt: License

.. image:: https://badges.gitter.im/plone/guillotina.png
   :target: https://gitter.im/plone/guillotina
   :alt: Chat



Naive aproach of pgfield with an external PG database


Basic instructions
------------------

* Python >= 3.7
* PostgreSQL >= 9.6




```
load_utilities:
  pgfield:
    factory: guillotina_pgfield.utility.PGFieldUtility
    provides: guillotina_pgfield.interfaces.IPGFieldUtility
    settings:
      dsn: postgres://user:passwd@pg_url:5432/db
      pool_size: 10
```
