# Firmware
This is a repository I made to share compiled Marlin 2.0.8 firmware for the Ender 3 pro with creality 4.2.7 board.

This firmware was compiled from the standard settings from the marin Github repository for the ender 3 pro 4.2.7 board. I made no edits to the firmware perameters. This is for a stock ender3 pro with the upgraded 4.2.7 main board.

I made this due to the frustraion with the copiled firmware provided by creality. Their firmware which is marked "Marlin 2.0" is in actuality Marlin 1.0 and cannot support newer features such as G02 and G03 arc commands. 

I do not take credit for the creation of any code or adjustment of any perameters within the firmware. I am only attempting to save other hobbiests the headache that I went through dealing with Creality's mismarked firmware.

INSTRUCTIONS

1. Load the inclued .bin file onto a blank micro SD card. (Some microSD cards have been reported to not work well for this. The microSD card included with your printer should work fine.)
2. Turn off your ender 3 pro.
3. Insert the microSD card with the firmware .bin file into your Ender 3 pro.
4. Turn on the ender 3 pro. (It should take longer to boot up than normal ~20 seconds)

You can check if the firmware was properly installed by viewing the info screen. It should say the Marlin version is 2.0.8. If it does not, rename the firmware .bin file and try installing it again. 
