# Connect Android
As script used to connect your android device to adb over wifi.

Steps for setup:
1) Download the `connect_android` file.

2) Make sure that `adb` location has been added to your `PATH`. [Here](https://www.xda-developers.com/adb-fastboot-any-directory-windows-linux/) are instructions on how that is done.

3) Connect your device via usb cable. To verify it is connected, you can use the command:
```bash
adb devices
```

4) If needed change permissions on `connect_android` for bash script to work:
```bash
chmod +x connect_android
```

5) Run the script `connect_android`.

6) *optional* Setup [scrcpy](https://github.com/Genymobile/scrcpy) if you want to use the optional scrcpy argument. You can then use `scrcpy` as an argument.

```bash
connect_android scrcpy
```
