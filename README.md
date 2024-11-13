# lefthook-configs

[Lefthook](https://github.com/evilmartians/lefthook) git hook configs

## Usage

Available LANG configs:

- deno
- golang
- markdown
- python
- rust

Add a lefthook config file to the project root:

```yaml
# lefthook.yml

remote:
  git: https://github.com/boldandbrad/lefthook-configs
  config: lefthook-LANG.yml
```

Run `lefthook install` in the local project directory.

