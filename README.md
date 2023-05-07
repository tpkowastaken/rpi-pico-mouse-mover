# Rpi pico mouse mover
hardware mouse mover script using curcuitpython that moves the mouse a bit. Useful for always staying online in microsoft teams or other apps
# Inspiration
I took the code from [raspi-mouse-jiggler](https://github.com/TomasHubelbauer/raspi-mouse-jiggler) but added an led to it. Also I found it pretty difficult for a begginer to know what he's doing so I made it simplier and smaller here.
# How to use
1. Install [circuitpy](https://circuitpython.org/board/raspberry_pi_pico/) on the rpi pico. You can do this simply by holding the bootsel button when plugging the rpi and then putting the .uf2 file inside the rpi pico directory (on the disk that was mounted). Note: if You installed Anything on this rpi pico previously you have to wipe it first by putting [flash_nuke.uf2](https://github.com/dwelch67/raspberrypi-pico/raw/main/flash_nuke.uf2) into the same directory.
2. copy the files from here to rpi pico ([adafruit_hid](https://github.com/adafruit/Adafruit_CircuitPython_HID/tree/main/adafruit_hid) to lib)
3. replug the rpi
4. Your mouse should be now jiggling just a bit but that's enough for microsoft teams or other software that might detect afk. In case it doesn't work you can increase the "shift" value in the main.py file. It's nice to have it instead of software solutions in case of your laptop being managed by your corporation.
