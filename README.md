# adb install -r Automator Service
This is a simple _Automator Service_ for MacOS that runs `adb install -r` in an apk in Finder. Right-click an apk and go to _Services > Install APK -r_.

It sends a notification when finished and also says "sucess" or "failure" plus the failure reason.

To install, simply copy `Install APK -r.workflow` to your `~/Library/Services` folder.

**Atention**: You'll probably need to update the adb path in the script: double click the workflow file to open it in Automator and edit it using your path to adb. To find out where adb is installed, try `adb --version` in Terminal.
