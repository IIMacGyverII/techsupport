# Microsoft Word - K5305-1PRv8-C_V20P-V15P-pr.doc

**Author:** e653024  


---

## Page 1

ADEMCO VISTA SERIES
VISTA-20P / VISTA-20PSIA
VISTA-15P / VISTA-15PSIA
Security Systems

Programming Guide

K5305-1PRV8  5/11  Rev. C

![Image 1 on page 1](images/Honeywell_VISTA-15P_20P_Programming_Guide_p1_img1.jpeg)


---

## Page 2

**RECOMMENDATIONS FOR PROPER PROTECTION**

**The Following Recommendations for the Location of Fire and Burglary Detection**
**Devices Help Provide Proper Coverage for the Protected Premises.**
**Recommendations For Smoke And Heat Detectors**

With regard to the number and placement of smoke/heat detectors, we subscribe to the recommendations
contained in the National Fire Protection Association's (NFPA) Standard #72 noted below.

Early warning fire detection is best achieved by the installation of fire detection equipment in all rooms and
areas of the household as follows: For minimum protection a smoke detector should be installed outside of
each separate sleeping area, and on each additional floor of a multi-floor family living unit, including
basements. *The installation of smoke detectors in kitchens, attics (finished or unfinished), or in garages is not*
*normally recommended.*

For additional protection the NFPA recommends that you install heat or smoke detectors in the living room,
dining room, bedroom(s), kitchen, hallway(s), attic, furnace room, utility and storage rooms, basements and
attached garages.

In addition, we recommend the following:
• Install a smoke detector inside every bedroom where a smoker sleeps.
• Install a smoke detector inside every bedroom where someone sleeps with the door partly or completely
closed. Smoke could be blocked by the closed door. Also, an alarm in the hallway outside may not wake up
the sleeper if the door is closed.

• Install a smoke detector inside bedrooms
where electrical appliances (such as
portable heaters, air conditioners or
humidifiers) are used.


| KITCHEN DINING BEDROOMBEDROOM TV ROOM KITCHEN DINING BDRM LIVING ROOM BDRM LIVING ROOM BEDROOM BEDROOM Smoke Detectors for Minimum Protec Smoke Detectors for Additional Prote BEDROOM Heat-Activated Detectors TO BEDROOM BR BEDROOM KTCHN LVNG RM . CLOSED GARAGE |  | KITCHEN | DINING | BDRM |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  | BDRM |
|  | TO BEDROOM BR BEDROOM KTCHN LVNG RM . |  |  |  |


| KITCHEN | BEDROOMBEDROOM BEDROOM |
| --- | --- |


• Install a smoke detector at both ends of a
hallway if the hallway is more than 40 feet
(12 meters) long.

• Install smoke detectors in any room where
an alarm control is located, or in any room
where alarm control connections to an AC
source or phone lines are made. If detectors
are not so located, a fire within the room
could prevent the control from reporting a
fire or an intrusion.
**THIS CONTROL COMPLIES WITH NFPA**
**REQUIREMENTS FOR TEMPORAL PULSE**
**SOUNDING OF FIRE NOTIFICATION**
**APPLIANCES.**

BASEMENT
floor_plan-001-V1

**Recommendations For Proper Intrusion Protection**

For proper intrusion coverage, sensors should be located at every possible point of entry to a home or
commercial premises. This would include any skylights that may be present, and the upper windows in a
multi-level building.

In addition, we recommend that radio backup be used in a security system so that alarm signals can still be
sent to the alarm monitoring station in the event that the telephone lines are out of order (alarm signals are
normally sent over the phone lines, if connected to an alarm monitoring station).

**–** 2 **–**

---

## Page 3

**TABLE OF CONTENTS**
**PROGRAMMING MODE COMMANDS .................................................................................................................... 4**

