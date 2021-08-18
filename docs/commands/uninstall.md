---
sidebar_position: 2
---

# Uninstall

Uninstalls a package or a list of packages.

## Usage

Uninstall packages easily using novus with just a single command.

You can find the list of installed packages by running

```bash
novus list --installed
```

## Alias

The letter **u** can be used as an alternative shortcut to **uninstall**.

Example:

```bash
novus u brave
```

## Flags

### portable

Uninstalls a portable version of the package if it exists.

Alias: -p

Example

```bash
novus uninstall atom --portable
```

### no-color

Turns off colored output during uninstallation.

Alias: -nc

Example

```bash
novus uninstall brave --no-color
```
