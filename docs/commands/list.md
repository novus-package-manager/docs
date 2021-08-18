---
sidebar_position: 4
---

# List

Lists all packages avaialable.

## Usage

List packages easily using novus with just a single command.

You can list a certain number of packages with

```bash
novus list [number]
```

## Alias

The word **show** can be used as an alternative to **list**.

Example:

```bash
novus show 10
```

## Flags

### all

Displays all packages available.

Alias: -a

Example

```bash
novus list --all
```

### version

Displays the package version along with the names.

Alias: -v

Example

```bash
novus list 10 --version
```

### installed

Displays only installed packages.

Alias: -i

Example

```bash
novus list 10 --installed
```

### local

Displays only local packages

Alias: -l

Example

```bash
novus list 10 --local
```
