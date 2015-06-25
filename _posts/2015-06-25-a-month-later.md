---
layout:     post
title:      "A month later..."
subtitle:   "My progress on nuntius."
author:     "flyingrub"
header-img: "img/post-bg-02.jpg"
category: gnome
---

## The problems faced.
As you perhaps saw, I started working on the project a bit late... My final exam took more of my time than i expected, but I passed it. And I needed to learn a brand new langage : Vala. But now, i can work at full speed on the project. And that is what i do :).

## The progress.
So, we are able to receive notification from tcp. And those can be dismissed from the Desktop side to the android side. We are also able to toggle action of a notification and send sms from nuntius. But we lack a good GUI, for now.
We also discovered a [bug](https://bugzilla.gnome.org/show_bug.cgi?id=751338) in the vala code related to string array which is now fixed.

## My plan for the future. 
I found some limitation of the glib api for notification :

* We don't have a way to know a notification was closed on the linux side ([bugzilla](https://bugzilla.gnome.org/show_bug.cgi?id=751516)). We need it so we can also dismiss the notification on the phone, when it's dismissed on the desktop.
* There is no way to display an inline reply entry. A possible workaround is to develop a gnome-shell extension, in order to be able to add a text entry to a notification.

I reworked a bit my agenda accordlingly with the nuntius team.

| Date  | Goal                                                                              |
| :---- |:--------------------------------------------------------------------------------- |
| 29/06 | Read/write sms from the desktop                                                   |
| 20/07 | Secure Lan Communication                                                          |
| 3/08  | Allow multiple device to connect to one computer                                  |
| 10/08 | Enhance graphics, Debug, code enhancement, testing. (Be ready for stable release) |
| 24/08 | Extra features (Answer call directly from your Computer)                          |