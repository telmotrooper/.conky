# My Conky config

## Setup
* Install Conky with either `sudo pacman -S conky` (Arch Linux) or `sudo apt-get install conky` (Debian/Ubuntu)
* Copy the files in this repository to `~/.conky` ("README.md" and "screenshot.png" can be safely skipped)
* Run `~/.conky/run_conky.sh`

## Starting with the computer
For the widgets to start with your computer you have to add `~/.conky/run_conky.sh` to your startup applications. This process is different between desktop environments, it might be as simple as searching for "startup applications" in your menu and adding it to the list.

## My network stats (download, upload and local IP) do not show
For these stats to work, you need to replace all the occurrences of "enp6s0" in "network_panel" with the name of your current network interface. You can find the names of the interfaces available with `ifconfig`, which you might or might not have installed.

## Screenshot
![](https://raw.githubusercontent.com/telmotrooper/.conky/master/screenshot.png)
