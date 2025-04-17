---
title: "Windows 11"
date: 2022-05-30T15:18:12+09:30
draft: false
categories: ["windows"]
weight: 2
enableEmoji: true
---

Installing Windows IoT Enterprise LTS version from a USB.
> You will need an empty USB with at least 8gb of storage
## Step 1: Making a bootable USB

1. Download the Windows 11 IoT Enterprise LTSC .iso from [MassGrave](https://drive.massgrave.dev/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso)
> The IoT Enterprise LTSC is a version of Windows that doesn't include any bloatware and has far fewer updates by only giving the needed security ones.
2. Download and run [Balena Etcher](https://etcher.balena.io/)
3. Select the Windows ```.iso``` file for the image
4. Select your USB for the drive
- :warning: The next step will format your USB deleting everything on it. :warning:
5. Click flash

## Step 2: Booting the USB
1. Once the flashing is complete restart your computer with the USB still plugged include
2. Enter your BIOS screen by pressing DEL or F2 or enter on startup
> The exact button you need to press varies from momtherboards. You can search your motherboard and find what button enters BIOS on startup.
3. Change the boot order so your computer boots from the USB
4. Go through the Windows Installation
> If Windows asks you to login to your work or school account, find the offline symbol and press that. This will let you sign in without a Microsoft account.

## Step 3: Activating Windows
1. Open powershell
2. Enter this code: ```irm https://get.activated.win | iex```
3. Press ```1``` on your keyboard to activate Windows.

## Complete
Windows 11 IoT Enterprise LTS is now fully activated on your PC.

