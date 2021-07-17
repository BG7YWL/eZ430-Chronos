![EZ430-Chronos](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/EZ430-Chronos.png)

The eZ430-Chronos is a highly integrated, wireless development system that provides a complete reference design for developers creating wireless smart watch applications. Chronos is a reference platform for many applications, such as wireless watch systems, personal displays for personal area networks, wireless sensor nodes for remote data collection, & other applications.

Based on the [CC430F6137](http://focus.ti.com/docs/prod/folders/print/cc430f6137.html) <1 GHz RF SoC, the eZ430-Chronos is a complete CC430-based development system, featuring a 96 segment LCD display and provides an integrated pressure sensor and 3-axis accelerometer for motion sensitive control.

The integrated wireless feature allows the Chronos to act as a central hub for nearby wireless sensors such as pedometers and heartrate monitors. The eZ430-Chronos offers temperature and battery voltage measurement and is complete with a USB-based [CC1111](http://focus.ti.com/docs/prod/folders/print/cc1111f32.html) (kits with black PCBs) or [CC1101](http://focus.ti.com/docs/prod/folders/print/cc1101.html)/[MSP430F5509](http://focus.ti.com/docs/prod/folders/print/msp430F5509.html) (kits with white PCBs) wireless interface to a PC.

The eZ430-Chronos watch may be disassembled to be reprogrammed with a custom application and includes an eZ430 USB programming interface.

# Contents

- [Development Features](#development-features)
  * [Related Videos](#related-videos)
- [What's Included](#what-s-included)
  * [Integrated Sensors](#integrated-sensors)
  * [Development Software](#development-software)
- [Ordering & Availability](#ordering---availability)
- [Documentation (User Guide, Schematics & Instructions)](#documentation--user-guide--schematics---instructions-)
- [Projects](#projects)
  * [New openchronos-ng-elf Release](#new-openchronos-ng-elf-release)
  * [Openchronos-ng Release](#openchronos-ng-release)
  * [Chronos Software Release](#chronos-software-release)
  * [Previous Chronos Software Releases](#previous-chronos-software-releases)
  * [Control Center for Windows (**Install this first**)](#control-center-for-windows----install-this-first---)
  * [[Factory Programmed Chronos Firmware](http://www.ti.com/lit/zip/slac341)](#-factory-programmed-chronos-firmware--http---wwwticom-lit-zip-slac341-)
  * [Data Logger](#data-logger)
  * [[Lucid Scribe Plugin](http://www.lucidcode.com/LucidScribe)](#-lucid-scribe-plugin--http---wwwlucidcodecom-lucidscribe-)
  * [[CC430F6137 Code Examples](http://www.ti.com/lit/zip/slac279)](#-cc430f6137-code-examples--http---wwwticom-lit-zip-slac279-)
  * [[eZ430 Python Tools](http://github.com/wolfmankurd/eZ430-tools)](#-ez430-python-tools--http---githubcom-wolfmankurd-ez430-tools-)
  * [Hello world](#hello-world)
  * [Wireless Update (RF BSL)](#wireless-update--rf-bsl-)
  * [OpenChronos Firmware](#openchronos-firmware)
  * [PC/Chronos Communication](#pc-chronos-communication)
  * [Wireless Door Lock](#wireless-door-lock)
  * [[Chronos-theremin](http://hyperglitch.com/dev/chronos-theremin): Motion-based Theremin MIDI controller (Linux)](#-chronos-theremin--http---hyperglitchcom-dev-chronos-theremin---motion-based-theremin-midi-controller--linux-)
  * [eZ430-Chronos + Visual Studio 2010 + Robotic RC car](#ez430-chronos---visual-studio-2010---robotic-rc-car)
  * [Interfacing the USB Transceiver with AT90USB µC](#interfacing-the-usb-transceiver-with-at90usb--c)
  * [Count Down Timer](#count-down-timer)
  * [Interval Training Application Example Using State Machine Design](#interval-training-application-example-using-state-machine-design)
  * [Battery Monitoring and Low Voltage Level Handling Application Example](#battery-monitoring-and-low-voltage-level-handling-application-example)
  * [[Chronos Flying Mouse](https://processors.wiki.ti.com/index.php/Chronos_Flying_Mouse)](#-chronos-flying-mouse--https---processorswikiticom-indexphp-chronos-flying-mouse-)
  * [[safeBABI](https://processors.wiki.ti.com/index.php/SafeBABI)](#-safebabi--https---processorswikiticom-indexphp-safebabi-)
  * [[Chronos High 5 Me!](https://processors.wiki.ti.com/index.php/Chronos_High_5_Me!)](#-chronos-high-5-me---https---processorswikiticom-indexphp-chronos-high-5-me--)
  * [[Electronic Rock-Em Sock-Em Robots](https://processors.wiki.ti.com/index.php/Electronic_Rock-Em_Sock-Em_Robots)](#-electronic-rock-em-sock-em-robots--https---processorswikiticom-indexphp-electronic-rock-em-sock-em-robots-)
  * [[Pro Swing Analyzer](https://processors.wiki.ti.com/index.php/Pro_Swing_Analyzer_-_Chronos_Project_Design)](#-pro-swing-analyzer--https---processorswikiticom-indexphp-pro-swing-analyzer---chronos-project-design-)
  * [[Smart Office: Automatic Lighting System](https://processors.wiki.ti.com/index.php/Smart_Office:_Automatic_Lighting_System)](#-smart-office--automatic-lighting-system--https---processorswikiticom-indexphp-smart-office--automatic-lighting-system-)
  * [[Ultimate Workout Companion](https://processors.wiki.ti.com/index.php/Ultimate_Workout_Companion)](#-ultimate-workout-companion--https---processorswikiticom-indexphp-ultimate-workout-companion-)
  * [[RF-PID: Personal Item Finder](https://processors.wiki.ti.com/index.php/RF-PID)](#-rf-pid--personal-item-finder--https---processorswikiticom-indexphp-rf-pid-)
  * [[Remote Disconnect and Load Management using Smart Energy Meter](https://processors.wiki.ti.com/index.php/Remote_Disconnect_and_Load_Management_using_Smart_Energy_Meter)](#-remote-disconnect-and-load-management-using-smart-energy-meter--https---processorswikiticom-indexphp-remote-disconnect-and-load-management-using-smart-energy-meter-)
  * [[EZ-House: Chronos Home Automation](https://processors.wiki.ti.com/index.php/EZ-House)](#-ez-house--chronos-home-automation--https---processorswikiticom-indexphp-ez-house-)
  * [[The Punch Meter](https://processors.wiki.ti.com/index.php/The_Punch_Meter)](#-the-punch-meter--https---processorswikiticom-indexphp-the-punch-meter-)
  * [[Location Aware Temperature Control](https://processors.wiki.ti.com/index.php/Location_Aware_Temperature_Control)](#-location-aware-temperature-control--https---processorswikiticom-indexphp-location-aware-temperature-control-)
  * [[Chronos Tennis](https://processors.wiki.ti.com/index.php/Chronos_Tennis)](#-chronos-tennis--https---processorswikiticom-indexphp-chronos-tennis-)
  * [[Rubato – Tempo at the discretion of the performer](https://processors.wiki.ti.com/index.php/Rubato_–_Tempo_at_the_discretion_of_the_performer)](#-rubato---tempo-at-the-discretion-of-the-performer--https---processorswikiticom-indexphp-rubato---tempo-at-the-discretion-of-the-performer-)
  * [[Altitude Accumulator](http://blog.frankvh.com/2010/11/11/ti-chronos-watch-custom-firmware/)](#-altitude-accumulator--http---blogfrankvhcom-2010-11-11-ti-chronos-watch-custom-firmware--)
  * [[Light Control](https://processors.wiki.ti.com/index.php/Light_Control)](#-light-control--https---processorswikiticom-indexphp-light-control-)
  * [[Chronos + Google Time-based One Time Password (TOTP) Authenticator](https://processors.wiki.ti.com/index.php/Chronos-otp)](#-chronos---google-time-based-one-time-password--totp--authenticator--https---processorswikiticom-indexphp-chronos-otp-)
  * [[Chronos plugin for the MiCasaVerde Vera home automation platform](http://code.mios.com/trac/mios_ez430-chronos/wiki/WikiStart)](#-chronos-plugin-for-the-micasaverde-vera-home-automation-platform--http---codemioscom-trac-mios-ez430-chronos-wiki-wikistart-)
  * [[Another robot with wheels and robot arm, using CC1110](http://http//lars.roland.bz/watch-controlled-robot/)](#-another-robot-with-wheels-and-robot-arm--using-cc1110--http---http--larsrolandbz-watch-controlled-robot--)
  * [[This Chronos firmware adds many new functions and extensions for existing menus](http://sourceforge.net/projects/ez430chronos)](#-this-chronos-firmware-adds-many-new-functions-and-extensions-for-existing-menus--http---sourceforgenet-projects-ez430chronos-)
  * [[**Chronos-Control | PC mouse and keyboard control using TI Chronos**](http://code.google.com/p/chronos-control/)](#---chronos-control---pc-mouse-and-keyboard-control-using-ti-chronos----http---codegooglecom-p-chronos-control--)
  * [[Toscanini: A gestural control interface for Max/MSP](http://github.com/conductiveio/toscanini)](#-toscanini--a-gestural-control-interface-for-max-msp--http---githubcom-conductiveio-toscanini-)
  * [[Skydiving Altimeter](https://processors.wiki.ti.com/index.php/Skydiving_Altimeter)](#-skydiving-altimeter--https---processorswikiticom-indexphp-skydiving-altimeter-)
  * [[Updated firmware and Control Center](http://sourceforge.net/projects/ez430chronosup/)](#-updated-firmware-and-control-center--http---sourceforgenet-projects-ez430chronosup--)
  * [[Persistent alarm clock](https://processors.wiki.ti.com/index.php/Persistent_alarm_clock)](#-persistent-alarm-clock--https---processorswikiticom-indexphp-persistent-alarm-clock-)
  * [[MyChronos: Slightly modified stock code with new features](https://github.com/vegos/MyChronos)](#-mychronos--slightly-modified-stock-code-with-new-features--https---githubcom-vegos-mychronos-)
  * [[Linux Joystick & Mouse driver](https://processors.wiki.ti.com/index.php/Linux_Joystick_%26_Mouse_driver)](#-linux-joystick---mouse-driver--https---processorswikiticom-indexphp-linux-joystick--26-mouse-driver-)
  * [Drummer](#drummer)
  * [Equilibrium](#equilibrium)
  * [[Authentication System by proximity](https://github.com/Sinkmanu/auth-system-chronos)](#-authentication-system-by-proximity--https---githubcom-sinkmanu-auth-system-chronos-)
  * [Contributing Projects](#contributing-projects)
- [Chronos Partners](#chronos-partners)
- [Compatible Accessories](#compatible-accessories)
  * [Chest straps for heart rate monitoring](#chest-straps-for-heart-rate-monitoring)
  * [Bike Sensors](#bike-sensors)
  * [Compatible RF Development Boards](#compatible-rf-development-boards)
- [Support](#support)
- [FAQ](#faq)
  * [433, 868 & 915 MHz Frequency Differences](#433--868---915-mhz-frequency-differences)
- [Related Products](#related-products)
  * [MetaWatch by Fossil/TI](#metawatch-by-fossil-ti)
- [Other Resources (SEO)](#other-resources--seo-)

# Development Features

![CC430F6137_Block_Diagram](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/CC430F6137_Block_Diagram.png)

- Fully reprogrammable development environment based on the [CC430F6137](http://focus.ti.com/docs/prod/folders/print/cc430f6137.html). The CC430 is an MSP430 that is integrated <1GHz wireless transceiver for custom wireless applications
- Highly integrated, re-programmable watch development tool includes on-board 3-axis accelerometer, pressure sensor, temperature sensor, battery voltage sensor
- 96-Segment LCD display driven directly by CC430
- Can be paired wirelessly with [heart rate monitors](http://en.wikipedia.org/wiki/Heart_rate_monitor), [pedometers](http://en.wikipedia.org/wiki/Pedometer) or other devices based on RF transceivers like the CC430 or [CC1111](http://focus.ti.com/docs/prod/folders/print/cc1111f32.html) during the development process
- Includes an eZ430 USB emulator that connects the Chronos to a PC for real-time, in-system programming and debugging
- Includes [IAR Kickstart](http://focus.ti.com/docs/toolsw/folders/print/iar-kickstart.html) and [Code Composer Studio](https://processors.wiki.ti.com/index.php/Category:Code_Composer_Studio_v4) integrated development environments
- The watch development tool is 30m water-resistant. See FAQ section in [User Guide](http://www.ti.com/lit/pdf/slau292) for details.

## Related Videos

- [eZ430-Chronos Unboxing](http://www.youtube.com/watch?v=UhzWHCwIyWs)
- [eZ430-Chronos Unboxing (german)](http://www.youtube.com/watch?v=CwIbWsb1z24)
- [eZ430-Chronos Intro and Feature Overview](http://www.youtube.com/watch?v=LDJIBydJvoM)
- [eZ430-Chronos Watch Disassembly and Assembly](http://www.youtube.com/watch?v=WDL3awjhLpw)
- [Wireless Door Unlocking Using Chronos](http://www.youtube.com/watch?v=yqMbdQptdfw)
- [TI EZ430-Chronos Works in Linux](http://www.youtube.com/watch?v=qECMFXM62-g)
- [Controlling a robot arm using an ez430 Chronos](http://www.youtube.com/watch?v=KwGtTwsyrW0)
- [Chronos Based Theremin Demo](http://www.youtube.com/watch?v=HV7xWMmI1PQ)
- [An RC car controlled with Chronos ez430 (Explanation)](http://www.youtube.com/watch?v=DfffM5-XYOs)
- [An RC car controlled with Chronos ez430 (Demo)](http://www.youtube.com/watch?v=dHkAxQxH-rM)
- [Chronos watch directly controlling a Mecanum Wheel Rover using Python](http://www.youtube.com/watch?v=PNRa-Ra-kiU)
- [eZ430-Chronos Custom text scrolling](http://www.youtube.com/watch?v=mt3Pcsp6kbo)
- [eZ430 Chronos, RC Car, Arduino, USB Host Shield (First tests)](http://www.youtube.com/watch?v=OrqsJbiiqeA)
- [eZ430 Chronos, RC Car, Arduino, USB Host Shield (Real driving tests)](http://www.youtube.com/watch?v=DdwEdJDi62Y)
- [eZ430 Chronos Slightly Modified Firmware](http://www.youtube.com/watch?v=p7fAdWZXn2k)

# What's Included

- Chronos watch
- eZ430 USB programming and debugging interface
- CC1111 USB RF access point (legacy kit, black PCB) or MSP430F5509/CC1101 USB Access point (current kit, white PCB)
- Chronos Disassembly Tool (Mini Phillips screwdriver)
- 2 extra screws
- 4-pin debugger solder-on connector for access point (current kit, white PCBs)
- CR2032 Coin Cell Lithium Battery (Battery life is estimated in [User Guide](http://www.ti.com/lit/pdf/slau292))

## Integrated Sensors

![Chronos_+_emulator](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Chronos_+_emulator.jpg)

- 3-Axis Accelerometer - current kit with white PCB ([Bosch Sensortec BMA250](http://www.bosch-sensortec.com/homepage/products_3/3_axis_sensors/acceleration_sensors/bma250_1/bma250))
- Pressure Sensor - current kit with white PCB ([Bosch Sensortec BMP085](http://www.bosch-sensortec.com/homepage/products_3/environmental_sensors_1/bmp085_1/bmp085))
- 3-Axis Accelerometer - legacy kit with black PCB ([VTI CMA3000 Series](http://www.vti.fi/en/products/accelerometers/consumer_electronics/cma3000_series/))
- Pressure Sensor - legacy kit with black PCB ([VTI SCP1000 Series](http://www.vti.fi/en/support/obsolete_products/pressure_sensors/))
- Temperature Sensor (Built in to [CC430F6137](http://focus.ti.com/docs/prod/folders/print/cc430f6137.html))
- Battery/Voltage Sensor (Built in to [CC430F6137](http://focus.ti.com/docs/prod/folders/print/cc430f6137.html))

## Development Software

Although there are many other compiler and integrated development environments for MSP430 including the [Rowley Crossworks](http://www.rowley.co.uk/), [MSPGCC](http://mspgcc.sourceforge.net/) and [MSPGCC4](http://mspgcc4.sourceforge.net/), the two main options supporting the eZ430-Chronos are IAR Embedded Workbench KickStart and Code Composer Studio. Both IAR and CCS have free code-limited versions supporting the Chronos. The projects for Chronos are delivered in both full source and pre-compiled library options to avoid any code size restrictions.

- [Code Composer Studio v5](http://processors.wiki.ti.com/index.php/Category:Code_Composer_Studio_v5)
- [IAR Embedded Workbench KickStart](http://www.ti.com/iarkickstart)
- [IAR visualSTATE demo version](http://www.iar.com/vs)

# Ordering & Availability

|                       | **Order Now** | ** RF Operating Frequency** | **Common Operating Region** | **Ship Date** |
| :-------------------: | :-----------: | :-------------------------: | :-----------------------------: | :-----------: |
| **eZ430-Chronos-433** |               |           433 MHz           |            Worldwide            |   Obsolete    |
| **eZ430-Chronos-868** | [TI eStore](https://estore.ti.com/eZ430-Chronos-868-eZ430-Chronos-Wireless-Watch-Development-Tool-P1735.aspx)<br>[Digikey](http://search.digikey.com/scripts/DkSearch/dksus.dll?Detail&name=296-25449-ND)<br>[Mouser](http://www.mouser.com/Search/Refine.aspx?Keyword=chronos) |           868 MHz           |         Europe & India          | In Stock Now! |
| **eZ430-Chronos-915** | [TI eStore](https://estore.ti.com/eZ430-Chronos-915-eZ430-Chronos-Wireless-Watch-Development-Tool-P1736.aspx)<br>[Digikey](http://search.digikey.com/scripts/DkSearch/dksus.dll?vendor=0&keywords=296-25344-ND)<br>[Mouser](http://www.mouser.com/Search/Refine.aspx?Keyword=chronos)<br>[Newark](http://www.newark.com/jsp/search/browse.jsp;jsessionid=CIESIGDKJQXMICXDUZ1G2WQ?N=0&Ntk=gensearch_001&Ntt=EZ430-CHRONOS&Ntx=mode+matchallpartial&suggestions=false&ref=globalsearch&_requestid=28264) |           915 MHz           |         N. & S. America         | In Stock Now! |

# Documentation (User Guide, Schematics & Instructions)

- **[eZ430-Chronos User Guide (SLAU292)](http://www.ti.com/lit/pdf/slau292): Start here** - Technical details and instructions for Chronos
- [CC430 User Guide](http://www.ti.com/lit/pdf/slau259): Technical user manual for using the CC430, the MCU in Chronos
- [CC430F613x Datasheet](http://www.ti.com/lit/gpn/cc430f6137): Electrical specifications for the CC430F613x
- [Chronos Teardown & Getting Started Presentation](https://processors.wiki.ti.com/images/e/e0/EZ430-Chronos_Presentation_2010.04.28.pdf): The combined presentations from ESC San Jose 2010.

# Projects

## New openchronos-ng-elf Release

[Openchronos-ng-elf](https://github.com/BenjaminSoelberg/openchronos-ng-elf) is a fork of Openchronos-ng that compiles with TI's new open source GCC compiler.
It also includes:

- A working Google Authenticator like module (OTP/2FA)
- Better stopwatch
- Great stability
- Easy build system
- Automatic builds of the firmware on CircleCI
- Direct download of the latest compiled firmware.
- Overall a much better user experience and closer usage to a normal wrist watch

## Openchronos-ng Release

[Openchronos-ng](http://openchronos-ng.sourceforge.net/) is a fork of openchronos where the entire system was reworked. We also added new features:

- [Virtual screen](https://sourceforge.net/p/openchronos-ng/blog/2012/05/virtual-screens-on-openchronos-ng/)
- [System message bus](https://sourceforge.net/p/openchronos-ng/wiki/System message bus/) for system<->module communication.
- hardware RTC timekeeping (no more clock inaccuracy).
- rework of [timer](https://sourceforge.net/p/openchronos-ng/wiki/Timer/) and ports drivers.
- implementation of a module build system (drop in applications).
- rework of the [display](https://sourceforge.net/p/openchronos-ng/wiki/Display system/) system.
- rework of the [menu](https://sourceforge.net/p/openchronos-ng/wiki/Menu system/) system.

The firmware code is also conceptually simpler and smaller which leaves room for more modules (applications). Have a look to our generated API docs if you plan to add functionality. Right now we are in the process of polishing the code, a release is coming very soon, stay in tune!

## Chronos Software Release

As of October 2013, new versions of the Chronos Software packages for [Windows](http://www.ti.com/lit/zip/slac341) and [Linux](http://www.ti.com/lit/zip/slac388) are available.

What’s new in release 1.9:

- Updated package to support CCSv5.5 / IAR EW430 5.60.2 and greater (functional with full and restricted (free) IDE versions). This applies to the Chronos Access Point as well to the Chronos source projects
- All the source projects (watch and access point) are available both in CCS and IAR
- Added Wireless Update feature to the new access point (white PCB) in source code and recovery files
- Merged software projects for watch with black and white PCB - (white/black PCB determination during runtime)
- Updated documentation including the last revision of the eZ430-Chronos user’s guide
- Fixed various minor issues in Chronos Control Center and Datalogger GUI

Known Limitation in release 1.9:

- The wireless update of the Chronos with the white access point takes slightly longer given a smaller payload length
- The USB friendly name for the white access point is not part of the DLL for source. Workaround: manually add "eZ430-ChronosAP" friendly name to sources
- Due to restricted write permissions under Program Files on Windows 7. Workaround: use different installation directory or copy IAR project to location different location

Important note for Windows 8 users:

- Windows 8 does not support the installation of unsigned drivers by default. Hence, ensure to "Disable driver signature enforcement" in the Windows 8 "Startup Setting" menu prior to running the eZ430-Chronos installer package.

## Previous Chronos Software Releases

What's new in release 1.8:

- Added documentation for new Chronos kit series (white PCBs) - Gerber files, schematics and BOM
- Added software projects for new Chronos kit series (white PCBs)
- Updated Control Center DLL & USB driver installation to support both, legacy (blach PCBs) and new Chronos kits (white PCBs)
- Added software projects for new MSP430F5509/CC1101 based access point
- Supports CCSv5.3 and IAR 5.51 and newer

Known issues in release 1.8:

- The Wireless Update feature is currently not available for the current Chronos kits (white PCB)
- The Wireless Update feature on the Chronos Control Center v1.2 will only work if the RF access point contains firmware version v1.1 (legacy Chronos kits with black PCB - see next section).
- CCS projects for new Chronos kits require full CCS license
- Only supports CCSv4.2.1 and IAR 5.20 or greater (legacy kit projects - black PCB)

What's new in release 1.2:

- Fixed LCD freeze issue (in some cases the LCD froze and was only updated when a button was pressed)
- Backlight stays on for 3 sec. when light button was pushed
- Misc. usability improvements in the Chronos Control Center and Datalogger application
- Fixed minor issues in Chronos Control Center and Datalogger application (text was cut off on some PCs)
- Setup issues in the IAR Wireless-Update project for the Chronos (CC430F6137) were fixed
- Updated documentation including eZ430-Chronos-433 Gerber files, schematics and BOM
- Overall CCS/IAR project cleanup and alignment with .txt recovery images
- Supports CCSv4.2.1 and IAR 5.20 and newer

Known issues in release 1.2:

- The Wireless Update feature on the Chronos Control Center v1.2 will only work if the RF access point contains firmware version v1.1 (see next section).
- Only supports CCSv4.2.1 and IAR 5.20 or greater

What's new in release 1.1:

- Linux support of Chronos Control Center / Data Logger PC software
- Upgraded to SimpliciTI 1.1.1
- Full sources are available now for the watch, the CC1111 access point and the GUI (the only exception is the Blue Robin protocol)
- Misc. fixes on the watch SW such as improved Key Lock, easier setting of the altitude (if you keep the button pushed, the value will change faster)
- The GUI allows to store Key configurations now (i.e. you can pre-define settings for PowerPoint, iTunes,...)
- New Wireless Update feature. This allows to update the software on the watch over the air. You can simply swap the Data

Logger/Sports Watch software examples (or your own ones, as long as allow to invoke the Wireless Update mechanism again) over the air, i.e. no need to open the watch. This requires an initial update of the watch, the PC software and the RF access point (you need the CC Debugger for that purpose).

Known issues in release 1.1:

- The software packages contain source projects for the Wireless Update. The corresponding IAR project will erase the calibration data of the watch (in information memory). Moreover, there may be a error message that no access point can be found. We're working on resolving this issue. In the meantime, please use the [eZ430-Chronos Firmware Update Tool](http://www.bm-innovations.com/chronos) from BM innovations to program the BSL memory of the CC430.
- The Wireless Update feature on the new Chronos Control Center v1.1 will only work once the RF access point was updated with the new software.

![EZ430-Chronos_Control_Center](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/EZ430-Chronos_Control_Center.png)

## Control Center for Windows (**Install this first**)

The eZ430 Chronos Control Center allows you to see most of the functionality of the Chronos in action. It will wirelessly pair with the Chronos and allow you to:

- Plot Accelerometer data
- Calibrate the accelerometer, temperature altimeter sensor
- Enables motion-based control of the mouse
- Enables wireless control of PowerPoint presentations
- Maps the buttons on the Chronos to user defined keyboard shortcuts
- Sync the time with your PC
- Update firmware on watch wirelessly (requires SW update on USB access point)
- Emulate a heart rate monitor. PC and Chronos will display the same heart rate and speed info.
- Download data logged on the Chronos to your PC. NOTE: The data logger isn't a part of the factory programming of the Chronos and different firmware must be downloaded to the Chronos.

**Installing the software ([SLAC341](http://www.ti.com/lit/zip/slac341)/[SLAC388](http://www.ti.com/lit/zip/slac388)) will also copy the following files to your computer:**

- Control Centers
  - Chronos Control Center binary
  - Chronos Data logger binary
  - GUI source code
- Documentation:
  - eZ430-Chronos User Guide ([SLAU292](http://www.ti.com/lit/pdf/SLAU292))
  - Schematics, Layout (Gerbers) & BOM for Access Point, Debug Interface, and Watch
- Drivers for:
  - RF Access Point
  - eZ430 debug interface
- Application Binaries (Recovery) for Sports watch firmware, Data logger firmware (all frequency), Wireless updater (rf BSL), RF Access Point.
- Application Source Code for Sports watch firmware, Data logger firmware (all frequency), Wireless updater (rf BSL), RF Access Point. Both IAR and CCS projects are included.

[Download Now for Windows (SLAC341)](http://www.ti.com/lit/zip/slac341)

[Download Now for Linux (SLAC388)](http://www.ti.com/lit/zip/slac388)

## [Factory Programmed Chronos Firmware](http://www.ti.com/lit/zip/slac341)

The factory-loaded program may be loaded back onto the watch if needed or it can be used as a starting point to create a new, custom application.

Features:

- Basic watch functions:
  - Time
  - Date
  - Alarm
  - Stopwatch
- Sensor Measurement and display:
  - Altitude
  - 3-Axis accelerometer
  - Battery voltage
  - Temperature
- Fitness Functions (Requires an compatible heart rate monitor):
  - Heart rate
  - Running speed
  - Distance traveled
  - Calories burned
- Wireless Modes:
  - ACC: Transmit accelerometer motion data
  - PPT: Wireless presentation control or bind Chronos keys to PC keyboard shortcuts
  - Sync: Syncs time and date with PC and calibrates Temperature and Altitude
- Wireless Protocols Included:
  - [SimpliciTI](http://www.ti.com/simpliciti)
  - [BlueRobin](http://www.bmwireless.com/index.php/bluerobin_bmwireless.html)

The source code for this project is installed by Chronos-setup.exe. By default, the source code is copied to C:\Program Files\Texas Instruments\eZ430-Chronos\Software Projects

[Download Now for Windows](http://www.ti.com/lit/zip/slac341)

[Download Now for Linux](http://www.ti.com/lit/zip/slac388)

## Data Logger

The eZ430-Chronos can be used as a data logger. Heart rate, temperature, and altitude can be logged in user definable intervals of 1 to 255 seconds. 8kB of internal Flash memory is reserved for logging for several hours up to days, depending on the settings. The stored data can be transferred to a PC (in CSV format) and used for further analysis.

The source code for this project is installed by Chronos-setup.

[Download Now for Windows](http://www.ti.com/lit/zip/slac341)

[Download Now for Linux](http://www.ti.com/lit/zip/slac388)

## [Lucid Scribe Plugin](http://www.lucidcode.com/LucidScribe)

Lucid Scribe is a performance monitor for your Self, designed to detect REM sleep and trigger audio tracks. It has a plugin for the chronos, but more sleep research data is needed on the [Lucid Scribe Project](http://www.lsdbase.org/category/hardware/TI-Chronos-EZ430) to complete the rapid eye movement detection algorithm.

## [CC430F6137 Code Examples](http://www.ti.com/lit/zip/slac279)

The code examples are a series of ~100 sample programs written in C that demonstrate several ways to configure each of the peripherals on the CC430. Using CCS or IAR, each file can be downloaded directly to the device or snippets from each example can be combined to achieve your desired function.

[Download Now](http://www.ti.com/lit/zip/slac279)

## [eZ430 Python Tools](http://github.com/wolfmankurd/eZ430-tools)

Fully open source project to provide python scripts which interact with the eZ430. With a view to create a fully featured python set of classes for interacting with the watch. [Git-Hub link](http://github.com/wolfmankurd/eZ430-tools)

Alternative python library which could be merged with the above :- [Alternative Python Library](http://www.madox.net/blog/2011/01/09/ti-ez430-chronos-watch-python-library-remote-control/)

## Hello world

Trivial example of how to show some data using the LCD display

- [blog post showing 'hi earth' code](http://blog.wikifotos.org/2010/02/09/hola-mundo-para-ez430-chronos/)

More advanced example of how to show some text on the LCD display and make it SCROLL

- [blog post showing a scrolling "Hello World" text](https://trandi.wordpress.com/2011/09/03/ti-ez430-watch-unbox-hworld/)

## Wireless Update (RF BSL)

The Wireless Update feature allows you to change the firmware on the Chronos wirelessly. There will be no need to open the enclosure to upgrade the program in use. Hardware debugging (setting breakpoints, single stepping, etc) is not possible over a BSL because physical access to the [JTAG/Spy Bi-Wire](https://processors.wiki.ti.com/index.php/JTAG_(MSP430)) is required for in-system programming.

All eZ430-Chronos produced after April 2010 will include this feature. The production code is found on the bottom of the box. However, earlier kits have to be manually updated to support the wireless Update.

How to update eZ430-Chronos to support the Wireless Update:

- Update your Chronos watch. Please download the eZ430-Chronos [Firmware Update Tool](http://www.bm-innovations.com/chronos) from BM innovations at:
  - Extract the files
  - Open watch, remove battery and connect to emulator (see eZ430-Chronos [user guide](http://www.ti.com/lit/pdf/slau292) for details)
  - Connect emulator to PC (Either Code Composer Studio or the IAR Embedded Workbench must be installed to obtain the drivers)
  - Select script according to local frequency
  - Click RUN
- Update the USB access point (requires the [CC-Debugger](http://focus.ti.com/docs/toolsw/folders/print/cc-debugger.html) and SmartRF programming interfaces) - **Only necessary for kit built before April 2010**:
  - Solder 5 wires onto the RF access point as described in the Chronos [user guide](http://www.ti.com/lit/pdf/slau292)
  - Download and install SmartRF Flash Programmer
  - Connect access point to emulator and the emulator to PC
  - Press "Reset" button on CC Debugger, LED will turn green
  - Open .hex file in SmartRF Flash Programmer according to frequency
  - Select option "Erase, Program and Verify" and click "Perform Action"

- Install new Chronos Control Center software from [SLAC341 for Windows](http://www.ti.com/lit/zip/slac341) or [SLAC388 for Linux.](http://www.ti.com/lit/zip/slac388)

- Updating Software on the watch:
  - Open Control Center
  - Select "Wireless Update" tab
  - Open .txt file e.g. Datalogger in directory: C:\Program Files\Texas Instruments\eZ430-Chronos\Recovery\Chronos Watch\Applications

- NOTE:
  Only transfer flash images to the watch, which allow invoking the updater software on the watch. 
  The file to be downloaded to the watch must be in TI-TXT format to work with this update procedure. 
  This new firmware must reside within the main memory flash (0x8000-0xFFFF), otherwise the update procedure fails due to boundary checks on the watch side.
  - Click "Update Watch"
  - Push "#" on the watch until "rFbSL" is shown on the LCD
  - Push "*" to activate update

The watch will show "RAM" for a short time. During that time, a part of the update software will be transferred to the RAM of the CC430 on the Chronos watch. Once this was finished, the actual code will be transferred, the progress will be shown in percent.

## OpenChronos Firmware

[OpenChronos](http://github.com/poelzi/OpenChronos/) is a modular firmware for the EZ430-Chronos, primary designed to be compiled with the msp430-gcc. Features can be configured with "make config" to save space and add additional components.

[Instructions to setup OpenChronos developer environment on Ubuntu](http://www.gulecha.org/2011/08/30/getting-openchronos-building-on-ubuntu-11-04/).

[Development group and mailing list](http://groups.google.com/group/openchronos/)

## PC/Chronos Communication

These programs have been tested in Windows, Linux, and Mac OS X.

By default, the programs are setup to run in Windows. You must change the COM port number to the COM port your wireless access point is assigned to in the code for the programs to work correctly. The directions for this are in the source code, so see the source code for details.

To get the programs working in Linux both programs have a line in the code that says:

`ser = serial.Serial(5,115200,timeout=1)`

change that line to:

`ser = serial.Serial("/dev/ttyACM0",115200,timeout=1)`

If another USB device attached to the machine the device may be /dev/ttyACM1, /dev/ttyACM2, etc.

or in OSX: Get pySerial (http://sourceforge.net/projects/pyserial)

`ser = serial.Serial("/dev/tty.usbmodem001",115200,timeout=1)`

If you get this console error, it means the access point dongle is not plugged in. If everything was loaded successfully once, a more informative dialog box is popped up in this case.

```
bad option "-mode": should be one of -blocking, -buffering, -buffersize, -encoding,
-eofchar, or -translation while executing
```

Once plugged in, you should get a dmesg log entry like this (Linux 2.6):

```
[219258.599319] cdc_acm: v0.26:USB Abstract Control Model driver for USB modems and ISDN adapters
```

- LabVIEW 2010 application to [read acceleration data from the Chronos](http://decibel.ni.com/content/docs/DOC-13030) (including a Theremin example)
- Python application to [sync the Chronos with host PC's time](http://pastebin.com/f62344dbd) ([Python 2.6](http://www.python.org/download/) and [pySerial](http://pyserial.sourceforge.net/) are both required)
- Python application to [read acceleration data from the Chronos](http://pastebin.com/f71ca7188) ([Python 2.6](http://www.python.org/download/) and [pySerial](http://pyserial.sourceforge.net/) are both required)
- Python code to [read the button presses in PPT mode](http://chemicaloliver.net/programming/receiving-ti-ez430-chronos-button-presses-in-processing-and-python/)
- Python script for [controlling mouse under Linux](http://hyperglitch.com/files/chronos_mouse.py)
- [Processing](http://processing.org/) version of the [accelerometer code](http://pastebin.com/f210226f8)
- [Processing](http://processing.org/) improved version of the accelerometer code above demonstrating how to write data to a file. [Code here](http://gist.github.com/b5a36b689365498506d6).
- [Processing](http://processing.org/) version of the code to [get button presses](http://chemicaloliver.net/programming/receiving-ti-ez430-chronos-button-presses-in-processing-and-python/)
- [Processing](http://processing.org/) sketch demonstrating how to [graph accelerometer data](http://chemicaloliver.net/programming/graphing-ti-ez430-chronos-watch-data-in-processing/)
- [Ruby](http://www.ruby-lang.org/en/) program to [read the accelerometer data](http://blog.32leaves.net/?p=817) from the Chronos and an application to control a robot arm
- [.Net](http://www.microsoft.com/net/) library written in C# to communicate with an Chronos access point. http://ez430chronosnet.sourceforge.net/
- [.Net](http://www.tupperbot.com/?p=105) Source code to get data in ACC mode using Visual Basic .NET (English): [http://www.tupperbot.com/](http://www.tupperbot.com/?p=105)
- [.Net](http://www.tupperbot.es/2010/09/chronos-ez430-and-visual-studio-net/) (Spanish) Source code to get data in ACC mode using Visual Basic .NET: [http://www.tupperbot.es/](http://www.tupperbot.es/2010/09/chronos-ez430-and-visual-studio-net/)
- [Matlab](http://en.wikipedia.org/wiki/MATLAB) simple code to [read acceleration data from the Chronos under Linux](http://www.martindobrovolny.cz/vyuka/laboratore/zo/podpora_vyb/ez430/download/ez430.m)

## Wireless Door Lock

Using the new TI eZ430-Chronos sport development watch, this an electronic door unlock device. The watch communicates wirelessly to lock and unlock the door after given a secret password (a sequence of taps on the watch’s 3-axis accelerometer). This system demonstrates an ultra-low power consumption wireless system using TI’s MSP430 architecture, achieving estimated battery lifetimes of over 4 years on the watch and over a year on the door.

- [More info and download code](https://ziyan.info/2010/01/secure-wireless-door-lock/)
- [Watch video demo](http://www.youtube.com/watch?v=yqMbdQptdfw)

## [Chronos-theremin](http://hyperglitch.com/dev/chronos-theremin): Motion-based Theremin MIDI controller (Linux)

Chronos-theremin is a Python script for using TI Chronos watch (wiki) as a MIDI controller under Linux. It can also be modified for any other serial device providing usable (preferably accelerometar data) output.

Chronos-theremin is released under GPLv3 license.

- [Project info and source code](http://hyperglitch.com/dev/chronos-theremin)
- [Video demo](http://www.youtube.com/watch?v=HV7xWMmI1PQ)

## eZ430-Chronos + Visual Studio 2010 + Robotic RC car

Use Visual Studio to get the data sent by the ez430-Chronos. transform the raw data and use it to control a robotic RC car.

- [Source code to read the ez430-Chronos using VB.Net](http://www.tupperbot.com/?p=105) also in [Spanish here](http://www.tupperbot.es/2010/09/chronos-ez430-and-visual-studio-net/)
- [Demo video of the system](http://www.youtube.com/watch?v=DfffM5-XYOs)
- [Demo video of the RC car driven by the ez430-Chronos.](http://www.youtube.com/watch?v=dHkAxQxH-rM)

## Interfacing the USB Transceiver with AT90USB µC

An ongoing project on using the USB Transceiver with an AVR(tm) AT90USB-series microcontroller, where the AVR microcontroller is in Host mode.

Initialization is already fully functional. It's [LUFA](http://www.fourwalledcubicle.com/LUFA.php) powered.

The Project goal is remote controlling various devices using the watch.

[Syso](https://processors.wiki.ti.com/index.php?title=User:Syso&action=edit&redlink=1) 21:15, 9 February 2010 (UTC)

## Count Down Timer

[Count down from any time under 20 hours.](http://tichronostimer.sourceforge.net/)

## Interval Training Application Example Using State Machine Design

This application example implements interval training utilities on the TI Chronos Watch using IAR visualSTATE and IAR Embedded Workbench for MSP430. It monitors heart rate and manages work and rest intervals. The application consists of an IAR visualSTATE project and an integrated IAR Embedded Workbench project. The projects can be built using code size and state limited versions of the tools available for free from IAR Systems website, still leaving enough room for modifications and additions to the source.

- [Download the project files and documentation](http://www.iar.com/vs_chronos)

## Battery Monitoring and Low Voltage Level Handling Application Example

This application example builds on the Interval Training example but is slightly more complex and adds battery monitoring and low voltage handling functionality. It also introduces the concept of parallel regions in the state machine.

- [Download the project files and documentation](http://www.iar.com/vs_chronos2)

## [Chronos Flying Mouse](https://processors.wiki.ti.com/index.php/Chronos_Flying_Mouse)

![Chronos_flying_mouse_main](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Chronos_flying_mouse_main.png)

Use the Chronos watch as an intuitive computer mouse or joystick with snap-to-click technology. [Watch the video!](http://www.youtube.com/watch?v=TDL3JRG_zrs).

## [safeBABI](https://processors.wiki.ti.com/index.php/SafeBABI)

Did you know: There have been 17 deaths this summer from children being left in hot cars?

The safe Baby Alert Broadcast Interface uses a TI C1110 wireless interface attached to a car seat to trigger an alarm on the eZ-430 Chronos watch when a baby is left in the car seat.

## [Chronos High 5 Me!](https://processors.wiki.ti.com/index.php/Chronos_High_5_Me!)

High five counter with Twitter reporting

![RockEm-Thumbnail](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/RockEm-Thumbnail.png)

## [Electronic Rock-Em Sock-Em Robots](https://processors.wiki.ti.com/index.php/Electronic_Rock-Em_Sock-Em_Robots)

**[Watch Our Video!](http://www.youtube.com/watch?v=WA5Bgmt-rL8)** Exciting 2-player game using the Chronos watch to punch and move the robots on an actual Rock 'Em Sock 'Em Robots game board.

## [Pro Swing Analyzer](https://processors.wiki.ti.com/index.php/Pro_Swing_Analyzer_-_Chronos_Project_Design)

![TIsportswatch](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/TIsportswatch.png)

Sports application specific to swing technique, speed, and other various logistics. When the Chronos watch was first announced for the Co-Op challenge, a bunch of ideas were thrown around about using the watch to control devices like your television or stereo. Although most of these ideas are useful, none of them reached out to potential consumers wanting to buy this watch. Feeding off the idea of pleasing a consumer, I started at the origin with watches original functions. This is a typical sports watch with functions such as a heart rate monitor, altimeter, stopwatch, running speed, etc. All sports enthusiast related functions. So, the natural progression is to improve the watch for the athlete. The goal is to give the target consumer, the athlete, additional reasons to make a buying decision as opposed to “couch potato” features like a TV controller giving no added convenience that a normal controller doesn’t already contain. The Pro Swing Analyzer, the next generation of sports watches.

## [Smart Office: Automatic Lighting System](https://processors.wiki.ti.com/index.php/Smart_Office:_Automatic_Lighting_System)

![Blinds](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Blinds.jpg)

**Watch the demonstration video - [Video!](http://www.youtube.com/watch?v=gVIsu5mOb-8)** The system implemented in this project includes wireless automatic and manual blinds controlled by the Chronos EZ430 watch. The blinds are controlled in an auto mode depending on the light intensity in front or behind the blinds (read from the 2 strategically placed light dependent resistors (LDR) sensors). The user also has the option of manual blinds control and turning the lights on and off in the room with the watch.

## [Ultimate Workout Companion](https://processors.wiki.ti.com/index.php/Ultimate_Workout_Companion)

![UWC_Small](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/UWC_Small.JPG)

The Ultimate Workout Companion offers the ultimate in TI technology to provide its user with the best workout experience possible. It interfaces simultaneously with multiple wireless devices and internal sensors to provide an accurate heart rate, distance traveled, calories burned, and weight lost. It warns the user if they are overexerting themselves or overheating. It also interfaces with your multimedia PC for playing and pausing workout videos.

## [RF-PID: Personal Item Finder](https://processors.wiki.ti.com/index.php/RF-PID)

![RFPIDProto](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/RFPIDProto.JPG)

Never lose your personal items again! The RF Item-Finder helps keep track of your daily items such as; cellphones, keys, mp3 players, or even television remotes.

## [Remote Disconnect and Load Management using Smart Energy Meter](https://processors.wiki.ti.com/index.php/Remote_Disconnect_and_Load_Management_using_Smart_Energy_Meter)

![System_Block_Diagram](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/System_Block_Diagram.jpg)

This application is for Smart Grid and Smart Energy (electricity) meter customers. Through this application, home owners and utility companies can remotely monitor and disconnect total or partial energy services. In addition, it serves as a tool for home and office owners with remote load management which allows them to save money on their electricity bills. **[Watch the video](http://www.youtube.com/watch?v=OgCx4uVDNVM)**

## [EZ-House: Chronos Home Automation](https://processors.wiki.ti.com/index.php/EZ-House)

![MyimageA](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/MyimageA.PNG)

EZ-Home uses the EZ-430 Chronos watch as a control device for the AC system and the lights of the house. It is also expandable to control the garage door, the main door of the house and any other application such as projector screens or hearths.

## [The Punch Meter](https://processors.wiki.ti.com/index.php/The_Punch_Meter)

![Screenshot](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Screenshot.jpg)

This is a 30 second game that requires strength and speed! An excellent stress relief for work. Enjoy.

## [Location Aware Temperature Control](https://processors.wiki.ti.com/index.php/Location_Aware_Temperature_Control)

![LATC_system](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/LATC_system.png)

The Location-Aware Temperature Control allows for more intelligent control of the user's home HVAC system. It wirelessly monitors the location and temperature of the room in which the user is currently located. This allows the system to dynamically control the indoor environment to maximize user comfort. It paves the way for inexpensive and eco-friendly smart homes, making this type of technology much more accessible to a large base of customers.

## [Chronos Tennis](https://processors.wiki.ti.com/index.php/Chronos_Tennis)

![Chronos_Watch_Poster](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Chronos_Watch_Poster.jpg)

Multiplayer Tennis Game Using the Chronos Watch

## [Rubato – Tempo at the discretion of the performer](https://processors.wiki.ti.com/index.php/Rubato_–_Tempo_at_the_discretion_of_the_performer)

![RubatoIcon](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/RubatoIcon.jpg)

Go ahead--embrace your inner hippie, rock 'n' roller, pop star, or whatever you want without losing the correct Tempo. This app adjusts your music Tempo to the rhythm of your heart.

## [Altitude Accumulator](http://blog.frankvh.com/2010/11/11/ti-chronos-watch-custom-firmware/)

![3in1_2](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/3in1_2.jpg)

For an active outdoors person. The altitude accumulator function tracks how much vertical you've gained. Great for hiking, biking, skiing, and other hilly outdoor pursuits. It accumulates total vertical gain as you travel over rolling terrain, tracking total vertical, peak altitude, and your current altitude relative to your starting point. It will also properly display altitudes of greater than 9999 feet by using the bottom line of the display. [Full sourcecode and details here.](http://blog.frankvh.com/2010/11/11/ti-chronos-watch-custom-firmware/)

## [Light Control](https://processors.wiki.ti.com/index.php/Light_Control)

No more need get out of the bed to switch the light on or off! In this project I adopted the firmware of the TI Chronos to control my bedroom light.

## [Chronos + Google Time-based One Time Password (TOTP) Authenticator](https://processors.wiki.ti.com/index.php/Chronos-otp)

Generates time code for the Google Authenticator. You don't have to worry when your phone dies anymore.

http://tnhh.net/pancake/chronos-otp.xml

Another implementation:

http://tinyhack.com/2011/03/02/ez430-chronos-otp/

ezTOTP

Compatible with google new 32 bytes secrets https://github.com/amd989/ezTOTP

## [Chronos plugin for the MiCasaVerde Vera home automation platform](http://code.mios.com/trac/mios_ez430-chronos/wiki/WikiStart)

Currently uses default chronos firmware to allow watch buttons to trigger home automation events. Future support for temperature sensor and accelerometer is planned. More information on the Vera platform is available at [MiCasaVerde](http://www.micasaverde.com/).

http://code.mios.com/trac/mios_ez430-chronos/wiki/WikiStart

## [Another robot with wheels and robot arm, using CC1110](http://http//lars.roland.bz/watch-controlled-robot/)

A small robot with wheels and a robot arm, controlled by the Chronos. Uses the CC1110 on the robot (not a USB stick). More information is available at [[1\]](http://lars.roland.bz/watch-controlled-robot/). A video is available on the same page. 

## [This Chronos firmware adds many new functions and extensions for existing menus](http://sourceforge.net/projects/ez430chronos)

A time adjustment improves watch accuracy significantly. An automatic adjustment for DST (Daylight Saving Time) and a day of week display is available. A second time zone display has an adjustable offset to the main time. The stopwatch is configurable as LAP timer. A countdown timer has been added. The new agility measurement gives an indication of how often and how strong the watch has been accelerated. Programmable time interval and number of measurement cycles are programmable for this measurement. An ambient pressure display is available. Last but not least, there is a number storage for up to 10 4-digit numbers with a locking mechanism and a configurable random number generator. The projects website provides the programming files for an immediate RFBSL download and a detailed user manual for all new functions. Files for all RF frequency versions are available.

http://sourceforge.net/projects/ez430chronos

## [**Chronos-Control | PC mouse and keyboard control using TI Chronos**](http://code.google.com/p/chronos-control/)

This project aims to provide a way for disabled people (such as people with spinal cord injuries) to control a computer using their head movements. System, collects instantaneous data about the head movement of the user, using an accelerometer (TI Chronos) mounted on the user’s head and then analyzes and translates this data to cursor movements or click actions. Mouse and keyboard can be both controlled by this system.

Includes source code which communicates with Chronos using Java.

http://code.google.com/p/chronos-control/

## [Toscanini: A gestural control interface for Max/MSP](http://github.com/conductiveio/toscanini)

![Toscanini](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Toscanini.png)

The [Toscanini](http://github.com/conductiveio/toscanini) interface retrieves motion data from the EZ-430 Chronos development tool and translates it into MIDI. Three streams of MIDI data are then sent out and can be used to control other Max/MSP applications, software synthesizers, plugins, outboard MIDI hardware, and anything else that makes use of the MIDI protocol on [mobilt bredband](http://www.mobiltbredbandv.se/). [Conductive IO](http://conductiveio.com/), the company that developed the interface, is creating a worldwide community of musicians, developers, artists, performers, and all others who are interested in using motion sensitive technology to further their craft. Contact: RobbyGrodin@ConductiveIO.com

## [Skydiving Altimeter](https://processors.wiki.ti.com/index.php/Skydiving_Altimeter)

This project turns your Chronos watch into skydiving altimeter.

## [Updated firmware and Control Center](http://sourceforge.net/projects/ez430chronosup/)

![Controll_Center](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/Controll_Center.jpg)

Updated clock and data logger firmware and updated control center sync and data logger sync.

This is updated watch firmware based on [eZ430-Chronos Firmware by monterosa](http://sourceforge.net/projects/ez430chronos/TI)
I removed the agility and put that in the data logger firmware. Also the number storage is removed.
Added new sync functions for the new Control Center.
Included is the new Control Center for windows executable (Linux and mac users can use the gui source with tcl/tk)
Also included is new data logger firmware with agility and ambient pressure logging.
This needs a new Data Logger Control center, windows executable is included. (Linux and mac users can use the gui source with tcl/tk)
All binairies for all 3 frequencies are included as well. and of course all the sources.
The data logger file is more readable now, in colums.

[http://sourceforge.net/projects/ez430chronosup](http://sourceforge.net/projects/ez430chronosup/files/)

## [Persistent alarm clock](https://processors.wiki.ti.com/index.php/Persistent_alarm_clock)

Have you ever turned off your alarm, telling yourself that you would wake up a few minutes later, only to wake up an hour later? Have you ever missed a meeting because you turned off your alarm and continued to sleep? With the Persistent Alarm Clock you never will again. The Persistent Alarm Clock records movement data from a TI Chronos EZ430 watch to ensure that you actually get up when you wake up. The software works with any Android device, making it not only effective, but also simple to use.

## [MyChronos: Slightly modified stock code with new features](https://github.com/vegos/MyChronos)

[MyChronos](https://github.com/vegos/MyChronos) has the following menu structure:
Line 1:
Time, Altitude, Barometer (in hPa), Alarm, Accelerometer
Line 2:
Date (Down for Year, 3-letters day of week name or 3-letters month name or 2-letters day-of-week or day), Temperature (Down for Max, Min measurement), Battery Voltage, PPT, Sync, Acc, Stopwatch, Reset, Rfbsl.

[Video demonstrating the menu structure/features](https://www.youtube.com/watch?v=p7fAdWZXn2k)

## [Linux Joystick & Mouse driver](https://processors.wiki.ti.com/index.php/Linux_Joystick_%26_Mouse_driver)

Use your Chronos watch as a joystick or mouse device on Linux.

## Drummer

Control percussion instruments by shaking your Chronos. With 3 independent axis we can control 3 instruments.
Note, this is for a PC, it uses either the software MIDI synthesizer of Windows (not very good quality) or one of your own like e.g. VirtualMIDISynth of CoolSoft.
Read the Help for instructions.
[Drummer.zip](http://processors.wiki.ti.com/index.php/File:Drummer.zip)

## Equilibrium 

Use your Chronos to balance a sphere on a tablet.
Note, this is a PC program.
Read the Help for instructions.
[Equilibrium.zip](http://processors.wiki.ti.com/index.php/File:Equilibrium.zip)

## [Authentication System by proximity](https://github.com/Sinkmanu/auth-system-chronos)

Authentication system by proximity using the eZ430-Chronos and CC1111 for Linux.

[Source Code](https://github.com/Sinkmanu/auth-system-chronos)
[Demo Video](https://www.youtube.com/watch?v=dartAQFoDF8)

## Contributing Projects

If you've developed a project for the eZ430-Chronos and would like to make it available for everyone, please post it here. Small projects (<2MB) can be uploaded directly to the wiki or they may hosted externally on your personal site, [Google Code](http://code.google.com/), [SourceForge](http://sourceforge.net/), Github, or any other file repository.

# Chronos Partners

The eZ430-Chronos kit was developed and manufactured by a team of partners. Besides [Texas Instruments](http://www.ti.com/), the main driver behind the Chronos, the partners include:

- [**BM Innovations**](http://www.bm-innovations.com/) developed most of the hardware and software. BMi is a development specialist for electronic equipment in the sports and fitness market.

If you would like to have a custom watch based on the Chronos developed or would like to purchase the Chronos in high volume, please contact [BMi directly](mailto:info@bm-innovations.com)


  BM innovations GmbH
  49 8764 94 91 42
  [info@bm-innovations.com](mailto:info@bm-innovations.com)

- [**Exosite**](http://exosite.com/) Exosite worked with the [**TI EZ430 Chronos RF Access Point Gateway**](http://exosite.com/project/ti_chronos_pc_gateway) system and monitor your wireless sensor data from the Texas Instruments “ez430-chronos” watch development kit and sends it to Exosite. We provided all the information about how you can connect products with Exosite and point to point information of APIs and demo of public dashboard on Exosite Portals.To purchase TI EZ430 Chronos RF contact

  **Exosite**
  +1 612 353 2161 x109
  [marketing01@exosite.com](mailto:marketing01@exosite.com)
  http://exosite.com/

- [**IDT**](http://www.idthk.com/) manufactured the Chronos. IDT is a leading manufacturer for electronic products in sports, fitness and health care.
- [**Johanson Technology**](http://www.johansontechnology.com/) antennas and matching components are used in the Chronos. Johanson Technology provides ceramic components that optimize RF front end designs. TI applications notes for Johanson Technologies [antennas](http://www.ti.com/lit/pdf/swra160) and [filter baluns](http://www.ti.com/lit/pdf/swra250) are available.
- [**Bosch Sensortec**](http://www.bosch-sensortec.com/en/) pressure sensors and accelerometers are used in the Chronos v1.1. Bosch Sensortec: your partner for sensor solutions with smallest package size and lowest power consumption.
- [**VTI Technologies**](http://www.vti.fi/) pressure sensors and accelerometers are used in the Chronos v1.0. VTI Technologies is a leading provider of acceleration, inclination, motion and pressure sensor solutions.

# Compatible Accessories

![EZ430-Chronos_chest_strap](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/EZ430-Chronos_chest_strap.jpg)

## Chest straps for heart rate monitoring

- [BM-CS5](http://www.bm-innovations.com/index.php/ez430-chronos) 868/915MHz Long Range (400m)
- [BM-CS5SR](http://www.bm-innovations.com/index.php/ez430-chronos) 868/915MHz Short Range (10m)

No chest straps are planned for 433MHz.

## Bike Sensors

- BM-BS2 Bike Sensor 868/915MHz - Measures speed and distance based on wheel rotation (according to BMi not before Q2 2011).

No bike sensor is planned for 433MHz.

## Compatible RF Development Boards

![CC1111EMK868-915](https://github.com/BG7YWL/eZ430-Chronos/blob/main/img/CC1111EMK868-915.png)

- [AMB8423](http://uk.farnell.com/amber-wireless/amb8423/module-radio-868-915mhz/dp/1642378) eZ430 868/915MHZ target board based on CC1101 and MSP430F2274
- [EM430F6137RF900](http://www.ti-estore.com/Merchant2/merchant.mvc?Screen=PROD&Product_Code=EM430F6137RF900) CC430 Wireless Development Board
- [CC1101EMK433](http://focus.ti.com/docs/toolsw/folders/print/cc1101emk433.html) CC1101 433 MHz Evaluation Module
- [CC1111EMK868-915](http://focus.ti.com/docs/toolsw/folders/print/cc1111emk868-915.html) CC1111 868/915 MHz Evaluation Module. This is similar to the USB Chronos Access Point except for minor differences in the schematic. It also includes additional headers and for reprogramming using the [CC Debugger](http://focus.ti.com/docs/toolsw/folders/print/cc-debugger.html).
- [CC1110DK-MINI-868](http://focus.ti.com/docs/toolsw/folders/print/cc1110dk-mini-868.html) CC1110 Mini Development kit
- [MSP430-CCRF](http://www.olimex.com/dev/msp-ccrf.html) Olimex MSP430-CCRF (*should work*, I've ordered the board and will test soon) 868/915MHz
- [EZ430-F2013](http://www.ti.com/tool/ez430-f2013) Is exactly the same as the FET (programmer stick) that comes with the watch (except for the case). So the [EZ430-T2012](http://www.ti.com/tool/ez430-t2012) can be programmed, debugged, flashed ect. as wel, have tested it.This is interesting for the 433MHz watch, 433MHz RF modules are very cheap like [TX433N](http://www.velleman.eu/products/view/?country=es&lang=en&id=350619), [RX433N](http://www.velleman.eu/products/view/?id=370780) less than 10 euro, and easy to connect to a [EZ430-T2012](http://www.ti.com/tool/ez430-t2012) Since 433MHz is not highly supported by TI and BM its very highly supported elsewhere and its the cheapest. Indoor/outdoor weather stationa, wireless doorbells.. ect.. almost always use 433MHz.The 433MHz version is the best choice for students and hobbyist I think (for experimenting).
- [panStamps](http://www.panstamp.com/products/wirelessarduino) are small Arduino modules with a CC1101 RF frontend for the 868/915MHz ISM bands. panStamps share the same protocol (SWAP) as [OpenChronos-NG](http://sourceforge.net/p/openchronos-ng/wiki/Home/) so the chronos watch (with OpenChronos-NG) can be used to read panStamp sensors and control panStamp actuators.

# Support

There are several options to get support for the Chronos:

- [Chronos Google Group](http://groups.google.com/group/ti-chronos-development-/topics)
- [MSP430 Forum](http://e2e.ti.com/support/microcontrollers/msp43016-bit_ultra-low_power_mcus/f/166.aspx)
- [support.ti.com](http://focus.ti.com/general/docs/dsnsuprt.tsp) Direct TI support.

# FAQ

## 433, 868 & 915 MHz Frequency Differences

There are 3 different versions of the eZ430-Chronos kit available, the eZ430-Chronos-433, -868, and -915. The only difference between each version is the RF operating frequency that is supported out-of-the-box. Having multiple operating frequencies available allows for the Chronos to comply with regional RF regulations worldwide. If you're debating on which version is best, it's recommended that you purchase the version that was designed for your specific region.

Theoretically, the biggest impact of changing the radio frequency is range. In general, radio frequency is inversely proportional to range. Low frequency signals travel a greater distance and penetrate through and around objects better than high frequency signals. On the other hand, lower frequencies require larger antennas due to the longer wavelength. In the case of the Chronos, the 868 and 915MHz version will have similar RF performance. Evaluation on the 433 MHz version is on-going, but the range is likely to be shorter as a 433MHz antenna can't be much bigger inside the watch housing compared to the other versions. More information will follow once results are available.

Because each version is based on the CC430F6137, most of the other RF performance features are functionally the same on each version. Power consumption, bandwidth, data rate will be identical for each version. The data rate is independent of the radio frequency so it's possible to achieve the max data rate of 500 kbps using any Chronos version.

The 868-MHz and 915-MHz watch hardware are physically identical and the radio frequency is software selectable so it's possible to switch frequency if necessary. However, the RF Access Points for the two respective kits are slightly different. The 868-MHz Access Point has a 0Ω resistor next to the antenna and the 915-MHz version does not. The 433-MHz kit is different than the other versions in both software and hardware.

# Related Products

## MetaWatch by Fossil/TI

[MetaWatch](https://processors.wiki.ti.com/index.php?title=MetaWatch&action=edit&redlink=1)

# Other Resources (SEO)

[Microcontroller, MCU, Embedded Controller](http://www.ti.com/lsds/ti/microcontroller/home.page?DCMP=TI_MCUS&HQS=Other+OT+mcu), [8 bit microcontroller](http://www.ti.com/lsds/ti/microcontroller/16-bit_msp430/8-bit_value_line.page?DCMP=Value_Line&HQS=Other+BA+430value-promo) alternatives, [16 bit microcontroller MSP430](http://www.ti.com/lsds/ti/microcontroller/16-bit_msp430/overview.page), [Arm Microcontroller, Arm Processor](http://www.ti.com/lsds/ti/microcontroller/arm_stellaris/overview.page?DCMP=Luminary&HQS=Other+OT+stellaris), [32 bit microcontroller, DC motor controller](http://www.ti.com/lsds/ti/microcontroller/32-bit_c2000/overview.page?DCMP=dsp_C2000&HQS=Other+PA+c2000), [Capacitive Touch Microcontroller, Capacitive Touch MCU](http://www.ti.com/ww/en/touch_screen_controllers_and_haptics/buttons_sliders_wheels.htm), [Microcontroller Code](http://focus.ti.com/mcu/docs/mcusplash.tsp?contentId=128826#CE), [Microcontroller Projects](http://e2e.ti.com/group/msp430launchpad/m/project/default.aspx), [smart grid](http://www.ti.com/ww/en/smart_grid_solutions/index.htm?DCMP=Metering&HQS=Other+OT+smartgrid), [6LoWPAN](http://focus.ti.com/paramsearch/docs/parametricsearch.tsp?family=wireless&familyId=2040&sectionId=646&tabId=2736&uiTemplateId=WLS_PRDSRCH_T&paramCriteria=no), [Safety Microcontroller, Automotive Microcontroller](http://focus.ti.com/mcu/docs/mcuprodoverview.tsp?sectionId=95&tabId=2835&familyId=1931&DCMP=hercules&HQS=hercules)

