# fix-bricked-jb4

For when I forget..

example using board: JB4_x55 Rev 3.0

B48/B58 firmware

Bricked on a normal USB serial cable update


To fix it in a TL866

Load the latest hex firmware file in the TL866 program

Then either manually set the configuration bits to match the image file in here, or put in a working JB4 PIC and read the config bits only.

Then write to the PIC

The user config/settings will all be garbage but at least the PIC & JB4 should work again now
