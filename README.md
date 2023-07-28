<div align="center">

# asdf-protoc-gen-connect-go [![Build](https://github.com/dylanrayboss/asdf-protoc-gen-connect-go/actions/workflows/build.yml/badge.svg)](https://github.com/dylanrayboss/asdf-protoc-gen-connect-go/actions/workflows/build.yml) [![Lint](https://github.com/dylanrayboss/asdf-protoc-gen-connect-go/actions/workflows/lint.yml/badge.svg)](https://github.com/dylanrayboss/asdf-protoc-gen-connect-go/actions/workflows/lint.yml)

[protoc-gen-connect-go](https://github.com/bufbuild/connect-go) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add protoc-gen-connect-go
# or
asdf plugin add protoc-gen-connect-go https://github.com/dylanrayboss/asdf-protoc-gen-connect-go.git
```

protoc-gen-connect-go:

```shell
# Show all installable versions
asdf list-all protoc-gen-connect-go

# Install specific version
asdf install protoc-gen-connect-go latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-connect-go latest

# Now protoc-gen-connect-go commands are available
protoc-gen-connect-go --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dylanrayboss/asdf-protoc-gen-connect-go/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [dylan](https://github.com/dylanrayboss/)
