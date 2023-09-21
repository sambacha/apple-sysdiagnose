# iOS Sysdiagnose (Using AssistiveTouch) 

## 1. For general iOS issues, please gather a sysdiagnose.

## 2. Enabling Logging Using AssistiveTouch

1. Enable AssistiveTouch by going to Settings > Accessibility $>$ Touch > AssistiveTouch.

- Notice the floating home button that appears on the screen.

2. Go to Settings $>$ Accessibility $>$ Touch $>$ Customize Top Level Menu.
3. Select Custom > Analytics. A small checkmark $(\checkmark)$ will appear next to your selection.
4. Reproduce the issue. Important: Note the date and time issue occurred and add this information to your report.
5. Trigger a sysdiagnose by using the CUSTOM ACTION you selected above. (Example: Double-Tap).

## 3. Notes:

- A gray bar will appear along the top indicating that the log gathering has started, and another will appear when its complete.
- It can take up 10 minutes for the diagnostic gathering to complete.

6. Once logging has completed, sync the device with your host computer or AirDrop the file to your Mac computer.
7. Attach the file listed at the path below under Log Locations to your report.

## 4. Notes:

- It's very important to note the date and time you reproduced the issue in your report.
- If applicable, please provide the name(s) of the affected app(s) in your report.
- Trigger the sysdiagnose as soon as possible after the problem occurs, even if the logs can't be synced until later.


## 5. Log Locations

## 6. iOS:

Go to: Settings.app > Privacy > Analytics \& Improvements > Analytics Data >

Locate the sysdiagnose file and AirDrop it to your Mac. Scroll down, if necessary, to the point where you see the sysdiagnose with today's date, tap on that file and then tap the box with an arrow in it at the top right. Then choose the Mac device to send it to from the list of devices that appear in the AirDrop area. Once the transfer is complete (this may take several minutes), the file will be located in the /Users/[Your Username]/Downloads folder. The name will be similar to this: "sysdiagnose_YYYY.MM.DD_HH-MM-SS-XX..."

## 7. macOS:

/Library/Logs/CrashReporter/MobileDevice/[Your_Device_Name]/DiagnosticLogs/sysdiagnose

Note: " /Library/..." actually translates to: /Users/[Your User Name]/Library/... The "/Users/[Your User Name]/Library/..." folder is hidden by default in macOS. To expose the folder, hold the option key while clicking the Finder's Go menu and the Library folder will appear in the menu. Any time you see a placeholder like "[Your Device Name]" or, "[Your User Name]" you should replace that part of the path with your actual device's name, or your computer user name.

## 8. Windows 10:

![](https://cdn.mathpix.com/cropped/2023_09_21_28a1f1301325985e4b97g-1.jpg?height=48&width=1751&top_left_y=2101&top_left_x=130)
Computer \Logs $\backslash$ CrashReporter $\backslash$ MobileDevice

## 9. Windows 8, 7, Vista:

C: \Users \[Your_User_Name]\AppData \Roaming \Apple Computer \Logs \CrashReporter \MobileDevice [Your_Device_Name]\DiagnosticLogs \sysdiagnose

Note: The AppData folder in Windows 8 is hidden by default. Click on the View menu item in a Windows navigation window and check the "Hidden items" checkbox and the AppData folder will appear in the list of folders under C:|Users|[Device_Name]. Important: Replace "[Your_Device_Name]" or "[Your_User_Name]" in the file paths above with the actual device name for the iOS device, or the actual user name you use on your computer.


