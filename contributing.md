# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test goose https://github.com/samhvw8/asdf-goose.git "goose -v"
```

Tests are automatically run in GitHub Actions on push and PR.
