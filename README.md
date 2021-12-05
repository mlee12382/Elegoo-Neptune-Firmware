# Elegoo-Neptune-Firmware
These are the firmware files as downloaded from Elegoo's website prior to them changing the download to be incomplete and only include the elegoo.txt files. These will work for both ABL with a bltouch and to go back to manual bed leveling however you will need to modify elegoo.txt to go back to manual leveling prior to flashing. Change the following lines:
cfg_leveling_mode 0
BED_LEVELING_METHOD 5
That should return the firmware to manual leveling mode, other than that just follow the pdf instruction files for selecting the correct firmware for your machine.
