# OpenWindowsSound

This repository contains a simple batch file that opens the Windows Sound settings window directly, making it easy to access and select a playback device with just a click. This is especially useful when the playback device icon is missing from the bottom-right corner of the desktop or when the device is disabled.

## How to Use

### Option 1: Using the Provided Batch File
1. Clone the repository or download the batch file.
   ```
   git clone https://github.com/hsuehyt/OpenWindowsSound.git
   ```
2. Navigate to the folder where the batch file is located.
3. Double-click the `openSoundSettings.bat` file to open the Windows Sound settings window directly.

### Option 2: Create a Desktop Shortcut (Alternative Method)
1. **Right-click on your desktop** and select **New > Shortcut**.
2. In the location field, enter:
   ```
   C:\Windows\System32\mmsys.cpl
   ```
   This points directly to the Sound Control Panel.
3. Click **Next**, then name the shortcut something like **"Sound Settings"** and click **Finish**.
4. Now, you can double-click the desktop shortcut to open the Sound settings window.

## Screenshot

![Sound Settings Window](https://github.com/hsuehyt/OpenWindowsSound/blob/main/Readme/Screenshot.png)

This shows the Windows Sound settings that will open when running the batch file or the shortcut.

## Why Use This?

- **Quick Access**: Instead of navigating through multiple menus, you can quickly open the sound settings and select your preferred playback device.
- **Device Missing?**: If the playback device icon is missing from the system tray at the bottom-right corner of your desktop, this shortcut will still open the Sound settings, allowing you to select or enable a device.
- **Device Disabled?**: If your device is disabled, you can enable it directly from the Sound settings window after running the batch file or using the shortcut.