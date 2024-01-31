# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test libsql-server https://github.com/jonasb/asdf-libsql-server.git "sqld --version"
```

Tests are automatically run in GitHub Actions on push and PR.
