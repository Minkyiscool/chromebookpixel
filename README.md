# Chromebook Pixel 2013
The Chromebook Pixel is a premium and in-house-made laptop that was released by Google in 2013 to display how much can be achieved through using the ChromeOS system. The Chromebook Pixel has an impressive 12.85 inch 3:2 ratio touch screen. The laptop, despite being constructed from aluminum, has very high prices up to around $1299 (£1050 UK).
Lots of people decide to install different operating systems, and this is what this guide can tell you about, as ChromeOS is no longer supported on this laptop.

# How do you install new OS's?
Before you continue, back up your data for any last changes, get an external mouse/keyboard, and prepare a USB with the OS you are installing.
This will require the WP screw being taken off from the back. The full guide for that is on [IFixIt](https://www.ifixit.com/Guide/Remove+the+Write+Protect+Screw/86362).

⚠️ **Warning**:
This process will erase data and modify firmware. Proceed at your own risk.

## Enable Developer Mode
1. Turn on the Pixel and hold down ESC + REFRESH, then press the power button.
2. Once you see the message "Chrome OS is missing or damaged.", press CTRL+D.
3. When you get "To turn OS verification off, press Enter.", press ENTER.
## Developer Shell
1. If you get another warning screen, press CTRL+D again.
2. Proceed with the setup, but right after you finished setting up your network, do NOT create a user account.
3. Instead, hold CTRL + ALT keys and press the -> button, this should bring up a terminal-style prompt.
4. Your login password is 'CHRONOS', then you should have all the administrative permissions.
## Mr. Chromebox Script
1. Run the command from [Mr. Chromebox Website](https://mrchromebox.tech/#fwscript).
2. Select the "Install/Update Full ROM Firmware" option in the menu, and you can choose to backup or not.
## You're done!
Now you can plug in your USB and run the installer with the UEFI!

# Supported Operating Systems

## Windows 10/11
<img src="https://github.com/user-attachments/assets/4eaccc86-6803-4ebe-98a2-58763981f6b8" alt="Windows" width="300" align="right">
Installing Windows on this Chromebook can be challenging, as you will need to be careful around battery, storage, and other hardware issues.

If you would like to install Windows 10, it will work as normal, but Windows 11 is not supported on this Intel CPU anymore so Tiny11 is more preferred.

Drivers for everything are in this zip file: [Google Drive Link](https://drive.google.com/file/d/1z29b-zFvfzYjM029l6L_Bj65GnFo2YcO/view?usp=sharing)
