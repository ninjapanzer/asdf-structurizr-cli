# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test structurizr-cli https://github.com/amoosbr/asdf-structurizr-cli.git "structurizr-cli"
```

Tests are automatically run in GitHub Actions on push and PR.
