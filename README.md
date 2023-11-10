# Gabriwar's Auto-Rice Bootstrapping Scripts (GARBS?)


## Features 
- hghly customizable
- EXTREMELY LOW resourece usage (RAM usage usually sits around 700 MB when idle and 1 to 3GB when browsing)
- light installation size (less than 8 GB if packages are modified)
- easy to make shortcuts
- no need for a mouse or trackpad
- easy to use
- simple but beautiful design
- perfect for low-end or older hardware
- focused on security, privacy, and usability


![memory usage](https://raw.githubusercontent.com/GabriWar/LARBS/master/pic-full-231110-2148-44.png)
![BTOP](https://raw.githubusercontent.com/GabriWar/LARBS/master/pic-full-231110-2149-16.png)


## Installation:

On an Arch-based distribution as root, run the following:

```
sh garbs.sh
```
(EXPERIMENTAL!!!!!)or if youre using an nvidia GPU:
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
- make sure it istalls nviia drivers (just download it form the nidia website and exectue it without starting x, dont autoconfig the x config)
- auto runs steam using gamemoderun
- make easier to use mangohud (maybe a shortcut)
