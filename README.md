# Conky-for-raspberry
get raspberry info throught ssh and display it in a simple conky + bash script to automate command like sshfs, vnc...

3 files
1 bash script on server machine (raspberry)
1 bash script for client
1 conky file


How it works :

just run bash client script, it will

  1 invoke bash server script => produce txt containing raspberry info 
  
  2 get txt file over ssh
  
  3 create conky
  4 enter loop, ask user for option or update every 120 sec
      1 mount
      2 VNC
      3 exit
      
      ![screenshot](Mhttps://github.com/Daguhh/Conky-for-raspberry/blob/master/My_conkyPi.png?raw=true "Title")
      
[![Build Status](https://travis-ci.org/brndnmtthws/conky.png)](https://travis-ci.org/brndnmtthws/conky)

**Conky** is a free, light-weight system monitor for X, that displays
any kind of information on your desktop.

Grab the [latest release from GitHub](https://github.com/brndnmtthws/conky/releases/latest).

### Features

Conky can display more than 300 built-in objects, including support for:

 * A plethora of OS stats (uname, uptime, **CPU usage**, **mem
   usage**, disk usage, **"top"** like process stats, and **network
   monitoring**, just to name a few).
 * Built-in **IMAP** and **POP3** support.
 * Built-in support for many popular music players ([MPD][],
   [XMMS2][], [BMPx][], [Audacious][]).
 * Can be extended using built-in [**Lua**](lua) support, or any of your
   own scripts and programs ([more](Lua Interface)).
 * Built-in [**Imlib2**][Imlib2] and [**Cairo**][cairo] bindings for arbitrary drawing
   with Lua ([more](wiki/Lua-API)).

... and much much more.

Conky can display information either as text, or using simple progress
bars and graph widgets, with different fonts and colours.

### Screenshots

[![screenshot](https://github.com/brndnmtthws/conky/wiki/configs/brenden/screenshot-thumb.png)](https://raw.github.com/wiki/brndnmtthws/conky/configs/brenden/screenshot.png)
[![screenshot](https://github.com/brndnmtthws/conky/wiki/configs/ke49/screenshot-thumb.png)](https://raw.github.com/wiki/brndnmtthws/conky/configs/ke49/screenshot.png)
[![screenshot](https://github.com/brndnmtthws/conky/wiki/configs/jc/screenshot-thumb.png)](https://raw.github.com/wiki/brndnmtthws/conky/configs/jc/screenshot.png)

See the [User Configs](https://github.com/brndnmtthws/conky/wiki/User-Configs) section of the wiki for more
screenshots and their associated Conky config files.
