<div align="center">

# asdf-az2aws [![Build](https://github.com/kuma0128/asdf-az2aws/actions/workflows/build.yml/badge.svg)](https://github.com/kuma0128/asdf-az2aws/actions/workflows/build.yml) [![Lint](https://github.com/kuma0128/asdf-az2aws/actions/workflows/lint.yml/badge.svg)](https://github.com/kuma0128/asdf-az2aws/actions/workflows/lint.yml)

[az2aws](https://github.com/kuma0128/az2aws) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add az2aws
# or
asdf plugin add az2aws https://github.com/kuma0128/asdf-az2aws.git
```

az2aws:

```shell
# Show all installable versions
asdf list-all az2aws

# Install specific version
asdf install az2aws latest

# Set a version globally (on your ~/.tool-versions file)
asdf global az2aws latest

# Now az2aws commands are available
az2aws --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kuma0128/asdf-az2aws/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [kuma0128](https://github.com/kuma0128/)
