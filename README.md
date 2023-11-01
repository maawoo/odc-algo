odc.algo
========

Algorithm utils of various kind.

Installation
------------

```
pip install odc-algo
```

Usage
-----

Building
--------

1. Install Rust. Follow instructions at https://www.rust-lang.org/tools/install
2. Install the python build tool. `pip install build`
3. Build the package. `python -m build`


Development
-------

1. Follow build instructions
2. Install as dev `pip install -e .[dev]`
This will still compile the rust code, but without optimisations. Which may cause the algorithms to be VERY slow.
Alternatively, install with the whl file.
