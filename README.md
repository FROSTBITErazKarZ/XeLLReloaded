XeLLReloaded
============

XeLL Reloaded v0.993
Disabled USB writes for the logfile (not working with EXT# anyways
Fixed the crashing when unplugging USB memories at runtime

v0.992 - 27/08/2013 * Released by a trigger happy Tuxuser *
! Corona video support !
* NTSC gives weird black/white screen
eMMC Reading support for Corona consoles (no flashing!)
* Not working when launched via XellLaunch
Rawflash verify features
Cygnos/DemoN builds included - 38400 UART baudrate
Logfile writing to USB or HTTP Webinterface
Dumps ANA-Registers to UART / Logfile
"Shutdown" and "Reboot" via HTTP Webinterface
Option to disable Network via xell config
Support for all 3 USB busses
* Crashing when USB is plugged out or attached at runtime
Switched from zlib to puff (smaller)
Support for mounting 1 USB memory device at runtime
Better support for big USB devices (or poorly formatted ones)

v0.991 - 19/02/2012
! Fixing booting of Linux Kernel on Reset Glitch Hack Consoles !
Write stackdump on fail to screen
additional offsets for reloading XeLL/updating XeLL-Reloaded
integrated cOz's rawflash application (look at README)
probably fixing freezing at "Reinit PHY..."
kboot.conf parsing (shows a menu inside XeLL, loads linux and homebrew elfs - look at README)
Fixing TFTP ACK on end of file
Fixing TFTP transfer for files with only 1 DATA block
Fixing possible buffer overflow when uncompressing gzipped file
dcbst the memory-range for Devtree and Initrd

23/09/2011
Fixed web interface download speed.
Fixed boot loop messages not clearing properly.
Added a 15 sec delay to have a chance to cancel updxell process.
Fixed ata init.
Libxenon improvements (controller leds,...).

01/09/2011
Initial Release of 2Stages XeLL Reloaded.
