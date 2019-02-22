# CH_Manager_Win10Fix
Readme how to fix common CH Manager Windows 10 Problems

## Disable Powermanagement for CH USB Devices to fix Calibration Problems 

1. Open Device Manager in Windows 
2. Find the CH Products list and expand it 
3. For every device listed: 
 1. Right click, then click properties in the window for the device.  
 2. Click the Power Management tab, if there is one.  If not, just close the window and move to the next device 
 3. UNCHECK the box that says ***"Allow the computer to turn off this device to save power"***


## Fix for greyed out boxes in CH Manager

Another fix for CHM on Windows 10 is disabling the SysMain/Superfetch service, which interferes with CHM from activating properly.

The way to tell if ***SysMain/Superfetch*** is whats causing the buttons to grey out is just open the Windows Store app and all of a sudden CHM starts working again.

As a rule of Thump: It´s usually more ***SysMain*** on an AMD System and ***Superfetch*** Service on Intel System, your mileage may vary.
