# WMR-Screen-Resolution-Script
Automatically starts WMR, sets all applicable monitors to 1080p, and resets settings back when WMR closes.

This is a automation of the script made here: https://github.com/kevdevrev/WMRHelperScripts. The main difference is that this script will launch WMR portal and then auto detect monitors connected to your PC with greater resolution or refresh rate than 1080p 60z, and set them all to 1080p. When WMR portal is closed the script will automatically reset all monitors to their previous resolutions and terminate.

**NOTE: This script requires C++ Redistributible https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0**

## Installation

 - Clone the repository to any directory on your PC
 - Download the `ChangeScreenResolution.exe` file from http://tools.taubenkorb.at/change-screen-resolution/
 - Move the `ChangeScreenResolution.exe` to the folder you cloned
 - Run the `Start WMR With Fix.bat` file
