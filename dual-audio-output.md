# Play music on both headphones and speaker!
This is about how I discovered that android can play media from both speaker and headphone line

## Reproduced on:
- Device: Redmi Note 11 4G (spes)
- OS: `ParanoidAndroid` aka `AOSPA` Topaz 4 (Android 13)
- Along with these apps:
  - [RootlessJamesDSP](https://github.com/timschneeb/RootlessJamesDSP) (package name me.timschneeberger.rootlessjamesdsp, version 1.6.14)
  - Google Clock (package name com.google.android.deskclock, version 8.5 - 853571623)
  - [AIMP](https://www.aimp.ru/) (package name com.aimp.player, version v4.31.1744 - 24.08.2026)

## Steps
- Change sound profile to Vibrate
- Plug-in in your headphones
- Play a song
- Go inside RootlessJamesDSP and turn it on
- Go to Google Clock and set up an alarm at the next minute
- Wait for the alarm to trigger (Music stop) and turn it off
- Music should be resumed and now sound output out of both speaker and headphone :D
