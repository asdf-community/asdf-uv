# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test uv https://github.com/b1-luettje/asdf-uv.git "uv --version"
```

Tests are automatically run in GitHub Actions on push and PR.
