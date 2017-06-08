# bind-serialupdater
Make http://www.vim.org/scripts/script.php?script_id=2445 compatible with vundle/pathogen/Plug and some small changes

## Installation
Add
```
Plug 'f-breidenstein/bind-serialupdater'
```
to your ~/.vimrc or ~/.config/nvim/init.vim and call ":PlugInstall"

## Usage
Your serial should be formated in the format **YYYYMMDD##** where:
- YYYY is the year
- MM is the month
- DD is the day and
- ## is a number between 00 and 99

To update the serial of a currently opened zonefile just execute
```
:call UpdateDNSSerial()
```
or add a shortcut to your .vimrc like this to bind the function to F6
```
map <F6> :call UpdateDNSSerialZone()<CR>
```

