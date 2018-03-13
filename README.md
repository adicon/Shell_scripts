# My shell scripts

## second_display
###Enable a second virtual display on Linux

This is just a shell script that enable the possibility to connect a remote device - like tablets or smartphones - to a Linux machine to achieve the functionality of a second display connected in parallel to the main one. The simple case use is with a laptop out of office when you need a second display: you can use just yout tablet and this simple shell script.

It function enlarging the virtual size of the current active display (doubling in width) and starting VNC daemon (x11vnc required) on the idden part. Once you are connected with your mobile device as a VNC client, you can drag application windows back and forward from the main screen to the remote one.


