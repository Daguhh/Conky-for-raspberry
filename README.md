# Conky-for-raspberry
get raspberry info throught ssh and display it in a simple conky + bash script to automate command like sshfs, vnc...

3 files :
1 bash script on server machine (raspberry)
1 bash script for client
1 conky file


How it works :
just run bash client script, it will : 
  1 invoke bash server script => produce txt containing raspberry info 
  2 get txt file over ssh
  3 create conky
  4 enter loop, ask user for option or update every 120 sec
      1 mount
      2 VNC
      3 exit
      
      
