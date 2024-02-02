# General Settings <br> ALL ACTIONS ARE PERFORMED AT YOUR OWN RISK!

### Disabling User Account Control

In the search, type "Control Panel", select small icons. Go to "User Accounts", "Change User Account Control settings", change to "Never notify".
<br><br>

### Control Panel

UPD: Don't forget to apply!
Select small icons, choose "Ease of Access Center":
Uncheck "Always read this section aloud" and "Always scroll this section".

- Image Optimization on the screen - uncheck all checkboxes.
- Keyboard Ease of Access:<br>
  / Pointer Control Settings - uncheck all checkboxes and below NUM LOCK: disable;<br>
  / Keyboards Sticky Keys Settings - uncheck all checkboxes;<br>
  / Input Filtering Settings - uncheck all checkboxes.
- Use text or visual images instead of sounds - select "No".
- Ease of Access to Touch Panels and Tablets - change "Screen Reader" to "No" (If there is no tablet and there are no restrictions on hearing and vision).
  <br><br>

### Disabling Disk Indexing.

UPD: ATTENTION! Takes a long time.
Open "This PC", right-click on the disk (C:) "Properties", uncheck "Allow files on this drive to have contents indexed" - "Apply" / "to drive and all subfolders" / "skip all".
<br><br>

### List of services that can be disabled in Windows (work in automatic mode)

UPD: Services are collected from Windows 10-11, some of them may not be on version 10 or 11, take this factor into account.<br>
Designations:<br>
(•) - disabling only for experienced users.<br>
(\*) - services that can be disabled.<br>

| #   | Service Name                                     | Property                                                                     |
| --- | :----------------------------------------------- | :--------------------------------------------------------------------------- |
| \*  | Microsoft Update Health Service                  | If you have uninstalled the Microsoft Update Health Service program          |
| \*  | Superfetch or SysMain                            | Can be disabled if SSD is used and RAM size is more than 8GB                 |
| •   | Windows Remediation Service                      | If you don't use Windows updates                                             |
| •   | Windows Search                                   | If you don't search for files using search                                   |
| •   | Windows Biometric Service                        | If passwords, PIN codes, fingerprints, Windows Hello are not used            |
| •   | System Guard Runtime Broker                      | If integrity checking of system files is not used                            |
| \*  | IP Helper                                        | If IPv6 protocol is not used                                                 |
| \*  | Print Spooler                                    | If there is no printer and printing functions are not used, including to PDF |
| \*  | Remote Access Connection Manager                 | If remote access via VPN is not used                                         |
| \*  | Downloaded Maps Manager                          | If Windows maps are not used                                                 |
| •   | Web Account Manager                              | If Microsoft Store and applications downloaded from it are not used          |
| •   | CNG Key Isolation                                | If passwords, PIN codes, fingerprints, Windows Hello are not used            |
| \*  | Data Usage                                       | If traffic information is not used                                           |
| •   | Connected User Experiences and Telemetry Service | If NTFS file movement in a local network is not used                         |
| •   | NetBIOS TCP/IP Helper Service                    | If local network is not used                                                 |
| \*  | Delivery Optimization                            | If Windows updates are not used                                              |
| \*  | Microsoft Account Sign-in Assistant              | If you don't use Microsoft products                                          |
| \*  | Sync Host                                        | If Windows Mail is not used and not signed in with a Microsoft account       |
| \*  | Sensor Data Service                              | If Windows-controlled tablet is not used                                     |
| \*  | Sensors                                          | If Windows-controlled tablet is not used                                     |
| •   | Windows Font Cache Service                       | If Microsoft Office is not updated                                           |
| \*  | Client License Service (ClipSVC)                 | If Microsoft Store and applications downloaded from it are not used          |
| \*  | Sensor Monitoring Service                        | If Windows-controlled tablet is not used                                     |
| •   | Connected Devices Platform Service               | If not used: Virtual desktops, Timeline, Your Phone, and Night Light         |
| •   | User Device Registration Service                 | If not used: Virtual desktops, Timeline, Your Phone, and Night Light         |
| \*  | Storage Service                                  | If Microsoft Store and applications downloaded from it are not used          |
| •   | Diagnostic Service Host                          | If computer diagnostics at the operating system level are not used           |
| \*  | User Experience Virtualization                   | Collection and tracking of data by Microsoft company                         |
| \*  | Windows Update Service                           | If Windows updates and Microsoft Store are not used                          |

<br>

### Fixing Automatic Brightness Adjustment

