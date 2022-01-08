<div align="center">

# asdf-bottom ![Build](https://github.com/barolab/asdf-bottom/workflows/Build/badge.svg) ![Lint](https://github.com/barolab/asdf-bottom/workflows/Lint/badge.svg)

[bottom](https://github.com/ClementTsang/bottom) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`.

# Install

Plugin:

```shell
asdf plugin add bottom
# or
asdf plugin add bottom https://github.com/barolab/asdf-bottom.git
```

bottom:

```shell
# Show all installable versions
asdf list-all bottom

# Install specific version
asdf install bottom latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bottom latest

# Now bottom commands are available
btm --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/barolab/asdf-bottom/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Romain Bailly](https://github.com/barolab/)

# Credits

This repository was heavily inspired from [asdf-exa](https://github.com/nyrst/asdf-exa)