**DATA FIELD PROGRAMMING FORM ..................................................................................................................... 5**
**CONFIGURABLE ZONE TYPES WORKSHEET .................................................................................................... 18**
∗ **56 ZONE PROGRAMMING MENU MODE ........................................................................................................... 19**
∗ **58 EXPERT ZONE PROGRAM MODE ................................................................................................................. 21**
**WIRELESS KEY PROGRAMMING TEMPLATES .................................................................................................. 22**
∗ **57 FUNCTION KEY PROGRAMMING MENU MODE .......................................................................................... 24**
**OUTPUT DEVICE PROGRAMMING GENERAL INFORMATION (*79/*80 Menu Mode) ..................................... 25**
∗ **79 RELAY/POWERLINE CARRIER DEVICE (X-10) PROGRAMMING MENU MODE ........................................ 25**
∗ **80 OUTPUT FUNCTION MENU MODE ................................................................................................................ 26**
∗ **81 ZONE LIST MENU MODE ................................................................................................................................ 28**
∗ **82 ALPHA DESCRIPTOR MENU MODE .............................................................................................................. 29**
**ALPHA VOCABULARY LIST  (For Entering Zone Descriptors) ......................................................................... 31**
**SETTING SCHEDULES .......................................................................................................................................... 32**
**AVS SYSTEM ENABLE and QUICK PROGRAMMING COMMANDS .................................................................. 33**
**SETTING THE REAL-TIME CLOCK ....................................................................................................................... 33**
∗ **29 COMMUNICATION DEVICE MENU MODE (Pass-Through Programming) ................................................. 34**
**UPLOADING/DOWNLOADING VIA the INTERNET .............................................................................................. 35**
**ZONE TYPE DEFINITIONS ..................................................................................................................................... 36**
**REPORT CODE FORMATS .................................................................................................................................... 37**
**SYSTEM SECURITY CODES ................................................................................................................................. 38**
**KEYPAD FUNCTIONS ............................................................................................................................................ 39**
**COMPATIBLE DEVICES ......................................................................................................................................... 39**
**VARIOUS SYSTEM TROUBLE DISPLAYS ............................................................................................................ 40**
**UL NOTICES ........................................................................................................................................................... 41**
**SIA QUICK REFERENCE GUIDE ........................................................................................................................... 41**
**ULC S304 REQUIREMENTS (for VISTA-15PCN and VISTA-20PCN) .................................................................. 41**
**FCC STATEMENTS ................................................................................................................................................ 42**
**LIMITATIONS STATEMENT ................................................................................................................................... 43**
**CONTACTING TECHNICAL SUPPORT ................................................................................................................. 43**
**WORKSHEET for** ∗ **56 ZONE PROGRAMMING ..................................................................................................... 44**
**WORKSHEET for** ∗ **57 FUNCTION KEY PROGRAMMING .................................................................................... 45**
**WORKSHEET for** ∗ **79 OUTPUT RELAY/POWERLINE CARRIER DEVICE PROGRAMMING ............................ 45**
**WORKSHEET for** ∗ **81 ZONE LIST PROGRAMMING ............................................................................................ 45**
**�** **WORKSHEET for** ∗ **80 OUTPUT FUNCTION PROGRAMMING ......................................................................... 46**
**WORKSHEET for SCHEDULES ............................................................................................................................. 47**
**TABLE OF DEVICE ADDRESSES .......................................................................................................................... 47**
**5800 SERIES TRANSMITTER INPUT LOOP IDENTIFICATION ........................................................................... 48**

**–** 3 **–**

---

## Page 4

**PROGRAMMING MODE COMMANDS**

**Compatibility: This document applies to systems with microprocessor version 9.1 or higher.**


| Task | Command/Explanation |
| --- | --- |
| Go to a Data Field | Press [∗] + [Field Number], followed by the required entry. |
| Entering Data | When the desired field number appears, simply make the required entry. When the last entry for a field is entered, the keypad beeps three times and automatically displays the next data field in sequence. If the number of digits that you need to enter in a data field is less than the maximum digits available (for example, the phone number fields *41, *42), enter the desired data, then press [∗ ] to end the entry. The next data field number is displayed. |
| Review a Data Field | Press [#] + [Field Number]. Data will be displayed for that field number. No changes will be accepted in this mode. |
| Deleting an Entry | Press [∗] + [Field Number] + [∗]. (Applies only to fields ∗40 thru *46, *94, and pager fields) |
| Initialize Download ID | Press ∗96. Initializes download ID and subscriber account number. |
| Reset Factory Defaults | Press ∗97. Sets all data fields to original factory default values. |
| Zone Programming | Press ∗56. Zone characteristics, report codes, alpha descriptors, and serial numbers for 5800 RF transmitters. |
| Function Key Programming | Press ∗57. Unlabeled keypad keys (known as ABCD keys) for special functions |
| Zone Programming (Expert Mode) | Press ∗58. Same options as *56 mode, but with fewer prompts. Intended for those familiar with this type of programming, otherwise *56 mode is recommended. |
| Output Device Mapping | Press ∗79. Assign module addresses and map individual relays/powerline carrier devices |
| Output Programming | Press ∗80. 4229 or 4204 Relay modules, Powerline Carrier devices, or on-board triggers |
| Zone List Programming | Press ∗81. Zone Lists for relay/powerline carrier activation, chime zones, pager zones, etc. |
| Alpha Programming | Press ∗82. Zone alpha descriptors |
| IP/GSM Programming | Press ∗29. For programming the IP/GSM options. |
| Exit Program Mode with installer code lockout | Press ∗98. Exits programming mode and prevents re-entry by: Installer Code + 8 0 0. To reenter programming mode, the system must be powered down, then powered up. Then use method A above. See field *88 for other *98 Program mode lockout options. |
| Exit Program Mode | Press ∗99. Exits program mode and allows re-entry by: Installer Code + 8 0 0 or method A above. |
| Scheduling Mode | Enter code + [#] + 64. Create schedules to automate various system functions. |
| Site-Initiated Download | Installer code + [#] + 1 (perform while system is disarmed and in normal mode) |


**AVS QUICK PROGRAMMING COMMANDS (for AAV sessions using the AVS system)**
For controls with the following firmware revision levels, these commands automatically configure the control for AVS
operation. VISTA-15P = version 6.0 or higher; VISTA-20P = version 7.0 or higher
• **installer code + [#] + [0] + 3** : enable AVS operation
• **installer code + [#] + [0] + 4** : enable AVS operation and enable panels sounds on the AVST speaker
• **installer code + [#] + [0] + 5** : remove all programming options set by [#] + [0] + 3 quick command
• **installer code + [#] + [0] + 6** : remove all programming options set by [#] + [0] + 4 quick command
Refer to the AVS SYSTEM ENABLE and QUICK PROGRAMMING COMMANDS section for details on the specific options
that are set with each command, depending on the control used.
To select the AAV session communication path (phone line/communication device), see field ∗ 55 Dynamic Signaling Priority.
To enable AAV operation, use ∗ 91 Options field (option 4).
**TO ENABLE REMOTE SERVICES**
1. Enable the Remote Interactive Services (RIS) option in

**SPECIAL PROGRAMMING MESSAGES**
• **OC** = OPEN CIRCUIT (no communication between
Keypad and Control).
• **EE** or **ENTRY ERROR** = ERROR (invalid field number
entered;  re-enter valid field number).
• After powering up, **AC, dI** (disabled) or “ **Busy Standby**
**vx.x** (firmware revision) **Dl** will be displayed after
approximately 4 seconds. This will revert to a “ **Ready** ”
message in approximately 1 minute, which allows PIRS,
etc. to stabilize.
You can bypass this delay by pressing [#] + [0].
**NOTE for CANADIAN PANELS:** Power up time is 2
minutes, and Contact ID report code 305 System Reset
is sent if the [#] + [0] command is not performed before
the 2 minutes expires.
• If **E4** or **E8** appears, more zones than the expansion
units can handle have been programmed. The display
will clear after you correct the programming.

programming field ∗ 91 (entry 2).
2. Use programming field ∗ 189 to enable a remote services

emulated keypad address.
3. Use ∗ 29 Menu mode to enable the communication

device.
4. If using Total Connect 2.0, use AlarmNet Direct website

to program the communicator and enable TC2 services.
Be sure to “send” the programming data down to the
Communicator.
**IMPORTANT: The Real-Time Clock** must be set before
the end of the installation. See procedure in the Setting the
Real-Time Clock section of this manual.

**–** 4 **–**

---

## Page 5

**DATA FIELD PROGRAMMING FORM**

Entries apply to the ADEMCO VISTA-15P/VISTA-15PSIA and ADEMCO VISTA-20P/VISTA-20PSIA controls, except entries
shown in dashed boxes, which apply only to the VISTA-20P/VISTA-20PSIA (partition entries) and are not applicable to the
VISTA-15P/VISTA-15PSIA. In addition, where noted, certain fields have special settings when used with the SIA panels
(indicated by **V20PSIA/V15PSIA** with heavy borders and reverse type throughout for easy identification).
Entry of a number other than one specified will give unpredictable results. Values shown in brackets are factory defaults.
**SIA Guidelines:** Notes in certain fields give instructions for programming the VISTA-20P/VISTA-15P for False Alarm Reduction.

**SIA Installations:** The VISTA-20PSIA and VISTA-15PSIA are certified SIA-compliant controls that meet SIA specifications for
False Alarm Reduction. The other controls described in this manual are not certified as SIA compliant, but can be
programmed for False Alarm Reduction. To program for False Alarm Reduction, follow the SIA Guidelines noted in the
applicable programming fields.


|  | ∗20 | Installer Code \| \| \| [4112] |
| --- | --- | --- |


The Installer Code is used to assign the 4-digit Master Security Code.
The Installer Code can perform all system functions except it cannot
disarm the system unless it was used to arm the system. For security
purposes, the factory default installer code should be changed.


|  | ∗21 |  | Quick Arm Enable [0,0] |
| --- | --- | --- | --- |


Part. 1
Part.2
If enabled, users can press the [#] followed by an arming key to arm
the system instead of using a security code. The security code is
always needed to disarm the system.


|  | ∗22 |  | RF Jam Option [0] |
| --- | --- | --- | --- |



|  |  |  |  | UL: must be 1 if wireless devices are used |  |
| --- | --- | --- | --- | --- | --- |
|  | ∗23 |  | Quick (Forced) Bypass [0,0] |  |  |



|  |  |  |  | UL: must be 0 |  |
| --- | --- | --- | --- | --- | --- |
|  | ∗24 |  | RF House ID Code \| \| \| [00,00,00] |  |  |


P1
P2
Common
The House ID identifies receivers and wireless keypads. If a 5827 or
5827BD Wireless Keypad or 5804BD Transmitter is being used, a
House ID code **must** be entered and the keypad set to the same
House ID. You can assign RF house ID for each partition


|  | ∗26 |  | Chime By Zone / [6, 7] |
| --- | --- | --- | --- |


1
2
**Chime by Zone**
If Chime by Zone is enabled (entry 1 – option 1), you can define the
specific zones intended to chime when faulted while the system is in
Chime mode. List chime zones on zone list 3 using *81 Menu mode.
**Keypad (KP) Trouble Sounding**
Keypad trouble sounding can be enabled/disabled for the conditions
listed for each entry.
For each entry, enter the sum of the desired options. Example Entry 1:
for Chime by Zone and System Low Battery sounding, enter 5. To
enable all options, enter 7.

**Entry 2**
0 = no “entry 2” keypad trouble sounds
1 = RF Supervision sounding enabled
2 = RF Low Battery sounding enabled
4 = RF Jam sounding enabled
7 = select all entry 2 options


|  | ∗27 |  | Powerline Carrier Device (X–10) [0] |
| --- | --- | --- | --- |


Powerline Carrier devices require a House ID, identified in this field.
Program Powerline Carrier devices in interactive modes ∗ 79, *80 and
*81.
UL: not for fire or UL installations

**–** 5 **–**

---

## Page 6


| ∗28 |  |
| --- | --- |

| [00]


| UL: must be 00 for UL Commercial Burg. installations |  |  |  |
| --- | --- | --- | --- |
| ∗29 Enable IP/GSM? – Communication Device Menu Mode (pass-through programming) This is a Menu Mode command, not a data field, for programming IP/GSM communication device options. See ∗29 Menu Mode section later in this document. |  |  |  |
|  | ∗31 |  | Single Alarm Sounding Per Zone [0] |


If enabled, limits alarm sounding on the bell output to once per zone
per armed period.

**V20PSIA/V15PSIA:** If “0” selected,
“alarm sounding per zone” will be the
same as the “number of reports in
armed period” set in field *93 (1 if one
report, 2 if 2 reports, unlimited for
zones in zone list 7).


|  | ∗32 |  | Fire Alarm Sounder Timeout [0] |
| --- | --- | --- | --- |



| UL: must be 1 for fire installations |  |  |  |
| --- | --- | --- | --- |
|  | ∗33 |  | Alarm Sounder (Bell) Timeout [1] |



| UL: For residential fire alarm installation, must be set for a minimum of 4 min (option 1); for UL Commercial Burglary installations, must be minimum 16 min (option 4) |  |  |  |
| --- | --- | --- | --- |
|  | ∗34 |  | Exit Delay \| \| [60,60] |


Part. 1
Part. 2


| in a 45-second delay. UL installations: For UL Commercial Burglar Alarm and UL Residential Burglar Alarm installations with line security, total exit time must not exceed 60 seconds. |  |  |  |
| --- | --- | --- | --- |
|  | ∗35 |  | Entry Delay #1 \| \| [30,30] |



| V20PSIA/V15PSIA: SIA Guidelines: minimum entry delay is 30 seconds 30-96 = 30 - 96 secs; 97 = 120 secs; For UL Residential Burglary Alarm installations, must be set for a maximum of 30 seconds; entry delay plus dial delay should not exceed 1 min. For UL 98 = 180 secs; 99 = 240 secs Commercial Burglar Alarm, total entry delay may not exceed 45 seconds. NOTE: Entries less than 30 will result Upon entering, the system must be disarmed before the time entered expires, in a 30-second delay. otherwise it sounds an alarm. |  |  |  |
| --- | --- | --- | --- |
|  | ∗36 |  | Entry Delay #2 \| \| [30,30] |


Part. 1
Part. 2

|  | ∗37 |  | Audible Exit Warning [1,1] |
| --- | --- | --- | --- |

Part. 1
Part. 2
Warning sound consists of slow continuous beeps until the last 10
seconds, and then it changes to fast beeps. Sound ends when exit time
expires.
SIA Guidelines: must be enabled
**V20PSIA/V15PSIA:** Feature always
enabled; field does not exist.

**–** 6 **–**

---

## Page 7


| ∗38 |  |
| --- | --- |

[0,0]
Part. 1
Part. 2
Confirmation of arming is 1/2-sec external sounder “ding.”
If 1 selected, ding occurs when closing report is sent if open/close
reporting is enabled, or at the end of Exit Delay. If 2 selected, ding
occurs upon reception of the wireless arming command.

**V15P/V15PSIA NOTE:** This option applies only to the Telco reporting
path (not for communication device).


| UL: must be 1 for UL Commercial Burglar Alarm inst. |  |  |  |
| --- | --- | --- | --- |
|  | ∗39 |  | Power Up In Previous State When the system powers up armed, an alarm will occur 1 minute after |


**V20PSIA/V15PSIA:** Feature always
enabled; field does not exist.


| DIALER PROGRAMMING (✱40 – ✱42) Do not fill unused spaces. Enter 0–9; #+11 for '✱'; #+12 for '#'; #+13 for a 2-second pause. If fewer than the maximum digits entered, exit the field by pressing [∗]. The next data field number is displayed. |  |  |  |
| --- | --- | --- | --- |
|  | ∗40 |  | PABX Access Code or Call \| \| \| \| \| |


**Call Waiting:** If the subscriber’s phone service has “call waiting” (and
is not using PABX),  enter “*70” (“# + 11”) plus “# + 13” (pause) as the
PABX entry to disable “call waiting” during control panel calls. If the
subscriber does not have “call waiting” and is not using PABX, make
no entry in this field.
**NOTES:**
1. The call waiting disable feature cannot be used on a PABX line.
2. Using Call Waiting Disable on a non-call waiting line will prevent
successful communication to the central station.

**V20PSIA/V15PSIA:** If call waiting is
used, enter call waiting disable digits
as described above, and also set Call
Waiting Disable option in field *91.


|  | ∗41 |  | Primary Phone No. \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| Secondary Phone No. \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |
|  | ∗42 |  |  |


Enter up to 20 digits. To clear entries, press ✱ 41 ✱ or ✱ 42 ✱ respectively .
Enter the respective phone numbers.


|  | ∗43 |  | Partition 1 Primary Acct. No. \| \| \| / \| \| \| \| \| [FFFFFFFFFF] |
| --- | --- | --- | --- |


| ∗44 |  |
| --- | --- |
| ∗45 |  |

**Part. 1 Secondary Acct. No.**
|   |   |   /    |   |   |   |   | [FFFFFFFFFF]
**Partition 2 Primary Acct. No.**
|    |    |    /    |    |    |    |    | [FFFFFFFFFF]
**Partition 2 Secondary Acct. No.**
Enter 4 or 10 digits, as chosen in *48
Report Format. Enter digits 0–9; #+11
for B; #+12 for C; #+13 for D; #+14 for
E; #+15 for F.
|    |    |    /    |    |    |    |    | [FFFFFFFFFF]
Enter [ ∗ ] as the fourth digit if a 3-digit account number (for 3+1 dialer
reporting format) is used. Enter 0 as the first digit of a 4-digit account
no. for 0000-0999. E.g., For Acct. **B234** , enter: #+11 + 2 + 3 + 4
To clear entries in a given field, press *43*, *44*, *45*, or *46* based
on the field being programmed

| ∗46 |  |
| --- | --- |



|  | ∗47 |  | Phone System Select [1] |
| --- | --- | --- | --- |


Select the type of phone service for the installation.


|  | ∗48 |  | Report F ormat [77] |
| --- | --- | --- | --- |

primary
secondary
Select the format for primary/secondary phone numbers

**–** 7 **–**

---

## Page 8


| ∗49 |  |
| --- | --- |

[0]


| Primary Phone No. 1 = Alarms, Restore, Cancel 2 = All except Open/Close, Test 3 = Alarms, Restore, Cancel 4 = All except Open/Close, Test 5 = All |  |  |  | 2nd Phone No. Others Open/Close, Test All All All |
| --- | --- | --- | --- | --- |
|  | ∗50 |  | Burglary Dialer Delay [2,0] |  |



| 24-hour zone types 6, 7, and 8 (silent panic, audible alarm, auxiliary V20PSIA/V15PSIA: alarm), which are always sent as soon as they occur. Delay Time: UL: Delay Time must be 0 1 = 15 seconds SIA Guidelines: delay must be minimum of 15 seconds 2 = 30 seconds 3 = 45 seconds Delay Disable: 0 = use delay set in entry 1 1 = dial delay disabled for zones listed in zone list 6 (use zone list 6 to enter those zones that require dial delay to be disabled; these zones ignore the setting in entry 1) UL: Dial delay plus entry delay must not exceed one minute; use zone list 6 to disable dial delay from appropriate zones, if necessary. |  |  |  |
| --- | --- | --- | --- |
|  | ∗53 |  | SESCOA/Radionics Select [0 |


Enter 0 for all non-SESCOA formats.

|  | ∗54 |  | Dynamic Signaling Delay [0] |
| --- | --- | --- | --- |


Select delay from 0 to 225 secs, in 15-sec increments.
Intended for reporting via a communication device on the ECP bus
(LRR). This field lets you select the time the panel should wait for
acknowledgment from the first reporting destination (see ∗ 55) before it
attempts to send a message to the second destination. Delays can be
selected from 0 to 225 seconds, in 15-second increments. This delay is
per message. If 0 is entered in this field, the control panel will send
redundant reports to both Primary Dialer and communication device.


|  | ∗55 |  | Dynamic Signaling Priority / [0] |
| --- | --- | --- | --- |


This field selects the primary communication path for reporting (dialer
or communication device) of **primary phone number** events † (see ∗ 49
Split/Dual Reporting) **and** selects the communication path used for
AAV sessions (phone line or communication device path). Use ∗ 29
IP/GSM menu mode to enable the communication device being used.

† Dynamic signaling applies only to the primary phone number. Reports
intended for the secondary phone number are not sent via the
communication device.

**For Dynamic Signaling Priority:** Select the initial reporting destination
for messages as follows:
**Primary Dialer First selected (** ***0*** **)** :
• If acknowledged before delay expires (see ∗ 54), then message will
not be sent via LRR.
• If not acknowledged before delay expires, message is sent to both
the Primary Phone No. and via LRR.
**Communication Device (LRR) First selected (** ***1*** **)** :
• If acknowledged before delay expires, then message will not be sent
to the primary dialer.
• If not acknowledged before delay expires, message is sent to both
the Primary Phone No. and via LRR.

**–** 8 **–**

---

## Page 9


| ∗55 |  |
| --- | --- |

**For AAV Path Select:**
• If using the UVS system or AVS system with non-ECP connection,
option 0 must always be used.
• If using the AVS system with ECP connection, either option (0 or 1)
may be used, but note the following:
**IMPORTANT:** If option “1” is selected, a 2-way voice (AAV) device
compatible with the communication device path must be used (ex.
GSMV4G, GSMX4G communicator). When selected, AAV sessions
**always** occur via the GSM communicator, even if reporting reverts to
phone line backup due to GSM communicator path reporting failure.

∗ **56** **,** ∗ **57** **,** ∗ **58** **Menu Modes**
These are Menu Mode commands, not data fields, for Zone Programming, Function Key Programming, and Expert Mode
Zone Programming respectively. See page 3 and respective sections later in this document.

**TO PROGRAM SYSTEM STATUS, & RESTORE REPORT CODES (** ∗ **59 thru** ∗ **68, *70 thru** ∗ **76, and** ∗ **89):**
**For 3+1 or 4+1 Standard Format:** Enter a code in the *first* box:
1–9, #+10 for 0, #+11 for B, #+12 for C, #+13 for D, #+14 for E, #+15 for F.
A 0 ( *not* #+10) in the *first* box disables a report. A 0 ( *not* #+10) in the *second* box results in advance to the next field.
**For Expanded or 4+2 Format:** Enter codes in *both* boxes (1st and 2nd digits) for 1–9, 0, or B–F, as described above.
A 0 ( *not* #+10) in the *second* box will eliminate the expanded message for that report. A 0 ( *not* #+10) in *both* boxes will disable
the report.
**For Ademco Contact ID® Reporting:** Enter any digit (other than 0) in the *first* box, to enable zone to report (entries in the
*second* boxes are ignored).A 0 ( *not* #+10) in the *first* box disables the report.

UL:  Report codes are required in fields *61, *65, *71, *72,  for UL Commercial Burglar Alarm installations.
Report codes are required in fields *60, *62, *63, *64, *70, *73, *74, *75, *76, for UL Commercial Burglar Alarm installations and required for
Residential Fire Alarm installations

**SYSTEM STATUS REPORT CODES** **(** ✱ **59–** ✱ **68)**

|  | ∗59 |  | Exit Error Alarm Report Code [0] |
| --- | --- | --- | --- |


After arming the system, entry/exit and interior zones remaining open
after exit delay expires cause an alarm sound at the keypad and
external sounder (keypad also displays “EXIT ALARM”), and entry
delay begins. Disarming before the end of the entry delay stops the
alarm sounding and no message is sent to the central station. Keypad
displays “CA” (fixed-word) or “ALARM CANCELED” (alpha display).
If the system is not disarmed before entry delay expires, an “EXIT
ALARM” message ( **V20PSIA/V15PSIA:** also zone alarm message) will
be sent to the central station. The keypad will display “EA” (fixed-word )
or “EXIT ALARM” (alpha display), and alarm sounding continues until
the system is disarmed (or timeout occurs).
**V20PSIA/V15PSIA:**
[1] Always enabled.

An Exit Alarm condition will also result if a fault occurs in an exit or
interior zone within 2 minutes following the end of the exit delay, and an
“EXIT ALARM” message will be sent to the central station (except for
**V20PSIA/V15PSIA** , see field *69 Recent Closing report). With Contact
ID format, the message will contain the zone number and error code
374 (“ALARM–EXIT ERROR”).


|  | ∗60 |  | Trouble Report Code \| [10] See UL System Reporting Note above *59. |
| --- | --- | --- | --- |


Sent if a zone has a trouble condition.

| ∗61 |  |
| --- | --- |


Sent when a zone is manually bypassed.

|  | ∗62 |  | AC Loss Report Code \| [10] See UL System Reporting Note above *59. |
| --- | --- | --- | --- |


Timing of this report is random with up to a 4-hour delay. If AC restores
before the report goes out, there is no “AC LOSS” report.


| ∗63 |  |
| --- | --- |


Sent when the system’s backup battery has a low-battery condition.

|  | ∗64 |  | Test Report Code \| [00] See System Reporting UL Note above *59. |
| --- | --- | --- | --- |


Sent periodically to test the communicator and phone lines.
Frequency of report is set in Scheduling mode (event 11) or by the key
commands listed at left:
Each mode sets schedule 32 (VISTA-20P) or schedule 08 (VISTA-15P)
to the stated repeat option; first test report sent 12 hours after
command. †

**† NOTE:** Make sure the Real-Time Clock is set to the proper time **before**
entering the test report schedule command to ensure that test reports are sent
when expected. (see Setting the Real-Time Clock section)

**–** 9 **–**

---

## Page 10


| ∗65 |  |
| --- | --- |



| Sent upon disarming the system in the selected partitions. See UL |  |  |  |
| --- | --- | --- | --- |
|  | ∗66 |  | Arm Away/Stay Rpt Code [0,0,0,0,0,0] |


Away
Stay
Away Stay
Away Stay
Part. 1
Part. 2
Common
This option allows for independent programming of Away and Stay
reports for each partition, including the common lobby.
**NOTE:** “OPEN” reports are not sent if the associated closing report is
not enabled.


|  | ∗67 |  | RF Trans. Low Bat Report Code \| [00] UL: must be enabled if wireless devices are used |
| --- | --- | --- | --- |


Sent when a transmitter low-battery condition exists.

|  | ∗68 |  | Cancel Report Code \| [00] |
| --- | --- | --- | --- |



| V20PSIA/V15PSIA: [10] Report enabled. |  |  |  |
| --- | --- | --- | --- |
|  | ∗69 |  | Recent Closing Report Code \| [11] |



| See above for entries. | V20PSIA/V15PSIA: Field does not apply to other controls. Similar to the Exit Error condition described in field *59, but occurs if any burglary zone is faulted within two minutes after the initial exit delay expires. Disarming the system within the two minutes stops the alarm sound and displays "ALARM CANCELED " or "CA" and faulted zone number. No message is sent to the Central Monitoring Station. If the system is not disarmed within two minutes, the alarm sound continues and a “recent closing” and a “zone alarm” message are sent to the Central Monitoring Station (after dial delay expires). |
| --- | --- |
| V20PSIA/V15PSIA: Always enabled. |  |
|  |  |


**RESTORE REPORT CODES (** ✱ **70 –** ✱ **76)**

|  | ∗70 |  | Alarm Restore Rpt Code [0] |
| --- | --- | --- | --- |


Alarm restore signals indicate that respective alarm zone(s) are no
longer faulted. Alarm restore reports are sent to the central station at
bell timeout (field *33), if the zone(s) in alarm are actually restored to a
non-faulted state at that time. Otherwise, alarm restore report(s) for
respective alarm zones are sent when the system is disarmed.
See UL System Reporting Note above *59.
If **Reports Per Armed Period Per Zone** (*93) is also programmed, the
system will report alarm and restore codes as described above until the
“Reports Per Armed Period” count is reached. Disarming and rearming
will reset the “Reports Per Armed Period” count.


|  | ∗71 |  | Trouble Restore Rpt Code \| [00] |
| --- | --- | --- | --- |



| See UL System Reporting Note above *59. |  |  |  |
| --- | --- | --- | --- |
|  | ∗72 |  | Bypass Restore Rpt Code \| [00] |



| See UL System Reporting Note above *59. |  |  |  |
| --- | --- | --- | --- |
|  | ∗73 |  | AC Restore Rpt Code \| [00] See UL System Reporting Note above *59. |


Sent after AC power has been restored after an AC power outage.

|  | ∗74 |  | Low Bat Restore Rpt Code \| [00] See UL System Reporting Note above *59. |
| --- | --- | --- | --- |


Sent after a system low-battery condition is restored to normal.

|  | ∗75 |  | RF Trans. Lo Bat Rst Rpt Code \| [00] |
| --- | --- | --- | --- |



| UL: must be enabled if wireless devices are used. See UL System Reporting Note above *59. |  |  |  |
| --- | --- | --- | --- |
|  | ∗76 |  | Test Restore Rpt Code \| [00] See UL System Reporting Note above *59. |


This is sent when the Test mode is exited or upon timeout (4hrs).
**–** 10 **–**

---

## Page 11

**OUTPUT AND SYSTEM SETUP (** ✱ **77 –** ✱ **93)**

|  | ∗77 |  | Daylight Saving Time Start/End \| [3][11] |
| --- | --- | --- | --- |


Enter the start and end month for daylight saving time, if applicable to
the region.


|  | ∗78 |  | Daylight Saving Time Start/End \| [2][1] |
| --- | --- | --- | --- |


Enter the start and end weekend for daylight saving time, if applicable
to the region.


| ∗79, *80, *81, *82 Menu Modes These are Menu Mode commands, not data fields, for Output Device Mapping, Output Programming, Zone List Programming, and Alpha Programming respectively. See page 3 and their respective sections for procedures. |  |  |  |
| --- | --- | --- | --- |
|  | ∗84 |  | Auto Stay Arm [3] |


If enabled, the system will automatically change AWAY mode to STAY
mode if the entry/exit door **is not** opened and closed within the exit
delay time after a user arms in AWAY mode from a wired keypad (non-
RF device). An Opening report followed by an Armed Stay report is
sent to the Central Station.
If the door **is** opened and closed within the exit delay period, the
system remains in AWAY mode.
Any RF device that arms the system AWAY overrides this feature and
the system remains armed AWAY.


|  | ∗85 |  | Cross Zone Timer [0] This option not for use in UL installations. |
| --- | --- | --- | --- |


Sets the maximum amount of time in which two cross zones must be
tripped in an armed system to send an alarm message to the Central
Station. If only one cross zone is tripped during this time, a trouble
message (CID code 380) for that zone is sent to the Central Station.

Assign cross zones on zone list 4, using *81 Menu mode.
**NOTE:** Cross zoning takes effect only after Exit Delay expires.


|  | ∗86 |  | Cancel Verify Keypad Display [1] |
| --- | --- | --- | --- |



|  | ∗87 |  | Misc. Fault Delay Time [0] |
| --- | --- | --- | --- |


(used with Configurable Zone Types “digit 6”)
Used with zones assigned to a configurable zone type with fault delay
on (configurable zone type digit “6”), and sets a zone response time of
15 seconds to 15 min. It can be assigned to zones with sensors that
provide a trouble indication when an oil tank is low, or similar
applications for critical condition monitoring where a non-alarm
response is desired.


|  | ∗88 |  | Program Mode Lockout Options [0] This table summarizes the Program Mode Lockout options: |
| --- | --- | --- | --- |



| Exit Command | *88 Entry | Reentry By: Installer Power-up† Downloader |  |  |
| --- | --- | --- | --- | --- |
| *99 | n/a | yes | yes | yes |
| *98 | 0 | no | yes | yes |
| *98 | 1 | yes | no | yes |
| *98 | 2 | no | no | yes |


**–** 11 **–**

---

## Page 12


| ∗89 |  |
| --- | --- |

| [00]
If an Event Logging selection is made in field ∗ 90, a message can be
sent to the central station receiver when the log is 80% full. If the log
becomes full, new messages overwrite the oldest messages in the log.


|  | ∗90 |  | Event Log Enables [3] |
| --- | --- | --- | --- |


This system can record various events in a history log (VISTA-20P =
100 events; VISTA-15P = 50 events). At any time, the downloader
operator can then upload the log and view or print out all or selected
categories of the log, or can clear the log. Event log can also be viewed
at an alpha keypad. The display/printout at the central station will show
the date, time, event, and description of the occurrences.
Data Entry Example: To select Alarm/Alarm Restore” and
“Open/Close”, enter 9 (1+ 8); to select all events, enter #15.
**NOTE** ***:*** System messages are logged when any non-zero entry is made.


|  | ∗91 |  | Option Selection / Remote [8, 0] |
| --- | --- | --- | --- |


Options
RIS Enable
**V20PSIA/V15PSIA: Call Waiting Disable / RIS Enable**
**IMPORTANT:** AAV should not be used when Paging or Alarm Reports
are sent to a secondary number unless the monitoring zone option is
used (which pauses calls). Otherwise, the call to the secondary number
by the communicator after the alarm report will prevent the AAV from
taking control of the telephone line, and the AAV “Listen in” session
cannot take place.

**Entry 2:** **Remote Interactive Services**
**(RIS) enable**
0 =  RIS disabled
1 = not applicable
2 =  RIS enabled
UL: for AAV, must use Honeywell AVS system; Exit Delay
Restart/Reset must be disabled

SIA Guidelines: Exit Delay Restart/Reset should be enabled.
† “Exit Delay Restart/Reset” option allows use of the [ ∗ ] key to restart
the exit delay at any time when the system is armed STAY or
INSTANT. This feature also enables automatic exit delay reset, which
resets exit delay if the entry/exit door is re-opened and closed before
exit delay time expires after arming AWAY. Automatic Exit Delay Reset
occurs only once during an armed AWAY period.
**Remote Interactive Services (RIS) Enable:** This option enables
enhanced Remote Interactive Services (RIS) such as Total Connect
2.0, Tuxedo/Z-Wave scenes and Home Automation (Control 4,
4232CBM), if supported by the communication service in use. If
enabled, device address 25 is automatically assigned.
**To Enable Remote Services:**
1. Enable the RIS option in this programming field (entry 2).
2. Use field ∗ 189 to enable a remote services emulated keypad
address.
3. Use ∗ 29 Menu mode to enable the communication device.
4. If using Total Connect 2.0, use AlarmNet Direct website to program
the communicator and enable TC2 services. Be sure to “send” the
programming data down to the Communicator.

**V20PSIA/V15PSIA:**
**Entry 1 Options:** Same as above.
**Entry 2 Call Waiting Disable / RIS**
**Enable:**
0 = call waiting not used
1 =  use call waiting disable digits

( ∗ 70) entered in field ∗ 40; (when
selected, the system dials the
entry in ∗ 40 only on alternate dial
attempts; this allows proper
dialing in case call waiting
service is later canceled by the
user).
2 =  RIS (Remote Interactive

Services) enabled
3 =  Call Waiting disable and RIS
enabled


|  | ∗92 |  | Phone Line Monitor Enable [0,0] |
| --- | --- | --- | --- |

1
2
**Entry 1:** Sets the length of time a phone line fault must remain after
detected before the second digit option is activated.

**Entry 2:** Selects the desired phone line fault response.
Option 2 may be used even if a relay unit or Powerline carrier device is
not connected to the control.
Programmed Output Device must either be programmed to be
STOPPED in field ∗ 80 or STOPPED by entry of [security code] + [#] + 8
+ device number. Partition in ∗ 80 should be set to “0,” for STOP.
UL: Field *92 must be enabled for fire alarm installations, UL commercial
burglar alarm installations and UL residential burglar alarm installations.
**Entry 2** :
0 = Keypad display when line is faulted
1 = Keypad display plus keypad trouble
sound. Each partition turns off its
own trouble sound. No automatic
timeout.
2 = Same as “1”, plus programmed
output device STARTS. If either
partition is armed, external sounder
activates also. External sounder
will be turned off by normal bell
timeout, or by security code plus
OFF from either partition (it need
not be the one that was armed).

If the control unit is used on a UL commercial burglar alarm system which
requires 2 methods of remote communication, then the control unit’s DACT
and the other method of signal transmission must monitor each other against
communication failure and line fault. The fault must be received and
annunciated within 200 seconds of its occurrence.

**–** 12 **–**

---

## Page 13


| ∗93 |  |
| --- | --- |

[1,0]
Restrict
**V20PSIA/V15PSIA**
Report Pairs Unlimited Reports Enable
Selection limits the number of alarm/alarm restore message pairs per
zone sent to the CS in an armed period. Swinger suppression applies
to burglary zones only.
SIA Guidelines: Must be set for option 1 or 2


|  | V20PSIA/V15PSIA: Restrict Report Pairs: 1 = 1 report pair; 2 = 2 report pairs Unlimited Reports Enable: 0 = restrict reports to the setting in entry 1 1 = unlimited reports for zones listed in zone list 7; (use zone list 7 to enter those zones that require unlimited reporting; these zones ignore the setting in entry 1) |  |
| --- | --- | --- |
|  |  |  |


**DOWNLOAD INFORMATION (** ✱ **94,** ✱ **95)**

| ∗94 |  |
| --- | --- |

|     |    |    |     |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
Enter the phone number of the downloading computer.
UL: downloading may be performed only if a technician is at the site.
Up/downloading via the Internet has not been evaluated by UL.


|  | ∗95 |  | Ring Count For Downloading [15] |
| --- | --- | --- | --- |



| phone module | answer machine | down- loading | Set field ∗95 to… |
| --- | --- | --- | --- |
| yes | no | no | 1-14 (not 0) |
| yes | yes | no | greater than rings set on answer machine (e.g., if ans. machine is 4 rings, set this field to 5). This allows access to the phone module if the answer machine is off. |
| yes | no | yes | 1-14 (not 0) |
| yes | yes | yes | 15 (bypasses answer machine†) |
| no | no | no | 0 |
| no | yes | no | 0 |
| no | no | yes | 1-14 |
| no | yes | yes | 15 |


**† NOTE:** If “15” is entered to bypass an answering machine, and a 4286
Phone Module is included in the system, you should note the following:
When calling in from an off-premises phone, the user should make the initial
call, allow 1 or 2 rings only, then hang up, then call again. The phone module
will now seize the line, and 2 long tones sound, followed by the usual voice
prompt for the access code. If this procedure is not followed, phone module
operation will not be possible.


| ∗96 | , , | ∗97 |
| --- | --- | --- |
| ∗98 |  | ∗99 |


**PAGER OPTIONS (** ✱ **160-** ✱ **172)**
The system can send various reports to several pagers (VISTA-20P = up to 4; VISTA-15P = up to 2).
To program pager reporting, do the following:
1. Enter the pager phone number(s), preface characters, and pager report options in data fields *160 - *171.
2. Enable Pager Delay, if desired, in field *172 (delays alarm reporting for ALL pagers).
3. Make sure appropriate user open/close pager reports are enabled (see Security Codes section in User Guide). Users that
perform actions in partition 1 will, if enabled, attempt to report to all pagers enabled for open/close reporting in partition 1.
Users that perform actions in partition 2 will, if enabled, attempt to report to all pagers enabled for open/close reporting in
partition 2.
4. If using latchkey pager report, define the latchkey report schedule using Scheduling mode (master code + [#] [6] [4] then
select event type *03* ). System must be armed for the Latchkey report to be sent.
5. If using a function key to manually send a message to a pager, use *57 Function Key Menu mode to define the key
(function *01* ).
6. If reporting zone alarms and troubles to a pager, use *81 Zone List menu mode to assign the zones associated with each
pager (zone lists 9-12 † ).

†   VISTA-15P supports zone lists 9 and 10 only.

**–** 13 **–**

---

## Page 14


| ∗160 |  |
| --- | --- |

|     |    |    |     |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
If entering fewer than 20 digits, exit by pressing [ ∗ ] + next field number.
To clear entries, press ∗ 160 ∗ .


|  | ∗161 |  | Pager 1 Characters \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |


Up to 16 optional characters may be sent as a prefix to the 7-digit
system status code sent to Pager #1 (if used). Phone number in field
*160 must have been entered. If fewer than 16 characters, exit by
pressing [ ∗ ] and next field number. To clear entries: press ∗ 161 ∗ .
The 16 characters may be composed of the following:
PIN number, Subscriber account number,
∗ character, # character, 2-second pause, †
special character(s) the user may decide to transmit
† Some paging systems require pause(s) before the prefix.
The Pager format for the 7-digit status code is defined as follows: XXX-
YYYY   where:
XXX
= 3-digit event code: 911 = Alarm, 811 = Trouble, 101 =
Opening (disarm), 102 = Closing (arm AWAY)
YYYY
= 4-digit user or zone number (depending on type of event).
The first digit indicates partition (0 = system, 1 = part 1, 2 =
part 2, 3 = common), followed by the 3-digit user or zone
number.


|  | ∗162 |  | Pager 1 Report Options [0,0,0] |
| --- | --- | --- | --- |

P1         P2      comm
For each partition, select from the listed options.
† For users enabled for paging. Reports to pager only when arming
(close)/disarming (open) from a keypad using a security code; auto-
arming/disarming, arming with assigned button, and keyswitch arming
do not send pager messages.


|  | ∗163 |  | Pager 2 Phone No. \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |


If entering fewer than 20 digits, exit by pressing [ ∗ ] + next field number.
To clear entries, press ∗ 163 ∗ .


|  | ∗164 |  | Pager 2 Characters \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |


If fewer than 16 characters, exit by pressing [ ∗ ] and next field number.
To clear entries, press ∗ 164 ∗ .


|  | ∗165 |  | Pager 2 Report Options [0,0,0] |
| --- | --- | --- | --- |


P1         P2      comm
Select for each partition (use zone list 10 for options 12 or 13)


|  | ∗166 |  | Pager 3 Phone No. \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |



|  | ∗167 |  | Pager 3 Characters \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |



|  | ∗168 |  | Pager 3 Report Options [0,0,0] |
| --- | --- | --- | --- |



|  | ∗169 |  | Pager 4 Phone No. \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |



|  | ∗170 |  | Pager 4 Characters \| \| \| \| \| \| \| \| \| \| \| \| \| \| \| |
| --- | --- | --- | --- |



|  | ∗171 |  | Pager 4 Report Options [0,0,0] |
| --- | --- | --- | --- |


**–** 14 **–**

---

## Page 15


| ∗172 |  |
| --- | --- |

[3]
This field determines the delay of alarm reports to the pager. This gives
the Central Station enough time to verify the alarm report it received
before the dialer attempts to dial the pager.
This delay is for ALL pagers in the system.

**MISCELLANEOUS SYSTEM FIELDS (*174-*181)**

| ∗174 |  |
| --- | --- |

[0]
For ESL smoke detectors
This is a maintenance feature for ESL 2-wire smoke detectors on Zone
1. If used, this option limits the number of smoke detectors to a
maximum of 10, rather than 16. To enable the “clean me” feature, a
time response setting of “3” (1.2 seconds) must be entered in ∗ 56 Zone
Programming for zone 1.
**NOTE:** If Clean Me is enabled, you must enter “3” in field ∗ 56
programming for zone 1 response time.


|  | ∗177 |  | Device Duration 1, 2 [0] [0] |
| --- | --- | --- | --- |


1
2
(used in *80 Menu mode-Device Actions 5/6)
These entries set the duration for output action options 5 (duration 1)
and 6 (duration 2) programmed in ∗ 80 Output Function Programming.


|  | ∗181 |  | 50/60 Hertz AC Operation [0] |
| --- | --- | --- | --- |


Select the type of AC power applied to the control (option is used for
Real-Time Clock synchronization)
**CONFIGURABLE ZONE TYPE OPTIONS (*182-*185)**
(see Configurable Zone Type Worksheet following data field ∗ 199)
• The system allows you to define custom zone types (VISTA-20P supports 4 [types 90-93]; VISTA-15P supports 2 [types 90,
91]) based on the options selected.
• All configurable zone types can be programmed via the downloader. Zone types 90-91 can also be programmed from a
keypad using data fields *182-*185.
• **IMPORTANT:** Be careful when selecting combinations of options for configurable zone types. Contradictory options can
cause unpredictable results.
**Configurable Zone Type Options**
**Auto Restore** (entry 2): Faults on zones set for this option are cleared; restore messages sent upon restoral of faults.
**Vent Zone** (entry 2): Zones set for this option are ignored if faulted when arming the system, but are protected if the zone is later restored
(e.g., an open window can be ignored when arming, but if the window is later closed, it will be protected; opening the window again causes an
alarm.)
**Bypass Disarmed** (entry 4): Zones set for this option can be bypassed only while the system is disarmed.
**Bypass Armed** (entry 4): Zones set for this option can be bypassed when the system is armed.
**Dial Delay** (entry 6): Alarms on zones set for this option participate in dial delay central station reporting, if system dial delay enabled in field
*50.
**Fault Delay** (entry 6): Faults on zones set for this option are delayed by the time set in field *87. Do not use this option if using entry/exit
delay for this zone type.
**Faults Display** (entry 7): Selects how faults on zones set for this zone type are displayed.
**Power Reset/Verification** (entry 7): Selects whether the system resets power (when user enters code + OFF), and whether the system
performs alarm verification (see description for zone type 16 in **Zone Type Definitions** section) when a fault occurs on these zones.
**Use Entry Delay** (entry 8): Selects whether to use the system’s entry delay times.
**Use Exit Delay** (entry 8): Selects whether to use the system’s exit delay time.
**Interior Type** (entry 8): Zones set for this option are treated same as standard zone type 4 (bypasses when armed STAY, faults displayed).
**Alarm Sounds** (entry 9): Selects the type of alarms sound for zones set for this zone type.
**Bell Timeout** (entry 9): Alarm sounding on zones set for this option remain for the duration set in fields *32 / *33.
**Fire Zone** (entry 9): Zones set for this option respond in the same manner as if programmed for zone type 9. Do not set fire zones to respond
as a “fault” in entries 1-6.
**Trouble Sounds** (entry 10): Selects the type of trouble sounds for zones set for this zone type (periodic beeps = once every 30 seconds;
trouble beeps = rapid beeping).
**Chime Enable** (entry 10): Zones set for this option cause a chime when Chime mode is on.

**–** 15 **–**

---

## Page 16


| ∗182 |  |
| --- | --- |

1
2
3
4
5
6
7
8
9
10
Enter the appropriate value for each entry, 1-10, based on the charts
provided in the Configurable Zone Type Worksheet section. Each entry
is the sum of the values of its selected options
To calculate the value for each entry, add the values of the selected
options in each of the entry’s columns shown in the respective chart
(one option per column). For example, to program entry 2 for “alarm
response to short,” “auto restore on,” but not a “vent zone,” enter 5 (“1”
for alarm short + “4” for auto restore-yes + “0” for vent zone-no).
UL: Do not configure zones as a fire alarm or UL burglar alarm zone.


| ∗183 |  |
| --- | --- |

Enter the desired 3-digit Contact ID® report codes for alarms and
troubles occurring on zones assigned to this zone type. Enter the
codes sequentially (all 6 digits). When entering digits, [#] moves cursor
back, [ ∗ ] moves forward.
**Important Notice on Report Codes:** To avoid confusion at the central
station, it is recommended that existing Contact ID® codes be used
with configurable zone types whenever possible. Check with the central
station for a complete list of Contact ID® report codes. If none of the
codes are suitable, choose a code in the reserved range of 750-789
and make sure to define the code with your central station.


|  | ∗184 |  | Configurable Zone Type 91 |
| --- | --- | --- | --- |


1
2
3
4
5
6
7
8
9
10
See ∗ 182 for entries.

UL: Do not configure zones as a fire alarm or UL burglar alarm zone.

| ∗185 |  |
| --- | --- |

See ∗ 183 for entries.


|  | ∗189 |  | AUI Device Enables [1, 1, 0, 0] |
| --- | --- | --- | --- |


AUI 1
AUI 2 AUI 3    AUI 4
System supports touchscreen style keypads (e.g., 6280, Tuxedo
Touch; V20P = up to 4; V15P = up to 2).
**NOTE:** Use of touchscreen style keypads does not affect the number of
standard keypads supported.

To enable a touchscreen keypad, enter the option corresponding to
each touchscreen’s home partition.
**Note for Remote Services Devices:** If using the Remote Services
feature of the communication device, select an option 5-7, depending
on the partition the Remote Services device is associated with (these
options automatically disable auto-stay arming when the system is
armed from the respective Remote Services device). Refer to the
communication device’s installation instructions for details on enabling
the Remote Services feature.
**Note for Remote Services Device Address:** Using an AUI device
address for Remote Services provides enhanced remote services
features, but an actual AUI device cannot use the same address. If no
AUI addresses are available (all four AUIs are being used), Total
Connect 2 cannot be used for remote services. However, Total
Connect 1 can be used by choosing an available standard keypad
address and using the appropriate keypad address field *190 - *196 to
select the Remote Services operating partition (some remote access
features will be unavailable).
For Remote Services device usage
5 = part. 1 (auto-stay arm disabled)
6 = part. 2 (auto-stay arm disabled)
7 = part. 3 (common; auto-stay arm
disabled)

**VISTA-15P:**
For Touchscreen device usage
0 = disable
1 = enable

For Remote Services device usage
5 = part. 1 (auto-stay arm disabled)
**Device Addresses:**
Touchscreen device 1: Must set to 1
Touchscreen device 2: Must set to 2
Touchscreen device 3: Must set to 5
Touchscreen device 4: Must set to 6

**KEYPAD OPTIONS *190-*196**
**To enable keypads:**
1. Set desired address at keypad (refer to keypad’s instructions for setting the address).
2. Use data fields *190-*196 to enable keypad addresses, assign a partition, and enable sound options.
3. Use fields *197, *198, and *199 to turn on partition number display, exit time interval display, and select fail display mode.
4. Set keypad-related data fields as appropriate: *21 Quick Arm Enable, *23  Forced Bypass, *84  Auto STAY Arm

N **OTES** : 1. Options for keypad 1, address 16, are set by the factory and cannot be changed.
2. Each keypad must be assigned a unique address. Keypads programmed with the same address will give
unpredictable results.

**–** 16 **–**

---

## Page 17


|  | ∗190 |  | Keypad 2 Device Address 17 [0] [0] |
| --- | --- | --- | --- |


Partition/
Sound
Enable
**Entry 1 - Partition/Enable:** Enter the desired option for the keypad’s
home partition.

**Note for Remote Services Devices:** If using the Remote Services
feature of the communication device, select an option 5-7 (option 5 for
VISTA-15P), depending on the partition the Remote Services device is
associated with (these options automatically disable auto-stay arming
when the system is armed from the respective Remote Services
device). Refer to the communication device’s installation instructions
for details on enabling the Remote Services feature.
**Entry 2 - Sound:** Enter the desired sound option for this keypad.

For Remote Services device usage
5 = auto-stay arm disabled
**Entry 2: Sound**
0 = no suppression
1 = suppress arm/disarm and Entry/Exit
beeps
2 = suppress chime beeps only
3 = suppress arm/disarm, Entry/Exit,
and chime beeps


|  | ∗191 |  | Keypad 3 Device Address 18 [0] [0] |
| --- | --- | --- | --- |


Part./ Enable
Sound

|  | ∗192 |  | Keypad 4 Device Address 19 [0] [0] |
| --- | --- | --- | --- |


Part./ Enable
Sound

|  | ∗193 |  | Keypad 5 Device Address 20 [0] [0] |
| --- | --- | --- | --- |


Part./ Enable
Sound

|  | ∗194 |  | Keypad 6 Device Address 21 [0] [0] |
| --- | --- | --- | --- |


Part./ Enable
Sound

|  | ∗195 |  | Keypad 7 Device Address 22 [0] [0] |
| --- | --- | --- | --- |


Part./ Enable
Sound

|  | ∗196 |  | Keypad 8 Device Address 23 [0] [0] |
| --- | --- | --- | --- |


Part./ Enable
Sound

| ∗197 |  |
| --- | --- |

[0]
If enabled, keypads display the exit time remaining after arming the
system, updated at the interval selected (i.e. if the exit delay is 30
seconds and “2” is selected in this field, the keypad display refreshes
every 2 seconds, displaying 30, 28, 26, 24, etc.).
An interval greater than “1” may be necessary for some older keypads
to allow users time to enter key presses between display updates.
**NOTE:** If enabled and using only 2-digit fixed-word keypads (e.g.,
6150RF), do not set exit delay time greater than 96 seconds. Using a
longer delay time may cause end-user confusion because 2-digit
display keypads cannot display times greater than “99.” If longer exit
time is required by the installation, it is recommended that the Exit
Time Display option be disabled (“0”).


|  | ∗198 |  | Display Partition Number [0] (VISTA-20P; for Alpha Display Keypads) |
| --- | --- | --- | --- |



|  | ∗199 |  | ECP Fail Display [0] |
| --- | --- | --- | --- |


Select “0” if using Alpha keypads and/or 3-digit Fixed-Word Display
keypads. ECP faults will display “1” plus the device address (00-15) of
device causing the fault (e.g., faults on device 07 display as “107”).
Select “1” if using 2-digit Fixed-Word Display keypads (e.g., certain
6128 series keypads). If selected, ECP faults for all devices will display
as “91” on 2-digit displays, and “191” on 3-digit or Alpha keypads.

**–** 17 **–**

---

## Page 18

**CONFIGURABLE ZONE TYPES WORKSHEET**


|  |  |  |
| --- | --- | --- |
| Entries for Fields *182 and *184 |  |  |
| Entry | Zone Type 90 (field *182) | Zone Type 91 (field *184) |
| 1 |  |  |
| 2 |  |  |
| 3 |  |  |
| 4 |  |  |
| 5 |  |  |
| 6 |  |  |
| 7 |  |  |
| 8 |  |  |
| 9 |  |  |
| 10 |  |  |
| To calculate the value for each entry: Simply add the values of the selected options in each of the entry’s columns (one option per column). For example, to program Entry 2 for “alarm response to short,” “auto restore on,” but not a “vent zone,” enter 5 (“1” for alarm short + “4” for auto restore yes + “0” for vent zone no). |  |  |
| INTACT OPEN SHORTED EOL ZONE-003-V0 Zone Conditions Represented in Entries 1-6 NOTES: 1. Do not use the “fault delay” option with a configurable zone type if it is set for an entry or exit delay, otherwise unpredictable results may occur. 2. To create an interior type zone, select “respond as interior zone type” (entry 8, interior type = yes), and set zone response to “fault” in entries 3-4 to ensure fault displays; do not set as “normal,” “alarm,” or “trouble.” 3. Do not set fire zones to respond as a “fault” (entries 1-6), otherwise faults will not display unless the [∗] key is pressed. 4. 4219/4229 modules must use EOLRs or unpredictable results may occur. 5. RF Zones: The “open” option in entries 1, 3, and 5 is not applicable for RF zones. Use the “intact EOL” option for normal RF zone conditions and “shorted” for off- normal RF zone conditions. 6. a. Zone-Doubling/Double-Balanced: A short on either zone of a zone-doubled pair or on a double-balanced zone causes a tamper condition. b. For double-balanced zones, this entry must be “0.” c. For zone-doubled zones, both zones of the doubled pair must be assigned |  |  |


| ENTRY 1 (See note 5 for RF zones) |  | ENTRY 2 (See note 5 for RF zones) |  |  |
| --- | --- | --- | --- | --- |
| Response when system disarmed and zone is: |  |  | Auto | Vent Zone |
| Intact EOL | Open | Shorted | Restore |  |
| RF zone normal | RF zone N/A | RF zn off-normal |  |  |
| 0 = normal 1 = alarm 2 = trouble 3 = fault | 0 = normal | 0 = normal 1 = alarm 2 = trouble 3 = fault see note 6 | 0 = no 4 = yes | 0 = no 8 = yes |
|  | 4 = alarm |  |  |  |
|  | 8 = trouble |  |  |  |
|  | 12 = fault |  |  |  |
|  |  |  |  |  |
| Entry 1 = EOL + Open |  | Entry 2 = Short + auto restore + vent zone |  |  |



| ENTRY 3 (See note 5 for RF zones) |  | ENTRY 4 (See note 5 for RF zones) |  |  |
| --- | --- | --- | --- | --- |
| Response when armed STAY and zone is: |  |  | Byp. when | Byp. when armed |
| Intact EOL | Open | Shorted | disarmed |  |
| RF zone normal | RF zone N/A | RF zn off-normal |  |  |
| 0 = normal 1 = alarm 2 = trouble 3 = fault | 0 = normal 4 = alarm 8 = trouble 12 = fault | 0 = normal 1 = alarm 2 = trouble 3 = fault see note 6 | 0 = no 4 = yes | 0 = no 8 = yes |
| Entry 3 = EOL + Open |  | Entry 4 = Short + byp. disarmed + byp. armed |  |  |



| ENTRY 5 (See note 5 for RF zones) |  | ENTRY 6 (See note 5 for RF zones) |  |  |
| --- | --- | --- | --- | --- |
| Response when armed AWAY and zone is: |  |  | Dial Delay | Fault Delay (see field *87) |
| Intact EOL | Open | Shorted | (see field *50) |  |
| RF zone normal | RF zone N/A | RF zn off-normal |  |  |
| 0 = normal 1 = alarm 2 = trouble 3 = fault | 0 = normal 4 = alarm 8 = trouble 12 = fault | 0 = normal 1 = alarm 2 = trouble 3 = fault see note 6 | 0 = no 4 = use delay | 0 = no 8 = use delay see note 1 |
| Entry 5 = EOL + Open |  | Entry 6 = Short + dial delay + fault delay |  |  |



| ENTRY 7 |  | ENTRY 8 |  |  |
| --- | --- | --- | --- | --- |
| Display Faults | Power Reset/ | Use Entry Delay 1/2 | Use Exit | Respond as |
|  | Verification |  | Delay | Interior Type |
| 0 = show alarms when armed & disarmed 1 = don’t show alarms when armed (show alarms, trbles, faults when disarmed) 3 = never show any alarms, trbles, faults | 0 = no 4 = power reset after fault (by code + OFF) 12 = verification (see zone type 16) | 0 = no 1 = delay 1 2 = delay 2 | 0 = no 4 = use exit delay | 0 = no 8 = yes see note 2 |
| Entry 7 = fault display + power reset/verification |  | Entry 8 = entry delay 1/entry delay 2 + exit delay + interior zone type |  |  |



| ENTRY 9 |  |  | ENTRY 10 |  |
| --- | --- | --- | --- | --- |
| Alarm Sounds | Use Bell | Respond as | Trouble | Chime when |
|  | Timeout | Fire Zone | Sounds | Chime Mode On |
| 0 = none 1 = steady keypad 2 = steady bell and keypad 3 = pulsing bell and keypad | 0 = no 4 = yes see fields *32, *33 | 0 = no 8 = yes see zone type 09; see note 4 | 0 = none 1 = periodic beep 2 = trouble beeps | 0 = no 4 = yes |
| Entry 9 = alarm sounds + bell timeout + fire zone |  |  | Entry 10 = trouble sounds + chime |  |


**–** 18 **–**

---

## Page 19

∗ **56 ZONE PROGRAMMING MENU MODE**
**(press *56 while in Program mode)** The Zone Programming Worksheet is on page 44.
**Zones and Partitions**
Each protection zone needs to be programmed with various attributes using *56 Zone Programming mode or ✱ 58 Expert
Programming Mode. Using this mode, enter the zone number to be programmed and make appropriate entries at the
prompts. Finally, Confirm the serial number of wireless transmitter zones.
The VISTA-20P system can control two independent areas of protection (known as partitions) for use by independent users, if
desired, by simply assigning zones to one or the other partition during zone programming. The VISTA-20P, by default,
automatically distributes users between the two partitions. The master user can change the user number distributions.
Zones can also be assigned to a common partition, which is an area shared by users of both partitions (such as a lobby in a
building). This allows either partition to arm, while leaving the common partition disarmed for access into the other partition.
The following describes the functioning of the VISTA-20P common partition:
• The common zone sounds and reports alarms only when both partitions are armed. If only one partition is armed, the
system ignores faults on the common zone.
• Either partition may arm its system if the common zone is faulted, but once armed, the other partition will not be able to arm
unless the common zone is first bypassed or the fault is corrected.
• Faults on the common zone are displayed on common zone keypads, and will also appear on another partition’s keypad
when that partition is armed.
• Either partition can clear and restore the common zone after an alarm.

∗ **56 Menu Mode**

| PROMPT |  | VALID ENTRIES |  |  | EXPLANATION |  |
| --- | --- | --- | --- | --- | --- | --- |

This display appears upon entry into this mode.
The default is 0 (No).
If 1 (Yes) is entered, you will be prompted to confirm each
transmitter after entering the serial and loop numbers (at the
“XMIT TO CONFIRM” prompt later).
**Confirm?**
0 = no
1 = yes
[ ∗ ] to continue
SET TO CONFIRM?
0 = NO   1 = YES   0

Enter Zn Num.
(00 = Quit)  10
Enter the zone number that you wish to program. Zone 10 has
been entered in the example display at left.
Enter a report code for zone 91 to enable addressable device
reporting.
Enter a report code for zone 92 to enable duress reporting.
95, 96, 99 are emergency (panic) key zones.
† if zone expanders are used.
**Zone Number**
VISTA-20P:
wired  01-08 (and 09-48 † );
wireless  09-48; RF button
zones 49-64
VISTA-15P:
wired 01-06 (and 09-24 † );
wireless 09-34; RF button
zones 49-56
Both Controls:
91 = addr. device report enable
92 = duress report enable
95, 96, 99 =emerg. zones
[ ∗ ] to continue
00 to quit

“IN: L” appears for wireless zones and indicates input type and
loop.
“IN: AD” appears for hardwire expansion zones (AW) and
indicates the module’s address (AD), which is based on the
zone number.
“HW: RT” appears for hardwire zones and indicates
configuration (EOL, NO, NC, zone doubling, double-balanced)
and response time selection.
**Summary Screen**
[ ∗ ] to continue
Zn  ZT  P RC    In:   L
10  00  1 10    RF:   1

10 Zone Type
Perimeter
03
Each zone must be assigned to a zone type, which defines the
way in which the system responds to faults in that zone. Enter the
Zone Type code from the list below:
**Note:** If 00 is entered, **Delete Zone ?** will be displayed.
00 = Not used
07 = 24-Hr Audible
20 = Arm–STAY*
01 = Entry/exit #1
08 = 24-Hr Aux
21 = Arm–AWAY*
02 = Entry/exit #2
09 = Fire
22 = Disarm*
03 = Perimeter
10 = Interior w/Delay
23 = No Alarm Resp
04 = Interior Follower
12 = Monitor Zone
24 = Silent Burglary
05 = Day/Night
14 = Carbon Monoxide
77 = Keyswitch
06 = 24-Hr Silent
16 = Fire w/Verify
81 = AAV Mon. Zone
*5800 button-type transmitters only
**Zone Type (ZT)**
See table at right.

Enter the Partition number for this zone. Partition 1 is shown
entered.
**Partition No. (P)**
(VISTA-20P)
1-3 = partition
(3 = common)
[ ∗ ] to continue
10 Partition
1

**–** 19 **–**

---

## Page 20

Enter the report code for this zone, which consists of 2
hexadecimal digits, each in turn consisting of 2 numerical digits.
For example, for a report code of “10,” enter *01* and *00* .
For Contact ID®, entering any non-zero entry as the first digit
enables the report code for this zone.
**Report Code (RC)**
First Digit: 1-9, 10 for 0, 11 for
B, 12 for C, 13 for D, 14 for E,
15 for F
00 to disable
Second Digit: same as above
[ ∗ ] to continue
10 Report Code
1st 01   2nd 00   10

This prompt appears only for zone numbers 02-08.
Zone 1 is automatically set for EOL operation.
† VISTA-20P
**Hardwire Type**
0 = EOL
1 = NC
2 = NO
3 = zone doubling (ZD) †;
4 = double-balanced (DB) †
[ ∗ ] to continue
02 HARDWIRE TYPE
EOL
0

Appears only for hardwire zones 01-08 (zone 02 is the display
shown).
Option 3: used for “clean me” option on zone 1 (see field ∗ 174).
**NOTE:** If zone doubling is being used, the response time
selected for zones 02-08 automatically applies to each zone’s
associated doubled zone.
**Response Time (RT)**
0 = 10mSec;
1 = 350mSec
2 = 700mSec
3 = 1.2 seconds
[ ∗ ] to continue
02 Response Time
1

**Input Device type (In)**
2 = AW (Aux wired zone)
3 = RF (supervised RF
transmitter
4 = UR (unsupervised RF
transmitter)
5 = Button type RF
transmitter
(unsupervised).
[ ∗ ] to continue
10 INPUT TYPE
RF TRANS
3


| Type | Description |
| --- | --- |
| RF (Supervised RF) | Sends periodic check-in signals, as well as fault, restore, and low-battery signals. The trans. must stay within receiver's range. |
| UR (Unsupervised RF) | Sends all the signals that the “RF” type does, but the control does not supervise the check-in signals. The transmitter may therefore be carried off-premises. |
| BR (Unsupervised Button RF) | Sends only fault signals. It will not send a low-battery signal until it is activated. The transmitter may be carried off-premises. |


**NOTE:**
• For the built-in hardwired zones, the Input Device type is
automatically displayed as HW and cannot be edited.
• To change the input type of a previously programmed wireless
device (type RF, UR, BR) to a wired zone (type AW), you must
first delete transmitter’s serial number (see To Delete A Serial
Number prompt)

**Input Serial number and**
**Loop Number**
[ ∗ ] to continue
Used only when enrolling
wireless transmitters.
Enroll the transmitter’s serial number and loop number as
follows:
1. a. Transmit two open/close sequences (for button-type trans,
press and release the button twice, waiting about 4 secs
before pressing the button the second time).
OR
b. Manually enter the 7-digit serial number printed on the label
of the transmitter. Press the [ ∗ ] key to move to the “L”
position, then enter the loop number.
Use the [A] (Advance) and [B] (Back) keys to move the
cursor forward and back within the screen. Pressing the [C]
(Copy) key will insert the previously enrolled serial number,
if desired (used when programming a transmitter with
several input loops).
To delete an existing serial number, enter 0 in the loop
number field. The serial number will change to 0's. If 0
was entered in error, simply re-enter the loop number or
press [#], and the serial number will return to the display.
2. Press [ ∗ ] to continue. The system now checks for a duplicate
serial/loop number.
If no duplicate is found, the display shows the serial number
and loop number.
3. Press [ ∗ ] to continue to confirmation screen.
10  INPUT S/N:       L
A022-4064      1

**–** 20 **–**

---

## Page 21

**NOTE:** If the [C] key is used to copy the previously enrolled
serial number, the cursor will move to the Loop column (L) with
the previous serial number displayed, and display a highlighted
question mark for the loop number.
**Loop Number Change**
[ ∗ ] to continue
10  INPUT S/N       L
A022-4064         ?

Enter the loop number and press [ ✱ ].  The system will now
check for a duplicate serial/loop number combination.

This prompt will only appear if you answered “Yes” at the first
prompt in this section.
The system will enter a confirmation mode so that the operation
of the actual programmed input can be confirmed.
Activate the loop input or button that corresponds to this zone.
**Confirmation Option**
[ ∗ ] to continue
XMIT TO CONFIRM
PRESS ✱ TO SKIP

If the serial number transmitted does not match the serial
number entered, a display similar to the one shown appears. If
the loop number does not match, it will also be displayed.
If so, activate the loop input or button on the transmitter once
again.  If a match is not obtained (i.e., summary display does not
appear), press the [#] key twice and then enter (or transmit) the
correct serial number.
**If Serial or Loop**
**Numbers do not match**
**after activating the**
**transmitter**
[ ∗ ] to continue
Entd A022-4063 1
Rcvd A022-4064  1

To delete an existing serial number, enter 0 in the loop number
field. The serial number will change to 0's.
If 0 was entered in error, simply re-enter the loop number or
press [#], and the serial number will return to the display.
**To Delete a Serial No.**
0 = delete serial number
# = undo deletion
[ ∗ ] to continue
10  INPUT S/N: L
A000-0000     0

If the serial number transmitted matches the serial
number entered, the keypad will beep 3 times and a
summary display will appear, showing that zone's
programming.  Note that an “s” indicates that a
transmitter’s serial number has been enrolled.
Press [ ∗ ] to accept the zone information and continue.
**Summary Screen**
[ ∗ ] to continue
Zn   ZT    RC    In:   L
10   03   10    RF:  1s

If you want to program descriptors for zones now, enter 1 (Yes)
and refer to the ∗ 82 Descriptor Programming section for
available descriptors ***.***
**Alpha Descriptors**
0 = no
1 = yes
[ ∗ ] to continue
PROGRAM ALPHA?
0 = NO  1 = YES    0

If 0 (No) was entered above, the system will return you to the
ENTER ZN NUM. prompt for the next zone.
When all zones have been programmed, enter 00 to quit
**Next Zone Number**
[ ∗ ] to continue;
00 = quit
ENTER ZN NUM.
(00 = QUIT)
11

**Completing Zone Programming**
• When you have finished programming all zones, test each zone using the system’s TEST mode.
• **Do not use the Transmitter ID Sniffer Mode for checking wireless transmitting devices** , as it will only check for
transmission of one zone on a particular transmitter, NOT the zones assigned to each additional loop.

∗ **58 EXPERT ZONE PROGRAM MODE**
**(press** ∗ **58 while in Data Programming mode)**
This method is designed for use by installers with previous experience in programming HONEYWELL control panels. This
mode is also used to program wireless keys using pre-defined templates.

Select whether you want confirmation of wireless device
enrollment. (See “XMIT TO CONFIRM” prompt later in this
section.) **We recommend that you confirm the programming**
**of every transmitter.**
If *1* (Yes) is entered, you will be prompted to confirm each
transmitter after entering the serial and loop numbers (at the
“XMIT TO CONFIRM” prompt later).
**Confirm?**
0 = no; 1 = yes; [ ∗ ] to
continue
SET TO CONFIRM?
0 = NO   1 = YES   0

A summary screen appears, showing zone 1’s currently
programmed values.
**Summary Screen**
01-64 = zone number;
[ ∗ ] to continue;
00 = quit
[D] to go to prompts for
wireless key programming
templates
Zn   ZT P  RC  HW:
RT
01   09  1  10    EL    1
Enter the zone number being programmed, then press [ ∗ ], which
displays a summary screen for that zone and the cursor moves
to the Zone Type location. The cursor then automatically moves
to the next locations after each entry is made.

**If programming a wireless key,** press the [D] key then skip to
the Wireless Key Programming Templates section following this
section. When [D] is pressed, you can choose from a series of
preset templates for easy programming of wireless key zones.

When all zones have been programmed, press *00* at this prompt
to quit this menu mode.

**–** 21 **–**

---

## Page 22

A summary screen with the selected zone’s current
programming appears.
Begin programming zone information as follows:
• Enter Zone Type (ZT), Partition (P), Report Code (RC; 0-9
only; use *56 mode to enter hex codes), and Input Device
Type (IN)* sequentially, but not the Loop No. (L).
• Use the [A] (Advance) and [B] (Back) keys on the keypad to
move the cursor within the screen.
• Use the [C] key to copy the previous zone’s attributes.
Press [ ✱ ] to save the programming and continue to the serial
number/loop number prompt. If needed, you can press the [#]
key to back up without saving.
* If HW (hardwired) or AW (Auxiliary) is entered for Input Device
Type, the next screen will be similar to the prompt shown, except
that HW or AW will be displayed under “IN”.
If RF, BR, or UR is entered, a prompt for Serial and Loop
number will be displayed, as described in ∗ 56 Menu mode
section.
When done, the display returns to the initial summary screen
prompt to let you program the next zone.
**To exit this mode,** enter 00 at the Summary Screen prompt.
**WIRELESS KEY PROGRAMMING TEMPLATES**
**Zone Programming**
ZT = see Zone Type chart
shown in *56 Menu
Mode “Zone Type”
prompt
P = partition 1, 2, 3
(common);
RC = 1 (send CID report); 0
(no report)
IN = input type;
L = loop number
[ ∗ ] to continue
Zn ZT  P  RC  IN:  L
10    00  1 10   RF 1

**(press the [D] key from *58 Menu mode Summary Screen)**
This procedure programs the wireless keys, **but a key is not active for arming/disarming until it is assigned to a user**
**number** (see ***System Operation*** section, Assigning Attributes Command in the User Guide).

**Template Number**
*1–3 = 5804 templates; 4–6*
*= 5804BD templates*
• Enter Template number 1–6 (see chart on next page).
See the defaults provided for each template in the chart that
follows these procedures.
• Select from templates.  Press [ ∗ ] to display template (1
shown selected).
**NOTE** : If necessary, press [#] to back up and re-enter
template number.
• Press [#] if you want to return to *58 Menu mode summary
screen.
TEMPLATE  ?
1–6
1

**Template Display**
• When [ ∗ ] is pressed, the selected template will be displayed.
Top line of display represents loop numbers; bottom line
represents zone type assigned for each loop.
• Press [ ∗ ] to accept template.
L    01    02    03   04
T    23    22    21 23

**Partition**
*VISTA-20P. 1 = partition 1;*
*2 = partition 2*
• Enter the partition in which the key is to be active, then press
[ ∗ ] to continue.
PARTITION
1

**Start Zone Number**
• The system will search for the highest available consecutive
4-zone group (the four zones in the case of the 5804 and
5804BD), and display the lowest zone number of the group.
If you want to start at a different zone, enter the zone desired,
and press [ ✱ ]. If that zone number is displayed, the system
has the required number of consecutive zones available,
beginning with the zone you entered.  If not, the system will
again display a suggested zone that can be used.
If the required number of consecutive zones is not available
at all, the system will display “00”.
ENTER START ZONE
00 = QUIT
36

**To quit this mode** and return to *58 Menu mode, enter 00 at
this prompt.

• Press [ ∗ ] to accept.
**Serial Number**
• Manually enter the serial number printed on the label for the
wireless key or press and release the button to transmit its
serial number.
• Press [ ∗ ] to accept the serial number.  The system will check
for a duplicate.
• If necessary, press the [#] key to back up without saving, and
re-enter the serial number.
• Use the [A] key to move forward within the screen, and the
[B] key to move backward.
INPUT S/N             L
AXXX-XXXX          –

**–** 22 **–**

---

## Page 23

**Confirm**
[ ∗ ] to continue
•
If “Yes” was entered at the **SET TO CONFIRM?** prompt
previously (see first prompt following entry into the ∗ 58
Expert Programming Mode), the display on the left will
appear. Confirm serial and loop numbers by activating the
wireless key.
**IMPORTANT:**
When confirmed, the key is not active for arming/disarming until
it is assigned to a user number (using the assigning attributes
command, attribute “4”). See ***System Operation*** section for
procedure.
XMIT TO CONFIRM
PRESS ✱ TO SKIP

If the serial number transmitted does not match the serial
number entered, a display similar to the one shown will appear.
If the loop number does not match, it will also be displayed.
If so, activate the button on the wireless key once again. If a
match is not obtained (i.e., summary display does not appear),
press the [#] key and then enter the correct serial number.
**Not Confirmed**
[ ∗ ] to continue
Entd   A022-4063
Rcvd  A022-4064

If the serial number transmitted matches the serial number
entered, the keypad will beep 3 times and will return you to the
Zone Number prompt to enter the starting zone for the next
wireless key.
Or you can return to *58 Menu mode by pressing 00 at the Zone
Number prompt.
**Wireless Key Predefined Default Templates**

LOOP 3
SERIAL #2
LOOP 1
GREEN/YELLOW
LED
LOOP 2
SERIAL #1
LOOP 3
SERIAL #1
LOOP 2
LOOP 2
RED/YELLOW
LED
LOOP 1
LOOP 4
SERIAL #2
LOOP 3
SERIAL #2
LOOP 4
LOOP 4
LOOP 3
SERIAL #1
LOOP 4
SERIAL #1
LOOP 1
LOOP 1
•
••••
•
• •••
• • •
••• •
•
•
ENROLL AS "BR"
5804BD-007-V1
**5804BD 2-Way Wireless Key**
**Transmitter**
SERIAL #2
LOOP 2
**5834-4 Wireless Key**
**Transmitter**
**5804 Wireless Key**
**Transmitter**
5804-001-V4
5834-013-V0

**NOTE:** Some transmitters are not intended for use in UL installations.


| For Button-Type Devices TEMPLATE 1 Loop Function Zone Type |  |  | For Button-Type Devices TEMPLATE 4 Loop Function Zone Type |  |  |  |
| --- | --- | --- | --- | --- | --- | --- |
|  | 1 No Response 2 Disarm 3 Arm Away 4 No Response | 23 22 21 23 |  | 1 2 3 4 | No Response No Response Arm Away Disarm | 23 23 21 22 |
| TEMPLATE 2 Lo | op Function | Zone Type | TEMPLATE 5 | Loop | Function | Zone Type |
|  | 1 No Response 2 Disarm 3 Arm Away 4 Arm Stay | 23 22 21 20 |  | 1 2 3 4 | No Response Arm Stay Arm Away Disarm | 23 20 21 22 |
| TEMPLATE 3 Lo | op Function | Zone Type | TEMPLATE 6 | Loop | Function | Zone Type |
|  | 1 24-hour audible 2 Disarm 3 Arm Away 4 Arm Stay | 7 22 21 20 |  | 1 2 3 4 | 24-hour audible Arm Stay Arm Away Disarm | 7 20 21 22 |


Deactivate a wireless key by deleting the associated user code:
Delete the User Code: Master code + [8] + 2-digit user no. + [#] [0]
Remove a wireless key from the system by deleting one of the wireless key zones using Zone Programming mode:
1. Press *56 while in Program mode then enter a zone number assigned to the wireless key.
2. Scroll through each prompt by pressing [ ∗ ] until the Input S/N prompt appears.
3. Enter 0 for the loop number and press [ ∗ ].
4. Exit program mode.

**–** 23 **–**

---

## Page 24

∗ **57 FUNCTION KEY PROGRAMMING MENU MODE**
**(press** ∗ **57 while in Data Programming mode)** The Function Key Worksheet is on page 45.
The system provides the ability to program each of the four keypad function keys to perform one of 12 system operations. The
end user can then activate the function by simply pressing and holding the programmed key for 2 seconds. Typical functions
(listed below) include single-button arming, turning lights on/off, or single-button paging.
To assign emergency key functions (function key option “00”), first program the respective emergency zone number (95 for
“A” key, 96 for “C” key, 99 for “B” key) with the desired zone type using ∗ 56 (or ∗ 58) Zone Programming mode, then use ∗ 57
Function Key menu mode to assign the desired key.
To use a function key to activate a relay action ( ∗ 57 Menu mode key function 07), use ∗ 79 Menu mode to map the output, and
use ∗ 80 Menu mode to define the output’s action; select system operation type “66.”
To use a function key for a user macro, use ∗ 57 menu mode to activate the desired key, then define the actual macro
functions using the user code + [#] + [6] [6] command.

Press the desired function key (A-D) you want to program.
**NOTE:** A key programmed as a function key is no longer
available to be used as an end-user macro key or panic key.
**Function Key**
Press the desired function
key, A-D.
[ ∗ ] to continue
0 = Exit this mode
Press Key to Pgm
0 = Quit
0

**A**
**3**
**2**
**1**
**OFF**
**AWAY**
**STAY**
**B**
**6**
**5**
**4**
**TEST**
**BYPASS**
**MAX**
keypad_keys-00-001-V0
**C**
**9**
**8**
**7**
**INSTANT**
**CODE**
**CHECK**
**D**
**#**
**0**
*****
**READY**

Enter the partition in which the function key is active.
**Partition Number**
**(VISTA-20P)**
1 = partition 1
2 = partition 2
3 = common partition
[ ∗ ] to continue
Partition
1

Enter the desired function for this key, 00 to 12, from the options
listed. (00 selected for example display shown at left). Press [ ∗ ]
to returns to key number prompt with the next function key letter
displayed.
**Define Key Function**
00-12 = see list at right
[ ∗ ] to continue; returns to
key number prompt with the
next function key letter
displayed
Key  "A"  Func
Zone  95
00

00 † = For the Function key selected, the functions are predefined as
follows:
If A selected = Zone 95 (emergency key, same as [1] [ ∗ ] pair)
If B selected = Zone 99 (emergency key, same as [ ∗ ] [#] pair)
If C selected = Zone 96 (emergency key, same as [3] [#] pair)
If D selected = Single-button paging
01 =
Single-button paging (sends a 999-9999 message to pager)
02 =
Display time
03 =
Arm AWAY (reports as User 00 if closing reports are enabled)
04 =
Arm STAY (reports as User 00 if closing reports are enabled)
05 =
Arm NIGHT-STAY (reports as User 00 if closing reports enabled)
06 =
Step Arming (arms STAY, then NIGHT-STAY ††† , then AWAY)
07 =
Output Device Command (for device programmed as system
operation type 66–function key in *80 Menu Mode)
08 =
Communication Test (sends Contact ID code 601)
09 =
Macro Key 1 (define macro by user code + [#] [6] [6] command)
10 =
Macro Key 2 (define macro by user code + [#] [6] [6] command)
11 †† = Macro Key 3 (define macro by user code + [#] [6] [6] command)
12 †† = Macro Key 4 (define macro by user code + [#] [6] [6] command)

† System defaults to these function key settings.
†† Macros 11-12 apply to VISTA-20P only.
††† If Night-Stay zones are listed in zone list 5

**–** 24 **–**

---

## Page 25

**OUTPUT DEVICE PROGRAMMING GENERAL INFORMATION (*79/*80 Menu Mode)**

**Output Devices:**
The VISTA-20P system supports up to 16 relays and/or Powerline Carrier devices (X-10 devices)
plus 2 built-in trigger outputs in any combination. These 18 “outputs” are assigned to system-wide
output numbers (01-18). Use *79 Menu Mode to assign output numbers and map them to device
addresses.
The VISTA-15P supports 8 relays and 2 built-in trigger outputs (total 10 outputs).
**Output Functions:**
The system also provides installer-defined output functions, which can be assigned to any of the
physical outputs. Therefore, the action of any one of the outputs can be based on as many of these
defined functions as desired. This lets a single relay or X-10 device perform many functions.
The control supports: V20P = up to 48 defined functions; V15P = up to 24 functions
Use *80 Menu Mode to define output functions.
**WARNING:** Relays and output devices are not recommended for life safety applications.
**NOTE:** When navigating the *79 and *80 menus: The [ ✱ ] key is used to accept an entry and advance to the
next prompt. The [#] key is used to revert back to the last question to check or change an entry. Press [ ✱ ] to
go forward again.

**Programming Output Devices**
1. Use *79 Menu Mode to assign module and output numbers and map them to device addresses.
**NOTE:** You must map output devices using *79 Menu Mode **before** you can use *80 menu Mode.
2. Use *80 Menu Mode to create output definitions, which control the output devices, if desired.
3. Use *81 Zone List Menu mode to define zone lists for use with output devices if the device action is based on more than
one zone.
• To program a device for manual activation (user code + [#] [7] / [#] [8] + 2-digit device number) or for scheduled automatic
activation, simply map the device using *79 Menu mode.
• To program a device to automatically activate upon a system event (or function key), use *79 Menu mode to map the device,
then use *80 Menu mode to define the automated device action.

∗ **79 RELAY/POWERLINE CARRIER DEVICE (X-10) PROGRAMMING MENU MODE**
**(press** ∗ **79 while in Programming mode)** The *79 Device Mapping Worksheet is on page 45.
Use this menu to assign Relay Module device addresses and specific relay numbers, and Powerline Carrier unit numbers. The
system is based on predefined module addresses for 4204 and 4229 modules. Refer to the table shown at the “Module
Address” prompt on the next page and set the modules’ addresses (via module DIP switches) accordingly.

The following table shows how these outputs are identified.


| This output… | is identified by… |
| --- | --- |
| Relays | the Relay Module’s device address and the relay position on that module (i.e. the physical relay number, 1-4, on that module). |
| X-10 Device | a house ID (entered in data field *27) and the unit number of the device. |
| Built-in Outputs | the output number assigned, 17 for Trigger 1 and/or 18 for Trigger 2. |


This is the logical (or reference) relay number as used in the
system. Relays and X-10 devices are numbered 01-16; the on-
board triggers are numbered 17 and 18 and can be programmed
for inverted output, if required.
**Device Output Number**
VISTA-20P:
01-16 = relays/X-10
17, 18 = on-board triggers
VISTA-15P:
01-08 = relays/X-10
17, 18 = on-board triggers
[ ∗ ] to continue
00 to quit
ENTER OUTPUT NO.
00 = QUIT
xx

(prompt appears only if trigger 17 or 18 was selected above)
Selecting *0* (no) sets the output level normally high (default
setting).
Selecting *1* (yes) sets the output normally low.
Output Trigger 17 can be used for resetting 4-wire smoke
detectors † by connecting it to the negative power terminal of the
smoke detector, selecting 1 at this prompt, and setting as zone
type 54, fire zone reset, in *80 Menu mode.
After entry, display returns to Output Number prompt. Use *80
Menu mode to program the function of the trigger.
**†** **Power Reset:** This control does not automatically reset power
to 4-wire smoke detector zones, so you must use a relay (e.g.,
4204, 4229) or on-board trigger to reset power (also required
for fire verification).
**Output Normally Low**
0 = no (standard default)
1 = yes
[ ∗ ] to continue
17 OUT NORM LOW
0 = NO 1 = YES
0

**–** 25 **–**

---

## Page 26

Select whether this is a relay or a Powerline Carrier (X-10)
device.
If Powerline Carrier Device (X-10) is selected, go to “A” prompt.
If relay is selected, skip to “B” prompt.
**Output Type**
0 = delete
1 = relay on 4204/4229
2 = Powerline Carrier Device
[ ∗ ] to continue
XX OUTPUT TYPE
DELETE
0

**“A”**

| XX UNIT No. yy | 01-16 = predefined address Enter the unit code (set at the device) and press [∗]. [∗] to continue The system returns to the Output Number prompt. |
| --- | --- |


**“B”**
**Module Address**
07-15 = predefined address
[ ∗ ] to continue
**REMOTE SERVICES NOTE:** If
using the communication device’s
Multi-Mode 4204 or 2-4204
options, select one of the 4204
addresses, though a physical
4204 module is not installed. If
using 2-4204 multi-mode option,
the second 4204 address is
automatically one number higher
than the first address. Make sure
these addresses are not used by
physical 4204 modules that may
be installed. If using Multi-Mode
Enhanced Reports option, RIS
must be enabled in field *91;
when enabled, address 25 is
automatically assigned. See the
communication device’s
instructions to enable Multi-Mode.
XX MODULE ADDR
07-15
yy


| Address | Module |
| --- | --- |
| 07 | 1st 4229 (with zones 09-16) |
| 08 | 2nd 4229 (with zones 17-24) |
| 09† | 3rd 4229 (with zones 25-32) |
| 10† | 4th 4229 (with zones 33-40) |
| 11† | 5th 4229 (with zones 41-48) |
| 12 | 1st 4204 |
| 13 | 2nd 4204 |
| 14† | 3rd 4204 |
| 15† | 4th 4204 |


This is the actual (or physical) relay number with respect to the
Relay Module upon which it is located. For 4204 modules, relay
numbers are 1-4. For 4229 modules, relay numbers are 1-2.
The system returns to the Output Number prompt for
programming the next device.
**Relay Position**
1-4 = relay position
[ ∗ ] to continue
XX REL POSITION
1-4
zz

**REMOTE SERVICES NOTE:** If using the communication device’s
multi-mode, program virtual 4204 relays to trigger on those
system events intended to be sent to the user’s email address.
(4204 option = up to 4 events; 2-4204 option = up to 8 events)

∗ **80 OUTPUT FUNCTION MENU MODE**
**(press** ∗ **80 while in Programming mode)** The Output Definition Worksheet is on page 46.
Use this mode to program output function definitions (up to 48 functions) that provide automated control of any of the output
devices, based on events occurring on individual zones or zones with certain zone types. Each output definition is identified
by an output function number, and includes the following components:


| Component | Description |
| --- | --- |
| Output Function No. | A reference number that defines an output’s characteristics. |
| Activated By | Determines whether the initiating event occurs on a zone, a zone list, or a zone type. |
| Event | Event that triggers the output action. Can be an event occurring on a specific zone number or a zone list, or a specific zone type. |
| Partition | If the output is activated by zone type, this defines the partition in which the programmed event is to cause the device action. |
| Output Action | Defines the action of the relay/X-10 device when the defined event occurs. Can close for 2 seconds, stay closed until reset, continuously pulse (1-second close-open-close-open, etc.), toggle the device state, or activate for a defined duration (set in data field *177). |
| Output No. | Assigns this function to a specific output number (defined in *79 Menu Mode). This is the output number that will perform this function upon the triggering event. Note that each defined function is associated with only one output number. This means that if more than one output device needs to perform this particular function, you need to define another output function number with the same attributes, but assign the appropriate output number. (i.e. output devices can be assigned more than one function number, but each function number can only be assigned a single output number. |


**For example,** if you want to pulse a strobe light upon fire alarms on zone 4 using a relay mapped to output number 2 (as
programmed in *79 Menu Mode), program the following in *80 Menu Mode:
**Prompt**
**Entry**
Output Funct. #
=
01 (assuming this is the first output function)
Activated By:
=
3 (zone number)
Enter Zn No.
=
04 (requires 2-digit zone numbers)
Output Action
=
3 (continuous pulse)
Output Number
=
02 (device mapped in *79 Menu Mode)

**–** 26 **–**

---

## Page 27

**80 Menu Mode**
Enter the output function number to be defined (or 00 to exit)
**Output Function No.**
(VISTA-20P: 01-48
(VISTA-15P: 01-24)
[ ∗ ] to continue; 00 to quit
Output Funct. #
(00 = Quit)
01

This screen displays a summary of the current output
programming (for this example, Zone List has been selected-this is
the default screen).
**A** = Output Action; **E** = Triggering event; **P** = Partition;
**Trig** = Trigger type
**Summary Screen**
[ ∗ ] to continue
01    A   E   P   Trig
?00  0    0   –  ZL=00

**NOTE:** A question mark in the summary screen indicates that the
device number shown has not been mapped. Use *79 Menu mode
to map the device.

Select where the initiating event for this output definition is to occur
as follows:
If you enter “0,” the following prompt appears:
Delete?
0 = NO,  1 = YES
Press 1 to delete this output definition. The system deletes the
output function and any previous programming.
**Activated By**
0 = delete
1 = zone list (go to “A”)
2 = zone type  (go to “B”)
3 = zone number (go to “C”)
[ ∗ ] to continue
01 Activated By:
Zone List

**A** ”
(prompt appears if zone list was selected)
Enter the desired zone list number associated with this output
number. At the ENTER EVENT prompt, enter the zone list event
that will activate this output
**NOTE:** Do not use pager zone lists 09-12 in output definitions.
**Zone List**
01-08 = zone list
[ ∗ ] to continue
01  Zn List
1

Enter Event
0 = restore; 1 = alarm;
Alarm
1
2 = fault; 3= trouble

**NOTE:** For alarm, fault, and trouble, an event on ANY zone in the
list activates the output, but ALL zones in the list must be restored
before the output is restored.
Press [ ✱ ] to continue and skip to the “Output Action” prompt.

“ **B** ”
(prompt appears if zone type was selected)
Enter the desired zone type associated with this output number. At
the PARTITION prompt, enter the partition in which this zone type
will occur.
**CHOICES FOR ZONE TYPES:**
00 = Not Used
05 = Day/Night
12 = Monitor Zone
01 = Ent/Exit #1
06 = 24 Hr Silent
14 = Carbon Monoxide††
02 = Ent/Exit #2
07 = 24 Hr Audible
16 = Fire w/verification
03 = Perimeter
08 = 24 Hr Aux
23 = No Alarm Response
04 = Interior Follower
09 = Fire
24 = Silent Burglary
10 = Interior w/Delay
77 = Keyswitch Zone
81 = AAV Monitor Zone
90-91 = Configurable
**CHOICES FOR** **SYSTEM OPERATION:**
20 = Arming–Stay
36 = **At Bell Timeout***
58 = Duress
21 = Arming–Away
38 = Chime
60 = AAV
22 = Disarming
39 = Any Fire Alarm
61 = AVS/GSMV4G session begin §
31 = End of Exit Time
40 = Bypassing
62 = AVS/GSMV4G session end §
32 = Start of Entry Time 41 = **AC Power Failure
66 = Function Key†
33 = Any Burglary Alarm 42 = **System Battery Low 67 = Bell Fail
43 = Comm. Failure
68 = Telco Line Cut
52 = Kissoff
78 = Keyswitch Red LED
54 = Fire Zone Reset
79 = Keyswitch Green LED
** Use 0 (Any) for Partition  No. (P) entry.
***  Or at Disarming, whichever occurs earlier.
**Zone Type**
See list at right for available
zone types.
01  Enter Zn type
Perimeter
03

† Use *57 Menu Mode to assign the function key (function “07”).
†† when used with an output function, the carbon monoxide zone type
activates upon CO alarms only. Does not activate for trouble conditions.

§ automatically set when appropriate AVS Quick Command performed.
**Note:** In normal operation mode:
Code + # + 7 + NN Key Entry **starts** Device NN.
Code + # + 8 + NN Key Entry **stops** Device NN.
Enter the partition in which this zone type will occur.

01 Partition
0 = any partition; 1 = partition 1;
Any partition 0
2 = partition 2; 3 = common
Press [ ✱ ] to continue and skip to the “Output Action” prompt.

**–** 27 **–**

---

## Page 28

“ **C** ”
(prompt appears if zone number was selected)
Enter the desired zone number associated with this output
number. At the ENTER EVENT prompt, enter the zone event
that will activate this output.
01 Enter Event
0 = restore; 1 = alarm/fault/trouble
Restore
0
Press [ ✱ ] to continue to the “Output Action” prompt
**Zone Number**
Press [ ✱ ] to continue.
01   Enter Zn No.
12

Enter the desired device action.
**Output Action**
0 = off
1 = Close for 2 seconds
2 = Stay Closed
3 = Pulse on & off (1 sec
ON, 1 sec OFF)
4 = Change Device State
5 = Duration 1 (see data
field *177)
6 = Duration 2 (see data
field *177)
Press [ ✱ ] to continue.
01 Output Action
Close for 2 sec
1

Enter the device output number (programmed in *79 Menu
Mode) you want associated with this output.
**Output Number**
01-16 = VISTA-20P outputs
01-08 = VISTA-15P outputs
17-18 = on-board triggers
Press [ ✱ ] to continue.
Enter Output No.
R02
02

A summary screen appears showing the programmed settings.
Press [ ∗ ] to return to OUTPUT FUNCTION NUMBER prompt
**Summary Screen**
Press [ ✱ ] to continue.
02    A   E   P   TRIG
R02  1   1    3  ZL=00

∗ **81 ZONE LIST MENU MODE**


| List No. | Used for… | Notes |
| --- | --- | --- |
| 1, 2 | general purpose (GP) | • Any list may include any or all of the system's zone numbers. • A zone list can be assigned to more than one output relay. • Zone List 4: When creating zone list 4 for cross zoning, include only zones assigned to zone types 3, 4, or 5. Do not include zones that have delays (entry/exit zones, interior w/delay) or 24-hour zones, as these zone types may produce unpredictable operation and may not function as intended. See field *85 for Cross Zone Timer option. • Zone List 6: V20PSIA/V15PSIA: See field *50 for Dial Delay Disable option. • Zone List 7: V20PSIA/V15PSIA: See field *93 for Unlimited Reports option. |
| 3 | chime-by-zone (see field *26 to enable option) |  |
| 4 | cross zones (see note at right) |  |
| 5 | night stay zones |  |
| 6 | general purpose V20PSIA/V15PSIA: dial delay disable |  |
| 7 | general purpose V20PSIA/V15PSIA: unlimited reports |  |
| 8 | general purpose |  |
| 9 | zones that activate Pager 1 |  |
| 10 | zones that activate Pager 2 |  |
| 11 | zones that activate Pager 3 (VISTA-20P) |  |
| 12 | zones that activate Pager 4 (VISTA-20P) |  |


***81 Menu Mode**
Enter the Zone List Number to program (or 00 to quit). Press [ ✱ ]
to advance.
In the following displays, zone list 01 has been selected.
**Zone List Number**
01-12 = zone list number
[ ∗ ] to continue
Zone List No.
(00 = Quit)
01

Enter each zone number to add to the zone list, followed by
pressing [ ✱ ] (example, 01 ✱ , 02 ✱ , 03 ✱ ). After all zones are
entered, press 00 to continue.
**IMPORTANT:** Do not include fire zones in zone lists that are
used to STOP device actions.
† VISTA-20P = 01-64; VISTA-15P = 01-06, 09-34, 49-56.
**Zone Number**
01-64 † = zone numbers
followed by [ ∗ ] to
accept each zone
00 to continue
01 Enter Zn Num.
(00 = Quit)
00

To delete the zone list, enter 1. All zones in the zone list will be
deleted automatically and the system returns to the Zone List
No. prompt.
To save the zone list, enter 0.
**Deleting Zone Lists**
0 = don’t delete list
1 = delete this zone list
[ ∗ ] to continue
01 Del Zn List?
0 = No  1 = Yes
0

**–** 28 **–**

---

## Page 29

To save the zone list, enter 0 and the system returns to the Zone
List No. prompt.
To delete a zone or zones in a zone list, enter 1 to continue.
**Deleting a Zone**
0 = don’t delete zones
1 = go to next prompt to
delete zones
[ ∗ ] to continue
01 Delete Zone?
0 = No  1 = Yes
0

Enter each zone to be deleted from the list, followed by [ ✱ ]. After
all zones to be deleted are entered, enter 00 to return to the
Zone List No. prompt so that another list can be programmed, if
desired.
† VISTA-20P = 01-64; VISTA-15P = 01-06, 09-34, 49-56.
**Delete the Zone**
01-64 † = zones to be
deleted from list
followed by [ ∗ ] to
accept each zone
00 to continue
01 Zn to Delete?
(00 = Quit)
00

∗ **82 ALPHA DESCRIPTOR MENU MODE**
The system lets you assign zone descriptors for protection zones, keypad panics, and RF receiver supervision faults. Each
description can be composed of a combination of up to 3 words selected from a vocabulary of words stored in memory (see
Alpha Vocabulary List page). In addition, up to 10 installer-defined words can be added to those already in memory, plus 3
additional words can be assigned as partition descriptors. Thus, when an alarm or trouble occurs in a zone, an appropriate
description for that zone's location can be displayed at the keypad. Zone descriptors are recommended for systems using Alpha
display keypads, and are necessary if a 4286VIP Phone Module is used.
**NOTE:** You can also enter zone descriptors when the zone is being defined in ✱ 56 Menu mode.
**4286 NOTE:** If using a 4286VIP Phone Module, select from those words in the Alpha Vocabulary List shown in **boldface**
**type** . The phone module will not provide annunciation of the other words.
If a Phone Module is added to an existing system, the Alpha descriptors presently in the system should be reprogrammed,
selecting from those words shown in **boldface** **type** in the Alpha Vocabulary List. The phone module will not provide
annunciation of any other words.

∗ **82 Menu Mode**

The “Program Alpha ?” prompt will appear. Press 1 to continue.
**Program Alpha**
0 = no (quit Alpha mode)
1 = yes
[ ∗ ] to continue
Program Alpha ?
0=No, 1=Yes 00

The “Custom Words” prompt will appear.
Press 0 to program standard alpha descriptors from the fixed
vocabulary. The system then automatically displays the descriptor
for zone 1.
Press 1 to define custom words (see “Adding Custom Words”).
**Custom Words**
0 = no
1 = yes
Custom W ords ?
0=No, 1=Yes 00

Note that this is a “Summary mode,” and that no entries can be
made. Entries can be made only when the display contains a
flashing cursor, which signifies Edit mode.”
To exit the Alpha Descriptor mode, press ∗ + 0 + 0 at the
summary display.
**Summary Screen**
[ ∗ ] to continue to edit mode
[#] = return to Program
Alpha prompt (to quit)
✱ ZN 01

Descriptor screen for zone 1 appears. To program a descriptor
(up to 3 words) for a zone, do the following:
1. Enter the desired zone number (existing descriptor, if any, is
displayed) and press [ ∗ ], then enter the zone number again to
start edit mode (flashing cursor appears).
2. a. Press [#] plus the 3-digit number from the Alpha Vocabulary
List for the first word.
b. Press [6] to accept the word and move the cursor for the next
word in the descriptor.
3. Repeat steps 2a and 2b for the second and third words (if used).
4. When all words for that descriptor have been entered, press [8]
to save the descriptor for that zone. The summary screen
displays for that zone and the flashing cursor disappears.
5. Press [ ∗ ] at the summary screen and repeat steps 1-4 to
assign a descriptor for the next zone.
6. When all descriptors have been entered, press [#]) at the last
descriptor summary screen to return to the PROGRAM
ALPHA? prompt. Enter 0 (no) at the prompt to exit this mode
and return to Data Field mode.
**Edit Mode – Flashing**
**Cursor**
✱ ZN 01
to edit = zone number then
[ ∗ ], then zone
number again
6 = save word and go to
next word in a
descriptor
8 = save descriptor and go
to next zone
[#] = return to Program
Alpha prompt (to quit)

**–** 29 **–**

---

## Page 30

EXAMPLE: “BACK DOOR”
a. From the list, BACK = 013, so, after entering the zone number
to be edited (step 1), enter #013. If you accidentally enter the
wrong word, simply press [#] plus the correct 3-digit number for
the word you want.
b. Press [6] to accept the selected word and continue to the next
word. (if this is the only word you are using for the descriptor
press [8] to save it).
c. Enter the 3-digit number for the next word, “DOOR,” whose
number is “057.” Enter # 0 5 7.
d. Because this is the last word in the example descriptor, press
[8] to save it. (If there was a third word in the descriptor, press
[6] to accept the selected word and continue to the third word.)
The summary screen displays with the selected descriptor.
**Descriptor Example**
EXAMPLE:
(a)

✱ ZN 01
B ACK

(b)
✱ ZN 01
BACK

(c)
✱ ZN 01
BACK
D OOR

(d)
✱ ZN 01
BACK
DOOR

The flashing cursor disappears, indicating that the word(s) are
saved for that zone, as shown in the summary display at the left.
To enter a descriptor for the next zone, press [ ✱ ] plus the
desired zone number. The summary display appears. Repeat
the previous steps to enter the descriptor for the zone.
**Summary Screen**
[ ∗ ] = to enter another zone
number
[#] = return to Program
Alpha prompt (to quit)
✱ ZN 01  BACK
DOOR

**Adding Custom Words (will not be annunciated by 4286 Phone Module)**
You can add up to 10 installer-defined words to the built-in vocabulary, which can then be used when programming zone
descriptors. Each of the 10 words can actually consist of a word string of one or more words, but no more than *ten*
characters can be used for each word or word string.
When adding custom words, the keypad keys perform the following functions:

[4] Moves cursor one space to the left.
[6] Moves cursor one space to the right.
[8] Saves the new word in the system's memory.
1. Select Custom Word mode (enter 1) when the prompt “CUSTOM WORD ?” is displayed.
2. Enter the number (01–10†) of the custom word or word string to be created, corresponding to index numbers 245 - 254
respectively (for example, if you are creating the first custom word or word-string, enter 01, for the second, enter 02, etc.).
A cursor will now appear at the beginning of the second line.
† or 11, 12, 13 for partition 1, partition 2 and common lobby descriptors respectively. See Assigning Partition
Descriptors paragraph below.
**NOTE:** Custom words 8, 9, and 10 are “reminder words” that are programmed using Scheduling Mode.
3. Refer to the Character List of letters, numbers, and symbols on a following page.
Press [#], followed by the two-digit entry for the first letter you would like to display (e.g., # 65 for “A”).
Press [6] to advance the cursor to the right, in position for the next character.
**To delete a character,** simply enter the SPACE character (#32) at the unwanted character’s location..
4. Repeat Step 3 to create the desired word(s). Note that the “4” key can be used to move the cursor to the left, if necessary.
Remember, no word or word-string can exceed 10 characters (except custom message/partition descriptor word numbers
11, 12, and 13, which can be a maximum of 16 characters).
5. When the word is complete, press the [8] key to save the custom word(s) and return to the “CUSTOM WORD ?” display.
Repeat Steps 2–5 for other custom words to be entered. To change a custom word, just overwrite it. When all words have
been programmed, press [0] to return to the Descriptor entry. The custom word(s) will be automatically added to the built-
in vocabulary.
**Assigning Partition/Custom Message Descriptors**
VISTA-15P: You can create a custom message display that appears on alpha keypads instead of “System Ready.” To assign
a custom message, use word number 11 as described below.
VISTA-20P: You can assign a partition descriptor (up to 16 characters) for each partition plus the common lobby. The system
displays the appropriate partition’s word instead of “DISARMED READY TO ARM.”
Use the same procedure as for adding custom words (described above), but use these word numbers in step 2:
11 = partition 1 ___________________________________________
12 = partition 2 ___________________________________________ (VISTA-20P only)
13 = common lobby ________________________________________ (VISTA-20P only)
Once a custom word is entered in any of these word locations (11-13), the system displays the appropriate partition’s word
instead of the default “DISARMED READY TO ARM” message.

**–** 30 **–**

---

## Page 31

**ALPHA VOCABULARY LIST  (For Entering Zone Descriptors)**
000 *(Word Space)*
**– A –**
**• 001 AIR**
***• 002 ALARM*** ∗
004 ALLEY
005 AMBUSH
**• 006 AREA**
**• 007 APARTMENT**
***• 009 ATTIC*** ∗
010 AUDIO
**– B –**
***• 012 BABY*** ∗
***• 013 BACK*** ∗
**• 014 BAR**
***• 016 BASEMENT*** ∗
***• 017 BATHROOM*** ∗
**• 018 BED**
***• 019 BEDROOM*** ∗
020 BELL
**• 021 BLOWER**
**• 022 BOILER**
023 BOTTOM
025 BREAK
**• 026 BUILDING**
**– C –**
028 CABINET
**•** **029 CALL**
030 CAMERA
031 CAR
033 CASH
034 CCTV
035 CEILING
036 CELLAR
**• 037 CENTRAL**
038 CIRCUIT
***• 040 CLOSED*** ∗
**• 046 COMPUTER**
047 CONTACT
**– D –**
**• 048 DAUGHTERS**
049 DELAYED
***• 050 DEN*** ∗
051 DESK
***• 052 DETECTOR*** ∗
***• 053 DINING*** ∗
054 DISCRIMINATOR
055 DISPLAY
**– L –**
***• 106 LAUNDRY*** ∗
**• 107 LEFT**
108 LEVEL
***• 109 LIBRARY*** ∗
**• 110 LIGHT**
111 LINE
***• 113 LIVING*** ∗
**• 114 LOADING**
115 LOCK
116 LOOP
117 LOW
**• 118 LOWER**
**– M –**
**• 119 MACHINE**
121 MAIDS
*122 MAIN* ∗
***• 123 MASTER*** ∗
***• 125 MEDICAL*** ∗
126 MEDICINE
128 MONEY
129 MONITOR
**• 130 MOTHERS**
***• 131 MOTION*** ∗
132 MOTOR
**– N –**
**• 134 NORTH**
135 NURSERY
**– O –**
***• 136 OFFICE*** ∗
***• 138 OPEN*** ∗
139 OPENING
**• 140 OUTSIDE**
142 OVERHEAD
**– P –**
143 PAINTING
***• 144 PANIC*** ∗
145 PASSIVE
***• 146 PATIO*** ∗
147 PERIMETER
**• 148 PHONE**
150 POINT
*151 POLICE* ∗
*152 POOL* ∗
**• 153 POWER**
**– V –**
209 VALVE
210 VAULT
212 VOLTAGE
**– W –**
213 WALL
214 WAREHOUSE
**• 216 WEST**
***• 217 WINDOW*** ∗
**• 219 WING**
220 WIRELESS
**– X –**
222 XMITTER
**– Y –**
223 YARD
**– Z –**
224 ZONE (No.)
***• 225 ZONE*** ∗
**• 226 0**
**• 227 1**
***• 228 1ST*** ∗
**• 229 2**
***• 230 2ND*** ∗
**• 231 3**
***• 232 3RD*** ∗
**• 233 4**
**• 234 4TH**
**• 235 5**
**• 236 5TH**
**• 237 6**
**• 238 6TH**
**• 239 7**
**• 240 7TH**
**• 241 8**
**• 242 8TH**
**• 243 9**
**• 244 9TH**
245 Custom Word #1
246 Custom Word #2
247 Custom Word #3
248 Custom Word #4
249 Custom Word #5
250 Custom Word #6
251 Custom Word #7
252 Custom Word #8
253 Custom Word #9
254 Custom Word #10
**– R –**
155 RADIO
**• 156 REAR**
157 RECREATION
159 REFRIGERATION
160 RF
**• 161 RIGHT**
***• 162 ROOM*** ∗
163 ROOF
**– S –**
164 SAFE
165 SCREEN
166 SENSOR
**• 167 SERVICE**
***• 168 SHED*** ∗
169 SHOCK
***• 170 SHOP*** ∗
171 SHORT
***• 173 SIDE*** ∗
174 SKYLIGHT
*175 SLIDING* ∗
***• 176 SMOKE*** ∗
**• 178 SONS**
**• 179 SOUTH**
180 SPRINKLER
**• 182 STATION**
184 STORE
***• 185 STORAGE*** ∗
186 STORY
*190 SUPERVISED* ∗
191 SUPERVISION
192 SWIMMING
193 SWITCH
**– T –**
194 TAMPER
196 TELCO
197 TELEPHONE
**• 199 TEMPERATURE**
200 THERMOSTAT
**• 201 TOOL**
202 TRANSMITTER
**– U –**
**• 205 UP**
**• 206 UPPER**
***• 207 UPSTAIRS*** ∗
***• 208 UTILITY*** ∗
***• 057 DOOR*** ∗
**• 059 DOWN**
**• 060 DOWNSTAIRS**
061 DRAWER
**• 062 DRIVEWAY**
**• 064 DUCT**
**– E –**
**• 065 EAST**
066 ELECTRIC
*067 EMERGENCY* ∗
068 ENTRY
**• 069 EQUIPMENT**
***• 071 EXIT*** ∗
072 EXTERIOR
**– F –**
**• 073 FACTORY**
075 FAMILY
**• 076 FATHERS**
**• 077 FENCE**
***• 079 FIRE*** ∗
***• 080 FLOOR*** ∗
081 FLOW
082 FOIL
**• 083 FOYER**
084 FREEZER
***• 085 FRONT*** ∗
**– G –**
***• 089 GARAGE*** ∗
**• 090 GAS**
091 GATE
**• 092 GLASS**
093 GUEST
094 GUN
**–** H –
***• 095 HALL*** ∗
**• 096 HEAT**
098 HOLDUP
*099 HOUSE* ∗
100 INFRARED
***• 101 INSIDE*** ∗
102 INTERIOR
103 INTRUSION
**– J –**
104 JEWELRY
**– K –**
***• 105 KITCHEN*** ∗

**Note:**
Bulleted ( **•** ) words in **boldface type** are those that are also available for use by the 4286 Phone Module. If using a
Phone module, and words other than these are selected for Alpha descriptors, the module will not provide
annunciation of those words.
*Italicized* words followed by an asterisk indicate those words supported by the 6160V/6150V Voice Keypads
**CHARACTER (ASCII) CHART (For Adding Custom Words)**

32 (space)
33
!
34
"
35
#
36
$
37
%
38
&
39
'
40
(
86
V
87
W
88
X
89
Y
90
Z
77
M
78
N
79
O
80
P
81
Q
82
R
83
S
84
T
85
U
68
D
69
E
70
F
71
G
72
H
73
I
74
J
75
K
76
L
59
;
60
<
61
=
62
>
63
?
64
@
65
A
66
B
67
C
50
2
51
3
52
4
53
5
54
6
55
7
56
8
57
9
58
:
41
)
42
*
43
+
44
,
45
–
46
.
47
/
48
0
49
1

**–** 31 **–**

---

## Page 32

**SETTING SCHEDULES**

**(Installer Code + [#] + [6] [4])**
The system provides schedules, which can be used to automatically control 11 types of system events at pre-defined times.
Some events are reserved for the installer only.
VISTA-20P:
Provides up to 32 schedules: 16 schedules for use by the end-user, 16 for use by the installer.
VISTA-15P:
Provides up to 8 schedules: 4 schedules for use by the end user, 4 for use by the installer.
**NOTES:**
• The master code can only access schedules 01-16 (VISTA-15P = 01-04) and events 00-07.
• System clock must be set before schedules can take effect.
• Programmed schedules do not take effect until the next scheduled “start” time. (e.g., if programming a schedule time window
for 8AM to 5PM, the schedule does not take effect until 8AM after the schedule has been programmed.)
**Schedule Mode**

Enter the desired schedule number.
**To Quit,** enter 00.
**Schedule Number**
VISTA-20P
01-16 = end-user schedules
17-32 = installer-only
VISTA-15P
01-04 = end-user schedules
05-08- = installer-only
[ ∗ ] to continue
ENTER SCHED NO.
00=QUIT
00

Enter the desired event number for event you want to occur at a
specified time.
Events 10-11 are reserved for the installer only.
Latch key report (option 03) is sent to all pagers in the user’s
partition and is active only when the system is armed (message
sent is 777-7777). User must be enabled for paging (see User
Attributes in ***System Operation*** section).
† Forced bypass is automatically enabled regardless of setting
in field *23.
†† If selected, system displays custom words 8, 9, and 10 at
defined time. Can be used as installer’s reminder message to
the end user.
†††  See key commands in Test Report Code data field *64
section to quickly set periodic test reporting intervals.
**Enter Event**
00 = clear event
01 = Relay On/Off
02 = User Access
03 = Latch Key Report to
Pager
04 = Forced Stay Arming †
05 = Forced Away Arming †
06 = Auto Disarm
07 = Display “Reminder”
10 = Display custom words ††
11 = Periodic Test Report †††
ENTER EVENT

Press [ ∗ ] to continue.

**NOTE:** Events 07 and 10 cause the keypad to beep every 30 seconds
when messages are displayed. Stop the beeps by pressing any key.

(For event 01-relay on/off)
Enter the physical device number as programmed in ∗ 79 Menu
Mode, then press [*] to continue to the “Start” prompt.
Device numbers 17 and 18 designate built-in triggers 1 and 2
respectively.
**Device Number**
V20P:
01-18 = device number
V15P: 01-08, 17, 18
Press [ ∗ ] to continue.
DEVICE NUMBER
XX

(For event 02-user access)
**Group Number**
1-8 = group number
Press [ ∗ ] to continue to the
“Start” prompt.
GROUP NUMBER
X

(V20P only; for events 03-07, 10)
**Partition**
0 = all partitions
1 = partition 1
2 = partition 2
3 = common
Press [*] to continue to the
“Start” prompt.
PARTITION
X

Enter the event’s start time and days of the week to occur.
To select days, position the cursor under the desired days using
the [ ∗ ] key to move forward, then press “1” to select the day.
**Start Time**
01-12 = hour
00-59 = minute
0 = AM; 1 = PM
Days = place “1” under days
Press [ ∗ ] to continue.
START    SMTW TFS
HH MMAM 0 0 1 0 0 0 0

(For events 01-relay on/off; 02-user access; 03-latch key report)
Enter the event’s stop time and days of the week to occur.
To select days, position the cursor under the desired days using
the [ ∗ ] key to move forward, then press “1” to select the day.
**Stop Time**
01-12 = hour
00-59 = minute
0 = AM; 1 = PM
Days = place “1” under days
Press [ ∗ ] to continue.
STOP    SMTW TFS
HH MMAM 0 0 1 0 0 0 0

– 32 –

---

## Page 33

Enter the desired repeat option for this schedule.
e.g., To make a schedule that happens everyday you would
select all days with a repeat count of 1. To make a schedule that
runs for one week then stops, select everyday with a repeat
count of 0.
**Repeat Option**
0 = do not repeat
1 = repeat weekly
2 = repeat biweekly (every
other week)
3 = repeat every third week
4 = repeat every fourth week
Press [ ∗ ] to continue.
REPEAT OPTION
0-4
X

(For events 01 and 11)
If selected, the scheduled start and stop times will vary within 60
minutes of the “hour” time. For example, if a schedule is set to
start at 6:15pm, it will do so the first time 6:15pm arrives, but on
subsequent days it will start anytime between 6:00 and 6:59 p.m.
**NOTE:** Do not use the random option if the start and stop times
are within the same “hour” setting, otherwise unpredictable
results may occur (e.g., the randomized stop time may occur
before the start time).
**AVS SYSTEM ENABLE and QUICK PROGRAMMING COMMANDS**
**Randomize**
0 = no
1 = yes
Press [ ∗ ] to continue and
return to ENTER SCHED
NO. prompt to program the
next schedule.
RANDOMIZE
0=NO  1=YES     X

Applies to an AVS system using an ECP connection to the control.
1. Install the AVS module according to its instructions.
2. Use one of the control’s AVS Quick Program commands as follows (see Quick Program Command Results below for
results of each command):

• **installer code + [#] + [0] + 3:** enable AVS operation without panel sounds on the AVST speaker
• **installer code + [#] + [0] + 4:** enable AVS operation and enable panel sounds on the AVST speaker
3. Use data field ∗ 55 Dynamic Signaling Priority to select the desired reporting paths (phone line and/or GSMV4G, GSMX4G)
and path for AAV communication.

4. To undo the Quick Command programming, use the following commands:
• **installer code + [#] + [0] + 5** : remove all options set by [#] + [0] + 3 quick command
• **installer code + [#] + [0] + 6** : remove all options set by [#] + [0] + 4 quick command


| Pre-Programmed | #03 Command |  | #04 Command |  |
| --- | --- | --- | --- | --- |
| Output Function No. (∗80 mode) | VISTA-15P series 22 (zone type 60, relay 07) 23 (zone type 61, relay 08) 24 (zone type 62, relay 08) | VISTA-20P series 46 (zone type 60, relay 15) 47 (zone type 61, relay 16) 48 (zone type 62, relay 16) | VISTA-15P series Same as #03 plus: 17 (zone type 14, relay 05) 18 (zone type 22, relay 05) 19 (zone type 39, relay 06) 20 (zone type 33, relay 06) 21 (zone type 36, relay 06) | VISTA-20P series Same as #03 plus: 41 (zone type 14, relay 13) 42 (zone type 22, relay 13) 43 (zone type 39, relay 14) 44 (zone type 33, relay 14) 45 (zone type 36, relay 14) |
| Output Relay No. (∗79 mode) | 07 (addr 08, relay pos 2) 08 (addr 08, relay pos 1) | 15 (addr 11, relay pos 2) 16 (addr 11, relay pos 1) | Same as #03 plus: 05 (addr 08, relay pos 4) 06 (addr 08, relay pos 3) | Same as #03 plus: 13 (addr 11, relay pos 4) 14 (addr 11, relay pos 3) |
| Protection Zone (∗56/∗58 mode) | 4229 zn 24 (zt 81, addr 08) | 4229 zn 48 (zt 81, addr 11) | Same as #03 command | Same as #03 command |
| Device Address | address 08 (AVS module) | address 11 (AVS module) | Same as #03 command | Same as #03 command |
| Data Field ∗91 | AAV enabled | AAV enabled | AAV enabled | AAV enabled |


**SETTING THE REAL-TIME CLOCK**
**IMPORTANT:** The Real-Time Clock must be set before the end of the installation.
**NOTE:** All partitions must be disarmed before the date/time can be set.
1.  Master Code +  [#]  +  [6] [3]
2. Press [ ∗ ] when the time/date is displayed.
A cursor appears under the first digit of the hour.
*To move cursor ahead, press [* ∗ *]. To go back, press [#].*
• Enter the 2-digit hour setting.
• Enter the 2-digit minute setting.
• Press [1] for PM or [2] for AM.
• Enter the last two digits of the current year.
• Enter the 2-digit month setting.
• Enter the 2-digit day setting.

3. To exit, press [ ∗ ] when cursor is at the last digit, or wait 30 seconds.

– 33 –

---

## Page 34

∗ **29 COMMUNICATION DEVICE MENU MODE** **(Pass-Through Programming)**
This mode is for programming an IP, GSM, or IP/GSM Communicator Module using an alpha keypad. Alternatively, these
options can be programmed via the AlarmNet Direct website. After programming is complete, the module must be registered
with AlarmNet before reporting via the communication device can occur. Refer to the device’s instructions for registration
procedures.

**NOTE:** The module must be set to device address 3.
**IMPORTANT:** The use of an IP/GSM Communicator Module
requires an AlarmNet–I account. Please obtain the account
information from the central station prior to programming this
module.

**Using an Alpha Keypad as a 7720P Programming Tool**
When programming with ∗ 29 menu mode, the alpha
keypad mimics the functions of the 7720P Programming
Tool. See figure to right and table below for 7720P key
functions. Each key has two possible functions: a normal
function and a SHIFT function.

**C**
**B**
**A**
**(A)**
3
STAY
2 AWAY
1
OFF
ARMED
**BS/ESC**
**E**
**D**
**F**
**(B)**
6 BYPASS
5
TEST
4
MAX
**/**
READY
**X**
**T**
**S**
**Normal functions:** The numeric values labeled directly
on the keys and the left-hand functions shown in
diagram on the ABC keys. To perform a normal key
function, simply press the desired key.
**(C)**
9 CHIME
8 CODE
7 INSTANT
**N / Y**
SHIFT
FUNCTION
WHEN LIT
**SPACE**
**ENTER**
**(D)**
**#**
0
**SHIFT**
READY
**SHIFT functions:** Those functions shown in diagram
above the numerical keys and the right-hand functions
shown on the ABC keys. To perform a SHIFT key
function, press SHIFT key (D key), then press the
desired function key (shift function is indicated by the lit
READY LED).
**7720P Emulation Template for Alpha Keypads**
6160-7720P-001-V0

∗ **29 IP/GSM Program Mode**
Press ∗ 29 while in Data Field Programming mode. The following prompts appear.

If using a communication device, enter 1 at this prompt and
enter 1-Prog at the next prompt to program the device. Use the
communication device’s Installation Guide for details of the
device’s programming prompts and instructions for registration.
**Fixed-Word Keypad Note:** Although programming IP/GSM
options cannot be done via a fixed-word keypad, IP/GSM can be
enabled by doing the following:
Enter ∗ **29** (to enter IP/GSM menu mode), then press **1 + [** ∗ **] + [** ∗ **]**
**Enable IP/GSM?**
0 = no, not using IP or GSM;
1 = yes using IP and/or
GSM module
[ ∗ ] to continue
[Default = 0 (no IP and/or GSM)]
ENABLE IP/GSM?
0=No, 1=Yes

Select whether you want to program the communication device
or enter the device’s diagnostic mode.
**Diagnostic Mode Note:** Diagnostic mode option available only
for communicators with firmware version 2.4.16 or higher.
**Programming /**
**Diagnostics Select**
1= Prog (program the
IP/GSM options)
2 = Diag (diagnostic mode)
0 = Quit; returns to data field
programming mode
1=PROG 2=DIAG
0=QUIT


| Key | Normal Key Function | SHIFT Key Function |
| --- | --- | --- |
| (A) = BS/ESC | [BS]: Press to delete entry Also, can reset EEPROM defaults † | [ESC]: Press to quit Program Mode |
| (B) = ↓/↑ | [↓]: Scroll down programming | [↑]: Scroll up programming |
| (C) = N/Y | [N]: Press for "NO" answer | [Y]: Press SHIFT-Y for "YES" answer |
| (D) = SHIFT | Press before pressing a SHIFT key function. Will light READY LED. LED goes out once a key is pressed. Press again for each SHIFT function desired. |  |
| 1/A | [1]: For entering the number 1 | [A]: Used for entering C.S. ID number |
| 2/B | [2]: For entering the number 2 | [B]: Used for entering C.S. ID number |
| 3/C | [3]: For entering the number 3 | [C]: Used for entering C.S. ID number |
| 4/D | [4]: For entering the number 4 | [D]: Used for entering C.S. ID number |
| 5/E | [5]: For entering the number 5 | [E]: Used for entering C.S. ID number |
| 6/F | [6]: For entering the number 6 | [F]: Used for entering C.S. ID number |
| 7/S | [7]: For entering the number 7 | [S]: Press to display diagnostic status |
| 8/T | [8]: For entering the number 8 | [T]: Press to send TEST messages |
| 9/X | [9]: For entering the number 9 | [X]: Press to reset the IP/GSM |
| [∗] / SPACE | [∗]: Used to select programming options | [SPACE]: Not used |
| 0 | [0]: For entering the number 0 |  |
| [#] / ENTER | [#] / ENTER: Press to accept entries | No SHIFT function |


– 34 –

---

## Page 35

**Registering the Communication Device with AlarmNet**
The communication device must be registered with AlarmNet before internet communication (via IP or GSM) can occur.

**Register Using the Alpha Keypad and** ∗ **29 Menu Mode**
1. Enter *29 Menu mode, select Diagnostic mode, then press Shift then [ ↑ ] key (D key followed by the B key). The
registration message is sent (“Registering” displayed) and the control waits for the acknowledgment.
2. “Registration SUCCESS” displayed, indicating successful registration.

**Or Register with AlarmNet Direct Website or by Phone**
To register via AlarmNet Direct Website, please go to:  https://services.alarmnet.com/AlarmNetDirect/userlogin.aspx.
To register by phone, call 1-800-222-6525. You will need the MAC ID and MAC CRC number and Subscriber information.
**Communication Device Status Report Codes**
The Communication Device sends status messages to the control panel for network connectivity failures. Trouble messages
are displayed on the keypad as “Check 103,” with status displayed as “LngRng Radio” followed by a 4-digit keypad display
status code, defined below.


| CODE | DESCRIPTION |
| --- | --- |
| 0000 | Control panel lost communication with internal device |
| 0005 | Communication device has lost contact with AlarmNet-G network |
| 000F | Communication device is not registered; account not activated |
| 0019 | GSM module shut down |
| 0400 | Communication device Power-on reset |


**UPLOADING/DOWNLOADING VIA the INTERNET**
**UL** : Up/downloading via the Internet has not been evaluated by UL.

This control, when used with a compatible Internet/Intranet Communication Device, supports upload/download programming
capability via the Internet using the AlarmNet network or, depending on the communication module used, a Private local area
network (Intranet). This allows site maintenance independent of central station monitoring, and modification to sites globally
via the Internet. Depending on the module used, Internet connection from the protected premises is either via high speed
(broadband) cable or phone service, or via the GSM/GPRS digital cellular network (GSM modules).

Refer to the instructions provided with the communication module for information regarding its installation, programming, and
registration. The System Requirements table below lists two sets of system requirements, depending upon whether you
intend to communicate over the Internet or whether you are communicating over a Private LAN (Intranet).


| Internet Communication At the Installation Site: • Appropriate Internet Communication Module • 7720P Programmer • Broadband Internet Access (for wired modules) • Broadband (Cable/DSL) Modem (for wired modules) • Broadband (Cable/DSL) Router (for wired modules if connecting more than one device to the Internet) • IP compatible Control Panel At the Downloading Office: • Broadband Internet Access • Broadband (Cable/DSL) Modem • Broadband (Cable/DSL) Router (optional, if connecting more than one device to the Internet) • Computer running Compass Downloading Software version that supports Internet upload/download for this control. | Intranet (Private LAN) Communication, if applicable* At the Installation Site: • Internet/Intranet Communication Module • 7720P Programmer • Ethernet Network Connection • IP compatible Control Panel At the Downloading Office: • 7810iR-ent IP Receiver and Internal Router • Computer(s) running the following software: - Compass Downloading Software version that supports IP upload/download for this control. - Compass Connect Data Server Application - Compass Connect Control Server Application * see module’s instructions for applicability for LAN usage NOTE: Compass, the Compass Connect Data Server, and the Compass Connect Control Server applications may all be installed on the same computer if desired. If they are installed on one computer, the computer must have a fixed IP Address. |
| --- | --- |


**To set up the control panel, do the following:**
1. Connect the communication device to the control panel’s ECP (keypad) terminals.
2. Internet Users: Connect the communication device to the Internet via a cable/DSL modem and router.
Intranet Users: Connect the communication device to the Intranet (LAN) via the appropriate Ethernet connection.
3. Enable the communication device (using ∗ 29 Menu mode) to enable alarm reporting and module supervision.
4. Using the communication device’s programming menus (via ∗ 29 Menu mode or 7720P programmer), program the
communication device for address 3 and program the device’s other options as required.
5. Register the communication device with AlarmNet. The communication device must be registered before downloading or
alarm reporting can take place.

**To perform upload/download functions:**
1. Connect the computer to the Internet and start the Compass downloading software.
2. Open the control’s account, then select the Communications function and click the Connect button.
3. At the Connect screen, check that the control’s MAC address is entered and the TCP/IP checkbox is checked.
4. Click Connect. The Internet connection to the control is made automatically via AlarmNet.
5. Once connected, use the Compass downloading software as normal to perform upload/download functions.

– 35 –

---

## Page 36

**ZONE TYPE DEFINITIONS**

Zone types define the way in which the system responds to faults in each zone.
**Type 00 Zone Not Used**
**Type 12 Monitor Zone**
• Works as a dynamic monitor of a zone fault/trouble (not alarm). In
the case of a short/open, the message, "*ALARM*-24 Hr. Non-Burg.
-#XXX " (where XXX is the zone number) will be sent to the Central
Station. The system keypad will display a “check” message
indicating the appropriate zone (but keypad beeping does not
occur). Upon restoral of the zone, the message, "*RESTORE*-24
Hr. Non-Burg. -#XXX " will be sent to the Central Station.
• The “check” message will automatically disappear from the keypad
dynamically, when the zone restores; a user code + off sequence is
not needed to reset the zone.
• Faults of this zone type are independent of the system, and can
exist at the time of arming without interference.
• Since this is a “trouble” zone type, do not use this zone type with
relays set to activate upon “alarm.”
**Type 14 24 Hour Carbon Monoxide Monitor**
• Assigned to any zone with a carbon monoxide detector.
• A carbon monoxide alarm produces keypad and detector sounding
(does not affect bell output).
• Always active and cannot be bypassed.
**Type 16 Fire w/Verification**
• Provides a fire alarm when zone is shorted, but only after the alarm
is verified to help eliminate false alarms due to electrical or physical
transients.
• Verifies alarm by resetting smoke detectors after short is detected
(removes power 7 seconds for zone 1, 3 seconds for trigger output).
Another short circuit within 90 seconds triggers fire alarm, otherwise
first alarm is ignored.
• Provides a trouble response when zone is open.
**Type 20 Arm-Stay (BR only)**
• Arms the system in Stay mode when the zone is activated.
• Pushbutton units send the user number to the central station when
arming or disarming.
• User number for button must be assigned.
**Type 21 Arm-Away (BR only)**
• Arms the system in Away mode when the zone is activated.
• Pushbutton units send the user number to the central station when
arming or disarming.
• User number for button must be assigned.
**Type 22 Disarm (BR only)**
• Disarms the system when the zone is activated.
• User number for button must be assigned.
**Type 23** * **No Alarm Response**
• Can be used on a zone when an output relay action is desired, but
with no accompanying alarm (e.g., lobby door access).
**Type 24 Silent Burglary**
• Usually assigned to all sensors or contacts on exterior doors and
windows where bells and/or sirens are NOT desired.
• Provides an instant alarm, with NO audible indication at any keypad
or external sounder, if the zone is faulted when the system is armed
in the Away, Stay, Instant, or Maximum modes.
• A report is sent to the central station.
**Type 77 Keyswitch**
• Assign to zone wired to a keyswitch.
• Do not use input type “BR” devices with this zone type.
**Type 81 AAV Monitor Zone (for AVS)**
• Assign to zone connected to AVS module.
• Monitors 2-way voice sessions as follows:
- When the zone is faulted, all alarm sounding and dialer reporting
stops, except for fire alarms, which immediately terminate the
voice session and cause a fire report to be sent.
- When the zone is restored (session ended), sounding resumes (if
bell timeout has not expired) and reports that were stopped are sent.
**Types 90-93 Configurable**
Program a zone with this zone type if the zone is not used.
**Type 01 Entry/Exit Burglary #1**
• Assign to zones that are used for primary entry and exit.
• Provides entry delay when zone is faulted if control is armed in
the Away, Stay, or Night-Stay modes.
• No entry delay provided when the panel is armed in the
Instant/Maximum mode.
• Entry delay #1 is programmable for each partition (field *35).
• Exit delay begins whenever the control is armed, regardless of
the arming mode selected, and is programmable (field ✱ 34).
**Type 02 Entry/Exit Burglary #2**
• Assign to zones that are used for entry and exit and require
more time than the primary entry/exit point.
• Provides a secondary entry delay, similar to entry delay #1.
• Entry delay #2 is programmable for each partition (field *36).
• Exit delay is same as described for Type 01.
**Type 03 Perimeter Burglary**
• Assign to all sensors or contacts on exterior doors and windows.
• Provides an instant alarm if the zone is faulted when the panel is
armed in the Away, Stay, Night-Stay, Instant or Maximum modes.
**Type 04 Interior Follower**
• Assign to a zone covering an area such as a foyer, lobby, or
hallway through which one must pass upon entry (to and from
the keypad).
• Provides a delayed alarm (using the programmed entry 1 time)
if the entry/exit zone is faulted first. Otherwise this zone type
gives an instant alarm.
• Active when the panel is armed in the Away mode.
• Bypassed automatically when the panel is armed in the Stay or
Instant modes; if armed in Night-Stay mode, zones assigned to
zone list 05 (night-stay zone list) are not bypassed when
system armed in Night-Stay mode.
**Type 05 Trouble by Day/Alarm by Night**
• Assign to a zone that contains a foil-protected door or window
(such as in a store), or to a zone covering a sensitive area such
as a stock room, drug supply room, etc.
• Can also be used on a sensor or contact in an area where
immediate notification of an entry is desired.
• Provides an instant alarm if faulted when armed in the Away,
Stay, Night-Stay, Instant or Maximum (night) modes.
• During the disarmed state (day), the system will provide a
latched trouble sounding from the keypad (and a central station
report, if desired).
**Type 06 24-hr Silent Alarm**
• Usually assigned to a zone containing an emergency button.
• Sends a report to the central station but provides no keypad
display or sounding.
**Type 07 24-hour Audible Alarm**
• Assign to a zone that has an emergency button.
• Sends a report to the central station, and provides an alarm
sound at the keypad, and an audible external alarm.
**Type 08 24-hour Auxiliary Alarm**
• Assign to a zone containing an emergency button, or to a zone
containing monitoring devices such as water or temperature
sensors.
• Sends a report to the central station and provides an alarm
sound at the keypad. (No bell output.)
**Type 09 Supervised Fire**
• Provides a fire alarm on short circuit and a trouble condition on
open circuit. A fire alarm produces a pulsing bell output.
• This zone type is always active and cannot be bypassed.
**Type 10 Interior w/Delay**
• Provides entry delay (using the programmed entry time), if
tripped when the panel is armed in the Away mode.
• Entry Delay 1 begins whenever sensors in this zone are
violated, regardless of whether or not an entry/exit delay zone
was tripped first.
• Bypassed when the panel is armed in the Stay or Instant
modes; if armed in Night-Stay mode, zones assigned to zone
list 05 (night-stay zone list) are not bypassed when system
armed in Night-Stay mode.

Allows for various custom responses. Options include response to
entry/exit delays, response opens/shorts, types of alarm/trouble
sounding, dial delay, and unique Contact ID report codes. Types 92
and 93 can only be programmed via downloader. UL installations:
Zone Types 90 -93 may not be used as fire or burglar alarm zones on
fire or UL burglar alarm installations.

* The system can still be armed when these zone types are in a
faulted condition.

– 36 –

---

## Page 37

**REPORT CODE FORMATS**


| FORMAT TYPE | DESCRIPTION |
| --- | --- |
| 3+1 and 4+1 Standard Formats Ex. SSS(S) A | Comprises a 3- (or 4-) digit subscriber number and a single-digit report code (e.g., Alarm, Trouble, Restore, Open, Close, etc). Ex. S = Subscriber ID; A = Report Code |
| 3+1 and 4+1 Expanded Formats Ex. SSS(S) A AAA(A) Z | Comprises a 3- (or 4-) digit subscriber number and a two-digit report code. The first digit is displayed on the first line. The first digit is repeated on the second line 3 (or 4) times followed by the second, “expanded” digit. Ex. S = Subscriber ID; A = Report Code–1st digit; Z = Typically Zone Number–2nd digit |
| 4+2 Format Ex. SSSS AZ | Comprises a 4-digit subscriber number and 2-digit report code. Ex. S = Subscriber ID; A = Report Code; Z = Typically Zone Number) |
| ADEMCO Contact ID Reporting Format Ex. CCCC Q EEE GG ZZZ | Comprises a 4- or 10-digit subscriber number (depending on format selected), 1-digit event qualifier (“new” or “restore”), 3-digit event code, and 3-digit zone number, user number, or system status number (see below for example explanation). |



| Code | Definition |
| --- | --- |
| 110 | Fire Alarm |
| 121 | Duress |
| 122 | Alarm, 24-hour Silent |
| 123 | Alarm, 24-hour Audible |
| 131 | Alarm, Perimeter |
| 132 | Alarm, Interior |
| 134 | Alarm, Entry/Exit |
| 135 | Alarm, Day/Night |
| 143 | Alarm, Expansion Module |
| 145 | ECP Module cover tamper |
| 146 | Silent Burglary |
| 150 | Alarm, 24-Hour Auxiliary/Monitor zone |
| 162 | Carbon Monoxide |
| 301 | AC Power |
| 302 | Low System Battery/Battery Test Fail |
| 305 | System Reset (Log only) |
| 321 | Bell/Siren Trouble |
| 333 | Trouble, Expansion Mod. Supervision |
| 341 | Trouble, ECP Cover Tamper |
| 344 | RF Receiver Jam |
| 351 | Telco Line Fault |
| 353 | Long Range Radio Trouble |
| 354 | Failure to Communicate (log only) |
| 373 | Fire Loop Trouble |
| 374 | Exit Error Alarm |
| 380 | Global Trouble, Trouble Day/Night |
| 381 | RF Sensor Supervision |
| 382 | Supervision Auxiliary Wire Zone |


| Code | Definition |
| --- | --- |
| 383 | RF Sensor Tamper |
| 384 | RF Sensor Low-battery |
| 393 | Clean Me |
| 401 | Disarmed, Armed AWAY, Armed MAXIMUM |
| 403 | Schedule Arm/Disarm AWAY |
| 406 | Cancel by User |
| 407 | Remote Arm/Disarm (Downloading) |
| 408 | Quick Arm AWAY |
| 409 | Keyswitch Arm/Disarm AWAY |
| 441 | Disarmed/Armed STAY/INSTANT, Quick-Arm STAY/INSTANT |
| 442 | Keyswitch Arm/Disarm STAY |
| 455 | Scheduled Arm Fail |
| 459 | Recent Closing (SIA panels only) |
| 570 | Bypass |
| 601 | Manually Triggered Dialer Test |
| 602 | Periodic Test |
| 606 | AAV to Follow |
| 607 | Walk Test Entered/Exited |
| 623 | Event Log 80% Full |
| 625 | Real-Time Clock was Changed (log only) |
| 627 | Program Mode Entry (log only) |
| 628 | Program Mode Exit (log only) |
| 642 | Latch Key (log only) |
| 750 - 789 | Reserved for Configurable Zone Type report codes (check with central station when using these codes) |


– 37 –

---

## Page 38

**SYSTEM SECURITY CODES**


| Level | User No. | Functions |
| --- | --- | --- |
| Installer | 01 | (default=4112) perform all security functions except can disarm only if used to arm; can enter program mode; can change System Master code; cannot assign any other user codes NOTE: For security purposes, the factory default installer code should be changed. |
| System Master | 02 | (default 1234) only one system master code per system; can perform all security functions, add/delete users in either partition, change system master code, view event log, set system clock, program keypad macro, program scheduled events, activate output devices (triggers/relays) |
| Partition Master (default) | P1 = 03 P2 = 33 | VISTA-20P. Same as Master, except add/delete users limited to assigned partition only, (these users can be assigned different authority levels, if desired; any user can be assigned the partition master authority level) |
| 0-User | 03-49 (V20P) 03-33 (V15P) | perform security functions (arm, disarm, etc.) only; cannot add/delete users, view event log, set system clock or program scheduled events |
| 1-Arm Only | see “user” | arm system only |
| 2-Guest | see “user” | can disarm the system only if it was used to arm the system |
| 3-Duress | see “user” | performs security functions, but also silently sends a duress message to the central station; reports as duress code user number. |
| 4-Partition Master | see “user” | VISTA-20P. See Partition Master paragraph above; used to assign other user numbers as partition masters |


Refer to the user guide for detailed procedures on adding/deleting security codes and changing user attributes.
The following is a brief description of how to add user codes.
**Changing the System Master code:**
Using Installer code: Installer code + [8] + 02 + new code
Using current System Master code: System Master code + [8] + 02 + new code + new code again
**Adding a User Code:**
Master code + [8] + 2-digit user no. + user’s code
**Deleting a User Code:**
Master code + [8] + 2-digit user no. + [#] [0]
**Assigning Attributes:**
Master code + [8] + 2-digit user no. + [#] [attribute no.] + value
**Attributes:**
**Values**
1 =
Authority Level
0-4 (see Authority Level table above)
2 =
Access Group
0-8 (0 = not assigned to a group)
3 =
Active Partition(s)
1, 2, 3 (common)
for this user;
Enter partitions consecutively if more than one and press [#] to end the entries.
4 =
RF Zone No.
Assigns user number to button type zone for arm/disarm ( **keyfob must be**
**enrolled in system first** ; see ***Wireless Key Templates*** section).
**Deactivating a key fob:** You can deactivate the arming/disarming functions for a
key fob (ex. if lost or stolen) by deleting the associated key fob user. See “Delete
a User” above. Other key fob functions such as panic or device activation (if
programmed) remain active. To fully remove the programming for a key fob,
delete the zone(s) associated with the key fob functions.
**IMPORTANT SECURITY NOTICE**
Please inform the User about the security importance of their key fob, and what to
do if it is lost.
Explain that the key fob is similar to their keys or access card. If lost or stolen,
another person can compromise their security system. They should immediately
notify the Dealer/Installer of a lost or stolen key fob. The Dealer/Installer will then
remove the key fob programming from the security system.

5 =
Open/Close Paging
1 for yes, 0 for no

– 38 –

---

## Page 39

**KEYPAD FUNCTIONS**


| Function | Description |
| --- | --- |
| Silence Burglary Alarms | Pressing any key will silence the keypad sounder for 10 seconds. Disarming the system (security code + OFF) silences both keypad and external sounders. |
| Silence Fire or Carbon Monoxide Alarms | Press the OFF [1] key to silence the keypad sounder and, for fire alarms, the external sounder. |
| Quick Arm | If enabled (field ∗21), you can press [#] in place of the system's security code, plus the desired arming key (Away, Stay, Instant, Maximum) |
| Single-Button arming | If programmed (*57 Function Key menu mode), lettered keys A-D can be used for arming, using options 3-AWAY, 4-STAY, 5-NIGHT-STAY, or 6-Step-Arming |
| Alarm Memory | When the system is disarmed, any zones that were in an alarm condition during the armed period will be displayed. To clear this display, simply repeat the disarm sequence (enter the security code and press the OFF key) again. |
| Arming Away | Enter code + AWAY [2] or simply press appropriate lettered key on the keypads. If the “Auto- Stay Arm” feature is enabled (field *84) and the entry/exit door is not opened and closed within the programmed exit delay time, the system will automatically arm in STAY mode if armed from a wired keypad (non-RF device). If the door is opened and closed within the exit delay period, the system arms in AWAY mode. |
| Arming Stay | Enter code + STAY [3] or simply press appropriate key on the keypads (see “Single-Button Arming” above). See “Arming Away” above for Auto-Stay arming feature. |
| Arming Night-Stay | Enter code + STAY [3] + STAY [3] or simply press appropriate key on the keypads (see “Single-Button Arming” above). |
| Arming Instant | Enter code + INSTANT [7]. |
| Arming Maximum | Enter code + MAXIMUM [4] or simply press appropriate lettered key on the keypads (see “Single-Button Arming” above). |
| Disarming | Enter code + OFF [1]. If entry delay or an alarm is active, you do not need to press OFF. |
| Bypassing Zones | Enter code + BYPASS [6] + zone number(s). |
| Forced (Quick) Bypass | To automatically bypass all faulted zones, use the “Quick Bypass” method. Enter code + BYPASS + [#], then wait for all open zones to be displayed. Arm when display indicates “ZONE BYPASSED” and “READY TO ARM”. |
| Chime Mode | Enter code + CHIME [9]. To turn chime off, enter code + CHIME again. |
| Activate Output Devices | [Security Code] + # + 7 + [2-digit Device #] activates (starts) that device. [Security Code] + # + 8 + [2-digit Device #] deactivates (stops) that device. |


**COMPATIBLE DEVICES**


| 2-Wire Smoke Detectors |  |
| --- | --- |
| Detector Type | Model No. |
| Photoelectric w/heat sensor | System Sensor 2WT-B |
| Photoelectric | System Sensor 2W-B |
| Photoelectric | System Sensor 2151 w/B110LP base |
| Photoelectric | Napco FW-2S |
| Keypads |  |
| Fixed-Word Keypad | 6150 |
| Alpha Keypad | 6160 |
| Voice Keypads | 6150V, 6160V |
| Touch Screen Keypad | 6272, 6280, TUXEDO |
| Wireless Receivers |  |
| Up to 8 transmitters | 5881L/5882L |
| Up to 16 transmitters | 5881M/5882M |
| Up to system max transmitters | 5881H/5882H |
| Transmitter Module | 5800TM |
| Up to system max transmitters | 5883 |
| Keypad/Receivers |  |
| Up to 16 trans, fixed-word | 6150RF |
| Up to system max trans, alpha | 6160RF |
| Modules |  |
| Wired Expander Module | 4219 |
| Wired Expander/Relay Module | 4229 |
| Relay Module | 4204 |
| Phone Module | 4286VIP |
| Communication Device | GSMV4G, GSMX4G, IGSMV4G etc. |
| Transformers |  |
| 25VA, 16.5VAC Plug-In Trans. | 1321 (1321CN in Canada) |
| 40VA, 16.5VAC Powerline Carrier Device Interface AC Transformer | 1361X10 |


– 39 –

---

## Page 40

**VARIOUS SYSTEM TROUBLE DISPLAYS**

| Alpha Display | Fixed Disp. | Meaning |
| --- | --- | --- |
| ALARM CANCELED | CA | Will appear if an exit or interior zone contained a fault during closing at the time the Exit Delay ended (e.g., exit door left open), but the system was disarmed during the Entry Delay time. The alarm sounder and keypad sound continuously, but stop when the system is disarmed. No message will be transmitted to the central station. |
| EXIT ALARM | EA | Appears when Exit Delay ends if an exit or interior zone contained a fault during closing. The alarm sounder and keypad sound continuously until the system is disarmed (or timeout occurs). An “Exit Alarm” message is sent to the central station. Also results if an alarm from an exit or interior zone occurs within 2 minutes after the end of an Exit Delay. |
| CHECK | CHECK | Indicates that a problem exists with the displayed zone(s) and requires attention. |
| ALARM 1xx FAULT 1xx CHECK 1xx | 1xx 1xx 1xx 91 | Indicates that communication between control and a zone expander or wireless receiver is interrupted, where “xx” is the device address. Check the wiring and DIP switch settings on the units. If field *199 is set to “1,” all ECP module problems are displayed as “91.” If there are wireless sensors in the system, the Check condition may also be caused by some change in the environment that prevents the receiver from receiving signals from a particular sensor. |
| SYSTEM LO BAT | BAT | With no zone number indicates that the system's standby battery is weak. |
| LO BAT | BAT | With a zone number and about twice-per-minute beeping at the keypad indicates that a low-battery condition exists in the wireless sensor displayed (zone “00” indicates a wireless keypad). If the battery is not replaced within 30 days, a “CHECK” display may occur. NOTE: Some wireless sensors contain a non-replaceable long-life battery which requires replacement of the entire unit at the end of battery life (e.g., Nos. 5802, 5802CP). |
| TELCO FAULT | 94 | Telephone Line Failure, indicates that a monitored telephone line (if programmed in field *92) has been cut or disconnected. Depending on how the system was programmed, the keypad may also produce a trouble sound, and the external sounder may be activated. Silence by entering installer code + OFF. |
| Busy-Standby | dl | If this remains displayed for more than 1 minute, the system is disabled. NOTE for CANADIAN PANELS: Power up time is 2 minutes, and CID code 305 System Reset is sent if the [#] + [0] command is not performed before the 2 minutes expires. |
| Modem Comm | CC | The system is in communication with the central station for change of function or status verification. |
| no display | no display | Power Failure If there is no keypad display at all and the LEDs are unlit, operating power (AC and battery) for the system has stopped and the system is inoperative. If the message “AC LOSS” (Alpha display keypads) or “NO AC” (Fixed-Word display keypads) is displayed, the keypad is operating on battery power only. If the battery standby capacity is used up during a prolonged AC power outage, the control's power will shut down to minimize deep discharge of the battery. |
| Comm. Failure | FC | A communication failure has occurred. |
| Open Circuit | 0C | The keypad is not receiving signals from the control; sees an open circuit. |
| Long Rng Trbl | bF | Backup communication device (LRR) had communication failure. |
| Bell Failure | 70 | Bell supervision failure. |
| RCVR Jam | 90 | RF jam detected. |
| KEYPAD LOW BAT | 00 BAT | Wireless keypad low battery. |
| Phone Okay | Cd | The dialer test has been successful (CID code 601). |
| Dialer Off | d0 | The dialer is disabled. |
| Test in Progress | dd | Walk test mode is active (CID code 607). |
| Upload Completed | dC | The upload or download session was completed. |
| Upload Failed | dF | The upload or download session failed before completion. |


– 40 –

---

## Page 41

**UL NOTICES**
1. Entry Delay No. 1 and No. 2 (fields ∗ 35, ∗ 36) cannot be greater than 30 seconds for UL Residential Burglar Alarm installations, and

entry delay plus dial delay should not exceed 1 minute. For UL Commercial Burglar Alarm installations, total entry delay may not
exceed 45 seconds.
2. For UL Commercial Burglar Alarm and UL Residential Burglar Alarm installations with line security, total exit delay time must not

exceed 60 seconds.
3. The maximum number of reports per armed period (field ∗ 93) must be set to “0” (unlimited) for UL installations.
4. Periodic testing (see scheduling mode) must be at least every 24 hours.
5. Alarm Sounder plus Auxiliary Power currents must not exceed 600mA total for UL installations (Aux power 500mA max.).
6. All partitions must be owned and managed by the same person(s).
7. All partitions must be part of one building at one street address.
8. If used, the audible alarm device(s) must be placed where it/they can be heard by all partitions.
9. For UL commercial burglar alarm installations the control unit must be protected from unauthorized access. The tamper switch

installed to protect the control unit enclosure door is suitable for this purpose.
10. Remote downloading without an alarm company technician on-site (unattended downloading) is not permissible for UL installations.
11. Auto-disarming is not a UL Listed feature.
12. As SIA limits for delay of alarm reporting and sounding can exceed UL limits for commercial and residential applications, the following

UL requirements per UL681 are provided:
The maximum time that a control unit shall be programmed to delay the transmission of a signal to a remote monitoring location, or to
delay the energizing of a local alarm sounding device to permit the alarm system user to enter and disarm the system, or to arm the
system and exit shall not exceed:
a) 60 seconds for a system with standard line security or encrypted line security,
b) 120 seconds for a system without standard line security or encrypted line security, or
c) 120 seconds for a system that does not transmit an alarm signal to a remote monitoring location.
13. This control is not intended for bank safe and vault applications.

**SIA QUICK REFERENCE GUIDE**
1. ∗ 31 Single Alarm Sounding per Zone: If “0” selected, “alarm sounding per zone” will be the same as the “number of reports in armed

period” set in field ∗ 93 (1 if one report, 2 if 2 reports, unlimited for zones in zone list 7).
2. ∗ 34 Exit Delay: Minimum exit delay is 45 seconds.
3. ∗ 35/*36 Entry Delay 1 and 2: Minimum entry delay is 30 seconds.
4. ∗ 37 Audible Exit Warning: Feature always enabled; field does not exist.
5. ∗ 39 Power Up in Previous State: Must be “1,” power up in previous state.
6. ∗ 40 PABX Access Code or Call Waiting Disable: If call waiting is used, call waiting disable option in field *91 must be set.
7. ∗ 50 Burglary Dial Delay: Delay must be minimum of 30 seconds.
8. ∗ 59 Exit Error Alarm Report Code: Always enabled.
9 ∗ 68 Cancel Report Code: Default is “code enabled.”
10. ∗ 69 Recent Closing Report Code: Always enabled.
11. ∗ 91 Option Selection: Exit Delay option should be enabled. If call waiting is used, Call Waiting Disable must be set to “1” (enabled).
12. ∗ 93 No. reports in Armed Period: Must be set for 1 or 2 report pairs.
13. Cross zone timer programming is set in field ∗ 85; cross zone pairs are assigned in zone list 4 using ∗ 81 Zone List mode.
14. Duress code is assigned by using the “add a user code” procedure found in the User Guide. Enable Duress code reporting by

programming zone 92 using ∗ 56 Zone Programming mode.
15. Fire alarm verification is a built-in system feature when a zone is programmed for zone type 16.
**ULC S304 REQUIREMENTS (for VISTA-15PCN and VISTA-20PCN)**

Refer to the following notes for systems intended for Low Risk Level (low extent of protection) and Medium Risk Level (medium extent of
protection) installations.
**Low Risk Level**
If the panel is used for Low Risk Level installations, the system must include the following:
• Subscriber control unit may use one telephone number, but it must be programmed that
a)
it transmits over the single channel to the receiver once every 24 hour;
b)
it detects a loss of communication and initiates the local trouble signal within 180 seconds;
c)
in event of failure in the communication channel, all alarm and trouble signals must be annunciated locally.
• Protection circuit conductors shall form one fully supervised circuit so arranged that an alarm signal will be initiated at the central
station from the effect of loss data, an open circuit or other change in normal status.
• Trouble response time must be in compliance with CAN/ULC-S301, Central and Monitoring Station Burglar Alarm Systems
**Medium Risk Level**
If the panel is used for Medium Risk Level installations, the system must include the following:
• Subscriber control unit may use at least two communication levels, one being the telephone number and the other being a radio
frequency communication channel – the GSM communicator may be used. The Subscriber control unit must be programmed that
a)
it transmits over the both channels to the receiver once every 24 hours;
b)
failure of communication of either channel is reported to the Central Station on the other channel within 240 sec;
c)
the first attempt to send a status change signal shall utilize the Telephone line. Where it is known to have failed, transmission
attempts over the alternate communication channel shall occur.
• Protection circuit conductors shall form double fully supervised circuits so arranged that an alarm signal will be initiated at the central
station from the effect of loss data, an open circuit or other change in normal status.
• Trouble response time must be in compliance with CAN/ULC-S301, Central and Monitoring Station Burglar Alarm Systems
**Perimeter, Space, Safe, and Vaults Protection**
Protection for perimeter, space, safe, and vaults need to be provided during the installation.
• For the Low Risk Security Level – Accessible openings should be contacted whether fixed or moveable;
• For the Medium Risk Security Level – All moveable and fixed accessible openings should be contacted.

– 41 –

---

## Page 42

**FCC STATEMENTS**
**FEDERAL COMMUNICATIONS COMMISSION (FCC) Part 15**
The user shall not make any changes or modifications to the equipment unless authorized by the Installation Instructions or User's Manual.
Unauthorized changes or modifications could void the user's authority to operate the equipment.

**CLASS B DIGITAL DEVICE STATEMENT**
This equipment has been tested to FCC requirements and has been found acceptable for use. The FCC requires the following statement for
your information:

This equipment generates and uses radio frequency energy and if not installed and used properly, that is, in strict accordance with the
manufacturer's instructions, may cause interference to radio and television reception. It has been type tested and found to comply with the
limits for a Class B computing device in accordance with the specifications in Part 15 of FCC Rules, which are designed to provide
reasonable protection against such interference in a residential installation. However, there is no guarantee that interference will not occur in
a particular installation. If this equipment does cause interference to radio or television reception, which can be determined by turning the
equipment off and on, the user is encouraged to try to correct the interference by one or more of the following measures:
• If using an indoor antenna, have a quality outdoor antenna installed.
• Reorient the receiving antenna until interference is reduced or eliminated.
• Move the radio or television receiver away from the receiver/control.
• Move the antenna leads away from any wire runs to the receiver/control.
• Plug the receiver/control into a different outlet so that it and the radio or television receiver are on different branch circuits.
• Consult the dealer or an experienced radio/TV technician for help.
This Class B digital apparatus complies with Canadian ICES-003.
Cet appareil numérique de la classe B est conforme à la norme NMB-003 du Canada.

**FCC/IC STATEMENT**
This device complies with Part 15 of the FCC rules and RSS 210 of Industry Canada. Operation is subject to the following two conditions: (1)
This device may not cause harmful interference, and (2) This device must accept any interference received, including interference that may
cause undesired operation.
Cet appareil est conforme à la partie 15 des règles de la FCC & de RSS 210 des Industries Canada. Son fonctionnement est soumis aux
conditions suivantes: (1) Cet appareil ne doit pas causer d' interférences nuisibles. (2) Cet appareil doit accepter toute interférence reçue y
compris les interférences causant une réception indésirable.

**TELEPHONE/MODEM INTERFACE**
**FCC Part 68**
This equipment complies with Part 68 of the FCC rules.  On the front cover of this equipment is a label that contains the FCC registration
number and Ringer Equivalence Number (REN).  You must provide this information to the telephone company when requested.

This equipment uses the following USOC jack: RJ31X
This equipment may not be used on telephone-company-provided coin service.  Connection to party lines is subject to state tariffs.  This
equipment is hearing-aid compatible.

**Industry Canada**
**NOTICE** : The Industry Canada Label identifies certified equipment. This certification means that the equipment meets telecommunications
network protective, operational and safety requirements as prescribed in the appropriate Terminal Equipment Technical Requirements
document(s). The Department does not guarantee the equipment will operate to the user’s satisfaction.

Before installing this equipment, users should ensure that it is permissible to be connected to the facilities of the local telecommunications
company. The equipment must also be installed using an acceptable method of connection. The customer should be aware that compliance
with the above conditions may not prevent degradation of service in some situations.

Repairs to certified equipment should be coordinated by a representative designated by the supplier. Any repairs or alterations made by the
user to this equipment, or equipment malfunctions, may give the telecommunications company to request the user to disconnect the
equipment.

Users should ensure for their own protection that the electrical ground connections of the power utility, telephone lines and internal metallic
water pipe system, if present, are connected together, This precaution may be particularly important in rural areas.

**Caution** : Users should not attempt to make such connections themselves but should contact appropriate electric inspection authority, or
electrician, as appropriate.

**Ringer Equivalence Number Notice:**
The **Ringer Equivalence Number** (REN) assigned to each terminal device provides an indication of the maximum number of terminals
allowed to be connected to a telephone interface.  The termination on an interface may consist of any combination of devices subject only to
the requirement that the sum of the Ringer Equivalence Numbers of all the devices does not exceed 5.

**Industrie Canada**
**AVIS:** l’étiquette d’Industrie Canada identifie le matériel homologué. Cette étiquette certifie que le matériel est conforme aux normes de
protection, d’exploitation et de sécurité des réseaux de télécommunications, comme le prescrivent les documents concernant les exigences
techniques relatives au matériel terminal. Le Ministère n’assure toutefois pas que le matériel fonctionnera à la satisfaction de l’utilisateur.

Avant d’installer ce matériel, l’utilisateur doit s’assurer qu’il est permis de le raccorder aux installations de l’enterprise locale de
télécommunication. Le matériel doit également être installé en suivant une méthode acceptée da raccordement. L’abonné ne doit pas oublier
qu’il est possible que la conformité aux conditions énoncées ci-dessus n’empêche pas la dégradation du service dans certaines situations.

Les réparations de matériel nomologué doivent être coordonnées par un représentant désigné par le fournisseur. L’entreprise de
télécommunications peut demander à l’utilisateur da débrancher un appareil à la suite de réparations ou de modifications effectuées par
l’utilisateur ou à cause de mauvais fonctionnement.

Pour sa propre protection, l’utilisateur doit s’assurer que tous les fils de mise à la terre de la source d’energie électrique, de lignes
téléphoniques et des canalisations d’eau métalliques, s’il y en a, sont raccordés ensemble. Cette précaution est particulièrement importante
dans les régions rurales.

**Avertissement :** L’utilisateur ne doit pas tenter de faire ces raccordements lui-même; il doit avoir racours à un service d’inspection des
installations électriques, ou à un électricien, selon le cas.

**AVIS : L’indice d’équivalence de la sonnerie** (IES) assigné à chaque dispositif terminal indique le nombre maximal de terminaux qui
peuvent être raccordés à une interface. La terminaison d’une interface téléphonique peut consister en une combinaison de quelques
dispositifs, à la seule condition que la somme d’indices d’équivalence de la sonnerie de tous les dispositifs n’excède pas 5.

– 42 –

---

## Page 43

**LIMITATIONS STATEMENT**
**WARNING**
**THE LIMITATIONS OF THIS ALARM SYSTEM**
While this System is an advanced design security system, it does not offer guaranteed protection against burglary, fire or other
emergency. Any alarm system, whether commercial or residential, is subject to compromise or failure to warn for a variety of reasons.
For example:
•
Intruders may gain access through unprotected openings or have the technical sophistication to bypass an alarm sensor or
disconnect an alarm warning device.
•
Intrusion detectors (e.g., passive infrared detectors), smoke detectors, and many other sensing devices will not work without
power. Battery-operated devices will not work without batteries, with dead batteries, or if the batteries are not put in properly.
Devices powered solely by AC will not work if their AC power supply is cut off for any reason, however briefly.
•
Signals sent by wireless transmitters may be blocked or reflected by metal before they reach the alarm receiver. Even if the signal
path has been recently checked during a weekly test, blockage can occur if a metal object is moved into the path.
•
A user may not be able to reach a panic or emergency button quickly enough.
•
While smoke detectors have played a key role in reducing residential fire deaths in the United States, they may not activate or
provide early warning for a variety of reasons in as many as 35% of all fires, according to data published by the Federal
Emergency Management Agency. Some of the reasons smoke detectors used in conjunction with this System may not work are
as follows. Smoke detectors may have been improperly installed and positioned. Smoke detectors may not sense fires that start
where smoke cannot reach the detectors, such as in chimneys, in walls, or roofs, or on the other side of closed doors. Smoke
detectors also may not sense a fire on another level of a residence or building. A second floor detector, for example, may not
sense a first floor or basement fire. Finally, smoke detectors have sensing limitations. No smoke detector can sense every kind of
fire every time. In general, detectors may not always warn about fires caused by carelessness and safety hazards like smoking in
bed, violent explosions, escaping gas, improper storage of flammable materials, overloaded electrical circuits, children playing
with matches, or arson. Depending on the nature of the fire and/or location of the smoke detectors, the detector, even if it operates
as anticipated, may not provide sufficient warning to allow all occupants to escape in time to prevent injury or death.
•
Passive Infrared Motion Detectors can only detect intrusion within the designed ranges as diagrammed in their installation manual.
Passive Infrared Detectors do not provide volumetric area protection. They do create multiple beams of protection, and intrusion
can only be detected in unobstructed areas covered by those beams. They cannot detect motion or intrusion that takes place
behind walls, ceilings, floors, closed doors, glass partitions, glass doors, or windows. Mechanical tampering, masking, painting or
spraying of any material on the mirrors, windows or any part of the optical system can reduce their detection ability. Passive
Infrared Detectors sense changes in temperature; however, as the ambient temperature of the protected area approaches the
temperature range of 90° to 105°F (32° to 40°C), the detection performance can decrease.
•
Alarm warning devices such as sirens, bells or horns may not alert people or wake up sleepers if they are located on the other
side of closed or partly open doors. If warning devices are located on a different level of the residence from the bedrooms, then
they are less likely to waken or alert people inside the bedrooms. Even persons who are awake may not hear the warning if the
alarm is muffled by noise from a stereo, radio, air conditioner or other appliance, or by passing traffic. Finally, alarm warning
devices, however loud, may not warn hearing-impaired people.
•
Telephone lines needed to transmit alarm signals from a premises to a central monitoring station may be out of service or
temporarily out of service. Telephone lines are also subject to compromise by sophisticated intruders.
•
Even if the system responds to the emergency as intended, however, occupants may have insufficient time to protect themselves
from the emergency situation. In the case of a monitored alarm system, authorities may not respond appropriately.
•
This equipment, like other electrical devices, is subject to component failure. Even though this equipment is designed to last as
long as 10 years, the electronic components could fail at any time.
The most common cause of an alarm system not functioning when an intrusion or fire occurs is inadequate maintenance. This alarm
system should be tested weekly to make sure all sensors and transmitters are working properly. The security keypad (and remote
keypad) should be tested as well.
Wireless transmitters (used in some systems) are designed to provide long battery life under normal operating conditions. Longevity
of batteries may be as much as 4 to 7 years, depending on the environment, usage, and the specific wireless device being used.
External factors such as humidity, high or low temperatures, as well as large swings in temperature, may all reduce the actual battery
life in a given installation. This wireless system, however, can identify a true low-battery situation, thus allowing time to arrange a
change of battery to maintain protection for that given point within the system.
Installing an alarm system may make the owner eligible for a lower insurance rate, but an alarm system is not a substitute for
insurance. Homeowners, property owners and renters should continue to act prudently in protecting themselves and continue to
insure their lives and property.
We continue to develop new and improved protection devices. Users of alarm systems owe it to themselves and their loved ones to
learn about these developments.

**CONTACTING TECHNICAL SUPPORT**
**PLEASE, before you call Technical Support, be sure you:**
• READ THE INSTRUCTIONS!
• Check all wiring connections.
• Determine that the power supply and/or backup battery are supplying proper voltages.
• Verify your programming information where applicable.
• Note the proper model number of this product, and the version level (if known) along with any documentation
that came with the product.
• Note your Honeywell customer number and/or company name.
Having this information handy will make it easier for us to serve you quickly and effectively.
Technical Support: *..........................................................................................* 1-800-645-7492 (8 a.m.-10 p.m. E.S.T.)

MyWebTech:  .............................................................. http://www.honeywell.com/security/hsc/resources/MyWebTech

– 43 –

---

## Page 44

**WORKSHEET for** ∗ **56 ZONE PROGRAMMING**
(VISTA-15P supports up to 32 zones: 1-6, 9-34, 49-56) [default shown in brackets]


| Zone | Zn Type | Part. | Report | Hardwire | Rsp. Time | Location |
| --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  | Type |  |  |
| 1 | [09] | [1] |  | [EOL] | [1] |  |
| 2 | [01] | [1] |  | [EOL] | [1] |  |
| 3 | [03] | [1] |  | [EOL] | [1] |  |
| 4 | [03] | [1] |  | [EOL] | [1] |  |
| 5 | [03] | [1] |  | [EOL] | [1] |  |
| 6 | [03] | [1] |  | [EOL] | [1] |  |



| Zone | Zn Type | Part. | Report | Input Type | Loop | Serial No. | Location |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 9 |  |  |  |  |  |  |  |
| 10 |  |  |  |  |  |  |  |
| 11 |  |  |  |  |  |  |  |
| 12 |  |  |  |  |  |  |  |
| 13 |  |  |  |  |  |  |  |
| 14 |  |  |  |  |  |  |  |
| 15 |  |  |  |  |  |  |  |
| 16 |  |  |  |  |  |  |  |
| 17 |  |  |  |  |  |  |  |
| 18 |  |  |  |  |  |  |  |
| 19 |  |  |  |  |  |  |  |
| 20 |  |  |  |  |  |  |  |
| 21 |  |  |  |  |  |  |  |
| 22 |  |  |  |  |  |  |  |
| 23 |  |  |  |  |  |  |  |
| 24 |  |  |  |  |  |  |  |
| 25 |  |  |  |  |  |  |  |
| 26 |  |  |  |  |  |  |  |
| 27 |  |  |  |  |  |  |  |
| 28 |  |  |  |  |  |  |  |
| 29 |  |  |  |  |  |  |  |
| 30 |  |  |  |  |  |  |  |
| 31 |  |  |  |  |  |  |  |
| 32 |  |  |  |  |  |  |  |
| 33 |  |  |  |  |  |  |  |
| 34 |  |  |  |  |  |  |  |


**NOTES:**
Zone Type: see chart ∗ 56
Zone Programming Menu
mode section.
Report Code: enabled if
first digit is a non-zero
number.
Hardwire Type (zns 2-8):
0 = EOL
3 = ZD
1 = NC
4 = DB
2 = NO
Input Type:
2 = AW (zones 9-48)
3 = RF (zones 9-48)
4 = UR (zones 9-48)
5 = BR (zones 49-64)
**NOTE:** Zones 9-16 not
available if zone
doubling enabled.
Response Time:
0 = 10msec
1 = 350msec
2 = 700msec
3 = 1.2 sec
**Reserved Zones**
91 = addressable device
report enable/disable
default zone type =
[05].
92 = Duress report
enable/disable


| 49 |  | [1] |  | [BR] |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 50 |  | [1] |  | [BR] |  |  |  |
| 51 |  | [1] |  | [BR] |  |  |  |
| 52 |  | [1] |  | [BR] |  |  |  |
| 53 |  | [1] |  | [BR] |  |  |  |
| 54 |  | [1] |  | [BR] |  |  |  |
| 55 |  | [1] |  | [BR] |  |  |  |
| 56 |  | [1] |  | [BR] |  |  |  |



| 95 | [00] | N/A** |  | N/A | N/A | N/A | keypad [1] / [∗] |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 96 | [00] | N/A** |  | N/A | N/A | N/A | keypad [3] / [#] |
| 99 | [06] | N/A** |  | N/A | N/A | N/A | keypad [∗] / [#] |


– 44 –

---

## Page 45

**WORKSHEET for** ∗ **57 FUNCTION KEY PROGRAMMING**

| Option | Function | A P1 P2 com |  |  | B P1 P2 com |  |  | C P1 P2 com |  |  |  | D P1 P2 com |  |  | Comments |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 01 | Paging |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 02 | Time Display |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 03 | Arm AWAY |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 04 | Arm STAY |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 05 | Arm NIGHT-STAY |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 06 | Step Arming |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 07 | Device Activation |  |  |  |  |  |  |  |  |  |  |  |  |  | Device: |
| 08 | Comm. Test |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 09 | Macro Key 1 |  |  |  |  |  |  |  |  |  |  |  |  |  | Assign each macro key to only a single partition. † |
| 10 | Macro Key 2 |  |  |  |  |  |  |  |  |  |  |  |  |  | Assign each macro key to only a single partition. † |
| 11 12 | Macro Key 3 Macro Key 4 |  |  |  |  |  |  |  |  |  |  |  |  |  | Assign each macro key to only a single partition. † Assign each macro key to only a single partition. † |
| 00 | Emergency Keys: | zone 95 |  |  | zone 99 |  |  | zone 96 |  |  |  | paging |  |  |  |
|  | Personal Emergency |  |  |  |  |  |  |  |  |  |  | n/a |  |  |  |
|  | Silent Alarm |  |  |  |  |  |  |  |  |  |  | n/a |  |  |  |
|  | Audible Alarm |  |  |  |  |  |  |  |  |  |  | n/a |  |  |  |
|  | Fire |  |  |  |  |  |  |  |  |  |  | n/a |  |  |  |
| Emergency Keys: A = paired keys [1] / [∗] (zone 95); B = paired keys [∗] / [#] (zone 99); C = paired keys [3] / [#] (zone 96) † There are only four macros system-wide. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |


**WORKSHEET for** ∗ **79 OUTPUT RELAY/POWERLINE CARRIER DEVICE PROGRAMMING**


|  | OUTPUT TYPE |  |  |  |
| --- | --- | --- | --- | --- |
|  | Relay |  | X10 |  |
| Output No. | Module Addr. | Pos (1-4) | Unit No. | Description |
| 01 |  |  |  |  |
| 02 |  |  |  |  |
| 03 |  |  |  |  |
| 04 |  |  |  |  |
| 05 |  |  |  |  |
| 06 |  |  |  |  |
| 07 |  |  |  |  |
| 08 |  |  |  |  |


|  | OUTPUT TYPE (09-16 apply to VISTA-20P only) |  |  |  |
| --- | --- | --- | --- | --- |
|  | Relay |  | X10 |  |
| Output No. | Module Addr. | Pos (1-4) | Unit No. | Description |



| 17 | On-Board Trigger 1 | norm output = |
| --- | --- | --- |
| 18 | On-Board Trigger 2 | norm output = |


**WORKSHEET for** ∗ **81 ZONE LIST PROGRAMMING**


| List No. | Used For… | Contains These Zones… |  |  |
| --- | --- | --- | --- | --- |
| 01 | General Purpose (GP) |  |  |  |
| 02 | General Purpose |  |  |  |
| 03 | Chime-by-Zone or GP | (see field *26 for Chime-by-Zone option) |  |  |
| 04 | Cross Zones or GP | (see field *85 for Cross Zone Timer option) |  |  |
| 05 | Night-Stay Zones or GP |  |  |  |
| 06 | Dial Delay Disable or GP |  | V20PSIA/V15PSIA: | see field *50 for Dial Delay Disable option |
| 07 | Unlimited Reports or GP |  | V20PSIA/V15PSIA: | see field *93 for Unlimited Reports option |
| 08 | General Purpose |  |  |  |
| 09 | Zones activating pager 1 |  |  |  |
| 10 | Zones activating pager 2 |  |  |  |
| 11 | Zones activating pager 3 | (VISTA-20P) |  |  |
| 12 | Zones activating pager 4 | (VISTA-20P) |  |  |


– 45 –

---

## Page 46


| Output Function Number (V20P=1-48) (V15P=1-24) | Activation Type and Detail |  |  |  | Partition Number (P) (if using ZT trig) 0 = any 1 = partition 1 2 = partition 2 3 = common | Event (for zone list/activated by) |  | Action 0 = off 1 = close 2 secs 2 = stay closed 3 = pulse 4 = toggle 5 = duration 1†† 6 = duration 2†† | Output Number V20P=1-18 V15P=1-8, 17, 18 | Device Type R = relay T = trigger X = X10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Activated by 0=delete 1=zn list 2=zn type 3=zn no. | Zone List (ZL) 1-8 = list | Zone Type (ZT) (see table below) | Zone No. (ZN) 00=none V20P: 01-64 V15P: 01-06, 09-34, 49-56 |  | By Zone List 0 = restore 1 = alarm 2 = fault 3 = trouble | By Zone No. 0 = restore 1 = alrm/flt/trbl |  |  |  |
| 1 |  |  |  |  |  |  |  |  |  |  |
| 2 |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |
| 4 |  |  |  |  |  |  |  |  |  |  |
| 5 |  |  |  |  |  |  |  |  |  |  |
| 6 |  |  |  |  |  |  |  |  |  |  |
| 7 |  |  |  |  |  |  |  |  |  |  |
| 8 |  |  |  |  |  |  |  |  |  |  |
| 9 |  |  |  |  |  |  |  |  |  |  |
| 10 |  |  |  |  |  |  |  |  |  |  |
| 11 |  |  |  |  |  |  |  |  |  |  |
| 12 |  |  |  |  |  |  |  |  |  |  |
| 13 |  |  |  |  |  |  |  |  |  |  |
| 14 |  |  |  |  |  |  |  |  |  |  |
| 15 |  |  |  |  |  |  |  |  |  |  |
| 16 |  |  |  |  |  |  |  |  |  |  |
| 17 |  |  |  |  |  |  |  |  |  |  |
| 18 |  |  |  |  |  |  |  |  |  |  |
| 19 |  |  |  |  |  |  |  |  |  |  |
| 20 |  |  |  |  |  |  |  |  |  |  |
| 21 |  |  |  |  |  |  |  |  |  |  |
| 22 |  |  |  |  |  |  |  |  |  |  |
| 23 |  |  |  |  |  |  |  |  |  |  |
| 24 |  |  |  |  |  |  |  |  |  |  |


**ZONE TYPE/SYSTEM OPERATION – Choices for Zone Types are:**
00 = Not Used
05 = Trouble Day/Alarm Night
10 = Interior w/Delay
24 = Silent Burglary
01 = Entry/Exit#1
06 = 24 Hr Silent
12 = Monitor Zone
77 = Keyswitch
02 = Entry/Exit#2
07 = 24 Hr Audible
14 = Carbon Monoxide§§
81 = AAV Monitor Zone
03 = Perimeter
08 = 24 Hr Aux
16 = Fire w/Verification
90-91 = Configurable
04 = Interior Follower
09 = Fire
23 = No Alarm Response
§§ when used with an output function,
the carbon monoxide zone type
activates only upon CO alarms. Does
not activate for trouble conditions.


| § | Note: In normal operation mode: Code + # + 7 + NN Key Entry starts Device Code + # + 8 + NN Key Entry stops Device |  |
| --- | --- | --- |
| ** Use 0 (any) for Partition No. (P) entry. *** Or at Disarming, whichever occurs earlier. † Use *57 Menu mode to assign the function key. †† Duration is set in program field *177. ††† Device action not used for these choices. § automatically set when appropriate AVS Quick Command performed. |  |  |


**–** 46 **–**

---

## Page 47


| No. | Event (see list below) | Device No. for “01” events: enter 01-18 | Group No. for “02” events: enter 1-8 | Partition for “04-06” events: enter 1, 2, or 3 (VISTA-20P) | Start Time/ Days | Stop Time/ Days | Repeat (1-4) | Random (yes/no) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 01 |  |  |  |  |  |  |  |  |
| 02 |  |  |  |  |  |  |  |  |
| 03 |  |  |  |  |  |  |  |  |
| 04 |  |  |  |  |  |  |  |  |
| 05 |  |  |  |  |  |  |  |  |
| 06 |  |  |  |  |  |  |  |  |
| 07 |  |  |  |  |  |  |  |  |
| 08 |  |  |  |  |  |  |  |  |
| 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 |  |  |  |  |  |  |  |  |


**TABLE OF DEVICE ADDRESSES**

| This Device | Uses Address | Reports as †† | Enabled By… |
| --- | --- | --- | --- |
| RF Receiver | 00 | 100 | ∗56 zone programming: input device type entry |
| AUI 1 (touchscreen) | 01 | n/a | automatic if AUI enable field ∗189 enabled for AUI 1 |
| AUI 2 (touchscreen) | 02 | n/a | automatic if AUI enable field ∗189 enabled for AUI 2 |
| AUI 3 (touchscreen) (V20P) | 05 | n/a | automatic if AUI enable field ∗189 enabled for AUI 3 |
| AUI 4 (touchscreen) (V20P) | 06 | n/a | automatic if AUI enable field ∗189 enabled for AUI 4 |
| Communications Device (LRR) | 03 | 103 | automatic if communications device enabled in menu mode ∗29 |
| 4286 Voice Module | 04 | 104 | automatic if phone module access code field ∗28 enabled |
| Zone Expanders (4219/4229): module 1 (for zones 09 - 16) module 2 (for zones 17 - 24) module 3 (for zones 25 - 32) module 4 (for zones 33 - 40) module 5 (for zones 41 - 48) | 07 08 09 (V20P) 10 (V20P) 11 (V20P) | 107 108 109 110 111 | ∗56 zone programming: input device type entry, then: automatic if zone no. 9-16 entered as AW type or relay assigned automatic if zone no. 17-24 entered as AW type or relay assigned automatic if zone no. 25-32 entered as AW type or relay assigned automatic if zone no. 33-40 entered as AW type or relay assigned automatic if zone no. 41-48 entered as AW type or relay assigned |
| Relay Modules (4204): module 1 module 2 module 3 module 4 | 12 13 14 (V20P) 15 (V20P) | 112 113 114 115 | ∗79 output device programming: device address prompt: entered at device address prompt entered at device address prompt entered at device address prompt entered at device address prompt |
| Keypads: keypad 1 keypad 2 keypad 3 keypad 4 keypad 5 keypad 6 keypad 7 keypad 8 | 16 17 18 19 20 21 22 23 | n/a n/a n/a n/a n/a n/a n/a n/a | data field programming as listed below: always enabled, all sounds enabled. data field ∗190 †† Addressable devices are identified by “1” plus the data field ∗191 device address when reporting. Enter report code for data field ∗192 zone 91 to enable device reporting (default = enabled). See field ∗199 for addressable device (ECP) 3-digit/2- data field ∗193 digit identification keypad display options. data field ∗194 AUI devices are not supervised and therefore do not data field ∗195 report. data field ∗196 |
| RIS Communication | 25 | n/a | automatic if Remote Interactive Services enabled in field ∗91 |
| 5800TM Module | 28 | n/a | automatic |


**–** 47 **–**

---

## Page 48

**5800 SERIES TRANSMITTER INPUT LOOP IDENTIFICATION**
All of the transmitters illustrated have one or more unique factory assigned input (loop) ID numbers. Each of the inputs
requires its own programming zone (e.g., a 5804's four inputs require four programming zones). For information on any
transmitter not shown, refer to the instructions accompanying that transmitter for details regarding loop numbers, etc.

**UL NOTE** : The following transmitters are not intended for use in UL installations:  5804BD, 5814, 5816TEMP, 5819,
5819WHS and 5819BRS.

The 5827BD and 5800TM can be used in UL Listed Residential Burglar installations.

LOOP 1
(LOW
SENSITIVITY
LOOP 1
(LOW
SENSITIVITY
LOOP
1
LOOP 2
(HIGH
SENSITIVITY)
LOOP 2
(HIGH
SENSITIVITY)
LOOP 1
LOOP
1
LOOP 3 (TEMP)
LOOP 3 (TEMP)
LOOP 4 (TAMPER)
LOOP 4 (TAMPER)
**5800PIR-RES**
ENROLL AS "RF"
**5800Micra**
ENROLL AS "RF"
**5800CO**
ENROLL AS "RF"
**5800PIR-OD**
ENROLL AS "RF"
**5800PIR/**
**5800PIR-COM**
ENROLL AS "RF"

LOOP 3
LOOP 2
OFF
ON
LOOP 4
LOOP 1
LOOP 2
LOOP 4
LOOP 1
LOOP 1
LOOP
1
LOOP
1
LOOP
3
LOOP 1
•
•
•••
•
•••
•
•• •
••
••
•
•
**5800SS1**
ENROLL AS "RF"
**5809**
ENROLL AS "RF"
**5804BD/5804BDV**
ENROLL AS "BR"
PROGRAM HOUSE ID
**5800WAVE**
PROGRAM
HOUSE ID
**5806/5806W3/5807**
**5808/5808LST/5808W3**
ENROLL AS "RF"
**5804E**
ENROLL AS "BR"

LOOP 1
(PRIMARY)
LOOP 2
(REED)
LOOP 2
(REED)
LOOP 2
(REED)
LOOP 1
LOOP 2
(AUX.
CENTER)
LOOP 3
(TERMINALS)
LOOP 1
(TERMINALS)
LOOP 3
(TERMINALS)
LOOP 1
LOOP 3
(AUX.
RIGHT)
LOOP 1
(INTERNAL
SHOCK
SENSOR
LOOP 1
LOOP 1
(TERMINALS)
**5819S (WHS & BRS)**
ENROLL AS "RF"
**5819**
ENROLL AS "RF"
**5814**
ENROLL
AS "RF"
**5817**
ENROLL AS "RF"
**5816**
ENROLL AS "RF"
**5818MNL**
ENROLL AS "RF"
**5811**
ENROLL AS "RF"

SERIAL #2
LOOP 1
SERIAL #1
LOOP 3
SERIAL #1
LOOP 2
SERIAL #2
LOOP 1
SERIAL #1
LOOP 3
SERIAL #1
LOOP 2
LOOPS
1 - 3
LOOP 1
LOOP 3
(TILT
SENSOR)
SERIAL #2
LOOP 3
ARMED
READY
SERIAL #2
LOOP 4
MIC
MESSAGE
LOOP 1
(TERMINALS)
SERIAL #1
LOOP 4
SERIAL #1
LOOP 1
SERIAL #2
LOOP 2
**5822T**
ENROLL AS "RF"
**5834-2**
ENROLL AS "BR"
**5828/5828V**
PROGRAM
HOUSE ID
**5834-4**
ENROLL AS "BR"
**5821**
ENROLL AS "RF"
**5820L**
ENROLL AS "RF"

SERIAL #1
LOOP 3
LOOP 1
(HIGH
SECURITY)
LOOP 1
(LOW SENSITIVITY)
SERIAL #1
LOOP 2
**AWAY**
**STAY**
SERIAL #1
LOOP 4
LOOP 2
(HIGH SENSITIVITY)
**1**
**2**
LOOP 2
(STANDARD
SECURITY)
LOOP 1
LOOP 1
SERIAL #1
LOOP 1
SERIAL #2
LOOP 3
**3**
**4**
5800-006-V2
SERIAL #2
LOOP 2
LOOP 3 (TILT MODE)
LOOP 4 (TAMPER)
**5878**
ENROLL AS "BR"
**5870API**
ENROLL AS "RF"
**5853**
ENROLL AS "RF"
**5869**
ENROLL AS "RF"
**5898**
ENROLL AS "RF"

**WARRANTY INFORMATION**
For the latest warranty information, please go to:
www.honeywell.com/security/hsc/resources/wa

2 Corporate Center Drive, Suite 100
P.O. Box 9040, Melville, NY  11747
Copyright © 2003 Honeywell International Inc.
www.honeywell.com/security

ÊK5305-1PRV8wŠ
K5305-1PRV8  5/11   Rev. C