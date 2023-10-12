---
title: "About"
image: "collage.png"
weight: 8
---

Infinitime is an open source firmware for the [Pinetime](https://www.pine64.org/pinetime/) smartwatch. It is written in modern C++ and based on FreeRTOS.

### Features

* **Open source** : released under the GPLv3 license
* **BLE** communication
* **Rich user interface** via display, touchpanel and push button
- **Time synchronization** via BLE
- **Notification** via BLE
- **Heart rate** measurements
- **Step** counting
- **Wake-up** on wrist rotation
- Quick actions
  * **Disable vibration** on notification
  * Brightness settings
  * Flashlight
  * Settings
- 2 watch faces:
  * Digital
  * Analog
- Multiple 'apps' :
  * **Music** (control the playback of the music on your phone)
  * **Heart rate** (controls the heart rate sensor and display current heartbeat)
  * **Navigation** (displays navigation instructions coming from the companion app)
  * **Notification** (displays the last notification received)
  * **Paddle** (single player pong-like game)
  * **Two** (2048 clone game)
  * **Stopwatch** (with all the necessary functions such as play, pause, lap, stop)
  * **Motion sensor and step counter** (displays the number of steps and the state of the motion sensor in real-time)
- User settings:
  * Display timeout
  * Wake-up condition
  * Time format (12/24h)
  * Default watch face
  * Battery status
  * Firmware validation
  * System information
- Supported by 3 companion apps (development is in progress):
  * [Gadgetbridge](https://codeberg.org/Freeyourgadget/Gadgetbridge/) (on Android)
  * Amazfish (on [Sailfish](https://openrepos.net/content/piggz/amazfish), Linux, and [Ubuntu Touch](https://open-store.io/app/uk.co.piggz.amazfish))
  * [Siglo](https://github.com/alexr4535/siglo) (on Linux)
  * **[Experimental]** [WebBLEWatch](https://hubmartin.github.io/WebBLEWatch/) Synchronize time directly from your web browser. [video](https://youtu.be/IakiuhVDdrY)
- OTA (Over-the-air) update via BLE
- [Bootloader](https://github.com/JF002/pinetime-mcuboot-bootloader) based on [MCUBoot](https://juullabs-oss.github.io/mcuboot/)


### Overview of InfiniTime 0.9.0
<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" src="https://video.codingfield.com/videos/embed/aa763c87-da82-42b6-ace5-21923a210049" frameborder="0" allowfullscreen></iframe>

### Integration with Amazfish
<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" src="https://video.codingfield.com/videos/embed/f3c4c81f-22df-4728-b5fb-982299476e07" frameborder="0" allowfullscreen></iframe>

### Integration with Gadgetbridge
<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" src="https://video.codingfield.com/videos/embed/6363b421-77b1-4c61-a79b-82c0375dca8a" frameborder="0" allowfullscreen></iframe>

### OTA
<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" src="https://video.codingfield.com/videos/embed/ad7b7368-f4e5-4352-9388-f69529d1b4fd" frameborder="0" allowfullscreen></iframe>
