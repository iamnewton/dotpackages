# dotpackages(1)

Typically software you buy comes with some sort of installer, why not your dotpackages? After manually setting up my dotpackages and installation for years, I decided to take a page from [some](https://github.com/necolas) [other](https://github.com/mathiasbynens) [people's](https://github.com/cowboy) [books](http://dotpackages.github.io) and set up a script that will configure my machine to run [ViM as an IDE](http://blog.sanctum.geek.nz/series/unix-as-ide/).  Along the way, I figured how to get all of the necessary [Homebrew](http://braumeister.org) & [Node](https://www.npmjs.org) packages installed as well as some useful [Ruby gems](http://rubygems.org). Feel free to [poke around](https://github.com/iamnewton/dotpackages/commits/main) the repository, [fork it](https://github.com/iamnewton/dotpackages/fork) to make it your own, [suggest things](https://github.com/iamnewton/dotpackages/issues?labels=feature+request) for me to include, [log a bug](https://github.com/iamnewton/dotpackages/issues/new), or maybe checkout the [features list](#features) to see what's included.

**N.B.** This project has a [Code of Conduct](./.github/CODE_OF_CONDUCT.md). By interacting with this repository, organization, and/or community you agree to abide by its terms.

## Installation

```bash
$ /bin/bash -c "$(curl -#fL https://raw.githubusercontent.com/iamnewton/dotpackages/main/bin/dotpackages)"
```

:exclamation: N.B. If you wish to [fork this project](https://github.com/iamnewton/dotpackages/fork) and maintain your own, you **MUST** substitute my username for your own in the above command and the variable (`$USERNAME`) found at the top of the `bin/dotpackages` script.

### Requirements

If you're on MacOS then you already have these, but a Linux system may not come with all:

* [curl](http://curl.haxx.se)
* [git](http://git-scm.com)

If you use the installation command above, then no need to worry as it will handle all of the dependencies for you, so it's best advised to use, but the following are also required if you plan to manually install and run the CLI.

* [homebrew](http://brew.sh)
* [node](http://nodejs.org)/[npm](https://www.npmjs.org)

## Features

There are several package installations handled via Homebrew & NPM that are listed in the [wiki](https://github.com/iamnewton/dotpackages/wiki). If you want to modify what is installed by default, removing or adding is possible by updating the package in the appropriate file.  Each package is stored in the `opt` directory and named for the package management software that is used.

:exclamation: N.B. Each package should be on a new line.

### Package Management libraries

* [Homebrew formulae](https://github.com/iamnewton/dotpackages/wiki/Homebrew)
* [Node packages](https://github.com/iamnewton/dotpackages/wiki/Node)
