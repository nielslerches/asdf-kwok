<div align="center">

# asdf-kwok [![Build](https://github.com/nielslerches/asdf-kwok/actions/workflows/build.yml/badge.svg)](https://github.com/nielslerches/asdf-kwok/actions/workflows/build.yml) [![Lint](https://github.com/nielslerches/asdf-kwok/actions/workflows/lint.yml/badge.svg)](https://github.com/nielslerches/asdf-kwok/actions/workflows/lint.yml)

[kwok](https://kwok.sigs.k8s.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kwok
# or
asdf plugin add kwok https://github.com/nielslerches/asdf-kwok.git
```

kwok:

```shell
# Show all installable versions
asdf list-all kwok

# Install specific version
asdf install kwok latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kwok latest

# Now kwok commands are available
kwok --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nielslerches/asdf-kwok/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Niels Lerche Sørensen](https://github.com/nielslerches/)
