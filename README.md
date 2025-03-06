# pre-commit-hooks

## Adding to your `.pre-commit-config.yaml`

```yaml
repos:
  - repo: https://github.com/erniedotson/pre-commit-hooks
    rev: v0.1.0  # Use the rev you want to point at
    hooks:
      - id: check-fixme
      # ...
```

## Hooks available

### `check-fixme`

Check for *FIXME:* comments.

### `check-todo`

Check for *TODO:* comments.
