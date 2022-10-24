# projectofthemonth: About
Every month (or just when I have the time to update), a new very-interesting-often-open-source project is dropped here as well as instructions on how to make it work. Look at it when bored, and come back irl with more determination.

It is not intended to steal other's projects, or anything else, it is just to promote the project of others! All projects are owned by their own authors whom I'm not, so go give their repo a star and all is thanks to them! Also all projects have their own licenses so go check them out before installing anything!
Also don't hesitate to follow the project's guidelines, go on their page, mine is just here for convenience and can be outdated!
All in all sorry for bad english.

## October 2022

OK let's start this. For this month, just get this awesome project:
```https://github.com/Swordfish90/cool-retro-term```
That'll get you covered in term of terminal personalisation for linux.
If you like old-school termials, hacker terminal, futuristic-style terminal, or just custom a terminal yourself, you're gonna be very happy.

#### For advanced geeks who want to compile themself:
###### Prerequisites

A linux distro on amd64 architecture, git and the base development program for your distro installed, and an admin account.

* Arch linux:
```sh
sudo pacman -Syu --needed git base-devel qt5-base qt5-declarative qt5-quickcontrols qt5-graphicaleffects
```

* Debian:
```sh
sudo apt install git build-essential qmlscene qt5-qmake qt5-default qtdeclarative5-dev qml-module-qtquick-controls2 qml-module-qtgraphicaleffects qml-module-qtquick-dialogs qml-module-qtquick-localstorage qml-module-qtquick-window2 qml-module-qt-labs-settings qml-module-qt-labs-folderlistmodel
```

* Ubuntu 20.04 and above:

You will need these packages in addition to the ones above.

```sh
sudo apt install qtquickcontrols2-5-dev qml-module-qt-labs-platform qml-module-qtquick-controls qml-module-qtquick-layouts qml-module-qtquick-localstorage
```

* Fedora:
```sh
sudo dnf -y install qt5-qtbase qt5-qtbase-devel qt5-qtdeclarative qt5-qtdeclarative-devel qt5-qtgraphicaleffects qt5-qtquickcontrols redhat-rpm-config && sudo ln -s /usr/lib64/qt5/bin/qmake /usr/bin/qmake
```

###### Install
(Check if instructions are still relevant at ```https://github.com/Swordfish90/cool-retro-term/wiki/Build-Instructions-(Linux)```)

```sh
# Get it from GitHub
git clone --recursive https://github.com/Swordfish90/cool-retro-term.git
# Go to the folder
cd cool-retro-term/
# Always look around before installing anything!
ls
# Build & compile
qmake && make
# Have fun!
./cool-retro-term
```

#### For less geeky
* Debian (also ubuntu)
```sh
sudo apt install cool-retro-term
```

* Arch linux
```sh
sudo pacman -Syu cool-retro-term
```
## November 2022
Check out my project on how to apply updates automatically on any linux system here: 
Should be usefull for all sysadmins!
