

### Getting debug info via logcat
#### With a computer:
- connect the device via USB
- open command prompt/terminal
- enter `adb logcat > logcatOutput.txt` to save the output to this file

**Note:** You must have [adb](https://developer.android.com/studio/releases/platform-tools.html) installed first!

#### On a device (with root)
- open terminal app *(can be enabled in developer options)*
- get root access via "su"
- enter `logcat -d -f /sdcard/logcatOutput.txt`

or 

- use [CatLog](https://play.google.com/store/apps/details?id=com.nolanlawson.logcat) or [aLogcat](https://play.google.com/store/apps/details?id=org.jtb.alogcat)

**Note:** Your device needs to be rooted for this approach!

## Development version


## Support

If you need assistance or want to ask a question about the Android app, you are welcome to [ask for support](https://help.nextcloud.com/c/clients/android) in our Forums or the [IRC-Channel](https://webchat.freenode.net/?channels=nextcloud-mobile). If you have found a bug, feel free to [open a new Issue on GitHub](https://github.com/nextcloud/android/issues). Keep in mind, that this repository only manages the Android app. If you find bugs or have problems with theserver/backend, you should ask the [Nextcloud server team](https://github.com/nextcloud/server) for help!

## Remarks

Google Play and the Google Play logo are trademarks of Google Inc.
