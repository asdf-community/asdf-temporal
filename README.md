<div align="center">

# asdf-temporal [![Build](https://github.com/joshkaplinsky/asdf-temporal/actions/workflows/build.yml/badge.svg)](https://github.com/joshkaplinsky/asdf-temporal/actions/workflows/build.yml) [![Lint](https://github.com/joshkaplinsky/asdf-temporal/actions/workflows/lint.yml/badge.svg)](https://github.com/joshkaplinsky/asdf-temporal/actions/workflows/lint.yml)

[temporal](https://docs.temporal.io/cli/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add temporal
# or
asdf plugin add temporal https://github.com/asdf-community/asdf-temporal.git
```

temporal:

```shell
# Show all installable versions
asdf list-all temporal

# Install specific version
asdf install temporal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global temporal latest

# Now temporal commands are available
temporal --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/joshkaplinsky/asdf-temporal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Josh Kaplinsky](https://github.com/joshkaplinsky/)
