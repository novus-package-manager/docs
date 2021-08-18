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

The letter **i** can be used as an alternative shortcut to **install**.

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

### portable

Installs a portable version of the package if it exists.

Alias: -p

Example

```bash
novus install atom --portable
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

### multithreaded

Enables multithreaded download for faster installation.

Alias: -m

Example

```bash
novus install brave --multithreaded
```
