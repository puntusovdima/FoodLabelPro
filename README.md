# FoodLabelPro

# Licensing

This software is proprietary and protected by copyright law.

Commercial Use: This software is not licensed for commercial use without a paid license. If you or your organization wish to use this software for commercial purposes, please visit https://www.google.com/search?q=https://hakero.com/pricing to purchase a license.

Personal Use: This software is provided for personal, non-commercial use only. The source code is provided for educational and review purposes and may not be copied, modified, or redistributed without explicit written permission.

Unauthorized use, reproduction, or distribution of this software is strictly prohibited. The full terms of our End-User License Agreement (EULA) can be found at https://www.google.com/search?q=https://hakero.com/eula.

Installation

End-User (Standard)

Download: Get the latest .apk file from the Releases page.

Enable "Install from Unknown Sources": Before installing, you may need to go to your device's settings to allow installations from sources other than the Google Play Store.

Install the APK: Open the downloaded .apk file from your device's file manager or notifications to begin the installation.

Wait for Play Protect: After installation, Android's Play Protect will automatically scan the app for safety. Once the scan is complete, you can open and use the application.

Developer / Kiosk Mode (via ADB)

For developers or setting up dedicated kiosk devices, you can install and set the device owner using the Android Debug Bridge (ADB):

# Install the application
./adb install FoodLabelPro.apk

# Set the app as device owner for kiosk mode
./adb shell dpm set-device-owner com.example.firebaselabelapp/.kiosk.KioskDeviceAdminReceiver


Features

Local, online databases

Smart import with adding to the same category

Wide range of TSPL printers support (Wi-Fi, Bluetooth, USB)

Built-in utility for testing Wi-Fi connection before printing

2/3 split main menu for fast navigation

Controls for label size, font, and printing density

Edit mode

Locked mode

Contact

For support, licensing inquiries, or other questions, please contact us at support@hakero.com or visit our website at https://hakero.com.
