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

## Inspiration / Thank you!

- [pre-commit](https://pre-commit.com)
- [@darold](https://github.com/darold) and [pgFormatter](https://github.com/darold/pgFormatter)
- [@adamchainz](https://github.com/adamchainz) and [pre-commit-dprint](https://github.com/adamchainz/pre-commit-dprint)
- [@gajus](https://github.com/gajus) and [pg-formatter](https://github.com/gajus/pg-formatter)
