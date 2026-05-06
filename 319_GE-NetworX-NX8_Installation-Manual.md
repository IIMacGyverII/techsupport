# Microsoft Word - NX8IP02.doc

**Author:** 208036681  
**Subject:** NX8 Control Panel Installation Manual (Rev P) 2002  


---

## Page 1

**NetworX NX-8**
**Control/Communicator**
**Installation Manual**

**Table of Contents**

**General Description.............................................................................................2**
**Ordering Information...........................................................................................2**
**Feature Definitions .......................................................................................... 3-6**
**Programming the LED Keypads........................................................................** **7**
**Programming the NX-8.................................................................................. 9-11**
**Types of Programming Data......................................................................... 9-11**
**Enrolling the Modules & Keypads....................................................................11**
L **Quick Start Installations ............................................................................11**

**Communicator Formats ....................................................................................12**
**Reporting Events to Phone #1, #2, & #3 .................................................... 12-15**
**Default Zone Types............................................................................................18**
**Zone Doubling....................................................................................................21**
**Programming the Outputs .......................................................................... 23-24**
**Programming Worksheets .......................................................................... 37-50**
**SIA and Contact ID Formats ....................................................................... 51-52**
**Expander Trouble Reporting Information........................................................53**
**Wiring Diagram ..................................................................................................54**
**Terminal Description .........................................................................................55**
**Telephone Interface Information ......................................................................56**
**CE Notice / Declaration .....................................................................................57**
**Underwriters Laboratories Information ...........................................................58**
**Specifications................................................................................................ Back**

**GE Interlogix**
**Gladewater, Texas**
**1-800-727-2339**

---

## Page 2

**GENERAL DESCRIPTION**

The NetworX NX-8 represents a new approach to security systems design. Drawing on our experience in the world
market as the largest exporter of USA manufactured controls, we have developed the most flexible, durable, and user-
friendly control ever seen in our industry. Featuring sophisticated software which allows up to 99 users to interface
with 48 zones, 8 partitions, and a host of integrated fire, access, verification, and input/output modules, all reported
with the most comprehensive and fast SIA and Contact ID formats. The NetworX design allows a fully loaded system
to be housed in one single metal enclosure, establishing for the first time, a logical solution and design response to
modular systems. Up to 32 modules can be added to expand the capabilities of the NX-8.

**ORDERING INFORMATION**

**CADDX PART #**
**DESCRIPTION**

NX-8 KIT
Includes NX-8 Control, NX-108E LED Keypad, & 16.5V 25VA Transformer
NX-8
NX-8 Control Only
NX-108E
8 Zone LED Keypad
NX-116E
16 Zone LED Keypad
NX-124E
24 Zone LED Keypad
NX-148E
Alphanumeric LCD Keypad
NX-200 **
Zone Doubling Kit (Includes 100 3.74k and 100 6.98k resistors)
NX-216
16 Zone Expander Module
NX-320 **
Smart Power Supply and Buss Extender
NX-408E #
8 Zone Wireless Expansion Module (UL LISTED PART #60-904)
NX-416E #
16 Zone Wireless Expansion Module (UL LISTED PART #60-904)
NX-448E #
48 Zone Wireless Expansion Module (UL LISTED PART #60-904)
NX-507E
Seven Relay Module
NX-508E
Eight Output Module
NX-534E **
Two-Way Listen-In Module
NX-540E **
"Operator" Telephone Interface Module
NX-580E **
Cellemetry Interface
NX-870E **
Fire Supervision Module
NX-1192E
192 Zone LCD Keypad
NX-1208E
8 Zone LED Keypad
NX-1248E
48 Zone LCD Keypad
NX-1308E
8 Zone LED Door Design Keypad
NX-1316E
16 Zone LED Door Design Keypad
NX-1324E
24 Zone LED Door Design Keypad
NX-1448E
48 Zone Fixed Language Icon Keypad

****** These products have not been tested and approved by Underwriters Laboratories, Inc.
**#** These wireless devices are only UL listed for residential applications.

Page 2

---

## Page 3

**FEATURE DEFINITIONS**

**Abort** - If enabled, the NX-8 will wait the programmed number of seconds in location 40 prior to sending an alarm.
During this delay time, the "Cancel" LED will flash. To abort the report, type in a code and press the [Cancel] key. The
LED will extinguish. If the report is not aborted within the allotted time, the LED will extinguish when the report is sent.
A Dialer Delay @ must be enabled in the A Characteristic Select @ of locations 110-149. **(See locations 40 and 110-149,**
**pages 22 and 33)**

**AC** **Fail** **/** **Low** **Battery** **Report/Warning** - The NX-8 can be programmed to report AC failure and/or Low Battery
conditions to the central station. It can also be programmed to sound the keypad immediately upon detection of the
condition. The AC failure report/warning can be delayed. **(See locations 37 and 39, page 21)**

**AC** **Power** **/** **Low** **Battery** **Sounder** **Alert** - If enabled, the NX-8 will beep the keypad sounder upon arming or
disarming if the AC power is missing or a low battery has been detected. **(See location 23, page 17)**

**Arm / Disarm Codes** - The NX-8 can have 99 four-digit codes or 66 six-digit codes to arm/disarm the control.
All
codes must have the same number of digits. The factory default for User #1 is [ **1** ]-[ **2** ]-[ **3** ]-[ **4** ] when using a 4-digit code,
or [ **1** ]-[ **2** ]-[ **3** ]-[ **4** ]-[ **5** ]-[ **6** ] for a 6-digit code. This code can then be used to enter the new arm/disarm codes. **(See**
**location 41, page 22** )

**Automatic Arming** - If programmed, the NX-8 will Auto Arm at a specified time. At this time, the keypad will beep for
50 seconds before the panel arms. The arming process will be stopped if a code is entered on the keypad. The NX-8
will attempt to arm after every 45 minutes of inactivity until the next “opening” time (loc. 52), or until the system is
armed. The 45-minute timer will be extended when there is activity in the building causing the "Ready" LED to turn off
and on. If closing reports are sent, the user code will be 97. **(See locations 23, and 52-55, pages 17 and 25)** **NOTE:**
**For UL installations, this feature shall be disabled.**

**Auto Cancel / Abort** - If enabled, the Cancel and/or Abort features will be automatic (pressing the [Cancel] button is
not required). The Cancel and Abort features, in locations 23 and 40 respectively, must be enabled to permit this Auto
feature to work. For proper operation of these features, A Dialer Delay @ must be enabled in the A Characteristic Select @
of locations 110-149 Zone Types. **(See location 41, page 22)**

**Automatic Bypass / Instant Arming** - When enabled, the control panel can automatically bypass interior follower
zones if an exit is not detected during the exit delay time. Entry delay zones can also be made instant.
**(See location 23, segments 1 and 3, page 17)**

**Auto** **Test** - This feature will cause the panel to call the central station to report a communicator test at a specified
interval. **(See location 51, page 25)**

**Auxiliary Outputs** - The NX-8 has four programmable outputs that can be used to activate relays, LED = s, etc. **(See**
**the terminal description on page 54 and locations 45-50, pages 23-24)**

**Auxiliary Power Overcurrent** - The NX-8 will illuminate the "Service" LED on the keypad whenever too much current
is drawn from any device powered by the system. This condition can be reported to the central station.
**(See location 37, page 21)**

**Box Tamper** - The NX-8 has an input for a normally closed tamper switch (see terminal drawing). The Box Tamper can
be programmed to report and/or sound the siren and/or the keypad. These terminals can be enabled or disabled in
programming. **(See locations 37 and 39, page 21)**

**Built** **In** **Siren** **Driver** - The NX-8 has a built-in 112db siren driver. When desired, this built-in driver can be easily
converted to a 1 amp voltage output through programming. **(See location 37, page 21)**

**Bypass Toggle** - This feature will enable the end user to toggle (turn on or off) the bypass of an interior zone with the
system armed by pressing the [Bypass] key. **(See location 23, page 17)**

**Call** **Back** - When enabled, the control will use the call back phone number to call the download computer before
beginning a download. **(See location 21, page 16)**

Page 3

---

## Page 4

**Cancel** - If enabled, the NX-8 will send a "Cancel" report if when the system is disarmed and the [Cancel] button is
pressed within 5 minutes of an alarm. Once the [Cancel] key is pressed, the "Cancel" LED will illuminate until the
central station acknowledges the "Cancel" report.
A Dialer Delay @ must be enabled in the A Characteristic Select @ of
locations 110-149. **(See location 23, page 17)**

**Code** **Required Options** - The NX-8 can be programmed to require a code for bypassing zones and/or initiating a
download using the [ r ]-[ **9** ]-[ **8** ] or [ r ]-[ **9** ]-[ **9** ] function. **(See locations 23 and 41, pages 17 and 22)**

**Communication Formats** - The NX-8 can report in multiple formats. It is recommended that you use Contact ID or SIA
formats if possible. If you wish to report to a pager or in a 4+2 format to a central station, you must program each code
to be reported. **(See locations 56-83 and 111-149, pages 26-30 and 33-36)**

**Cross Zoning** - This feature requires two or more trips on a zone or zones programmed as "cross zones" within a
specified time before reporting an alarm. During the time between trips, the NX-8 can be programmed to sound the
keypad and/or the siren. The NX-8 can also be programmed to report an alarm after two or more trips on the same
zone. **(See locations 37, 39, 40 and 110-149, pages 21 - 22, 33 - 36)**

**Dual** **/** **Split** **/** **Multiple** **Reports** - The NX-8 can send communication reports to three different phone numbers for
dual, split or multiple reports selectable by event or partition. **(See locations 4, 10, and 16, pages 12-15)**

**Duress Code** - If a duress code is programmed the NX-8 will send a duress signal whenever the panel is armed or
disarmed with this code. If open/close reports are sent, the user code will be 254. **(See location 44, page 23)**

**Dynamic Battery Test** - The NX-8 can be programmed to perform a Dynamic Battery Test for a selected duration the
first time the panel is armed or disarmed every day, as well as by pressing [ r ][4] Test Function. If the panel is not
armed or disarmed during the day, it will perform the test at midnight. The NX-8 can also be programmed to perform a
missing battery test every 12 seconds. **(See locations 37 and 40, pages 21 and 22)**

**Entry-Guard** - This unique low level arming mode has been developed to reduce the most common source of false
alarms. When armed with the A Instant @ LED on, the opening of any zones designated as "Entry Guard zone" will
initiate the keypad sounder and start the entry delay before creating an alarm. All other zones will function as normal.
This arming mode will encourage system owners to use their system more frequently when the premises are
occupied. **(See locations 111-149, pages 33-36) NOTE: For UL installations, this feature shall be disabled.**

**Exit Error** - If enabled, the NX-8 will send an "Exit Error Report" if an entry/exit zone is faulted at the instant the exit
delay expires. This report will be sent along with the user number that armed the system, if the panel is not disarmed
before the entry delay expires. The alarm report will also be sent. Even if this feature is not enabled, the siren will
sound if any entry/exit zone is faulted at the instant the exit delay expires. **(See location 23, page 17)**

**Expander** **Trouble** - The NX-8 will report expander trouble to the central station if enabled. This condition will
illuminate the "Service" LED on the keypad even if not reported. NOTE: The keypads are considered expanders. The
number of the expansion devices reported can be found on page 53. **(See location 37, page 21)**

**Fail** **to** **Communicate** - The NX-8 will illuminate the "Service" LED if a report fails to reach the central station. If
enabled, when the next report is successfully communicated, a Fail to Communicate code will be reported. **(See**
**location 37, page 21)**

**Fire Alarm Verification** - When enabled, the NX-8 will verify a Fire alarm by requiring more than one trip on a smoke
detector within a specified time before creating an alarm. **(See location 40, page 22)** **This feature is not approved**
**for residential use in California.**

**Force Arming** - When enabled, the NX-8 can be Force Armed with zones violated. Under this condition, if a force
armable zone is not secure, the "Ready" LED will flash. At the end of the exit delay, these zones will become
bypassed. If these zones become secured any time during the arming cycle, they will be unbypassed and active in the
system. If "Bypass Report" is enabled, the force arming zones can be programmed to report bypass when they are
Force Armed (default), or to not report bypass even if "Bypass Report" is enabled. **(See locations 37, and 111-149,**
**pages 21 & 33-36)** **NOTE: For UL installations, this feature shall be disabled.**

**Ground** **Fault** - If the NX-870 is used, a fault of the earth ground can be reported to the central station. If it is not
reported, this condition will illuminate the "Service" LED on the keypad. **(See location 37, page 21)**

Page 4

---

## Page 5

**Group Bypass** - A designated group of zones can be programmed to bypass by pressing [ **Bypass** ]- [ **0** ]-[ **Bypass** ]-
[ **Bypass** ] prior to arming. **(See locations 111-149, pages 33-36)** **NOTE: For UL installations, this feature shall be**
**disabled.**

**Immediate** **Restore** **By** **Zone** - The NX-8 can be programmed to send alarm and restore reports as soon as they
occur, or wait until the siren time has expired. **(See location 37,** **page 21)**

**Internal Event Log** - Up to 185 events can be stored in memory along with the date and time of the event. These
events can later be viewed through downloading. **All reportable events report to the log.**

**Keypad Activated Panics** - The NX-8 has three keypad activated panics that will send reports to the central station:
Auxiliary 1 (Fire), Auxiliary 2 (Medical), and Keypad Panic. Auxiliary 1 will activate the steady (Fire) siren, Auxiliary 2
will sound the keypad, and the Keypad Panic can be programmed to be silent or audible (sound siren). **(See location**
**23, page 17)**

**Keypad** **Sounder** **Control** - The NX-8 can be programmed to sound the keypad sounder for certain events. **(See**
**location 39, page 21)**

**Keypad Tamper** - If enabled, the NX-8 will disable the keypad for 60 seconds and communicate a tamper signal to the
central station if 30 keypresses are entered without producing a valid code. **(See location 23, page 17)**

**Keyswitch** **Arm/Disarm** - Any zone on the NX-8 can be programmed as a keyswitch zone.
If this is done, a
momentary short on this zone will arm/disarm the control. If opening/closing reports are sent, the user code will be 99.
**(See "Default Zone Types", page 18)**

**LED** **Extinguish** - This feature will extinguish all LED = s on the keypad, except the "Power" LED, after 60 seconds
without a keypress. Pressing any numeric key will illuminate all LED = s. **(See location 23, page 17)**

**Local Programming Lockout** - This feature will disable programming of all locations or specified locations from the
keypad. **(See location 21, page 16)**

**Log Full Report** - A report can be sent to the central station when the event log is full. **(See location 37, page 21)**
**Lost Clock Service Light** - The NX-8 can be programmed to illuminate the "Service" LED when the internal clock has
an invalid time due to power loss. **(See location 37, page 21)**

**Manual Test** - The NX-8 can be programmed to perform a bell and/or communicator test when [ r ]-[ **4** ] is entered while
the system is in the disarmed state. **(See location 37, page 21)**

**On Board Zone Disable** - The eight zones on the NX-8 panel can be disabled in order to have a completely wireless
alarm system. **(See location 37, page 21)**

**Partitions** - The NX-8 can be partitioned into a maximum of eight separate systems with distinct reporting codes, user
codes, and operating features for each system. **(See locations 26 - 36, pages 19 - 20)**

**Program Code** - The factory default for the "Go To Program" code is [ **9** ]-[ **7** ]-[ **1** ]-[ **3** ] when using a 4-digit code or, if the
6-digit option is used, the default is [ **9** ]-[ **7** ]-[ **1** ]-[ **3** ]-[ **0** ]-[ **0** ]. The program code can also be used as an Arm/Disarm code.
If used as an Arm/Disarm code, and open/close reports are sent, the user code will be 255. **(See location 43, page**
**22)**

**Quick** **Arm** **Feature** - The NX-8 has a one button "Quick Arm" feature which can be used to arm the system by
pressing the [ **Exit** ] key or the [ **Stay** ] key on the keypad. If closing reports are sent, the user code will be 98. **(See**
**location 23, page 17)**

**Recent Closing** - If enabled, the NX-8 will send a "Recent Closing Report" to the central station if an alarm occurs
within 5 minutes after the panel is armed. The user number that armed the system will also be sent. **(See location**
**23, page 17)**

**Re-exit** - The NX-8 has the ability to restart the exit delay for a quick exit without disarming the system by pressing
the [ **Exit** ] key while the system is armed. **(See location 23, page 17)**

**Shutdown** - This mode will cause the keypads to turn off all LED = s, except the "Power" LED, and not accept
keypresses. **(See location 21, page 16)**

Page 5

---

## Page 6

**Siren Blast For Arming** - The NX-8 can be programmed to give a one second siren blast when the panel is armed, at
the end of the exit delay, or when the central station receiver acknowledges the closing report. It can also give one
blast for remote (keyswitch) arming and two blasts for remote disarming. **(See location 37, page 21)**

**Siren Supervision** - The NX-8 has a A Siren Supervision @ circuit that will constantly monitor the siren on the NX-8 and
can be programmed to report if the wires are cut. **(See location 37, page 21)**

**Silent Exit Option** - The exit delay can be silenced by pressing [ r ]-[ **Exit** ] before arming the control panel or when
using the re-exit feature. The exit delay can also be silenced permanently in all partitions. ( **See location 37, page 21)**

**Start/End** **Programming** **and** **End** **Downloading** - A report can be sent when local programming is started and
ended. A report can also be sent when a download session ends. **(See location 37, page 21)**

**Swinger Shutdown** - This feature allows a zone or zones to be automatically bypassed after a specified number of
alarms. When a zone is tripped, the alarm ‘counter’ reflects “1” in memory. If a new (first) alarm is detected in a
different zone, the counter remains at “1”. If an alarm is detected on a previously tripped zone, the count increments to
“2”. The ‘counter’ will increment each time an alarm is detected on a zone with multiple trips. Bypassing will occur on
the zone that causes the count to equal the number programmed in location 38; the ‘counter’ will reset to zero (0); and
begin a new trip count where the next alarm will set the ‘counter’ to 1. If immediate restore is enabled in location 37,
the alarms (and restores, if enabled) will be sent as they occur. If immediate restore is not enabled, a second or
subsequent alarm will not be sent until the siren times out. **(See** **location** **37** **and** **38,** **page** **21)** **NOTE:** **For** **UL**
**installations, this feature shall be disabled.**

**Telephone** **Line** **Monitor** - The NX-8 has a Telephone Line Monitor that monitors the voltage and current of the
telephone line for a detection of a faulted phone line. This condition can also be reported to the central station. If the
report is enabled, only the Telephone Line Restore will be reported unless the NX-870 is being used. **(See locations**
**37, 39, and 40, pages 21-22)**

**Temporal Siren Disable** - If disabled, the Fire Siren will be steady and Fire Voltage Out will be the same as Burglary
(continuous). Otherwise, the Fire Siren will be temporal. **(See location 37, page 21)** **NOTE: For UL installations,**
**do NOT disable.**

**Tone Sniff Answering Machine Defeat** - If enabled, only one call is required to defeat the answering machine. To use
this feature you must have a Hayes 1200 Smart Modem or a Caddx 1200 module. From the computer, call the panel
as normal. When the answering machine answers, the panel will hear the tones from the modem and seize the phone
line for a download. **(See location 21, page 16)**

**Two** **Call** **Answering** **Machine** **Defeat** - If enabled, to defeat an answering machine, two telephone calls must be
made to the premises. On the first call, let the phone ring one or two times. The control panel will detect these rings
and start a 45 second timer, during which, the control panel will answer the next call on the first ring. **This** **is** **not**
**recommended for commercial applications.** **(See location** **21, page 16)**

**Walk-Test Mode** - If enabled, entering [ r ] [Chime] followed by a user code will allow a walk-through zone test where
all zones become silent and local (non-reporting). During this test the chime light will flash on the LED keypad. Each
time a zone is faulted, the zone light on the LED keypad will illuminate and the chime will sound. The number of the
faulted zone(s) will be displayed on the LCD keypad. It will also be entered into alarm memory and the internal log.
To exit at any time during this mode, enter a user code. Otherwise the A Walk-Test Mode @ will automatically exit after
15 minutes. **(See location 41, page 22)**

**Wireless Sensor Missing/Low Battery** - The NX-8 will send a report to the central station when a wireless sensor
has detected a low battery or has not reported to the receiver. The "Service" LED will illuminate when either condition
exists.
**(See location 37, page 21)**

**Zone Bypassed Sounder Alert** - If this feature is enabled, the NX-8 will beep the keypad sounder upon arming if a
zone is bypassed. **(See location 23, page 17)**

**Zone Doubling** - This feature allows you to use the eight zones on the panel as sixteen normally closed zones. When
this feature is used European double E.O.L. configuration cannot be used on the first sixteen zones. **THIS FEATURE**
**DOES NOT INCREASE THE TOTAL NUMBER OF AVAILABLE ZONES BEYOND 48.** If one of the sixteen zones
must be a fire zone, it must be one of Zones 1 to 8. The corresponding upper zone will become unavailable. For
example, if Zone 6 is a fire zone, then Zone 14 will not be available.
**(See location 37, page 21)**

**Zone** **Types** **(Configurations)** - The NX-8 has 20 programmable Zone Types that determine how each zone will
function and report. The default Zone Types are listed on page 18. **(See locations 111-149, pages 33-36)**

Page 6

---

## Page 7

**PROGRAMMING THE NX-8 LED KEYPADS**

This section describes how to program the address and partition of each keypad as well as the options that are
available. The address of the keypad is important because this is how the panel supervises the keypads.

The factory default for the Master code is [ **1** ]-[ **2** ]-[ **3** ]-[ **4** ] when using a 4-digit code or [ **1** ]-[ **2** ]-[ **3** ]-[ **4** ]-[ **5** ]-[ **6** ] for a 6-digit
code. The factory default for the "Go To Program" code is [ **9** ]-[ **7** ]-[ **1** ]-[ **3** ] for a 4-digit code or [ **9** ]-[ **7** ]-[ **1** ]-[ **3** ]-[ **0** ]-[ **0** ] for a
6-digit code.

**[** r **] [9] [2]**
**(Applies to LED keypad ONLY)**
**1)** Enter [ r ] [ **9** ] [ **2** ] [ **program code** ].
2) Enter the zone number (1 - 48) you want the keypad to start at.
3) Enter [ r ] to save and exit.

**[** r **]-[9]-[3] Set keypad options**
**1)** Enter [ r ]-[ **9** ]-[ **3** ] [ **program code** ]- **The "Service" LED will flash** .
**2)** LEDs 1-8 can now be toggled on/off to enable/disable the following functions:
**3)** After enabling/disabling the desired functions press [ r ]


| LED |  |  | Keypad Feature Enabled |
| --- | --- | --- | --- |
| 1 |  | RESERVED. DO NOT PROGRAM THIS AT ALL! |  |
| 2 |  | Enable Silent Keypad option. Silences the entry/exit sounder & chime only. |  |
| 3 |  | Enable Ding Dong sound for Chime - If off, chime will be a single tone. (See location 40, page 22) |  |
| 4 |  | Enable Keypress Silence option (silences the pulsing keypad sounder for 5 seconds when a key is pressed) |  |
| 5 |  | Enable Armed Status Suppression (will not allow the keypad to display faulted or bypassed zones when the system is armed) |  |
| 6 |  | Enable Panic, Fire, Medical Beeptone (will sound a short beep to verify that the keypress was accepted) |  |
| 7 |  | Suppresses the "Service" LED (NOTE: For UL installations, the Service LED shall not be suppressed.) (will not allow the "Service" LED to illuminate for any reason. If there is a system trouble, pressing [r]-[2] will still show the service menu.) |  |
| 8 |  | Enable multi-partition viewing (enables temporary viewing of all partitions by pressing [r]-[1]-[partition number]) |  |


