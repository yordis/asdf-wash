<div align="center">

# asdf-wash [![Build](https://github.com/yordis/asdf-wash/actions/workflows/build.yml/badge.svg)](https://github.com/yordis/asdf-wash/actions/workflows/build.yml) [![Lint](https://github.com/yordis/asdf-wash/actions/workflows/lint.yml/badge.svg)](https://github.com/yordis/asdf-wash/actions/workflows/lint.yml)

[wash](https://github.com/wasmCloud/wash) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wash
# or
asdf plugin add wash https://github.com/yordis/asdf-wash.git
```

wash:

```shell
# Show all installable versions
asdf list-all wash

# Install specific version
asdf install wash latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wash latest

# Now wash commands are available
wash --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yordis/asdf-wash/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Yordis Prieto](https://github.com/yordis/)
