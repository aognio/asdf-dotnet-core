# 🚧 asdf-dotnet-core

[![Build Status](https://travis-ci.org/emersonsoares/asdf-dotnet-core.svg?branch=master)](https://travis-ci.org/emersonsoares/asdf-dotnet-core)

.Net Core plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add dotnet-core https://github.com/emersonsoares/asdf-dotnet-core.git
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of .Net Core.

You can specify a DotNet installation channel by setting up the `DEFAULT_DOTNET_CORE_CHANNEL` environment variable
that defaults to `STS` (Standard-Term Support)

```
DEFAULT_DOTNET_CORE_CHANNEL="LTS" asdf install dotnet-core latest
```

See https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core for more information.

## DOTNET_ROOT
To set DOTNET_ROOT in your shell's initialization add the following:

`. ~/.asdf/plugins/dotnet-core/set-dotnet-home.bash`

For zsh shell, instead use:

`. ~/.asdf/plugins/dotnet-core/set-dotnet-home.zsh`

For fish shell, instead use:

`. ~/.asdf/plugins/dotnet-core/set-dotnet-home.fish`
