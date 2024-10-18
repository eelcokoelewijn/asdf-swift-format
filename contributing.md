# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]
```

```shell
asdf plugin test swift-format https://github.com/eelcokoelewijn/asdf-swift-format.git "swift-format --help"
```

Tests are automatically run in GitHub Actions on push and PR.
