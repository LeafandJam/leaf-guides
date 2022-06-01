---
title: "uYou+"
date: 2022-05-31T12:36:31+09:30
draft: false
categories: ["youtube","ios"]
---

uYou+ is the iOS version of the popular Youtube Vanced for android (no longer maintained.) It offers all perks of YouTube Premium, for free. It also includes features such as SponsorBlock which skips video sponsors for you.

This installation guide is a re-formatted and simplified version of [the official guide here](https://github.com/qnblackcat/uYouPlus/wiki/Installation)

This guide will use sideloading through the AltStore method.

# Install AltStore

##  macOS:

### Requirements:

- macOS 10.14.4 and up.
- An iOS/iPadOS device running iOS 13 and later (because uYouPlus requires iOS/iPadOS 13+).
- An Apple account: you can use a spare account, but make sure that account was logged into a device before. 

### Steps
1. Get AltStore for macOS from https://altstore.io/

2. Install Mail Plug-in:

Open AltStore. You will see the AltServer icon in the Menu bar. Now select Install Mail Plug-in and follow the instruction. Enter your mac's password when AltStore asks you. 

3. Enable Mail Plug-in:

Now we need to enable Mail Plug-in: Simply open the Mail app and go to ```Mail > Preferences > Manage Plug-ins > Enable AltPlugin.mailbundle```. Follow the instruction AltStore tells you.

4. Install AltStore to your iDevice:

- Plug your phone into your Mac. Make sure AltServer and the Mail app are running.
- Click the AltServer icon in the Mac menu bar, click Install AltStore, then choose your phone.
- Enter the Apple ID when AltStore asks you.
The process might take a few minutes. You'll see AltStore on your Home Screen when it is done.

Done! Head to [Install uYou+](http://leafguides.xyz/posts/uyou+/#install-uyou)

## ⊞ Windows:

### Requirements:

- Windows 10 and up.
- iTunes and iCloud from Apple installed. AltStore will not work with iTunes & iCloud from Microsoft Store:

    - iTunes: https://www.apple.com/itunes/download/win64

    - iCloud: https://updates.cdn-apple.com/2020/windows/001-39935-20200911-1A70AA56-F448-11EA-8CC0-99D41950005E/iCloudSetup.exe

- An iOS/iPadOS device running iOS 13 and later (because uYouPlus requires iOS/iPadOS 13+).
- An Apple account: you can use a spare account, but make sure that account was logged into a device before.

### Steps
1. Install iTunes and iCloud
2. Get AltStore for Windows from https://altstore.io/
    - Run AltInstaller.msi to setup AltServer

3. Install AltStore to your phone
    - Plug your phone into your PC/Laptop.
    - Open AltServer (it will appear as an icon in the Notification Area). Click Install AltStore and select your phone.
    - Enter the Apple ID when AltStore asks you.
    - The process might take a few minutes. You'll find AltStore on your Home Screen when it is done.

Done! Head to [Install uYou+](http://leafguides.xyz/posts/uyou+/#install-uyou)

# Install uYou+
1. Configure AltStore:
    -  AltStore is installed on your phone, but you can't open it right now. To fix that, go to ```Settings > General > Profile & Device Management```. There will be a profile with your account name in here. After you trust the profile, AltStore can be opened.

    - In AltStore, go to ```Settings > Sign in with Apple ID```. Enter the Apple ID that was used to install AltStore. If AltStore says “Could not find AltServer”, then check if your phone is connected to Mac/PC.


Congrats 🎉 You've just successfully configured AltStore.

2. Install uYouPlus:
    - Get the latest version of uYouPlus from the [release page](https://github.com/qnblackcat/uYouPlus/releases/latest). Select AltStore from the Share sheet.

    - Remove App Extensions is not recommened since it will remove the ability to use Open in YouTube shortcut & Open in YouTube Extension (https://github.com/CokePokes/YoutubeExtensions). uYouPlus will take 3 app IDs in total.

    - The process might take a few minutes. After that, you will uYouPlus on your Home Screen 🎉

# Refresh uYou+
Unfortunately, apps that have been installed using non-developer Apple IDs are only valid for 7 days, and uYouPlus is not an exception. At which point it will no longer open (you'll see an error that says "YouTube is no longer available").

To compensate for this, AltStore will periodically attempt to refresh uYouPlus in the background. In order for AltStore to do that, you must connect your phone with your Mac/PC via cable or Wi-Fi. Then click Refresh All in ```AltStore > My Apps```

To enable Refresh Apps over Wi-Fi. Make sure your phone and your Mac/PC are on the same network.
    macOS: Open Finder and enable ```“Show this iPhone when on WiFi”``` for your phone.
    Windows: Open iTunes and enable ```iTunes Wi-Fi sync``` for your phone.

# Comments
Let me know what you think below!
{{< chat uYouPlus >}}





