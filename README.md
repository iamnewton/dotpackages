# dotpackages(1)

A set of packages I tend to use when setting up a new computer.

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

If you use the installation command above, then no need to worry as it will handle the dependencies for you, so it's best advised to use, but the following are also required if you plan to manually install and run the CLI.

* [homebrew](http://brew.sh)
* [node](http://nodejs.org)/[npm](https://www.npmjs.org)

## Packages

Check out the [README in `/opt`](./opt/README.md) for a list of packages.