Information for laptops with Intel processors:
If you experience brightness fluctuations when disconnecting from the power cable, you need to open "Intel Graphics Control Panel", select "System", "Power", and in the "Display Power Saving" section, turn off the toggle switch.
<br><br><br><br><br><br><br><br><br><br>

# Windows 10 <br> ALL ACTIONS ARE PERFORMED AT YOUR OWN RISK!

### Disabling Windows Firewall or Windows Defender Notifications.

Press Win + R, type regedit and press Enter.<br>
In the path: Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender Security Center\Notifications<br>
In the empty window, right-click, create "DWORD (32-bit) Value" and name it DisableNotifications.<br>
Then open the parameter by double-clicking and set the value to 1, apply and restart the PC.
<br><br>

### Configuring System Properties

UPD: Don't forget to apply!<br>
This PC, right-click, properties.<br>
In the context menu, open "Advanced system settings"

- Computer Name / Optionally if you want another name.
- Advanced / Performance, you can disable everything, but it doesn't significantly affect the system, you can use "Adjust for best appearance" even on weak PCs.
- System Protection / Local Disk (C:)(System) Enable protection! Allocate 7-12GB of memory.
- Remote Desktop (If you don't want any connections to the PC from outside, you can disable it.)
  <br><br>

### SETTINGS Program

#### 1. System

- Notifications & Actions (Can be disabled as desired) / and there is a section to edit quick action tiles, you can set it up as needed.
- Focus Assist (recommended for experienced users)
  Turn off all toggles and checkboxes. And in the same menu, "Set up priority list", Turn off the toggles and remove all applications.
- Power & Sleep, set the values you need / In the same menu "Additional power settings", it will open the power management panel - where you can set high performance (on a laptop, battery consumption will be higher).
- Memory / Turn off "Memory integrity feature".
- Tablet or Tablet Mode (Apply if the screen is not touch-sensitive) - never use tablet mode / Ask before switching modes. There is also a "Change additional tablet settings" option, where you turn off all toggles.
- Multitasking - turn off timeline.
- Shared experiences - turn off "Let apps on other devices open and message app".
- Clipboard - turn off all toggles and clear data. UPD: (Clipboard will also work when using Ctrl + C).

#### 2. Personalization

- Colors / Turn off transparency effects.
- Lock Screen - turn off all toggles.
- Themes / Desktop icon settings, you can enable icons "This PC" and "Recycle Bin".

#### 3. Apps

- Apps & Features - uninstall pre-installed programs that are not needed.
- Default Apps, you can set what is necessary.
- Offline Maps - turn off all toggles and use "Delete all maps".
- Startup - you can disable programs that start when the PC is turned on.

#### 4. Gaming

- Xbox Game Bar - turn off all toggles and checkboxes.
- Captures - if you don't use screen recording, turn off all toggles and checkboxes.
- Game Mode - turn on.

#### 5. Accessibility

- Narrator - turn off all toggles and checkboxes (if narrator is not used).
- Speech - turn off all toggles and checkboxes.
- Keyboard - turn off all toggles and checkboxes.
- Mouse - turn off all toggles and checkboxes.

#### 6. Privacy

UPD: Don't forget to click on "Change" and then turn the toggle on or off according to the situation.

- General - turn off all toggles except "Let Windows track app launches".
- Voice Activation - turn off all toggles.
- Handwriting Personalization - turn off all toggles.
- Diagnostics & Feedback - check "Required diagnostic data". Then turn off all options. Feedback frequency (Never). Delete diagnostic data.
- Activity History - turn off all toggles and checkboxes. Clear activity history.

TURN ON ALL PERMISSIONS OR TURN OFF ALL PERMISSIONS IN THESE SETTINGS:
| Permission Name | Action |
|:---------------------------|------------|
| Location | TURN ON |
| Camera | TURN ON |
| Microphone | TURN ON |
| Voice Activation | Turn off |
| Account Info | Turn off |
| Contacts | Turn off |
| Calendar | Turn off |
| Phone Calls | Turn off |
| Call History | Turn off |
| Email | Turn off |
| Tasks | Turn off |
| Messaging | Turn off |
| Radios | Turn off |
| Other Devices | Turn off |
| Background Apps | Turn off |
| App Diagnostics | Turn off |
| Automatic File Downloads | SKIP |
| Documents | TURN ON |
| Pictures | TURN ON |
| Videos | TURN ON |
| File System | TURN ON |
<br>

#### 7. Update and Security

- Windows Update Center, inside the "Additional settings" section, turn off all toggles. And inside "Delivery Optimization", disable the option to download from other computers.
  <br><br>

### Disabling Microsoft Defender

To disable Microsoft Defender, you need to open "Settings" / "Update & Security" / "Windows Security" / "Open Windows Security service".
"Virus & threat protection" / "Manage settings" and turn off all toggles.
UPD: after restarting the PC, Defender will be enabled again.
<br><br><br><br><br><br><br><br><br><br>

# Windows 11 <br> ALL ACTIONS ARE PERFORMED AT YOUR OWN RISK!

### Configuring System Properties

UPD: Don't forget to apply!
This PC, right-click, properties.
Settings will open, look for "related links" and open "Advanced system settings"

- Computer Name / Optionally, if you want another name.
- Advanced / Performance, you can disable everything, but it doesn't significantly affect the system, you can use "Adjust for best appearance" even on weak PCs.
- System Protection / Local Disk (C:)(System) Enable protection! Allocate 7-12GB of memory.
- Remote Desktop (If you don't want any connections to the PC from outside, you can disable it.)

---

### SETTINGS Program

#### 1. System

- Notifications (Can be disabled as desired), but it's better to leave it.
- Power & Sleep, set the values you need / In the same menu "Power mode", set to "Best performance" (on a laptop, battery consumption will be higher).
- Memory / Turn off "Memory integrity feature".
- Nearby sharing - turn off (If online connection between PC and smartphone is not used).
- Troubleshoot - change to "Ask me before running".
- Clipboard, turn off "Clipboard history" and clear data. UPD: (Clipboard will also work when using Ctrl + C).

#### 2. Personalization

- Colors / Turn off transparency effects.
- Themes / Desktop icon settings, you can enable icons "This PC" and "Recycle Bin".
- Lock Screen / Turn off all checkboxes and toggles. Lock screen status - "Nothing".
- Start / Use "More pins". Turn off all toggles.
- Taskbar / You can disable all toggles as desired.
- Device usage / Turn off all toggles.

#### 3. Apps

- Installed apps - uninstall pre-installed programs that are not needed.
- Default Apps, you can set what is necessary.
- Offline Maps - turn off toggles. Remove the checkmark from "Automatically update".
- Startup - you can disable programs that start when the PC is turned on.

#### 4. Gaming

- Xbox Game Bar - turn off.
- Captures - if you don't use screen recording, turn off all toggles.
- Game Mode - turn on.

#### 5. Accessibility

- Narrator - turn off all toggles and checkboxes (if narrator is not used).
- Speech - turn off all toggles and checkboxes.
- Keyboard - turn off all toggles and checkboxes. UPD: "Use the PrtSc key to open Snipping Tool" you can leave it as desired.
- Mouse - turn off all toggles and checkboxes.

#### 6. Privacy

- General - turn off all toggles except "Let Windows track app launches".
- Voice Activation - turn off all toggles.
- Handwriting Personalization - turn off all toggles. "Clear the custom dictionary".
- Diagnostics & Feedback - turn off all toggles, and Delete diagnostic data. Feedback frequency (Never).
- Activity History - turn off all toggles. Clear activity history.

TURN ON ALL PERMISSIONS OR TURN OFF ALL PERMISSIONS IN THESE SETTINGS:

| Permission Name          | Action   |
| :----------------------- | -------- |
| Location                 | TURN ON  |
| Camera                   | TURN ON  |
| Microphone               | TURN ON  |
| Voice Activation         | Turn off |
| Notifications            | TURN ON  |
| Account Info             | Turn off |
| Contacts                 | Turn off |
| Calendar                 | Turn off |
| Phone Calls              | Turn off |
| Call History             | Turn off |
| Email                    | Turn off |
| Tasks                    | Turn off |
| Messaging                | Turn off |
| Radios                   | Turn off |
| Other Devices            | Turn off |
| App Diagnostics          | Turn off |
| Automatic File Downloads | SKIP     |
| Documents                | TURN ON  |
| Downloads Folder         | TURN ON  |
| Music                    | TURN ON  |
| Pictures                 | TURN ON  |
| Videos                   | TURN ON  |
| File System              | TURN ON  |
| Screen Snip              | TURN ON  |
| Screenshots and Apps     | TURN ON  |

<br>

#### 7. Windows Update Center

- "Additional settings" turn off all toggles. And inside "Delivery Optimization", disable the option to download from other computers.

---

### Disabling Microsoft Defender

To disable Microsoft Defender, you need to open "Settings" / "Privacy & security" / "Windows Security" / "Open Windows Security service".
"Virus & threat protection" / "Manage settings", turn off all toggles.
UPD: after restarting the PC, Defender will be enabled again.
