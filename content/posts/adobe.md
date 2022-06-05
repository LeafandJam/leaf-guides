---
title: "Adobe"
date: 2022-05-31T17:15:24+09:30
draft: false
categories: ["windows","adobe","macos"]
---
Installing all Adobe applications for free!



# ⊞ Windows
## GenP Method
> This guide is a cleaned up version of the great guide found [here](https://www.reddit.com/r/GenP/wiki/redditgenpguides) from the [r/GenP](https://reddit.com/r/genp) subreddit.

__This method does not work for Lightroom CC/Classic. Use the below guides for this app.__

1. Downloads Needed
- [Creative Cloud (CC)](https://creativecloud.adobe.com/apps/all/desktop?action=install&source=apps&productId=creative-cloud)
- [GenP)](https://www.mediafire.com/file/3lpsrxiz47mlhu2/Adobe-GenP-2.7.zip/file)
-[CCStopper - bypass credit card screen](https://github.com/eaaasun/CCStopper/releases/tag/v1.1.3)
2. Download and Extract all GenP to a folder (using a file manager such as [7zip](https://7-zip.org))

3. Download & Install Creative Cloud    
    - __DO NOT INSTALL "Genuine Software Detector"__
4. Open Creative Cloud & Install Apps you want
    - Choose TRY or START TRIAL
    - Adobe now will ask for a Credit Card before accessing trials.
    - extract CCStopper, open CCStopper.bat, input number 4, hit Enter
5. Exit and Quit Creative Cloud services
    - ```CTRL+SHIFT+ESC``` to open Task Manager
    - Terminate any "Creative Cloud", "CC..." and "Adobe" Processes running
6. Stop & disable Adobe Genuine services (IMPORTANT)
    - Click on Windows button, type ```Services.msc``` - Open Services
    - Find "Adobe Genuine Monitor Service" and "Adobe Genuine Software Integrity Service"
    - _If for some reason you don't find both, do it for the one that you can find_
    - _If you dont find one, or both services then skip this step_
    - Right Click on each one > Properties
    - Change the following to:
        - Startup type: DISABLED
        - Service Status: STOPPED
    - Hit Apply, OK, and close it
    - You must do it for __BOTH__ services
7. Delete this folder "AdobeGCClient"
    - ```C:\Program Files (x86)\Common Files\Adobe\AdobeGCClient```
    - _If you can't find this folder skip this step_
8. Run GenP on installed apps of Step #4
    - Check CC2022 box for automatic detection and click the Pill Picture
    - The app will find all the paths by itself
9. Disable any Adobe programs from startup (IMPORTANT)
    - ```CTRL+SHIFT+ESC``` to open Task Manager
    - Click ```Startup``` button
    - Disable Adobe Programs
10. Registry Editor (optional, but recommended)
    - Click on windows button, type ```Regedit.msc``` and Open the Registry Editor
    - Navigate to ```Computer\HKEY_CURRENT_USER\SOFTWARE\Classes\CLSID\```
    - Look for the ```{0E270DAA-1BE6-48F2-AC49-.........}```
    - Click on it (it will show new things to the right side)
    - Double click or right click > Modify on ```System.IsPinnedToNameSpaceTree```
    - Change key value to ```0```
    - Click ```OK``` and close it.
    - [If you get an "Unlicsened Pop-Up" try this fix](https://www.reddit.com/r/GenP/comments/ue47y6/possible_solution_to_unlicensed_app_popup_no/)
11. __OPEN APPS THROUGH WINDOWS MENU - NOT THROUGH CREATIVE CLOUD__
    - All done







    







## Monkrus method.
For this guide you will need:

- [qbittorrent](https://qbittorrent.org)

It's also recomended to have an adblock such as
- [uBlock Origin](https://ublockorigin.com/)

A video guide is available [here](https://youtu.be/CC5E3uyedao). (I did not create this video guide)


Go to this link for the [Adobe Master Collection](https://w14.monkrus.ws/search?q=Adobe+Master+Collection+2022&max-results=20&by-date=true).

This website is in Russian but you don't need to read anything. To translate it simply look at the right and find the country flags. Chose your desired language.

Click the top link to get Adobe Master Collection 2022 v8 (or new if new versions uploaded)

Scroll down to the bottom where there is a list of links as shown below.

![links](/posts/monkrusLinks.png)

Click one link such as the ```PB.WTF``` link and find the blue __"magnet"__ button as shown below:

![torrent](/posts/monkrusDownload.png)

In this case it is the blue one. 

Click it and complete the captcha if asked. If it doesn't suggest opening it qbittorrent automatically then download the .torrent and open it using qbittorrent. 

Once finished torrenting, you will have an .iso file. 

Mount the file by double clicking it and run the file named ```autoplay```.

This will bring up the installation for your Adobe apps! 

Finished.

## Filecr Method
[Filecr](https://filecr.com/?s=Adobe) has pre-activated copies of Adobe programs. Simply find the desired app and download the installer.

The password for the zip file that is downlaoded is ```123```. To unzip this package you will need a package manaager such as [7zip](https://7-zip.org)

#  macOS
This method is for the M1 chip Macs. This is the easiest method I have tried.

Go to [Cmacked](https://cmacked.com) and search for the desired Adobe app. 

Simply click download and download the .dmg. 

Double click this and install!

# Comments
Let me know what you think below!
{{< chat adobe >}}