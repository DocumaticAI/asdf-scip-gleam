<div align="center">

# asdf-scip-gleam [![Build](https://github.com/DocumaticAI/asdf-scip-gleam/actions/workflows/build.yml/badge.svg)](https://github.com/DocumaticAI/asdf-scip-gleam/actions/workflows/build.yml) [![Lint](https://github.com/DocumaticAI/asdf-scip-gleam/actions/workflows/lint.yml/badge.svg)](https://github.com/DocumaticAI/asdf-scip-gleam/actions/workflows/lint.yml)

[scip-gleam](https://github.com/DocumaticAI/scip-gleam) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add scip-gleam
# or
asdf plugin add scip-gleam https://github.com/DocumaticAI/asdf-scip-gleam.git
```

scip-gleam:

```shell
# Show all installable versions
asdf list-all scip-gleam

# Install specific version
asdf install scip-gleam latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scip-gleam latest

# Now scip-gleam commands are available
scip-gleam --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/DocumaticAI/asdf-scip-gleam/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Documatic](https://github.com/DocumaticAI/)
