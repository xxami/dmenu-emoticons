# dmenu_emoticons

## how does it work
1. bind "bash /path/to/dmenu_emoticons.sh" in window manager
2. choose an emoticon that dmenu show
3. select it and it will be copied and pasted into the active program

## what it needs to install
- dmenu 4.5 - http://tools.suckless.org/dmenu/
- clipboard.vala - http://p.rdw.se/clipboard.vala by
  [slaeshjag](http://github.com/slaeshjag/)
- xdotool - sudo apt-get install xdotool
- dmenu xft patch - http://tools.suckless.org/dmenu/patches/xft
- ja_JP.utf8 in locale -a (or edit dmenu_emoticons.sh)
- suitable japanese font (fonts-mona used by default)

## how to add own emoticons
add them to the lists in same format of dmenu_emoticons.sh

## bugs / problems
- font doesnt show some emoticons i have not found best one yet
- some emoticons break bash i dont know why i try to avoid them

## thanks to
- http://japaneseemoticons.net/ for most emoticons used here
- thank yuu to slaeshjag for clipboard.vala and help
- thank yuu to lodysama for linux help
