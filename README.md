Prebuild binary of libVLC: vlc-sdk.7z (Only armeabi-v7a is included)

- Specify DroidSansFallback.ttf as default fonts for Chinese subtitle 

## Compile environment

### OS
Linux mark-VirtualBox 3.2.0-29-generic-pae #46-Ubuntu SMP Fri Jul 27 17:25:43 UTC 2012 i686 i686 i386 GNU/Linux

### Source version
#### VLC for Android (git://git.videolan.org/vlc-ports/android.git)
b17066a9fb007c65e33a7ebf1c4acd447a04b0e7 (Thu May 22 18:49:12 2014 +0200)

#### VLC (git://git.videolan.org/vlc.git)
2e8d457afe1dc56a86bcb3dc2d39d8c95c7ba3c3 (Mon May 19 19:05:00 2014 +0800)

### Config
ANDROID_ABI=armeabi-v7a
--with-default-font=/system/fonts/DroidSansFallback.ttf 

## Reference

[Sample project for embedded VLC in Android](https://bitbucket.org/edwardcw/libvlc-android-sample)

[VLC for Android compile steps] (https://wiki.videolan.org/AndroidCompile)
