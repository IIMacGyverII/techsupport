# ADT7AIO Install Instructions

**Author:** Tom Kaminski  

## Table of Contents

- [System Features](#page-5) *(Page 5)*
- [Proper Installation Steps](#page-7) *(Page 7)*
- [Creating a Customer Account](#page-8) *(Page 8)*
  - [Customer Information](#page-8) *(Page 8)*
  - [Security](#page-8) *(Page 8)*
  - [Total Connect 2.0](#page-9) *(Page 9)*
- [Connect the Control Panel](#page-10) *(Page 10)*
  - [Backup Battery Installation](#page-10) *(Page 10)*
    - [Installing the Rechargeable Backup Battery](#page-10) *(Page 10)*
    - [System Low Battery Messages](#page-10) *(Page 10)*
    - [Replacing the Rechargeable Backup Battery](#page-11) *(Page 11)*
  - [Wall Mounting](#page-11) *(Page 11)*
  - [Desktop Mounting](#page-12) *(Page 12)*
  - [Communication Modules](#page-13) *(Page 13)*
    - [Installing the PROLTE Series Cellular Communications Module](#page-13) *(Page 13)*
    - [Installing the PROWIFIZW Wi-Fi and Z-Wave Communications Module](#page-14) *(Page 14)*
    - [Installing the PROTAKEOVER Wireless Converter Module](#page-15) *(Page 15)*
  - [AC Power](#page-16) *(Page 16)*
- [Initial Configuration](#page-17) *(Page 17)*
- [Configure Wireless Devices](#page-18) *(Page 18)*
  - [Sensors](#page-18) *(Page 18)*
  - [Range](#page-18) *(Page 18)*
  - [Frequency Agility](#page-18) *(Page 18)*
  - [One-Go-All-Go](#page-18) *(Page 18)*
  - [Smoke / CO Maintenance](#page-18) *(Page 18)*
  - [Transmitter Supervision](#page-18) *(Page 18)*
  - [Transmitter Battery Life](#page-19) *(Page 19)*
  - [Testing Signal Strength](#page-19) *(Page 19)*
  - [Keypad / Touchscreen Setup](#page-19) *(Page 19)*
  - [PROSIXLCDKP Wireless Keypad](#page-19) *(Page 19)*
  - [PROWLTOUCH Wireless Touchscreen](#page-20) *(Page 20)*
    - [Connecting the PROWLTOUCH to Wi-Fi](#page-21) *(Page 21)*
- [Configuring Programming](#page-23) *(Page 23)*
  - [Touchscreen Display](#page-23) *(Page 23)*
  - [Navigation Keys/Home Screen](#page-24) *(Page 24)*
  - [Master User Options](#page-25) *(Page 25)*
  - [Programming](#page-26) *(Page 26)*
    - [Setting up the Communication Links](#page-26) *(Page 26)*
    - [Registration, Programming, and Testing](#page-26) *(Page 26)*
  - [Zone Response Type Definitions](#page-26) *(Page 26)*
  - [Zone Assignments](#page-28) *(Page 28)*
  - [AN360 Programming Fields](#page-28) *(Page 28)*
    - [Configuring Partitions and their Options](#page-30) *(Page 30)*
    - [Configuring Programming (Continued)](#page-32) *(Page 32)*
    - [Adding Sensors](#page-32) *(Page 32)*
  - [Configuring Programming (Continued)](#page-33) *(Page 33)*
  - [PROINDMV Setup and Configuration](#page-33) *(Page 33)*
    - [Adding Keyfobs](#page-34) *(Page 34)*
    - [Adding PROSiXLCDKP Keypads](#page-34) *(Page 34)*
    - [Configuring Settings](#page-35) *(Page 35)*
- [System Operation](#page-39) *(Page 39)*
  - [Keypad/Touchscreen Operation](#page-39) *(Page 39)*
    - [PROSIXLCDKP Wireless Alpha Keypad Displays and Operation](#page-39) *(Page 39)*
    - [Keypad Menu Mode](#page-39) *(Page 39)*
    - [Keypad Supervision](#page-39) *(Page 39)*
  - [PROWLTOUCH Touchscreen Displays and Operation](#page-40) *(Page 40)*
    - [Master User Options](#page-40) *(Page 40)*
  - [Amazon Alexa](#page-41) *(Page 41)*
  - [Events](#page-41) *(Page 41)*
  - [Wi-Fi Settings](#page-41) *(Page 41)*
  - [System Displays](#page-42) *(Page 42)*
  - [Partitioning](#page-43) *(Page 43)*
    - [Goto Command](#page-43) *(Page 43)*
  - [System Clock](#page-43) *(Page 43)*
  - [Scheduling](#page-43) *(Page 43)*
  - [Audio Alarm Verification (AAV) (Two-Way Voice)](#page-43) *(Page 43)*
  - [Security Codes](#page-44) *(Page 44)*
    - [Programming Security Codes via Control Panel or Touchscreens](#page-44) *(Page 44)*
    - [Z-Wave Locks and User Code Push](#page-44) *(Page 44)*
    - [Keypad User Code Lockout](#page-44) *(Page 44)*
  - [Disarming / Cancelling an Alarm / Clearing Alarm Memory](#page-45) *(Page 45)*
  - [Rebooting the System](#page-45) *(Page 45)*
  - [Panic Key/Icons](#page-45) *(Page 45)*
  - [Event Log (Events)](#page-45) *(Page 45)*
    - [Contact ID® Event Log Codes](#page-46) *(Page 46)*
    - [Central Station Messages](#page-47) *(Page 47)*
- [Confirming (Testing) the System](#page-48) *(Page 48)*
  - [Test Modes](#page-48) *(Page 48)*
    - [Communications Tests](#page-48) *(Page 48)*
    - [Walk Test Mode](#page-48) *(Page 48)*
    - [Normal Mode Test](#page-48) *(Page 48)*
    - [Reporting Test](#page-49) *(Page 49)*
- [Automation](#page-50) *(Page 50)*
  - [Introduction to Automation](#page-50) *(Page 50)*
    - [Z-Wave Range](#page-50) *(Page 50)*
    - [Additional Z-Wave Information](#page-50) *(Page 50)*
  - [Accessing and Controlling Z-Wave Devices](#page-51) *(Page 51)*
  - [Z-Wave Device Management Screen](#page-51) *(Page 51)*
    - [Enrolled Devices](#page-51) *(Page 51)*
    - [Including (Adding) Automation Devices](#page-51) *(Page 51)*
    - [Excluding (Removing) Automation Devices](#page-52) *(Page 52)*
    - [Network Wide Inclusion](#page-53) *(Page 53)*
    - [Local Controller Info](#page-53) *(Page 53)*
    - [Shift Controller](#page-53) *(Page 53)*
    - [Update Network](#page-53) *(Page 53)*
    - [Remove All Failed Devices](#page-53) *(Page 53)*
    - [Reset Controller](#page-53) *(Page 53)*
  - [Alexa](#page-54) *(Page 54)*
  - [Bluetooth Disarm](#page-55) *(Page 55)*
- [Regulatory Agency Statements](#page-57) *(Page 57)*
- [Specifications](#page-59) *(Page 59)*
- [SIA Quick Reference Guide](#page-59) *(Page 59)*
- [NOTES  NOTES](#page-60) *(Page 60)*
- [Contacting Technical Support](#page-62) *(Page 62)*
- [PROA7/PROA7PLUS RESIDENTIAL BURGLAR AND FIRE ALARM CONTROL PANEL SUMMARY OF CONNECTIONS](#page-63) *(Page 63)*


---

## Page 1

PROA7/PROA7PLUS Series
Installation and Setup Guide

800-25082A    10/20    Rev. A
PROA7/PROA7PLUS

---

## Page 2

**RECOMMENDATIONS FOR PROPER PROTECTION**
The Following Recommendations for the location of fire and burglary detection devices help provide proper coverage for the protected
premises.
Recommendations for Smoke and Heat Detectors
With regard to the number and placement of smoke/heat detectors, we subscribe to the recommendations contained in the National
Fire Protection Association's (NFPA) Standard #72 noted below.
• Early warning fire detection is best achieved by the installation of fire detection equipment in all rooms and areas of the household as
follows: For minimum protection a smoke detector should be installed outside of each separate sleeping area, and on each additional
floor of a multi-floor family living unit, including basements. The installation of smoke detectors in kitchens, attics (finished or
unfinished), or in garages is not normally recommended.
• For additional protection the NFPA recommends that you install heat or smoke detectors in the living room, dining room, bedroom(s),
kitchen, hallway(s), attic, furnace room, utility and storage rooms, basements and attached garages.
In addition, we recommend the following:
• Install a smoke detector inside every bedroom where a smoker sleeps.
• Install a smoke detector inside every bedroom where someone sleeps with the door partly or completely closed. Smoke could be
blocked by the closed door. Also, an alarm in the hallway outside may not wake up the sleeper if the door is closed.
• Install a smoke detector inside bedrooms where electrical appliances (such as portable heaters, air conditioners or humidifiers) are
used.
• Install a smoke detector at both ends of a hallway if the hallway is more than 40 feet (12 meters) long.
• Install smoke detectors in any room where an alarm control is located, or in any room where alarm control connections to an AC
source or phone lines are made. If detectors are not so located, a fire within the room could prevent the control from reporting a fire
or an intrusion.

**THIS CONTROL COMPLIES WITH NFPA REQUIREMENTS FOR TEMPORAL PULSE SOUNDING OF**
**FIRE NOTIFICATION APPLIANCES.**

Recommendations for Proper Intrusion Protection
• For proper intrusion coverage, sensors should be located at every possible point of entry to a home or premises. This would include
any skylights that may be present, and the upper windows in a multi-level building.
• In addition, we recommend that radio backup be used in a security system. This ensures that alarm signals can be sent to the alarm
monitoring station in the event that the communications are out of order (if connected to an alarm monitoring station).

This Honeywell Home security system is designed for use with devices manufactured or approved by Resideo Technologies, Inc.,
through its subsidiary Ademco Inc. (“Resideo”). Your security system is not designed for use with any device that may be attached to
your security system's touchpad or other communicating bus if Resideo has not approved such device for use with your security
system. Use of any such unauthorized device may cause damage or compromise the performance of your security system and affect
the validity of your Resideo limited warranty. When you purchase devices that have been manufactured or approved by Resideo you
acquire the assurance that these devices have been thoroughly tested to ensure optimum performance when used with your security
system.

---

## Page 3

*PROA7/PROA7PLUS Installation and Setup Guide*

**Table of Contents**
**System Features .........................................................................................................................................................................1**
**Proper Installation Steps ...........................................................................................................................................................3**
**Creating a Customers Account .................................................................................................................................................4**

Customer Information ............................................................................................................................................................4
Security .................................................................................................................................................................................4
Total Connect 2.0 ..................................................................................................................................................................5
**Connect the Control Panel .........................................................................................................................................................6**

Backup Battery Installation ....................................................................................................................................................6
Installing the Rechargeable Backup Battery ...................................................................................................................6
System Low Battery Messages ......................................................................................................................................6
Replacing the Rechargeable Backup Battery .................................................................................................................7
Wall Mounting ........................................................................................................................................................................7
Desktop Mounting ..................................................................................................................................................................8
Communication Modules .......................................................................................................................................................9

Installing the PROLTE Series Cellular Communications Module ...................................................................................9
Installing the PROWIFIZW Wi-Fi and Z-Wave Communications Module ..................................................................... 10
Installing the PROTAKEOVER Wireless Converter Module ......................................................................................... 11
AC Power ............................................................................................................................................................................ 12
**Initial Configuration .................................................................................................................................................................. 13**
**Configure Wireless Devices .................................................................................................................................................... 14**

Sensors ............................................................................................................................................................................... 14
Range .................................................................................................................................................................................. 14
Frequency Agility ................................................................................................................................................................. 14
One-Go-All-Go ..................................................................................................................................................................... 14
Smoke / CO Maintenance ................................................................................................................................................... 14
Transmitter Supervision ....................................................................................................................................................... 14
Transmitter Battery Life ....................................................................................................................................................... 15
Testing Signal Strength ....................................................................................................................................................... 15
Keypad / Touchscreen Setup .............................................................................................................................................. 15
PROSIXLCDKP Wireless Keypad ....................................................................................................................................... 15
PROWLTOUCH Wireless Touchscreen .............................................................................................................................. 16

Connecting the PROWLTOUCH to Wi-Fi ..................................................................................................................... 17
**Configuring Programming ....................................................................................................................................................... 19**

Touchscreen Display ........................................................................................................................................................... 19
Navigation Keys/Home Screen ............................................................................................................................................ 20
Master User Options ............................................................................................................................................................ 21
Programming ....................................................................................................................................................................... 22

Setting up the Communication Links ............................................................................................................................ 22
Registration Programming and Testing ........................................................................................................................ 22
Zone Response Type Definitions ......................................................................................................................................... 22
Zone Assignments ............................................................................................................................................................... 24
AN360 Programming Fields................................................................................................................................................. 24

Editing AlarmNet Services ............................................................................................................................................ 24
Editing Total Connect 2.0 Services .............................................................................................................................. 25
Configuring Partitions and their Options ....................................................................................................................... 26
*Configuring Programming (Continued)* ......................................................................................................................... 28
Adding Sensors ............................................................................................................................................................ 28
*Configuring Programming (Continued)* ................................................................................................................................ 29
PROINDMV Setup and Configuration .................................................................................................................................. 29

Adding Keyfobs ............................................................................................................................................................ 30
Adding PROSiXLCDKP Keypads ................................................................................................................................. 30
Configuring Settings ..................................................................................................................................................... 31
**System Operation ..................................................................................................................................................................... 35**

Keypad/Touchscreen Operation .......................................................................................................................................... 35
PROSIXLCDKP Wireless Alpha Keypad Displays and Operation ................................................................................ 35
Keypad Menu Mode ..................................................................................................................................................... 35
Keypad Supervision ..................................................................................................................................................... 35
PROWLTOUCH Touchscreen Displays and Operation ....................................................................................................... 36

Master User Options .................................................................................................................................................... 36
Amazon Alexa ..................................................................................................................................................................... 37
Events ................................................................................................................................................................................. 37
Wi-Fi Settings ...................................................................................................................................................................... 37

- i -

---

## Page 4

*PROA7/PROA7PLUS Installation and Setup Guide*
System Displays .................................................................................................................................................................. 38
Partitioning........................................................................................................................................................................... 39

Goto Command ............................................................................................................................................................ 39
System Clock ....................................................................................................................................................................... 39
Scheduling ........................................................................................................................................................................... 39
Audio Alarm Verification (AAV) (Two-Way Voice) ............................................................................................................... 39
Security Codes .................................................................................................................................................................... 40

Programming Security Codes via Control Panel or Touchscreens ............................................................................... 40
Z-Wave Locks and User Code Push ............................................................................................................................ 40
Keypad User Code Lockout .......................................................................................................................................... 40
Disarming / Cancelling an Alarm / Clearing Alarm Memory ................................................................................................. 41
Rebooting the System ......................................................................................................................................................... 41
Panic Key/Icons ................................................................................................................................................................... 41
Event Log (Events) .............................................................................................................................................................. 41

Contact ID ® Event Log Codes ..................................................................................................................................... 42
Central Station Messages ............................................................................................................................................ 43
**Confirming (Testing) the System ............................................................................................................................................ 44**

Test Modes .......................................................................................................................................................................... 44
Communications Tests ................................................................................................................................................. 44
Walk Test Mode ........................................................................................................................................................... 44
Normal Mode Test ........................................................................................................................................................ 44
Reporting Test .............................................................................................................................................................. 45
**Automation ................................................................................................................................................................................ 46**

Introduction to Automation ................................................................................................................................................... 46
Z-Wave Range ............................................................................................................................................................. 46
Additional Z-Wave Information ..................................................................................................................................... 46
Accessing and Controlling Z-Wave Devices ........................................................................................................................ 47
Z-Wave Device Management Screen .................................................................................................................................. 47

Enrolled Devices .......................................................................................................................................................... 47
Including (Adding) Automation Devices ........................................................................................................................ 47
Excluding (Removing) Automation Devices.................................................................................................................. 48
Network Wide Inclusion ................................................................................................................................................ 49
Local Controller Info ..................................................................................................................................................... 49
Shift Controller .............................................................................................................................................................. 49
Update Network ............................................................................................................................................................ 49
Remove All Failed Devices ........................................................................................................................................... 49
Reset Controller ........................................................................................................................................................... 49
Alexa ................................................................................................................................................................................... 50
Bluetooth Disarm ................................................................................................................................................................. 51
**Regulatory Agency Statements ............................................................................................................................................... 53**
**Specifications ........................................................................................................................................................................... 55**
**SIA Quick Reference Guide ..................................................................................................................................................... 55**
**NOTES NOTES .......................................................................................................................................................................... 56**
**Contacting Technical Support ................................................................................................................................................. 58**
**PROA7/PROA7PLUS RESIDENTIAL BURGLAR AND FIRE ALARM CONTROL PANEL SUMMARY OF**
**CONNECTIONS ......................................................................................................................................................................... 59**

- ii -

---

## Page 5

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Features***


| System Features | PROA7 | PROA7PLUS |
| --- | --- | --- |
| • 7.0-inch Color Graphic Touchscreen |  |  |
| • Partitions | 4 | 4 |
| • Voice Announcement of System and Zone Status |  |  |
| • Automatic Home (Stay) Arming |  |  |
| • Night Home (Stay) Arming |  |  |
| • User Codes (Master, Standard, Guest, Arm Only) | 96 | 96 |
| • User code Lockout |  |  |
| • Panic Functions (Police, Fire, Medical/Personal and Silent Police) |  |  |
| • Supports Auxiliary Wireless Touchscreens (PROWLTOUCH) and Keypads (PROSIXLCDKP) |  |  |
| • Audio Alarm Verification (AAV) (Two—Way Voice) - Utilizes the Control Panel and Wireless Touchscreens for voice stations |  |  |
| • Event Log | 4,000 | 4,000 |
| • RF Jam Detection for all supported wireless technologies |  |  |
| • Exit Error feature (detects difference between an actual alarm and exit alarm caused by leaving a door open after the exit delay expires) |  |  |
| • Built-in Case Tamper |  |  |
| • Optional Wall Mount Tamper |  |  |
| • Built-in Camera (takes a snapshot when the system is disarmed from the Main Panel. They can be viewed by the user in the panel Camera Log, and in Total Connect 2.0.) |  |  |
| • Multi-Language (English, French, Spanish, Portuguese) |  |  |
| • Screen Saver |  |  |
| Home Automation |  |  |
| • Integrated Z-Wave Plus Support (requires the PROWIFIZW module) |  |  |
| • Supports up to 78 Z-Wave devices with the following maximums: Light Modules: 60 Door Lock: 6 Z-wave Thermostats: 6* Wi-Fi Thermostats: 4* * Combination Z-Wave & Wi-Fi thermostats maximum = 6 |  |  |
| • Supports Z-Wave Network Wide Inclusion (NWI) Mode |  |  |
| • Alexa Integration |  |  |
| • Blue Tooth Disarming (BLE) |  |  |
| Zones and Devices |  |  |
| • 4 Panel Panic Zones |  |  |
| • Intrusion/Fire Zones | 250 | 250 |
| - PROSiX™/SiX™ Series devices (sensors) | 127 | 127 |
| - 5800™ Series wireless technologies (requires PROTAKEOVER module*) * The PROTAKEOVER module supports communication with certain previously installed wireless sensors and modules. |  |  |
| - PROSiX Series Keyfobs (8 button) | 32 | 32 |
| - 8 PROSiX Series Keypads/Touchscreens (supports PROSIXLCDKP Wireless Keypads and PROWLTOUCH Wireless Touchscreen) per partition |  |  |
| • 10 Temperature Zones |  |  |
| • 8 Wiselink – Motion Viewers |  |  |


- 1 -

---

## Page 6

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Features*** *(Continued)*


| Alarm Output | PROA7 | PROA7PLUS |
| --- | --- | --- |
| • Built-in 85db Sounder |  |  |
| • Steady Output for burglary/panic |  |  |
| • Temporal (3) Pulse Output for fire alarms |  |  |
| • Temporal (4) Pulse Output for carbon monoxide alarms |  |  |
| Communication |  |  |
| • LTE Cell Communications (Backup path when used with a Wi-Fi connection) |  |  |
| - PROLTE-A (ATT) |  |  |
| - PROLTE-V (Verizon) |  |  |
| - PROLTE-CN (Bell - Canada) |  |  |
| • Wi-Fi Central Station communication (PROWIFIZW Required) |  |  (included) |
| System Power |  |  |
| • Primary Power: Plug-in Power Supply, 110VAC to 9VDC, 2.5A output p/n 300- 10260, (300-10260-CAN in Canada) |  |  |
| • Backup Battery: Rechargeable Lithium-ion Battery Pack p/n 300-10186, rated at 3.6/4.2Vdc, 7500 mAH | 24-Hour | 24-Hour |
| Programming |  |  |
| • Options stored in Flash |  |  |
| • Can be uploaded, downloaded or controlled using capable Cellular or Wi-Fi Communications Module |  |  |
| • Flash Downloading |  |  |
| • Registered, programmed, and tested via AlarmNet 360™. Use a PC or Smart Device to go to: www.alarmnet360.com or the AlarmNet360 App. |  |  |
| Agency |  |  |
| • UL / ULC Residential Burglary |  |  |
| • UL / ULC Residential Fire |  |  |
| • UL / ULC Commercial Burglary |  |  |


- 2 -

---

## Page 7

*PROA7/PROA7PLUS Installation and Setup Guide*
***Proper Installation Steps***

The proper steps for the PROA7/PROA7PLUS Control Panel to be installed are as follows:
1. **Create:** Create a Customer Account using the AlarmNet 360 App or web portal (www.alarmnet360.com)
2. **Connect:** Connect communication source and power up the Control Panel.  Allow the system to register with AN360.
a. Install Cellular Communicator (PROLTE-A, PROLTE-V, or PROLTE-CN), Wi-Fi/Z-Wave (PROWIFIZW) module,
and/or Takeover (PROTAKEOVER) module.

b. Mount the wall plate or attach the desk stand. Connect power supply wiring and install and connect the battery.
c. Secure the panel to the backplate and plug in the power supply (allow two minutes for the system to power up) and
connect to a Wi-Fi network when prompted.

d. Allow the panel to connect to AN360 and download any programming that has been setup earlier.
3. **Configure:** Program the system (enroll sensors, keypads, Keyfobs, Z-Wave, users, & settings). **NOTE:** The Control
Panel auto-syncs with every program change.

4. **Confirm:** Test the system and confirm that all programmed sensors are operational and reporting to the Central Station.
5. **Commission:** Commission the system and train the customer on the proper use of the PROA7/PROA7PLUS Control
Panel and Total Connect 2.0.

- 3 -

---

## Page 8

*PROA7/PROA7PLUS Installation and Setup Guide*
***Creating a Customer Account***
From the programming menu select "+ New Account" in the upper right-hand corner of the page.  Next, select the panel type as
ProSeries.


| New or Existing Customer | Select "New Customer" or "Existing Customer" (if creating additional account for one customer) |
| --- | --- |
| Customer Type | Select the "Customer Type" as Residential or Commercial |
| Customer Name and Contact details | Enter the first and last name; home, work, and cell phone numbers; customer's email address |


**Security**
**Location**

| Location Name | Enter the location name such as Home, Vacation Home, etc. (used with Total Connect 2.0) |
| --- | --- |
| Dealer Reference ID | Enter the internal account number specified for the customer. The maximum character limit is 25. |
| Sold By | Type the name of the Salesperson |
| Installed By | Type the name of the installation technician |
| Contract End Date | Set the contract end date by selecting the month, year, and date in the calendar |


**Address**

| Country | Select the country from the drop-down list |
| --- | --- |
| Address Line 1 | Type the address of the customer |
| Address Line 2 | Type the address of the customer |
| City | Type the City of the customer |
| State/Territory | From the drop-down list, select the state of the customer |
| Zip Code | Type the zip code of the customer. NOTE: this is not a mandatory field. If you have selected Total Connect account during Account Creation, ensure to add the zip code. |
| Notes | Type any extra information related to the customer |


**Control Panel**

| Type | Choose the Control Panel type from the drop-down list |
| --- | --- |
| Revision | Select the correct revision of the control being installed |
| Would you like to enter the MAC ID now? | Select "Yes" and enter the MAC ID and CRC of the communicator being installed. |
| Alarm Reporting Number | This is the CITY-CS-SUB account number for the communicator. |
| Continue | The security account is verified based on the CITY-CS-SUB, MAC ID, and whether the Control Panel revision and communicator type are compatible. |
| Packages | Select the required package from the drop-down menu. |
| Add-Ons | Two Way Voice Select to Enable two-way communication between the Control Panel and the Central Station, following an alarm condition. Video Alarm Select to enable Central Station supported video alarm verification. Verification Advanced Always Enabled and adds additional assurance that signals are sent Protection Logic to the Central Station in the event that the alarm system equipment is compromised prior to sending an alarm. Video Service Based on the selected service level, the video clip from the camera is retained. (PROA7PLUS Only) |



| Two Way Voice | Select to Enable two-way communication between the Control Panel and the Central Station, following an alarm condition. |
| --- | --- |
| Video Alarm Verification | Select to enable Central Station supported video alarm verification. |
| Advanced Protection Logic | Always Enabled and adds additional assurance that signals are sent to the Central Station in the event that the alarm system equipment is compromised prior to sending an alarm. |
| Video Service | Based on the selected service level, the video clip from the camera is retained. (PROA7PLUS Only) |


- 4 -

---

## Page 9

*PROA7/PROA7PLUS Installation and Setup Guide*


| Create New Account | Select to create a new Total Connect account for the panel. |
| --- | --- |
| Use Existing Account | Select to use an existing Total Connect account for the panel. |
| TC2 Account Name | Type a name for the account |
| TC2 Master User Name | Type a master user name for the account. This is the Username your customer uses when logging in. |
| TC2 Master user E-Mail ID | Type a master user E-Mail ID for the account |
| Total Connect 2.0 Plan | Select the Total Connect 2.0 Plan |
| Panel Master Code | Type the master code of the panel. This code is available on your Control Panel. |
| Location Zip Code | Type the zip code of your location |
| Pre-configure Total Connect 2.0 Account | Select this feature to enable pre-configuration of Total Connect 2.0 account prior to sending welcome e-mails to your customer. |
| Does the customer have a SkyBell Account? | Based on the account availability, select the relevant option and proceed. |


**End User Preferences**

| Language | From the list, select to program a user-friendly language for the application. |
| --- | --- |
| Time Zone | From the list, select the time zone. |
| Date Format | Select to set the date format. |
| Time Format | Select to set the time format. |
| Notifications | From the list of available notifications, you can click to: Select/Deselect All, or Select the relevant notifications. |


Once all fields have been addressed click "Finish" on the top-right corner of the page.  A summary screen is provided to check
the details again and click "Confirm Creation".

- 5 -

---

## Page 10

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel***

**Backup Battery Installation**
The Control Panel is equipped with an integral, replaceable, rechargeable battery pack rated at 3.6/4.2Vdc. In the event of an
AC power loss, the system is supported by the long-life backup battery that is supervised for connection and for low voltage
conditions. If the battery is missing, or a low battery condition is detected, a “low battery” message is displayed, and a report is
sent to the Central Station. In addition, the system beeps once every 60 seconds to audibly indicate a low battery condition
(press any key to stop the beeping). Follow the steps and refer to the figure below to install and connect the battery.


| Battery Part Number | Battery Standby Time Low Battery Notification |
| --- | --- |
| 300-10186 | 24-hours (minimum) At least 1-hour before battery depletion |


**Installing the Rechargeable Backup Battery**
1.
Insert the battery pack into the case.
2.
Connect the battery connector to the receptacle on the PC board.
3.
Install the side cover.
4a. Connect the power cable to the GND and +9V terminals on the wall mount and to the + and – terminals on the Power
Supply. Refer to the Wiring Table (on page 9) for maximum wire gauge and length. **Do not apply power at this time** . OR
4b. Connect the power supply connector to the receptacle on the desk mount. **Do not apply power at this time.**

**NOTE:** If using the optional wall mount configuration, refer to the wall mounting procedure. If using the Desk Mount refer to the
desk mounting procedure.

**Rechargeable batteries may take up to 24-hours to fully charge. The “System Low Battery” message**
**displays until the battery is fully charged.**

**System Low Battery Messages**
The “System Low Battery” message may be displayed on the Keypads/Touchscreens. The message displays until the battery is
fully charged. Additionally, when the low battery condition exists the Keypads/Touchscreens emit one beep every 60 seconds.
The beeps can be silenced by pressing any key on the Keypads/Touchscreens. The beeps only need to be silenced one time
and they are not emitted again.  No further action is required. The “Low Battery” message clears automatically when the battery
is fully charged. Additionally, the system sends a Low Battery Restore (CID R302) message to the Central Station **.**

- 6 -

---

## Page 11

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel*** *(Continued)*

**Replacing the Rechargeable Backup Battery**
When battery replacement is required, remove electrical power (refer to the *System Shutdown* section for additional information)
and follow the steps below.

**Remove the battery**
1.  Unscrew the screw securing the Control Panel to the wall or desk mount.
2.
Release the catch that secures the Control Panel to the wall or desk mount.
3.
Rotate the Control Panel and lift it from the wall or desk mount, being careful not to damage the wiring.
4.
Remove the side cover.
5.  Disconnect the battery pack connector from the receptacle on the back of the PC board.
6.
Remove the battery pack from the case.

**Install the replacement battery**
1.
Insert a replacement battery pack p/n 300-10186 into the Control Panel.
2.
Connect the battery connector to the receptacle on the PC board.
3.
Install the side cover.
4.
Connect the power supply connector to the receptacle on the desk mount. **Do not apply power at this time.**
5.
Install the control onto the wall or desk mount.
6.  Install the screw to secure the control.
7.
Plug the power supply into a 24-hour, 110VAC non-switched outlet. Upon power-up, the “System Standby!” screen displays.
NOTE: Allow up to two minutes for power-up.

**NOTE:** If a Cellular Communication Module is being installed, verify the module’s signal strength before selecting a final
mounting location. Refer to *Checking the Signal Strength* in the Communications Module section.

**Wall Mounting**
**NOTE:** When selecting a location for the Control Panel, be sure to provide a separation of at least 10 feet between 2.4GHz
devices such as Wi-Fi Routers/Access Points.
For wall mounting follow the steps and refer to the figure below.
1.  Feed the field wiring through the appropriate openings in the wall mount.
2.  Attach the wall mount to a sturdy wall using the provided screws.
3.
If required, install an additional mounting screw in the case tamper.
4.
Align the cleats on the back of the Control Panel with the slots on the wall mount as shown below.
5.
Snap the Control Panel into place.
6.
Once attached, insert the screw to secure the Control Panel to the wall mount.

- 7 -

---

## Page 12

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel*** *(Continued)*

**Desktop Mounting**
**NOTE:** When selecting a location for the Control Panel, be sure to provide a separation of at least 10 feet between 2.4GHz
devices such as Wi-Fi Routers/Access Points.

The PROA7DM is intended for use with the PROA7/PROA7PLUS Control Panels and can be positioned at a 60° or 30° angle.
1.
Choose the desired angle and align the hooks on the desk stand with the slots on the backplate.
2.
Slide the desk stand **up** to lock it in place. To use the other position, flip the stand the other way before fitting it to the
backplate.

3.
Install the PROA7/PROA7PLUS on the desk stand and lock it into place.
4.
Install the set screw.

5.
Route the power supply cable through the opening in the desk mount and connect it to the receptacle on the
PROA7/PROA7PLUS.

- 8 -

---

## Page 13

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel*** *(Continued)*

**Communication Modules**
The Control Panel supports Central Station reporting using wireless/cellular and Wi-Fi communications devices as well as
upload/download programming capability via the Internet. This allows site maintenance independent of Central Station
monitoring, and modification to sites globally via the Internet.  Additionally, an internal Z-Wave module allows the Control Panel
to support Home Automation functions while a Converter module is used to support other wireless technologies. (P/N 800-25182
for additional information.) The Control Panel is compatible with the following Communication Modules:

**Model**
**Description**
PROLTE-A
LTE Cellular Communications Module (US/Canada, AT&T network)
PROLTE-V
LTE Cellular Communications Module (US, Verizon network)
PROLTE-CN
LTE Cellular Communications Module (Canada, Bell)
PROWIFIZW
Z-Wave/Wi-Fi Communications Module
PROTAKEOVER
Wireless Converter Module

**RF Exposure**
**WARNING: The Control Panel must be installed to provide a separation distance of at least 7.8 in (20 cm)**
**from all persons and not co-located or operated in conjunction with any other transmitter except in**
**accordance with FCC multi-transmitter product procedures.**

**Ensure that all electrical power has been removed from the Control Panel before installing communication**
**modules. Refer to the** ***System Shutdown*** **section for additional information.**

**Installing the PROLTE Series Cellular Communications Module**
Follow the steps and refer to the figure below to install the LTE Communications Module.

1.  Remove electrical power (if applied). Refer to
the *System Shutdown* section for additional
information.
2.  Remove the screw securing the control to the
wall mount or desk mount.
3.
Rotate the Control Panel and lift it from the wall
or desk mount, being careful not to damage the
wiring.
4.
Remove the left side cover.
5.
Insert the module into the slot on the left side of
the Control Panel as shown and ensure the
receptacle is securely seated on the Control
Panel’s edge connector.
6.
Install the set screw
7.
Install the cover
8.
Install the control onto the wall or desk mount.
9.
Install the screw to secure the control.
10. Plug the power supply into a 24-hour, 110VAC
non-switched outlet. Upon power-up, the
“System Standby!” screen displays.  NOTE:
Allow up to two minutes for power-up.

**IMPORTANT:** A cellular or Wi-Fi communicator is required to register the Control Panel.

- 9 -

---

## Page 14

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel*** *(Continued)*

**Communication Modules (Continued)**
**Installing the PROWIFIZW Wi-Fi and Z-Wave Communications Module**
Follow the steps and refer to the figure below to install the Wi-Fi/Z-Wave Communications Module. **NOTE:** this module comes
preinstalled in the control (PROA7PLUS Only).

**Ensure that all electrical power has been removed from the Control Panel before installing communication**
**modules. Refer to the** ***System Shutdown*** **section for additional information.**

1.  Remove electrical power (if applied). Refer to
the *System Shutdown* section for additional
information.
2.  Remove the screw securing the control to the
wall mount or desk mount.
3.
Rotate the Control Panel and lift it from the
wall or desk mount, being careful not to
damage the wiring.
4.
Remove the left side cover.
5.
Insert the module into the slot on the left side
of the Control Panel as shown and ensure the
receptacle is securely seated on the Control
Panel’s edge connector and secured with the
provided screw.
6.  Install the cover
7.  Install the control onto the wall or desk mount.
8.  Install the screw to secure the control.
Plug the power supply into a 24-hour, 110VAC
non-switched outlet. Upon power-up, the
“System Standby!” screen displays. **NOTE:**
Allow up to two minutes for power-up.

- 10 -

---

## Page 15

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel*** *(Continued)*

**Communication Modules (Continued)**
**Installing the PROTAKEOVER Wireless Converter Module**
Follow the steps and refer to the figure below to install the Wireless Converter Module. Refer to the PROTAKEOVER module
Installation Instruction (p/n 800-25182) for additional information.

**Ensure that all electrical power has been removed from the Control Panel before installing**
**communication modules** **. Refer to the** ***System Shutdown*** **section for additional information.**

1.  Remove electrical power (if applied).
Refer to the *System Shutdown* section
for additional information.

2.  Remove the screw securing the control
to the wall mount. Rotate the Control
Panel and lift it from the wall mount,
being careful not to damage the wiring.

4.
Remove the right side cover.
5.  Set the rotary switch on the
PROTAKEOVER module to the setting
associated with the existing wireless
sensors and modules and the Control
Panel. Refer to the table for the
supported protocols.

6.
Insert the PROTAKEOVER module into
the slot on the right side of the Control
Panel as shown and ensure the
receptacle is securely seated on the
Control Panel’s edge connector. Secure
with the provided screw.

**Take Over Module**
**Rotary Switch Settings**
**Protocol**
**PROA7/PROA7PLUS**
5800
0
2GIG
1
DSC
2
ITI/Qolsys
3
Bosch
4

7.
Reinstall the access cover, taking care to
avoid bending the contracts on the
module.

8.
Remove the existing wall mount and
replace with the wall mount (containing
the integrated antenna) provided with
PROTAKEOVER module.

**Note:** To avoid damaging the connector pins
on the module, do not force the rear
case during the installation.

9.
Install the control on the replacement
wall mount and secure with the screw.

**NOTE:** The PROTAKEOVER module supports communication with certain previously installed wireless sensors and modules.
Refer to PROTAKEOVER Compatibility chart (p/n R800-26221 or later) for a list of tested and approved vendor
wireless devices.

- 11 -

---

## Page 16

*PROA7/PROA7PLUS Installation and Setup Guide*
***Connect the Control Panel*** *(Continued)*

**AC Power**
The Control Panel is powered by a 9VDC, 2.5 Amp Plug-in Power Supply, 300-10260  (300-10260-CAN in Canada). Refer to
the wiring table below for wire gauge and length.


|  | Maximum Cable Length Between |  | Wire Gauge (AWG) |
| --- | --- | --- | --- |
|  | Power Supply and Control Panel |  |  |
|  | Up to 25 feet (7.62m) |  | # 22 |
|  | Up to 45 feet (13.72m) |  | # 20 |
|  | Up to 70 feet (21.34m) |  | # 18 |
|  | Up to 110 feet (33.53m) |  | # 16 |

**Use only the 300-10260 (300-10260-CAN**
**Canada) Power Supply.  Do not plug the power**
**supply into the AC outlet until after all wiring**
**connections have been made.**

**Wiring Overview**
The following summarizes the electrical connections associated with the Control Panel. Follow the steps and refer to the
Summary of Connections diagram for additional information.

**Make Electrical Connections**
1. Remove the Control Panel’s rear case/backplate.

2a. Connect the power cable to the GND and +9V terminals on the Control Panel and to the + and – terminals on the Power
Supply. Refer to Wiring table for wire gauge and length.  OR

2b. Connect the power supply connector to the receptacle on the Control Panel.
3.  Install the rear case/backplate onto the Control Panel and secure with the screw.

**Summary of Connections**

- 12 -

---

## Page 17

*PROA7/PROA7PLUS Installation and Setup Guide*
***Initial Configuration***

System Startup
Before connecting power to the Control Panel, the customer's account must be
configured in AlarmNet 360 (AN360) located at www.alarmnet360.com.   Refer
to the Creating Customer Account section above for more information.
Bootup sequence
Detecting Devices
LTE Communicator
Wi-Fi/Z-Wave Card
Wireless Takover Module

Communicator Setup
QS-163-V0_Initial_Boot_Up

| SyCsotmemmu Sntiacarttourp Setup DEMO MODE Bootup sequence |  |  |
| --- | --- | --- |
|  | yCsotmemmu Sntiacarttourp Setup DEMO MODE ootup sequence |  |
|  | Detecting Devices CLeTlElu lCarommunicator Details |  |
|  | Wi-Fi/Z-Wave Card |  |
|  | WWi-iFreiless Takover Module SETUP |  |
|  | NEXT Communicator Setup |  |
|  |  |  |

Touch "Details" to view the Cellular Communicators ID numbers.
If using Wi-Fi, touch "Setup" to configure.  If not using Wi-Fi, touch "Next".

QS-164-V0_Initial_Boot_Up1
• Touch "Wi-Fi" Networks to select from a list of broadcasted networks. Follow
the on-screen prompts to connect to the network.
Wi-Fi
Wi-Fi Networks
• Touch "Add Network Manually" if connecting to a hidden network.
Add Network Manually
• If using the WPS option to connect to the network, start the WPS process on
the router first, then touch the WPS option on the screen.
WPS
Press the WPS button on your router, then press here

QS-165-V0_Initial_Boo
t_Up2

| SyCsotmemmu Sntiacarttourp Setup DEMO MODE Bootup sequence |  |  |
| --- | --- | --- |
|  | yCsotmemmu Sntiacarttourp Setup DEMO MODE ootup sequence |  |
|  | Detecting Devices CLeTlElu lCarommunicator Details |  |
|  | Wi-Fi/Z-Wave Card |  |
|  | WWi-iFreiless Takover Module SETUP Connected to Network 1 |  |
|  | NEXT Communicator Setup |  |
|  |  |  |

Once connected to the Wi-Fi network touch "Next".

QS-166-V0_Initial_Boot_Up3
Connected
After "Next" was touched the Control Panel attempts to connect to the edge-to-
cloud server in AN360.

Touch "REGISTER" to start the registration process.
The edge-to-cloud application is connected to the server.

REGISTER
QS-167-V0_Initial_Boot_Up4
Registration
The Control Panel connects, verifies the account information, and then
downloads the pre-existing configuration to the Control Panel.  Next, the home
screen appears.
Connect with AlarmNet360
Verify account
Download system configuration

QS-168-V0_Initial_Boot_Up5

- 13 -

---

## Page 18

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configure Wireless Devices***

**Sensors**
All devices and sensors are setup, programmed, and tested via AlarmNet 360.  Use a PC or Smart Device to go to:
www.alarmnet360.com or use the AlarmNet360 app.  The Control Panel supports up to 250 total wireless zones; 127 of which
can be PROSiX/SiX™ Series Wireless while any of them can be 5800 Series or another technology:
• PROSiX/SiX™ Series Wireless
• 5800™ Series wireless technologies (requires PROTAKEOVER module) Communicates with wireless devices that transmit
on the following frequencies 319.5MHz, 345MHz, 433.42 and 433.92MHz. Refer to the PROTAKEOVER Compatibility chart
for a list of compatible devices. Only one of these technologies can be used at one time.

**IMPORTANT:** Once paired, PROSiX/SiX™ Series transmitters cannot be used with another Control Panel until
they are unpaired (deleted) from the current Control Panel.  When being unpaired, the transmitters must be
powered up and within range of the Control Panel so the transmitters can receive the unpairing signal.  Devices
can only be unpaired via AlarmNet 360.  Some SiX™ transmitters can be defaulted manually within 24hrs of being
paired to the Control Panel.  Check the installation instructions of that transmitter for details.

**Range**
The range of any wireless device ultimately depends on the building construction.  The ranges specified below are typical for
most installations.
• PROSiX/SiX™ Series Wireless has a nominal range of 300+ feet @ 2.4GHz.
• 5800™ Series Wireless has a nominal range of 200 feet @ 345MHz.
**Frequency Agility**
Communications between the Control Panel and SiX™ Series transmitters are automatically monitored by the panel. When
excessive environmental interference (i.e. from Wi-Fi routers) is detected on the 2.4GHz channel, the Control Panel
automatically switches to a quieter channel to allow clearer communication.
**One-Go-All-Go**
SiX™ Series transmitters are bi-directional, so they not only send signals to the Control Panel, but they also receive signals from
the Control Panel.  If enabled in programming, the Control Panel sends a signal to all devices (i.e. smoke, CO, or combo
devices) during a fire or CO alarm causing all of those devices to sound.  This also applies to PROSiX/SiX Series Keypads /
Touchscreens and Sirens, which all sound for burg alarms as well.
**Smoke / CO Maintenance**
The PROSiX/SiX™ Series smoke detectors and smoke / CO combo detectors can send “High Sensitivity” or “Low Sensitivity”
Maintenance signals when they become too dirty to detect smoke or if they become too sensitive.  End-of-Life (EOL) is also
supported for CO detectors.
**Transmitter Supervision**
Each transmitter is supervised by a check-in signal that it sends to the Control Panel.  If at least one check-in is not received
from each supervised transmitter within their designated time period, the "missing" transmitter’s zone number(s) and
"Supervision" is displayed and it initiates a trouble signal, no matter if the panel is armed or disarmed. The supervision for a
transmitter can be disabled by programming it as “Unsupervised” so that it may be carried off the premises, such as a panic
button.  If set for Unsupervised, the Control Panel ignores ONLY the supervision signals it receives from that transmitter, but
still recognizes all other signals, including Low Battery.  Both SiX™ and 5800™ Series transmitters have built-in tamper
protection and initiates a trouble condition if the Control Panel is disarmed and an alarm if it is armed. Wireless keys are not
supervised.
• PROSiX/SiX Series Burg and panic transmitters send a check-in signal every 60 minutes with a 12-hour panel check.
• PROSiX/SiX Series Life Safety transmitters send a check-in signal every 60 seconds with a 2-hour panel check.  These
include smoke / CO detectors, and sirens.
• PROSiXLCDKP keypads are supervised at 15-minute intervals
• 5800™ Series transmitters send a check-in signal every 70-90 minutes with a 12-hour panel check.
• A power cycle of the Control Panel or a “System Reboot” via touchscreen restarts the 12-hour timer.

- 14 -

---

## Page 19

*PROA7/PROA7PLUS Installation and Setup Guide*
***Wireless Devices*** *(Continued)*

**Transmitter Battery Life**
Batteries in the wireless transmitters may last from 4–10 years, depending on the environment, usage, and the specific wireless
device being used.  Factors such as humidity, high or low temperatures, as well as large swings in temperature may all reduce
the actual battery life in any installation. The wireless system can identify a true low battery condition, thus allowing the dealer or
end user time to arrange a change of battery and maintain protection for that point.  Batteries should be replaced within 2 weeks
of going into a low battery condition.

**IMPORTANT:** SiX™ and 5800™ Series transmitters draw quick bursts of current during transmission, then sit idle
with very nominal current draw.  Most batteries are not designed for this type of use, therefore, only batteries listed as
compatible should be used to attain if the expected battery life. Each transmitter’s Installation Instructions lists
compatible battery manufacturers and their part numbers.  When other non-approved batteries are used, the quick
bursts of current draw kill the battery cells prematurely causing them to go low in a matter of months and can also
cause unpredictable results.  Other low quality batteries have not been UL tested and pose a safety hazard if used.
**Testing Signal Strength**
This system provides a sensor walk test mode for checking wireless signal strength.  The battery status and signal strength for
PROSiX/SiX™ Series transmitters are displayed in AlarmNet 360 and through the PROA7/PROA7PLUS Control Panel (press
Menu > Sensors).

**Important Security Notice**
Please inform the User about the security importance of their wireless key (key fob), and what to do if it is lost.
Explain that the wireless key is similar to their keys or access card. If lost or stolen, another person can compromise their
security system. They should immediately notify the Dealer/Installer of a lost or stolen wireless key. The Dealer/Installer then
removes the wireless key programming from the security system.

**Keypad / Touchscreen Setup**
The PROSIXLCDKP must be paired with the Control Panel via the AlarmNet 360 Programming Tool.  Use a PC or Smart Device
to go to:  www.alarmnet360.com or the AlarmNet360 App.  After putting the system into Learn Mode, power up each device or
initiate the pairing sequence individually to pair the keypad with the system.  The wired keypads/touchscreens do not power up
on battery alone; they must be powered up with their supplied transformer.
**PROSIXLCDKP Wireless Keypad**
The PROSIXLCDKP keypad attempts to pair automatically upon power up. If it is not paired during power up, any button can be
pressed or power cycle the unit to restart the pairing process.  The keypad can be either wall or desk mounted.  Desk mounting
requires the optional PROSIXLCDDM kit.  For additional information refer to the PROSIXLCDKP Installation and Setup Guide
(p/n 800-25152 or later).
The keypad can be either wall or desk mounted using the optional PROSIXLCDDM kit.  For additional information refer to the
Installation and Setup Guide (p/n R800-25933 or later).

When wiring the wall mount, use the wire table below to determine the gauge of wire needed between the transformer and
mounting plate. For proper wiring instructions, refer to the Installation and Setup Guide (p/n 800-25152 or later).


| Maximum Cable Length Between Keypad and Power Supply | Wire Gauge (AWG) |
| --- | --- |
| Up to 19ft (5.8m) Up to 30ft (9m) | #22 #20 |
| Up to 51ft (15.5m) | #18 |
| Up to 75ft (23m) | #16 |


The keypad is powered by a 9Vdc, 1.5A plug-in transformer, P/N 300-07332US or 300-07332-CAN (Canada. Use
the above chart to determine the length of the wire run and the gauge for the installation.

**IMPORTANT:** The wireless keypad uses SiX™ technology. Once they are paired to the Control Panel, they
cannot be used with another Control Panel until it is unpaired (deleted) from the current Control Panel.  When
being unpaired, the keypads must be powered up and within range of the Control Panel, so they can receive the
unpairing signal.  Devices must be unpaired via AlarmNet 360.

- 15 -

---

## Page 20

*PROA7/PROA7PLUS Installation and Setup Guide*
***Wireless Devices*** *(Continued)*
**PROWLTOUCH Wireless Touchscreen**
The PROWLTOUCH Touchscreen communicates to the Control Panel via Wi-Fi.  The Control Panel must have the
PROWIFIZW Wi-Fi module installed; and connected to the same router the PROWLTOUCH.  Wireless Touchscreens (if
installed), are functionally the same as the Control Panel.  They duplicate the Control Panel’s displays and functions.  Most
everything that can be done at the Control Panel can also be done at the Touchscreen.  The PROWLTOUCH communicates to
the Control Panel via Wi-Fi.  It can be either wall mounted with the wall docking station or desk mounted with either the built-in
desk stand or separate optional desk mount.  The built-in desk stand option angles the touchscreen at approx. 30°. **NOTE:** when
pairing, the Control Panel must not be in sensor learn mode.
**PROWLTOUCH Wireless Touchscreen**

**Status LED**
**Meaning**
Red - Steady
System Armed
Red - Flashing
Alarm / Alarm Memory
Amber - Steady
System trouble
Amber - Flashing
Device trouble – System cannot be armed
Green - Steady
Ready to Arm
Green - Flashing
Device trouble - System can be armed
Green & Red
Alternately Flashing

System is in Programming Mode

Off
Not ready to Arm

**NOTE:** The power button has 2 different functions:
• Press and Release toggles the screen off and on
• Press and Hold to display the options of Power Off or Restart.

**Touchscreen Mounting Options**
**Built-In Desk Stand**

The touchscreen can be powered by the supplied micro USB cable and the 5Vdc, 1.5A plug-in transformer.  For
optimal performance, use the supplied transformer to charge the Lithium Ion Polymer battery.  The battery may not
charge properly if it’s plugged into any other USB port.

**PROWLTOUCHWM (Sold Separately)**
**PROWLTOUCHDM (Sold Separately)**

- 16 -

---

## Page 21

*PROA7/PROA7PLUS Installation and Setup Guide*
***Wireless Devices*** *(Continued)*

**Connecting the PROWLTOUCH to Wi-Fi**
1. After powering up the PROWLTOUCH Touchscreen, it
prompts you to enter Wi-Fi Networks or Add Network
Manually.
To pick from a list of available networks press Wi-Fi
Networks.
**NOTE:** Panel must not be in Sensor Learn Mode

2. Select the network.

3. Enter the correct password and press Connect.
**NOTE:** As long as the PROA7/PROA7PLUS is connected to
the same Wi-Fi network, it acquires the IP address of the
PROA7/PROA7PLUS and pairs with the Control Panel.

4. PROWLTOUCH searches for the IP address of the
Control Panel.  When it finds the IP address of the
Control Panel it displays:

- 17 -

---

## Page 22

*PROA7/PROA7PLUS Installation and Setup Guide*
***Wireless Devices*** *(Continued)*

5. Enter the 4-digit Installer PIN to Pair with the Control
Panel.

6. Select the Home partition for this keypad.
7. Once the PROWLTOUCH is successfully paired, it
shows in AN360 under keypads.  There you can edit
the name and partition assignment or delete the
keypad if desired.

- 18 -

---

## Page 23

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming***
**Navigating Menus**
**Touchscreen Display**
The Control Panel’s Liquid Crystal Display (LCD) touchscreen displays variable icons and text on “screens”. The screen displays
status icons and associated text, the current time and date, system status information and menu choices. The Menu area
includes a list of commands, or choices that apply to the current selection. The status area provides information about various
system events and a colored bar also provides an indication of system status. A “Home Screen” is displayed whenever power is
applied to the system. System status is also indicated by the Power (left) and Status (right) Status LEDs.

**PROA7 / PROA7PLUS Control Panel**

**System Status LED Functions**


| LED | Status | Meaning |
| --- | --- | --- |
| Power (Left) | Green – Steady Off | AC Connected/Battery Charged |
|  |  | No AC Power |
| Status (Right) | Green – Steady Amber – Steady Red – Steady Red Flashing Red/Green – Flashing Off | System Ready to Arm |
|  |  | System trouble |
|  |  | System Armed |
|  |  | Alarm or Alarm Memory |
|  |  | System in Programming mode |
|  |  | Not ready to arm |


- 19 -

---

## Page 24

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*
**Navigation Keys/Home Screen**
System Status is displayed below the large icon on the left side of the touchscreen. In addition, the Home Screen displays the
current weather, date and time and selectable options are displayed on a separate menu. Select the Menu icon to display the
available Menu options.
Navigating through the screens is accomplished by lightly touching the icons or menu items on the touchscreen. Once activated,
the Control Panel advances to the next screen, toggles between options or scrolls through multiple options that can be selected.
The system provides a prompt when a specific input is required.

PANEL OPTIONS TAB

SYSTEM�
STATUS

SYSTEM�
STATUS
ICON
2

QS-071-V1
PANIC ICONS
MENU
ALERTS
OR

**Home Screen (Page 1 shown)**

| Icon | Function |
| --- | --- |
| Armed Away | Indicates the system is armed in Away mode. |
| Armed Home | Indicates the system is armed in Home (Stay) mode |
| Armed Night | Indicates the system is armed in Night mode |
| Disarmed | Indicates the system is disarmed and Ready to Arm. |
| Not Ready | Indicates the system is disarmed and Not Ready to Arm. |
| Panic Keys | Access to programmed Panic Keys such as Fire, Police, Medical. |
|  | Displayed when Alert Message(s) are Present |


| Icon | Function |
| --- | --- |
| Alexa | Indicates Amazon Alexa has been enabled. |
| Fire | Alerts Central Station of a fire condition. (Displays zone 995) |
| Police | Alerts Central Station of a police emergency. (Displays zone 999, default is silent) |
| Medical | If programmed, alerts Central Station to other types of emergency. (Displays zone 996) |


- 20 -

![Image 1 on page 24](images/Honeywell_ProA7_ProA7Plus_Installation_Manual_p24_img1.png)


---

## Page 25

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*

**Master User Options**
Selecting the Menu icon on the Home Screen displays the User options list. Scroll up or down to view all the available options.
The list provides access to the Installer and User configurable features. Entering the Installer or Master User Code is required to
access the User Tools Menu. Additional information regarding these features can be found in the User Guide.


| Selection |  |  | Function |
| --- | --- | --- | --- |
|  |  | Menu | Provides access to menu |
|  |  | Favorites | Provides access to selected Z-Wave devices for quick access |
|  |  | Devices | Provides access to Z-Wave functions. |
|  |  | Sensors | Provides access to Zone information and options |
|  |  | Cameras | Provides access to built-in camera and Motion Viewer Captures (PROA7PLUS Only) |
|  |  | Scenes | Provides access to view and run scenes |
|  |  | Events | Provides access to system events |
|  |  | Settings | Provides access to system settings |
|  |  | Tools | Provides access to User Programming options (Installer or Master User Code required for access) |


- 21 -

---

## Page 26

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*

**Programming**
**Setting up the Communication Links**
**Note:** Do not connect to a receptacle controlled by a switch.  Allow two minutes for power-up.
1.
Plug the power supply into a 24-hour, 110VAC non-switched outlet. Upon power-up, the “Please Standby!” message
displays on the home screen.
2.
Connect the Control Panel to the local router.
Tools **→** Master User Code → Wi-Fi Settings → Scan for Network OR Manually Connect to Network OR WPS → Enter
required information OR follow prompts → OK

**Registration, Programming, and Testing**
Registration, Programming and Testing is conducted through AlarmNet 360 Programming Tool. On a laptop, PC or Smart Device, go to:
www.alarmnet360.com or use the AlarmNet360 app.

**Zone Response Type Definitions**
During programming, you must assign a zone type to each zone, which defines the way the system responds to each zone in
both the armed and disarmed states.  Zone types are defined below.


| Type | Function | Characteristics |
| --- | --- | --- |
| Not Used | Used to program a zone that is not used. | • None |
| Door/Window Delay 1 (Entry/Exit 1) | Assigned to sensors or contacts on primary entry and exit doors. | • Entry delay #1 timing is programmable. • Exit delay is independently programmable. • Exit and entry delays when armed in Away, Stay or Night Stay mode. • No entry delay when armed in Stay or Away Instant modes. • Exit delay begins regardless of the arming mode selected. |
| Door/Window Delay 2 (Entry/Exit 2) | Assigned to sensors or contacts on secondary entry and exit doors that might be further from the keypad (typically used for a garage, loading dock, or basement door). | • Entry delay #2 timing is programmable. • Exit delay is independently programmable. • Instant alarm when armed in the Stay Instant or Away Instant mode. • Exit delay begins regardless of the arming mode selected. |
| Instant Perimeter (Perimeter) | Assigned to glass break sensors or contacts on exterior doors and windows | • Instant alarm when armed in any mode and during entry/exit delays. |
| Interior Stay/Away (Interior Follower) | Assigned to motion detectors covering an area (i.e.: foyer, lobby, or hallway) that must be passed during entry/exit delays to reach the keypad. Provides an instant alarm if the entry/exit zone is not violated first and protects an area in the event an intruder gains access through an unprotected area. | • Follows entry/exit delays when the delays are active. • Instant alarm when armed in Away or Away Instant mode. • Bypassed automatically when armed in Stay, Night Stay or Stay Instant mode. |
| Motion Away Standard Delay (Interior with Delay) | Assigned to motion detectors covering an area that includes an unprotected entry/exit door. Provides entry delay (using the programmed entry time), if tripped when the system is armed in the Away mode. | • Initiates Door/Window Delay #1 (with programmed entry time) when armed in the Away mode. • Provides Entry and exit delays when armed in the Away mode. • Instant alarm when armed in the Away Instant mode. • Bypassed when the system is armed in the Stay or Stay Instant mode. • Exit delay regardless of the arming mode selected. |
| Night Zone | Assigned to motion detectors covering an area such as a basement or garage that should not be passed through during the night. Provides an instant alarm if the entry/exit zone is not violated first and protects an area in the event an intruder gains access through an unprotected area. Assigned to motion detectors that are active in Night Stay mode. | • Follows entry/exit delays when the delays are active. • Instant alarm when armed in Away, Away Instant, or Night Stay mode. • Bypassed automatically when armed in Stay or Stay Instant mode. |


- 22 -

---

## Page 27

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*
**Zone Response Type Definitions (Continued)**


| Type | Function | Characteristics |
| --- | --- | --- |
| Night Zone with Delay | Assigned to motion detectors covering an area such as a basement or garage that should not be passed through during the night. Provides an entry delay and protects an area in the event an intruder gains access through an unprotected area. Assigned to motion detectors that are active in Night Stay mode. | • Initiates Door/Window Delay #1 (with programmed entry time) when armed in the Away and Night Stay modes. • Instant alarm when armed in the Away Instant mode. • Bypassed in the Stay and Stay instant modes. • Provides Entry and exit delays when armed in Night Stay mode. |
| Day Zone (Day/Night) | Usually assigned to a zone that covers a sensitive area (i.e.: stock room, drug supply room, etc.) It can also be used on a sensor or contact in an area where immediate notification of an entry is desired. | • Instant alarm, when armed in Away, Stay, Night Stay, Stay Instant, or Away Instant mode. • Provides a latched trouble sounding from the keypad and, if desired, a Central Station report when disarmed (day). |
| 24-hour Medical | Assigned to a personal emergency button or keypad panic. This zone type is always active. | • Instant alarm, when in the armed or disarmed state (always active). • Keypad sounding only, no bell output. |
| 24-hour Auxiliary | Assigned to a zone containing a button for use in personal emergencies or to a zone containing monitoring devices (i.e.: water or temperature sensors, etc.). | • Sends a report to the Central Station and provides an alarm sound at the keypad. (There is no keypad timeout.) |
| Silent Burglary (Silent Burglary) | Assigned to sensors or contacts on exterior doors and windows where sirens are NOT desired. | • Instant alarm, with No audible indication when armed in the Away, Stay, Stay Instant, Night Stay, or Away Instant mode. • Report sent to the Central Station. |
| 24-hour CO (Carbon Monoxide) | Assigned to any wireless zone with a carbon monoxide detector. This zone type is always active and cannot be bypassed. | • Bell output, keypads and detectors provide Temporal 4 Pulse when this zone type is alarmed on all partitions. |
| Trouble Beeps Only (24 Hour Trouble) | Used with Other response type. | • The system provides a trouble sound from the keypad (and a Central Station report, if desired). |
| 24 Hour Fire (No Verification) | Assigned to any wireless zone used as a fire zone. This zone type is always active and cannot be bypassed. | • Bell output, keypads and detectors provide Temporal 3 Pulse when this zone type is alarmed on all partitions. |
| 24 Hour Fire w/ Verification (Fire with Verification) | Assigned to any wireless zone used as a fire zone. Fire with verification is available with smoke detector device type. It cannot be used with heat detectors, combination heat/smoke detectors or fire pull stations. This zone type is always active and cannot be bypassed. | • Bell output, keypads and detectors provide Temporal 3 Pulse on all partitions when this zone type is alarmed and the alarm has been verified. • System verifies alarm by delaying reporting and alarm sounding for 30 seconds after alarm is detected. If the zone remains faulted after 30 seconds a fire alarm is provided. If any other fire zone is faulted during the 30 second delay window a fire alarm is immediately provided for that zone. An alarm for original fire zone is provided, if that zone is still faulted. If there are no fire alarms after the 30 second delay expires, the system opens a 60 second window. If any fire zone is faulted during that window a fire alarm is immediately provided for that zone. |
| Non-Reporting Output (No Alarm Response) | Assigned when no-alarm response is required. Used for activating scenes or Total Connect notifications. | • No reports to the Central Station. • No keypad sounding or chime and no display on screen. • System can still be armed. |
| Monitor Zone (Monitor) | Assigned to any wireless zone used for asset protection. Works as a dynamic monitor of a zone fault/trouble (not alarm). | • Reports to the Central Station, if enabled. • Fault/restores events are logged by the system. • No keypad sounding or chime. • System can still be armed. |


- 23 -

---

## Page 28

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*


| 1-250 | Wireless Protection Points | 935 | Panel Low Battery |
| --- | --- | --- | --- |
| 280-407 | Temperature Protection Points | 936 | Panel AC Loss |
| 500-627 | Keyfob Zones | 950 | Panel Communication Failure |
| 628-659 | BLE Zones | 951 | Communication Path Failure |
| 800-831 | Touchscreens/Touchpads | 995 | Fire Panic |
| 900 | Base Unit Tamper | 996 | Medical Panic |
| 930 | RF Jam SiX Series | 998 | Silent Panic |
| 931 | RF Jam 5800 | 999 | Police Panic |
| 934 | Panel Battery Missing |  |  |



| Field Name | Programming Options | Information |
| --- | --- | --- |
| Editing AlarmNet Services |  |  |
| Supervision | Daily | This is the supervision interval the communicator sends to AlarmNet. (Not to be confused with periodic test message). |
| Advanced Protection Logic | Enabled | This communication enhancement provides added notification in the event of a panel compromise due to damaging or disabling attempts. Operation: • System is armed • Delayed zone type (i.e.; Entry/Exit or Perimeter with Comm delay) has been faulted thereby starting the programmed delay. • Contact ID alarm message sent to AlarmNet and held. • Normal disarm: If the system is disarmed within the programmed entry delay + Comm delay (if programmed), no alarm message is sent to the Central Station. • No disarm: due to real alarm or panel compromise – If the system is not disarmed, the corresponding alarm message is transmitted from AlarmNet to the Central Station. • No communication response: In the event that a communicator does not respond to AlarmNet within 15 minutes of receiving an entry alarm message, a new contact ID message E316 Tamper is sent to the Central Station. |
| Video Alarm Verification | Enabled Disabled | Video Alarm Verification is integrated with the use of up to 8 PROINDMV indoor motion viewers and Total Connect 2.0 |


- 24 -

---

## Page 29

*PROA7/PROA7PLUS Installation and Setup Guide*


| Field Name | Programming Options | Information |
| --- | --- | --- |
| Two-Way Voice | Enabled Disabled | Allows the Central Station operator to listen and/or talk to individuals on premises following receipt of an alarm report over the Cellular or Wi-Fi Communicator. The two way voice session is initiated following any burg or panic report to the Central Station. The session is not initiated for Fire, CO or duress alarms. The Two-Way Voice feature is activated in the 'Listen Mode,' allowing the Central Station operator to evaluate the situation. After the session is initiated, the panel sirens and keypad sounds are discontinued and will remain off, even if the AAV session is ended before bell timeout. The panel begins transmitting a beep acknowledgement to the Central Station once per second. The beep alternates between two separate tones, and indicates the control is awaiting a command from the Central Station Operator. If no command is received within two minutes, the session times out and the call is terminated. A new Fire or CO alarm will terminate an AAV Session in order to report. AAV Rules for Panels with multiple communication paths: a. The two-way Voice session will always utilize the alarm reporting path, unless Cellular only is selected in AlarmNet. b. Control Panels using Wi-Fi in addition to the Cellular Communicator have the option to select ‘IP with Cell Rollover’ or ‘Cell Only’ for 2-Way Voice path. If ‘Cell Only’ is selected Alarms will be sent over IP and the 2-Way voice session will go over Cell. If ‘IP with Cell Rollover’ is selected the panel will attempt to send the alarm report via Internet first. If Alarm Reporting is successful over Wi-Fi, then the two way Voice session is attempted over the Wi-Fi path, If for some reason the 2 Way Voice session “fails” to be established over the Wi-Fi path, the system will not attempt to use the cellular path for the two way Voice session. If alarm reporting over the Wi-Fi path fails, Alarm communication will automatically roll over to the cellular communication path and the resulting two-way voice session will also utilize the cell. |
| Editing Total Connect 2.0 Services |  |  |
| Total Connect 2.0 | Security Smart Security Smart Home | Select the desired Total Connect 2.0 package. |
| Video Service | None 7 Days 30 Days |  |
| Video Doorbell Service | Enabled Disabled |  |


- 25 -

---

## Page 30

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*


| Field Name | Programming Options | Information |
| --- | --- | --- |
| Select “P1: HOME PARTITION” OR “+ADD” to enable up to three additional partitions. |  |  |
| Partition Name | Home Partition Partition-02 (If enabled) Partition-03 (If enabled) Partition-04 (If enabled) | Programmable and each partition should be given a name. |
| Description |  |  |
| Partition Number | 1 2 (If enabled) 3 (If enabled) 4 (If enabled) | Not programmable |
| Entry Delay 1 | None 15 Seconds 30 Seconds 45 Seconds 60 Seconds 90 Seconds 2 Minutes 3 Minutes 4 Minutes | The time period in which you must disarm the system before an alarm condition occurs after activating a zone with response type entry/exit 1 or interior with delay assigned to it. |
| Entry Delay 2 | None 15 Seconds 30 Seconds 45 Seconds 60 Seconds 90 Seconds 2 Minutes 3 Minutes 4 Minutes | The time period in which you must disarm the system before an alarm condition occurs after activating a zone with response type entry/exit 2 assigned to it. NOTE: Must be equal to or greater than Entry Delay 1 |
| Exit Delay | 45 Seconds 60 Seconds 90 Seconds 120 Seconds | The time period in which you have to exit the premises after arming the system to any mode. |
| Arm Ding | All RF None RF KeyFob RF Keypad | Confirmation of Arm and Disarm ding is provided when 'Arm Ding' via RF Fob or RF keypad is enabled in programming. The arm ding occurs after the exit delay has expired and the disarm ding occurs immediately after disarming with a keyfob or RF keypad, and is longer than arming confirmation ding. |
| Quick Arm | Enabled Disabled | Quick Arm allows arming the system without entering a user code. Press the Away, Stay, or Night Shield to arm. |
| Force Bypass | Enabled Disabled | When Force Bypass is enabled for a Partition in programming, the user is presented with the "BYPASS & ARM" button from the Home Screen when a zone is faulted. When pressed the panel will Bypass all Faulted zones and Arm when Arm Away, Home, or Night is pressed. When Force bypass is not enabled this option is not presented, instead faulted zones must be bypassed from the Sensors screen before the user will be presented with the Arm option. |
| Chime Mode | Enabled Disabled | This toggles the chime feature on or off for the selected partition. The "Chime" feature of the system is controlled by the end user with a toggle command (Settings- >Chime). Whether or not a zone will chime is determined during initial programming or by the user in the "Sensors" section of the Tools Menu. There are 11 options to customize each zone for individual chime sounds. |


- 26 -

---

## Page 31

*PROA7/PROA7PLUS Installation and Setup Guide*


| Field Name | Programming Options | Information |
| --- | --- | --- |
| Quick Exit | Enabled Disabled | Quick Exit allows the user to press the Quick Exit button to restart the exit delay AFTER exit delay has expired only when the system is armed in HOME or NIGHT mode. This is to allow for someone to enter or exit without having to disarm the system. If Quick Exit is not enabled the Quick Exit button will not appear on the TouchScreen for the user. |
| Silent Exit | Enabled | Not programmable (always enabled) The Audible Exit warning can be disabled from any Touchscreen with each Arming by pressing 'Silent Exit' before pressing Arm Away. This will prevent the panel and remote keypads from giving Exit warning sounds for the entire duration of Exit time on this attempt. NOTE: When 'Silent Exit' is selected the panel will DOUBLE the exit delay time. |
| Power Up in previous | Enabled Disabled | Not programmable (always enabled) If the panel is powered completely down (AC and Backup Battery), it will return to its' previous state when power is restored. If the panel was armed custom with zones bypassed it will return to that same state on powerup. |
| Restart Exit Time | Enabled Disabled | Not programmable (always enabled) 'Exit Delay Restart' allows the user to press the 'Restart Timer' key any time DURING the exit delay after arming NIGHT, HOME or AWAY. to restart the Exit time. This can be done once during Away arming exit delay, and unlimited times during Home or Night arming exit delay. NOTE: When armed Away, if an entry/exit door is tripped a second time before exit delay time expires, the Exit delay time will always restart. |
| Display Exit Time | Enabled Disabled | Not programmable (always enabled) The Display will show the countdown of exit delay time in seconds on the screen of the Main Console and/or all keypads in that Partition. |
| Auto Stay Arming | Enabled Disabled | When the Partition is armed to Away and an entry/exit door was not violated within the programmed exit delay time, the Partition will automatically arm HOME at the end of Exit Delay. The panel will Auto Stay Arm when armed Away via: Main Panel or Keypad. The panel will NOT Auto Stay arm when armed Away via: Keyfob or Total Connect NOTE: If O/C reports are being sent, the system will report both Away and Stay. If the panel is armed Instant the Instant mode will remain once it changes to Auto Stay Arm. It will Arm in the Stay Instant mode. |


- 27 -

---

## Page 32

*PROA7/PROA7PLUS Installation and Setup Guide*


| Field Name | Programming Options | Information |
| --- | --- | --- |
| 1. Select "Sensors" |  |  |
| 2. Click "Add Sensor" |  |  |
| 3. Select the Sensor Type | SiX™ or Motion Viewer 5800 or Takeover |  |
| 4. Learn the MAC Address | LEARN the MAC Address OR enter the serial number | For SiX™ or Motion Viewer select "Learn" and activate the sensor as instructed in the sensors installation guide and watch the led flash rapidly, and within 20 seconds go solid for 3 seconds indicating success For 5800 or Takeover manually enter the serial number or select "Learn" and activate the sensor. NOTE: Clicking "Learn" changes the display on the PROA7/PROA7PLUS to Installer Programming and acknowledges when a sensor is enrolled. |
| 5. Partitions | Home Partition | Choose partition to assign the sensor. |
| 6. Zone Number | Enter Zone Number | Defaults to the first available zone. |
| 7. Zone Description 1 | Enter Zone Description 1 | Enter Zone Descriptor 1. Choose from the presented list for Spoken Words, or enter a custom word for display only. |
| 8. Sensor Version | Not programmable |  |
| 9. Zone Description 2 | Enter Zone Description 2 | Enter Zone Descriptor 2. Choose from the presented list for Spoken Words, or enter a custom word for display only. |
| 10. Device Type | Enter predefined word: Police, Door, Environmental, Flood, Medical, Other, Temperature, Window, Garage Door, Glass Break, and Motion Sensor | This populates based on the PROSiX transmitter type learned. Choose from the options presented, and corresponding Response type. The 'Device Type' chosen will be Spoken as the Third Zone Descriptor (unless Other is selected) |
| 11. Loop Number/Service | 1,2,3,4 (5800) Reed (PROSiX) External (PROSiX) 1 - 8 Contact (SiXC2W) | Each transmitter may support multiple services, such as PROSiXCOMBO, PROSiXSMOKE, PROSiXCT, PROSiXSHOCK, etc. Select the correct service/Loop for this zone. Select Add Service to use more services on the device. |
| 12. Supervision | RF Supervised RF Unsupervised |  |
| 13. Chime | Disabled, Standard, Melody, Melody Long, Ascend, Ascend Long, Alert 1, Alert 2, Doorbell 1, Doorbell 2, Evolve | This option is not programmable for the following Device Types: Not Used, Smoke Detector, Heat Sensor, Carbon Monoxide Detector, Medical, Fire, Other, Temperature, Police |
| 14. Response Type | Refer to Device/Response Type Matrix | Select the Zone Response type from the list presented based on the Device Type selected |
| 15. Alarm Report | Enabled Disabled | Enables/Disables Alarm Report to be sent to Central Station |
| Pet Immunity | Enabled Disabled | Only available for SiX Motion Sensors |
| Arm Night | Enabled Disabled | Only available for any sensor with a Device Type of Motion Sensor or PROINDMV Motion Viewer |
| Sensitivity | Max Sensitivity Medium Sensitivity Low Sensitivity Lowest Sensitivity | Only Available for SiX Glass Break (SiXGB) and SiXSHOCK Sensors |
| One Go / All Go | Enabled Disabled | Only available for SiX Smoke/Heat/CO Devices |


- 28 -

---

## Page 33

*PROA7/PROA7PLUS Installation and Setup Guide*

***Configuring Programming (Continued)***

**PROINDMV Setup and Configuration**

**How it works**
•
The PROINDMV passive infrared only detects while the Partition is Armed.
•
Once you enter the Sensor Walk test mode the PROINDMV PIR will start detecting and can be walk tested.
•
When Armed, during Entry delay the PROINDMV holds any captures if tripped, and if not disarmed and an alarm occurs the
captures are sent after the reporting delay expires. If disarmed before entry delay or reporting expires captures are
discarded.
•
After a capture the PROINDMV waits from 1.5 to 3 minutes before it will capture again. Maximum of 8 captures during an
Armed state based on "Number of Alarm Reports" setting.

**Configuration**

| Field Name | Programming Options | Information |
| --- | --- | --- |
| 1. Select "Sensors" |  |  |
| 2. Click "Add Sensor" |  |  |
| 3. Select the Sensor Type | SiX™ or Motion Viewer |  |
| 4. Learn the MAC Address * | LEARN the MAC Address | For SiX™ or Motion Viewer select "Learn" install the batteries in the motion viewer. The white LED will flash constantly as the device enrolls. NOTE: Clicking "Learn" changes the display on the PROA7/PROA7PLUS to Installer Programming and acknowledges when a sensor is enrolled. |
| 5. Partitions | Home Partition | Choose partition to assign the sensor. |
| 6. Zone Number | Enter Zone Number | Defaults to the first available zone. |
| 7. Zone Description 1 | Enter Zone Description 1 | Enter Zone Descriptor 1. Choose from the presented list for Spoken Words, or enter a custom word for display only. |
| 8. Zone Description 2 | Enter Zone Description 2 | Enter Zone Descriptor 2. Choose from the presented list for Spoken Words, or enter a custom word for display only. |
| 9. Device Type | IMV |  |
| 10. Supervision | RF Supervised RF Unsupervised |  |
| 11. Response Type | Perimeter, Interior Follower, or Interior With Delay |  |
| 12. Alarm Report | Enabled Disabled |  |
| 13. Arm Night | Enabled Disabled |  |
| 14. Sensitivity | High Low | Select sensitivity setting of the PIR Motion sensor |
| 15. Intrusion Type | Video Mode Intrusion Mode | Select Video Mode for 10-second video capture or Picture Mode for snap shot capture on Alarm. |


- 29 -

---

## Page 34

*PROA7/PROA7PLUS Installation and Setup Guide*


| Field Name | Programming Options | Information |
| --- | --- | --- |
| 1. Select "KeyFobs" |  |  |
| 2. Type | SiX™ |  |
| 3. Learn the MAC Address | Learn MAC Address | Select Learn and when the panel is ready Press the top two keys on the keyfob simultaneously to start the enrollment process. |
| 4. Choose the No. Of Keys | 1 Button Key 2 Button Key 4 Button Key 6 Button Key 8 Button Key | Select Keyfob Type |
| 5. Keyfob version | N/A | Displays the version of the keyfob |
| 6. Available Starting Zone | 500-624 | Select the first Zone to assign the keyfob |
| 7. Partition * | Home Partition | Select the Partition for the Keyfob |
| 8. User Name | Select User | Select a User from the Programmed List |
| 9. Button 0* *Number is variable depending on the Keyfob selected | 24 Hour Silent 24 Hour Audible 24 Hour Auxiliary Fire No Verification Arm Stay Arm Away Disarm No Response | Program an action for each button to be used |



| Field Name | Programming Options | Information |
| --- | --- | --- |
| 1. Select "Keypads" |  |  |
| 2. Keypad Type | SiX™ Keypad | Not programmable. Select LEARN |
| 3. MAC Address * | Keypad MAC Address | Press the "Learn" button to enroll the Keypad MAC Address. Follow the prompts on the keypad for proper enrollment steps. |
| 4. Zone | 800-831 |  |
| 5. Zone Description 1 |  | Enter Zone Description |
| 6. Zone Description 2 |  | Enter Zone Description |
| 7. Keypad Version |  | Not programmable |
| 8. Partition * | Home Partition | Select the Partition for the Keypad |
| 9. Supervision Interval | 15Min | Not programmable |


- 30 -

---

## Page 35

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*


| Field Name | Programming Options | Information |  |
| --- | --- | --- | --- |
| COMMUNICATOR |  |  |  |
| Alarm Reporting Number | XX-XX-XXXX Enter: 2-digit City ID 2-digit CS ID 4-digit Subscriber ID | This is the 2-digit City ID, 2-digit Central Station ID, and 4-digit account number assigned to the customer by AlarmNet. |  |
| Supervision | Daily | Not programmable |  |
| Communication Path (internal Device) | Disabled Cellular Wi-Fi Wi-Fi and Cellular |  |  |
| Old Alarm Time | 10 Minutes 15 Minutes 30 Minutes 1 Hour 2 Hours 4 Hours 8 Hours 12 Hours 24 Hours | The old alarm time sets how long an undelivered alarm is retried for delivery to the Central Station. If the message is not validated, it is retried until the old alarm time is reached or the message is validated. Once Old Alarm Time has been exceeded, the radio will clear the message from its buffer and can notify the Control Panel via trouble notification. |  |
| Wi-Fi Fault Time | 0-99 Minutes 60 Minutes | In the event the module detects a Wi-Fi communication path failure, enter the time delay (in minutes) before the module notifies the Control Panel with a trouble message. The Control Panel can then notify the Central Station over an alternate path. |  |
| Cellular Fault Time | 0-99 Minutes 60 Minutes | In the event the module detects a Cellular communication path failure, enter the time delay (in minutes) before the module notifies the Control Panel with a trouble message. The Control Panel can then notify the Central Station over an alternate path. |  |
| Cellular 24Hr Test/UL864 Comm. Fire | Enabled Disabled | If enabled, sends a 24-hour test report message over cellular network. |  |
| Cellular Rollover | Enabled Disabled | If enabled, all messages (including AlarmNet network supervisory messages) are sent over the Cellular network in the event of an Internet failure. If disabled, all messages (except AlarmNet network supervisory messages) are sent automatically over the cellular network in the event of an Internet failure. |  |
| Use DHCP | Enabled Disabled | Not programmable |  |
| SYSTEM |  |  |  |
| Alarm Report Delay | No Delay 15 Seconds 30 Seconds 45 Seconds | The Control Panel can delay the Central Station communication when a Burglary Alarm occurs. The delay applies to ALARM only, and will not apply to Fire, CO, or 24 hr panic zone types. |  |
| Burglary Alarm Sound | Enabled Disabled |  | When enabled, an audible alarm, which includes any zone |
|  |  |  | type that would activate an external sounder, |
|  |  |  | automatically increases the volume of the panel's internal |
|  |  |  | sounder to 85dB. When disabled, audible alarms will |
|  |  |  | sound from the panel at a low db sound, used for testing |
|  |  |  | purposes. NOTE: External Sounders are not disabled |
|  |  |  | when "Burg Alarm Sound" is disable. |
| Daylight Savings Time | Enabled Disabled |  |  |
| Time Zone Offset | (UTC-5:00 Eastern Time (US & Canada) |  |  |
| Software Version | XXXXXXXXXXXXXXXXX | (Viewable Only) |  |
| Temperature Unit | Fahrenheit Celsius | Select display for Z-Wave Thermostat devices |  |
| Installer Language | English |  |  |
| User Language | English | Select English, Spanish, French, or Portuguese |  |


- 31 -

---

## Page 36

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*


| Field Name | Programming Options | Information |  |
| --- | --- | --- | --- |
| Bluetooth Disarm | Enabled Disabled |  | Handsfree disarm - Supports up to 6 cell phones with |
|  |  |  | Bluetooth. Each is assigned to a user to disarm a |
|  |  |  | selected Partition based on proximity. Once the Entry |
|  |  |  | delay begins, if the User's assigned Cell phone is marked |
|  |  |  | as having left and returned, the Partition will Disarm and |
|  |  |  | Log/Report the Disarm based on that User. |
| Enable Alexa | Enabled Disabled |  | Enables or disables Amazon Alexa Voice service with |
|  |  |  | skills. Can be accessed via the Main Panel or |
|  |  |  | PROWLTOUCH Wi-Fi keypads. |
| Backlight Timeout | No 30 Seconds 2 minutes 10 minutes 30 minutes | Sets the Control Panel backlight timeout period. |  |
| Lack of Usage Notify | Disabled 7 Days 27 Days 90 Days 180 Days |  | When enabled the system notifies the Central Station if |
|  |  |  | an end user does not operate (arm/disarm) any partition |
|  |  |  | in the security system within a specified amount of time. |
|  |  |  | The time is reset per arm/disarm event. If triggered, the |
|  |  |  | system will send a System Inactivity report of E654. There |
|  |  |  | is no local annunciation indicating that the report has |
|  |  |  | been sent to the CS. |
| RF Jam Log | Disabled RF Jam Log RF Jam Log and Report | Detects a condition that may impede proper RF reception (i.e., jamming or other RF interference). RF jamming occurs when something in our frequency range (345MHz and 2.4Ghz) has been transmitting for 20 seconds or longer. In any Armed/Disarmed state it causes the display to show a triangle with an exclamation point inside and the message RF Jam with a rapid trouble beeping that can be silenced with any key press. If trouble reporting is enabled a report to Central Monitoring Station (E344 RF Receiver Jam) will be sent. Once the trouble is cleared a Restore report will be sent (R344) if Trouble Restore reporting is enabled. The reported zones are 900 for 5800 Wireless, 905 for SiX Wireless and 906 for Wiselink. NOTE: The panel can still be Armed if an RF Jam condition exists. |  |
| Burglary Bell Timeout | No 4 Minutes 8 Minutes 12 Minutes 16 Minutes | Select the time for timeout of the Burglary Alarm Sounder. |  |
| Fire Bell Timeout | No 4 Minutes 8 Minutes 12 Minutes 16 Minutes | Select the time for timeout of the Fire Alarm Sounder. |  |
| Number of Reports (Swinger Shutdown) | 1-6 2 | Limits the number of messages sent per zone to the Central Station during an armed period, and how many times the local sounder will sound per zone per armed period. Also, limits Motion Viewer captures per Armed period |  |
| First Test Report Offset | 6 Hours 12 Hours 18 Hours 24 Hours | Select the time for the first test report following power- up of the Control Panel. |  |
| Report Frequency | Never Every Day Every 7 Days Every 30 Days | Select the Report Frequency for the Periodic Test report. |  |


- 32 -

---

## Page 37

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*


| Field Name | Programming Options | Information |  |  |
| --- | --- | --- | --- | --- |
| Panel Sync Delay Time | 0 - 120 Minutes 3 Minutes |  | Select to set a delay time for the panel to sync back with |  |
|  |  |  | AlarmNet 360 when a change is made locally. |  |
| REPORT SELECTION |  |  |  |  |
| Arm Away | Enabled Disabled | Panel can report Open-Disarm/Close-Arm by user. If enabled all users will report via any path enabled. Reports User 0-96 and keyfobs also report the user number associated with the fob. Remote Arms or Power up Armed reports as User 0. Panel will report Open even if Closing report is not enabled. |  |  |
| Arm Stay | Enabled Disabled |  |  |  |
| Disarm | Enabled Disabled |  |  |  |
| Exit Error | Enabled Disabled | Not programmable (Viewable only) If the system is armed and an entry/exit or interior zone is still open after the exit delay time has expired, an alarm will sound and the entry delay timer is started. If the system is disarmed before the end of the entry delay, the alarm sounding will stop and no message will be sent to the Central Station. The system status bar will display "ALARM CANCELED" as well as Alarm and the descriptor of the zone or zones that were left open. If the system is not disarmed before the end of the entry delay mentioned above, and an entry/exit or interior zone is still open, an E374 (Exit Error Alarm) message will be sent to the Central Station, along with the Alarm on faulted zone. The message "Alarm, Exit Error" will display in the system status bar and the alarm sounding will continue until the system is disarmed (or timeout occurs). |  |  |
| Alarm Restore | Enabled Disabled |  | If enabled, all alarm restores are sent to the Central |  |
|  |  |  | Station. |  |
| Alarm Cancel | Enabled Disabled |  | Alarm Cancel is sent upon a valid code being entered at |  |
|  |  |  | Partition following an alarm condition being reported |  |
| Test | Enabled Disabled | Not programmable (Viewable only) |  |  |
| Test Restore | Enabled Disabled | Not programmable (Viewable only) |  |  |
| Low Battery | Enabled Disabled |  | If enabled, Low System battery report is sent to Central Station. |  |
|  |  |  | Station. |  |
| Low Battery Restore | Enabled Disabled |  | If enabled, Low System battery report restore is sent to Central Station. |  |
|  |  |  | Central Station. |  |
| RF Low Battery | Enabled Disabled |  | If enabled, RF Transmitter low battery report is sent to th |  |
|  |  |  | Central Station. |  |
| RF Low Battery Restore | Enabled Disabled |  | If enabled, RF Transmitter low batter restore report is sen |  |
|  |  |  | to the Central Station. |  |
| Recent Closing | Enabled Disabled | Not programmable (Viewable only) If enabled, a Recent Closing is sent to the Central Station. A Recent Closing condition is similar to an Exit Error condition, but occurs if a Burg Alarm occurs on the panel within two minutes of the exit delay expiring. If a recent closing condition occurs, both recent closing E459 by user, and the alarm report are sent. This alerts the Central Station that the Alarm may be due to User error. |  |  |
| Event Log Full | Enabled Disabled |  | If enabled, and once the event log reaches its 4,000 even | t . |
|  |  |  | capacity it sends an event log full event to Central Station |  |
| Trouble | Enabled Disabled | If enabled, reports Troubles to the Central Station. |  |  |
| Trouble Restore | Enabled Disabled | If enabled, reports Trouble restore to the Central Station. |  |  |
| Bypass | Enabled Disabled |  | If enabled, reports all zone bypasses to the Central |  |
|  |  |  | Station. |  |
| Bypass Restore | Enabled Disabled |  | If enabled, reports all zone bypass restores to the Centra |  |
|  |  |  | Station. |  |
| AC Loss | Enabled Disabled | If enabled, AC Loss reports to the Central Station. |  |  |


- 33 -

---

## Page 38

*PROA7/PROA7PLUS Installation and Setup Guide*
***Configuring Programming*** *(Continued)*


| AC Loss Restore | Enabled Disabled | If enabled, AC Loss Restore reports are sent to the Central Station. |
| --- | --- | --- |
| PANEL EVENT LOGS (Stored in Panel Memory) |  |  |
| Log All Events | Enabled Disabled | Not programmable (Viewable only) |
| Log Alarm Events | Enabled Disabled | Not programmable (Viewable only) |
| Log Open/Close Events | Enabled Disabled | Not programmable (Viewable only) |
| Log Trouble Events | Enabled Disabled | Not programmable (Viewable only) |
| Log Non Security Events | Enabled Disabled | Not programmable (Viewable only) |
| Log Bypass Events | Enabled Disabled | Not programmable (Viewable only) |


- 34 -

---

## Page 39

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation***
**Keypad/Touchscreen Operation**
The keypads and touchscreens allow the user to arm and disarm the system, and perform other system functions, such as
bypassing zones. Zone and system conditions (alarm, trouble, bypass) are displayed. When an alarm occurs, the Control Panel,
along with any keypad and touchscreen sounds, and the zone(s) in alarm is displayed. Pressing any key silences the keypad
sounder for 10 seconds (only once). Disarming the system silences all sounds. Once disarmed, any zones that were in an alarm
condition during the armed period displays (memory of alarm).  To clear alarm memory, simply repeat the disarm sequence. The
Control Panel also features chime annunciation, and three Emergency Panic keys / icons for fire, police, and medical / personal
emergency alarms.  These keys can notify the Central Station of an alarm condition, if that service is connected.


| LED | Status | Meaning |
| --- | --- | --- |
| POWER STATUS | Red - Steady | No AC power is present and battery is very low. |
|  | Green - Steady Green - Flashing | AC power is present No AC is present and unit is operating on battery power |
|  | Red - Flashing | No AC power is present and battery is low. |
|  | Amber- Steady Off | Battery is charging System/Partition is Not Ready to Arm OR in |
|  | Red - Steady Green - Steady | Programming Mode System/Partition is Armed System/Partition is Ready to |
|  | Red - Flashing | Arm Alarm detected OR Alarm in memory |
| TROUBLE | Off | System is in Programming mode OR no troubles present |
|  | Red - Steady | System trouble is present |
|  | Red - Flashing | Device trouble is present |


**Keypad Key Functions**

**Keypad Menu Mode**
This mode displays keypad programmed information and provides access to Default, Reset, LCD Brightness and
Backlight options.  Access the menu mode by holding the
key for 2 seconds.  Press
key to scroll or
the
key to exit.  This mode exits after 1 minute of no keypad activity.  See below for settings and options.


| Display | Meaning / Option |
| --- | --- |
| App: Boot: | Displays the keypad’s current App and Boot versions |
| RF6: | Displays the keypad’s SiX software version and the keypad MAC ID |
| Default Keypad | Prompts to Default Keypad. = CONFIRM to remove keypad from Control Panel. NOTE: If the keypad is repowered within 24 hours, it attempts to re-pair with the Control Panel. After 24 hours, it needs to be re-enrolled. |
| Partition= Keypad ID= | Displays Partition assignment and Keypad ID programmed in the Control Panel. |
| Reset Keypad | Prompts to Reset Keypad. = CONFIRM (restart) |
| LCD Brightness | Prompts to change LCD brightness. toggles from Low, Medium, and High |
| Backlight Adjust | Press to cycle through options for: Always Off / ON, After 1, 5, or 15 minutes |
| A: None B: None | (Future Use) (Future Use) |


**Keypad Supervision**
All keypads are supervised; however, touchscreens are NOT supervised.  If the system loses communications with a wireless
keypad for 15 minutes, the system latches into a trouble condition.  If a touchscreen loses wireless connection to the Control
Panel, it displays a black screen with “Please Standby”.  This message clears and displays status once it reconnects.

- 35 -

---

## Page 40

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued)*

**PROWLTOUCH Touchscreen Displays and Operation**
The PROWLTOUCH touchscreen duplicates the functions of the Control Panel and mirrors its displays.

**Master User Options**
Selecting the Menu icon on the PROWLTOUCH Home Screen display the User options list. The options and operations
duplicate those of the Control Panel and provide access to the Installer and User configurable features.  When entering the
Tools menu, the Installer Code provides more options than the Master Code. Additional information regarding these features
can be found in the full User Guide.


| Status LED | Meaning |
| --- | --- |
| Red - Steady | System Armed |
| Red - Flashing | Alarm/Alarm Memory |
| Amber - Steady | System trouble |
| Amber - Flashing | Device trouble – System cannot be armed |
| Green - Steady | Ready to Arm |
| Green - Flashing | Device trouble - System can be armed |
| Green & Red Alternately Flashing | System is in Programming Mode |
| Off | Not ready to Arm |


- 36 -

---

## Page 41

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued)*

**Amazon Alexa**
The Alexa feature (requires Wi-Fi) mimics the user’s Alexa device (PROA7PLUS Only), allowing access to their Alexa account.
Each PROWLTOUCH must be added to the user’s Amazon account by following this procedure.

1.  Select the
Settings option .
2.  Select Voice Services.
3.  Select Amazon Alexa (available only if Amazon Alexa has been enabled in panel programming).
4.  Accept the End User License Agreement (EULA).
5.  The system displays a link https://amazon.com/us/code and a 6-digit code.
6.  From a PC, laptop, or smart phone, go to the link and sign into the user’s Amazon account.
7.  Enter the 6-digit code displayed on the touchscreen.
8.  After a few moments, the touchscreen displays “Amazon Alexa Login.  Login Successful”.
9.  The touchscreen shows as “WTS” in the Alexa app.
10. Select “OK”.

**NOTE:** If the touchscreen is ever unpaired from a system, it resets the Alexa feature and it must be added back to the Amazon
account using the above steps.

**Events**
The Events page displays everything in the system’s Event Log.  It provides a brief description and partition(s) the event
occurred in.

**Wi-Fi Settings**
Wi-Fi settings let you connect to a wireless network via network scan, manual connection, or WPS.  This connection is for the
Control Panel to the router, not the PROWLTOUCH Touchscreen (if installed).

- 37 -

---

## Page 42

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued)*

**System Displays**
The Control Panel and PROWLTOUCH Touchscreen displays the following icons along with specific zone status information (if
applicable) to indicate system status.  The icons associated with the programmed zones are displayed on the Zones screen.
**NOTE:** Only the SiX series wireless provide specific icons based on the type of transmitter is being used.  E.g. The system
knows that a SiXPIR motion detector is programmed, so the system assigns the following icon when faulted
. Any 5800

wireless or hard wired zone is assigned the following icon,
, no matter what type of transmitter or zone it is.


| Icon |  |  | Function |
| --- | --- | --- | --- |
|  |  |  | Disarmed |
|  |  |  | Armed Away |
|  |  |  | Armed Home |
|  |  |  | Armed Night Stay |
|  |  |  | Armed Custom |
|  |  |  | Intrusion Alarm (displayed on red screen) |


| Icon | Function |
| --- | --- |
|  | Battery level |
|  | Wi-Fi Signal Strength |
|  | Bluetooth Connected |
|  | Signal Strength |
|  | AC power connected |
|  |  |


| Icon |  |  | Function |
| --- | --- | --- | --- |
|  |  |  | Fire Alarm |
|  |  |  | Police Alarm |
|  |  |  | Personal Alarm |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |


- 38 -

---

## Page 43

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued* ***)***
**Partitioning**
Up to four partitions can be used in the Control Panel which allows different areas of the premises to work independently of each
other; therefore, each can be armed and disarmed separately.  Partition one is enabled by default, the other three partitions
have to be enabled via AlarmNet 360 programming.  Partition numbers display on the PROSIXLCDKP keypad.  The control
panel and PROWLTOUCH touchscreen display the partition name to indicate which partition is being viewed.

**Goto Command**
**Control Panel and PROWLTOUCH**
Goto commands are available on the Control Panel and PROWLTOUCH Touchscreen.  Simply touch the partition drop down
(located above the status icon) and select the partition name to log onto. The user is able to access only the partitions in which
the security code is programmed. The display times out after 2-minutes of no keypad activity and automatically return to its
home partition.

**PROSIXLCDKP**
Allows users to access another partition from the Control Panel or any keypad and operate that partition.  Any security code that
has been programmed into more than one partition can perform the Goto command by typing in the security code +
+ single
digit partition number
,
,
or
.  The user is able to access only the partitions in which the security code is
programmed.  The keypad times out after 30 seconds of no keypad activity and automatically return to its home partition.

**IMPORTANT:** **Fire and CO Alarms display and sound on other partitions’ keypads and sirens.  The alarms**
**can be silenced from each partitioned keypad, but alarm memory can only be cleared from the partition’s**
**keypad / touchscreen in which the alarm occurred.**

**System Clock**
The system clock is retrieved from AlarmNet 360 automatically once the system is communicating.  The clock can be viewed at
the panel or any touchscreen.  Even though the clock is automatically set, the time zone is selectable in panel programming.
**Scheduling**
Scheduling is accomplished via Total Connect 2.0 and available to the user once a Z-Wave automation device has been
enrolled into the system. Up to 100 scenes can be programmed with various options of controlling Z-Wave Automation and auto
arm / disarm.
**Audio Alarm Verification (AAV) (Two-Way Voice)**
If this feature is enabled, a hands-free voice session can take place after an alarm signal has been sent through the cellular or
Wi-Fi network.   The Central Station can initiate the voice session and talk to homeowner on site without the homeowner
needing to touch anything.


| KEY | FUNCTION |
| --- | --- |
| 1 | Selects high-volume Talk Mode. Typically used with Key 3, Listen Mode, toggling back and forth. |
| 2 | Selects 2-Way Voice Mode allowing automatic switching between the site and the Central Station operator. |
| 3 | Selects Listen Mode. Typically used with Key 1, Talk Mode, toggling back and forth. |
| 4 | AAV session starts at the panel. Press 4 to move to each touchscreen in order and back to the panel. |
| 7 | Restarts the 5-minute voice session timeout. Sessions automatically terminate after 5 minutes unless 7 (or any other command) is entered. |
| *8n | Selects touchscreen station number where “n” is the station number. |
| 99 | Terminates the voice session. If this is not entered, the communication line stays connected for up to 5 minutes. |


- 39 -

---

## Page 44

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued)*
**Security Codes**
Up to 96 Security Codes (User Numbers) can be added, deleted, and partitioned to the Control Panel either through the
keypads, touchscreens, or the AlarmNet 360 programming tool.  There two Security Codes defaulted in the system which is the
Installer Code, user number 01, and is set to 4112; the System Master Code, user number 02, and is set to 1234 in all 4
partitions.  The Master Code can be used to enter additional 4-digit Security Codes via keypads and touchscreens while the
system is in the Disarmed state.  Security Codes cannot be added or changed while the partition is armed in any mode.

**Programming Security Codes via Control Panel or Touchscreens**

1. From the menu screen, select the
Setting option.
2. Select User Management and enter the Master Code. The system displays all current users.
3. Select a User from the displayed list to EDIT user information. The user’s Name, User Code, Partition and Authority Level
are now changeable.  Select “SAVE” when editing is complete.

4. To delete a User, select the
alongside the desired User, then select delete and enter Master Code.
5. After saving the user can edit the code to add Bluetooth Disarming and Z-Wave lock control.  See "Automation" section for
more information.

**NOTES:** Names can be applied to Security Codes so that the panel can report and log the name of the person(s) who are
arming and disarming the Control Panel.  These names can only be programmed via touchscreen or AlarmNet 360.  If
programmed in via AlarmNet 360, the names are reflected in the touchscreens.

**Authority Levels**
• **User** – Can arm, disarm, and bypass zones.
• **Arm Only** – Can arm, but cannot disarm.
• **Guest** – Can arm, but cannot disarm unless it was used to arm.  Additionally, it cannot disarm if the system was armed via the
Quick Arm feature.
• **Partition Master** – Can add and delete Security Codes just like the System Master Code, except it cannot change or delete
the System Master Code.
• **Duress** : Can arm and disarm the control, but used in case of a duress situation because it sends a report (Contact ID E121
Duress) to the Central Station when entered.
• **Master** – Is User Number 02, defaulted to 1234 in all 4 partitions, and can add and delete any Security Code in the Control
Panel. This Authority Level cannot be changed for user 02, nor can it be applied to any other user.
• **Installer** – Is User Number 01, defaulted to 4112, can arm disarm and bypass in all four partitions, but can only disarm if the
code was used to arm the Control Panel.

**Z-Wave Locks and User Code Push**
The PROA7/PROA7PLUS Control Panel can push user codes (including Duress codes) out to compatible Z-wave locks, this
provides a way to have the codes in the Lock and the Panel always match. When a user code is entered in the panel you can
select 'Z-wave Lock Control'. If you select 'YES' for ANY User, then the panel will send those enabled codes out to the Lock,
overwriting any codes in the lock so that it matches the panel. From this point the panel will keep its user codes in sync with the
Lock.
**NOTE:** If this feature is used, codes can never be added directly to the Lock, they must be added to the panel to send to the
Lock. Any codes added to Lock will be overwritten the next time the panel does a Sync.

**Keypad User Code Lockout**
This feature is always enabled. When a user has entered 5 incorrect Arm/Disarm commands within a 15-minute window and a
valid command is not executed, the system stops processing additional numeric key presses in that Partition for 15 minutes (or
until a valid keyfob is used to Disarm/Arm). The PROSIXLCD displays 'User Code Err, Keys Locked'.  The PROWLTOUCH and
Control Panel display, "Panel is Locked.  Your panel has been temporarily locked due to multiple PIN attempts."
A “Wrong Code Entry” event is entered into the Event Log and a message (Event 461 “Wrong Code Entry”) is transmitted to the
Central Station with the Partition designation. Any numeric 0-9 key press during the lockout will restart the 15-minute window.
When the lockout expires or the Lockout is cleared with a Keyfob, a Restore message is sent to the Central Station and entered
the Event Log.
**NOTES**
• RF Fobs will work during a keypad lockout, and when used will clear the lockout. Duress codes will also not operate during a
lockout.
• GoTo a Partition that is in Lockout will not function.
• Power down or reboot clears the Lockout.

- 40 -

---

## Page 45

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued* ***)***
**Disarming / Cancelling an Alarm / Clearing Alarm Memory**
• **Disarming during entry delay or alarm:** To disarm the system during the entry delay simply enter the 4-digit code on the
keypad provided on the Control Panel or PROWLTOUCH. **NOTE:** for the PROSiXLCDKP type in a valid user code +
.
• **Disarming during the exit delay:** To disarm during the exit delay press 'Cancel' in the bottom left of the screen. **NOTE:** for
the PROSiXLCDKP type in a valid user code +
.
• **Disarming while system is armed:** On the main control or PROWLTOUCH press 'Disarm' and enter the valid user code to
disarm. **NOTE:** for the PROSiXLCDKP type in a valid user code +
.
• **Clearing Alarm Memory:** To clear alarm memory on the main control or PROWLTOUCH press 'OK' on the Alarm Cancel
window. **NOTE:** for the PROSiXLCDKP type in a valid user code +
.
**NOTE:** If the alarm signal has been sent, the Cancel signal is sent once the first disarm is entered.  If the Abort Window is
enabled (30 seconds by default) and the system is disarmed from an alarm before the abort window expires, no signals are
sent.
**Rebooting the System**
The Reboot function allows you to restart the system without having to power cycle it.  This can be done from the Control Panel
or the PROWLTOUCH Touchscreen or from AlarmNet 360. To reboot the system from the Control Panel or wireless
touchscreen, perform the following:

1. Select
Tools and enter the Installer or Master / Partition Master Code.
2. Select “Reboot System”.
3. A confirmation screen appears. Select “OK”. The system restarts.
**Panic Key/Icons**
The system features three Emergency Panics for 24-hour silent, audible, fire or medical / personal alarms.  The Emergency
Panic buttons can be used to manually initiate their respective alarms and send their reports to the Central Station.  These
functions are identified by the system on the keypads and touchscreens as follows:


| PROSIXLCDKP Keypad |  |  | There are 3 ways to activate an Emergency Panic alarm: 1. Press the Panic button and within 10 seconds press the desired Emergency button (Fire, Police, Medical / Personal). 2. Press desired Emergency button and within 10 seconds press the Panic button. 3. Press desired Emergency button and within 10 seconds press the same key. NOTE: Only the programmed Emergency keys light up when the Panic key is pressed. If the Emergency key does not light up, it is not programmed. |
| --- | --- | --- | --- |
| Zone | Panic |  |  |
| 995 | Fire |  |  |
| 999 | Police |  |  |
| 996 | Medical/Personal |  |  |
| PROA7/PROA7PLUS / PROWLTOUCH |  |  | To activate an Emergency Panic alarm: 1. Touch the panic icon on the bottom left hand corner of the screen. 2. Touch the desired Emergency Icon (Fire, Police, Medical / Personal, and silent). NOTE: Only the programmed Emergency Icons display. |
| Zone | Panic |  |  |
| 995 | Fire |  |  |
| 996 | Medical/Personal |  |  |
| 998 | Silent |  |  |
| 999 | Police |  |  |


**Event Log (Events)**
The control’s event log is capable of recording and displaying up to 4,000 system events.  These events are stored locally in the
Control Panel in chronological order. When the maximum number of events is reached in the Event Log, the system overwrites
the oldest event first.  The event log can be viewed through the touchscreens by selecting the Events option from the Menu and
entering the Master Code. Refer to the control’s User Manual for additional information.  The Events displayed vary depending
upon the options that are programmed.  The table below provides definitions of the events/codes that may be transmitted to the
Central Station and/or displayed by the Control Panel.  If the event code is preceded by an “E”, it means the event is new and
ongoing.  If preceded by an “R”, it means the event has been restored.

**NOTE:** In the unlikely condition that the backup battery becomes fully discharged when AC power is lost, a low battery
condition occurs before completely discharging.  Any system activity performed after the low battery notification is not
saved in the event log.  Additionally, the control reverts to the status condition as before the low battery notification.

- 41 -

---

## Page 46

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued)*


| CID Code | Definition | Event Log Display |
| --- | --- | --- |
| 100 | Medical Alarm | Medical Alarm |
| 110 | Fire Alarm | Fire Alarm |
| 120 | Panic Alarm | Panic Alarm |
| 121 | Duress Alarm | Duress Alarm |
| 122 | Silent Alarm | Silent Alarm |
| 123 | Audible Alarm | Audible Alarm |
| 131 | Perimeter Alarm | Perimeter Alarm |
| 132 | Interior Alarm | Interior Alarm |
| 134 | Entry/Exit Alarm | Entry/Exit Alarm |
| 135 | Day/Night Alarm | Day / Night Alarm |
| 137 | Sensor Tamper Alarm | Tamper Alarm |
| 143 | Base Unit & Keypad Failure | Exp Module Failure |
| 145 | Base Unit & Keypad Tamper | Exp Module Tamper |
| 146 | Silent Burglary Alarm | Silent Burglary |
| 150 | 24-Hour Non-Burglary Alarm | 24 Hr Non-Burglary Alarm |
| 162 | Carbon Monoxide Alarm | CO Alarm |
| 301 | AC Loss Trouble | AC Loss |
| 302 | Low System Battery Trouble | System Low Battery |
| 305 | System Reset Trouble | System Reset |
| 308 | System shutdown | System shutdown |
| 309 | Battery Test Failure | Battery Test Fail |
| 311 | Battery Discharged or Not Installed | Battery Dead/Missing |
| 316 | System Tamper* | System Tamper |
| 330 | System Peripheral Trouble | System Peripheral Trouble |
| 333 | Expansion Module Failure | Exp Module Failure |
| 338 | Expansion Module Battery Failure | Exp Module Batt. Failure |
| 341 | Base Unit & Keypad Tamper Trouble | Cover Tamper |
| 344 | RF Jam Detected | RF Jam Detect |
| 350 | Communication Path Trouble | Comm. Path Trouble |
| 353 | Cellular Communication Transmitter Trouble | Cellular Comm. Trouble |
| 354 | Failure to Communicate Event | Fail to Communicate |
| 372 | Sensor Faulted | Sensor Faulted |
| 373 | Fire Trouble | Fire Trouble |
| 374 | Exit Error Alarm | Exit Error Alarm |
| 378 | Cross Zone Trouble | Cross Zone Trouble |
| 380 | Sensor Trouble | Sensor Trouble |
| 381 | Loss of RF Supervision Trouble, | Superv Loss-RF |
| 383 | Sensor Tamper Trouble | Sensor Tamper |
| 384 | RF Low Battery | RF Low Battery |
| 385 | Smoke Detector High Sensitivity Trouble | High Sense |
| 386 | Smoke Detector Low Sensitivity Trouble | Low Sense |
| 394 | Carbon Monoxide End Of Life | Carbon Monox End Of Life |
| 401 | Armed Away / Max by User | R401 - Arm Away E401 - Disarmed |
| 406 | Cancel | Cancel |
| 407 | System Armed/Disarmed Remotely | Armed/Disarmed Remotely |
| 408 | Quick Arm | Quick Arm |
| 412 | Download Okay | Download OK |
| 414 | Security Off | Security Off |
| 441 | Armed Stay / Instant by User | R441 - Arm Stay E441 - Disarmed from Stay |


- 42 -

---

## Page 47

*PROA7/PROA7PLUS Installation and Setup Guide*
***System Operation*** *(Continued* ***)***


| CID Code | Definition | Event Log Display |
| --- | --- | --- |
| 459 | Recent Close | Recent Closing |
| 461 | Wrong Code Entry | Wrong Code Entry |
| 570 | Zone/Sensor Bypass | Zone Bypass |
| 571 | Fire Zone Bypass | Fire Bypass |
| 573 | Burglary Zone Bypass | Burg Bypass |
| 601 | Manual Trigger Test Start | Man Trigger Test Start |
| 602 | Periodic Test Report | Periodic Test Rep |
| 607 | Walk Test Mode Start | Walk Test Start |
| 627 | Programming Mode Entry | Program Mode Entry |
| 628 | Programming Mode Exit | Program Mode Exit |
| 654 | System Inactivity | System Inactivity |


**Central Station Messages**
The following Contact ID messages are generated by the Control Panel’s cellular and Wi-Fi communicators for the conditions
listed.


| Alarm Condition | Alarm Code | Restore Code |
| --- | --- | --- |
| Power On / Reset | E339 00 950 |  |
| Primary Communication Path Supervision | E350 C0 951 | R350 C0 951 |
| Secondary Communication Path Supervision | E350 C0 952 | R350 C0 952 |
| Communications Failure | E359 00 950 | R359 00 950 |
| Communications Failure Reminder | P359 00 950 |  |
| New Registration | E360 00 000 |  |
| Authorized Substitution Registration | E361 00 000 |  |
| Unauthorized Substitution Registration | E362 00 000 |  |
| Test | E601 00 000 |  |


- 43 -

---

## Page 48

*PROA7/PROA7PLUS Installation and Setup Guide*
***Confirming (Testing) the System***

**TO THE INSTALLER**
Regular maintenance and inspection (at least annually) by the installer and frequent testing by the user are vital to continuous
satisfactory operation of any alarm system. The installer should assume the responsibility of developing and offering a regular
maintenance program to the user as well as acquainting the user with the proper operation and limitations of the alarm system
and its component parts. Recommendations must be included for a specific program of frequent testing (at least weekly) to
ensure the system’s proper operation at all times.

**Test Modes**
The following test modes can be initiated by touchscreen command:
• Test Communicator
• Test Sensors (Walk Test)
• Normal Mode Test
• Reporting Test (AN360)

**IMPORTANT:** Notify the Central Station to put the account on test so they do not dispatch authorities.

**Communications Tests**
There are two ways to perform Communications Tests:

• From the Control Panel or the PROWLTOUCH Touchscreen, select
Tools and enter the Master Code or Partition
Master Code then select System Tests. Select “Test Communicator” then select the desired Communication test.

- Test Wi-Fi = Test the Signal Strength, Speed, and Access to the internet.
- Test Cellular = Test the Sim Status, Signal Strength, and Access to the internet.
- Test All = Test both at the same time.
• The system displays status for Cellular and Broadband (IP).  Exit to the previous screen by selecting “<” or to the home

security screen by selecting the small
icon.
• Communication Test cannot be performed from the PROSIXLCDKP.
**NOTE:** Communication Tests can only be initiated from partition 1.

**Walk Test Mode**
Alarm signals are not sent during Walk Test Mode .
1. Walk Test can be initiated from keypads and touchscreens.
2. From the Control Panel or the PROWLTOUCH Touchscreen, select
Tools and enter the Installer Code, Master Code or
Partition Master Code then select System Tests > Test Sensors. Select "Start Test" to initiate the test mode.
3. From the PROSIXLCDKP Keypads, type in the Master Code or Partition Master Code +
+
.  Each keypad emits a
periodic beep ponce every minute as a reminder that it is still in Walk Test mode.
4. A pop-up displays, "Start Sensor Test. Please trigger sensors to see results."  Select "OK" to continue or "Cancel" to quit.
5. Upon entering Walk Test, the Sounder and all keypads (excluding touchscreens) sound for 2 seconds.
6. Fault each zone (wireless keyfobs, doors, windows, motion detectors, etc.) and listen for the Chime beeps from the keypads
and touchscreens.  All protection zones and wireless keys Chime in Walk Test mode.  The touchscreens also annunciate the
zone’s Voice Descriptor. **NOTE:** For SiX™ Wireless devices it displays the signal quality and the level of the battery, with
the exception of the SiXFob.  It only speaks the zone that it is programmed to (i.e. Zone 500).
7. To exit Walk Test Mode, select "End Test" or from the PROSIXLCD keypads type in the Installer code, Master Code, or
Partition Master Code +
. **NOTE:** The test mode timeout and exit automatically after 4 hours.

**Normal Mode Test**
With the system in the disarmed state, check that all zones are physically restored with no faults on the system.  If the system is
“not ready” check the keypads or touchscreens for the faulted zone(s). Restore the faulted zone(s) so that the “Status” LED
lights green. Fault and restore every sensor individually to assure that the zones fault and restore properly from the keypads and
touchscreens.
Additionally, the Installer can got to Settings > Secondary Keypad to see the signal strength and battery life of all the SiX RF
(PROSiXLCDKP) Keypads.

- 44 -

---

## Page 49

*PROA7/PROA7PLUS Installation and Setup Guide*
***Testing the System*** *(Continued* ***)***

**Reporting Test**
**Through the Control Panel:**
Alarm signals are sent to the Central Station during the following test.
1. Arm the system and activate zones.  Keep in mind that the Swinger Shutdown is defaulted at 2 reports per zone per armed
period (selectable 1-6), so only the first 2 signals are sent from that zone no matter how many times it was activated.  From
the Control Panel enter the 4-digit code to disarm the system on the displayed keypad.  Next, press ok to clear alarm
memory.  If using the PROSiXLCDKP disarm the system twice (4 Digit Code + 1) to clear alarm memory and then re-arm the
system to test additional zones.  The Abort Window is set to 30 seconds (selectable None–45 seconds), which means the
Control Panel waits this amount of time before sending the alarm signals after the alarm is initiated.
**NOTE:** Swinger Shutdown and Abort Window do not apply to 24hr zones such as Fire, Carbon Monoxide, and Panics.
2. Initiate each of the system’s Emergency keys to ensure proper operation and reports to the Central Station.  If the system
has been programmed for silent emergency, there are no audible alarms or displays. A report is sent to the Central Station.
3. Notify the Central Station when all tests are complete and verify the reports with them.

**Through AlarmNet 360:**
1. Click on "Reporting Test"
2. Click on "New Reporting Test" the following message appears: "This Reporting Test ensures that the alarm signal from each

sensor is reported to the Central Station. Please ensure the panel is armed before starting the test.  Please Notify the Central
Station that testing will be in progress prior to starting the reporting test. This will ensure the Central Station will not dispatch
the authorities and notify the end users."
3. Check the box next to "I have informed the Central Station."
4. Click "Start Test" and a zone list appears
5. Activate each zone and when the proper signal is received a green check mark appears in the Reporting Test Status column.
6. When complete click "Stop Test"
7. Enter a name for the test and any notes desired.
8. Press "Done" and the following prompt displays "Alarm Report Test Saved.  The test is complete.  Now you can start
monitoring the alarms."
9. Check the box next to "I have informed the Central Station"
10. Click "Finish".

- 45 -

---

## Page 50

*PROA7/PROA7PLUS Installation and Setup Guide*
***Automation***

**Introduction to Automation**

Your PROA7/PROA7PLUS is a Primary Z-Wave Controller which controls of a mesh network of wireless Z-Wave and Z-Wave
Plus ™ devices.  This system may be used with all devices certified with the Z-Wave Plus certificate and should be compatible
with such devices produced by other manufacturers.  Z-Wave products are “included” into the Controller, so once they are
programed, each device is assigned a unique address which allows them to communicate with each other and cannot be
activated by a neighbor’s Z-Wave automation system.  Z-Wave is a wireless protocol that many manufacturers can add to their
products such as in-wall light switches, in-wall outlets/receptacles, plug in lamp/appliance modules, thermostats, door locks,
garage door openers, and many more.  These devices can be individually controlled locally from the Control Panel and
Touchscreens, manually at each device, or remotely from the Total Connect 2.0 app.  The PROA7/PROA7PLUS can control as
many as 78 Z-Wave devices, which are sold separately.  Every device is enrolled into the system differently and some are more
difficult than others.  We highly recommend hiring a professional to install devices such as thermostats, in-wall switches,
receptacles, and door locks.  Other devices such as plug-in lamp modules can be easily added to your automation system,
typically by the push of a button.  Z-Wave home control networks are designed to work properly alongside wireless security
sensors, Wi-Fi, Bluetooth and other wireless devices. Some 900MHz wireless devices such as baby cams, wireless video
devices and older cordless phones may cause interference and limit Z-Wave functionality.

**Z-Wave Range**
The PROA7/PROA7PLUS security system complies with the Z-Wave Plus standard of open-air, line of sight transmission
distances of 500 feet. Actual performance in a home depends on the number of walls between the Control Panel and the
destination device, the type of construction and the number of Z-Wave devices installed in the Z-Wave network.

• Each wall or obstacle between the remote and the destination device can reduce the maximum range of 500 feet by
approximately 25-30%.  Refrigerators, large TV’s, mirrors, etc. can reduce range by much more or completely block a signal.
• Brick, tile or concrete walls block more of the RF signal than walls made of wooden studs and drywall.
• Wall-mounted Z-Wave devices installed in metal junction boxes suffer a significant loss of range (approximately 20%) since
the metal box blocks a large part of the RF signal.

**Additional Z-Wave Information**
• Z-Wave devices communicate with each other to make sure signals get from the Controller to the destination device, so the
more devices in the Z-Wave network, the better they work and the more stable the network becomes.  A signal can hop from
device to device four times to get to the destination device.  Battery operated devices, such as door locks, do not hop signals
to other devices.  This is to conserve battery power.  Only constant powered devices can hop signals.  The Controller learns
the best path (from device to device) in the network to get a signal to the destination device.

• There can be one primary controller with multiple secondary controllers in a Z-Wave network.  If you have a scenario where
a different manufacturer’s controller needs to be primary, a “Shift Controller” command can be performed; which shifts the
primary to secondary and secondary to primary, making the PROA7/PROA7PLUS the secondary controller.  If this controller
is being used as a secondary controller, use this procedure to reset this controller only if the network primary controller is
missing or otherwise inoperable.

• When included as a secondary controller, this device can support Association command class Group 1 (aka Lifeline) up to 3
node ID’s.

• Each Z-Wave device knows when it is learned into a Z-Wave network.  Once it is included into a network, it can not learn into
a different one until it is excluded (removed) from the existing one.

• The system is not aware of door locks being enabled with any temporary user shutdown feature such as Vacation Mode. The
system continues to lock/unlock a door if programmed to do so.

• Certain model of Z-Wave door locks with thumbturns allow a brief period in which the thumbturn can be operated manually
before the device locks automatically.  Locks of this type are not recommended for use with Scenes.

• Some Z-Wave devices may not communicate low-battery notifications. Please pay attention to low battery indications on
individual devices and replace batteries when the notifications appear.

• The Control Panel issues a “Failed” status on Z-Wave devices when it does not receive a response back from that device.
These devices are indicated by a
symbol on the Z-Wave Device Management menu.  This can be due to range,
interference, or the device itself.  If the Control Panel receives a signal from the device, the “Failed” status clears.

**IMPORTANT**
**Automation can ONLY be used for lifestyle enhancement.  It must not be used for personal**
**safety or property protection nor for use to control power to medical or life support equipment!**

**Z-Wave automation functionality is supplementary only and has not been evaluated by compliance**
**agency.**

- 46 -

![Image 1 on page 50](images/Honeywell_ProA7_ProA7Plus_Installation_Manual_p50_img1.png)


![Image 2 on page 50](images/Honeywell_ProA7_ProA7Plus_Installation_Manual_p50_img2.png)


---

## Page 51

*PROA7/PROA7PLUS Installation and Setup Guide*
***Automation (Continued)***

**Accessing and Controlling Z-Wave Devices**
Select
, then scroll down and select “Devices”
, and next choose “All Devices”.  This populates a list of all the currently
included (enrolled) Z-Wave devices.  From here the devices can be controlled by choosing the appropriate desired action for
each device.

**Z-Wave Device Management Screen**

Select
, then scroll down and select “Devices”
, and next choose “Z-Wave Device Management”.  This screen has the
following options:

•
Shift Controller
•
Remove All Failed
Devices
•
Enrolled Devices
•
Network Wide
Inclusion Mode
•
Update Network
•
Inclusion Mode
•
Reset the Controller
•
Local Controller Info
•
Exclusion Mode

**Enrolled Devices**
This option provides a list of all Z-Wave device enrolled in the network and their status (online, offline, etc.).
**Including (Adding) Automation Devices**
Including, or adding, devices to the network can be done locally or using AN360 (www.alarmnet360.com or the AN360 App).
The following procedure explains how to “Include” Z-Wave products along with explaining other Z-Wave features.


| Note: If using older (300 series/First Gen) Z-Wave devices with the control there will be some loss of functionality. It is |  |  |
| --- | --- | --- |
| recommended that 500 series or higher devices be used to ensure for full functionality | . |  |



| Touchscreen Display Local | AN360 |
| --- | --- |
| 1. Select . Z-Wave Management 2. Scroll down and select “Devices” . Enrolled Devices 3. From the right, select “Z-Wave Inclusion Mode Management”. Exclusion Mode 4. A keypad displays. Enter the Master or Partition Master code. Networkwide Inclusion Mode 5. Select “Inclusion Mode” if the device being added is very close to the Control Panel and can signal directly to it. QS-091-V0 _ Z-Wave_Management_1 Select “Network Wide Inclusion” if the device supports it, which is to be included through hopping signals through the Z-Wave network. NOTE: The display shows the DSK PIN when the system is put into “Learn Mode”. 6. The system is ready to include a device. Activate the device. NOTES: • Each type of Z-Wave device has its own unique way to initiate its inclusion process. Please refer to your devices instructions on how to include it into a Z- Wave Controller. • Some devices, such as door locks, may require to be within 3 feet of the Control Panel to be included into the network. Once included, it can be installed in the desired location. | 1. Login to AN360 2. Select Z-Wave Devices on the left-hand side of the screen. 3. Select “Include Devices” and the screen displays “Enter to inclusion mode please wait” then “Ready to Include device. Press the function button on device.” |


- 47 -

---

## Page 52

*PROA7/PROA7PLUS Installation and Setup Guide*


| Touchscreen Display Local | AN360 |
| --- | --- |
| 7. It indicates “1 Device Included”. Select . If a device is not including, try the following: • If possible, bring the Z-Wave device closer to the Control Panel. • Try going through the excluding procedure in the next section. If the device was tested in a different network and not excluded, it can not include into a different network until it receives an exclusion signal. Then try to include it again. 8. By default, when a device is included into the system, it has its own generic name such as “Device 1” or something similar. To rename the device, touch the device name on the left side. 9. A keyboard displays, enter the desired name of the device. Then select . NOTE: Up to 40 characters can be used to create a name, however, only the first 25 characters are shown in the “Favorites” screen, which is covered later. The new device name is displayed. Select < to go back to the device’s full screen. | 4. Include the next device, or if finished select “Abort” to return to the Z-Wave Devices screen. 5. To change the device name, select the pencil icon to the right of the device. |


**Excluding (Removing) Automation Devices**
The following procedure explain how to exclude Z-Wave products from a Z-Wave network, so they can be used in a different
network.  This can also be used if you are having problems including a device in to a network, which allows a device to be
included after being excluded.


| Touchscreen Display Local 1. Select then, scroll down and select | AN360 |
| --- | --- |
| Z-Wave Management “Devices” . From the right, select “Z- Enrolled Devices Wave Management”. 2. Enter the Master or Partition Master Inclusion Mode code. Exclusion Mode 3. Select “Exclusion Mode”. Networkwide Inclusion Mode QS-091-V0 _ Z-Wave_Management_1 | 1. Login to AN360 2. Select Z-Wave Devices on the left-hand side of the screen. |
| 3. It prompts you to exclude Z-Wave device by pressing the function button on the device. Typically, you would exclude the device the same way it was included. See the instructions for that device for further details. 4. It indicates “1 Device Excluded”. Select or continue excluding more devices if needed. | 3. Select “Exclude Devices” and the screen displays “Enter to exclusion mode please wait” then “Ready to exclude device. Press the function button on device.” |


- 48 -

---

## Page 53

*PROA7/PROA7PLUS Installation and Setup Guide*
***Automation (Continued)***

**Touchscreen Display**
**Local**
**AN360**
4. Exclude the next device, or if
finished select “Abort” to
return to the Z-Wave Devices
screen.
5. After you select
, the “Z-
Wave Management” page is displayed.
Select **<** to go back to the main screen.
Z-Wave Management
Enrolled Devices
Inclusion Mode
Exclusion Mode
Networkwide Inclusion Mode

QS-091-V0 _ Z-Wave_Managemen
t_1
**Network Wide Inclusion**
Network Wide Inclusion allows you to include devices through the network, not just within direct range of the
controller (Control Panel).

**Local Controller Info**
Provides the controllers Name, Security Level, Vendor Name, NodeID, and Z-Wave Role.

**Shift Controller**
Shifts the PROA7/PROA7PLUS to secondary Controller in case you have a different manufacturer’s Controller that needs to be
primary.  A Z-Wave network can have one primary controller with multiple secondary controllers.

**Update Network**
Use this after adding, removing, or relocating a Z-Wave device.  This allows the panel to remap signals to each device in the
network.

**Remove All Failed Devices**
Any device that has failed can be removed from the Controller with this function.  Use only when the device does not work in any
location and has been proven bad.

**Reset Controller**
If the Control Panel is the primary controller for your network, resetting it results in the devices in your network to be orphaned
and it is necessary after the reset to exclude and re-include all the devices in the network.  This defaults the Z-Wave Controller
in the system which removes all programmed Z-Wave devices, however, the devices do not receive an exclusion signal.  So,
when they need to be included, they need to be excluded first.

- 49 -

---

## Page 54

*PROA7/PROA7PLUS Installation and Setup Guide*
***Automation (Continued)***

**Alexa**
If you want the Alexa feature (PROA&PLUS Only), it must be enabled in “Settings” through AN360
(www.alarmnet360.com).  Each Touchscreen installed on your system, including the Control Panel, is considered a
separate device to Alexa.  The following setup procedure must be performed on the Control Panel and each
Touchscreen as desired.  In the devices section of your Alex app, the Control Panel is identified as “QSAIO” (All-In-
One) while each Touchscreen is identified as “WTS” (Wireless Touchscreen).

The Control Panel and Touchscreens supports a variety of general Alexa skills:
• Weather Update
• Flash News Briefing
• Sports Updates
• Stock Updates
• Local Traffic & Drive Time
• To Do Lists
• Add Events to Calendar
• Shopping Lists
• Direct Shopping
• Reminders
**NOTE:  Phone Calls are NOT supported on the Control Panel or Touchscreens.**
• Recipes/Meal Ideas/Wine Pairing
• Math Calculations
• Distance Calculations
• Timers
• Alarms

If using Total Connect 2.0, the account can be linked as a skill through your Alexa app.  It is linked with your Total
Connect 2.0 username and password.  Once they are linked, perform the following commands through your Alexa
devices:
• “Alexa, ask Total Connect “What is the status of my security
system?””
• “Alexa, ask Total Connect, “Is my security system armed?””
• “Alexa, tell Total Connect to Arm.”
• “Alexa, tell Total Connect to Arm Away.”

• “Alexa, tell Total Connect to Arm Stay.”
• “Alexa, tell Total Connect to run bedtime”.  (Bedtime can be
a scene programmed to turn lights off and arm the system).
• Any programmed scene can be activated from Alexa,
except for scenes that unlock doors or Disarm the system.
**NOTES:**
• Any Automation Scene programmed to run when the system is armed activates when you tell Alexa to arm your system.
• As a security feature, the system cannot be Disarmed using Alexa.  Alexa is not associated with any user codes in your
system.  Disarming requires the entry of a valid 4-digit code.
• For multi-location Total Connect 2.0 accounts, only the first (single) location in Total Connect 2.0 is supported.
• For multi-partition Control Panels, Alexa is supported from any partition. Total Connect 2.0 scenes from Alexa is supported
from partition one..
The following procedure explains how to setup Alexa on the Control Panel and Touchscreens.

**Step**
**Touchscreen Display**
**Description**

1. Select
then, scroll down and select “Settings”
.  From the right, select
“Voice Services.”
2. Select “Amazon Alexa”.
3. Enter the Master or Partition Master code.  Read the End User License
Agreement carefully.  If you accept the agreement, select
.  If you

do not agree, select
.

4. Once you accept the license agreement, you are prompted to go to the
amazon web site as described on this screen.  Log into the Amazon account
with your username and password.  Enter the 6-digit code provided from this
screen into Amazon site.
5. When the Amazon web site has indicated “Success!  Your registration is
complete.”.  The screen automatically updates and indicates “Login
Successful”.  Select
.

- 50 -

---

## Page 55

*PROA7/PROA7PLUS Installation and Setup Guide*
***Automation*** *(Continued)*


|  |  | 6. Select . Access this screen again by following steps 1-3. If you , then Alexa is not available on the device from which you logged out. If you want to re-enable the device, repeat steps 1-6 again on the device from which you logged out from. |
| --- | --- | --- |



|  |  | After the Alexa feature has been enabled on the Control Panel and each Touchscreen, the “Display & Audio Settings” screen displays a toggle button for Alexa Voice Commands on each enabled device. If Alexa is not enabled on a Touchscreen, Alexa Voice Commands are not displayed. When Alexa Voice Commands is enabled, it turns blue and Alexa can be used with all available features. If disabled, Alexa does not respond to any commands until it has been re-enabled. |
| --- | --- | --- |



|  |  | The Alexa icon is displayed in the bottom of the Home screen. Anytime you prompt “Alexa”, the bottom bar above the Alexa Logo animates in accordance with the Alexa operation and an X displays next to the Alexa icon to stop any announcements. The bottom bar also flashes yellow when there is a notification and turn red if Alexa Voice Commands has been disabled. |
| --- | --- | --- |
|  |  |  |


**Bluetooth Disarm**
If the “Bluetooth Disarm” feature has been enabled (PROA7PLUS Only) in “Settings” in AN360 (www.alarmnet360.com), the
system disarms as soon as a user’s Bluetooth device is connected to the system.  Multiple devices can be paired per user, but
up to a maximum of six Bluetooth devices in the system.  Each of the six Bluetooth devices can be setup in the Control Panel
and each Touchscreen.

**IMPORTANT SECURITY NOTICE**
Your Bluetooth device is similar to your house keys.  If lost or stolen, another person can compromise your security system.
Immediately notify your Dealer of a lost or stolen Bluetooth device.  Your Dealer can then disable Bluetooth programming
from your security system.

**Touchscreen Display**
**Description**

|  |  | 1. Select then, scroll down and select “Settings” .. From the right, select “User Management”. 2. A keypad is displayed. Enter the Master or Partition Master code. 3. Select the desired user from the list. |
| --- | --- | --- |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |



|  |  |  | 4. Scroll down in the user, then select “Bluetooth Disarm”. 5. Select “PAIR”. |
| --- | --- | --- | --- |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |


- 51 -

---

## Page 56

*PROA7/PROA7PLUS Installation and Setup Guide*
***Automation (Continued)***
6. The Control Panel enters pairing mode.  In the user’ device, enable Bluetooth
and look for the Control Panel or Touchscreen.  It is labelled “ProSeries-
XXXXX”, where X is the last 5 digits of its MAC address.

7. The Control Panel or Touchscreen provides a 6-digit passkey.  You may need
to enter this on your device or it may display automatically.  Select “PAIR’ on

your device and select
on the Control Panel or Touchscreen.

8. Once paired, the Control Panel displays the connected device, its MAC,
partition it is to control and its connection status.  You have the option to
“UNPAIR” the user’s device.

- 52 -

---

## Page 57

*PROA7/PROA7PLUS Installation and Setup Guide*
***Regulatory Agency Statements***
**Federal Communications Commission (FCC) & ISED Statements**
The user shall not make any changes or modifications to the equipment unless authorized by the Installation Instructions or User's Manual.  Unauthorized changes or
modifications could void the user's authority to operate the equipment.

**CLASS B DIGITAL DEVICE STATEMENT**
This equipment has been tested to FCC requirements and has been found acceptable for use. The FCC requires the following statement for your information:
This equipment generates and uses radio frequency energy and if not installed and used properly, that is, in strict accordance with the manufacturer's instructions,
may cause interference to radio and television reception. It has been type tested and found to comply with the limits for a Class B computing device in accordance
with the specifications in Part 15 of FCC Rules, which are designed to provide reasonable protection against such interference in a residential installation. However,
there is no guarantee that interference will not occur in a particular installation. If this equipment does cause interference to radio or television reception, which can
be determined by turning the equipment off and on, the user is encouraged to try to correct the interference by one or more of the following measures:
•
If using an indoor antenna, replace it with a quality outdoor antenna.

•
Reorient the receiving antenna until interference is reduced or eliminated.
•
Move the radio or television receiver away from the receiver/control.
•
Move the antenna leads away from any wire runs to the receiver/control.
•
Plug the receiver/control into a different outlet so that it and the radio or television receiver are on different branch circuits.
•
Consult the dealer or an experienced radio/TV technician for help.
This Class B digital apparatus complies with Canadian ICES-003.
Cet appareil numérique de la classe B est conforme à la norme NMB-003 du Canada .
**FCC ISED Statement**
This device complies with Part 15 of the FCC Rules, and ISED’s license-exempt RSSs. Operation is subject to the following two conditions: (1) This device may not
cause harmful interference, and  (2) This device must accept any interference received, including interference that may cause undesired operation.
Cet appareil est conforme à la partie 15 des règles de la FCC et exempt de licence RSS ISED. Son fonctionnement est soumis aux conditions suivantes: (1) Cet
appareil ne doit pas causer d’interférences nuisibles. (2) Cet appareil doit accepter toute interférence reçue y compris les interférences causant une réception
indésirable.

Responsible Party / Issuer of Supplier’s Declaration of Conformity: Honeywell International, 2 Corporate Center Drive., Melville, NY 11747, Ph: 516-577-2000.

**Agency Notices**
1.
For Residential Burglar Alarm installations with line security, total exit delay time must not exceed 60 seconds. For Burglar Alarm
installations without line security, total exit delay time must not exceed 120 seconds.
2.
Periodic testing must be at least every 24 hours.
3.
Remote downloading without an alarm company technician on-site (unattended downloading) is not permissible for ETL installations.
4.
As SIA limits for delay of alarm reporting and sounding can exceed UL Standard limits for commercial and residential applications, the
following requirements per UL681 are provided:
The maximum time that a control unit shall be programmed to delay the transmission of a signal to a remote monitoring location, or to delay
the energizing of a local alarm sounding device to permit the alarm system user to enter and disarm the system, or to arm the system and
exit shall not exceed:
a)  60 seconds for a system with standard line security or encrypted line security,
b)  120 seconds for a system without standard line security or encrypted line security, or
c)  120 seconds for a system that does not transmit an alarm signal to a remote
monitoring  location.

**RF Exposure Warning**
The antenna(s) used for this transmitter must be installed to provide a separation distance of at least 7.8 in (20 cm) from all
persons and must not be co-located or operated in conjunction with any other transmitter except in accordance with FCC and
ISED multi-transmitter product procedures.

**Mise en Garde**
**Exposition aux Frequences Radio:** La/les antenne(s) utilisée(s) pour cet émetteur doit/doivent être installée(s) à une
distance de séparation d'au moins 20 cm (7,8 pouces)  personne et ne pas être située(s) ni fonctionner parallèlement à tout
autre transmetteur ou antenne, excepté en conformité avec les procédures de produit multi transmetteur FCC et ISEDs .

**IMPORTANT NOTE ABOUT EXTERNAL ANTENNAS**
If an external cellular radio antenna is used, the antenna may be installed or replaced ONLY by a professional installer.

**To the Installer**
PROLTE-A: The external antenna gain shall not exceed 6.63 dBi for 700MHz and 850MHz, 6.0 dBi for 1700MHz and 8.5 dBi for
1900MHz. Under no conditions may an antenna gain be used that would exceed the ERP and EIRP power limits as specified in
FCC Parts 22H, 24E and 27.
PROLTE-V: The external antenna gain shall not exceed 6.94 dBi for 700MHz, 6.0 dBi for 1700MHz and 9.01 dBi for 1900MHz.
Under no conditions may an antenna gain be used that would exceed the ERP and EIRP power limits as specified in FCC Parts
22H, 24E and 27.
PROLTE-CN: The external antenna gain shall not exceed 6.63 dBi for 700MHz and 850MHz, 6.0 dBi for 1700MHz and 8.51 dBi
for 1900MHz. Under no conditions may an antenna gain be used that would exceed the ERP and EIRP power limits as specified
IC RSS-130, RSS-132, RSS-133, and RSS-139.

- 53 -

---

## Page 58

*PROA7/PROA7PLUS Installation and Setup Guide*
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
Emergency Management Agency. Some of the reasons smoke detectors used in conjunction with this System may not work are as
follows.  Smoke detectors may have been improperly installed and positioned. Smoke detectors may not sense fires that start
where smoke cannot reach the detectors, such as in chimneys, in walls, or roofs, or on the other side of closed doors. Smoke
detectors also may not sense a fire on another level of a residence or building. A second floor detector, for example, may not
sense a first floor or basement fire. Finally, smoke detectors have sensing limitations.  No smoke detector can sense every kind of
fire every time. In general, detectors may not always warn about fires caused by carelessness and safety hazards like smoking in
bed, violent explosions, escaping gas, improper storage of flammable materials, overloaded electrical circuits, children playing with
matches, or arson. Depending on the nature of the fire and/or location of the smoke detectors, the detector, even if it operates as
anticipated, may not provide sufficient warning to allow all occupants to escape in time to prevent injury or death.
•
Passive Infrared Motion Detectors can only detect intrusion within the designed ranges as diagrammed in their installation manual.
Passive Infrared Detectors do not provide volumetric area protection. They do create multiple beams of protection, and intrusion
can only be detected in unobstructed areas covered by those beams. They cannot detect motion or intrusion that takes place
behind walls, ceilings, floors, closed doors, glass partitions, glass doors, or windows.  Mechanical tampering, masking, painting or
spraying of any material on the mirrors, windows or any part of the optical system can reduce their detection ability. Passive
Infrared Detectors sense changes in temperature; however, as the ambient temperature of the protected area approaches the
temperature range of 90° to 105°F (32° to 40°C), the detection performance can decrease.
•
Alarm warning devices such as sirens, bells or horns may not alert people or wake up sleepers if they are located on the other side
of closed or partly open doors. If warning devices are located on a different level of the residence from the bedrooms, then they are
less likely to waken or alert people inside the bedrooms. Even persons who are awake may not hear the warning if the alarm is
muffled by noise from a stereo, radio, air conditioner or other appliance, or by passing traffic. Finally, alarm warning devices,
however loud, may not warn hearing-impaired people.
•
Telephone lines needed to transmit alarm signals from a premises to a central monitoring station may be out of service or
temporarily out of service. Telephone lines are also subject to compromise by sophisticated intruders.
•
Even if the system responds to the emergency as intended, however, occupants may have insufficient time to protect themselves
from the emergency situation. In the case of a monitored alarm system, authorities may not respond appropriately.
•
This equipment, like other electrical devices, is subject to component failure.  Even though this equipment is designed to last as
long as 10 years, the electronic components could fail at any time.
The most common cause of an alarm system not functioning when an intrusion or fire occurs is inadequate maintenance. This alarm
system should be tested weekly to make sure all sensors and transmitters are working properly. The security keypad (and remote
keypad) should be tested as well.
Wireless transmitters (used in some systems) are designed to provide long battery life under normal operating conditions. Longevity of
batteries may be as much as 4 to 7 years, depending on the environment, usage, and the specific wireless device being used. External
factors such as humidity, high or low temperatures, as well as large swings in temperature, may all reduce the actual battery life in a
given installation. This wireless system, however, can identify a true low battery situation, thus allowing time to arrange a change of
battery to maintain protection for that given point within the system.
Installing an alarm system may make the owner eligible for a lower insurance rate, but an alarm system is not a substitute for insurance.
Homeowners, property owners and renters should continue to act prudently in protecting themselves and continue to insure their lives
and property.
We continue to develop new and improved protection devices. Users of alarm systems owe it to themselves and their loved ones to
learn about these developments.

**Warning:** this unit includes an alarm verification feature that will result in a delay of the system alarm signal from the indicated circuits.
The total delay (control unit plus smoke detectors) shall not exceed 60 seconds. No other smoke detector shall be connected to these
circuits unless approved by the local authority having jurisdiction.

**Avertissement:** Cette unité peut être programmée pour utiliser une fonction de vérification d’alarme d’incendie qui entraîne un délai
dans la signalisation des alarmes provenant des circuits dédiés à l’incendie. Le délai total (unité de commande et détecteurs de fumée)
ne doit pas dépasser 60 secondes. Aucun autre détecteur de fumée ne doit être raccordé à ces circuits sans l’approbation des autorités
compétentes locales.

**Note:** Each protected circuit within this control is supervised.

- 54 -

---

## Page 59

*PROA7/PROA7PLUS Installation and Setup Guide*
***Specifications***

**PROA7/PROA7PLUS Series Residential Burglar and Fire Alarm Control Panel**

**Physical:**
Dimensions .......................................................................................... 7.875” (200mm) W x 5.75” (146mm) H x 1.0” (25.4mm) D
**Electrical:**
Voltage Input ............................................................................................. 110VAC, 60 Hz/9 Vdc from plug-in 2.5A power supply
Rechargeable Backup Battery  .................................................................. Lithium-ion battery pack rated at 3.6/4.2V, 7500 mAH
**Communication:**
Formats Supported .......................................................................................................................... 4-digit Contact ID® Reporting
***SIA Quick Reference Guide***


| Programming Section | Feature | Range | Shipping Default | SIA Requirement |
| --- | --- | --- | --- | --- |
| AN360 Programming Fields |  |  |  |  |
| REPORTER/ REPORT SELECTION | Exit Error | Not selectable | Enabled | Enabled |
|  | Recent Closing | Not selectable | Enabled | Enabled |
|  | Alarm Cancel | Enabled or Disabled | Enabled | Enabled |
| SYSTEM | Number of Reports | 1 to 6 | 2 | 2 |
|  | Alarm Report Delay (Abort Window) | 15, 30 and 45 seconds | 30 seconds | 30 seconds* |
| PARTITIONS | Entry Delay # 1 | None, 15, 30, 45, 60 and 90 seconds and 2, 3 or 4 minutes | 30 seconds | 30 seconds minimum |
|  | Entry Delay # 2 | None, 15, 30, 45, 60 and 90 seconds and 2, 3 or 4 minutes | 30 seconds | 30 seconds minimum |
|  | Exit Delay | 45, 60, 90 and 120 seconds | 60 Seconds | 45 seconds minimum |
|  | Restart Exit Time | Enabled or Disabled | Enabled | Enabled |
|  | Exit Warning | Not selectable | Enabled | Enabled |
|  | Auto Stay Arming | Enabled or Disabled | Enabled | Enabled |
|  | Cross Zone Delay | 30 seconds and 2 minutes (in 30 second increments), 3 minutes and 4 minutes | None (Disabled) | Enabled and two zones programmed |
| ZONES | Fire Alarms | Zone Type “Fire with Verification” must be selected for Fire Zone 95 | Disabled | Disabled |
| User Guide |  |  |  |  |
| User Functions/ User Access | Duress |  | Disabled | Disabled |
| System Functions/ Testing the System** | System Test | System tests provided as a User Function | n/a | n/a |
|  | Communications | While the system is in Test mode, no alarm reports are sent to the Central Station | Disabled | Disabled |


* Combined Entry Delay and Alarm Report Delay (Abort Window) should not exceed 1 minute.
** Refer to the User Guide for procedures on Testing the System.

- 55 -

---

## Page 60

*PROA7/PROA7PLUS Installation and Setup Guide*
**NOTES**

- 56 -

---

## Page 61

*PROA7/PROA7PLUS Installation and Setup Guide*
**NOTES**

- 57 -

---

## Page 62

*PROA7/PROA7PLUS Installation and Setup Guide*
***Contacting Technical Support***

**To view support videos,**
**scan the QR code with a**
**smart device.**

**PLEASE, before you call the Product Support Group, be sure you:**
• READ THE INSTRUCTIONS!
• Check all wiring connections.
• Determine that the power supply and/or backup battery are supplying proper voltages.
• Verify your programming information where applicable.
• Note the proper model number of this product, and the version level (if known) along with any documentation that came
with the product.

• Note your customer number and/or company name.
Having this information handy makes it easier for us to serve you quickly and effectively.

- 58 -

![Image 1 on page 62](images/Honeywell_ProA7_ProA7Plus_Installation_Manual_p62_img1.png)


---

## Page 63

*PROA7/PROA7PLUS Installation and Setup Guide*

***PROA7/PROA7PLUS RESIDENTIAL BURGLAR AND FIRE ALARM CONTROL***
***PANEL SUMMARY OF CONNECTIONS***

**Notes:** Connection of the fire alarm signal to a fire alarm headquarters or a Central Station shall be permitted with the approval
of the local authority having jurisdiction. The burglar alarm signal shall not be connected to a police emergency number. The
System must be checked by a qualified technician once every three years

- 59 -

---

## Page 64

The product should not be disposed of with other household waste. Check for the nearest authorized collection centers
or authorized recyclers. The correct disposal of end-of-life equipment will help prevent potential negative consequences
for the environment and human health.

Any attempt to reverse-engineer this device by decoding proprietary protocols, de-compiling firmware, or any similar
actions is strictly prohibited.
For support, visit: www.resideo.com
For warranty information, visit: www.security.honeywellhome.com/warranty

Resideo Technologies, Inc
2 Corporate Center Drive, Suite 100
P.O. Box 9040, Melville, NY 11747

www.resideo.com

© 2020 Resideo Technologies, Inc. All rights reserved.
The Honeywell Home trademark is used under license from Honeywell
International, Inc.
This product is manufactured by Resideo Technologies, Inc. and its affiliates.
Ê800-25082ADŠ

800-25082A 10/20  Rev. A