**[** r **]-[9]-[4] Set Keypad Number and Partition**
**1)** Enter [ r ]-[ **9** ]-[ **4** ]-[ **program code** ]- **The "Service" LED and the "Instant" LED will flash.**
**2)** Enter the keypad number (1-8)
**3)** Press [ r ]- **The "Instant" LED will illuminate steady and the"Service" LED will remain flashing** .
**4)** Enter the partition number for the keypad (The keypad will automatically exit this mode at this time)

**[** r **]-[9]-[5] Set elapsed increments since last autotest**
**1)** Enter [ r ]-[ **9** ]-[ **5** ]-[program code]- **The "Service" LED will flash.**
**2)** Enter [100's digit] -[10's digit]-[1's digit]-[#]

**[** r **]-[9]-[6]** **Set system date**
**1)** Enter [ r ]-[ **9** ]-[ **6** ]-[master code].
**The "Service" LED will flash.**
**2)** Enter [day of week (1=Sun)]-[month 10's digit]-[month 1's digit]-[day 10's digit]
[day 1's digit] -[year 10's digit]-[year 1's digit]

**[** r **]-[9]-[7]** **Set system clock**
**1)** Enter [ r ]-[ **9** ]-[ **7** ]-[master code].
**The "Service" LED will flash.**
**2)** Enter [hour 10's digit]-[hour 1's digit]-[minutes 10's digit]-[minutes 1's digit]

Page 7

---

## Page 8

**CHANGING USER CODES:**
**1)** Enter [ r ]-[ **5** ]-[ **master code** ] - The "Ready" LED will flash.
**2)** Enter the 2 digit user number (always 2 digits such as "03" for user 3) - The "Ready" LED will illuminate
steady.
**3)** Enter the new user code designated for that individual - The "Ready" LED will flash indicating that the code
was accepted. If it rejects the code, the sounder will beep 3 times,
***Note for NX1300 Series LED Keypad*** : The zone lights will illuminate indicating the first digit of the “user
code”. (Lights 1-8 on = code is blank; lights 1-8 off = “0”; lights 1 and 8 = “9”.) Use the up and down scroll
keys to view the next digit or enter a new 4- or 6-digit “user code”. While using the scroll keys you can
change any digit by entering a new digit. This will advance you to the next digit.
**4)** If another user code needs to be programmed, return to step 2.
**5)** Press [ **#** ] while the "Ready" LED is flashing to exit the User Code Programming Mode.

**ASSIGNING AUTHORITY LEVEL:**
**1)** Enter [ r ]-[ **6** ]-[ **master code** ] - The "Ready" LED will flash.
**2)** Enter [2 digit user number] (always 2 digits such as 03 for user 3) - The "Ready" LED will illuminate steady
and the "Instant" LED will flash. Refer to the chart below for the description of each LED. Turn the LED on
for the features that you desire **.**


|  | LED |  |  | ATTRIBUTES IF LED 8 IS OFF | LED |  |  | ATTRIBUTES IF LED 8 IS ON |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 |  |  | Reserved |  | 1 |  | Activate output #1 |  |  |
| 2 |  |  | Arm Only |  | 2 |  | Activate output # 2 |  |  |
| 3 |  |  | Arm Only After Close Window |  | 3 |  | Activate output # 3 |  |  |
| 4 |  |  | Master arm/disarm (can program other codes) |  | 4 |  | Activate output # 4 |  |  |
| 5 |  |  | Arm/disarm code |  | 5 |  | Arm/disarm |  |  |
| 6 |  |  | Allowed to bypass zones (see location 23) |  | 6 |  | Bypass Zones |  |  |
| 7 |  |  | Code will send open / close reports |  | 7 |  | Open / Close Reporting |  |  |
| 8 |  |  | If this LED is on, LEDs 1-7 will use the chart to the right |  | 8 |  | If this LED is off, LEDs 1-7 use the chart to the left |  |  |


