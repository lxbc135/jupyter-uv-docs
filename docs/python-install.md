## Installing Python using uv
Often users install Python from https://www.python.org/. But if you need to switch versions sometimes, for example, to test some feature compatibility, then the uv version manager would help with that.

To install the latest Python version, which is 3:

```sh
uv python install 3
```

If you have installed multiple versions, you can use a particular one:

```sh
uv python pin 3.12
```

To see all available Python versions:

```sh
uv python list
```

The installed ones show their installed local file path.

To uninstall a Python version:

```sh
uv python uninstall 3.11
```

For more help:

```sh
uv python --help
```

**Reference**: https://docs.astral.sh/uv/reference/cli/#uv-python
