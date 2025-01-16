# HOWTO merge from upstream

- apply the new patch to the files
- modify the files to have the changes from the original
- build a new patch from the modified files vs. what is checked in to master
- try to do this in the win32-sparse-patch branch and THEN pull it in to this branch for the final lmdb_m package

# Original

This is a universal Python binding for the LMDB ‘Lightning’ Database.

See [the documentation](https://lmdb.readthedocs.io) for more information.

### CI State
[![master](https://github.com/jnwatson/py-lmdb/workflows/Build,%20run,%20and%20test%20py-lmdb/badge.svg)](https://github.com/jnwatson/py-lmdb/actions/workflows/python-package.yml)

# Python Version Support Statement

This project has been around for a while.  Previously, it supported all the
way back to before Python 2.5.  Currently, py-lmdb supports Python >= 3.5
and pypy.

The last version of py-lmdb that supported Python 2.7 was 1.4.1.
