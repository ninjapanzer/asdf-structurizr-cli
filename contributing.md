# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# Test just install of version without a test command (structurizr-cli has no version, help command option, that returns exit code 0)
asdf plugin test structurizr-cli https://github.com/amoosbr/asdf-structurizr-cli.git

# If run in the plugin source folder validate with a sample workspace.dsl
asdf plugin test structurizr-cli https://github.com/amoosbr/asdf-structurizr-cli.git "structurizr-cli validate -w $(pwd)/test/workspace.dsl"
```

Tests are automatically run in GitHub Actions on push and PR.
