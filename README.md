# pre-commit-import-linter #

A simple [pre-commit][0] hook to enforce contracts defined by [import-linter][1].

## Example ##

Default setting, load configuration from the default location.
The display shows verbose messages and the process time of each contract.

```yaml
  - repo: https://github.com/CJHwong/pre-commit-import-linter
    hooks:
      - id: pre-commit-import-linter
```


[0]: https://pre-commit.com/
[1]: https://import-linter.readthedocs.io/en/stable/index.html