**3)** Enter [ r ] - The "Instant" LED will illuminate steady.
This moves you to the partition enable. (This tells the system what partition this user can arm/disarm.
LEDs 1-8 illuminate for each partition that the user has authorization for. To change any of these
numbers, press 1-8 to permit or deny access to the user.
(Example: If LED #2 is lit, then user has
assigned access to that partition. By pressing the [ **2** ] key, the LED will go off indicating the user has
been denied access to that partition.)
**4)** Enter [ r ]
This returns you back to step 2 above. At this point you may enter another user number to assign
attributes for. You may continue this procedure until you have assigned authority levels to all user
numbers - or - you may press [ **#** ] key to exit the Assigning Authority Level Program.

***NOTE:*** ***Any*** ***master*** ***arm/disarm*** ***code*** ***can*** ***add*** ***or*** ***change*** ***a*** ***user*** ***code*** ***if*** ***the*** ***master*** ***code*** ***has*** ***access*** ***to*** ***the***
***same partitions as the code being added/changed.*** ***Consequently, when programming the user codes***
***for a partitioned system*** *,* ***leave at least one code (can be "go to program code" if enabled in location***
***43) access to all partitions or you will not be able to add new users.*** ***If you desire the end user to be***
***able to add new codes, you must remove the partition authority from all blank codes.***

**[** r **]-[9]-[8]**
Pressing [ r ]-[ **9** ]-[ **8** ] while the system is disarmed will cause the control to do a callback for a download.
***NOTE: A valid user code may be required after [*** r ***]-[9]-[8] if enabled in location 41, page 22.***

**[** r **]-[9]-[9]**
Pressing [ r ]-[ **9** ]-[ **9** ] while the system is disarmed will cause the control panel to seize the phone line for a
download. ***NOTE: A valid user code may be required after [*** r ***]-[9]-[9] if enabled in location 41.***

Page 8

---

## Page 9

**PROGRAMMING THE NX-8 CONTROL**

**ENTERING THE PROGRAM MODE:** To enter the Program Mode, press [ r ]-[ **8** ]. At this time, the five function LEDs
(Stay, Chime, Exit, Bypass, & Cancel) will begin to flash. Next, enter the "Go To Program Code" (FACTORY
DEFAULT IS [ **9** ]-[ **7** ]-[ **1** ]-[ **3** ]). If the "Go To Program Code" is valid, the "Service" LED will flash and the five function
LEDs will illuminate steady. You are now in the Program Mode and ready to select the module to program.

**SELECTING THE MODULE TO PROGRAM:** Since all modules connected to the NX-8 are programmed through the
keypad, the module you are programming should be the first entry. To program the NX-8 Control Panel, enter [ **0** ]-[ **#** ].
The [ **0** ] is the module number of the control and the [ **#** ] is the entry key. Other module entry numbers can be found in
their corresponding manuals.

**PROGRAMMING A LOCATION:** Once the number of the module to be programmed has been entered, the "Armed"
LED will illuminate, indicating it is waiting for a programming location to be entered. Any location can be accessed by
directly entering the desired programming location followed by the pound [ **#** ] key. If the location entered is a valid
location, the "Armed" LED will extinguish, the "Ready" LED will illuminate and the binary data for the first segment of
this location will be shown by the zone LED's. While entering new data, the "Ready" LED will begin flashing to indicate
a data change in process. The flashing will continue until the new data is stored by pressing the [ r ] key. Upon
pressing the [ r ] key, the keypad will advance to the next segment and display its data. This procedure is repeated
until the last segment is reached. Pressing the [ **#** ] key will exit from this location, and the "Armed" LED will illuminate
again waiting for a new programming location to be entered. If the desired location is the next sequential location,
press the [POLICE] key. If the previous location is desired press the [FIRE] key. If the same location is desired press
the [MEDIC] key. To review the data in a location, repeat the above procedure, pressing the [ r ] key without any
numeric data entry. Each time the [ r ] key is pressed, the programming data of the next segment will be displayed for
review.

**EXITING A LOCATION:** After the last segment of a location is programmed, pressing the [ r ] key will exit that location,
turn the "Ready" LED off and the "Armed" LED on. The [ r ] key must be pressed or the data will not be saved. To exit
before the last segment, press [ **#** ]. As before, you are now ready to enter another programming location. If an attempt
is made to program an invalid entry for a particular segment, the keypad sounder will emit a triple error beep (beep,
beep, beep), and remain in that segment awaiting a valid entry.

**EXITING THE PROGRAM MODE :** When all the desired changes in programming have been made, it is time to exit
the program mode. Pressing the [Exit] key will exit this programming level, and go to the "Select a Module To
Program" level. If no additional modules are to be programmed, pressing the [Exit] key again will exit the program
mode. If there is a module to be programmed, it may be selected by entering its address followed by the [ **#** ] key (see
"Selecting the Module To Program" above). The procedure for programming these devices is the same as for the
control panel, except the locations will be for the module selected.

**PROGRAMMING DATA**

Programming data is always one of two types. One type of data is numerical and can take on values from 0 -15 or 0 -
255 depending on the location's segment. The other type of data is a feature selection type. Feature selection data is
used to turn features on or off. Use the following procedures when working with these two data types:

**NUMERICAL DATA:** Numerical data is programmed by entering a number from 0-255 on the numeric keys of the
system keypad. To view the data in a location, a binary process is used. With this process, the LED = s for zones 1
through 8 are utilized, and the numeric equivalents of their illuminated LED = s are added together to determine the data
in a programming location. The numeric equivalents of these LED = s are as follows:
Zone 1 LED = **1**
Zone 2 LED = **2**
Zone 3 LED = **4**
Zone 4 LED = **8**

Zone 5 LED = **16**
Zone 6 LED = **32**
Zone 7 LED = **64**
Zone 8 LED = **128**
Example: If the numerical data to be programmed in a location is "66", press [ **6** ]-[ **6** ] on the keypad. The LED = s for
Zone 2 and Zone 7 will become illuminated indicating 66 is in that location (2 + 64 = 66). See this example on page
10. Once the data is programmed, press the [ r ] key to enter the data and advance to the next segment of that
location. After the last segment of a location is programmed, pressing the [ r ] key will exit that location, turn the
"Ready" LED off and the "Armed" LED on. As before, you are now ready to enter another programming location. If an
attempt is made to program a number too large for a particular segment, the keypad sounder will emit a triple beep,
indicating an error, and remain in that segment awaiting a valid entry.

On the LCD keypad, the number in the location will be displayed.
For locations with a maximum of 15, the
hexidecimal equivalent will be displayed in parenthesis. Example: **11 (B)** or **14 (E)** .

Page 9

---

## Page 10

**PROGRAMMING EXAMPLE TO BE INSERTED HERE.**

Page 10

---

## Page 11

**FEATURE SELECTION DATA:** Feature selection data will display the current condition (on or off) of eight features
associated with the programming location and segment selected. Pressing a button on the touchpad (1 thru 8) that
corresponds to the "feature number" within a segment, will toggle (on/off) that feature. Pressing any numeric key
between [ **1** ] and [ **8** ] for selection of a feature, will make the corresponding LED illuminate (feature ON). Press the
number again, and the LED will extinguish (feature OFF). You will see that numerous features can be selected from
within one segment. For instance, if all eight features of a segment are desired, pressing [ **1** ]-[ **2** ]-[ **3** ]-[ **4** ]-[ **5** ]-[ **6** ]-[ **7** ]-[ **8** ] will
turn on LED's 1 thru 8 as you press the keys, indicating that those features are enabled. **LCD Keypad Users Note: The**
**numbers of the enabled features will be displayed.** **However, the features not enabled will display a hyphen (-).** After the
desired setting of features is selected for this segment, press the [ r ] key. This will enter the data and automatically
advance to the next segment of the location. When you are in the last segment of a location and press the [ r ] to enter
the data, you will exit that location. This will now turn the "Ready" LED off and the "Armed" LED on. As before, you
are now ready to enter another programming location.

**LOADING FACTORY DEFAULTS**
To load the factory defaults, enter the program mode using the procedure on page 9, then type [ **9** ]-[ **1** ]-[ **0** ]-[ **#** ]. The
keypad will beep 3 times indicating that the loading is in progress. The loading takes about 6 seconds.

**ENROLLING MODULES AND KEYPADS**
For supervision purposes, the NX-8 has the ability to automatically find and store in its memory, the presence of all
keypads, zone expanders, wireless receivers, and any other module connected to the data terminal. This allows these
modules to be supervised by the control panel. To enroll the modules, enter the Program Mode of the NX-8 control
panel as described on page 9. When the Program Mode is exited, the NX-8 control will automatically enroll the
devices. The enrolling process takes about 12 seconds, during which time the "Service" LED will illuminate. User
codes will not be accepted during the enrolling process. If a speaker is attached to the NX-8, it will click at this time. If
a siren or bell is attached to the NX-8, it will sound for about 1 second. Once a module is enrolled, if it is not detected
by the control, the "Service" LED will illuminate.

L
**QUICK START INSTALLATION**
For most routine installations, the "Quick Start" option will allow for enabling a majority of the options available with the
NX-8, when communicating in Contact ID or SIA formats and without partitioning. The "Quick Start" locations can be
identified by the L symbol.

**CONTROL PANEL PROGRAMMING LOCATIONS**
L
**LOCATION 0** - **PHONE NUMBER 1** **(20 segments, numerical data)**
The first telephone number is programmed in location 0. A "14" indicates the end of the phone number. Delays of four
seconds can be programmed at any point in the phone number by programming a "13" in the appropriate segment. If
tone dialing is desired, program a "15" in the segment where tone dialing should begin. If the entire number should be
tone dialing, program a "15" in the first segment. Program an A 11" for a A r @ , and a A 12" for a A # @ .

L
**LOCATION 1 - ACCOUNT CODE FOR THE PHONE #1** **(6 segments, numerical data)**
The account code sent when Phone #1 is dialed is programmed in location 1. Program a A 10" in the segment
immediately after the last digit of the account code.
If the account code is 6 digits long, program all 6 segments.

L
**LOCATION 2 - COMMUNICATOR FORMAT FOR PHONE #1** **(1 segment, numerical data)**
Location 2 contains the communicator format used to transmit to the receiver connected to Phone #1. Consult the
instructions for your central station receiver to determine which format is compatible. Select a format from the list on
the following page. If you require a format other than those listed, review the override options described in location 18,
to build the appropriate format. A "15" must be programmed in location 2 in addition to the entries in location 18 in
order to create a special format. If this location contains a "0", the built-in communicator will be disabled, and the NX-
8 will function as a local only control.

L
**LOCATION 3 - DIAL ATTEMPTS/BACKUP CONTROL FOR PHONE # 1** **(2 segments, numerical data)**

**Segment 1- Dial attempts:** Location 3, Segment 1 is used to enter the number of dial attempts ( 1 to 15 Attempts) the
communicator will make to Phone #1 before ending the notification process.
Factory default is "8" and the
communicator will make eight (8) attempts to the first number.

Page 11

---

## Page 12

**Segment 2- Phone #1 Backup Control:** Programming a " **0** " in Segment 2 of this location will cause the NX-8 to make
the designated number of attempts to Phone #2 before setting the "Fail To Communicate" condition and stop
reporting. Programming a " **1** " in this segment will cause the NX-8 to stop trying to communicate after the designated
number of attempts have been made to Phone #1. If a " **2** " is programmed in this segment, it will cause the NX-8 to
make the dial attempts in increments of two. The first two attempts will be made to Phone #1, the next two attempts to
Phone #2, then repeating until the total number of attempts designated in Segment 1 is completed.

**FORMAT SELECTIONS**


| DATA |  |  | FORMAT |  | DESCRIPTION |
| --- | --- | --- | --- | --- | --- |
| 0 |  | Local |  |  | Communicator is disabled |
| 1 |  | Universal 4+2 |  |  | Two digit event code 1800hz transmit 2300hz handshake double round parity 40pps |
| 2 |  | 3+1 fast (or 4+1) |  |  | One digit event code 1900Hz transmit 1400Hz handshake double round parity 20pps |
| 3 |  | Reserved |  |  | Reserved |
| 4 |  | Pager |  |  | 2 digit event code DTMF transmission |
| 5 |  | 3/1 or 4/1 slow |  |  | 1800hz transmit 2300hz handshake double round parity 20 p.p.s. hex capability |
| 6 |  | 3/1 or 4/1 slow |  |  | 1800hz transmit 1400hz handshake double round parity 20 p.p.s. hex capability |
| 7 |  | 3/1 or 4/1 fast |  |  | 1800hz transmit 2300hz handshake double round parity 40 p.p.s. hex capability |
| 8 |  | 3/1 or 4/1 fast |  |  | 1800hz transmit 1400hz handshake double round parity 40 p.p.s. hex capability |
| 9 |  | 3/1 or 4/1 fast with parity |  |  | 1800hz transmit 2300hz handshake single round w/parity 40 p.p.s. hex capability |
| 10 |  | 3/1 or 4/1 fast with parity |  |  | 1800hz transmit 1400hz handshake single round w/parity 40 p.p.s. hex capability |
| 11 |  | 4+2 express |  |  | 2 digit event code DTMF transmission |
| 12 |  | 4+2 fast |  |  | Two digit event code 1900hz transmit 1400hz handshake double round parity 20 p.p.s. |
| 13 |  | Ademco Contact ID |  |  | DTMF (see pages 51-52) |
| 14 |  | SIA |  |  | FSK (see pages 51-52) |
| 15 |  | Custom format |  |  | (See location 18, page 16) |


**REPORTING EVENTS TO PHONE NUMBER 1**
Phone #1 has two programming locations that are used to select which events are reported to this phone number.
Location 4 is used to select which events are reported to Phone #1. Location 5 is used to select which partitions are
reported to Phone #1. If dual or split reporting is not desired, location 4 should be used to select all events to Phone
#1 and location 5 should be left at the factory default of "0". If dual or split reporting is desired, and the split is based
on the event type (such as alarm, open/close, etc.), location 4 should be used to select only those events that should
be reported to Phone #1 and location 5 should be left at the factory default of "0". If dual or split reporting is desired,
and the split is based on partition, location 4 should be programmed as a "0" and location 5 should be used to select
those partitions that should be reported to Phone #1.
If no events should be reported to Phone #1, both locations
should be programmed as "0" (disabling all options).

**LOCATION 4 - EVENTS REPORTED TO PHONE # 1** **(2 segments, feature selection data)**

**Segment 1:**
1 = Alarms and Alarm Restores.
2 = Opening and Closings.
3 = Zone Bypass and Bypass Restores.
4 = Zone Trouble and Trouble Restores.
5 = Power Fail, Low Battery, Power Restore, and Low Battery Restore.
6 = Bell Cut , Telephone Line Cut, Bell Cut Restore, Telephone Line Restore.
7 = Test Reports.
8 = Start and End programming, Download complete.

Page 12

---

## Page 13

**Segment 2:**
1 = Zone and Box Tamper and Tamper Restore.
2 = Auxiliary Power Overcurrent, Ground Fault, and Restore for both.
3 = Wireless Sensor Missing and Restore.
4 = Wireless Sensor Low Battery and Restore.
5 = Expander Trouble and Restore.
6 = Fail To Communicate.
7 = Reserved.
8 = Reserved.

**LOCATION 5 - PARTITIONS REPORTED TO PHONE #1**
**(1 segment, feature selection data)**
Location 5 is used when events to be reported to a phone number are based upon the partition regardless of the
event. If this location is used, location 4 should be programmed as "0".

**Segment 1:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

L
**LOCATION 6** - **PROGRAMMING PHONE #2** **(20 segments, numerical data)**
Phone #2 is programmed in location 6. A "14" indicates the end of the phone number. Delays of four seconds can be
programmed at any point in the phone number by programming a "13" in the appropriate segment. If tone dialing is
desired, program a "15" in the segment where tone dialing should begin. If the entire number should be tone dialing,
program a "15" in the first segment. Program an A 11" for a A r @ , and a A 12" for a A # @ .

L
**LOCATION 7 - ACCOUNT CODE FOR THE PHONE #2** **(6 segments of numerical data)**
The account code sent when Phone #2 is dialed is programmed in location 7. Program a A 10" in the segment
immediately after the last digit of the account code. If the account code is 6 digits long, program all 6 segments. If
this location is left unprogrammed, account code 1 will be used when the second phone number is dialed.

L
**LOCATION 8 - COMMUNICATOR FORMAT FOR PHONE # 2** **(1 segment, numerical data)**
Location 8 contains the communicator format used to transmit to the receiver connected to Phone #2. Consult the
instruction manual for your central station receiver to determine which format is compatible, and select from the 15
formats listed on page 12. If you require a format other than those listed, review the override options described in
Location 18 to build the appropriate format. A "15" must be programmed in location 8 in addition to the entries in
location 18 in order to create a special format. If this location contains a "0", format 1 will be used when Phone #2 is
dialed.

**LOCATION 9 - DIAL ATTEMPTS/BACKUP CONTROL FOR PHONE #2** **(2 segments, numerical data)**

**Segment 1, Dial attempts:** Segment 1 of Location 9 is used to enter the number of dial attempts (1 to 15 attempts)
the communicator will make to Phone #2 before ending the notification process. Factory default is "8" and the
communicator will make the same number of attempts as those programmed in location 3.

**Segment 2, Phone #2 Backup Control:** Programming a " **0** " in Segment 2 of this location will cause the NX-8 to make
the designated number of attempts to Phone #1 before setting the "Fail To Communicate" condition and stop
reporting. Programming a " **1** " in this segment will cause the NX-8 to stop trying to communicate after the designated
number of attempts have been made to Phone #2. If a " **2** " is programmed in this segment, it will cause the NX-8 to
make the dial attempts in increments of two. The first two attempts will be made to Phone #2, the next two attempts to
Phone #1, then repeating until the total number of attempts designated in Segment 1 is completed.

Page 13

---

## Page 14

**REPORTING EVENTS TO PHONE NUMBER 2**

Phone #2 can be used to back up Phone #1 or for a second receiver to multi-report or split report events. Phone #2
has two programming locations that are used to select which events are reported to this phone number. Location 10 is
used to select which events are reported to Phone #2, and location 11 is used to select which partitions are reported to
Phone #2. If dual or split reporting is not desired, location 10 and location 11 should be left at the factory default of
"0". If multi-reporting or split reporting is desired, and the split is based on the event type (such as alarm, open close
etc.), location 10 should be used to select only those events that should be reported to Phone #2, and location 11
should be left at the factory default of "0". If dual or split reporting is desired, and the split is based on partition, then
location 10 should be programmed as "0", and location 11 should be used to select those partitions that should be
reported to the Phone #2. If no events should be reported to Phone #2, both locations should be "0".

**LOCATION 10 - EVENTS REPORTED TO PHONE #2**
**(2 segments of feature selection data)**

**Segment 1:**
1 = Alarms and Alarm Restores.
2 = Opening and Closings.
3 = Zone Bypass and Bypass Restores.
4 = Zone Trouble and Trouble Restores.
5 = Power Fail, Low Battery, Power Restore, and Low Battery Restore.
6 = Bell Cut , Telephone Line Cut, Bell Cut Restore, Telephone Line Restore.
7 = Test Reports.
8 = Start and End programing, Download complete.

**Segment 2:**
1 = Zone and Box Tamper and Tamper Restore.
2 = Auxiliary Power Overcurrent and Ground Fault and Restore for both.
3 = Sensor Missing and Restore.
4 = Sensor Low Battery and Restore.
5 = Expander Trouble and Restore.
6 = Fail To Communicate.
7 = Reserved.
8 = Reserved.

**LOCATION 11 - PARTITIONS REPORTED TO PHONE #2**
**(1 segment, feature selection data)**
Location 11 is used when events to be reported to a phone number are based upon the partition regardless of the
event. If this location is used, location 10 should be "0".

**Segment 1:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

**LOCATION 12** - **PROGRAMMING PHONE #3**
**(20 segments, numerical data)**
Phone #3 is programmed in location 12. A "14" indicates the end of the phone number. Delays of four seconds can
be programmed at any point in the phone number by programming a "13" in the appropriate segment. If tone dialing is
desired, program a "15" in the segment where tone dialing should begin. If the entire number should be tone dialing,
program a "15" in the first segment. Program an A 11" for a A r @ , and a A 12" for a A # @ .

**LOCATION 13 - ACCOUNT CODE FOR PHONE #3** **(6 segments, numerical data)**
The account code sent when Phone #3 is dialed is programmed in location 13. Program a A 10" in the segment
immediately after the last digit of the account code. If the account code is 6 digits long, program all 6 segments. If
location 6 is left unprogrammed, account code 1 will be used when the Phone #3 is dialed.

**LOCATION 14 - COMMUNICATOR FORMAT FOR PHONE #3**
**(1 segment, numerical data)**
Location 14 contains the communicator format used to transmit to the receiver connected to phone #3. Consult the
instruction manual for your central station receiver to determine which format is compatible, and select from the 15
formats listed on page 12. If you require a format other than those listed, review the override options described in
Location 18 to build the appropriate format. A "15" must be programmed in location 14 in addition to the entries in
location 18 in order to create a special format. If this location contains a "0", format 1 will be used when Phone #3 is
dialed.

Page 14

---

## Page 15

**LOCATION 15 - DIAL ATTEMPTS/BACKUP CONTROL FOR PHONE #3** **(2 segments, numerical data)**

**Segment 1, Dial Attempts:** Segment 1 of Location 15 is used to enter the number of dial attempts (1 to 15 attempts)
the communicator will try to Phone #3 before ending the notification process.
Factory default is "8" and the
communicator will make the same number of attempts as those programmed in location 3.

**Segment 2, Phone # 3 Backup Control:** Programming a " **0** " in Segment 2 of this location will cause the NX-8 to
make the designated number of attempts to Phone #2 before setting the "Fail To Communicate" condition and stop
reporting. Programming a " **1** " in this segment will cause the NX-8 to stop trying to communicate after the designated
number of attempts have been made to Phone #3. If a " **2** " is programmed in this segment, it will cause the NX-8 to
make the dial attempts in increments of two. The first two attempts will be made to Phone #3, the next two attempts to
Phone #2, then repeating until the total number of attempts designated in Segment 1 is completed.

**REPORTING EVENTS TO PHONE NUMBER 3**

Phone #3 can be used for a third receiver to multi-report or split report events. Phone #3 has two programming
locations that are used to select which events are reported to this phone number. Location 16 is used to select which
events are reported to Phone #3, and Location 17 is used to select which partitions are reported to Phone #3. If dual
or split reporting is not desired, location 16 and location 17 should be left at the factory default of "0". If multi-reporting
or split reporting is desired and the split is based on the event type (such as alarm, open/close, etc.), then location 16
should be used to select only those events that should be reported to Phone #3 and location 17 should be left at the
factory default of "0". If dual or split reporting is desired, and the split is based on partition, then location 16 should be
programmed to "0" and location 17 should be used to select those partitions that should be reported to Phone #3. If
no events should be reported to Phone #3, both locations should be "0".

**LOCATION 16 - EVENTS REPORTED TO PHONE #3**
**(2 segments, feature selection data)**
**Segment 1:**
1 = Alarms and Alarm Restores.
2 = Opening and Closings.
3 = Zone Bypass and Bypass Restores.
4 = Zone Trouble and Trouble Restores.
5 = Power Fail, Low Battery, Power Restore, and Low Battery Restore.
6 = Bell Cut, Telephone Line Cut, Bell Cut Restore, Telephone Line Restore.
7 = Test Reports.
8 = Start and End programming, Download complete.

**Segment 2:**
1 = Zone and Box Tamper and Tamper Restore.
2 = Auxiliary Power Overcurrent and Ground Fault and Restore for both.
3 = Sensor Missing and Restore.
4 = Sensor Low Battery and Restore.
5 = Expander Trouble and Restore.
6 = Fail To Communicate.
7 = Reserved.
8 = Reserved.

**LOCATION 17 - PARTITIONS REPORTED TO PHONE #3** **(1 segment, feature selection data)**
Location 17 is used when events to be reported to a phone number are based upon the partition regardless of the
event. If this location is used, location 16 should be "0".

**Segment 1:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

Page 15

---

## Page 16

**LOCATION 18 - CUSTOM COMMUNICATOR FORMAT** **(See locations 2, 8, &14)**

**Segment 1:**
1 = On for 1800hz transmit; Off for 1900hz.
2= On for 2300hz handshake; Off for 1400hz.
3= On for cksum parity; Off for double round parity.
4= On for 2 digit event code; Off for 1 digit event code.
5= Reserved.
6= Reserved.
7= On for 20 p.p.s.; Off for 10 or 40 p.p.s.
8= On for 10 p.p.s.; Off for 20 or 40 p.p.s.

**Segment 2 :**
1= On for pager format (no handshake required).
2= On for 1400/2300 handshake.
3= Reserved
4= Reserved.
5= On for Contact ID.
6= On for SIA.
7= On for Contact ID or 4+3.
8= On for DTMF.

**Segment 3 & 4:** Reserved.

L
**LOCATION 19 - DOWNLOAD ACCESS CODE** **(8 segments,** **numerical data)**
Location 19 contains the eight digit access code the NX-8 must receive from the downloading software before the
panel will permit downloading to occur. The factory default code is 84800000.

L
**LOCATION 20 - NUMBER OF RINGS TO ANSWER**
**(1 segment,** **numerical data)**
Location 20 contains the number of rings to answer for a download. Enter a number from A 0" (disabled) to "15".
Factory default is "8" and the NX-8 will answer on 8 rings.

L
**LOCATION 21 - DOWNLOAD CONTROL** **(1 segment,** **feature selection data)**
Location 21 contains the feature selections for the controlling of download sessions. The following features can be
enabled or disabled using this location. (See the feature definitions beginning on page 3)
**Segment 1:**
1 -
On enables two call answering machine defeat.
2 -
On enables tone sniff answering machine defeat.
3 -
On requires call back before download session.
4 -
Shutdown **(can only be viewed from the keypad, must be changed through downloading)** .
5 -
On locks all local programming. **(can only be viewed from the keypad, must be changed through**
**downloading)**
6 -
On locks programming of all locations associated with the communicator **(can only be viewed from the**
**keypad, must be changed through downloading)**
7 -
On locks out download section. **(can only be viewed from the keypad, must be changed through**
**downloading.** **If "On", locations 19 - 22 cannot be viewed from the keypad; can only be viewed**
**from the keypad when "Off".)**
8 -
On enables call back at auto test interval.

L
**LOCATION 22 - DOWNLOAD CALL BACK NUMBER (20 segments,** **numerical data)**
If a telephone number is programmed into this location, and "Require Callback" is enabled in location 21, the control
panel will hang up for approximately 36 seconds (ensuring that the calling party has disconnected), and then call back.
If tone dialing is desired, program an "15" in the segment where tone dialing should begin. If the entire number should
be tone dialing, program an A 15" in the first segment. Four-second delays can be obtained anywhere in the sequence
by programming a "13" in the appropriate delay location. **WARNING:** THE CALLBACK PHONE NUMBER SHOULD
ALWAYS BE REVIEWED FOR ACCURACY BEFORE DISCONNECTING.

Page 16

---

## Page 17

L **LOCATION 23 - PARTITION 1,** **FEATURE AND REPORT SELECTIONS** **(3 segments,** **feature selection data)**
Location 23 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system. In addition, certain communicator reports are enabled in location 23. Each of these features can be enabled
by partition. For additional partition information see locations 88-109 on pages 30-33. **If** **the** **feature** **selection**
**location for any partition is left blank, that partition will use this location for the feature selection.**

This location contains 3 segments of 8 features each. (See the feature definitions beginning on page 3.)

**Segment 1:**
1 - On enables the Quick Arm feature.
2 - On enables the Re-exit feature.
3 - On enables the Automatic Bypass feature.
4 - On enables the Silent Keypad Panic feature **(overrides the audible panic selection)** .
5 - On enables the Audible Keypad Panic feature.
6 - On enables the Keypad Aux 1 feature (FIRE).
7 - On enables the Keypad Aux 2 feature (MEDICAL).
8 - On enables the Keypad Multiple Code Attempt Tamper feature.

**Segment 2 :**
1 - On enables the LED Extinguish feature.
2 - On enables the Require Code for Bypassing feature.
3 - On enables the Zone Bypassed Sounder Alert feature.
4 - On enables the AC Power/Low Battery Sounder Alert feature.
5 - On enables Bypass toggle.
6 - On enables Silent Auto Arm.
7 - On enables the Automatic Instant feature.
8 - Reserved.

**Segment 3:**
1 - On enables Opening and Closing reports.
2 - On enables Zone Bypass reporting.
3 - On enables Zone Restore reporting.
4 - On enables Zone Trouble reporting.
5 - On enables Zone Tamper reporting.
6 - On enables the Cancel reporting.
7 - On enables the Recent Closing report.
8 - On enables the Exit Error report.

L
**LOCATION 24 - ENTRY / EXIT TIMERS (4 segments, numerical data)**
Location 24 is used to program the Entry/Exit times. There are 2 separate Entry/Exit times.

**Segment 1,**
**Entry time 1:** This is the entry time that will be used when a delay 1 zone type initiates an entry delay
Valid entries are 10-255 seconds.
**Segment 2,**
**Exit time 1:**
This is the exit time that will be used for all zones designated as delay 1. Valid entries
are 10-255 seconds.
**Segment 3,**
**Entry time 2** : This is the entry time that will be used when a delay 2 zone type initiates an entry delay.
Valid entries are 10-255 seconds.
**Segment 4,**
**Exit time 2:**
This is the exit time that will be used for all zones designated as delay 2. Valid entries
are 10-255 seconds.

Page 17

---

## Page 18

**DEFAULT ZONE TYPES (Configurations)**

Zones can be programmed to be one of twenty different zone types (configurations). Zone types # 17 - 20 can be
used for wireless or hardwired zones using European double EOL configuration. The default zone types are listed
below. These zone types can be customized by programming locations 110-149.


| DATA | DESCRIPTION OF DEFAULT ZONE TYPES |
| --- | --- |
| "1" | DAY ZONE - Instant when system is armed trouble zone when system is disarmed. |
|  | 24-HOUR AUDIBLE - Creates an instant yelping siren alarm regardless of the armed state of the control panel. |
| "2" |  |
|  |  |
|  | ENTRY/EXIT DELAY 1- A trip will start entry delay 1. The lack of a trip during exit delay will enable the Automatic Bypass or Instant mode if so programmed. |
| "3" |  |
|  |  |
|  | FOLLOWER WITH AUTO- BYPASS DISABLED - This zone will be instant when the system is armed and no entry or exit delays are being timed. It is delayed during entry and exit delay times. This zone will not automatically bypass even if enabled in Segment 1 of Location 23. |
| "4" |  |
|  |  |
|  | INTERIOR FOLLOWER WITH AUTO- BYPASS ENABLED - This zone will be instant when the system is armed and no entry or exit delay is being timed. It is delayed during entry and exit delay times. This zone will automatically bypass if enabled in Segment 1 of Location 23. |
| "5" |  |
|  |  |
| "6" | INSTANT - This zone creates an instant alarm whenever it is tripped and the Armed LED is on. |
|  | 24-HOUR SILENT - Creates an instant silent alarm regardless of the armed state of the control panel. It will not display on the keypad. |
| "7" |  |
|  |  |
|  | FIRE - This zone will light the Fire LED and sound the temporal siren each time the zone is shorted. It will also rapidly flash the Fire LED indicating a trouble if the zone is open. |
| "8" |  |
|  |  |
|  | ENTRY/EXIT DELAY 2- A trip will start entry delay 2. The lack of a trip during exit delay will enable the Automatic Bypass or Instant mode if so programmed. |
| "9" |  |
|  |  |
|  | 24-HOUR SILENT SUPERVISED- Creates an instant silent alarm regardless of the armed state of the control panel. It will display on the keypad. |
| "10" |  |
|  |  |
|  | KEYSWITCH ZONE - This zone type will arm and disarm the partition or partitions of the control panel that it resides in each time the zone is shorted. Keyswitch arming will report as user #99. |
| "11" |  |
|  |  |
|  | INTERIOR FOLLOWER WITH "CROSS ZONE" ENABLED - This zone will be instant when the system is armed and no entry or exit delay is being timed. It is delayed during entry and exit delay times. If a "Cross Zone" is not being timed it will start a "Cross Zone" timer. If a "Cross Zone" is being timed it will create an instant alarm. This zone will automatically bypass when enabled in Segment 1 of Location 23. |
| "12" |  |
|  |  |
|  | INSTANT ENTRY GUARD - This zone creates an instant alarm whenever it is tripped and the Stay LED is off. It will start an entry delay time 2 if it is tripped and the system is armed and the Stay LED is on. |
| "13" |  |
|  |  |
|  | ENTRY/EXIT DELAY 1 WITH GROUP BYPASS ENABLED - A trip will start entry delay 1. This zone will bypass when the "Group Bypass" command is entered at the keypad. The lack of a trip during exit delay will enable the Automatic Bypass or Instant mode if so programmed. |
| "14" |  |
|  |  |
|  | INTERIOR FOLLOWER WITH GROUP BYPASS ENABLED - This zone will be instant when the system is armed and no entry or exit delays are being timed. It is delayed during entry/exit delay times. This zone will bypass when the "Group Bypass" command is entered at the keypad. This zone will automatically bypass if enabled in Segment 1 of Location 23. |
| "15" |  |
|  |  |
|  | INSTANT WITH GROUP BYPASS ENABLED - This zone creates an instant alarm whenever it is tripped and the Armed LED is on. This zone will bypass when the "Group Bypass" command is entered at the keypad. |
| "16" |  |
|  |  |
|  | ENTRY/EXIT DELAY 1 WITH TAMPER ENABLED- A trip will start entry delay 1. The lack of a trip during exit delay will enable the Automatic Bypass or Instant mode if so programmed. This zone type can be used to enable tamper on a wireless transmitter. |
| "17" |  |
|  |  |
|  | INTERIOR FOLLOWER WITH TAMPER AND AUTO-BYPASS ENABLED - This zone will be instant when the system is armed and no entry or exit delay is being timed. It is delayed during entry and exit delay times. This zone will automatically bypass if enabled in Segment 1 of Location 23. This zone type can be used to enable tamper on a wireless transmitter. |
| "18" |  |
|  |  |
|  | INSTANT WITH TAMPER ENABLED - This zone creates an instant alarm whenever it is tripped and the Armed LED is on. This zone type can be used to enable tamper on a wireless transmitter. |
| "19" |  |
|  |  |
|  | ENTRY/EXIT DELAY 2 WITH TAMPER ENABLED-A trip will start entry delay 2. The lack of a trip during exit delay will enable the Automatic Bypass or Instant mode if so programmed. This zone type can be used to enable tamper on a wireless transmitter. |
| "20" |  |
|  |  |


Page 18

---

## Page 19

**NOTE: To “null” a zone, program the zone in “Partition Select” as zero (0) in all partitions and do not**
**use end-of-line resistors.**

L
**LOCATION 25 - ZONES 1-8 ZONE TYPE** **(8 segments, numerical data)**
Location 25 contains the Zone Type for zones 1-8. Segment 1 is for zone 1, and Segment 8 is for zone 8.
Default Zone Types are found in the table on page 18. To customize a Zone Type, see page 33.

**LOCATION 26 - PARTITION SELECT, ZONES 1-8** **(8 segments, feature selection data)**
Location 26 is used to select the partition(s) that zones 1 - 8 reside in. A zone may reside in any combination
of the 8 partitions. **If** **a** **burglary** **zone** **resides** **in** **more** **than** **1** **partition,** **it** **will** **only** **be** **active** **when** **all**
**partitions it resides in are armed.** **A zone that resides in more than 1 partition will be reported to its**
**lowest partition number.** Location 26 has 8 segments. Segment 1 corresponds to zone 1, and Segment 8
corresponds to zone 8.

**Segments 1 - 8:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

L
**LOCATION 27 - ZONES 9-16 ZONE TYPE**
**(8 segments, numerical data)**
Location 27 contains the Zone Type for zones 9 -16. Segment 1 is for zone 9, Segment 8 is for zone 16.
Default Zone Types are found in the table on page 18. To customize a Zone Type, see page 33.

**LOCATION 28 - PARTITION SELECT, ZONES 9-16**
**(8 segments, feature selection data)**
Location 28 is used to select the partition(s) that zones 9-16 reside in. A zone may reside in any combination
of the 8 partitions. **If** **a** **burglary** **zone** **resides** **in** **more** **than** **1** **partition,** **it** **will** **only** **be** **active** **when** **all**
**partitions** **are** **armed.** **A** **zone** **that** **resides** **in** **more** **than** **1** **partition** **will** **be** **reported** **to** **its** **lowest**
**partition.**
Location 28 has 8 segments. Segment 1 corresponds to zone 9 and Segment 8 corresponds to
zone 16.

**Segments 1 - 8:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

L
**LOCATION 29 - ZONES 17-24 ZONE TYPE** **(8 segments, numerical data)**
Location 29 contains the Zone Type for zones 17-24. Segment 1 is for zone 17, Segment 8 is for zone 24.
Default Zone Types are found in the table on page 18. To customize a Zone Type, see page 33.

**LOCATION 30 - PARTITION SELECT, ZONES 17-24** **(8 segments, feature selection data)**
Location 30 is used to select the partition(s) that zones 17-24 reside in.
A zone may reside in any
combination of the 8 partitions. **If a burglary zone resides in more than 1 partition, it will only be active**
**when** **all** **partitions** **are** **armed.**
**A** **zone** **that** **resides** **in** **more** **than** **1** **partition** **will** **be** **reported** **to** **its**
**lowest** **partition.**
Location 30 has 8 segments.
Segment 1 corresponds to zone 17 and Segment 8
corresponds to zone 24.

**Segments 1 - 8:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

Page 19

---

## Page 20

L
**LOCATION 31 - ZONES 25-32 ZONE TYPE GROUP**
**(8 segments, numerical data)**
Location 31 contains the Zone Type for zones 25-32. Segment 1 is for zone 25, Segment 8 is for zone 32. Default
Zone Types are found in the table on page 18. To customize a Zone Type, see page 33.

**LOCATION 32 - PARTITION SELECT, ZONES 25-32**
**(8 segments, feature selection data)**
Location 32 is used to select the partition(s) that zones 25-32 reside in. A zone may reside in any combination of the 8
partitions. **If** **a** **burglary** **zone** **resides** **in** **more** **than** **1** **partition** **it** **will** **only** **be** **active** **when** **all** **partitions** **are**
**armed.** **A** **zone** **that** **resides** **in** **more** **than** **1** **partition** **will** **be** **reported** **to** **its** **lowest** **partition.**
Segment 1
corresponds to zone 25 and Segment 8 corresponds to zone 32.

**Segments 1 - 8:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

L
**LOCATION 33 - ZONES 33-40 ZONE TYPE**
**(8 segments, numerical data)**
Location 33 contains the Zone Type for zones 33-40. Segment 1 is for zone 33 Segment 8 is for zone 40. Default
Zone Types are found in the table on page 18. To customize a Zone Type, see page 33.

**LOCATION 34 - PARTITION SELECT, ZONES 33-40**
**(8 segments of feature selection data)**
Location 34 is used to select the partition(s) that zones 33-40 reside in. A zone may reside in any combination of the 8
partitions. **If** **a** **burglary** **zone** **resides** **in** **more** **than** **1** **partition,** **it** **will** **only** **be** **active** **when** **all** **partitions** **are**
**armed.** **A** **zone** **that** **resides** **in** **more** **than** **1** **partition** **will** **be** **reported** **to** **its** **lowest** **partition.** Segment 1
corresponds to zone 33 and Segment 8 corresponds to zone 40.

**Segments 1 - 8:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

L
**LOCATION 35 -** **ZONES 41-48 ZONE TYPE**
**(8 segments of numerical data)**
Location 35 contains the Zone type for zones 41-48. Segment 1 is for zone 41 Segment 8 is for zone 48. Default
Zone Types are found in the table on page 18. To customize a Zone Type, see page 33.

**LOCATION 36 - PARTITION SELECT, ZONES 41-48**
**(8 segments, feature selection data)**
Location 36 is used to select the partition or partitions that zones 41-48 reside in. A zone may reside in any
combination of the 8 partitions. **If a burglary zone resides in more than 1 partition it will only be active when all**
**partitions** **are** **armed.** **A** **zone** **that** **resides** **in** **more** **than** **1** **partition,** **will** **be** **reported** **to** **its** **lowest** **partition.**
Location 36 has 8 segments. Segment 1 corresponds to zone 41 and Segment 8 corresponds to zone 48.

**Segments 1 -** **8:**
1 = Partition #1
2 = Partition #2
3 = Partition #3
4 = Partition #4
5 = Partition #5
6 = Partition #6
7 = Partition #7
8 = Partition #8

Page 20

---

## Page 21

L
**LOCATION 37 - SIREN AND SYSTEM SUPERVISION**
**(5 segments, feature selection data)**
Location 37 is used to enable various system feature and reporting options. (Refer to the feature definitions.)

**Segment 1:**
1 - On if siren sounds for "Telephone Line Cut" when armed.
2 - On if siren sounds for "Telephone Line Cut" when disarmed.
3 - On if siren blast at arming.
4 - On if siren blast at exit expiration.
5 - On if siren blast at closing kissoff.
6 - On if siren sounds during a "Cross Zone" verification time.
7 - On if siren sounds for a Zone or Box Tamper.
8 - On if siren blasts 1 time for keyswitch or wireless arming; 2 times for disarming.

**Segment 2:**
1 - On if siren driver should be a voltage output. Off if on board siren driver enabled.
2 - On if siren sounds for expander trouble (required for UL installations).
3 - On for Immediate Restore by zone. Off for zones to restore only when siren is off.
4 - On if Dynamic Battery Test performed at arming. Off if performed at disarming. (See location 40)
5 - On if Battery Missing Test is performed every 12 seconds.
6 - On if Manual Bell Test performed during [ r ]-[4] test function.
7 - On if Manual Communicator Test performed during [ r ]- [4] test function.
8 - On if Box Tamper terminals on the control panel are enabled.

**Segment 3:**
1 - On if Box Tamper report enabled.
2 - On if AC Fail reporting enabled.
3 - On if Low Battery reporting enabled.
4 - On if Aux. Power Overcurrent report enabled.
5 - On if Siren Supervision report enabled.
6 - On if Telephone Line Cut report enabled.
7 - On if Ground Fault Detection report enabled.
8 - On if Expander Trouble reporting enabled.

**Segment 4:**
1 - On if Fail To Communicate report enabled.
2 - On if Log Full report enabled.
3 - On if Autotest report enabled.
4 - On if Start/End programming report enabled.
5 - On if End Download report enabled.
6 - On if Sensor Low Battery report enabled.
7 - On if Sensor Missing report enabled.
8 - Reserved.

**Segment 5:**
1 = On enable Lost Clock service light.
2 = On enables Zone Doubling (requires NX-200 Zone Doubling Kit).
3 = On disables On-Board 8 zones.
4 = On will allow two trips on same cross-zone to activate an alarm.
5 = On will **not** allow zones that are force armed to report bypass.
6 = On enables Silent Exit option.
7 = Use internal crystal for clock.
8 = Disable Temporal Siren on Fire. **NOTE: Do NOT disable for UL listed systems.**

L
**LOCATION 38 - SWINGER SHUTDOWN COUNT**
Location 38 contains the number of trips during an arming cycle that the NX8 will allow before bypassing a zone. The
count determination is described in the feature definitions beginning on page 3. **NOTE: For UL installations, this**
**feature shall be disabled.**
.
L
**LOCATION 39 - KEYPAD SOUNDER CONTROL** **(1 segment, feature selection data)**
**Segment 1:**
1 - On if keypad sounds for A Telephone Line Cut @ when the system is armed.
2 - On if keypad sounds for A Telephone Line Cut @ when disarmed.
3 - On if keypad sounds upon AC Power Failure.
4 - On if keypad sounds when a Low Battery is detected.
5 - On if keypad sounds during Cross Zone trip time.
6 - On if keypad sounds for zone and box tampers.
7 - Reserved.
8 - On if keypad sounds for expander trouble (required for UL installations).

Page 21

---

## Page 22

L
**LOCATION 40 - SYSTEM TIMERS**
**(10 segments, numerical data** )
Location 40 contains the duration of various system timing functions. Example: If you desire the duration of the
Dynamic Battery Test to be 30 minutes, you should program [3]-[0]-[ r ] in segment 1 of this location. The [3]-[0] is the
number of minutes, and the [ r ] stores the data and moves to the next segment of this location.
**Segment 1** - Dynamic Battery Test duration in minutes 0-255 minutes **("0" = no test)**
**Segment 2** - AC Fail report delay in minutes 0-255 minutes.
**Segment 3** - Power Up Delay in seconds 0-60 seconds ("0" = no power up delay).
**Segment 4** - Siren Time in minutes 1-255 minutes.
**Segment 5** - Telephone Line Cut delay in seconds 0-255 seconds **("0" = no TLM).**
**Segment 6** - Cross Zone time in minutes 0-255 **("0" = no cross zoning).**
**Segment 7** - Chime time in 50 mS (1/20th second) increments from 0-12 seconds ("0" = follows zone 255 latched).
**Segment 8** - Dial delay in seconds 0-255 seconds **(“0 ” = no abort delay).**
**Segment 9** - Fire Alarm Verification time in seconds 120-255 seconds **("0" = no fire alarm verification)** . ***NOTE:***
***This feature is not approved for residential use in California***
**Segment 10** -Listen-In time in seconds 0-255 **("0" = no Listen-In time).**

***Note: The "Listen-In" feature cannot be enabled for UL Listed systems.*** ***The "Dynamic Battery Test" feature***
***cannot exceed four (4) hours.*** ***The dial delay shall be set to -0-.***

**LOCATION 41 - SPECIAL FEATURES**
**(1 segment, feature selection data)**

**Segment 1:**
1 -
On enables the 6-digit code option. If 6-digit option is enabled, all arm/disarm codes and the "Go To
Program Code" are 6 digits. If this option is enabled, the default user 1 code is [ **1** ]-[ **2** ]-[ **3** ]-[ **4** ]-[ **5** ]-[ **6** ].
**NOTE:** **IF** **YOU** **ENABLE** **THIS** **OPTION,** **VERIFY** **THAT** **THE** **"GO** **TO** **PROGRAM** **CODE"** **IS** **A** **SIX-**
**DIGIT CODE BEFORE EXITING PROGRAMMING.**
2 -
On requires code entry for [ r ]-[ **9** ]-[ **8** ] (perform call back download) and [ r ]-[ **9** ]-[ **9** ] (answer incoming call for
download) functions.
3 -
Enable Auto Cancel / Abort (Refer to feature definitions beginning on page 3)
4 -
Enable Walk-Test Mode (Refer to feature definitions beginning on page 3)
5-8
Reserved.
L
**LOCATION 42 - GO TO PROGRAM CODE (6 segments, numerical data)**
Location 42 contains the "Go To Program Code". This location contains either a 4 or 6-digit code. If the 6-digit code
option is enabled in Location 41, THIS CODE MUST CONTAIN SIX (6) DIGITS. If this option is not enabled in
location 41, the last 2 segments (digits) will be ignored. With the NX-8 disarmed, the "Go To Program Code" can be
used to enter the Program Mode.

**LOCATION 43 - GO TO PROGRAM CODE PARTITION AND AUTHORIZATION** **(2 segments, feature selection)**
The "Go To Program Code" can be used as a standard arm/disarm code. When using the code to arm or disarm, the
user ID is 255. (This code may not be changed in the Run Mode.)

**Segment 1:**
1 - Reserved.
2 - On enables "Go To Program Code" as an arm only code.
3 - On enables "Go To Program Code" as an arm only after closing.
4 - On enables "Go To Program Code" as a master arm/disarm code (can change user codes)
5 - On enables "Go To Program Code" as an arm/disarm code.
6 - On enables "Go To Program Code" to bypass zones.
7 - On enables "Go To Program Code" opening and closing reports.
8 - Reserved.

**Segment 2:**
1 - On enables the "Go To Program Code" for Partition #1.
2 - On enables the "Go To Program Code" for Partition #2.
3 - On enables the "Go To Program Code" for Partition #3.
4 - On enables the "Go To Program Code" for Partition #4.
5 - On enables the "Go To Program Code" for Partition #5.
6 - On enables the "Go To Program Code" for Partition #6.
7 - On enables the "Go To Program Code" for Partition #7.
8 - On enables the "Go To Program Code" for Partition #8.

L
**LOCATION 44 -** **DURESS CODE (6 segments,** **numerical data)**

Page 22

---

## Page 23

Location 44 contains the "Duress" code. This Location contains either 4 or 6 digits. If the 6-digit code option is
enabled in Location 41, THIS CODE MUST CONTAIN SIX (6) DIGITS. If the 6-digit option is not enabled in location
41, the last 2 digits will be ignored. **If the duress code is programmed, it will work for all partitions.**

**LOCATION 45 - AUXILIARY OUTPUT 1-4 PARTITION SELECTION**
**(4 segments, feature selection data)**
Location 45 is used to select which partition(s) the events must occur in before the output will activate. Location 45
has 4 segments. Segment 1 corresponds to output 1, and Segment 4 corresponds to output 4.

**Segment 1**
**Segment 2**
**Segment 3**
**Segment 4**
**(Auxiliary 1)**
**(Auxiliary 2)**
**(Auxiliary 3)**
**(Auxiliary 4)**
1= Partition #1
1= Partition #1
1= Partition #1
1= Partition #1
2= Partition #2
2= Partition #2
2= Partition #2
2= Partition #2
3= Partition #3
3= Partition #3
3= Partition #3
3= Partition #3
4= Partition #4
4= Partition #4
4= Partition #4
4= Partition #4
5= Partition #5
5= Partition #5
5= Partition #5
5= Partition #5
6= Partition #6
6= Partition #6
6= Partition #6
6= Partition #6
7= Partition #7
7= Partition #7
7= Partition #7
7= Partition #7
8= Partition #8
8= Partition #8
8= Partition #8
8= Partition #8

**LOCATION 46 - AUXILIARY OUTPUT 1-4** **SPECIAL TIMING**
**(4 segments, feature selection data)**
Location 46 contains special timing feature activation for the four auxiliary outputs. Segment 1 corresponds to output
1, Segment 4 corresponds to output 4.

**Segments 1 - 4:**
1 = On if output should be timed in minutes; Off if timed in seconds.
2 = On if output should latch; Off if output should be timed.
3 = On if output should stop timing upon code entry; Off if the output should continue to time
upon code entry.
4 = On if output should only activate between the closing and opening time in loc. 52 and 53.
5 = On if output should only activate between the opening and closing time in loc. 52 and 53.
6 = On if output should be inverted (0 volts going to 12 volts when activated).
7 = Reserved.
8 = Reserved.

**LOCATION 47 - AUXILIARY OUTPUT #1, EVENT AND TIME**
**(2 segments, numerical data)**

**Segment 1:**
Use the chart on page 24 to select the event that will activate Auxiliary Output 1.
**Segment 2:**
Program the timing from 0-255 (minutes or seconds, depending on data programmed in Segment 1,
Location 46). Programming a "0" makes the output follow the event.

**LOCATION 48 - AUXILIARY OUTPUT #2, EVENT AND TIME (2 segments, numerical data)**

**Segment 1:**
Use the chart on page 24 to select the event that will activate Auxiliary Output 2.
**Segment 2:**
Program the timing from 0-255 (minutes or seconds, depending on data programmed in Segment 2,
Location 46). Programming a "0" makes the output follow the event.

**LOCATION 49- AUXILIARY OUTPUT #3, EVENT AND TIME** **(2 segments, numerical data)**

**Segment 1:**
Use the chart on page 24 to select the event that will activate Auxiliary Output 3.
**Segment 2:**
Program the timing from 0-255 (minutes or seconds, depending on data programmed in Segment 3,
Location 46). Programming a "0" makes the output follow the event.

**LOCATION 50- AUXILIARY OUTPUT #4, EVENT AND TIME** **(2 segments, numerical data)**

**Segment 1:**
Use the chart on page 24 to select the event that will activate Auxiliary Output 4. .
**Segment 2:**
Program the timing from 0-255 (minutes or seconds, depending on data programmed in Segment 4,
Location 46). Programming a "0" makes the output follow the event.

Page 23

---

## Page 24

**AUXILIARY OUTPUT EVENT SELECTION**


|  | DATA |  |  | EVENT |  |  | DATA |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |  |  |  | EVENT |  |
| 0 / |  |  | Burglary Alarm |  |  | 26 |  |  | Fire Trouble |  |  |
| 1 / |  |  | Fire Alarm |  |  | 27 |  |  | Chime |  |  |
| 2 / |  |  | 24 Hour Alarm |  |  | 28 / |  |  | Expander Trouble |  |  |
| 3 / |  |  | Trouble Alarm |  |  | 29 |  |  | Dynamic Battery Test Time |  |  |
| 4 / |  |  | Tamper Alarm |  |  | 30 |  |  | Open Period |  |  |
| 5 |  |  | Yelping Siren (Burglary) |  |  | 31 |  |  | Closed Period |  |  |
| 6 |  |  | Temporal Siren (Fire) |  |  | 32 |  |  | Listen-In |  |  |
| 7 |  |  | Any Siren |  |  | 33 |  |  | Line Seizure |  |  |
| 8 |  |  | Any Bypass |  |  | 34 |  |  | Ground Start |  |  |
| 9 |  |  | AC Fail |  |  | 35 |  |  | Fail To Communicate |  |  |
| 10 |  |  | Low Battery |  |  | 36 |  |  | Telephone Line Fault |  |  |
| 11 / |  |  | Duress |  |  | 37 |  |  | Program Mode |  |  |
| 12 / |  |  | Aux 1 Keypad Zone |  |  | 38 |  |  | Download In Process |  |  |
| 13 / |  |  | Aux 2 Keypad Zone |  |  | 39 |  |  | Ground Fault |  |  |
| 14 / |  |  | Panic Keypad Zone |  |  | 40 |  |  | Short Circuit (Over-current) |  |  |
| 15 |  |  | Keypad Tamper |  |  | 41 |  |  | Box Tamper |  |  |
| 16 / |  |  | Autotest |  |  | 42 |  |  | Siren Tamper |  |  |
| 17 |  |  | Alarm Memory |  |  | 43 |  |  | Any Open |  |  |
| 18 |  |  | Entry |  |  | 44 |  |  | Any Short |  |  |
| 19 |  |  | Exit |  |  | 45 |  |  | Any Fault (Open/ Short on Non-Fire Zone) |  |  |
| 20 |  |  | Entry or Exit |  |  | 46 / |  |  | Any Alarm |  |  |
| 21 |  |  | Armed State |  |  | 47 |  |  | Beeping Keypad |  |  |
| 22 |  |  | Disarmed State |  |  | 48 / |  |  | Code Entry (See note below) |  |  |
| 23 |  |  | Ready |  |  | 49 ˜ / |  |  | Key FOB Function 1 |  |  |
| 24 |  |  | Not Ready |  |  | 50 ˜ / |  |  | Key FOB Function 2 |  |  |
| 25 |  |  | Fire |  |  |  |  |  |  |  |  |


˜ **Events 49 & 50 require NX-408, NX-416, or NX-448 wireless receivers to operate.**
/ **If set to follow** **condition, these events will be 1 second.**

**Notes :** When Event 48 is programmed, it is possible to program a user code's authorization to select which output(s)
a particular code will activate. When LED 8 is on for an authorization, then LEDs 1- 4 correspond to that code
activating outputs 1 - 4 respectively. **(See programming the LED keypads on page 8.)**

Page 24

---

## Page 25

L
**LOCATION 51 - AUTOTEST CONTROL** **(4** **segments, numerical data)**

**Segment 1:**
Program a "1" if the interval is to be in hours; Program a "0" if in days. Add a A 2" to suppress the daily
test or a A 3" to suppress the hourly test if any report has been sent.
**Segment 2:**
Program the Autotest interval from 1-255 hours/days.
**Segment 3:**
Program the Autotest report hour in 24 hour format (if the interval is in hours, this segment is ignored).
**Segment 4:**
Program the Autotest report time, number of minutes after the hour.

**LOCATION 52** **- OPENING TIME** **(2 segments,** **numerical data)**
Location 52 contains the time in 24 hour format the NX-8 enables codes designated as arm only after closing. This
time is only valid on those days programmed in location 54. **Note:** Opening time must be earlier than closing time for
Auto Arm, Aux. Outputs, or Code Authorization to function properly.

**Segment 1:**
Program the hour of the opening time **.**
**Segment 2:**
Program the minutes after the hour of the opening time.

**LOCATION 53 - CLOSING TIME/AUTOMATIC ARMING TIME** **(2 segments, numerical data** )
Location 53 contains the time in 24 hour format the NX-8 disables the disarm capability for codes designated as arm
only after closing. This is also the time the Automatic Arming sequence will begin (if enabled in location 55). **Note:**
Opening time must be earlier than closing time for Auto Arm, Aux. Outputs, or Code Authorization to function properly.

**Segment 1:**
Program the hour of the closing / auto arm time **.**
**Segment 2:**
Program the minutes after the hour of the closing / auto arm time.

**LOCATION 54 - DAYS OF THE WEEK EACH PARTITION IS OPEN** **(8 Segments, feature selection data)**
Location 54 selects which days of the week each partition is open. On these days, A arm only after close window @
codes will be able to arm and disarm during open window. **NOTE: If any partition is not programmed to be opened**
**and is programmed to Auto-Arm (Location 55), the NX-8 will try to arm every 45 minutes for the duration of the**
**closed** **period.** On days not selected here, A arm only after close window @ codes will not disarm. Segment 1 is for
partition 1, and segment 8 is for partition 8 **.** **(See locations 52 and 53 for the opening and closing times for the**
**open days.)**

**Segment 1-8:**
1 - Open on Sunday.
2 - Open on Monday.
3 - Open on Tuesday.
4 - Open on Wednesday.
5 - Open on Thursday.
6 - Open on Friday.
7 - Open on Saturday.
8 - Reserved.

**LOCATION** **55** **-** **DAYS OF** **THE WEEK** **FOR** **AUTO** **ARMING** **IN** **PARTITIONS 1** **THRU** **8** **(8** **Segments,** **feature**
**selection data)**
Location 55 selects which days each partition will auto arm. Segment 1 is for partition 1, and segment 8 is for partition
8. If a zone is faulted when the panel tries to auto arm, the zone will be bypassed.

**Segments 1-8:** 1 - Auto Arming on Sunday.
2 - Auto Arming on Monday.
3 - Auto Arming on Tuesday.
4 - Auto Arming on Wednesday.
5 - Auto Arming on Thursday.
6 - Auto Arming on Friday.
7 - Auto Arming on Saturday.
8 - Reserved.

Page 25

---

## Page 26

**LOCATIONS 56- 83 ARE ONLY USED WHEN REPORTING EVENTS TO A PAGER OR USING A SLOW FORMAT**
**SUCH AS 4+2.** **WHEN USING CONTACT ID OR SIA, THERE IS NO NEED TO PROGRAM THESE LOCATIONS.**

**LOCATION 56-** **RESTORE COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY (8 segments, numerical**
**data)**
Location 56 contains the event code for any zone "Restore" for a 4+2 format. The digit programmed in this location will
be sent as the tens digit in place of the alarm event code. **The zone ID will always be reported as the ones digit of**
**the zone number (i.e. 9 for zone 29).** This location contains 8 segments. Any segment left as "0" will follow the
Segment 1 selection.

**Segment 1:** - Partition #1, "Restore Code".
**Segment 2:** - Partition #2, "Restore Code".
**Segment 3:** - Partition #3, "Restore Code".
**Segment 4:** - Partition #4, "Restore Code".
**Segment 5:** - Partition #5, "Restore Code".
**Segment 6:** - Partition #6, "Restore Code".
**Segment 7:** - Partition #7, "Restore Code".
**Segment 8:** - Partition #8, "Restore Code".

**LOCATION 57 - BYPASS COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY (8 segments, numerical**
**data)**
Location 57 contains the event code for a zone "Bypass" for a 4+2 format. The digit programmed in this location will be
sent as the tens digit. **The zone ID will always be reported as the ones digit of the zone number (i.e. 9 for zone**
**29).** This location contains 8 segments. Any segment left as "0" will follow the Segment 1 selection.

**Segment 1** - Partition #1, "Bypass Code".
**Segment 2** - Partition #2, "Bypass Code".
**Segment 3** - Partition #3, "Bypass Code".
**Segment 4** - Partition #4, "Bypass Code".
**Segment 5** - Partition #5, "Bypass Code".
**Segment 6** - Partition #6, "Bypass Code".
**Segment 7** - Partition #7, "Bypass Code".
**Segment 8** - Partition #8, "Bypass Code".

**LOCATION 58 - TAMPER COMMUNICATOR CODE, SLOW SPEED FORMATS (8 segments, numerical data)**
Location 58 contains the event code for a zone "Tamper" for a 4+2 format. The digit programmed in this location will
be sent as the tens digit. **The** **zone** **ID** **will** **always** **be** **reported** **as** **the** **zone** **number** **(i.e.** **9** **for** **zone** **29).** Any
segment left as "0" will follow the Segment 1 selection.

**Segment 1** - Partition #1, "Tamper Code".
**Segment 2** - Partition #2, "Tamper Code".
**Segment 3** - Partition #3, "Tamper Code".
**Segment 4** - Partition #4, "Tamper Code".
**Segment 5** - Partition #5, "Tamper Code".
**Segment 6** - Partition #6, "Tamper Code".
**Segment 7** - Partition #7, "Tamper Code".
**Segment 8** - Partition #8, "Tamper Code".

Page 26

---

## Page 27

**LOCATION 59 - TROUBLE COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY** **(8 segments, numerical**
**data )**
Location 59 contains the event code for a zone "Trouble" for a 4+2 format. The digit programmed in this location will
be sent as the tens digit. **The** **zone** **ID** **will** **always** **be** **reported** **as** **the** **zone** **number** **(i.e.** **9** **for** **zone** **29).** Any
segment left as "0" will follow the event code for partition 1.

**Segment 1** - Partition #1, "Trouble Code".
**Segment 2** - Partition #2, "Trouble Code".
**Segment 3** - Partition #3, "Trouble Code".
**Segment 4** - Partition #4, "Trouble Code".
**Segment 5** - Partition #5, "Trouble Code".
**Segment 6** - Partition #6, "Trouble Code".
**Segment 7** - Partition #7, "Trouble Code".
**Segment 8** - Partition #8, "Trouble Code".

**LOCATION 60 - SENSOR LOW BATTERY COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY**
**(8 segments,** **numerical data)**
Location 60 contains the event code for a zone "Sensor Low Battery" for a 4+2 format. The digit programmed in this
location will be sent as the tens digit.. **The zone ID will always be reported as the zone number (i.e. 9 for zone 29).**
Any segment left as "0" will follow the Segment 1 selection.

**Segment 1** - Partition #1, "Sensor Low Battery Code".
**Segment 2** - Partition #2, "Sensor Low Battery Code".
**Segment 3** - Partition #3, "Sensor Low Battery Code".
**Segment 4** - Partition #4, "Sensor Low Battery Code".
**Segment 5** - Partition #5, "Sensor Low Battery Code".
**Segment 6** - Partition #6, "Sensor Low Battery Code".
**Segment 7** - Partition #7, "Sensor Low Battery Code".
**Segment 8** - Partition #8, "Sensor Low Battery Code".

**LOCATION** **61-** **SENSOR** **MISSING** **COMMUNICATOR** **CODE,** **SLOW** **SPEED** **FORMATS** **ONLY** **(8** **segments,**
**numerical data** )
Location 61 contains the event code for a zone "Sensor Missing" for a 4+2 format. The digit programmed in this
location will be sent as the tens digit.. **The zone ID will always be reported as the zone number (i.e. 9 for zone 29).**
Any segment left as "0" will follow the Segment 1 selection.

**Segment 1** - Partition #1, "Sensor Missing Code".
**Segment 2** - Partition #2, "Sensor Missing Code".
**Segment 3** - Partition #3, "Sensor Missing Code".
**Segment 4** - Partition #4, "Sensor Missing Code".
**Segment 5** - Partition #5, "Sensor Missing Code".
**Segment 6** - Partition #6, "Sensor Missing Code".
**Segment 7** - Partition #7, "Sensor Missing Code".
**Segment 8** - Partition #8, "Sensor Missing Code".

**LOCATION 62 - DURESS COMMUNICATOR CODE,** **SLOW SPEED FORMATS ONLY (2 segments, numerical**
**data)**
Location 62 contains the tens and ones digits that will be sent for a 4+2 format if the Duress code is enabled in
location 44. Segment 1 contains the tens digit, segment 2 contains the ones digit.

**LOCATION 63 - KEYPAD AUXILIARY 1 COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY** **(2 segments,**
**numerical data )**
Location 63 contains the tens and ones digits that will be sent for a 4+2 format if the keypad "Auxiliary 1" (FIRE) is
enabled in the partition feature selection . Segment 1 contains the tens digit, segment 2 contains the ones digit.

**LOCATION 64 - KEYPAD AUXILIARY 2 COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY** **(2 segments,**
**numerical data)**
Location 64 contains the tens and ones digits that will be sent for a 4+2 format if the keypad "Auxiliary 2" (MEDICAL)
is enabled in the partition feature selection. Segment 1 contains the tens digit, segment 2 contains the ones digit.

Page 27

---

## Page 28

**LOCATION** **65** **-** **KEYPAD** **PANIC** **COMMUNICATOR** **CODE,** **SLOW** **SPEED** **FORMATS** **ONLY** **(2** **segments,**
**numerical data)**
Location 65 contains the tens and ones digits that will be sent for a 4+2 format if the keypad "Panic" is enabled in the
partition feature selection Segment 1 contains the tens digit segment 2 contains the ones digit.

**LOCATION** **66** **-** **KEYPAD** **MULTIPLE** **CODE** **ENTRY** **TAMPER** **COMMUNICATOR** **CODE,** **SLOW** **SPEED**
**FORMATS ONLY** **(2 segments, numerical data)**
Location 66 contains the tens and ones digits that will be sent for a 4+2 format if the keypad "Multiple Code Entry"
(Tamper) is enabled in the partition feature selection. Segment 1 contains the tens digit, segment 2 contains the ones
digit.

**LOCATION 67 - BOX TAMPER / BOX TAMPER RESTORE COMMUNICATOR CODE, SLOW SPEED FORMATS**
**ONLY** **(4 segments, numerical data)**
Location 67 contains the tens and ones digits that will be sent for a 4+2 format if the "Box Tamper" feature is enabled
in location 37. Segment 1 contains the tens digit of the "Box Tamper". Segment 2 contains the ones digit of the "Box
Tamper". Segment 3 contains the tens digit of the "Box Tamper Restore". Segment 4 contains the ones digit of the
"Box Tamper Restore".

**LOCATION 68 - AC FAIL / AC FAIL RESTORE COMMUNICATOR CODES, SLOW SPEED FORMATS ONLY**
**(4 segments, numerical data)**
Location 68 contains the tens and ones digits for a 4+2 format that will be sent if "AC Fail Reporting" is enabled.
Segment 1 contains the tens digit of the "AC Fail Reporting". Segment 2 contains the ones digit of the "AC Fail
Reporting". Segment 3 contains the tens digit of the "AC Fail Restore". Segment 4 contains the ones digit of the "AC
Fail Restore".

**LOCATION** **69**
**-** **LOW** **BATTERY** **/** **LOW** **BATTERY** **RESTORE** **COMMUNICATOR** **CODES** **,** **SLOW** **SPEED**
**FORMATS ONLY** **(4 segments, numerical data)**
Location 69 contains the tens and ones digits for a 4+2 format that will be sent if "Low Battery Reporting" is enabled..
Segment 1 contains the tens digit of the "Low Battery Reporting". Segment 2 contains the ones digit of the "Low
Battery Reporting". Segment 3 contains the tens digit of the "Low Battery Restore". Segment 4 contains the ones
digit of the "Low Battery Restore".

**LOCATION** **70** **-** **AUX** **POWER** **OVERCURRENT/** **AUX** **POWER** **OVERCURRENT** **RESTORE** **COMMUNICATOR**
**CODES,** **SLOW SPEED FORMATS ONLY** **(4 segments, numerical data)**
Location 70 contains the tens and ones digits for a 4+2 format that will be sent if "Aux Power Overcurrent Reporting"
is enabled. Segment 1 contains the tens digit of the "Aux Power Overcurrent ReportIng". Segment 2 contains the
ones digit of the "Aux Power Overcurrent Reporting". Segment 3 contains the tens digit of the "Aux Power Overcurrent
Restore". Segment 4 contains the ones digit of the "Aux Power Overcurrent Restore".

**LOCATION** **71** **-** **BELL** **TAMPER** **AND** **BELL** **TAMPER** **RESTORE** **COMMUNICATOR** **CODES,** **SLOW** **SPEED**
**FORMATS ONLY** ( **4 segments, numerical data** )
Location 71 contains the tens and ones digits for a 4+2 format that will be sent if siren supervision reporting is
enabled. Segment 1 contains the tens digit of the "Bell Tamper Reporting". Segment 2 contains the ones digit of the
"Bell Tamper Reporting". Segment 3 contains the tens digit of the "Bell Tamper Restore". Segment 4 contains the
ones digit of the "Bell Tamper Restore".

**LOCATION** **72** **-** **TELEPHONE** **LINE** **CUT** **AND** **TELEPHONE** **LINE** **CUT** **RESTORE** **COMMUNICATOR** **CODES,**
**SLOW SPEED FORMATS ONLY**
**(4 segments, numerical data** )
Location 72 contains the tens and ones digits for a 4+2 format that will be sent if "Telephone Line Cut Reporting" is
enabled. Segment 1 contains the tens digit of the "Telephone Line Cut Reporting". Segment 2 contains the ones digit
of the "Telephone Line Cut Reporting". Segment 3 contains the tens digit of the "Telephone Line Cut Restore".
Segment 4 contains the ones digit of the "Telephone Line Cut Restore".

**LOCATION 73** **- GROUND FAULT AND GROUND FAULT RESTORE COMMUNICATOR CODES, SLOW SPEED**
**FORMATS ONLY**
**(4 segments, numerical data** )
Location 73 contains the tens and ones digits for a 4+2 format that will be sent if "Ground Fault Reporting" is enabled,
and the NX-870 is installed. Segment 1 contains the tens digit of the "Ground Fault Reporting". Segment 2 contains
the ones digit of the "Ground Fault Reporting". Segment 3 contains the tens digit of the "Ground Fault Restore".
Segment 4 contains the ones digit of the "Ground Fault Restore".

Page 28

---

## Page 29

**LOCATION** **74** **-** **EXPANDER** **TROUBLE** **AND** **EXPANDER** **TROUBLE** **RESTORE** **COMMUNICATOR** **CODES,**
**SLOW SPEED FORMATS ONLY**
**(4 segments, numerical data** )
Location 74 contains the tens and ones digits for a 4+2 format that will be sent if "Expander Trouble Reporting" is
enabled. Segment 1 contains the tens digit of the "Expander Trouble Reporting". Segment 2 contains the ones digit
of the "Expander Trouble Reporting". Segment 3 contains the tens digit of the "Expander Trouble Restore". Segment
4 contains the ones digit of the "Expander Trouble Restore".

**LOCATION 75 - FAIL TO COMMUNICATE COMMUNICATOR CODE,** **SLOW SPEED FORMATS ONLY**
**(2 segments, numerical data** )
Location 75 contains the tens and ones digits for a 4+2 format that will be sent if the "Fail To Communicate Reporting"
is enabled. Segment 1 contains the tens digit, segment 2 contains the ones digit.

**LOCATION 76 -** **LOG FULL COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY (2 segments, numerical**
**data)**
Location 76 contains the tens and ones digits for a 4+2 format if the "Log Full Reporting" is enabled. Segment 1
contains the tens digit, segment 2 contains the ones digit.

**LOCATION 77 - OPENING COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY (8 segments, numerical**
**data)**
Location 77 contains the tens digit of a 4+2 format if the "Opening Reporting" is enabled. **The ones digit is the ones**
**digit of the user number that did the opening. If the user is greater than 9, the numbers will begin repeating** . If
it is required to report openings and closings for more than 9 users, Contact ID or SIA format must be used. Any
segment left as "0" will follow the Segment 1 selection.

**Segment 1** - Opening Code for Partition #1.
**Segment 2** - Opening Code for Partition #2.
**Segment 3** - Opening Code for Partition #3.
**Segment 4** - Opening Code for Partition #4.
**Segment 5** - Opening Code for Partition #5.
**Segment 6** - Opening Code for Partition #6.
**Segment 7** - Opening Code for Partition #7.
**Segment 8** - Opening Code for Partition #8.

**LOCATION 78 - CLOSING COMMUNICATOR CODE,** **SLOW SPEED FORMATS ONLY (8 segments, numerical**
**data)**
Location 78 contains the tens digit of a 4+2 format if the "Closing Reporting" is enabled. **The ones digit is the ones**
**digit of the user number that did the closing.** **If the user is greater than 9, the numbers will begin repeating** . If
it is required to report openings and closings for more than 9 users, Contact ID or SIA format must be used. Any
segment left as "0" will follow the Segment 1 selection.

**Segment 1** - Closing Code for Partition #1.
**Segment 2** - Closing Code for Partition #2.
**Segment 3** - Closing Code for Partition #3.
**Segment 4** - Closing Code for Partition #4.
**Segment 5** - Closing Code for Partition #5.
**Segment 6** - Closing Code for Partition #6.
**Segment 7** - Closing Code for Partition #7.
**Segment 8** - Closing Code for Partition #8.

**LOCATION 79 - AUTOTEST COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY** **(2 segments, numerical**
**data)**
Location 79 contains the tens and ones digits for a 4+2 format that will be sent if the "Autotest" or "Manual Test" is
enabled. Segment 1 contains the tens digit segment 2 contains the ones digit.

**LOCATION** **80** **-** **RECENT** **CLOSING** **AND** **EXIT** **ERROR** **COMMUNICATOR** **CODE,** **SLOW** **SPEED** **FORMATS**
**ONLY** **(2 segments, numerical data)**
Location 80 contains the tens digit for a 4+2 format that will be sent if "Recent Closing" and/or "Exit Error Reporting" is
enabled. Segment 1 contains the tens digit for the "Recent Closing Reporting". Segment 2 contains the digit for the
"Exit Error Reporting". **The ones digit is the ones digit of the user who closed.** **If the user number is greater**
**than 9, the numbers will begin repeating (i.e. 9 for user 29).** If it is required to report Recent Closings and Exit
Errors for more than 9 users, Contact ID or SIA format must be used.

Page 29

---

## Page 30

**LOCATION 81 - START PROGRAM** **AND END PROGRAM COMMUNICATOR CODES,** **SLOW SPEED FORMATS**
**ONLY** **(4 segments, numerical data)**
Location 81 contains the tens and ones digits for a 4+2 format that will be sent if "Start / End Programming Reporting"
is enabled. Segment 1 contains the tens digit of the "Start Program Reporting". Segment 2 contains the ones digit of
the "Start Program Reporting". Segment 3 contains the tens digit of the "End Program Reporting". Segment 4
contains the ones digit of the "End Program Reporting".

**LOCATION** **82** **-** **END** **DOWNLOAD** **COMMUNICATOR** **CODE,** **SLOW** **SPEED** **FORMATS** **ONLY** **(4** **segments,**
**numerical data)**
Location 82 contains the tens and ones digits for a 4+2 format that will be sent if "End Downloading Reporting" is
enabled. Segment 1 and 2 are reserved. Segment 3 contains the tens digit of the "End Download Reporting".
Segment 4 contains the ones digit of the "End Download Reporting". **Note** : A start download report will be sent to the
internal event log.

**LOCATION 83 - CANCEL COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY (1 segments, numerical**
**data)**
Location 83 contains the tens digit for a 4+2 format that will be sent if "Cancel Reporting" is enabled. Segment 1
contains the tens digit for the "Cancel Communicator Reporting". **The ones digit is the ones digit of the user who**
**canceled.** **If** **the** **user** **number** **is** **greater** **than** **9,** **the** **numbers** **will** **begin** **repeating** **(i.e.** **9** **for** **user** **29).** If it is
required to report Cancels for more than 9 users, Contact ID or SIA format must be used.

**LOCATIONS** **84-87** **RESERVED.**

*******
**LOCATIONS 88-109 ARE FOR PROGRAMMING DIFFERENT ACCOUNT CODES AND/OR**
*******
*******
**FEATURES FOR EACH PARTITION. IF A LOCATION IS LEFT UNPROGRAMMED, THE**
*******
******
**FEATURE FOR PARTITION 1 AND ACCOUNT CODE FOR THE PHONE NUMBER WILL BE USED**
******

**LOCATION 88 - ACCOUNT CODE FOR PARTITION 1** **(6 segments, numerical data)**
Location 88 contains the account code sent when partition 1 is reported. **If location 88 is left unprogrammed (all**
A **10"s), then the account code corresponding to the Phone number dialed will be used.** If the account code is
less than six digits, program a A 10" in the segment immediately after the last digit of the account code. If the account
code is 6 digits long, program all 6 segments.

**LOCATION 89 - ACCOUNT CODE FOR PARTITION 2**
**(6 segments, numerical data)**
Location 89 contains the account code sent when partition 2 is reported. **If location 89 is left unprogrammed (all**
A **10"s), then the account code corresponding to the Phone number dialed will be used.** If the account code is
less than six digits, program a A 10" in the segment immediately after the last digit of the account code. If the account
code is 6 digits long program all 6 segments.

**LOCATION 90 - PARTITION 2 FEATURE AND REPORTING SELECTIONS** **(3 segments,** **feature selection data)**
Location 90 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system.
In addition, certain communicator reports are enabled in this location. Each of these features can be
enabled by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location
23, Segments 1,2, and 3 (page 17) for the feature selections. **If** **all** **segments** **are** **blank** **(nothing** **enabled),** **the**
**features for partition 1 will be used.**

**LOCATION 91 - PARTITION 2 ENTRY EXIT TIMERS** **(4** **segments, numerical data)**
Location 91 is used to enter in seconds the Entry and Exit times. There are 2 separate entry and exit times.
Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry time 1:**
Entry time that will be used when a Delay 1 zone type initiates an entry delay.
**Segment 2, Exit time 1** :
Exit time that will be used for all zones designated as Delay 1.
**Segment 3, Entry time 2:**
Entry time that will be used when a Delay 2 zone type initiates an entry delay.
**Segment 4, Exit time** **2:**
Exit time that will be used for all zones designated as Delay 2.

**LOCATION 92 - ACCOUNT CODE FOR PARTITION 3** **(6 segments, numerical data)**
The account code sent when partition 3 is reported is programmed in location 92.
**If** **location** **92** **is** **left**
**unprogrammed (all** A **10" ) then the account code corresponding to the Phone number dialed will be used.** If
the account code is less than six digits, program a A 10" in the segment immediately after the last digit of the account
code. If the account code is 6 digits long program all 6 segments.

Page 30

---

## Page 31

**LOCATION 93 - PARTITION 3 FEATURE AND REPORTING SELECTIONS** **(3 segments, feature selection data)**
Location 93 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system. In addition, certain communicator reports are enabled in this location. Each of these features can be enabled
by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location 23,
Segments 1, 2, and 3 (page 17) for the feature selections. **If all segments are blank (nothing enabled), the features**
**for partition 1 will be used.**

**LOCATION 94 - PARTITION 3 ENTRY EXIT TIMERS**
**(4 segments, numerical data)**
Location 94 is used to enter in seconds the Entry and Exit times. There are 2 separate entry and exit times. Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry time 1:**
Entry time that will be used when a Delay 1 zone type initiates an entry delay.
**Segment 2, Exit time 1:**
Exit time that will be used for all zones designated as Delay 1.
**Segment 3, Entry time 2:**
Entry time that will be used when a Delay 2 zone type initiates an entry delay.
**Segment 4, Exit time** **2:**
Exit time that will be used for all zones designated as Delay 2.

**LOCATION 95 - ACCOUNT CODE FOR PARTITION 4** **(6 segments, numerical data)**
The account code sent when partition 4 is reported is programmed in location 95.
**If** **location** **95** **is** **left**
**unprogrammed (all** A **10" ) then the account code corresponding to the Phone number dialed will be used.** If the
account code is less than six digits, program a A 10" in the segment immediately after the last digit of the account code.
If the account code is 6 digits long, program all 6 segments.

**LOCATION 96 - PARTITION 4 FEATURE AND REPORTING SELECTIONS** **(3 segments, feature selection data)**
Location 96 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system.
In addition, certain communicator reports are enabled in this location. Each of these features can be
enabled by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location
23, Segments 1,2, and 3 (page 17) for the feature selections. **If** **all** **segments** **are** **blank** **(nothing** **enabled),** **the**
**features for partition 1 will be used.**

**LOCATION 97 - PARTITION 4 ENTRY EXIT TIMERS** **(4 segments, numerical data)**
Location 97 is used to enter in seconds the Entry and exit times. There are 2 separate entry and exit times. Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry time 1:**
Entry time that will be used when a Delay 1 zone type initiates an entry delay.
**Segment 2, Exit time 1:**
Exit time that will be used for all zones designated as Delay 1.
**Segment 3, Entry time 2:**
Entry time that will be used when a Delay 2 zone type initiates an entry delay.
**Segment 4, Exit time** **2:**
Exit time that will be used for all zones designated as Delay 2.

**LOCATION 98 - ACCOUNT CODE FOR PARTITION 5** **(6 segments, numerical data)**
The account code sent when partition 5 is reported is programmed in location 98.
**If** **location** **98** **is** **left**
**unprogrammed (all** A **10" ) then the account code corresponding to the Phone number dialed will be used.** If the
account code is less than six digits, program a A 10" in the segment immediately after the last digit of the account code.
If the account code is 6 digits long, program all 6 segments.

**LOCATION 99 - PARTITION 5 FEATURE AND REPORTING SELECTIONS** **(3 SEGMENTS, NUMERICAL DATA)**
Location 99 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system. In addition, certain communicator reports are enabled in this location. Each of these features can be enabled
by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location 23,
Segments 1,2, and 3 (page 17) for the feature selections. **If all segments are blank (nothing enabled), the features**
**for partition 1 will be used.**

**LOCATION 100 - PARTITION 5 ENTRY EXIT TIMERS** **(4 segments, numerical data** )
Location 100 is used to enter in seconds the Entry and exit times. There are 2 separate entry and exit times. Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry Time 1:**
Entry time that will be used when a delay 1 zone type initiates an entry delay.
**Segment 2, Exit Time 1:**
Exit time that will be used for all zones designated as delay 1.
**Segment 3, Entry Time 2:**
Entry time that will be used when a delay 2 zone type initiates an entry delay.
**Segment 4, Exit Time 2:**
Exit time that will be used for all zones designated as delay 2.

Page 31

---

## Page 32

**LOCATION 101 - ACCOUNT CODE FOR PARTITION 6** **(6 segments, numerical data)**
The account code sent when partition 6 is reported is programmed in location 101. **If** **location** **101** **is** **left**
**unprogrammed** **(all** A **10"** **)** **then** **the** **account** **code** **corresponding** **to** **the** **Phone** **number** **dialed** **will** **be** **used.**
Program the account code is less than six digits, program a A 10" in the segment immediately after the last digit of the
account code. If the account code is 6 digits long, program all 6 segments.

**LOCATION 102 - PARTITION 6 FEATURE AND REPORTING SELECTIONS** **(3 segments, feature selection data)**
Location 102 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system.
In addition, certain communicator reports are enabled in this location. Each of these features can be
enabled by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location
23, Segments 1, 2, and 3 (page 17) for the feature selections. **If all segments are blank (nothing enabled), the**
**features for partition 1 will be used.**

**LOCATION 103 - PARTITION 6 ENTRY EXIT TIMERS** **(4 segments, numerical data)**
Location 103 is used to enter in seconds the Entry and Exit times. There are 2 separate entry and exit times. Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry Time 1:**
Entry time that will be used when a Delay 1 zone type initiates an entry delay.
**Segment 2, Exit Time 1:**
Exit time that will be used for all zones designated as Delay 1.
**Segment 3, Entry Time 2:**
Entry time that will be used when a Delay 2 zone type initiates an entry delay.
**Segment 4, Exit Time** **2:**
Exit time that will be used for all zones designated as Delay 2.

**LOCATION 104 - ACCOUNT CODE FOR PARTITION 7** **(6 segments, numerical data)**
The account code sent when partition 7 is reported is programmed in location 104.
**If** **location** **104** **is** **left**
**unprogrammed (all** A **10" ) then the account code corresponding to the Phone number dialed will be used.** If the
account code is less than six digits, program a A 10" in the segment immediately after the last digit of the account code.
If the account code is 6 digits long, program all 6 segments.

**LOCATION 105 - PARTITION 7 FEATURE AND REPORTING SELECTIONS** **(3 segments, feature selection data)**
Location 105 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system.
In addition, certain communicator reports are enabled in this location. Each of these features can be
enabled by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location
23, Segments 1,2, and 3 (page 17) for the feature selections. **If** **all** **segments** **are** **blank** **(nothing** **enabled),** **the**
**features for partition 1 will be used.**

**LOCATION 106 - PARTITION 7** **ENTRY EXIT TIMERS (4 segments,** **numerical data)**
Location 106 is used to enter in seconds the Entry and Exit times. There are 2 separate entry and exit times. Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry Time 1:**
Entry time that will be used when a Delay 1 zone type initiates an entry delay.
**Segment 2, Exit Time 1:**
Exit time that will be used for all zones designated as Delay 1.
**Segment 3, Entry Time 2:**
Entry time that will be used when a Delay 2 zone type initiates an entry delay.
**Segment 4, Exit Time** **2:**
Exit time that will be used for all zones designated as Delay 2.

**LOCATION 107 -** **ACCOUNT CODE FOR PARTITION 8** **(6 segments, numerical** **data)**
The account code sent when partition 8 is reported is programmed in location 107.
**If** **location** **107** **is** **left**
**unprogrammed (all** A **10" ) then the account code corresponding to the Phone number dialed will be used.** If the
account code is less than six digits, program a A 10" in the segment immediately after the last digit of the account code.
If the account code is 6 digits long, program all 6 segments.

**LOCATION 108 - PARTITION 8 FEATURE AND REPORTING SELECTIONS** **(3 segments, feature selection data)**
Location 108 is used to enable certain features that can be accessed or are visible to the user from the keypad of the
system.
In addition, certain communicator reports are enabled in this location. Each of these features can be
enabled by partition. This location contains 3 segments, with eight possible features per segment. Refer to Location
23, Segments 1,2, and 3 (page 17) for the feature selections. **If** **all** **segments** **are** **blank** **(nothing** **enabled),** **the**
**features for partition 1 will be used.**

Page 32

---

## Page 33

**LOCATION 109 - PARTITION 8** **ENTRY EXIT TIMERS** **(4 segments,** **numerical data)**
Location 109 is used to enter in seconds the Entry and Exit times. There are 2 separate entry and exit times. Valid
entries are 10-255 seconds. **If all segments are** A **0", the entry and exit times for partition 1 will be used.**

**Segment 1, Entry Time 1:**
Entry time that will be used when a Delay 1 zone type initiates an entry delay.
**Segment 2, Exit Time 1:**
Exit time that will be used for all zones designated as Delay 1.
**Segment 3, Entry Time 2:**
Entry time that will be used when a Delay 2 zone type initiates an entry Delay.
**Segment 4, Exit Time** **2:**
Exit time that will be used for all zones designated as Delay 2.

**LOCATIONS 110-149 ARE USED TO CHANGE THE ZONE TYPES (Configurations) AS LISTED IN THE TABLE**
**ON** **PAGE** **18.** **THESE** **LOCATIONS** **ARE** **CONSIDERED** **ADVANCED** **PROGRAMMING** **AND** **SHOULD**
**ONLY BE CHANGED WITH A THOROUGH UNDERSTANDING OF THE OPERATION OF EACH BIT.**

**LOCATION 110 - ZONE TYPE 1 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 110 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2 the digit in location 110 should be from 1-
15.The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 111 - ZONE TYPE 1 CHARACTERISTIC SELECT (3 segments, feature selection data)**

**Segment 1:**
1 = Fire (turn on if this is a fire zone).
2 = 24 hour (turn on for non-fire 24 hour zones).
3 = Keyswitch zone. (normally open switch)
4 = Follower (turn on for burglary zones that are Instant during non-entry times).
5 = Delay 1 zone (follows timer 1 entry and exit times).
6 = Delay 2 zone (follows timer 2 entry and exit times).
7 = Interior (turn on if this zone should Automatically Bypass or Bypass for Stay Arming).
8 = Local only (turn on if this zone should not be reported).

**Segment 2:**
1 = On if Zone Type will beep the keypad for alarm.
2 = On if Zone Type will sound the yelping siren for alarm.
3 = On if Zone Type will sound the temporal siren for alarm.
4 = On if Zone Type will chime.
5 = On if Zone Type can be bypassed.
6 = On if Zone Type is included in the group shunt.
7 = On if Zone Type is force armable.
8 = On if Zone Type is entry guard.

**Segment 3:**
1 = On enables Fast Loop Response. (50mS)- Off= 500mS
2 = On enables Double End Of Line Tamper zone. (Mainly used for tamper on wireless zones)
3 = On enables Trouble Reporting zone. (Day zone and Fire zones)
4 = On if Zone Type is a Cross Zone.
5 = On enables Dialer Delay zone. (See location 40, page 22)
6 = On if Zone Type will swinger shutdown. (See location 38, page 21)
7 = On enables Restore reporting.
8 = On enables Listen-In. (See location 40, page 22)

**LOCATION 112 - ZONE TYPE 2 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 112 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2 the digit in location 112 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 113 - ZONE TYPE 2 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 114 - ZONE TYPE 3 ALARM EVENT CODE (1 segment, numerical data)**
Location 114 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 114 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

Page 33

---

## Page 34

**LOCATION 115 - ZONE TYPE 3 CHARACTERISTIC SELECT** **(3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 116 - ZONE TYPE 4 ALARM EVENT CODE**
**(1 segment, numerical data)**
Location 116 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2 the digit in location 116 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 117 - ZONE TYPE 4 CHARACTERISTIC SELECT** **(3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 118 - ZONE TYPE 5 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 118 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 118 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 119 - ZONE TYPE 5 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 120 - ZONE TYPE 6 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 120 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2 the digit in location 120 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 121 - ZONE TYPE 6 CHARACTERISTIC SELECT**
**(3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 122** **- ZONE TYPE 7 ALARM EVENT CODE**
**(1 segment, numerical data)**
Location 122 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52.The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 122 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 123 - ZONE TYPE 7 CHARACTERISTIC SELECT** **(3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 124 - ZONE TYPE 8 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 124 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 124 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 125 - ZONE TYPE 8 CHARACTERISTIC SELECT** **(3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 126 - ZONE TYPE 9 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 126 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 126 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 127 - ZONE TYPE 9 CHARACTERISTIC SELECT** **(3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 128 - ZONE TYPE 10 ALARM EVENT CODE (1 segment, numerical data)**
Location 128 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 128 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

Page 34

---

## Page 35

**LOCATION 129 - ZONE TYPE 10 CHARACTERISTIC SELECT (3 segments, feature selection data** )
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 130 - ZONE TYPE 11 ALARM EVENT CODE (1 segment, numerical data)**
Location 130 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 130 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 131 - ZONE TYPE 11 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 132 - ZONE TYPE 12 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 132 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52.The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 132 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 133 - ZONE TYPE 12 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 134 - ZONE TYPE 13 ALARM EVENT CODE (1 segment, numerical data)**
Location 134 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 134 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 135 - ZONE TYPE 13 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 136 - ZONE TYPE 14 ALARM EVENT CODE (1 segment, numerical data)**
Location 136 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 136 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 137 - ZONE TYPE 14 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 138 - ZONE TYPE 15 ALARM EVENT CODE (1 segment, numerical data)**
Location 138 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 138 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 139 - ZONE TYPE 15 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page33.

**LOCATION 140 - ZONE TYPE 16 ALARM EVENT CODE (1 segment, numerical data)**
Location 140 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 140 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 141 - ZONE TYPE 16 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

Page 35

---

## Page 36

**LOCATION 142 - ZONE TYPE 17 ALARM EVENT CODE** **(1 segment, numerical data)**
Location 142 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 142 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 143 - ZONE TYPE 17 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 144 - ZONE TYPE 18 ALARM EVENT CODE (1 segment, numerical data)**
Location 144 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 144 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 145 - ZONE TYPE 18 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 146 - ZONE TYPE 19 ALARM EVENT CODE (1 segment, numerical data)**
Location 146 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 146 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 147 - ZONE TYPE 19 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

**LOCATION 148 - ZONE TYPE 20 ALARM EVENT CODE (1 segment, numerical data)**
Location 148 contains the event code sent for a Contact ID or SIA report. The desired event code should be chosen
from the list on page 52. The zone ID will be that zone that is in alarm. If 4+2 format is being used, the number
programmed in this location will be sent as the tens digit. When using 4+2, the digit in location 148 should be from 1-
15. The zone ID for 4+2 formats will be the ones digit of the zone that is in alarm.

**LOCATION 149 - ZONE TYPE 20 CHARACTERISTIC SELECT (3 segments, feature selection data)**
Use "Zone Type Characteristic Selections" described in Location 111, page 33.

Page 36

---

## Page 37

**NX-8 PROGRAMMING WORKSHEETS**
(Factory defaults for segments are in ***bold italics*** text and "Quick Start" locations are identified with the L symbol.)


| LOC | PG | DESCRIPTION |  | DEFAULT |  |  | PROGRAMMING DATA |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L 0 | 11 | PHONE #1 |  | 14-14-14-14-14-14-14-14-14-14- 14-14-14-14-14-14-14-14-14-14 |  |  | ____________________ ____________________ |
| L 1 | 11 | PHONE #1, ACCOUNT CODE |  | 10 - 10 - 10 - 10 - 10 - 10 |  |  | ______ |
| L 2 | 11 | PHONE #1, REPORTING FORMAT |  | 0 |  |  | _ |
| L 3 | 11 | PHONE #1, DIAL ATTEMPTS BACKUP CONTROL |  | 8 0 |  |  | _ _ |
| 4 | 12 | PHONE #1, SELECTING EVENTS TO REPORT TO PHONE #1 |  |  |  |  |  |
|  |  | Segment #1 (Circle Numbers To Program) |  |  | Segment #2 (Circle Numbers To Program) |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Alarms and Restores Open/Close Bypass Zone Trouble Power Trouble (AC Failure or Low Battery) Siren & Telephone Fault Test Reports Program, Download, & Log Full |  | 1 2 3 4 5 6 7 8 | Tampers Short Circuit & Ground Fault Sensor Lost Sensor Low Battery Expander Trouble Failure To Communicate Reserved Reserved |  |
| 5 | 13 | PHONE #1, SELECTING WHICH PARTITIONS REPORT TO PHONE #1 |  |  |  |  |  |
|  |  | Segment #1 (Circle Numbers To Program) |  |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  |  |  |  |



| L 6 | 13 | PHONE #2 |  | 14-14-14-14-14-14-14-14-14-14- 14-14-14-14-14-14-14-14-14-14 |  |  |  | ____________________ ____________________ |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L 7 | 13 | PHONE #2, ACCOUNT CODE |  | 10 - 10 - 10 - 10 - 10 - 10 |  |  |  | ______ |  |
| L 8 | 13 | PHONE #2, REPORTING FORMAT |  | 0 |  |  |  | _ |  |
| 9 | 13 | PHONE #2, DIAL ATTEMPTS BACKUP CONTROL |  | 8 0 |  |  |  | _ _ |  |
| 10 | 14 | PHONE #2, SELECTING EVENTS TO REPORT TO PHONE #2 |  |  |  |  |  |  |  |
|  |  | Segment #1 (Circle Numbers To Program) |  |  |  | Segment #2 (Circle Numbers To Program) |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Alarms and Restores Open/Close Bypass Zone Trouble Power Trouble (AC Failure or Low Battery) Siren & Telephone Fault Test Reports Program, Download, & Log Full |  |  | 1 2 3 4 5 6 7 8 | Tampers Short Circuit & Ground Fault Sensor Lost Sensor Low Battery Expander Trouble Failure To Communicate Reserved Reserved |  |  |


Page 37

---

## Page 38


| LOC | PG | DESCRIPTION | DEFAULT |  |
| --- | --- | --- | --- | --- |
|  |  |  |  | PROGRAMMING DATA |



| 11 | 14 | PHONE #2, SELECTING WHICH PARTITIONS REPORT TO PHONE #2 |  |  |
| --- | --- | --- | --- | --- |
|  |  |  | Segment #1 (Circle Numbers To Program) |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |



| 12 | 14 | PHONE #3 |  | 14-14-14-14-14-14-14-14-14-14- 14-14-14-14-14-14-14-14-14-14 |  |  | ____________________ ____________________ |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | 14 | PHONE #3, ACCOUNT CODE |  | 10 - 10 - 10 - 10 - 10 - 10 |  |  | ______ |
| 14 | 14 | PHONE #3, REPORTING FORMAT |  | 0 |  |  | _ |
| 15 | 15 | PHONE #3, DIAL ATTEMPTS BACKUP CONTROL |  | 8 0 |  |  | _ _ |
| 16 | 15 | PHONE #3, SELECTING EVENTS TO REPORT TO PHONE #3 |  |  |  |  |  |
|  |  | Segment #1 (Circle Numbers To Program) |  |  | Segment #2 (Circle Numbers To Program) |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Alarms and Restores Open/Close Bypass Zone Trouble Power Trouble (AC Failure or Low Battery) Siren & Telephone Fault Test Reports Program, Download, & Log Full |  | 1 2 3 4 5 6 7 8 | Tampers Short Circuit & Ground Fault Sensor Lost Sensor Low Battery Expander Trouble Failure To Communicate Reserved Reserved |  |
| 17 | 15 | PHONE #3, SELECTING WHICH PARTITIONS REPORT TO PHONE #3 |  |  |  |  |  |
|  |  | Segment #1 (Circle Numbers To Program) |  |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  |  |  |  |



| 18 | 16 | FORMAT OVERRIDE |  |  |  |
| --- | --- | --- | --- | --- | --- |
|  |  | Segment #1 (Circle Numbers To Program) |  | Segment #2 (Circle Numbers To Program) |  |
|  |  | 1 2 3 4 5 6 7 8 | On = 1800hz transmit; Off = 1900hz On = 2300hz handshake; Off = 1400hz. On =cksum parity; Off = double round parity On = 2 digit event code; Off = 1 digit code Reserved. Reserved. On = 20 p.p.s.; Off = 10 or 40 p.p.s. On = 10 p.p.s.; Off = 20 or 40 p.p.s. | 1 2 3 4 5 6 7 8 | On = pager format (no handshake required) On = 1400/2300 handshake Reserved Reserved On = Contact ID On = SIA On = Contact ID or 4+3 On = DTMF |
|  |  | Segments #3 & #4 RESERVED |  |  |  |


Page 38

---

## Page 39


| LOC | PG | DESCRIPTION | DEFAULT | PROGRAMMING DATA |
| --- | --- | --- | --- | --- |



| L 19 | 16 | DOWNLOAD ACCESS CODE | 8-4-8-0-0-0-0-0 | ________ |
| --- | --- | --- | --- | --- |
| L 20 | 16 | RINGS TO ANSWER DOWNLOAD | 8 | _ |



| L 21 | 16 | DOWNLOAD CONTROL |  |
| --- | --- | --- | --- |
|  |  | Segment #1 (Circle Numbers To Program) |  |
|  |  | 1 2 3 4 5 6 7 8 | Enables two call answering machine defeat Enables tone sniff answering machine defeat Requires callback before downloading Shutdown control panel Lock out local programming Lock out communicator programming Lock out download section Enables callback at autotest interval |



| L 22 | 16 | CALLBACK PHONE NUMBER |  |  |  |  |  | 14-14-14-14-14-14-14-14-14-14- 14-14-14-14-14-14-14-14-14-14 | ____________________ ____________________ |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L 23 | 17 | PARTITION #1, FEATURE SELECTION |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 |  |  |  | Segment #2 |  |  |  |  |  | Segment #3 |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper |  | 1 2 3 4 5 6 7 8 |  | LED extinguish enable Require user code for bypassing zones Bypass sounder alert AC power/low battery sounder alert Enables bypass toggle Enables silent auto arm Enables automatic instant Reserved |  |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |



| L 24 | 17 | ENTRY/EXIT TIMERS |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1 (Entry Time #1) | 30 |  |
|  |  | Segment #2 (Exit Time #1) | 60 |  |
|  |  | Segment #3 (Entry Time #2) | 30 |  |
|  |  | Segment #4 (Exit Time #2) | 60 |  |



| L 25 | 19 | ZONES 1-8, ZONE TYPES |  |  |  |  |  |  | 3-5-6-6-6-6-6-6 |  |  |  |  |  |  |  |  | ________ |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 26 | 19 | ZONES 1-8, PARTITION SELECTION (Segment 1=Zone 1 thru Segment 8=Zone 8) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segments |  |  | 1 |  |  | 2 |  | 3 |  |  | 4 |  |  | 5 |  | 6 |  |  | 7 |  |  | 8 |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |


Page 39

---

## Page 40


| LOC | PG | DESCRIPTION |  | PROGRAMMING DATA |
| --- | --- | --- | --- | --- |
|  |  |  | DEFAULT |  |



| L 27 | 19 | ZONES 9-16, ZONE TYPES |  |  |  |  |  |  |  |  |  | 6-6-6-6-6-6-6-6 |  |  |  |  |  |  |  | ________ |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 28 19 |  | ZONES 9-16, PARTITION SELECTION (Segment 1=Zone 9 thru Segment 8=Zone 16) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  | 4 |  |  | 5 |  |  | 6 |  |  |  | 7 |  |  | 8 |  |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |



| L 29 19 |  | ZONES 17-24, ZONE TYPES |  |  |  |  |  |  |  |  |  | 6-6-6-6-6-6-6-6 |  |  |  |  |  |  |  | ________ |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 30 | 19 ZONES 17-24, PARTITION SELECTION (Segment 1=Zone 17 thru Segment 8=Zone 24) Segments 1 2 3 4 5 6 7 8 Partition #1 1 1 1 1 1 1 1 1 Partition #2 2 2 2 2 2 2 2 2 Partition #3 3 3 3 3 3 3 3 3 Partition #4 4 4 4 4 4 4 4 4 Partition #5 5 5 5 5 5 5 5 5 Partition #6 6 6 6 6 6 6 6 6 Partition #7 7 7 7 7 7 7 7 7 Partition #8 8 8 8 8 8 8 8 8 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  | 4 |  |  | 5 |  |  | 6 |  |  |  | 7 |  |  | 8 |  |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |



| L 31 | 20 | ZONES 25-32, ZONE TYPES |  |  |  |  |  |  |  |  |  | 6-6-6-6-6-6-6-6 |  |  |  |  |  |  |  | ________ |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 32 | 20 | ZONES 25-32, PARTITION SELECTION (Segment 1=Zone 25 thru Segment 8=Zone 32) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  | 4 |  |  | 5 |  |  | 6 |  |  |  | 7 |  |  | 8 |  |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |



| L 33 | 20 | ZONES 33-40, ZONE TYPES |  |  |  |  |  |  |  |  |  | 6-6-6-6-6-6-6-6 |  |  |  |  |  |  |  | ________ |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 34 | 20 | ZONES 33-40, PARTITION SELECTION (Segment 1=Zone 33 thru Segment 8=Zone 40) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  | 4 |  |  | 5 |  |  | 6 |  |  |  | 7 |  |  | 8 |  |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |


Page 40

---

## Page 41


| LOC | PG | DESCRIPTION |  | PROGRAMMING DATA |
| --- | --- | --- | --- | --- |
|  |  |  | DEFAULT |  |



| L 35 | 20 | ZONES 41-48, ZONE TYPES |  |  |  |  |  |  |  |  |  |  |  | 6-6-6-6-6-6-6-6 |  |  |  |  |  |  | ________ |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 36 20 |  | ZONES 41-48, PARTITION SELECTION (Segment 1=Zone 41 thru Segment 8=Zone 48) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segments |  |  |  | 1 |  |  | 2 |  |  | 3 |  | 4 |  |  | 5 |  |  | 6 |  |  | 7 |  |  | 8 |  |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |
| L 37 | 21 | SIREN AND SYSTEM SUPERVISION |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segment #1 (Circle numbers to program) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Siren sounds for telephone line cut while armed. Siren sounds for telephone line cut while disarmed. Siren blast at arming. Siren blast at exit delay expiration. Siren blast at closing kissoff. Siren sounds during a cross zone verification time. Siren sounds for a tamper. Siren blast one time for keyswitch arming, two times for disarming. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segment #2 (Circle numbers to program) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Convert siren driver to voltage out. Siren sounds for expander trouble (required for U.L.). Immediate Restore by zone. Dynamic battery test performed upon arming. Battery missing test performed every 12 seconds. Manual bell test performed during [r]-[4] test function. Manual communicator test performed during [r]-[4] test function. Box tamper enabled. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segment #3 (Circle numbers to program) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Box Tamper report enabled. AC Fail report enabled. Low Battery report enabled. Auxiliary power over current report enabled. Siren supervision report enabled. Telephone Line Cut report enabled. Ground Fault Detection report enabled. Expander trouble report enabled. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segment #4 (Circle numbers to program) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Failure To Communicate report enabled. Log Full report enabled. Autotest report enabled. Start and End Programming report enabled. End Download report enabled. Sensor Low Battery report enabled. Sensor Missing report enabled. Reserved. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |


Page 41

---

## Page 42


| LOC | PG | DESCRIPTION | DEFAULT | DATA |
| --- | --- | --- | --- | --- |



| L 37 | 21 | Segment #5 (Circle numbers to program) |  |  |
| --- | --- | --- | --- | --- |
|  |  | 1 2 3 4 5 6 7 8 | Lost Clock service LED enable. Zone Doubling enable. Disable on-board eight zones. Enables two trips on the same cross-zone to activate the alarm. Disables bypass reports for force armed zones Silent exit. Clock uses internal crystal. Disable Temporal Siren on Fire (Do not disable on UL listed systems) |  |



| L 38 | 21 | SWINGER SHUTDOWN COUNT |  | 0 | _ |  |
| --- | --- | --- | --- | --- | --- | --- |
| L 39 | 21 | KEYPAD SOUNDER CONTROL |  |  |  |  |
|  |  | Segment #1 (Circle numbers to program) |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Keypad sounds for Telephone Line Cut when in the Armed state. Keypad sounds for Telephone Line Cut when in the Disarmed state. Keypad sounds upon AC Power Failure. Keypad sounds upon Low Battery Detection. Keypad sounds during Cross Zone Trip Time. Keypad sounds for Tamper Alarm. Reserved. Keypad sounds for expander trouble (required for UL). |  |  |  |



| L 40 | 22 | SYSTEM TIMERS |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1 Dynamic Battery Test duration (0-255 minutes) | 0 | _ |
|  |  | Segment #2 AC Failure report delay (0-255 minutes) | 5 | _ |
|  |  | Segment #3 Power Up Delay (0-60 seconds) | 0 | _ |
|  |  | Segment #4 Siren Time (1-255 minutes) | 8 | _ |
|  |  | Segment #5 Telephone Line Cut delay (0-255 seconds) | 0 | _ |
|  |  | Segment #6 Cross Zone Time (0-255 minutes) | 5 | _ |
|  |  | Segment #7 Chime Time in 50 mS increments (0-255) | 3 | _ |
|  |  | Segment #8 Dialer delay ( 0-255 seconds) | 0 | _ |
|  |  | Segment #9 Fire Alarm Verification Time (120-255 sec.) | 0 | _ |
|  |  | Segment #10 Listen-In Time (0-255 seconds) | 0 | _ |



| 41 | 22 | SPECIAL FEATURES |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1 (Circle numbers to program) |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Enables six digit code option. All arm/disarm/Go To Program codes require six digits Requires valid user code entry for [r]-[9]-[8] and [r]-[9]-[9] functions to work. Enable Auto Cancel / Abort. Enable Walk-Test Mode. Reserved. Reserved. Reserved. Reserved. |  |



| L 42 | 22 | GO TO PROGRAM CODE | 9-7-1-3-0-0 | ______ |
| --- | --- | --- | --- | --- |


Page 42

---

## Page 43


| LOC | PG | DESCRIPTION |  |  | DEFAULT | DATA |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 43 | 22 | GO TO PROGRAM CODE PARTITION AND AUTHORIZATION |  |  |  |  |  |
|  |  |  | Segment #1 (Circle numbers to program) |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Reserved. Enables "Go To Program Code" as an arm only code. Enables "Go To Program Code" as an arm only after closing. Enables "Go To Program Code" as a master arm/disarm code (can change user codes) Enables "Go To Program Code" as an arm/disarm code. Enables "Go To Program Code" to bypass zones. Enables "Go To Program Code" opening and closing reports. Reserved. |  |  |  |
|  |  |  | Segment #2 (Circle numbers to program) |  |  |  |  |
|  |  | 1 2 3 4 5 6 7 8 |  | Enables "Go To Program Code" for partition #1. Enables "Go To Program Code" for partition #2. Enables "Go To Program Code" for partition #3. Enables "Go To Program Code" for partition #4. Enables "Go To Program Code" for partition #5. Enables "Go To Program Code" for partition #6. Enables "Go To Program Code" for partition #7. Enables "Go To Program Code" for partition #8. |  |  |  |



| L 44 | 23 | DURESS CODE |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 15-15-15-15-15-15 |  |  |  |  |  |  |  | ______ |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 45 | 23 | AUXILIARY OUTPUTS 1-4 PARTITION SELECTION |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  |  | 4 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Partition #1 Partition #2 Partition #3 Partition #4 Partition #5 Partition #6 Partition #7 Partition #8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 46 | 23 | AUXILIARY OUTPUTS 1-4 SPECIAL TIMING |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | Segments |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 |  |  | 2 |  | 3 |  |  | 4 |  |
|  |  | Auxiliary output timed in minutes. Auxiliary output to latch. Auxiliary output to stop timing upon user code entry. Auxiliary output to activate only between closing and opening time. Auxiliary output to activate only between opening and closing time. Invert auxiliary output ( 0 volts going to 12 volts when activated). Reserved Reserved |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  |
| 47 | 23 | AUXILIARY OUTPUT #1, EVENT & TIME |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1: Program the event number for output #1 here. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 0=Burglary alarm |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #2: Program the timing for output #1 here . |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 10 seconds |  |  |  |  |  |  |  |  |  |  |  |  |
| 48 | 23 | AUXILIARY OUTPUT #2, EVENT & TIME |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1: Program the event number for output #2 here. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1=Fire alarm |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #2: Program the timing for output #2 here . |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 10 seconds |  |  |  |  |  |  |  |  |  |  |  |  |
| 49 | 23 | AUXILIARY OUTPUT #3, EVENT & TIME |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1: Program the event number for output #3 here. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 2= 24 Hour Alarm |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #2: Program the timing for output #3 here . |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 10 seconds |  |  |  |  |  |  |  |  |  |  |  |  |
| 50 | 23 | AUXILIARY OUTPUT #4, EVENT & TIME |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1: Program the event number for output #4 here. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 21-Armed State |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #2: Program the timing for output #4 here . |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 0=Follow condition |  |  |  |  |  |  |  |  |  |  |  |  |


Page 43

---

## Page 44


| LOC | PG | DESCRIPTION | DEFAULT | DATA |
| --- | --- | --- | --- | --- |



| L 51 | 25 | AUTOTEST CONTROL |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Program a "1" if the interval is hours, a "0" if in days. | 0 |  |
|  |  | Add a A2" to suppress the daily test or a A3" to suppress the hourly |  |  |
|  |  | test. |  |  |
|  |  | Segment #2: Program the autotest interval from 1-255 days or hours. | 24 |  |
|  |  | Segment #3: Program the autotest report in 24 hour time format. | 2 |  |
|  |  | Segment #4: Program the autotest report time, minutes after the | 0 |  |
|  |  | hour. |  |  |
| 52 | 25 | OPENING TIME |  |  |
|  |  | Segment #1: Program the hour of the opening time. | 8 |  |
|  |  | Segment #2: Program the minutes after the hour of the opening | 0 |  |
|  |  | time. |  |  |
| 53 | 25 | CLOSING TIME / AUTO ARMING TIME |  |  |
|  |  | Segment #1: Program the hour of the closing time / auto arming | 20 |  |
|  |  | time. |  |  |
|  |  | Segment #2: Program the minutes after hour of closing / auto | 0 |  |
|  |  | arming time. |  |  |



| 54 | 25 | DAYS OF THE WEEK EACH PARTITION IS OPEN |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  |  | 4 |  |  | 5 |  |  | 6 |  |  | 7 |  | 8 |  |
|  |  | Sunday Monday Tuesday Wednesday Thursday Friday Saturday Reserved |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  |



| 55 | 25 | DAYS OF THE WEEK "AUTO ARMING" WILL OCCUR IN PARTITIONS 1-8 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  | Segments |  |  | 1 |  |  | 2 |  |  | 3 |  |  | 4 |  |  | 5 |  |  | 6 |  |  | 7 |  | 8 |  |
|  |  | Sunday Monday Tuesday Wednesday Thursday Friday Saturday Reserved |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  |  | 1 2 3 4 5 6 7 8 |  | 1 2 3 4 5 6 7 8 |  |  |



| 56 | 26 | RESTORE COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Partition #1 Restore code | 0 | _ |
|  |  | Segment #2: Partition #2 Restore code | 0 | _ |
|  |  | Segment #3: Partition #3 Restore code | 0 | _ |
|  |  | Segment #4: Partition #4 Restore code | 0 | _ |
|  |  | Segment #5: Partition #5 Restore code | 0 | _ |
|  |  | Segment #6: Partition #6 Restore code | 0 | _ |
|  |  | Segment #7: Partition #7 Restore code | 0 | _ |
|  |  | Segment #8: Partition #8 Restore code | 0 | _ |


Page 44

---

## Page 45


| LOC | PG | DESCRIPTION | DEFAULT |  |
| --- | --- | --- | --- | --- |
|  |  |  |  | DATA |
| 57 | 26 | BYPASS COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY |  |  |
|  |  | Segment #1: Partition #1 Bypass code | 0 | _ |
|  |  | Segment #2: Partition #2 Bypass code | 0 | _ |
|  |  | Segment #3: Partition #3 Bypass code | 0 | _ |
|  |  | Segment #4: Partition #4 Bypass code | 0 | _ |
|  |  | Segment #5: Partition #5 Bypass code | 0 | _ |
|  |  | Segment #6: Partition #6 Bypass code | 0 | _ |
|  |  | Segment #7: Partition #7 Bypass code | 0 | _ |
|  |  | Segment #8: Partition #8 Bypass code | 0 | _ |



| 58 | 26 | TAMPER COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Partition #1 Tamper Code | 0 | _ |
|  |  | Segment #2: Partition #2 Tamper Code | 0 | _ |
|  |  | Segment #3: Partition #3 Tamper Code | 0 | _ |
|  |  | Segment #4: Partition #4 Tamper Code | 0 | _ |
|  |  | Segment #5: Partition #5 Tamper Code | 0 | _ |
|  |  | Segment #6: Partition #6 Tamper Code | 0 | _ |
|  |  | Segment #7: Partition #7 Tamper Code | 0 | _ |
|  |  | Segment #8: Partition #8 Tamper Code | 0 | _ |



| 59 | 27 | TROUBLE COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Partition #1 Trouble Code | 0 | _ |
|  |  | Segment #2: Partition #2 Trouble Code | 0 | _ |
|  |  | Segment #3: Partition #3 Trouble Code | 0 | _ |
|  |  | Segment #4: Partition #4 Trouble Code | 0 | _ |
|  |  | Segment #5: Partition #5 Trouble Code | 0 | _ |
|  |  | Segment #6: Partition #6 Trouble Code | 0 | _ |
|  |  | Segment #7: Partition #7 Trouble Code | 0 | _ |
|  |  | Segment #8: Partition #8 Trouble Code | 0 | _ |



| 60 | 27 | SENSOR LOW BATTERY COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Partition #1 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #2: Partition #2 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #3: Partition #3 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #4: Partition #4 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #5: Partition #5 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #6: Partition #6 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #7: Partition #7 Sensor Low Battery Code | 0 | _ |
|  |  | Segment #8: Partition #8 Sensor Low Battery Code | 0 | _ |



| 61 | 27 | SENSOR MISSING COMMUNICATOR CODE, SLOW SPEED FORMATS ONLY |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Partition #1 Sensor Missing Code | 0 | _ |
|  |  | Segment #2: Partition #2 Sensor Missing Code | 0 | _ |
|  |  | Segment #3: Partition #3 Sensor Missing Code | 0 | _ |
|  |  | Segment #4: Partition #4 Sensor Missing Code | 0 | _ |
|  |  | Segment #5: Partition #5 Sensor Missing Code | 0 | _ |
|  |  | Segment #6: Partition #6 Sensor Missing Code | 0 | _ |
|  |  | Segment #7: Partition #7 Sensor Missing Code | 0 | _ |
|  |  | Segment #8: Partition #8 Sensor Missing Code | 0 | _ |


Page 45

---

## Page 46


| LOC | PG | DESCRIPTION | DEFAULT |  |
| --- | --- | --- | --- | --- |
|  |  |  |  | DATA |



| COMMUNICATOR CODES FOR SLOW SPEED FORMATS ONLY |  |  |  |  |
| --- | --- | --- | --- | --- |
| 62 | 27 | DURESS | 0-0 | __ |
| 63 | 27 | AUXILIARY 1 | 0-0 | __ |
| 64 | 27 | AUXILIARY 2 | 0-0 | __ |
| 65 | 28 | KEYPAD PANIC | 0-0 | __ |
| 66 | 28 | KEYPAD MULTIPLE CODE ENTRY TAMPER | 0-0 | __ |
| 67 | 28 | BOX TAMPER / BOX TAMPER RESTORE | 0-0-0-0 | ____ |
| 68 | 28 | AC FAIL / AC RESTORE | 0-0-0-0 | ____ |
| 69 | 28 | LOW BATTERY / LOW BATTERY RESTORE | 0-0-0-0 | ____ |
| 70 | 28 | POWER SHORT / POWER SHORT RESTORE | 0-0-0-0 | ____ |
| 71 | 28 | BELL TAMPER / BELL TAMPER RESTORE | 0-0-0-0 | ____ |
| 72 | 28 | TELEPHONE LINE CUT/TELEPHONE LINE CUT RESTORE | 0-0-0-0 | ____ |
| 73 | 28 | GROUND FAULT / GROUND FAULT RESTORE | 0-0-0-0 | ____ |
| 74 | 29 | EXPANDER TROUBLE / EXPANDER TROUBLE RESTORE | 0-0-0-0 | ____ |
| 75 | 29 | FAILURE TO COMMUNICATE | 0-0 | __ |
| 76 | 29 | LOG FULL COMMUNICATOR CODE | 0-0 | __ |



| 77 | 29 | OPENING CODE COMMUNICATOR CODE |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Opening Code for Partition #1 | 0 | _ |
|  |  | Segment #2: Opening Code for Partition #2 | 0 | _ |
|  |  | Segment #3: Opening Code for Partition #3 | 0 | _ |
|  |  | Segment #4: Opening Code for Partition #4 | 0 | _ |
|  |  | Segment #5: Opening Code for Partition #5 | 0 | _ |
|  |  | Segment #6: Opening Code for Partition #6 | 0 | _ |
|  |  | Segment #7: Opening Code for Partition #7 | 0 | _ |
|  |  | Segment #8: Opening Code for Partition #8 | 0 | _ |



| 78 | 29 | CLOSING COMMUNICATOR CODE |  |  |
| --- | --- | --- | --- | --- |
|  |  | Segment #1: Closing Code for Partition #1 | 0 | _ |
|  |  | Segment #2: Closing Code for Partition #2 | 0 | _ |
|  |  | Segment #3: Closing Code for Partition #3 | 0 | _ |
|  |  | Segment #4: Closing Code for Partition #4 | 0 | _ |
|  |  | Segment #5: Closing Code for Partition #5 | 0 | _ |
|  |  | Segment #6: Closing Code for Partition #6 | 0 | _ |
|  |  | Segment #7: Closing Code for Partition #7 | 0 | _ |
|  |  | Segment #8: Closing Code for Partition #8 | 0 | _ |



| 79 | 29 | AUTOTEST COMMUNICATOR CODE | 0-0 | __ |
| --- | --- | --- | --- | --- |
| 80 | 29 | RECENT CLOSING AND EXIT ERROR | 0-0 | __ |
| 81 | 30 | START PROGRAMMING / END PROGRAMMING | 0-0-0-0 | ____ |
| 82 | 30 | END DOWNLOAD | 0-0-0-0 | ____ |
| 83 | 30 | CANCEL COMMUNICATOR CODE | 0 | _ |
| 84-87 | 30 | RESERVED | 0-0-0-0 | RESERVED |
| 88 | 30 | PARTITION 1, ACCOUNT CODE | 10-10-10-10-10-10 | ______ |
| 89 | 30 | PARTITION 2, ACCOUNT CODE | 10-10-10-10-10-10 | ______ |


Page 46

---

## Page 47


| LOC | PG | DESCRIPTION |  |  |  |  | DEFAULT |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |  |  |  |  |  | DATA |
| 90 | 30 | PARTITION 2, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 |  |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper | 1 2 3 4 5 6 7 8 |  | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 91 | 30 | PARTITION 2 ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  |  | 0 |  |  |  |  | _ |



| 92 | 30 | PARTITION 3, ACCOUNT CODE |  |  |  |  | 10-10-10-10-10-10 |  |  |  |  | ______ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 93 | 31 | PARTITION 3, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 |  |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper |  | 1 2 3 4 5 6 7 8 | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 94 | 31 | PARTITION 3 ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  |  | 0 |  |  |  |  | _ |



| 95 | 31 | PARTITION 4, ACCOUNT CODE |  |  |  | 10-10-10-10-10-10 |  |  |  |  | ______ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 96 | 31 | PARTITION 4, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper | 1 2 3 4 5 6 7 8 | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 97 | 31 | PARTITION 4, ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  | 0 |  |  |  |  | _ |



| 98 | 31 | PARTITION 5, ACCOUNT CODE | 10-10-10-10-10-10 | ______ |
| --- | --- | --- | --- | --- |


Page 47

---

## Page 48


| LOC | PG | DESCRIPTION | DEFAULT |  |
| --- | --- | --- | --- | --- |
|  |  |  |  | DATA |



| 99 | 31 | PARTITION 5, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | Segment #1 |  |  |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper |  | 1 2 3 4 5 6 7 8 |  | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 100 | 31 | PARTITION 5, ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |



| 101 | 32 | PARTITION 6, ACCOUNT CODE |  |  |  |  |  | 10-10-10-10-10-10 |  |  |  |  | ______ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 102 | 32 | PARTITION 6, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 |  |  |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper |  | 1 2 3 4 5 6 7 8 |  | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 103 | 32 | PARTITION 6, ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |



| 104 | 32 | PARTITION 7, ACCOUNT CODE |  |  |  |  |  | 10-10-10-10-10-10 |  |  |  |  | ______ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 105 | 32 | PARTITION 7, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 |  |  |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper |  | 1 2 3 4 5 6 7 8 |  | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 106 | 32 | PARTITION 7, ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |



| 107 | 32 | PARTITION 8, ACCOUNT CODE | 10-10-10-10-10-10 | ______ |
| --- | --- | --- | --- | --- |


Page 48

---

## Page 49


| LOC | PG | DESCRIPTION | DEFAULT | DATA |
| --- | --- | --- | --- | --- |



| 108 | 32 | PARTITION 8, FEATURE AND REPORTING SELECTION |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | Segment #1 |  |  |  | Segment #2 |  |  |  |  | Segment #3 |  |  |
|  |  | 1 2 3 4 5 6 7 8 | Quick Arm Re-Exit Auto Bypass Silent Panic Audible Panic Auxiliary 1 Auxiliary 2 Multi Keypress Tamper |  | 1 2 3 4 5 6 7 8 |  | LED Extinguish enable Require user code for bypassing zones Bypass sounder alert AC Power/Low Battery sounder alert Enables Bypass toggle Enables Silent Auto Arm Enables Automatic Instant Reserved |  |  | 1 2 3 4 5 6 7 8 |  | Open/Close Bypass Restore Trouble Tamper Cancel Recent Closing Exit Error |  |
| 109 | 33 | PARTITION 8, ENTRY/EXIT TIMERS |  |  |  |  |  |  |  |  |  |  |  |
|  |  | Segment #1 (Entry Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #2 (Exit Time #1) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #3 (Entry Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |
|  |  | Segment #4 (Exit Time #2) |  |  |  |  |  | 0 |  |  |  |  | _ |



| 110 | 33 | ZONE TYPE 1 ALARM EVENT CODE |  |  |  | 8 |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 111 | 33 | _ ZONE TYPE 1 CHARACTERISTIC SELECT |  |  |  |  |  |
|  |  | Segment #1 (Circle numbers to program) |  |  |  |  |  |
|  |  | 1 2 3 4 | Fire (enable for fire zone). 24 Hour (enable for non-fire 24 hour zone). Keyswitch zone. Follower (enable for burg zones that are instant during non-entry times). | 5 6 7 8 | Delay 1 zone (enable to follow Timer 1 Entry/Exit times). Delay 2 zone (enable to follow Timer 2 Entry / Exit times). Interior (Enable for auto bypass or stay arming). Local Only (enable if zone is not to be reported). |  |  |
|  |  | Segment #2 (Circle numbers to program) |  |  |  |  |  |
|  |  | 1 2 3 4 | Keypad audible on alarm. Yelping siren on alarm. Temporal siren on alarm. Chime. | 5 6 7 8 | Bypassable. Group Shunt. Force armable. Entry Guard. |  |  |
|  |  | Segment #3 (Circle numbers to program) |  |  |  |  |  |
|  |  | 1 2 3 4 | Fast Loop Response. Double End of Line Tamper zone. Trouble zone (Day zone). Cross Zone. | 5 6 7 8 | Dialer Delay zone. Swinger zone. Restore reporting. Listen-In. |  |  |


**THE DEFAULTS LISTED IN THE ODD NUMBERED LOCATIONS BELOW REPRESENT THE THREE SEGMENTS OF**
**EACH** **OF** **THOSE** **LOCATIONS.** **USE** **THE** **THREE** **SEGMENT** **CHARTS** **FROM** **LOCATION** **111** **TO** **UNDERSTAND**
**THESE DEFAULTS.**


| 112 | 33 | ZONE TYPE 2 ALARM EVENT CODE | 2 | _ |
| --- | --- | --- | --- | --- |
| 113 | 33 | ZONE TYPE 2 CHARACTERISTIC SELECT | 2-125-78 |  |
| 114 | 33 | ZONE TYPE 3 ALARM EVENT CODE | 7 | _ |
| 115 | 34 | ZONE TYPE 3 CHARACTERISTIC SELECT | 5-1245-5678 |  |
| 116 | 34 | ZONE TYPE 4 ALARM EVENT CODE | 5 | _ |
| 117 | 34 | ZONE TYPE 4 CHARACTERISTIC SELECT | 45-125-5678 |  |
| 118 | 34 | ZONE TYPE 5 ALARM EVENT CODE | 5 | _ |
| 119 | 34 | ZONE TYPE 5 CHARACTERISTIC SELECT | 457-125-5678 |  |
| 120 | 34 | ZONE TYPE 6 ALARM EVENT CODE | 4 | _ |
| 121 | 34 | ZONE TYPE 6 CHARACTERISTIC SELECT | 0-1245-5678 |  |
| 122 | 34 | ZONE TYPE 7 ALARM EVENT CODE | 0 | _ |
| 123 | 34 | ZONE TYPE 7 CHARACTERISTIC SELECT | 2-0-78 |  |
| 124 | 34 | ZONE TYPE 8 ALARM EVENT CODE | 1 | _ |


Page 49

---

## Page 50


| 125 | 34 | ZONE TYPE 8 CHARACTERISTIC SELECT | 1-13-378 |  |
| --- | --- | --- | --- | --- |
| 126 | 34 | ZONE TYPE 9 ALARM EVENT CODE | 7 | _ |
| 127 | 34 | ZONE TYPE 9 CHARACTERISTIC SELECT | 6-1245-5678 |  |
| 128 | 34 | ZONE TYPE 10 ALARM EVENT CODE | 2 | _ |
| 129 | 35 | ZONE TYPE 10 CHARACTERISTIC SELECT | 24-5-78 |  |
| 130 | 35 | ZONE TYPE 11 ALARM EVENT CODE | 3 | _ |
| 131 | 35 | ZONE TYPE 11 CHARACTERISTIC SELECT | 3-0-0 |  |
| 132 | 35 | ZONE TYPE 12 ALARM EVENT CODE | 5 | _ |
| 133 | 35 | ZONE TYPE 12 CHARACTERISTIC SELECT | 457-125-45678 |  |
| 134 | 35 | ZONE TYPE 13 ALARM EVENT CODE | 4 | _ |
| 135 | 35 | ZONE TYPE 13 CHARACTERISTIC SELECT | 0-12458-5678 |  |
| 136 | 35 | ZONE TYPE 14 ALARM EVENT CODE | 7 | _ |
| 137 | 35 | ZONE TYPE 14 CHARACTERISTIC SELECT | 5-12456-5678 |  |
| 138 | 35 | ZONE TYPE 15 ALARM EVENT CODE | 5 | _ |
| 139 | 35 | ZONE TYPE 15 CHARACTERISTIC SELECT | 457-1256-5678 |  |
| 140 | 35 | ZONE TYPE 16 ALARM EVENT CODE | 4 | _ |
| 141 | 35 | ZONE TYPE 16 CHARACTERISTIC SELECT | 0-12456-5678 |  |
| 142 | 36 | ZONE TYPE 17 ALARM EVENT CODE | 7 | _ |
| 143 | 36 | ZONE TYPE 17 CHARACTERISTIC SELECT | 5-1245-25678 |  |
| 144 | 36 | ZONE TYPE 18 ALARM EVENT CODE | 5 | _ |
| 145 | 36 | ZONE TYPE 18 CHARACTERISTIC SELECT | 457-125-25678 |  |
| 146 | 36 | ZONE TYPE 19 ALARM EVENT CODE | 4 | _ |
| 147 | 36 | ZONE TYPE 19 CHARACTERISTIC SELECT | 0-1245-25678 |  |
| 148 | 36 | ZONE TYPE 20 ALARM EVENT CODE | 7 | _ |
| 149 | 36 | ZONE TYPE 20 CHARACTERISTIC SELECT | 6-1245-25678 |  |


**ZONE** **WORKSHEET**


|  | 1 |  |  |  | 13 |  |  |  | 25 |  |  |  | 37 |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | 2 |  |  |  | 14 |  |  |  | 26 |  |  |  | 38 |  |  |
|  | 3 |  |  |  | 15 |  |  |  | 27 |  |  |  | 39 |  |  |
|  | 4 |  |  |  | 16 |  |  |  | 28 |  |  |  | 40 |  |  |
|  | 5 |  |  |  | 17 |  |  |  | 29 |  |  |  | 41 |  |  |
|  | 6 |  |  |  | 18 |  |  |  | 30 |  |  |  | 42 |  |  |
|  | 7 |  |  |  | 19 |  |  |  | 31 |  |  |  | 43 |  |  |
|  | 8 |  |  |  | 20 |  |  |  | 32 |  |  |  | 44 |  |  |
|  | 9 |  |  |  | 21 |  |  |  | 33 |  |  |  | 45 |  |  |
|  | 10 |  |  |  | 22 |  |  |  | 34 |  |  |  | 46 |  |  |
|  | 11 |  |  |  | 23 |  |  |  | 35 |  |  |  | 47 |  |  |
|  | 12 |  |  |  | 24 |  |  |  | 36 |  |  |  | 48 |  |  |


Page 50

---

## Page 51

**APPENDIX 1 REPORTING FIXED CODES IN CONTACT ID AND SIA**
The table below list the event codes sent for the following reports (if enabled) when using CONTACT ID or SIA
formats.

**REPORT**
**CONTACT ID**
**SIA**

MANUAL TEST
601
RX
AUTOTEST
602
RP
OPEN (user number)
401
OP
CLOSE (user number)
401
CL
CANCEL (user number)
406
OC
DOWNLOAD COMPLETE
412
RS
START PROGRAM
627
LB
END PROGRAM
628
LX
GROUND FAULT
310
GF
GROUND FAULT RESTORE
310
GK
RECENT CLOSE (user number)
401
CR
EXIT ERROR (user number)
457
EE
EVENT LOG FULL
605
JL
FAIL TO COMMUNICATE
354
RT
EXPANDER TROUBLE (device number)
333
ET
EXPANDER RESTORE (device number)
333
ER
TELEPHONE FAULT
351
LT
TELEPHONE RESTORE
351
LR
SIREN TAMPER (device number)
321
YA
SIREN RESTORE (device number)
321
YH
AUX POWER OVER CURRENT (device number)
312
YP
AUX POWER RESTORE (device number)
312
YQ
LOW BATTERY (device number)
309
YT
LOW BATTERY RESTORE (device number)
309
YR
AC FAIL (device number)
301
AT
AC RESTORE (device number)
301
AR
BOX TAMPER (device number)
137
TA
BOX TAMPER RESTORE (device number)
137
TR
KEYPAD TAMPER
137
TA
KEYPAD PANIC (audible)
120
PA
KEYPAD PANIC (silent)
121
HA
DURESS
121
HA
KEYPAD AUXILIARY 1
110
FA
KEYPAD AUXILIARY 2
100
MA
RF SENSOR LOST (zone number)
381
*T
RF SENSOR RESTORE (zone number)
381
*R
SENSOR LOW BATTERY (zone number)
384
XT
SENSOR BATTERY RESTORE (zone number)
384
XR
ZONE TROUBLE (zone number)
380
*T
ZONE TROUBLE RESTORE (zone number)
380
*R
ZONE TAMPER (zone number)
137
TA
ZONE TAMPER RESTORE (zone number)
137
TR
ZONE BYPASS (zone number)
570
*B
BYPASS RESTORE (zone number)
570
*U

**THE NUMBER IN PARENTHESES FOLLOWING THE EVENT IS THE NUMBER THAT WILL BE REPORTED**
**AS THE ZONE NUMBER. IF THERE ARE NO PARENTHESES, THE ZONE WILL BE** A **0". SEE PAGE 53 FOR**
**THE DEVICE NUMBERS.**

*** The character transmitted in this slot will be the first character from the event code of the zone that**
**is bypassed or in trouble.** **(See locations 110 - 141)**

Page 51

---

## Page 52

**APPENDIX 2 REPORTING ZONE CODES IN SIA OR CONTACT ID**

The NX-8 has the ability to report SIA level 1 transmissions to either or both phone numbers. Each report in SIA
consists of an Event Code and a Zone or User ID. The Zone ID will be the zone number that is in alarm. The event
code will come from the chart below and be programmed in the zone type event code.

**Programmed Event Code**
**SIA Code**
**Description**

0
HA
Holdup Alarm
1
FA
Fire Alarm
2
PA
Panic alarm
3
BA
Burglary Alarm
4
BA
Burglary Alarm
5
BA
Burglary Alarm
6
UA
Untyped Alarm
7
BA
Burglary Alarm
8
BA
Burglary Alarm
9
UA
Untyped Alarm
10
HA
Holdup Alarm
11
MA
Medical Alarm
12
PA
Panic alarm
13
TA
Tamper Alarm
14
RP
Periodic Test
15
GA
Gas Alarm
16
KA
Heat Alarm
17
WA
Water Alarm
18
QA
Emergency Alarm
19
SA
Sprinkler Alarm
20
ZA
Freeze Alarm

The NX-8 has the ability to report Ademco Contact ID transmissions. Each report in Contact ID consists of an Event
Code and a Zone ID. The zone ID is the zone that created the alarm. The event code will come from the chart below
and be programmed in the zone type event code.

**Programmed Event Code**
**Contact ID Code**
**Description**

0
122
Silent Panic
1
110
Fire Alarm
2
120
Panic alarm
3
130
Burglary Alarm
4
131
Perimeter Alarm
5
132
Interior Alarm
6
133
24 Hour Burglary
7
134
Entry Alarm
8
135
Day/Night Alarm
9
150
Non Burglary 24 Hour
10
121
Duress Alarm
11
100
Medical Alarm
12
123
Audible Panic Alarm
13
137
Tamper Alarm
14
602
Periodic Test
15
151
Gas Detected
16
158
High Temp
17
154
Water Leakage
18
140
General Alarm
19
140
General Alarm
20
159
Low Temp

Page 52

---

## Page 53

**APPENDIX 3 EXPANDER NUMBERS FOR REPORTING EXPANDER TROUBLE**

The tables below list the device numbers that will be reported for trouble conditions.


|  | Device |  |  | Device # reported |  |
| --- | --- | --- | --- | --- | --- |
| NX-8 Control Panel |  |  | 0 |  |  |
| NX-534E Two Way Listen-In |  |  | 64 |  |  |
| NX-540E “Operator” |  |  | 40 |  |  |
| NX-580E Cellemetry Interface |  |  | 76 |  |  |
| NX-870E Fire Supervision |  |  | 9 |  |  |


**KEYPADS**


|  | KEYPAD |  |  | PART 1 |  | PART 2 |  |  | PART 3 |  |  | PART 4 |  |  | PART 5 |  |  | PART 6 |  |  | PART 7 |  |  | PART 8 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 |  |  | 192 |  | 193 |  |  | 194 |  |  | 195 |  |  | 196 |  |  | 197 |  |  | 198 |  |  | 199 |  |
| 2 |  |  | 200 |  | 201 |  |  | 202 |  |  | 203 |  |  | 204 |  |  | 205 |  |  | 206 |  |  | 207 |  |
| 3 |  |  | 208 |  | 209 |  |  | 210 |  |  | 211 |  |  | 212 |  |  | 213 |  |  | 214 |  |  | 215 |  |
| 4 |  |  | 216 |  | 217 |  |  | 218 |  |  | 219 |  |  | 220 |  |  | 221 |  |  | 222 |  |  | 223 |  |
| 5 |  |  | 224 |  | 225 |  |  | 226 |  |  | 227 |  |  | 228 |  |  | 229 |  |  | 230 |  |  | 231 |  |
| 6 |  |  | 232 |  | 233 |  |  | 234 |  |  | 235 |  |  | 236 |  |  | 237 |  |  | 238 |  |  | 239 |  |
| 7 |  |  | 240 |  | 241 |  |  | 242 |  |  | 243 |  |  | 244 |  |  | 245 |  |  | 246 |  |  | 247 |  |
| 8 |  |  | 248 |  | 249 |  |  | 250 |  |  | 251 |  |  | 252 |  |  | 253 |  |  | 254 |  |  | 255 |  |


**HARDWIRE EXPANDER** (NX-216)
**OUTPUT MODULE** (NX-508 / NX-508E)


|  | Starting zone number |  | Expander # reported |  |
| --- | --- | --- | --- | --- |
| Zone 9 (All switches off) |  | 22 |  |  |
| Zone 9 (Switch 1 on) |  | 23 |  |  |
| Zone 17 (Switch 2 on) |  | 16 |  |  |
| Zone 25 (Switch 1 & 2 on) |  | 17 |  |  |
| Zone 33 (Switch 3 on) |  | 18 |  |  |
| Zone 41 (Switch 1 & 3 on) |  | 19 |  |  |


| Address & Dip Switch Setting |  |  |
| --- | --- | --- |
| 24 | (Switch 1 & 2 on) |  |
| 25 | (Switch 3 on) |  |
| 26 | (Switch 1 & 3 on) |  |
| 27 | (Switch 2 & 3 on) |  |
| 28 | (Switch 1,2,&3 on) |  |
| 29 | (All switches off) |  |
| 30 | (Switch 1 on) |  |
| 31 | (Switch 2 on) |  |


**WIRELESS RECEIVER** (NX-448 / NX-448E)
**REMOTE POWER SUPPLY** (NX-320/NX-320E)


|  | Switch Setting |  |  | Expander # reported |  |
| --- | --- | --- | --- | --- | --- |
| All switches off |  |  | 35 |  |  |
| Switch 1 on |  |  | 36 |  |  |
| Switch 2 on |  |  | 37 |  |  |
| Switches 1 & 2 on |  |  | 38 |  |  |
| Switch 3 on |  |  | 39 |  |  |
| Switches 1 & 3 on |  |  | 32 |  |  |
| Switches 2 & 3 on |  |  | 33 |  |  |
| Switch 1, 2 & 3 on |  |  | 34 |  |  |


|  | Address & Dip Switch Setting |  |  |
| --- | --- | --- | --- |
| 84 |  | (All switches off) |  |
| 85 |  | (Switch 1 on) |  |
| 86 |  | (Switch 2 on) |  |
| 87 |  | (Switch 1 & 2 on) |  |
| 88 |  | (Switch 3 on) |  |
| 89 |  | (Switch 1 & 3 on) |  |
| 90 |  | (Switch 2 & 3 on) |  |
| 91 |  | (Switches 1, 2, & 3 on) |  |


Page 53

---

## Page 54

**NX-8 WIRING DIAGRAM**
� ***For CE labeled products, please refer to page 57 for specific electrical requirements.***

Page 54

---

## Page 55

**TERMINAL DESCRIPTION**


|  | TERMINAL |  |  | DESCRIPTION |  |
| --- | --- | --- | --- | --- | --- |
|  | R1 |  | House Telephone Ring (Grey). |  |  |
|  | R |  | Telephone Ring (Red). |  |  |
|  | T |  | Telephone Tip (Green). |  |  |
|  | T1 |  | House Telephone Tip (Brown). |  |  |
|  | EARTH |  | Earth Ground. Connect to a cold water pipe or a 6 to 10 foot driven rod. |  |  |
|  | AC |  | AC input. Connect to a 16.5V 25, 40 or 50 VA Class ll U.L. approved transformer. |  |  |
| BELL + & BELL - |  |  | If used as a siren output(default), the speaker rating should be 15 watt at 8 or 16 ohm, or 30/40 watt at 4, 8, or 16 ohms. If voltage output is selected in location 37, this output becomes voltage output, 12VDC, 1 Amp maximum load. NOTE: A 3.3K Ωresistor may be required across the bell terminals when a 12 VDC siren is used. If no resistor is used, you may experience voltage leakage into the siren which will cause these devices to output a small signal. |  |  |
| KP DATA |  |  | Connect to the data terminal on the keypads and the expanders. Maximum number of devices (keypads + expanders) is 32. See AMaximum Wire Run@ chart below. |  |  |
|  | KP COM |  | Connect to the Common terminal on the keypads and the expanders. |  |  |
| KP POS |  |  | Connect to the POS terminal on the keypads and the expanders. This terminal and AUX PWR + are limited to 1 amp total current when added together. |  |  |
| SMOKE+ |  |  | Smoke detector power 12VDC, 1.5 amps maximum (For those jurisdictions which allow the Priority zone to be used with smoke detectors.) |  |  |
|  | COM |  | Connect negative wire of powered devices such as motion detectors and smoke detectors. |  |  |
| AUX PWR+ |  |  | Connect positive wire of all powered devices except smoke detectors and keypads. This terminal and KP POS are limited to 1 amp total current when added together. |  |  |
| ZONE 8 |  |  | Connect to one side of zone 8 loop. Connect the other side to com terminal. Open or short causes alarm. Zone 8 may be used for a two-wire smoke detector using a 680 ΩE.O.L. resistor. W3 must be set for two-wire smoke detector loop. For normal zone operation, W4 must be set. |  |  |
|  | COM |  | Common (-) terminal for zones 7 & 8. (See the wiring diagram for examples.) |  |  |
| ZONE 7 |  |  | Connect to one side of zone 7 loop. Connect the other side to COM terminal. Open or short causes alarm. |  |  |
|  | ZONE 6 - |  | Connect as described for zones 7 & 8. Only zone 8 can be a two-wire zone. (See the wiring diagram for examples.) |  |  |
|  | ZONE 1 |  |  |  |  |
| AUX 4 – AUX 1 |  |  | Connect negative lead of low current device [relay, LED(install 1kΩresistor in series with LED), etc.]. Connect positive lead of device to AUX PWR +. Current is limited to 50mA when output is negative, and 250FA when output is positive. |  |  |


**NETWORX KEYPAD MAXIMUM WIRE RUN**

**(Note:** These numbers are for one keypad at the end of the wire. When connecting more than one keypad to the
end of the wire, a higher gauge wire will be required.)


|  |  | WHEN CONNECTED TO NX-8 |  |  | WHEN CONNECTED TO NX-320 |  |
| --- | --- | --- | --- | --- | --- | --- |
| Length in feet | Wire Gauge |  |  | Wire Gauge |  |  |
| 250 | 24 |  |  | 22 |  |  |
| 500 | 20 |  |  | 18 |  |  |
| 1000 | 18 |  |  | 16 |  |  |
| 1500 | 16 |  |  | 14 |  |  |
| 2500 | 14 |  |  | 12 |  |  |


Page 55

---

## Page 56

**LOCAL TELEPHONE COMPANY INTERFACE INFORMATION**

**TELEPHONE CONNECTION REQUIREMENTS**

Except for telephone company provided ringers, all connections to the telephone network shall be made through
standard plugs and standard telephone company provided jacks or equivalent in such a manner as to allow for
immediate disconnection of the terminal equipment. Standard jacks shall be so arranged that if the plug connected
thereto is withdrawn, no interference to the operation of the equipment at the customer’s premises which remains
connected to the telephone network, shall occur by reason of such withdrawal.

**INCIDENCE OF HARM**

Should terminal equipment or protective circuitry cause harm to the telephone network, the telephone company shall,
where practical, notify the customer that temporary discontinuance of service may be required. However, where prior
notice is not practical, the telephone company may temporarily discontinue service if such action is deemed
reasonable in the circumstances. In the case of such temporary discontinuance, the telephone company shall promptly
notify the customer who will be given the opportunity to correct the situation. The customer also has the right to bring a
complaint to the FCC if he feels the disconnection is not warranted.

**CHANGES IN TELEPHONE COMPANY EQUIPMENT OR FACILITIES**

The telephone company may make changes in its communications facilities, equipment, operations, or procedures
where such action is reasonably required and proper in its business. Should any such change render the customers
terminal equipment incompatible with the telephone company facilities, the customer shall be given adequate notice to
make modifications to maintain uninterrupted service.

**GENERAL**

The FCC prohibits customer provided terminal equipment be connected to party lines.

**IMPORTANCE OF THE RINGER EQUIVALENCE NUMBER**

The Ringer Equivalence Number (REN) of this device is 0.1B. This number is a representation of the electrical load
that it applies to your telephone line.

**MALFUNCTION OF THE EQUIPMENT**

In the event that the device should fail to operate properly, the customer shall disconnect the equipment from the
telephone line to determine if it is the customers equipment that is not functioning properly. If the problem is with the
device, the customer shall discontinue use until it is repaired.

**EQUIPMENT INFORMATION**

MANUFACTURER OF CONNECTING EQUIPMENT:
**CADDX CONTROLS,** **INC.**
FCC REGISTRATION NUMBER: GCQUSA-31771-AL-T, RINGER EQUIVALENCE: 0.1 B

Page 56

---

## Page 57

**NOTICES** ***(Applies to products which***
***have the CE mark attached)***

Declaration of Conformity
**Network Compatibility Declaration**
We declare under our sole responsibility that this
product is designed to work with the networks in the
countries marked with a check ( ✓ ) and may have
interworking problems with the countries that are not
checked. Due to the inherent differences in the
individual PSTNs, certain software settings may need
to be adjusted on a country-to-country basis. If it is
desired to use this equipment on a network other than
the one on which it was originally installed, you should
contact your equipment supplier .

**Manufacturer’s Name:**
Caddx Controls
**Manufacturer’s Address:**
1420 North Main Street
Gladewater TX 75647

**EU Representative:**
Interlogix Europe

**Product Identification**
**Product:**
**NetworX**
**Model:**
**NX-8**
**Brand:**
**CADDX**


| (✓) Austria | ( ) Liechtenstein |
| --- | --- |
| (✓) Belgium | _ (✓) Luxembourg |
| (✓) Denmark | (✓) Netherlands |
| (✓) Finland | (✓) Norway |
| (✓) France | (✓) Poland |
| (✓) Germany | (✓) Portugal |
| (✓) Greece | (✓) Spain |
| (✓) Iceland | (✓) Sweden |
| (✓) Ireland | (✓) Switzerland |
| (✓) Italy | (✓) United Kingdom |


**R&TTE Directive**
See EMC and LVD tests below

**EMC Directive**
**EN50081-1**
**EN50130-4**
**EN55022**
**EN60950**
**EN61000-3-2**
**EN61000-3-3**

**Telecom Approval Notice**
This equipment has been approved in accordance with
the Council Decision 98/482/EC for pan-European,
single terminal connection to the public switched
telephone network (PSTN). However, due to the
differences between the individual PSTNs provided in
different countries, the approval does not, of itself, give
an unconditional assurance of successful operation on
every PSTN network termination point. In the event of
problems, you should contact your equipment supplier
in the first instance.
**LVD Directive**
**EN 60950** : 1999-4 3rd edition

**Means of Conformity**
We declare under our sole responsibility that this
product is in conformity with Directive 1999/5/EC
(R&TTE); Directive 73/23/EEC (LVD); and Directive
89/336/EEC (EMC) and based on test results using
(non)-harmonized standards in accordance with the
Directives mentioned.

**Electrical Requirements**
This device automatically adjusts to voltages within the
range of 230 V 50/60 Hz.
Fuse: Type T 200mA 250 VAC
**Additional Tests**
This equipment has been tested and found to comply
with the following standards (which are no longer
required for compliance).

Page 57

---

## Page 58

**UNDERWRITERS LABORATORIES INFORMATION**

The NetworX NX-8 holds the following listings from Underwriters Laboratories (US and Canadian):

**Household Burglary (UL1023) (ORD-C1023-1974)**
**Household Fire (UL985) (CAN/ULC** **S545-M89)**
**Local Grade A Mercantile, Police Station Connect with Basic Line Security (UL609) (requires #NX-003-C**
**enclosure) (CAN/ULC** **S303-M91)**
**Grade B & C Central Station Burglar Alarm Unit (UL1610) (CAN/ULC** **S304-M88)**
**Home Health Care Signaling** **(UL1637)**

When installing an NX-8 in compliance with Underwriters Laboratories, the following instructions must be observed:
! Initiating and indicating devices must be rated at 11.5 to 12.4 V DC residential, 12.0 V DC commercial.
! When using partitioning in Commercial Burglary applications, the main control must be protected by a 24-hour
alarm circuit.
! Force Arming and Auto Arming shall not be enabled.
! For residential fire applications, the indicating devices shall be a Wheelock 34T-12 or equivalent.
! The "Listen-In" feature shall not be enabled.
! The Siren/Bell Test shall be enabled. The auxiliary outputs controlling the audible device require a minimum cutoff
time of 15 minutes for commercial burglary, 4 minutes for residential applications, or 30 minutes for commercial
burglary for Canada.
! For residential fire installations, the Dynamic Battery Test time cannot exceed four (4) hours.
! Ringback shall be enabled on UL commercial burglary installations.
! On commercial burglary installations, the fire initiating circuits shall not be connected.
! The Entry-Guard feature shall be disabled.
! Swinger Shutdown shall be disabled.
! Group Bypassing shall be disabled.
! Delay before dial seizure shall be set to "0".
! Total current draw from aux power connections at terminal positions POS, AUX PWR, and SMOKE PWR must not
exceed 400 mA.
! Remote Downloading shall not be used on UL listed systems.
! For residential burglary applications, the maximum entry and exit delay times shall be 45 and 60 seconds
respectively. The exit delay time shall not exceed 60 seconds for commercial burglar alarm applications.
! The keyswitch option shall not be used.
! The telephone line monitor shall be enabled.
! The Telephone Line Cut delay shall not exceed 90 seconds.
! 24-hour communicator test transmission is required.
! For 24 hours of standby power using a 7.0 AH battery, limit auxiliary power load to 140 mA.
! For 24 hours of standby power using a 17.2 AH battery, limit auxiliary power load to 400 mA.
! The silent keypad option shall not be enabled.
! UL has only verified compatibility with the following listed DACRs and formats: Sure-Gard SG-MLR2-DG:
2,9,10,12,13,14; Silent Knight 9000 - 2,12; FBI - CP220FBI, 13; and Ademco 685: 2,11,12, and 13.
! For burglary installations, cross-zoned detectors shall overlap 100 percent in the area of coverage and similar
coverage areas must be used. For example, interior protection is cross-zoned with interior protection, and so on.
! Expander trouble must activate the siren (Loc 37, Segment 2, LED 2)
! For UL 1637, expander trouble must activate keypad sounder (Loc 39, Segment 1, LED 8)
! For Canadian installations, the class II transformer secure tab shall not be employed.

**MINIMUM SYSTEM CONFIGURATIONS FOR UL INSTALLATIONS**
**(Residential Fire, Residential Burglary, Commercial Burglary)**

! The NetworX NX-8 panel is necessary to initiate Residential and Commercial installations.
! At least one compatible keypad is needed for all applications.
! At least one bell fixture is required for all applications, except Grade C Central Station. For Grade A Local, the
AD10-12 bell and Grade A bell housing shall be used.
! Commercial UL applications require #NX-003-C metal enclosure. Supplied screws to be used.
! A minimum of two (2) keypads are required for Home Health applications and each keypad must be set to a
unique address.
! The wireless devices are only UL listed for residential applications.
! The DACT shall be enabled for all commercial burglary applications.

Page 58

---

## Page 59

**BOARD INSTALLATION**
Inside the can, several 2-holed insertion points have been
constructed. This allows for either vertical or horizontal placement of
the modules. Notice that each insertion point has two sizes of holes -
a larger hole and a smaller hole.

**Diagram 1** : The black plastic PCB guides are grooved on one edge
where the PC board will be seated. The end with the half-moon
protrusion fits into the larger hole. The smaller hole is for the screw.

**Diagram 2** : Place the *first* black plastic PCB guide in the top insertion
point, grooved edge downward. The half-moon protrusion will be in
the large hole. It does not require force. Insert one of the provided
screw into the smaller hole (from inside the can) to secure it in place.
A screwdriver should reach through the notch that runs the length of
the guide to tighten the screw. The *second* PBC guide should be
positioned opposite the first (grooved edge up) and placed in the
lower insertion point, using the same procedures described above.
Once mounted, screw it in securely.

**Diagram 3** : The PC Board should slide freely in the grooves of both
guides.

K
**IMPORTANT!**
1.
If separate power supplies are necessary to accommodate additional devices, safety
standards require that each power supply be prominently marked with adequate instructions
for removing all power from the unit.
2.
Dispose of used batteries according to the manufacturer’s instructions and/or local
government authorities.
3.
Installation personnel should thoroughly read and understand the installation instructions and
the users manuals for the panel and all the accessories to be included with the system
before attempting to install a security system.

�
**WARNING!**
Replace only with Panasonic #LC12V4BP or Yuasa #NP4-12 battery. Observe polarity when
installing a new battery. Installing the battery backwards may cause damage to the panel. There
is a risk of explosion if the battery is replaced with an incorrect type.

**NOTE**
Electrical codes will vary depending upon the country and city where the system is installed. It is
the installer’s responsibility to ensure that the electrical installation is safe and conforms to all
applicable codes, laws, or regulations. Only qualified persons should connect this device to the
mains supply.

Page 59

![Image 1 on page 59](images/GE_NetworX_NX-8_Installation_Manual_p59_img1.jpeg)


![Image 2 on page 59](images/GE_NetworX_NX-8_Installation_Manual_p59_img2.jpeg)


---

## Page 60

**SYSTEM NOTES**

Page 60

---

## Page 61

**SPECIFICATIONS**

**OPERATING POWER**
**16.5 VAC 25, 40, or 50 VA Transformer**

**AUXILIARY POWER**
**w/25 VA Transformer**
**12 VDC Regulated 500 mA**
**w/40 or 50 VA Transformer**
**12 VDC Regulated 1 AMP**
**w/NX-320 Power Supply**
**12 VDC Regulated 2 AMPS + Control**
**Panel Power**

**LOOP RESISTANCE**
**Standard Loop**
**300 Ohms Maximum**
**2-Wire Smokes**
**30 Ohms Maximum**

**BUILT-IN SIREN DRIVER**
**2-tone (Temporal and Yelp)**

**LOOP RESPONSE**
**Selectable 50mS or 500mS**

**OPERATING TEMPERATURE**
**32 to 120 degrees F**

**LED KEYPAD**
**Current Draw**
**130 mA max.**
**Zones Normal w/o Sounder**
**55 mA**
**Dimensions**
**6.4" Wide**
**4.0" High**
**1.1" Deep**

**NX-148 LCD KEYPAD**
**Current Draw**
**110 mA max.**
**w/o Sounder**
**75 mA**
**Dimensions**
**6.4" Wide**
**5.3" High**
**1.0" Deep**

**METAL ENCLOSURE DIMENSION**
**11.25" Wide**
**11.25" High**
**3.50" Deep**

**SHIPPING WEIGHT**
**9 lbs.**

**1420 NORTH MAIN STREET**
**GLADEWATER, TEXAS** **75647**
**1-800-727-2339**
**FAX 903-845-6811**

**www.caddx.com**

**NX-8 INSTALLATION MANUAL**
**NX8IP02**
**REV. P**
**(07-25-02** )

![Image 1 on page 61](images/GE_NetworX_NX-8_Installation_Manual_p61_img1.jpeg)
