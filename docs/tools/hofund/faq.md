# hofund — FAQ

## How is sensitive data handled?
Consult the official repository for security guidelines and supported secret backends.

## Can I use multiple config sources?
Yes, typical patterns allow layering (env vars, files, remote stores). See [Usage](usage.md).

## How do I migrate existing configs?
Use `hofund import` to bring in YAML/JSON; validate with `hofund list`.
