# Klipper Config
My personal Klipper config for my Longer LK4 Pro. You will need to adjust things like the BLTouch offsets to match your printer.

# Known Issues
- Touchscreen is Landscape
- Abort/pause on the touchscreen dont work

# Components for a working LK4 Pro Klipper Install
- A raspberry pi running MainsailOS - https://github.com/raymondh2/MainsailOS
- Desuuuu's Klipper fork, including DGUS touchscreen support - https://github.com/Desuuuu/klipper 
- My fork of Desuuuu's DGUS touchscreen firmware(a work in progress, currently the same as Desuuuu's repo.) Plan to fix abort/pause buttons not working, and UI being landscape rather than portrait. - https://github.com/GeoCyberwolf/DGUS-reloaded-Klipper-LK4Pro
- The config files found here
- Time, patience and perserverence

# Stuff specific to my printer
 - Having a BLTouch installed, comment out the bltouch, bed_mesh, screws_tilt_adjust and homing_override sections if you do not have one.
 - The way my BLTouch is mounted, you will probably need to adjust your X, Y and Z offsets to suit your particular printer
