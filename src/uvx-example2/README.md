# uvx-example2

This is the second example module for testing [uvx](https://docs.astral.sh/uv/guides/tools/#running-tools).

## About

This module demonstrates how to create a Python package with a script entry point that uses dot notation in its name.

## Script Entry Point

This package provides the following script:
- `example.example2` - Prints "Hello from example2!"

## Local Development

### Running with uv

From this directory (`src/uvx-example2`):

```bash
uv run example.example2
```

### Installing in editable mode

```bash
# Install the package
pip install -e .

# Run the script
example.example2
```

### Using uvx (from Git)

```bash
uvx --from git+https://github.com/yourusername/uvx-example.git#subdirectory=src/uvx-example2 example.example2
```
