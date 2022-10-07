<div align="center">

# asdf-test [![Build](https://github.com/starkers/asdf-test/actions/workflows/build.yml/badge.svg)](https://github.com/starkers/asdf-test/actions/workflows/build.yml) [![Lint](https://github.com/starkers/asdf-test/actions/workflows/lint.yml/badge.svg)](https://github.com/starkers/asdf-test/actions/workflows/lint.yml)


[test](https://github.com/starkers/test) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add test
# or
asdf plugin add test https://github.com/starkers/asdf-test.git
```

test:

```shell
# Show all installable versions
asdf list-all test

# Install specific version
asdf install test latest

# Set a version globally (on your ~/.tool-versions file)
asdf global test latest

# Now test commands are available
ggg --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/starkers/asdf-test/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Stark](https://github.com/starkers/)
