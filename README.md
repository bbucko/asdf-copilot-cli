<div align="center">

# asdf-copilot-cli [![Build](https://github.com/bbucko/asdf-copilot-cli/actions/workflows/build.yml/badge.svg)](https://github.com/bbucko/asdf-copilot-cli/actions/workflows/build.yml) [![Lint](https://github.com/bbucko/asdf-copilot-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/bbucko/asdf-copilot-cli/actions/workflows/lint.yml)

[copilot-cli](https://github.com/github/copilot-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-copilot-cli  ](#asdf-copilot-cli--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add copilot-cli
asdf plugin add copilot-cli
# or
asdf plugin add copilot-cli https://github.com/bbucko/asdf-copilot-cli.git
asdf plugin add copilot-cli https://github.com/bbucko/asdf-copilot-cli.git
```

copilot:

```shell
# Show all installable versions
asdf list-all copilot

# Install specific version
asdf install copilot latest

# Set a version globally (on your ~/.tool-versions file)
asdf global copilot latest

# Now copilot commands are available
copilot --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bbucko/asdf-copilot/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Blazej Bucko](https://github.com/bbucko/)
