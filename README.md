## Dependencies:

```
pip install sphinx-rtd-theme sphinx-copybutton
```

## Setup:

1. Modify `source/conf.py`.
2. Add .rst pages to `source` tree.

## Build

```
$ mkdir build
$ sphinx-build -M html source build
```

## Publish
Export contents of `build/html` to host.
