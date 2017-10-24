# xamarin-forms-android-linux-tools
Collection of command line tools for Xamarin.Forms Android on Linux

Please modify the config*.sh files first.

Use build.sh to build the entire Android application.

Use deploy.sh to copy the apk on Android emulator and run the application.

Use fast.sh to build the PCL and run the application (takes nearly 4-5 seconds on i5-2520M CPU).

NEW: use android-dll-fast.sh to build the Droid dll and run the application (first time it takes nearly 10 seconds, after that - 5 seconds).

NEW: clean.sh

NEW: xbuild.sh and xfast.sh - use it instead of build.sh and fast.sh where it fails with Net Standard libraries;

NEW: utils_debug_flag.sh - to see the number of a line (in logcat) if you have an Exception;

Use localize-app.sh to create the AppResources.designer.cs class file.

localize-base.sh is an example how to compile the second resx, for example, BaseResources.resx to the class file.

Documentation: https://goo.gl/mQvTJk (!)

More details about this experiment: https://xamarin-forms-linux.blogspot.com/
