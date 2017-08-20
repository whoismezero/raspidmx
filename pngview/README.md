# pngview

Utility to display a PNG image on the Raspberry Pi screen using the Dispmanx windowing system. Press Esc key to exit. Use 'w', 's', 'a' and 'd' keys to move the image on screen. Use '+' and '-' keys to change the number of pixels the image moves (default is 1).

If in non-interactive mode (-n): Set a timeout in milliseconds to run for a certain time, e.g: "-t 3000" to run for 3 seconds. (Not setting a timeout, or setting the timeout to zero "-t 0" will run indefinitely.)

    Usage: pngview [-b <RGBA>] [-d <number>] [-l <layer>] [-x <offset>] [-y <offset>] <file.png>

    -b - set background colour 16 bit RGBA
         e.g. 0x000F is opaque black
    -d - Raspberry Pi display number
    -l - DispmanX layer number
    -x - offset (pixels from the left)
    -y - offset (pixels from the top)
    -n - non-interactive mode
    -t - timout (in milliseconds)

