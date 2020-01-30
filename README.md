# dotgit.git
This repository contains a useful, intelligent Git configuration and a number of helpful aliases and commands.

## Installation
This directory is meant to be the directory `~/.config/git`, as might be created by

```
$ cd
$ mkdir -p .config
$ cd .config
$ git clone git@gitlab:laristra/dotgit git
```

The last command fails if such a directory already exists; you'll have to merge the contents.
That command is also an example of the utility of this configuration: it allows omitting the `git@` on such commands for several hosts.

Git automatically looks for `~/.config/git/config` in _addition_ to `~/.gitconfig` since version 1.7.12; values in the latter file take precedence.
This allows personal settings (at least `user.name` and `user.email`) to be maintained without editing the common configuration file.

Also add `bin` to `PATH` to enable the `git-` scripts.

## Documentation
The aliases in `config` and the commands have explanatory comments; the latter also have at least a usage message.
