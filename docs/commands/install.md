---
sidebar_position: 1
---

# Install

Installs a package or a list of packages.

## Usage

Install packages easily using novus with just a single command.

You can find the list of packages by running

```bash
novus list
```

## Alias

The letter `i` can be used as a alternative shortcut to `install`.

Example:

```bash
novus i brave
```

## Versioning

Novus allows you to install a specific version of any package.

This is made extremely easy by suffixing the package name with `@<version>`

Example

```bash
novus i brave@1.25.66
```

## Flags

### verbose

Displays verbose during installation.

Alias: -v

Example

```bash
novus install brave --verbose
```

### no-color

Turns off colored output during installation.

Alias: -nc

Example

```bash
novus install brave --no-color
```

### no-progress

Disables progress bar during installation.

Alias: -np

Example

```bash
novus install brave --no-progress
```
