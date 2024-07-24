# ROGUEOUTCAST1BEAMWASH

## Software Versions

[V1.240718 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/bd2ace8f8e3b25fde061694296d64dad27f1a02a/firmware/V1.240718.zip)
- Improved dimming performance
- Added separate ring and center LED power adjustment

[V1.230727 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.230727.zip)
- Added dimmer channel improvements

[V1.221103 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.221103.zip)
- Added 3-second delay to the LED On so that the LED only lights up 3 seconds after a full reset is performed

[V1.220822 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.220822.zip)
- Added new personalities

[V1.220311 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.220311.zip)
- Fixed bug that causes defrost fan to be always on

[V1.220217 - Rogue Oucast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.220217.zip)
- Improved Red Shift effect
- Fixed bug that causes the USB stick to be undetected when doing a USB upload

[V1.220112 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.220112.zip)
- Added Red Shift
- Fixed CTO control to be consistent across all fixtures

[V1.210211 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.211011.zip)
- Fixed minor bugs

[V1.210922 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.210922.zip)
- Corrected the version number

[V1.210831 - Rogue Outcast 1 BeamWash](https://github.com/Chauvet-Pro/ROGUEOUTCAST1BEAMWASH/blob/c9ca3661b85e0db7bde2020e72a10a8f42e59398/firmware/V1.210831.zip)
- Improved the color temperature consistency when dimming down

&nbsp; 

## USB Software Update Instructions
1.  Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message “***USB Update***” will be displayed. Press **< YES >**.
3.	The next screen will show the software versions available for this fixture on the USB drive. For multiple versions of the software for the same fixture, use **< UP >** or **< DOWN >** to select the desired version. Press **< ENTER >**.
4.	The ***"USB Update*** screen will re-appear. Press **< YES >**.
5.	The upgrade will start. DO NOT turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: ***"USB Update Wait"***. USB update can take several minutes to complete.
    > When the USB stops blinking, all the motors will power down, and the display will go blank. DO NOT turn off the power. The fixture will automatically reboot when the update is done.
6.  Go to **Sys Info** on the fixture's menu map and confirm the firmware revision.
7.	When the boot-up process is finished, restart the fixture.


### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the **UPLOAD 08** device to fix this. 
