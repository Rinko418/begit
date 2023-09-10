# Begit

## Begit CLI

A small CLI wrapper for `@begit/core`

## Installation

Run `npm i -g @begit/cli` to install. Invoke with `begit`

## Usage

For a comprehensive list of features, use the help command as below:

```bash
begit --help
```

Which will print something like:

```bash
begit

ARGUMENTS:
  <URL>         - The URL to clone
  [Destination] - a string [optional]

OPTIONS:
  --subdir, -s <str> - a string

FLAGS:
  --help, -h - show help
```

### Cloning a repositoy

To clone a repository to the current working directory, simply:

```bash
begit Tommypop2/begit
```

URLs are also accepted:

```bash
begit https://github.com/Tommypop2/begit
```

You can also specify the desired branch via a `#`:

```bash
begit Tommypop2/begit#main
```

## From javascript

A smaller and lighter degit alternative with typescript support
