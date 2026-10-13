# project-template

Shared [copier](https://copier.readthedocs.io) template for my Rust/Python projects.

## Usage

```sh
copier copy --vcs-ref v0.1.0 gh:vlaci/project-template .   # adopt
copier update --defaults                                   # upgrade
```

Add `extend = "ruff-base.toml"` to `[tool.ruff]` in `pyproject.toml`.

## Nix building blocks

```nix
ptLib = import ./nix/project-template.nix;
```
