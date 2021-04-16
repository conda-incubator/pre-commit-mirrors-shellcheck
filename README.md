# shellcheck pre-commit hook

Hook for shellcheck with conda as a language.

- For pre-commit: see https://github.com/pre-commit/pre-commit
- For shellcheck: see https://github.com/koalaman/shellcheck

### Using shellcheck with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/Quantco/pre-commit-mirrors-shellcheck
  rev: "" # The git sha / tag you want to point to
  hooks:
    - id: shellcheck-conda
```
