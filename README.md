 Please report issues resulting from this download to
https://github.com/Sci-Nc


This FIRMWARE is based of TH3D.com Creality V4.x.  and Marlin 2. Firmware files with  an added custom bootscreen/status screen for fun. 
 It's provided for free so there is absolutely no warranty or guarantee that it will not damage your machine or work.
 I will do what I can to help fix any problems there may be and I’ll make changes to the firmware accordingly with no time guarantee.
 <div class="container-fluid"> <div class="row alert alert-warning custom-alert"> <div class="col-lg-1 col-md-2 visible-lg-block visible-md-block custom-alert-icon"> <i class="fa fa-exclamation-circle fa-4x" aria-hidden="true"></i> </div> <div class="col-lg-11 col-md-10 custom-alert-text"> <p>It is crucial to obtain accurate temperature measurements. As a last resort, use 100k thermistor for <code class="language-plaintext highlighter-rouge">TEMP_SENSOR</code> and <code class="language-plaintext highlighter-rouge">TEMP_SENSOR_BED</code> but be highly skeptical of the temperature accuracy.</p> </div> </div> </div>
 *Added default fix for screen artifacts which I can adjust if this does not work for you
 https://marlinfw.org/docs/basics/troubleshooting.html#graphical-lcd-artifacts

*PIDBED TUNING ENABLED - https://marlinfw.org/docs/gcode/M303.html

*TEMPERATURE RUNOUT DETECTION ON - 

*Linear Advance K value=0 (use M900 KX.XX in your starting code for this feature)
*Babystep resolution is 0.025mm
*Home Location is -10, -10


All Donations for GNU work are appreciated and will go towards getting better equipment to do more work for the open source community.

*No less than 50% of your donation will be re-donated back to the folks at Th3D.com and Marlin.org

https://www.paypal.com/donate/?hosted_button_id=KYCXACAX5F2ML
                   
# creality Firmware: Bin Files For Easier Install
Open source firmware from TH3d.com compiled into bin format for easier install.




Instructions:
1. Download Zip and extract the required file onto an empty SD card that you know is working
2. Power off the 3D printer and unplug the usb cord 
3. Insert the Sd card that has your file
4. Power on the 3D printer and wait for the file to install automatically
5. After the boot screen loads power off the 3D printer and remove the sd card
6. erase the file from your SD card before you use it

After Install:
Reset your EEPROM. If you don't the settings may not work correctly
Double check that your Axis and Extruder steps are correct and report any problems to https://github.com/Sci-Nc  so that I can fix the firmware for everyone.
https://www.th3dstudio.com/estep-calculator/

