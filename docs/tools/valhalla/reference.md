# valhalla — Reference

> Template; replace with the canonical reference from the valhalla repository.

## CLI

```text
valhalla [command] [options]
```

### Commands (examples)
- `list` — list available tasks
- `run <task>` — execute a task
- `init` — create a starter configuration

### Options (examples)
- `--config <file>` — path to config file
- `--verbose` — verbose output

## Configuration (example)

```yaml
# valhalla.yaml
version: 1
plugins: []
tasks:
  build:
    steps:
      - echo "Building"
```
