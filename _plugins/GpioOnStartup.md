---
layout: plugin

id: GpioOnStartup
title: GPIO On Startup
description: Provides a means for turning on a GPIO pin (LED) on startup then off on shutdown
authors:
jsbass
license: GPL

date: 2021-08-01

homepage: https://github.com/jsbass/OctoPrint-GpioOnStartup
source: https://github.com/jsbass/OctoPrint-GpioOnStartup
archive: archive link to install your plugin via pip, e.g. from github: https://github.com/jsbass/OctoPrint-GpioOnStartup/archive/master.zip

tags:
- GPIO
- Startup
- Shutdown
- LED

screenshots:

featuredimage: 

---

This simple plugin allows you to configure a GPIO pin that will go high on startup and low on shutdown of the OctoPrint server. It uses [gpiozero](https://gpiozero.readthedocs.io/) to set the GPIO pin high and low. The plugin defaults to having no pin set and will do nothing. You have to set a pin in the settings menu in order for the plugin to turn something on and off.
