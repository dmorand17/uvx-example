# uvx-example

This is an example project for testing how to use [uvx](https://docs.astral.sh/uv/guides/tools/#running-tools).

## About

This repository serves as a simple demonstration and testing ground for working with `uvx`, a tool for running Python applications in isolated environments.

This project includes two separate modules (`example1` and `example2`) that can be invoked independently.

## Usage with uvx

### Running example1

```bash
uvx --from git+https://github.com/yourusername/uvx-example.git example1
```

### Running example2

```bash
uvx --from git+https://github.com/yourusername/uvx-example.git example2
```

### Running the default script

```bash
uvx git+https://github.com/yourusername/uvx-example.git
```

## Local Testing

You can also test locally by installing in editable mode:

```bash
# Install the package
pip install -e .

# Run the scripts
example1
example2
uvx-example
```

## Purpose

The main goal of this project is to:
- Experiment with `uvx` functionality
- Test package distribution and execution via `uvx`
- Demonstrate best practices for `uvx`-compatible projects
- Show how to create multiple entry points in a single package
