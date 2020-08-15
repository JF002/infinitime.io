---
title: "About"
image: "montage.jpg"
weight: 8
---

Infinitime is an open source firmware for the [Pinetime](https://www.pine64.org/pinetime/) smartwatch. It is written in modern C++ and based on FreeRTOS.

### Features

* **Open source** : released under the GPLv3 license
* **BLE** communication
* **Rich user interface** via display, touchpanel and push button
* Time synchronisation, notifications and music control via **BLE**
* Multiple 'apps' :
    * **Clock** (displays the date, time, battery level, ble connection status, heart rate and step count)
    * **System info** (displays various info : BLE MAC, build date/time, uptime, version,...)
    * **Brightess** (allows the user to configure the brightness of the display)
    * **Music** (control the playback of the music on your phone)
* Supported by 2 companion apps (developpments ongoing):
    * **Gadgetbridge** (on Android)
    * **Amazfish** (on SailfishOS)
* [Experimental] **OTA** (Over-the-air) update via BLE
* [Experimental] **Bootloader** based on MCUBoot
