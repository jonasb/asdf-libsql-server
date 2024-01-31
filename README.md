<div align="center">

# asdf-libsql-server [![Build](https://github.com/jonasb/asdf-libsql-server/actions/workflows/build.yml/badge.svg)](https://github.com/jonasb/asdf-libsql-server/actions/workflows/build.yml) [![Lint](https://github.com/jonasb/asdf-libsql-server/actions/workflows/lint.yml/badge.svg)](https://github.com/jonasb/asdf-libsql-server/actions/workflows/lint.yml)

[libsql-server](https://github.com/tursodatabase/libsql/tree/main/libsql-server) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add libsql-server https://github.com/jonasb/asdf-libsql-server.git
```

libsql-server:

```shell
# Show all installable versions
asdf list-all libsql-server

# Install specific version
asdf install libsql-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global libsql-server latest

# Now libsql-server commands are available
sqld --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jonasb/asdf-libsql-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jonas Bengtsson](https://github.com/jonasb/)
