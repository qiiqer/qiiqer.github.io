---
layout: post
title: "Disable changing proxy settings in Windows XP"
date: 2015-02-14
categories: Windows XP Registry Setting Proxy Settings
---
1. In the run window, type *mmc*.
2. Click on File, Add/Remove Snap In (or press control + m)
3. On the *Standalone* tab, click on the *Add...* button. 
4. From the available standalone snap-ins choose 'Group Policy' and proceed to finish.
5. Now go back to *Console Root* window and click on 'Local Computer Policy'+'User configuration' + 'Administrative Templates' + 'Windows Components' + 'Internet Explorer'
6. Enable *Disable changing proxy settings* on the details panel of the Internet Explorer. 
