# logchange — Usage

This section covers common tasks and workflows with logchange.

## Add entries

```bash
logchange add "fix: correct typo in README"
logchange add "feat: add API endpoint for X"
```

## Generate changelog

```bash
logchange generate
```

## Release process (example)

```bash
# Prepare release notes from changes since last tag
logchange generate --since-tag v1.2.3 --output CHANGELOG.md

# Tag and push
git tag v1.2.4
git push --tags
```

## Troubleshooting

- Ensure your repository is clean before generating.
- Validate your entry formatting if generation fails.
