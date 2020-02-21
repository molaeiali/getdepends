# Get Depends

A script that gets a binary and give it's dependencies on Arch Linux using ldd.

# Usage

```bash

getdepends [-i <input file path>] [-f <format output for PKGBUILD>] [-e <exclude core packages>] 

```


# Dependencies

```
core/glibc: For `ldd`
core/coreutils: For `sort`, `readlink`
extra/pkgfile: For `pkgfile`
```

# Installation

Install from [AUR](https://aur.archlinux.org/packages/getdepends/):
```bash
yay -S getdepends
```

# Attribution

Code is copied from this user: [edotux](https://unix.stackexchange.com/users/218253/edotux) on [stackexchange](stackexchange.com)
