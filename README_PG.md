# My (PG) Notes #

[Errata](https://www.oreilly.com/catalog/errata.csp?isbn=0636920830702)

TODO: install fastai extensions for Jupyter / Git.

$ pipinstall nbdev
$ nbdev_install_hooks

Create file precommit-config.yaml with following contents:

repos:
\- repo: https://github.com/fastai/nbdev
  rev: 2.2.10
  hooks:
\  - id: nbdev_clean
\  - id: nbdev_export
