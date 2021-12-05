# choco

> A command-line interface for the Chocolatey package manager.
> Some subcommands such as `choco install` have their own usage documentation.
> More information: <https://chocolatey.org>.

- Display all locally installed packages:

`choco list --local-only`

- Install one or more space-separated packages:

`choco install {{package(s)}}`

- Install packages from a custom configuration file:

`choco install {{path/to/packages.config}}`

- Search for a package:

`choco search {{query}}`

- Display a list of available features:

`choco feature list`

- Execute Chocolatey command:

`choco {{command}}`

- Call general help:

`choco -?`

- Call help on a specific command:

`choco {{command}} -?`

- Check the Chocolatey version:

`choco --version`