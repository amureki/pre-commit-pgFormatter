# pgFormatter pre-commit mirror

Mirror of the [pgFormatter](https://github.com/darold/pgFormatter) for [pre-commit](https://pre-commit.com/).
Uses [Node.js thin-wrapper](https://github.com/gajus/pg-formatter).

## Installation

Add to your pre-commit config:

```yaml
- repo: https://github.com/amureki/pre-commit-pgFormatter
  rev: ''  # Use the sha / tag you want to point at
  hooks:
    - id: pg_format
```
