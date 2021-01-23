---
title: "InfiniTime 0.11.0"
date: 2021-01-23T10:58:39-05:00
tags: ["PineTime", "Release"]
---

# InfiniTime 0.11.0 

**[Download and release note on Github](https://github.com/JF002/Pinetime/releases/tag/0.11.0)**

Here is another big release with 2 major additions : the integration of theheart-rate sensor and InfiniNav, a navigation app!

Thanks to [Daniel](https://github.com/daniel-thompson) from [Wasp-os](https://github.com/daniel-thompson/wasp-os), I've finally been able to integrate the **heart rate sensor** using a **100% FOSS implementation**! To be honest, I've *just* ported the HR driver and algorithm from the Python code in Wasp-os and integrated it as an app in InfiniTime.

The *Heart rate* app in InfiniTime allows you to start and stop the heart rate sensor and displays the current heart rate value. This value is also displayed on the clock face when the HR sensor is running.

InfiniTime also exposes the standard **Heart Rate Service** over BLE, which allows any application supporting this service to read the heart rate value from the PineTime. Amazfish has added support for the heart rate service for InfiniTime in the last version.

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" src="https://video.codingfield.com/videos/embed/ee1e94e9-f2ae-4ea4-8f26-c16a8cb8e299" frameborder="0" allowfullscreen></iframe>

**InfiniNav** is a great contribution from [piggz](https://github.com/piggz), the creator of [Amazfish](https://github.com/piggz/harbour-amazfish). This app is design to work in conjunction with a companion app and a navigation app running on a phone, for example. As he doesn't things halfway, piggz also integrated this functionality in Amazfish and relies on [Pure-Maps](https://github.com/rinigus/pure-maps) for the navigation.

Basically, all you have to do is connect your PineTime to Amazfish and start a route in PureMaps. Then you'll be able to receive the navigation instruction (text message, big icon and distance remaining) in the Navigation app in InfiniTime.

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" src="https://video.codingfield.com/videos/embed/1fd64ff8-5a5b-48d9-b7f8-298df0dc383e" frameborder="0" allowfullscreen></iframe>

As a remainder, Amazfish is a nice companion app for many smartwatches and activity trackers, PineTime included, that runs on SailfishOS and that have recently been ported to 'mainstream' Linux distributions. A package has already been introduced in Manjaro-ARM.

Improvement on the **display of the battery level** have been done by [Panky-codes](https://github.com/Panky-codes) : the battery level is filtered so that it doesn't fluctuate from +/- 10% each time the indicator is refreshed.

Finally, we had some fun with [Nuxij](https://github.com/Nuxij) and [pfeerick](https://github.com/pfeerick) adding support for [Gitpod](https://gitpod.io) to the project. Gitpod allows you to create an online workspace (IDE, development environment,...) easily from configuration files included in the project. From Gitpod, you are able to edit the code, build it (and download binary files), create pull-requests,...
