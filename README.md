# pacaur-safe-updater
A little script to define versions of packages wich compromise your system and prevent them to get installed.

This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

## Usage:

Edit the script and enter the names and versions of the packages you don't want to install into the array. 

You have to copy the file e.g. to $HOME/bin and make it executable if it is not yet.

Then you can easily run
```
pacaur-safe-updater
```
instead of
```
pacaur -Syu
```
