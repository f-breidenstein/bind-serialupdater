# bind-serialupdater
Make http://www.vim.org/scripts/script.php?script_id=2445 compatible with vundle/pathogen and some changes

## Installation
Add
```
Bundle 'fbreidenstein/bind-serialupdater'
```
to your .vimrc and call ":BundleInstall"

## Usage
Your serial should be formated in the format **YYYYMMDD##** where YYYY is the
year, MM is the month, DD is the day and ## is a nukber between 00 and 99.

To update the serial of a currently opened zonefile just execute
```
:call UpdateDNSSerial()
```
or add a shortcut to your .vimrc

