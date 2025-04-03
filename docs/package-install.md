## Installing packages with uv

**To add package to your project**:

```sh
uv add numpy
```

where `numpy` is a package name.
It will add `numpy` to `pyproject.toml` file and install it in the virtual environment.

**Note**: To install package to virtual environment _without_ adding it to pyproject.toml, you could do this:

```sh
uv pip install numpy
```

But it's better to add it to `pyproject.toml` using `uv add`.

**Reference**: https://docs.astral.sh/uv/reference/cli/#uv-add
