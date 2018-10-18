# Apple-Automatic-Appearance-Mode-Switcher-for-Nighttime
Applescript to switch the appearence mode from light to dark on macOS Mojave automatically during nighttime


## Installation
- download the apple script
- open it with Script-Editor
- set t1 and t2 to wanted start and end times for light mode
- export the script as stay-open application
- in the info.plist file of the application insert the following lines to run the application in the background
  ```
  <key>LSBackgroundOnly</key>
  <string>1</string>
  ```
  (see: https://groups.google.com/forum/#!topic/macenterprise/vn2zVFHh3HA)
- add the application to your startup applications
