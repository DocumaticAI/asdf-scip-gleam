# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test scip-gleam https://github.com/DocumaticAI/asdf-scip-gleam.git "scip-gleam --version"
```

Tests are automatically run in GitHub Actions on push and PR.
