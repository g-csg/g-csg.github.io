# Electronics

# Table of Contents
1. [Soldering Irons](#soldering-irons)
2. [Microcontroller Brands](#microcontroller-brands)
3. [Single Board Computer Brands](#single-board-computer-brands)

# Soldering Irons
1. [About Soldering](#about-soldering)
2. [Solder](#solder)
3. ["Integrated Cartridge" vs "Old" Style Soldering Tips](#"integrated-cartridge"-vs-"old"-style-soldering-tips)
4. [Tip Shapes and Applications](#tip-shapes-and-applications)
5. ["Old" Style Soldering Irons](#"old"-style-soldering-irons)
6. [Integrated Tip Soldering Irons](#integrated-tip-soldering-irons)

# About Soldering
Soldering is the process of joining together two items, typically electrical components, by melting metal to create a "joint" connection between the two. This is typically done via a "soldering iron," which is a very hot (200C-400C) metal rod. The metal that is used to create this connection is referred to as "solder," (sometimes informally referred to as just "lead") and is typically a lead-tin alloy. Leadless solder is also used, especially in large-scale manufacturing. A short video of soldering in action can be found [here.](https://youtu.be/oqV2xU1fee8?t=132)

# Solder
Common lead-tin ratios for hobbyist soldering applications are 60/40 or 63/37. Common diameter sizes are 0.1mm to 1.5mm but can vary depending on the application. Most solder also contain a liquid or gel-like cleaning agent called "flux" (or "rosin flux") that is contained within the metal alloy to aid in creating clean solder connections (or "joints"). When soldering, smoke is produced from the flux boiling off from contact with a hot soldering iron, and that smoke is unhealthy to inhale. The only Chinese brand of solder that is recommended is ["Kaina" branded solder](https://www.aliexpress.com/item/32679230667.html). A comparison between different Chinese lead brands can be found [here.](https://youtu.be/DWbQbC3hGXQ) 

# "Integrated Cartridge" vs "Old" Style Soldering Tips
Soldering irons have a simple job: heat up a metal rod to an appropiate temperature to melt solder. More specifically, just the tip of a metal rod needs to be heated. There are currently two ways that conventional soldering irons do this. The "old" way that older and inexpensive soldering irons do this is by heating a ceramic rod, which interfaces to a short metal tip. A video demonstrating this can be found [here.](https://youtu.be/aSweeoah-5s?t=147) The main issues with this method is that the heat transfer between the ceramic heating element and the soldering iron tip is not optimal; there may be air gaps between the two, the ceramic heating element may be oversized and thus most of the heat is wasted into areas that aren't the tip, and it may be difficult to know the exact temperature of the tip. However, tips are typically very inexpensive.

Budget soldering irons have recently transitioned into a new style of soldering iron tips, following the popularity of JBC soldering irons and the venerated Hakko FX-951, which implements an "integrated" tip. The tip of the iron is a long rod that has the heater, temperature sensor and tip element all in one, with no air gaps between the heating element and the metal tip. All of the power delivery is done through there, with electrical contacts at the bottom to receive power from the iron. As a result of this, replacement tips are more expensive, but the gains in heating effeciency and temperature accuracy outweigh this.

A detailed video comparing the two types of soldering iron tips can be found [here](https://www.youtube.com/watch?v=scvS2yeUH00).

The editors of this section recommend getting the newer style of "integrated" tips. Even the cheapest integrated-style irons will outperform expensive "old"-style soldering irons. The advantages of heating speed, accuracy, heat retention and overall efficiency will outclass almost any "old"-style iron.

# Tip shapes and tip applications
Different soldering iron tip shapes will serve different purposes when soldering, and you will need to choose the correct tip for the technique/component you are soldering on. [Hakko's T12/T15 Cartridge standard accommodates various shapes.](http://www.hakko.com/english/tip_selection/series_t15.html) For example, an appropriate general-use soldering tip would be a chisel "BC/C" tip, as opposed to something like a thin conical tip "I" tip, where the very tip has poor heat transfer.

# "Old" Style Soldering Irons
Many of these soldering irons are sold under different brands, but are generally all the same.
1. [Eruntop 60W](#eruntop-60w) ($5)
2. [Yihua 947](#yihua-947) ($10)
3. [Aoyue 469](#aoyue-469) ($30)
4. [Yihua 937D](#yihua-937d) ($30)

## Eruntop 60W
todo

Usually comes with no name, this is a popular blue soldering iron that plugs straight into AC. The shitty potentiometer only regulates voltage, no actual temperature regulation.
This is the cheapest of anything under the sun, aim a little higher.

## Yihua 947
todo

What appears to be a slightly "upgraded" variant of the former.

## Aoyue 469
todo

A rather small soldering station with just a potentiometer and no screen.

## Yihua 937D
todo

This seems to be one of the better "old" type stations from China, as bulky as it is. There is also a "+" variant that is higher wattage.

# Integrated Tip Soldering Irons
[KSGER T12](#ksger-t12) (~$40)
[TS100](#ts100) ($50)
[TS80](#ts80) (~$70)
[STC T12](#stc-t12) ($20)

## KSGER T12
todo

A popular "smart" station that's powered with an STM32 controller with all of the bells and whistles. OLED Screen with proper menu, power readout, sleep mode, "boost" mode, and some other stuff.

Also has an option for accurately selecting tips/calibrating tips that are Hakko or otherwise not KSGER's to get accurate temperature, and with preset profiles (for KSGER tips) and profiles to save custom tip calibrations.

KSGER's official store sells multiple irons/handles, so you can pick the one you prefer aesthetically/ergonomically.

Powered with IEC (3 pin PC PSU) cable and with in-line fuse. The PSU inside the unit is well made.
KSGER's official store is on Aliexpress, BangGood units MAY be unofficial.

The station also has a "mini" variant that has no power supply and is instead powered with a 24V, 5A barrel jack. Much thinner, if that's your thing.

30-50 USD depending on configuration.

[Review](https://www.rchelicopterfun.com/t12-soldering-station.html).
[KSGER's Official Aliexpress Store](https://www.aliexpress.com/store/1486111)

## TS100
todo
A pen-based soldering iron with an OLED menu that takes a barrel jack connection. A very good portable iron.

[Review](https://www.youtube.com/watch?v=ao39bPEyok4)

## TS80
todo
Similar as above but takes a Quick Charge 3 USB-C connection. Convenient approach if you have a QC3 power bank and do soldering out often.

[Review](https://www.youtube.com/watch?v=_Z9es-D9_8g)

## STC T12
todo
Also known as the Quicko T12-951. Quicko also seem to do a KSGER-like station too.
A T12 station with a dumber microcontroller and alarm clock segment display. Usually comes in DIY kit form and may not include PSU.

# Microcontroller Brands

The features of a microcontroller is largely dependent on its use case; It would be impractical to blindly recommend specific microcontrollers. Instead, this is a non-exhaustive list of chinese microcontroller brands, some of which have created unique products (or product families) built off already existing technologies such as Arduino.

# Microcontroller Brands
1. [WAVGAT](#wavgat)
2. [WeMos](#wemos)
3. [Funduino](#funduino)
4. [Geekcreit](#geekcreit)

<TODO: include small discussion about different families of microcontrollers and their features (e.g. ESP8266, ATmega, etc)>

# Single Board Computer Brands

For the same reasons as the #[Microcontroller Brands](#microcontroller-brands) section, it would not be very practical to simply list every Single-Board Computer (SBC) offered by Chinese companies, instead just the brands are listed. Future plans for this project may discuss minimum and recommended spec'd specific SBC's for running software such as [Plex](https://www.plex.tv/), [Nextcloud](https://nextcloud.com/), [pfsense](https://www.pfsense.org/), [Pi-Hole](https://pi-hole.net/) [Videogame Console Emulation](https://www.reddit.com/r/SBCGaming/), and other various [Homelab](#https://www.reddit.com/r/homelab/) uses.

1. [OrangePi](#orangepi)
2. [RockPi](#RockPi)
3. [AtomicPi](#AtomicPi)
4. [Rock64](#Rock64)
5. [Odroid](#Odroid)
