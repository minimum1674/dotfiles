# minimum/aegnx's dotfiles
TL;DR: minimal project, aimed at appearance, but has functionality
## just a quick word before we start
i tried to be as minimal as possible while including the essentials.
if you want to tell me if something is wrong my dms are open on discord (``aegnx.``).
i tried this on arch, and it is super successful.
i reccomend installing kde plasma and running it once before i3-wm, because it downloads and does all the essentials to get a working system without a problem.
aight time for the tutorial
## for the experienced people:
get the packages ```starship i3-wm polybar picom rofi``` 
if you dont have git installed run this
```
sudo pacman -S --needed base-devel git
```
and just put these into your .config folder like below
```
git clone https://github.com/minimum1674/dotfiles
cd dotfiles
cp config/* ~/.config/ 
```
done! restart and enjoy
**if you are on other distros use your own package manager instead of pacman and install git your way**
## the tutorial
## 1. getting the packages
### 1-1. a fresh arch install
if you are a newbie

after you are in the tty and you are done setting up networkmanager, install the group ``plasma`` with this command
```
sudo pacman -S plasma
```
dont worry, it does not include any bloat because its not the ``kde`` group, its the ``plasma`` group.

then, get your drivers set up

***OR***

if you already have a desktop environtment, you're already there

***OR***

if you are an arch pro

get the ``i3-wm polybar starship picom rofi pipewire`` packages after you are done configuring 
### 1-2. other operating systems
you need to get 
```
i3-wm polybar picom rofi
```
from your package manager, if you dont know what your package manager is and you have neofetch installed, run
```
neofetch --config=none | grep Packages
```
you will get an output like
```
                                         Packages: 1060 (pacman)
```
pacman is your package manager, flatpak and snap dont count

then, get searching to find some documentation on how to install the things up there
## 2. get those config files there
***still not done, gonna come back and finish it***
