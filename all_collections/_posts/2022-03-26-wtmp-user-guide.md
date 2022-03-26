---
layout: post
title: WTMP User Guide
date: 2022-03-26
categories: [wtmp, android, guide]
---

If you are using WTMP, please note that…

![followme](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide.png)

Hello Friend. This text provides answers to the basic questions that may arise when using the application. Let’s start.

## How to use

The pictures below illustrate the basic principles of using the application.

![guide1](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide1.png)

1. Click button to activate WTMP
2. Close WTMP
3. Lock screen
4. Unlock screen
5. Launch other apps
6. Lock screen
7. Unlock screen and launch WTMP. Click on the completed report.

![guide2](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide2.png)

## Permissions 👮🏻‍♂️

### Camera permission

WTMP needs this permission to take pictures. To avoid any confusion: The app does not record video at any point, the permission for taking photos and recording videos is simply the same.

### Why does WTMP need to be administrator?

WTMP need administrator rights to look out for failed unlock attempts. Android only detects a password or pattern as incorrect if it has at least 4 digits/characters or pattern dots.

### Will WTMP erase all my device data if too many failed unlock attempts?

**No.** WTMP will **never** erase your device’s data, even though a warning appears when you activate WTMP that says “… erase all the phone’s data if too many incorrect passwords are typed”. The warning you see is just a standard unchangeable message provided by the Android System.

## Cloud Sync ☁️

### Why does WTMP need access to my Gmail account?

Not resembling other security applications, WTMP is a standalone application. It does not send your pictures or locations to any third party server that would then forward this data to your Google Drive. Privacy is important, so WTMP instead uses Google’s authorization system OAuth2.0 to safely send reports directly from your device. This will not give WTMP access to your email addresses or contacts. WTMP will only use this permission to send reports to the your Google Drive defined by you from within the app.

### Is Cloud Sync available by subscription?

**No.** There are no paid subscriptions in our application. Cloud Sync is a one-time purchase.

## Common questions 👨🏻‍🔧

### There are 3 types of reports:

1. **Device unlocked.** The user has unlocked the device and uses it.
2. **Device not unlocked.** Someone picked up the phone and saw that it was locked.
3. **Unlock attempt.** Someone tried to unlock the device several times.

![guide3](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide3.png)

WTMP report types and screenshots of the screens that correspond to these report types

### Background work!

One of the most common problems that Android users encounter is apps being killed in the background. In the case of phones killing apps in the background, there’s not much the developer can do. Developers are band together and fight this problem. For this a site was created. [Don’t Kill My App](https://dontkillmyapp.com/). The website tells users how they can fix the issue. **Please check your device on this [website](https://dontkillmyapp.com/) 🙏🏼.** This is very important if your phone/tablet is on this list: Huawei, OnePlus, Samsung, Xiaomi, Meizu, Oppo, Lenovo and others.

### How to remove WTMP from my device if it has administrator rights?

Google says: “… To uninstall an existing device admin app, users need to first unregister the app as an administrator.” This can be done in the Android settings. For your convenience, we made a delete button inside the application itself. Take a look at the picture below.

![guide4](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide4.png)

When failed unlock attempts monitoring enabled. Click 💀uninstall button in the application settings. OR: You can revoke administrator rights in the Android settings. After that, you can remove the application in the standard way.

### How to open Advanced Settings?

1. Open Application Settings screen
2. Make a triple click on the word “Settings”

![guide5](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide5.png)

### Daytime photos are too dark

1. Open Advanced Settings
2. Increase the time delay before photo

![guide6](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/userguide6.png)

We do not recommend increasing the delay time to the maximum. The shorter this time, the better for recording reports.

### FaceID, Face unlock

We do not recommend using FaceID. It is not safe. If you use FaceID, the application will not be able to understand that someone tried to unlock the device. We strongly recommend using a password or pattern. Android only detects a password or pattern as incorrect if it has at least 4 digits/characters or pattern dots. FaceID can intercept the camera, so the report can be without a photo.
