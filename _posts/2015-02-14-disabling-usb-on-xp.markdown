---
layout: post
title: "Disable use of USB storage devices on Windows"
date: 2015-02-14
categories: windows registry
---
1. In the run window, type *regedit* to pull up registry editor. 
2. In the registry editor get to the HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/USBSTOR and change the value to 4 to enable and 3 to disable. 
