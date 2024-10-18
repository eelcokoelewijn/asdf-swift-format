<div align="center">

# asdf-swift-format [![Build](https://github.com/eelcokoelewijn/asdf-swift-format/actions/workflows/build.yml/badge.svg)](https://github.com/eelcokoelewijn/asdf-swift-format/actions/workflows/build.yml) [![Lint](https://github.com/eelcokoelewijn/asdf-swift-format/actions/workflows/lint.yml/badge.svg)](https://github.com/eelcokoelewijn/asdf-swift-format/actions/workflows/lint.yml)

[swift-format](https://github.com/swiftlang/swift-format) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

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
asdf plugin add swift-format
# or
asdf plugin add swift-format https://github.com/eelcokoelewijn/asdf-swift-format.git
```

swift-format:

```shell
# Show all installable versions
asdf list-all swift-format

# Install specific version
asdf install swift-format latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swift-format latest

# Now swift-format commands are available
swift-format --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/eelcokoelewijn/asdf-swift-format/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Eelco Koelewijn](https://github.com/eelcokoelewijn/)
