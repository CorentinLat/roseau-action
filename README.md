# Roseau Action

This GitHub Action runs a Roseau analysis between the last two commits.

## Usage

```yaml
jobs:
  run-roseau:
    runs-on: ubuntu-latest
    steps:
      - uses: alien-tools/roseau-action@v1
        with:
          report-artifact (optional): "csv" | "html" | "none" (default)
