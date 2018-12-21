# ALSA Switcher & Multiband EQ

![](https://img.shields.io/badge/license-MIT-blue.svg)

Script & Config to utilize a Multiband EQ and switch between audio devices from the linux CLI

* ALSA (Advanced Linux Sound Architecture)
* LADSPA (Linux Audio Developers Simple Plugin Architecture)
* mbeq (ladspa plugin)

Currently the script switches between a USB DAC & a USB Headset.

The USB DAC (speakers) has no EQ & the USB Headset has a Multiband EQ (based on frequency response graph)

## screenshot

![](https://raw.githubusercontent.com/equk/alsa-sw-eq/master/screenshot.png)

## Requirements

* asoundconf
* ncurses
* dialog
* ladspa
* alsa-plugins

### References

http://www.ladspa.org/

https://www.alsa-project.org/main/index.php/Asoundrc/

[Steve Harris' LADSPA Plugin](http://plugin.org.uk/ladspa-swh/docs/ladspa-swh.html)
