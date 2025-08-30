# hofund — Reference

> Template; replace with canonical documentation from hofund repository.

## CLI

```text
hofund [command] [options]
```

### Commands (examples)
- `init` — initialize project config
- `set <key> <value>` — set a configuration value
- `get <key>` — read a configuration value
- `list` — list keys
- `import <file>` — import config from file
- `export` — export config

### Options (examples)
- `--format <yaml|json|toml>`
- `--env <name>`

## Configuration files

- Default location: `hofund.yaml` (example)
- Supports environment overrides and secret stores (depending on setup)
