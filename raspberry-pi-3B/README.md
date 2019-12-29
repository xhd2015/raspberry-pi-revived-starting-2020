# About
This directory contains a tutorial on how to startup raspberry pi 3 in a display-less mode.

# Flush system image
Refer to 
# Edit the config.txt
add the following lines
```txt
dtoverlay=disable-bt
boot_delay=5
``` 
# cmdline.txt
replace all `console=` parameters with `console=/dev/ttyAMA0,115200`.

# connect
Then connect the raspberry pi 3B to the PC that installed the driver,and wait for 5 seconds,you will see output.
