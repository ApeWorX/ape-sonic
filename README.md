# Quick Start

Ecosystem Plugin for Sonic support in Ape

## Dependencies

- [Python 3](https://www.python.org/downloads) version 3.10 or greater.

## Installation

### via `ape`

You can install this plugin using `ape`:

```bash
ape plugins install sonic
```

or via config file:

```yaml
# ape-config.yaml
plugins:
  - name: sonic
```

### via `pip`

You can install the latest release via [`pip`](https://pypi.org/project/pip/):

```bash
pip install ape-sonic
```

### via source

You can clone the repository and install for development:

```bash
git clone https://github.com/ApeWorX/ape-sonic.git
cd ape-sonic
uv sync --group dev
uv run prek install
```

## Quick Usage

Installing this plugin adds support for the Sonic ecosystem:

```bash
ape console --network sonic:mainnet
```
