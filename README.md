# Pomander
> */pōˈmandər,ˈpōˌmandər/* (noun) -
> a ball or perforated container of sweet-smelling substances such as herbs and spices, placed in a closet, drawer, or codebase to perfume the air or (formerly) carried as a supposed protection against infection.

## System Requirements

You need a working copy of npm, the package manager that comes bundled with [Node.js](https://nodejs.org/en/).

Using npm, install standard:

```
npm install -g standard
```

## Installation
Within a git repository, run the following command:
```sh
curl -s https://raw.githubusercontent.com/focusloop-official/pomander/master/bin/install | bash
```

## Usage
Pomander uses a pre-commit hook to run staged JavaScript files through StandardJS before each commit. Thanks to Hack Reactor for the original version of Pomander.

[StandardJS](http://standardjs.com/) is a popular linter that checks your code for syntax and style errors with zero configuration necessary.

To skip Pomander, commit with the `--no-verify` option.
