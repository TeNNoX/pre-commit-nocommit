# pre-commit-nocommit
Hook for [pre-commit](https://pre-commit.com/) that prevents committing files with a NOCOMMIT comment (case insensitive):

```javascript
config.veryInsecureModeForDevelopment = true //NOCOMMIT
```

# Usage:

```yaml
repos:
  - repo: https://github.com/tennox/pre-commit-nocommit
    rev: master
    hooks:
      - id: nocommit-comment
```
