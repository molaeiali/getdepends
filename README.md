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
