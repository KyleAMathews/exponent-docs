---
title: Installation
old_permalink: /versions/v6.0.0/introduction/installation.html
previous___FILE: ./index.md
next___FILE: ./learning.md
---

There are two tools that you need to develop apps with Expo - a desktop development tool and a mobile client to open your app.

## Desktop Development Tool: XDE

XDE stands for Expo Development Environment. It is a standalone desktop app that includes all dependencies you'll need to get started.

[Download the latest version of XDE for Mac](https://github.com/exponent/xde/releases/latest).

_Linux and Windows support is planned but not currently available._.

## Mobile Client: Expo for iOS and Android

The Expo client is like a browser for apps built with Expo. When you boot up XDE on your project it generates a unique development URL for you, and you can access that from the Expo client on iOS or Android, either on a real device or in a simulator.

### On your device

[Download for Android 4.4+ from the Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent) or [for iOS 8+ from the App Store](https://itunes.com/apps/exponent)

### iOS simulator

Install [Xcode through the Apple App Store](https://itunes.apple.com/app/xcode/id497799835). It'll take a while, go have a nap. Next, open up Xcode, go to preferences and click the Components tab, install a simulator from the list [(screenshot).](/_static/img/xcode-simulator.png)

### Android emulator

Follow the [Genymotion Installation guide](https://docs.genymotion.com/Content/01_Get_Started/Installation.htm) -- the Individual Basic plan is free and works great with Expo. Once you've installed Genymotion, create a virtual device - we recommend a Nexus 5, the Android version is up to you. Start up the virtual device when it's ready.

Once the emulator is open and you have a project open in XDE, you can press _Open project in Expo on Android_ in XDE and it will install the Expo client to the emulator and open up your app inside of it.

## Node.js

To get started wtih Expo you don't necessarily need to have Node.js installed, but as soon as you start actually building something you'll want to have it. [Download the latest version of Node.js](https://nodejs.org/en/).
