<div align="center">

# asdf-anchor [![Build](https://github.com/suicide/asdf-anchor/actions/workflows/build.yml/badge.svg)](https://github.com/suicide/asdf-anchor/actions/workflows/build.yml) [![Lint](https://github.com/suicide/asdf-anchor/actions/workflows/lint.yml/badge.svg)](https://github.com/suicide/asdf-anchor/actions/workflows/lint.yml)

[anchor](https://github.com/coral-xyz/anchor) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add anchor
# or
asdf plugin add anchor https://github.com/suicide/asdf-anchor.git
```

anchor:

```shell
# Show all installable versions
asdf list-all anchor

# Install specific version
asdf install anchor latest

# Set a version globally (on your ~/.tool-versions file)
asdf global anchor latest

# Now anchor commands are available
anchor --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/suicide/asdf-anchor/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [suiiii](https://github.com/suicide/)
