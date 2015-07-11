---
layout:     post
title:      "Status Report"
subtitle:   "My progress on nuntius."
author:     "flyingrub"
header-img: "img/post-bg-03.jpg"
category: gnome
---

## TO DO

#### Embed a QR code View directly in nuntius-android.
I've found [this](https://github.com/dlazaro66/QRCodeReaderView). It can be a good start to work without an external app.

#### UI imprevement on both side.
For the android side, regroup settings in category. Perhaps create a different MainView without settings, just the number of device connected, a way to start/stop the server and the possibilty to add a new server to the trusted one.

On linux, we lack a good way to interact with notification. A gnome-shell extension could be a possiblity to enhance the notification. Improve the actual Nuntius main window.

#### Make the nuntius-android discoverable by nuntius-linux. 
In my mind, this will be the hardest part. Check what our competitors are doing. Check http://developer.android.com/training/connect-devices-wirelessly/nsd.html, ZeroConf, Bonjour, UPnP, mDNS, Avahi. Check valadoc.org for the Avahi bindings...

#### Multiple device use on the linux side.
This will not be hard to implement, i've been thinking to add a Connection variable in each notification in order to retrieve easily interact with the device that sent the notification.


## Question

#### Should LAN be an alternative to Bluetooth or complement it?