<div align="center">

# asdf-structurizr [![Build](https://github.com/amoosbr/asdf-structurizr/actions/workflows/build.yml/badge.svg)](https://github.com/amoosbr/asdf-structurizr/actions/workflows/build.yml) [![Lint](https://github.com/amoosbr/asdf-structurizr/actions/workflows/lint.yml/badge.svg)](https://github.com/amoosbr/asdf-structurizr/actions/workflows/lint.yml)


[structurizr-cli](https://github.com/structurizr/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.
- `java`: At runtime can be provided by asdf java plugin, for development (`asdf plugin test` command) needs to be put on path separate
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add structurizr-cli
# or
asdf plugin add structurizr-cli https://github.com/ninjapanzer/asdf-structurizr-cli.git
```

structurizr-cli:

```shell
# Show all installable versions
asdf list-all structurizr-cli

# Install specific version
asdf install structurizr-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global structurizr-cli latest

# Now structurizr-cli commands are available
structurizr-cli
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/amoosbr/asdf-structurizr/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alexander Moosbrugger](https://github.com/amoosbr/)
