cactuscon2014
=============
![illuminated](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/illuminated.jpg)

# Order of the Cactar

## Purpose

This repository contains the design and documentation for the CactusCon 2014 electronic badge.
The Cactar badge serves the following four functions:

 0. Aesthetically appealing badge earned as reward for community interaction
 0. Ethernet tap
 0. USB 3.0 breakout
 0. Teensy 2.0 mounting option, plus breadboard area

The following sections will explain in greater detail the design and symbology behind the badge.

## Technical Details
![cactuscon](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/cactuscon.jpg)

Funding for the badge and (free!)
[CactusCon](http://cactuscon.com/speakers) security conference was made possible by generous donations from
[guests](https://www.kickstarter.com/projects/cactuscon/cactuscon-2014) and
[sponsors](http://cactuscon.com/sponsors).
Manufacturing of the badge occured with
[Advanced Circuits](http://www.4pcb.com/) at their Aurora, Colorado facility.
Badges were assembled and tested on site by guests with assistance from members of
[HeatSync Labs](http://heatsynclabs.org/).
Parts for incomplete badges may still be available through
[DigiKey](http://digikey.com/short/952t9).

The Cactar badge design was possible only by
[standing on the shoulders of giants](http://en.wikipedia.org/wiki/Standing_on_the_shoulders_of_giants).
Board design was done with the free version of
[EAGLE](http://www.cadsoftusa.com/download-eagle/). A custom
[ULP](http://www.cadsoftusa.com/downloads/ulps) was created to allow importing of vector graphics from
[Inkscape](http://www.inkscape.org/en/).
Gerber files are viewable through the HTML5 and WebGL renderer at
[MayhewLabs](http://mayhewlabs.com/webGerber/),
make sure optimizations are turned off if in EAGLE when CAM processing for best compatability.

The network tap portion of the badge was made possible due to the fantastic work of
[Michael Ossmann](http://ossmann.blogspot.com/2011/02/throwing-star-lan-tap.html).
Data will flow through ports located on the arms in both directions, while data flows out through the feet.
In this way the feet allow tapping of data and each foot taps data flowing from a different direction.

```
A <> B
V    V
```

The USB 3.0 breakout serves as a general test and hacking tool, stemming from the desire to have a product like the
[USB 2.0 tester](https://www.tindie.com/products/FriedCircuits/usb-tester-20/) for USB 3.0,
and based on experience with the
[PS4 Camera](http://ps4eye.tumblr.com/).

![usb3](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/usb3.jpg)

Surrounding the CactusCon logo are holes for mounting a
[Teensy 2.0](http://www.pjrc.com/store/teensy.html) or other micro development board.
The accompanying breadboard area is for general hacking, it can also accomodate small boards such as the
[USB mini host shield](http://www.circuitsathome.com/products-page/arduino-shields/usb-host-shield-for-arduino-pro-mini)
for creation of a
[keylogger](http://www.irongeek.com/i.php?page=security/homemade-hardware-keylogger-phukd).
Another possibility might include mounting an
[ethernet module](http://www.pjrc.com/teensy/td_libs_Ethernet.html)
for analyzing tapped packets through a microprocessor.

## Manifestum

There are several symbols located throughout the CactusCon badge, some of which may be more obvious than others.
Starting at the top, an
[Eye of Providence](http://en.wikipedia.org/wiki/Eye_of_Providence) seems appropriate given the
nature of the badge, as
[knowledge is power](http://en.wikipedia.org/wiki/Information_Awareness_Office).
Radiating from the eye are my initials, EW, as the connected semi-circles and lines beneath the
solder mask.

![head](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/head.jpg)

The symbols
[Tau](http://en.wikipedia.org/wiki/Tau) (τ) and
[Phi](http://en.wikipedia.org/wiki/Phi) (φ) are on either side of the badge.
Tau was chosen because it is
[twice as good as π](http://tauday.com/tau-manifesto), however if you confuse Tau with
[Tao](http://en.wikipedia.org/wiki/Tao) or
[TAO](http://en.wikipedia.org/wiki/Tailored_Access_Operations) that is okay too.
Phi was chosen for the
[Golden Ratio](http://en.wikipedia.org/wiki/Golden_ratio) and the beauty of mathematics in understanding our universe.

Below Tau and Phi and between the USB 3.0 headers is the HeatSync Labs logo.
Next to the copper
[CactusCon](http://cactuscon.com/) logo and silk-screened
[Early Warning](http://earlywarning.com/) and
[Aeris Secure](https://aerissecure.com/) logos is the breadboard area,
with the initials HSL viewable as square pads from the top side, and the adjacent
[heatsynclabs.org](http://heatsynclabs.org/) address present beneath the solder mask.

Located on the top-side right foot is a glider from
[Conway's Game of Life](http://www.bitstorm.org/gameoflife/), chosen as an unofficial
'[hacker](http://www.catb.org/~esr/faqs/hacker-howto.html#attitude)' emblem.
Located on the back-side left foot is a
[Jolly Roger](http://en.wikipedia.org/wiki/Jolly_Roger), chosen to emobody the concept of
[danger and freedom](http://www.unix.org/license-plate.html).

![eof](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/eof.jpg)

## Fin

Special thanks to [@LosT](https://twitter.com/1o57) for delivering an awesome keynote and creating badges to aspire to.

And especially thanks to all of the guests, presenters, sponsors, and organizers who helped to make this a very special event.

Follow [@CactusCon](https://twitter.com/cactuscon),
       [@HeatSyncLabs](https://twitter.com/heatsynclabs), and
       [@wils0ne](https://twitter.com/wils0ne) for more greatness.

![side a](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/cactar1.png)
![side b](https://raw.githubusercontent.com/erikwilson/cactuscon2014/master/imgs/doc/cactar2.png)
