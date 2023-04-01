vers
====

Command-line PEP-0440_ version parser, bumper, and normalizer.

.. _PEP-0440: https://peps.python.org/pep-0440

Examples
--------

::

  $ vers --version 1.2 --bump minor
  1.3

  $ vers --version 1.2 --bump minor --bump dev
  1.3dev0

  $ vers --version 1.2 --bump minor --bump _rc
  1.3_rc0

  $ vers --version 1.2_rc2 --bump release
  1.2

  $ vers --version 1.2_rc2 --normalize
  1.2rc2

License
-------

GPL-3.0-or-later

TODO
----

Tests, packaging.
