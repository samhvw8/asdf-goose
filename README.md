<div align="center">

# asdf-goose [![Build](https://github.com/samhvw8/asdf-goose/actions/workflows/build.yml/badge.svg)](https://github.com/samhvw8/asdf-goose/actions/workflows/build.yml) [![Lint](https://github.com/samhvw8/asdf-goose/actions/workflows/lint.yml/badge.svg)](https://github.com/samhvw8/asdf-goose/actions/workflows/lint.yml)


[goose](https://pressly.github.io/goose/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add goose
# or
asdf plugin add goose https://github.com/samhvw8/asdf-goose.git
```

goose:

```shell
# Show all installable versions
asdf list-all goose

# Install specific version
asdf install goose latest

# Set a version globally (on your ~/.tool-versions file)
asdf global goose latest

# Now goose commands are available
goose -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/samhvw8/asdf-goose/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sam Hoang](https://github.com/samhvw8/)
