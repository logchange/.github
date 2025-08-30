# hofund — Usage

## Common commands

```bash
# List configuration keys
hofund list

# Import configuration from file
hofund import config.yaml

# Export configuration
hofund export --format json > config.json
```

## Environments

```bash
# Work with named environments
hofund env create staging
hofund env use staging
```

## Troubleshooting

- Verify permissions if hofund manages secrets/backends.
- Validate file formats when importing/exporting.
