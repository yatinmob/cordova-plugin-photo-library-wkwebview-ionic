# What is this?

It's a fork/replacement for https://github.com/terikon/cordova-plugin-photo-library-wkwebview.

# Why?

1- https://github.com/terikon/cordova-plugin-photo-library not work for wkwebview.
2- In my project have error:

`** BUILD FAILED **

The following build commands failed:
CompileSwift normal x86_64 /.../Plugins/cordova-plugin-photo-library-wkwebview/PhotoLibraryService.swift
CompileSwiftSources normal x86_64 com.apple.xcode.tools.swift.compiler
(2 failures)
xcodebuild: Command failed with exit code 65
[ERROR] An error occurred while running subprocess cordova.

# What I Use It For
- Only this.photoLibrary.saveImage(targetPath, album, {})

# My configuration

Ionic:

   Ionic CLI                     : 6.12.2
   Ionic Framework               : @ionic/angular 5.3.2
   @angular-devkit/build-angular : 0.1102.8
   @angular-devkit/schematics    : 11.2.8
   @angular/cli                  : 11.2.8
   @ionic/angular-toolkit        : 3.1.1

Cordova:

   Cordova CLI       : 10.0.0
   Cordova Platforms : android 9.0.0, ios 6.2.0

System:

   Android SDK Tools : 26.1.1
   ios-deploy        : 1.9.2
   ios-sim           : 8.0.2
   NodeJS            : v10.16.0
   npm               : 6.14.11
   OS                : macOS Big Sur
   Xcode             : Xcode 12.5 Build version 12E262
# How to Use?

Just use this as a drop-in replacement for that plugin.

Anyway, instead of installing the original plugin, install this one.

So follow the instructions from that one, but instead use this:

```bash
cordova plugin add cordova-plugin-photo-library-wkwebview-ionic
npm i --save cordova-plugin-photo-library-wkwebview-ionic
```

or if you have the old one installed already:

```bash
cordova plugin rm cordova-plugin-photo-library
cordova plugin add cordova-plugin-photo-library-wkwebview-ionic
npm i --save cordova-plugin-photo-library-wkwebview-ionic
```

Yeah, you will still need the "@ionic-native/photo-library" plugin.

# I've Got Issues

I will not maintain this project. I simply corrected my mistake. ;)