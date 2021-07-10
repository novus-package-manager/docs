---
sidebar_position: 3
---

# Update

Updates a package or a list of packages to their latest versions.

## Usage

Updates packages easily using novus with just a single command.

You can find the list of packages installed by running

```bash
novus list --installed
```

## Alias

The word **upgrade** can be used as an alternative to **update**.

Example:

```bash
novus upgrade brave
```

## Flags

### verbose

Displays verbose while updating.

Alias: -v

Example

```bash
novus update brave --verbose
```

### no-color

Turns off colored output while updating.

Alias: -nc

Example

```bash
novus update brave --no-color
```

### no-progress

Disables progress bar while updating.

Alias: -np

Example

```bash
novus update brave --no-progress
```
