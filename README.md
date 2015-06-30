# Kodi For Video
This remote aim to control [Kodi](http://kodi.tv/). I'm inspire from [Yatse](https://play.google.com/store/apps/details?id=org.leetzone.android.yatsewidgetfree) another android application. 

## Features
* Some
* Features
* Listed
* Here

## Requirements
* [Kodi](http://kodi.tv/)

## Setup
### Kodi Setup
After installing it you must configure Kodi for beeing controlled by Unified Remote.

1. Launch Kodi.  
2. Go to "System" → "Service" → Web Server.
3. Check "Allow control of Kodi via HTTP".
4. You can change the Port number. But it's important to configure the remote command with the same port.

### Unified Remote
Inside the folder "KodiForVideo", there is a file "settings.prop". You can configure the following parameters (all values are default):

- host: localhost
- kodiPath: %programfiles(x86)%\\Kodi\\Kodi.exe
- pathForThumbnail: nothing (*currently disable because of perf problem*)
- playerId: none (*information retrieve from Kodi*)
- port: **80**
- status: stop (*this is a variable for the remote command)*
- trace: 0 (*disable/enable tracing*)   

## Feature


## Download
[Remote Name](&lt;link&gt;) use "file upload" to get link

## Github
You can find the project [here](https://github.com/yuyuki/KodiForVideo).

## Screenshots
![Main](http://i.imgur.com/luZF7QP.png = 250px)
![Playback](http://i.imgur.com/ElX7cGS.png)
![Source](http://i.imgur.com/JNYZPYV.png)
![Library](http://i.imgur.com/FjE2k29.png)