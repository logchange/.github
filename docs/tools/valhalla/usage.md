# valhalla — Usage

## Tasks

```bash
# List tasks
valhalla list

# Run a task
valhalla run <task-name>
```

## Configuration

```yaml
# valhalla.yaml (example)
tasks:
  build:
    steps:
      - echo "Building..."
```

## Troubleshooting

- Ensure configuration file is in the project root.
- Use `--verbose` for more logging if supported.
