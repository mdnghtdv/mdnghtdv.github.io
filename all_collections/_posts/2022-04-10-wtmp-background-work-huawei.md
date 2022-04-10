---
layout: post
title: WTMP Background Work on Huawei Devices
date: 2022-04-10
categories: [wtmp, android, huawei, guide]
---

One of the most common problems that Android users encounter is apps being killed in the background. 
In the case of phones killing apps in the background, there’s not much the developer can do. 
Developers are band together and fight this problem. The Don’t Kill My App website tells users how they can fix the issue.
The information below is based on the relevant section of Huawei on the Don't Kill My App [website](https://dontkillmyapp.com/huawei).

Traditionally Huawei and their Android customization called EMUI belongs to the most troubled on the market with respect to non-standard background process limitations.
There are no APIs and no documentation for those extensions. On default settings, background processing simply does not work right and apps working in background will break.
In some of the EMUI versions no user accessible settings can prevent the system to break background processing longer than 60 minutes.
This is done by an evil custom service called *HwPFWService* (and in EMUI 9 this is called *PowerGenie*) developed and bundled with EMUI by Huawei.

## App Launch on some EMUI 8, 9 and 10 devices

Go to `Settings > Battery > App launch` (alternative way `Settings > Battery > App launch`) and then set WTMP app to `Manage manually` and make sure everything is turned on.

1. Open `Settings > Apps` or `Settings > Battery`. This feature may or may not be available for all devices or labeled differently.
2. Open `App launch` section. When `Manage automatically` is enabled, some app launches will be prevented to save power.
3. Turn off `Manage automatically` for the WTMP app.
4. Make sure to ENABLE all toggles in the `Manage manually` section! Press `OK`.

![app_launch_emui](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/app_launch_emui.png)

## Classic battery optimization on EMUI 9+ devices

1. Open `Settings`, and search for and access `Battery optimization`. Touch the little inverted triangle next to `Not allowed` (or `Don't allow`).
2. Touch `All apps`.
3. Locate and touch WTMP app.
4. Select `Don’t allow`.

![bat_opt_emui](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/bat_opt_emui.png)

### P.S.

Huawei is extremely inventive in breaking apps on their devices. In addition to all the non-standard power management measures, they introduced a new task killer app build right into EMUI 9 on Android Pie.
It is called *PowerGenie* and it kills all apps that are not on its whitelist. You cannot add custom apps on their pre-defined whitelist. 
This means there is no other way to fix proper app functionality on Huawei than uninstalling *PowerGenie* as described [here](https://dontkillmyapp.com/huawei).
