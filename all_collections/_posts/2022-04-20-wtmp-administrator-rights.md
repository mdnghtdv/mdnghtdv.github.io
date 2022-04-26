---
layout: post
title: WTMP Administrator Rights
date: 2022-04-20
categories: [wtmp, android, administrator]
---

All questions about device admin

## Why does WTMP need to be administrator?

WTMP need administrator rights to look out for failed unlock attempts. 
Android only detects a password or pattern as incorrect if it has at least 4 digits/characters or pattern dots.

## How to remove WTMP from my device if it has administrator rights?
Google says: “… To uninstall an existing device admin app, users need to first unregister the app as an administrator”. 
This can be done in the Android settings. For your convenience, we made a delete button inside the application itself. 
Click uninstall button 💀 in the application settings. Take a look at the picture below.

![uninstall](https://raw.githubusercontent.com/mdnghtdv/mdnghtdv.github.io/main/assets/images/uninstall_button.png)

## Will WTMP erase all my phone’s data if too many failed unlock attempts?

No. WTMP will never erase any data from your phone. App uses administrator rights only to monitor failed unlock attempts. 
Android is so designed that when you request administrator rights, it displays a warning with text “… erase all the phone’s data if too many incorrect passwords are typed”. 
The warning you see is just a standard unchangeable message provided by the Android System.
