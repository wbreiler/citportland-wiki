# Ubuntu Install Guide
<img src="https://i.imgur.com/q7GqrC9.gif" width="50%" height="50%"/>

## Installing Steam on Ubuntu:
To install the Steam launcher, make sure you have `multiverse` repository enabled by running `$ sudo add-apt-repository multiverse` and update your apt cache by running `$ sudo apt update`. Once your apt cache is updated, install it by running `$ sudo apt install steam`. Once it's installed, open the Applications Menu and open Steam and log in.

## Installing Epic Games on Ubuntu:
To install Epic Games, you're going to have to do some other things first.
- 1. Find your architecture version
    * Open a terminal (Ctrl + Alt + T) and run:
        * `$ uname -m`
- 2. If it is 64-bit (the output of the above command is `x86_64`), do the following:
    * Open a terminal (Ctrl + Alt + T) and run:
        * `$ wget https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher/releases/download/v1.8.1/heroic_1.8.1_amd64.deb`
    * Install it by running:
        * `$ sudo dpkg -i herotic_1.8.1_amd64.deb`
