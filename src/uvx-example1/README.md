# uvx-example1

This is the first example module for testing [uvx](https://docs.astral.sh/uv/guides/tools/#running-tools).

## About

This module demonstrates how to create a Python package with a script entry point that uses dot notation in its name.

## Script Entry Point

This package provides the following script:
- `example.example1` - Prints "Hello from example1!"

## Local Development

### Running with uv

From this directory (`src/uvx-example1`):

```bash
uv run example.example1
```

### Installing in editable mode

```bash
# Install the package
pip install -e .

# Run the script
example.example1
```

### Using uvx (from Git)

```bash
uvx --from git+https://github.com/yourusername/uvx-example.git#subdirectory=src/uvx-example1 example.example1
```
