Custom Boot Screen, I left Marlin Boot Screen Enabled with TH3Dstudio.com 

  ![ezgif com-gif-maker](https://user-images.githubusercontent.com/105161928/172275333-c877394d-b229-4efc-8048-43fb26466d36.gif)

  
*TEMPERATURE RUNOUT DETECTION ON

*Linear Advance K value=0 (use M900 KX.XX in your starting code)

*Babystep resolution is 0.025mm

*Home Location is -10, -10

*Added default fix for screen artifacts which I can variate if required
just message with your screen model number and I'll do what I can.
 https://marlinfw.org/docs/basics/troubleshooting.html#graphical-lcd-artifacts

*PIDBED TUNING ENABLED - https://marlinfw.org/docs/gcode/M303.html

  ![cxvcxvcx](https://user-images.githubusercontent.com/105161928/172274680-0e98fe90-cbe3-4632-af30-e438587ac87e.png)

NOTE: It is HIGHLY recommended to use an external bed MOSFET with the CR-10 series machines due to the high load the beds have.
The V4.2.7 boards will work on 12V machines but they are designed for 24V printers that use less Amperage.
// If you need a MOSFET, 
buy one here: https://www.th3dstudio.com/product/high-amp-12v-24v-mosfet-heated-bed-or-hotend/

This FIRMWARE is based off TH3D.com Creality V4.x.  and Marlin 2. Firmware files with  an added custom bootscreen/status screen for fun. 
 It's provided for free so there is absolutely no warranty or guarantee that it will not damage your machine or work.
 I will do what I can to help fix any problems there may be and I’ll make changes to the firmware accordingly with no time guarantee.

Marlin offers two levels of thermal protection:

Check that the temperature is actually increasing when a heater is on. If the temperature fails to rise enough within a certain time period (by default, 2 degrees in 20 seconds), the machine will shut down with a “Heating failed” error. This will detect a disconnected, loose, or misconfigured thermistor, or a disconnected heater.
Monitor thermal stability. If the measured temperature drifts too far from the target temperature for too long, the machine will shut down with a “Thermal runaway” error. This error may indicate poor contact between thermistor and hot end, poor PID tuning, or a cold environment.

 

Donations are appreciated and will go towards getting better equipment to do more work for the open source community.

No less than 50% of donations will be re-donated back to the Teams at Th3D.com and Marlin.org

https://www.paypal.com/donate/?hosted_button_id=KYCXACAX5F2ML
                   
# creality Firmware: Bin Files For Easier Install
Open source firmware from TH3d.com that I've compiled into a bin format for an easier install. I was kind of surprised that no-one had them available so here they are.

Instructions:
1. Download Zip and extract the required file onto an empty SD card that has been formatted to FAT32

2. Power off the 3D printer and unplug the usb cord 
3. Insert the Sd card and power on your printer
4. Wait for the file to install automatically
5. After the boot screen loads RESET EEPROM through the advanced settings in the menu options
6. Make the required adjustment to the E-Step value through the advanced settings in the menu options
7. erase the file from your SD card before you use it

After Install:
You MUST MANUALLY RESET EEPROM USING ADVANCED SETTINGS WITHIN THE MENU OPTIONS. If you don't the settings will not work correctly.
Double check that your Axis and Extruder steps are correct and report any problems to https://github.com/Sci-Nc  so that I can fix the firmware.

![Free_Sample_By_Wix](https://user-images.githubusercontent.com/105161928/172274897-cb41bf87-13b8-4e86-bd6f-356c4ef7ac4d.jpeg)

RESOURCES:
https://marlinfw.org/docs/configuration/configuration.html#configuring-marlin
https://www.th3dstudio.com/estep-calculator/
https://cdn.prusa3d.com/downloads/drivers/PrusaSlicer_Win_standalone_2.4.2.exe#_ga=2.43694501.1675382600.1654555695-1794174945.1654223607
