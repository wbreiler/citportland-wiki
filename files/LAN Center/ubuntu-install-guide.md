# Ubuntu Install Guide
<img src="https://i.imgur.com/q7GqrC9.gif" width="512" height="512"/>

## Preface:
This guide is good for Ubuntu, as well as other Debian or Ubuntu based Linux distros. Some examples include Lubuntu, Xubuntu, Kubuntu, Linux Mint, Knoppix, and Deepin. You also **MUST** be comfortable using a command line to install packages.

## Installing Steam on Ubuntu:
1. Confirm that the `multiverse` Ubuntu repository is enabled by doing the following:
    * Open a terminal (Ctrl + Alt + T) and run:
        * `$ sudo add-apt-repository multiverse`
    * Update your apt repository cache:
        * `$ sudo apt update`
2. Install the Steam package:
    * Open a terminal (Ctrl + Alt + T) and run:
        * `$ sudo apt install steam`
3. Open the Applications menu and run Steam!


## Installing Epic Games on Ubuntu:
1. Find your architecture version
    * Open a terminal (Ctrl + Alt + T) and run:
        * `$ uname -m`
2. If it is 64-bit (the output of the above command is `x86_64`), do the following:
    * Open a terminal (Ctrl + Alt + T) and run:
        * `$ wget https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher/releases/download/v1.8.1/heroic_1.8.1_amd64.deb`
    * Install it by running:
        * `$ sudo dpkg -i herotic_1.8.1_amd64.deb`
3. Open the Applications menu, run Heroic, follow the on screen instructions, and play games!
