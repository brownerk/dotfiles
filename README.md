# egorvdot's dotfiles
## Contents

What's in there?

Environment configurations for my workstations.

I use MacOS as main workstation and Ubuntu, CentOS as servers.


## Structure

- [`configs`](https://github.com/egorvdot/dotfiles/tree/issue-0-init/configs) - dotfiles for utilities
- [`meta`](https://github.com/egorvdot/dotfiles/tree/issue-0-init/meta) - dotbot and its configs for configuring utilities
- [`os`](https://github.com/egorvdot/dotfiles/tree/issue-0-init/os) - environment initializers for OS-es

Environment initializer uses `profile` with the list of dotbot's configs.


## Installation

I am using [`dotbot`](https://github.com/anishathalye/dotbot/)
to set things up.

Steps for initializing of environment:

1. Clone this repo
2. `cd` into `os/<os name>` folder
3. Run: `./install`

Steps for the installation custom configuration:

1. Clone this repo
2. Run `./install-standalone <configurator-name> ...`

   For example, `./install-standalone dotbot` updates all submodules of this repository.
