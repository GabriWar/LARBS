# Gabriwar's Auto-Rice Bootstrapping Scripts (GARBS?)

## Installation:

On an Arch-based distribution as root, run the following:

```
sh garbs.sh
```
or if youre using an nvidia GPU:
```
sh garbsn.sh
```
That's it.


## Options
- `-r`: custom dotfiles repository (URL)
- `-p`: custom programs list/dependencies (local file or URL)
- `-a`: a custom AUR helper (must be able to install with `-S` unless you
  change the relevant line in the script


## TODO:
- add coolbits config as default in the nvidia installer (gives more control over things)
- ...
