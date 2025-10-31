# 🧩 pre-commit-devmoji

A [pre-commit](https://pre-commit.com/) hook for [**devmoji**](https://github.com/folke/devmoji) — automatically decorate your commit messages with emojis ✨.


## Installation

```
# .pre-commit-config.yaml

repos:
  - repo: https://github.com/iwpnd/pre-commit-devmoji
    rev: latest # or rev: v0.0.1
    hooks:
      - id: devmoji
```

Then run:

```
pre-commit install --hook-type prepare-commit-msg
```


## License

MIT

## Maintainer

Benjamin Ramser - [@iwpnd](https://github.com/iwpnd)

Project Link: [https://github.com/iwpnd/pre-commit-devmoji](https://github.com/iwpnd/pre-commit-devmoji)

## Acknowledgements

[folke](https://github.com/folke) - maintainer of [devmoji](https://github.com/folke/devmoji)
[asottile](https://github.com/asottile) - maintainer of [pre-commit](https://github.com/pre-commit/pre-commit)
