<div align="center">

# asdf-uv [![Build](https://github.com/b1-luettje/asdf-uv/actions/workflows/build.yml/badge.svg)](https://github.com/b1-luettje/asdf-uv/actions/workflows/build.yml) [![Lint](https://github.com/b1-luettje/asdf-uv/actions/workflows/lint.yml/badge.svg)](https://github.com/b1-luettje/asdf-uv/actions/workflows/lint.yml)

[uv](https://github.com/astral-sh/uv) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add uv
# or
asdf plugin add uv https://github.com/b1-luettje/asdf-uv.git
```

uv:

```shell
# Show all installable versions
asdf list-all uv

# Install specific version
asdf install uv latest

# Set a version globally (on your ~/.tool-versions file)
asdf global uv latest

# Now uv commands are available
uv --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/b1-luettje/asdf-uv/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [b1-luettje](https://github.com/b1-luettje/)
