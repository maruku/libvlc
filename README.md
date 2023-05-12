Prebuild binary of libVLC: vlc-sdk.7z (Only armeabi-v7a is included)
- Specify DroidSansFallback.ttf as default fonts for Chinese subtitle 

## Note
VideoLAN provide official LibVLC binary release now, you can use it by adding this line to your project dependencies:
```
implementation 'org.videolan.android:libvlc-all:{THE-TAG-NAME}'
```
Go to https://code.videolan.org/videolan/vlc-android/-/tags to see the tag name

## Compile environment

### OS
Linux mark-VirtualBox 3.2.0-29-generic-pae #46-Ubuntu SMP Fri Jul 27 17:25:43 UTC 2012 i686 i686 i386 GNU/Linux

### Source version
#### VLC for Android (git://git.videolan.org/vlc-ports/android.git)

```
   tag 0.9.10
   Tagger: Jean-Baptiste Kempf <jb@videolan.org>
   Date:   Wed Oct 15 11:56:09 2014 +0200

   VLC for Android 0.9.10

   This release adds support for ARMv8 processors, limited Android-L acceleration,
   add support for keyboard, cleans the code and fixes minor issues.
   
   commit 630a95b1441df1e8fffab69c69169dc81679e073
   Author: Jean-Baptiste Kempf <jb@videolan.org>
   Date:   Wed Oct 15 11:55:18 2014 +0200
```

### Config
ANDROID_ABI=armeabi-v7a
--with-default-font=/system/fonts/DroidSansFallback.ttf 


## Reference
- [Sample project for embedded VLC in Android](https://bitbucket.org/edwardcw/libvlc-android-sample)
- [VLC for Android compile steps](https://wiki.videolan.org/AndroidCompile)
- [How to Install Android SDK without Android Studio on Ubuntu](https://linuxopsys.com/topics/install-android-sdk-without-android-studio-on-ubuntu)
