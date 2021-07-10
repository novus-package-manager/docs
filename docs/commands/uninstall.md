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

The letter `u` can be used as a alternative shortcut to `uninstall`.

Example:

```bash
novus u brave
```

## Flags

### verbose

Displays verbose during uninstallation.

Alias: -v

Example

```bash
novus uninstall brave --verbose
```

### no-color

Turns off colored output during uninstallation.

Alias: -nc

Example

```bash
novus uninstall brave --no-color
```

### no-progress

Disables progress bar during uninstallation.

Alias: -np

Example

```bash
novus uninstall brave --no-progress
```
