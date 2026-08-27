# Awesome LIN Bus with stars

[![GitHub stars](https://badgen.net/github/stars/iDoka/awesome-linbus)](https://GitHub.com/iDoka/awesome-linbus/stargazers/) ⭐ 245 | 🐛 1 | 📅 2023-09-06
[![GitHub forks](https://badgen.net/github/forks/iDoka/awesome-linbus)](https://GitHub.com/iDoka/awesome-linbus/network/) ⭐ 245 | 🐛 1 | 📅 2023-09-06
[![GitHub watchers](https://badgen.net/github/watchers/iDoka/awesome-linbus/)](https://GitHub.com/iDoka/awesome-linbus/watchers/) ⭐ 245 | 🐛 1 | 📅 2023-09-06

<p align="center"><img src="https://github.com/iDoka/awesome-linbus/raw/main/lin_logo.png" alt="LIN logo" width="300" heigth="150"/></p>

> :tractor: Awesome Tools, Hardware And Resources For LIN Bus

This list helps a reverse engineering LIN bus devices with lightly specializing in automotive embedded controller software and communication understanding.

> **Note**
> Items marked as "🔝" are highly recommended.

Permanent URL to this list: <https://github.com/iDoka/awesome-linbus> ⭐ 245 | 🐛 1 | 📅 2023-09-06

## Contents

This is a [LIN](http://en.wikipedia.org/wiki/Local_Interconnect_Network) protocol ToC:

* [Intro](#intro)
* [SW Tools](#sw-tools)
  * [Linux related](#linux-related)
* [Parsers](#parsers)
* [Hardware](#hardware)
* [SLLIN protocol (like slcan)](#sllin-protocol-like-slcan)
* [unsorted](#unsorted)

## Intro

* [LIN Bus Explained](https://www.csselectronics.com/pages/lin-bus-protocol-intro-basics) - A Simple Intro.

## SW Tools

* [TSMaster](https://github.com/TOSUN-Shanghai/TSMaster) ⭐ 424 | 🐛 85 | 📅 2026-07-07 - Powerful open environment for automotive CAN and LIN bus monitoring, simulation, testing, diagnostics, calibration and so on *(Closed source)*.

### Linux related

* [linux-lin](https://github.com/lin-bus/linux-lin) ⭐ 49 | 🐛 11 | 🌐 C | 📅 2026-03-23 - Linux kernel LIN bus support implemented as TTY line discipline for generic UART conrollers: [Documentation](https://github.com/lin-bus/linux-lin/wiki) ⭐ 49 | 🐛 11 | 🌐 C | 📅 2026-03-23; [Paper](https://github.com/lin-bus/linux-lin/wiki/sllin-rtlws14-paper.pdf) ⭐ 49 | 🐛 11 | 🌐 C | 📅 2026-03-23.

## Parsers

* [LDF Parser](https://github.com/c4deszes/ldfparser) ⭐ 87 | 🐛 7 | 🌐 Python | 📅 2025-12-09 - Tool is able parse LIN Description Files, retrieve signal names and frames from them, as well as encoding messages using frame definitions and decoding them.
* [LDF-Parser](https://github.com/TrippW/LDF-Parser) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2020-09-12 - Parser for retrieving data from automotive Lin description files (LDF).
* [NCF-Parser](https://github.com/TrippW/NCF-Parser) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2019-01-26 - Parser for retrieving data from automotive Node Configuration Files (NCF).

## Hardware

* [linbus](https://github.com/zapta/linbus) ⭐ 207 | 🐛 30 | 🌐 Eagle | 📅 2019-03-01 - Arduino based LINBUS stack and signal interceptor/injector.
* [LinUSBConverter](https://github.com/uCAN-LIN/LinUSBConverter) ⭐ 91 | 🐛 10 | 🌐 C | 📅 2026-06-15 - LIN to USB converter with LIN master support compatible with SLCAN.
* [linbus-phat](https://github.com/cepr/linbus-phat) ⭐ 10 | 🐛 0 | 📅 2019-01-11 - LIN Bus interface for Raspberry PI Zero.
* [budgetcan](https://github.com/ryedwards/budgetcan_fw#how-to-use-the-lin-driver) - Firmware to support gs\_usb on most STM32 devices with LIN bus support.

## SLLIN protocol (like slcan)

SLLIN protocol - that is like slcan protocol for linux based OS.

* [sllin linux](https://github.com/trainman419/linux-lin) ⭐ 49 | 🐛 11 | 🌐 C | 📅 2026-03-23
* [sllin](https://github.com/sstiller/sllin) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2016-02-02 - Linux driver for LIN interfaces (serial line qdisc).
* [start\_lin\_demo.sh](https://gerrit.automotivelinux.org/gerrit/c/AGL/meta-agl-demo/+/22877/1/recipes-kernel/sllin/files/start_lin_demo.sh)

## unsorted

* [LIN](https://github.com/gandrewstone/LIN) ⭐ 132 | 🐛 11 | 🌐 C++ | 📅 2021-01-23 - The LIN protocol implemented over Arduino APIs (Serial and Digital IO).

* [macchina LIN](https://github.com/macchina/LIN) ⭐ 123 | 🐛 8 | 🌐 C++ | 📅 2019-01-29 - Arduino library to add dual LIN support on SAM3X based boards.

* [Volvo LIN bus reader](https://github.com/laurynas/volvo_linbus) ⭐ 110 | 🐛 6 | 🌐 C++ | 📅 2020-12-25

* [open-LIN](https://github.com/open-LIN/open-LIN-c) ⭐ 91 | 🐛 2 | 🌐 C++ | 📅 2025-05-01 - Implementation of Local interconnect network in C.

* [ESP32-LIN-Interface-Library](https://github.com/mestrode/Lin-Interface-Library) ⭐ 47 | 🐛 2 | 🌐 C++ | 📅 2026-02-07 - LIN-Master functions (write and request LIN-Frames via hardware UART of an ESP32.

* [ESP32-openLIN](https://github.com/CW-B-W/ESP32-openLIN) ⭐ 21 | 🐛 2 | 🌐 C++ | 📅 2023-09-01 - The **open-LIN** implementation on ESP32 based on [ESP32-SoftwareLIN](https://github.com/CW-B-W/ESP32-SoftwareLIN) ⭐ 32 | 🐛 4 | 🌐 C++ | 📅 2023-09-24.

* [BMW Pierburg CWA400 waterpump LIN controller example](https://github.com/brainiac27/cwa400_lin) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2023-07-31

* [LIN compiler](https://github.com/PersonalTransport/LIN) ⭐ 10 | 🐛 20 | 🌐 Java | 📅 2016-07-06 - LIN is a compiler (written in java) that will parse LIN Node capability and LIN description files and generate C source code that implements the LIN 2.2 spec for slave or master nodes.

* [Uart to LinBus on Android](http://fatalfeel.blogspot.com/2013/09/uart-to-linbus.html)

* [LIN Nodes](https://github.com/John-Titor/LIN_Nodes) - Firmware and PCB designs for various LIN network nodes intended for retrofitting older vehicles.

<!--
https://github.com/marmotton/esp32-connected-car-lora
https://github.com/festlv/carpc RaspberryPi based CarPC build, to replace stock Volvo navigation system
https://github.com/festlv/carpc/blob/master/doc/volvo_can_buttons.txt
https://github.com/festlv/carpc/tree/master/linux_software/driver
https://github.com/festlv/carpc/blob/master/linux_software/driver/driver.py
-->

***

## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

## Footnotes

1. Also might be useful [this curated list](https://github.com/iDoka/awesome-canbus) ⭐ 3,432 | 🐛 6 | 📅 2026-08-07 of awesome tools and resources for CAN bus reverse engineering with lightly specializing in automotive embedded controller software and communication understanding.
2. The another awesome list [CAN ID collections](https://github.com/iDoka/awesome-automotive-can-id) ⭐ 978 | 🐛 0 | 📅 2026-08-12 also might be useful.
3. Please follow [this](https://github.com/iDoka/awesome-linbus) ⭐ 245 | 🐛 1 | 📅 2023-09-06 root-repo for lastest updates.

<!--
## Tags

#awesome
#awesome-list
#lin
#lin-bus
#local-interconnect-network
#logger
#sniffer
#slcan
#socketcan
#car-hacking
#bus-monitoring
#lawicel
#elm327
#linutils
#automotive
#embedded
#arduino
#rpi
#raspberry-pi
#sae
#obd-ii
#slcan-protocol
#usbtin
#usb2can
#iso9141
#iso17987
#ldf
#electric-vehicles
#vehicular-networks
#python
#automotive-security
-->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
