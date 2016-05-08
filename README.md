# Prebuiltive

In order to run prebuiltive, first locate to the location of /Android/SDK/platform-tools on your computer, and open a command prompt window there. With your Android plugged in, run:
```
//Following directory locations and file names can all be changed:
adb push C:\users\manas\IdeaProjects\Prebuiltive\app\src\main\libs\armeabi\prebuiltive /data/local
```
If you're using your computer's terminal (Android teriminal emulators are set to shell by default), run:
```
adb shell
```
Now to change the file's permissions in order to run it:
```
//switch to directory
cd /data/local
//check permissions
ls -al
//change permissions
chmod 777 prebuiltive
//check changed permissions
ls -al
```
When that's all done, all that's now left is:
```
./prebuiltive
```
