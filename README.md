<div align="center">

# asdf-argc [![Build](https://github.com/rgeraskin/asdf-argc/actions/workflows/build.yml/badge.svg)](https://github.com/rgeraskin/asdf-argc/actions/workflows/build.yml) [![Lint](https://github.com/rgeraskin/asdf-argc/actions/workflows/lint.yml/badge.svg)](https://github.com/rgeraskin/asdf-argc/actions/workflows/lint.yml)

[argc](https://github.com/sigoden/argc) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add argc
# or
asdf plugin add argc https://github.com/rgeraskin/asdf-argc.git
```

argc:

```shell
# Show all installable versions
asdf list-all argc

# Install specific version
asdf install argc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global argc latest

# Now argc commands are available
argc --argc-version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rgeraskin/asdf-argc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Roman Geraskin](https://github.com/rgeraskin/)
