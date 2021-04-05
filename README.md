# ACCT Toolbelt

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)

[![Version](https://img.shields.io/npm/v/acct-cli.svg)](https://npmjs.org/package/acct-cli)

[![Downloads/week](https://img.shields.io/npm/dw/acct-cli.svg)](https://npmjs.org/package/acct-cli)

[![License](https://img.shields.io/npm/l/acct-cli.svg)](https://github.com/luizgamabh/acct-cli/blob/master/package.json)



[toc]

## Usage

```bash
$ npm install -g acct
$ acct COMMAND
running command...
$ acct (-v|--version|version)
acct-cli/0.0.1 win32-x64 node-v14.2.0
$ acct --help [COMMAND]
USAGE
$ acct COMMAND
...
```
# Commands

- [`acct help [COMMAND]`](#acct-help-command)
- [`acct generate [WHAT]`](#acct-generate-what)
- [`acct zip [FILE]`](#acct-zip-file)

## `acct help [COMMAND]`

display help for acct toolbelt

```bash
USAGE
$ acct help [COMMAND]
ARGUMENTS
 COMMAND command to show help for
OPTIONS
 --all see all commands in CLI
```

## `acct generate [WHAT]`

ACCT scaffold command

```bash
USAGE
$ acct generate [WHAT]
OPTIONS
 -f, --force   Force rewriting existing file with same name
 -h, --help    show CLI help
 -n, --name=name file name
```

_See code: [src\commands\generate.ts](https://github.com/luizgamabh/acct-cli/blob/v0.0.1/src\commands\generate.ts)_

## `acct zip [FILE]`

Generates zip file into .releases directory of your current project based on latest tag

```bash
USAGE
$ acct zip [FILE]
OPTIONS
 -f, --force
 -h, --help    show CLI help
 -n, --name=name name to print
```

_See code: [src\commands\zip.ts](https://github.com/luizgamabh/acct-cli/blob/v0.0.1/src\commands\zip.ts)_
