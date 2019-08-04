# python_static_mini
A static-prebuilt version of Python2.7 for ARM-V7 devices



Usage for android devices:

1. adb push python_static_mini/ /data/python

2. adb remount

3. adb shell "mv /data/python/python /system/bin"

4. adb shell sync

5. run set_env.sh after adb shell

