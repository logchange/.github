# logchange — Reference

> This is a template. Replace with authoritative options from the logchange repo.

## CLI

```text
logchange [command] [options]
```

### Commands
- `init` — initialize configuration in current repo
- `add <message>` — add a change entry
- `generate` — generate release notes/changelog

### Common options
- `--since-tag <tag>` — only include changes after tag
- `--until-tag <tag>` — include changes up to tag
- `--output <file>` — write result to file

## Configuration

- File: `.logchange.yml` (example)
- Keys: `categories`, `templates`, `exclude`, `scopes` (examples)
