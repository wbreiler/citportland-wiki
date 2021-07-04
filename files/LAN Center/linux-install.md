# Linux Install Guide
![linux in a nutshell](https://media.giphy.com/media/4Zgy9QqzWU8C3ugvCa/giphy.gif)

## Installing Steam on Ubuntu:
To install the Steam launcher, make sure you have `multiverse` repository enabled by running `$ sudo add-apt-repository multiverse` and update your apt cache by running `$ sudo apt update`. Once your apt cache is updated, install it by running `$ sudo apt install steam`. Once it's installed, open the Applications Menu and open Steam and log in.

## Installing Epic Games on Ubuntu:
To install Epic Games, you're going to have to do some other things first.
- 1. Install Wine
    * Enable 32-bit architecture: 
        * `$ sudo dpkg --add-architecture i386`
    * Download Wine's repository key: 
        * `$ wget -nc https://dl.winehq.org/wine-builds/winehq.key`
    * Add the repository key to your system:
        *  `$ sudo apt-key add winehq.key`
    * Add the repository to your system: 
        * `sudo apt-add-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ focal main'`
    * Update your apt cache and install the latest version of Wine: 
        * `$ sudo apt update`
        * `$ sudo apt install --install-recommends winehq-stable`
- 2. Install Lutris
    * Add the Lutris PPA:
        *  `$ sudo add-apt-repository ppa:lutris-team/lutris`
    * Update your apt cache and install the latest version of Lutris:
        * `$ sudo apt update`
        * `$ sudo apt install lutris`