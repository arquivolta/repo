# repo

Arch Linux PKGBUILD files for core Arquivolta packages

## Rebuilding full repo

```sh
PKGDEST=/path/to/repo ./build-all --sign
cd /path/to/repo
repo-add ./arquivolta.db.tar.gz *.zst --sign
```
