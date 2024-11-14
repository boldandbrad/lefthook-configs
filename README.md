# lefthook-configs

[Lefthook](https://github.com/evilmartians/lefthook) remote git hook configs.

## Usage

Available LANG configs:

- [deno](./lefthook-deno.yml)
- [golang](./lefthook-golang.yml)
- [python](./lefthook-python.yml)
- [rust](./lefthook-rust.yml)

Add a lefthook config file to the project root:

```yaml
# lefthook.yml

remotes:
  - git_url: https://github.com/boldandbrad/lefthook-configs
    configs:
      - lefthook-deno.yml
```

Run `lefthook install` in the local project directory.
