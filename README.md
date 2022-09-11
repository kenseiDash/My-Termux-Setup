# My-Termux-Setup
<h1 align="center">
    <img src="https://i.ibb.co/KwccR6Z/k.png">
</h1>


## Install

pkg install x11-repo

pkg update && pkg upgrade -y

pkg install git -y

 
bash





## Desktop Interface XFCE

pkg install tigervnc

pkg install xfce4-terminal

pkg install xfce4

vncserver

vncserver -kill :1

cd .vnc

nano xstartup

#!/bin/sh
unset SESSION_MANAGER
unset DBUS_SESSION_BUS_ADDRESS
exec startxfce4

chmod +x ~/.vnc/xstartup





## Startup

vncserver :1  -geometry 1600x720
