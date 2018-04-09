---
layout: post
title:  Oreo & Nougat ROMs, CAF
category: blog
excerpt: Some words about Oreo
author: Vojtěch Hejsek
---

### Say "Hello" to Oreo

![Android Oreo](http://liquidporting.github.io/images/oreo.png)

As you noticed, Android Oreo (8.0) got recently released by Google and their latest devices including:

* Pixel (sailfish)
* Pixel XL (marlin)
* Pixel C (dragon)
* Nexus 6P (angler)
* Nexus 5X (bullhead)

got the latest Android update officially via OTA updates or factory images. But what about our devices?
Well, Oreo development goes faster than anybody expected and two or three days later, some devices got an unofficial AOSP based Oreo ROMs. That was quick!
Developers are preparing source codes for their devices for Oreo bring up and we aren't an exception.
ROM developers recently reported that Nougat based custom ROMs such as Resurrection Remix, Dirty Unicorns and probably others will officially stop generating new Nougat builds
for their devices after September security patch.

## Nougat and Oreo
Now let's get into Liquid Porting & Development's devices! We'll release few builds for our devices even after September because there will be some new regular monthly patches available for Nougat.
When Oreo based ROMs will be stable and usable as a daily driver, we'll surely start making a new builds for our Snapdragon devices (there is no chance for MediaTek) based on AOSP and LineageOS.
Works on Oreo bringup started so stay tuned for a new stuff.

Confirmed devices that will get Oreo based ROMs:

* OnePlus 5 (cheeseburger)
* Xiaomi Redmi 4X (santoni)

### CAF
Easier said than done but this is the game plan. We need to fix any CAF device specific issues. Meaning that things like the camera, sound, sensors, data, wifi, etc need to be working in stable condition.
We don’t move forward until this stage is completed. This stage is also going to be a pain but again, our maintainers don’t quit. We will not give in to things around us or pressure from users.
If it takes us longer than expected then it takes us longer than expected.
Once all CAF devices are deem stable, the CAF manifest along with any necessary repos that were modified will be pushed to the main organization.
This will allow maintainers to continue to further improve on performance and/or stability.
If users come up with anything, we attempt to fix it. The goal for this stage is to gather up bug reports and fix them.