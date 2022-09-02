

# Debloating Morotola G200

This is my "opinionated" debloating instruction

Prerequisites:
1. ADB installed on your computer

Steps:
1. Enable developer mode
2. Enable debugging mode via USB
3. Plug phone via USB to your computer
4. Open terminal and run these commands:


```sh
adb shell

pm uninstall -k --user 0 com.android.chrome

pm uninstall -k --user 0 com.google.android.apps.photos
pm uninstall -k --user 0 com.google.android.apps.chromecast.app
pm uninstall -k --user 0 com.google.android.apps.fitness
pm uninstall -k --user 0 com.google.android.apps.youtube.music.setupwizard
pm uninstall -k --user 0 com.google.android.apps.youtube.music
pm uninstall -k --user 0 com.google.android.apps.subscriptions.red
pm uninstall -k --user 0 com.google.android.apps.photos
pm uninstall -k --user 0 com.google.android.apps.podcasts
pm uninstall -k --user 0 com.google.android.apps.magazines
pm uninstall -k --user 0 com.google.android.apps.tachyon
pm uninstall -k --user 0 com.google.android.apps.wellbeing

pm uninstall -k --user 0 com.google.android.calendar
pm uninstall -k --user 0 com.google.android.googlequicksearchbox
pm uninstall -k --user 0 com.google.android.contacts
pm uninstall -k --user 0 com.google.android.googlequicksearchbox
pm uninstall -k --user 0 com.google.android.videos
pm uninstall -k --user 0 com.google.android.gm
pm uninstall -k --user 0 com.google.android.youtube

pm uninstall -k --user 0 com.google.android.syncadapters.contacts
pm uninstall -k --user 0 com.google.android.printservice.recommendation

pm uninstall -k --user 0 com.facebook.system
pm uninstall -k --user 0 com.facebook.appmanager
pm uninstall -k --user 0 com.facebook.katana
pm uninstall -k --user 0 com.facebook.services

pm uninstall -k --user 0 com.motorola.android.fmradio
pm uninstall -k --user 0 com.motorola.genie
pm uninstall -k --user 0 com.motorola.moto

```

