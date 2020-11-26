1) Create a directory named "cdm" in your Kodi's home directory*
2) Extract the zip file containing your device's architecture in the "cdm" directory.
3) Make sure the "Decrypter path" is set to "special://home/cdm" in the InputStream Adaptive add-on settings.

* This is the directory that also contains "addons", "media", "system", "userdata" and more.

---------------------------------------------------------------------------------------------------

To use Widevine on an Android device you may need to manually install the required Widevine files by using adb,
you can install the required files by using "widevine-android-armv7-adb.zip" and follow those instructions:

1) Install Android ADB drivers if you are using Windows. (drivers can be found here: https://adb.clockworkmod.com/)
2) Extract the "widevine-android-armv7-adb.zip" zip file to your PC.

Android USB device:
3) Connect your Android device to your PC with the USB cable.

Android Network device:
3) Lookup your Android device's ip adres, if it cannot be connected to your PC by USB.
3.1) Open "adb-connect-device.bat" in a text editor, change the ip adres and save the file.
3.2) Now run "adb-connect-device.bat" and wait for it to connect to your Android device.

4) Once your device is connected run "adb-install-widevine.bat" and wait for it to complete.
5) Restart your device when you are ready to restart it.
6) Enjoy Widevine on your Android device*1

* You can use the app "DRM Info" found in the store to see if Widevine is installed.
*1 The installer is only tested with a rooted Android 5.xx, 6.xx and 7.xx device.