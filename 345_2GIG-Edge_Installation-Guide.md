# 2GIG_Edge_Installation_Guide

## Table of Contents

- [Introduction](#page-5) *(Page 5)*
  - [About this Guide](#page-5) *(Page 5)*
  - [Document Conventions](#page-5) *(Page 5)*
  - [Safety Precautions and Notations](#page-5) *(Page 5)*
  - [Technical Support](#page-5) *(Page 5)*
  - [Taking Security Innovation to the 2GIG EDGE Security Panel](#page-6) *(Page 6)*
  - [Features:](#page-6) *(Page 6)*
  - [Capabilities of the 2GIG EDGE Panel](#page-6) *(Page 6)*
  - [Introduction to Smart Areas](#page-7) *(Page 7)*
- [Internal Components](#page-8) *(Page 8)*
  - [Additional Accessories](#page-9) *(Page 9)*
  - [Kits & Keypads](#page-9) *(Page 9)*
  - [Antennas](#page-9) *(Page 9)*
  - [Sensors & Peripherals](#page-9) *(Page 9)*
  - [Smart Home Controls](#page-9) *(Page 9)*
- [Important Information](#page-10) *(Page 10)*
  - [For Residential Settings](#page-10) *(Page 10)*
  - [Operating Temperature](#page-10) *(Page 10)*
- [Planning the Installation](#page-10) *(Page 10)*
  - [Choose the Location for the Panel’s Backplate](#page-10) *(Page 10)*
  - [Recommended Tools and Equipment](#page-10) *(Page 10)*
  - [Choose the Wall Location](#page-10) *(Page 10)*
  - [Where to Place Wireless Sensors](#page-11) *(Page 11)*
  - [Where to Place Burglary Protection Sensors](#page-12) *(Page 12)*
  - [Where to Place Fire Protection Sensors](#page-12) *(Page 12)*
  - [Where NOT to Install a Smoke Alarm](#page-12) *(Page 12)*
- [Install External Attic Mount Antenna (Optional)](#page-13) *(Page 13)*
  - [Mount Antenna](#page-13) *(Page 13)*
  - [Install Jumper](#page-14) *(Page 14)*
  - [Connect the Antenna.](#page-15) *(Page 15)*
- [Mount the Panel](#page-16) *(Page 16)*
  - [Mount the Backplate to a Wall](#page-16) *(Page 16)*
  - [Connect an External Alarm Sounder](#page-17) *(Page 17)*
  - [To connect an external alarm sounder to the 2GIG EDGE Panel:](#page-17) *(Page 17)*
  - [Optional Desktop Kit](#page-17) *(Page 17)*
  - [Connect the Hardwire Loops](#page-18) *(Page 18)*
  - [To install the hardwire loop wiring for the contact sensors:](#page-18) *(Page 18)*
  - [Connect the Power Wires](#page-19) *(Page 19)*
  - [Terminal Block – Maximum Wire Gauge and Length](#page-19) *(Page 19)*
  - [Connecting the power supply to the 2GIG EDGE Panel:](#page-19) *(Page 19)*
  - [Connect Power (Barrel Connector)](#page-20) *(Page 20)*
  - [Connect the Backup Battery](#page-20) *(Page 20)*
  - [WARNING](#page-20) *(Page 20)*
  - [Replacing the Battery](#page-21) *(Page 21)*
  - [Terminal Blocks Wiring Diagram](#page-23) *(Page 23)*
  - [Control Panel Wiring Diagram](#page-24) *(Page 24)*
  - [Hang the 2GIG EDGE Panel](#page-25) *(Page 25)*
  - [Install Retaining Wall Bracket and Connect the AC Power Supply](#page-25) *(Page 25)*
  - [Update Firmware](#page-26) *(Page 26)*
- [Installer Toolbox ](#page-27) *(Page 27)*
  - [Panel Programming – Wireless Zones ￼](#page-28) *(Page 28)*
    - [Panel Programming –  Built-In Zones ￼](#page-30) *(Page 30)*
    - [Panel Programming – Keyfobs ￼](#page-33) *(Page 33)*
    - [Panel Programming – Keypads ￼](#page-35) *(Page 35)*
    - [Panel Programming – Image Sensors  ￼](#page-37) *(Page 37)*
    - [Panel Programming – Network Settings ](#page-39) *(Page 39)*
  - [Forget Network](#page-40) *(Page 40)*
  - [Join Other Network](#page-40) *(Page 40)*
  - [WPS](#page-40) *(Page 40)*
    - [Smart Home Settings ](#page-41) *(Page 41)*
    - [System Test](#page-42) *(Page 42)*
    - [Panel Programming – Advanced Programming ](#page-43) *(Page 43)*
- [Advanced Programming](#page-43) *(Page 43)*
  - [System Configuration](#page-43) *(Page 43)*
    - [Q101: Change installer code ](#page-43) *(Page 43)*
      - [Q102: Security pin code length](#page-43) *(Page 43)*
      - [Q103: Lock installer programming](#page-44) *(Page 44)*
      - [Q104: Lock default programming](#page-44) *(Page 44)*
      - [Q105: 2-way voice](#page-44) *(Page 44)*
      - [Q106: Disable siren after two-way audio](#page-44) *(Page 44)*
      - [Q107: Smart Areas ](#page-44) *(Page 44)*
      - [Q108: Z-Wave feature](#page-45) *(Page 45)*
      - [Q109: Master user can access Z-Wave setup](#page-45) *(Page 45)*
      - [Q110: Smart Home Controls require master code](#page-45) *(Page 45)*
      - [Q111: Main Panel Sounder Follows](#page-45) *(Page 45)*
      - [Q112: Z-Wave siren mode](#page-45) *(Page 45)*
      - [Q113: Quick arming](#page-45) *(Page 45)*
      - [Q114: Auto stay](#page-45) *(Page 45)*
      - [Q115: Exit delay restart](#page-46) *(Page 46)*
      - [Q116: Allow quick exit](#page-46) *(Page 46)*
      - [Q117: Quick bypass](#page-46) *(Page 46)*
      - [Q118: Auto unbypass for manual bypass](#page-46) *(Page 46)*
      - [Q119: Alert on disarm with keyfob after alarm](#page-46) *(Page 46)*
      - [Q120: Keyfob arm/disarm confirmation](#page-47) *(Page 47)*
      - [Q121: Keyfob/remote arming mode on system not ready](#page-47) *(Page 47)*
      - [Q122: Alarm cancel display](#page-47) *(Page 47)*
      - [Q123: Cross sensor zones 99-100](#page-47) *(Page 47)*
      - [Q124: Event logs](#page-47) *(Page 47)*
      - [Q125: LED Mode Control](#page-47) *(Page 47)*
      - [Q126: Commercial Burglary Support](#page-47) *(Page 47)*
  - [Timers, Delays & Counts](#page-48) *(Page 48)*
    - [Q201: Exit delay, in seconds](#page-48) *(Page 48)*
      - [Q202: Entry delay 1, in seconds](#page-48) *(Page 48)*
      - [Q203: Entry delay 2, in seconds](#page-48) *(Page 48)*
      - [Q204: Alarm cancel time, in minutes](#page-48) *(Page 48)*
      - [Q205: Alarm abort window transmission delay](#page-48) *(Page 48)*
      - [Q206: Burglary bell cutoff time](#page-48) *(Page 48)*
      - [Q207: Fire bell cutoff time](#page-49) *(Page 49)*
      - [Q208: Swinger shutdown count](#page-49) *(Page 49)*
      - [Q209: Cross sensor timeout, in seconds](#page-49) *(Page 49)*
      - [Q210: Time to detect AC loss, in minutes](#page-49) *(Page 49)*
      - [Q211: Random AC loss report time](#page-49) *(Page 49)*
      - [Q212: Siren supervision time](#page-50) *(Page 50)*
  - [Panel Configurations](#page-50) *(Page 50)*
    - [Q301: Police emergency key](#page-50) *(Page 50)*
      - [Q302: Fire emergency key ](#page-50) *(Page 50)*
      - [Q303: Emergency key](#page-50) *(Page 50)*
      - [Q304: On-Board Camera](#page-50) *(Page 50)*
      - [Q305: Temperature display units](#page-51) *(Page 51)*
      - [Q306: Configuration change acknowledgement](#page-51) *(Page 51)*
      - [Q307: Open collector #1 output](#page-51) *(Page 51)*
      - [Q308: Open collector #2 output](#page-51) *(Page 51)*
      - [Q309: Allow backlight always on](#page-51) *(Page 51)*
  - [Troubles](#page-52) *(Page 52)*
    - [Q401: Radio modem network failure time, in minutes](#page-52) *(Page 52)*
      - [Q402: Radio network failure causes trouble](#page-52) *(Page 52)*
      - [Q403: Radio network failure reports](#page-52) *(Page 52)*
      - [Q404: Broadband network failure time in minutes](#page-52) *(Page 52)*
      - [Q405: Broadband network failure causes trouble](#page-52) *(Page 52)*
      - [Q406: Broadband network failure reports](#page-52) *(Page 52)*
      - [Q407: Trouble doesn’t sound at night](#page-53) *(Page 53)*
      - [Q408: RF jam causes trouble](#page-53) *(Page 53)*
      - [Q409: System tamper causes trouble](#page-53) *(Page 53)*
  - [CS Reporting](#page-53) *(Page 53)*
    - [Q501: CS lack of usage notification time, in days](#page-53) *(Page 53)*
      - [Q502: Periodic test, in days](#page-53) *(Page 53)*
      - [Q503: Programming mode entry reports to CS](#page-53) *(Page 53)*
      - [Q504: Trouble reports to CS](#page-54) *(Page 54)*
      - [Q505: Trouble restore reports to CS](#page-54) *(Page 54)*
      - [Q506: Manual bypass reports to CS](#page-54) *(Page 54)*
      - [Q507: Bypass restore reports to CS](#page-54) *(Page 54)*
      - [Q508: Force bypass reports](#page-54) *(Page 54)*
      - [Q509: AC loss reports to CS](#page-54) *(Page 54)*
      - [Q510: AC restore reports to CS](#page-54) *(Page 54)*
      - [Q511: System low battery reports to CS](#page-55) *(Page 55)*
      - [Q512: System low battery restore reports to CS](#page-55) *(Page 55)*
      - [Q513: RF low battery reports to CS](#page-55) *(Page 55)*
      - [Q514: Sensor low battery restore reports to CS](#page-55) *(Page 55)*
      - [Q515: System disarmed reports to CS](#page-55) *(Page 55)*
      - [Q516: System armed reports to CS](#page-55) *(Page 55)*
      - [Q517: Alarm restore reports to CS](#page-55) *(Page 55)*
      - [Q518: Smart test reports](#page-56) *(Page 56)*
  - [Restore the Factory Default Settings](#page-56) *(Page 56)*
- [2GIG EDGE Remote Keypad ](#page-56) *(Page 56)*
- [Panel Programming](#page-57) *(Page 57)*
  - [Sensor Programming Reference](#page-57) *(Page 57)*
  - [Sensor Equipment Type](#page-58) *(Page 58)*
  - [Equipment Codes](#page-58) *(Page 58)*
  - [Transmission ID (TXID)](#page-59) *(Page 59)*
  - [Normal State](#page-59) *(Page 59)*
  - [Sensor Loop](#page-59) *(Page 59)*
  - [Transmission Delay](#page-60) *(Page 60)*
  - [Voice Descriptor](#page-60) *(Page 60)*
  - [Sensor Reports](#page-61) *(Page 61)*
  - [Sensor Supervised](#page-61) *(Page 61)*
  - [Sensor Chime](#page-61) *(Page 61)*
  - [Advanced Programming Reference](#page-62) *(Page 62)*
  - [ANSI/SIA CP-01-2010 Features to Limit False Alarms](#page-66) *(Page 66)*
- [Limited Warranty](#page-67) *(Page 67)*
  - [Waste Electrical and Electronic Equipment (WEEE) Statement](#page-67) *(Page 67)*
- [WARNINGS](#page-67) *(Page 67)*
  - [Limitations of Alarm Products](#page-67) *(Page 67)*
  - [Risk of Noise Induced Hearing Loss](#page-67) *(Page 67)*


---

## Page 1

TM

2GIG EDGE
™
Security & Smart
Home System

INSTALLATION
GUIDE

![Image 1 on page 1](images/2GIG_Edge_Installation_Guide_p1_img1.jpeg)


![Image 2 on page 1](images/2GIG_Edge_Installation_Guide_p1_img2.jpeg)


---

## Page 2

**Table of Contents**

**INTRODUCTION . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5**
About this Guide .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 5
Document Conventions .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 5
Safety Precautions and Notations .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 5
Technical Support . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 5
Taking Security Innovation to the 2GIG EDGE Security Panel .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 6
Features **: .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  6**
Capabilities of the 2GIG EDGE Panel . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 6
Introduction to Smart Areas .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 7
**INTERNAL COMPONENTS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **8**
Additional Accessories . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
Kits & Keypads .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
Antennas . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
Sensors & Peripherals  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
Smart Home Controls . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 9
**IMPORTANT INFORMATION .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **10**
For Residential Settings .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
Operating Temperature . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
**PLANNING THE INSTALLATION .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **10**
Choose the Location for the Panel’s Backplate .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
Recommended Tools and Equipment .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
Choose the Wall Location  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 10
Where to Place Wireless Sensors  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 11
Where to Place Burglary Protection Sensors .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 12
Where to Place Fire Protection Sensors .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 12
Where NOT to Install a Smoke Alarm  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 12
**INSTALL EXTERNAL ATTIC MOUNT ANTENNA (OPTIONAL) .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **13**
Mount Antenna .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 13
Install Jumper .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 14
Connect the Antenna . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
**MOUNT THE PANEL .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **16**
Mount the Backplate to a Wall . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 16
Connect an External Alarm Sounder .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 17
To connect an external alarm sounder to the 2GIG EDGE Panel: .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 17
Optional Desktop Kit  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 17
Connect the Hardwire Loops .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 18
To install the hardwire loop wiring for the contact sensors: .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 18
Connect the Power Wires . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 19
Terminal Block – Maximum Wire Gauge and Length .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 19
Connecting the power supply to the 2GIG EDGE Panel: .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 19
Connect Power (Barrel Connector) .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 20
Connect the Backup Battery .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 20
WARNING . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 20
Replacing the Battery . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 21
Terminal Blocks Wiring Diagram  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 23
Control Panel Wiring Diagram .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 24
Hang the 2GIG EDGE Panel .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 25
Install Retaining Wall Bracket and Connect the AC Power Supply .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 25
Update Firmware  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 26
**INSTALLER TOOLBOX  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **27**

Panel Programming – Wireless Zones
.  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  28
Panel Programming –  Built-In Zones
.  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 30
Panel Programming – Keyfobs
.  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 33
Panel Programming – Keypads
.  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 35

Panel Programming – Image Sensors
.  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 37
Panel Programming – Network Settings  . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 39
Forget Network . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 40
Join Other Network .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  40
WPS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 40

*Installation Guide for the 2GIG EDGE Security Panel*
2

---

## Page 3

Smart Home Settings  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  41
System Test . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 42
Panel Programming – Advanced Programming  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 43
**ADVANCED PROGRAMMING .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **43**
System Configuration . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 43
Q101: Change installer code  . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 43
Q102: Security pin code length .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 43
Q103: Lock installer programming .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 44
Q104: Lock default programming . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 44
Q105: 2-way voice .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 44
Q106: Disable siren after two-way audio .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 44
Q107: Smart Areas  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 44
Q108: Z-Wave feature  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q109: Master user can access Z-Wave setup .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q110: Smart Home Controls require master code . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q111: Main Panel Sounder Follows .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q112: Z-Wave siren mode .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q113: Quick arming .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q114: Auto stay .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 45
Q115: Exit delay restart  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 46
Q116: Allow quick exit .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 46
Q117: Quick bypass .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 46
Q118: Auto unbypass for manual bypass  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 46
Q119: Alert on disarm with keyfob after alarm . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 46
Q120: Keyfob arm/disarm confirmation .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Q121: Keyfob/remote arming mode on system not ready .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Q122: Alarm cancel display .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Q123: Cross sensor zones 99-100 . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Q124: Event logs  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Q125: LED Mode Control .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Q126: Commercial Burglary Support .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 47
Timers, Delays & Counts  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q201: Exit delay, in seconds  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q202: Entry delay 1, in seconds . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q203: Entry delay 2, in seconds . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q204: Alarm cancel time, in minutes .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q205: Alarm abort window transmission delay .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q206: Burglary bell cutoff time . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 48
Q207: Fire bell cutoff time  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 49
Q208: Swinger shutdown count . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 49
Q209: Cross sensor timeout, in seconds .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 49
Q210: Time to detect AC loss, in minutes .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 49
Q211: Random AC loss report time .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 49
Q212: Siren supervision time .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 50
Panel Configurations  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 50
Q301: Police emergency key .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 50
Q302: Fire emergency key .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 50
Q303: Emergency key  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 50
Q304: On-Board Camera .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 50
Q305: Temperature display units .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 51
Q306: Configuration change acknowledgement .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 51
Q307: Open collector #1 output . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 51
Q308: Open collector #2 output . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 51
Q309: Allow backlight always on .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 51
Troubles . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q401: Radio modem network failure time, in minutes .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q402: Radio network failure causes trouble  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q403: Radio network failure reports . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q404: Broadband network failure time in minutes . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q405: Broadband network failure causes trouble .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q406: Broadband network failure reports  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 52
Q407: Trouble doesn’t sound at night  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53

Copyright © 2022 Nortek Security & Control LLC
3

---

## Page 4

Q408: RF jam causes trouble .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53
Q409: System tamper causes trouble .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53
CS Reporting . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53
Q501: CS lack of usage notification time, in days .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53
Q502: Periodic test, in days .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53
Q503: Programming mode entry reports to CS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 53
Q504: Trouble reports to CS . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q505: Trouble restore reports to CS . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q506: Manual bypass reports to CS  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q507: Bypass restore reports to CS  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q508: Force bypass reports . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q509: AC loss reports to CS  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q510: AC restore reports to CS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 54
Q511: System low battery reports to CS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q512: System low battery restore reports to CS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q513: RF low battery reports to CS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q514: Sensor low battery restore reports to CS  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q515: System disarmed reports to CS  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q516: System armed reports to CS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q517: Alarm restore reports to CS . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 55
Q518: Smart test reports .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 56
Restore the Factory Default Settings . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 56
**2GIG EDGE REMOTE KEYPAD  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **56**

**PANEL PROGRAMMING .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **57**
Sensor Programming Reference .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 57
Sensor Equipment Type .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 58
Equipment Codes .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 58
Transmission ID (TXID) .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 59
Normal State . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 59
Sensor Loop .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 59
Transmission Delay . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 60
Voice Descriptor .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 60
Sensor Reports .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 61
Sensor Supervised .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 61
Sensor Chime .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 61
Advanced Programming Reference . .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 62
ANSI/SIA CP-01-2010 Features to Limit False Alarms .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 66
**LIMITED WARRANTY  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **67**
Waste Electrical and Electronic Equipment (WEEE) Statement .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 67
**WARNINGS .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .** **67**
Limitations of Alarm Products .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 67
Risk of Noise Induced Hearing Loss .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 67

*Installation Guide for the 2GIG EDGE Security Panel*
4

---

## Page 5

**INTRODUCTION**

Before you get started, review this information.
**About this Guide**
This guide is designed for distributors, alarm dealers, and professional installers of the 2GIG EDGE Security & Smart Home System. It provides
general system information, safety precautions, and step-by-step instructions for installing and setting up the system. It is intended for use only
by professional installers who are employed by or under contract with an authorized 2GIG alarm dealer.

For a list of registered alarm dealers and distributors in your area, visit: http://www.nortekcontrol.com or http://www.2gig.com.
**Document Conventions**
This section describes the document conventions used in this guide.
**Safety Precautions and Notations**
It is imperative that you observe all of the safety precautions documented in this guide. For your safety and the safety of others, the following table
details how this guide calls special attention to information intended to safeguard life, health, and property.


| DANGER!!! This notation is used to indicate hazardous situations which, if not avoided, will result in serious injury or death. | WARNING!! This notation is used to indicate potentially hazardous situations which, if not avoided, could result in serious injury or death. |
| --- | --- |
| CAUTION! This notation is used to indicate a potentially hazardous situation which, if not avoided, could result in minor or moderate injury. | IMPORTANT: This notation is used to indicate a situation which, if not avoided, could result in property damage, equipment damage, or data loss. |
| NOTE: This notation is used to call attention to notable information that should be followed when installing, servicing, or using this product. | TIP: This notation is used to call attention to helpful hints related to using the product. |


**Technical Support**
Should you require support services for this system, contact Technical Support at Nortek Security & Control.
For support in the USA and Canada, contact Technical Support at Nortek Security & Control:
» **Phone:** 800-421-1587
» **Online:** www.nortekcontrol.com/support/
For support outside of the USA or Canada, contact your regional distributor. For a list of distributors in your region, visit the websites above.

Copyright © 2022 Nortek Security & Control LLC
5

---

## Page 6

**Taking Security Innovation to the 2GIG EDGE Security Panel**
The 2GIG EDGE panel sets a new benchmark in form and function with its sleek design that is thinner and more powerful than ever. Our on
the edge processing technology is the difference that enables touch-free disarm and the industry-first home security system with built-in face
recognition and analytics within the panel itself – so private data stays private for greater peace of mind.

Our cutting-edge enhancements include double the viewing area, higher resolution, two speakers and dual microphones, delivering superb audio
quality and 2-way voice communication. With smart home capabilities, the 2GIG EDGE panel is your competitive advantage in selling the evolution
of security and automation.

**2GIG EDGE Control Panel - Front View**
**Features** **:**

» **Face Recognition:** Built-in camera recognizes faces and can arm and disarm
the system.
» **Bluetooth disarm:** With Bluetooth capability, easily disarm the system without
touching the panel.
» **Photo snapshot:** On-board camera takes arm/disarm photos adding additional
security and peace of mind knowing user codes are used by authorized user.
» **Slideshow** **:** Videos and pictures can play on screen, making it easy to show how-
to training videos or turn the panel into a photo display.
» **Video Live View:** Cameras and doorbell cameras work with the panel, with up
to eight different camera feeds viewable directly from the panel. View four camera feeds at a time.
» **Doorbell on the Panel:** See who’s at the door and talk to them right from the panel.
» **Touchscreen Display:** A large, full-color, 7-in (17.8 cm) diagonal touchscreen with an intuitive user interface.
» **Data Privacy & 2GIG EDGE Panel processing of personal data:** Rather than sending images and private biometric data
to the Cloud for processing, 2GIG EDGE panel uses on-the-edge analytics to process and authenticate faces privately.
» **Smart Home Controls & Scenes:** Customize your living space with advance automation rules, scenes and notifications to best fit
your unique needs.
» **Geofencing:** Location services allow for the panel to activate scenes based on geo-location.
» **LTE Communication (AT&T, Verizon):** Long Term Evolution with 4G connectivity to the AT&T and Verizon network.
» **Mobile System Control:** Easily control your system remotely utilizing your Remote Service Provider app.
» **Dual Path (WiFi/Cell):** System communicates to the network using both the cellular LTE and Wi-Fi. If one service goes down for any
reason, the other is always available and communicating. Enjoy free and faster updates with Wi-Fi connection.
» **Piezo Sounder and Internal Speaker:** An 85 dB Piezo Sounder sounds external alarms. An internal speaker to delivers voice
annunciations, chimes, other system notifications.
**CAUTION!** Long or repeated exposure to sounds at or above 85 dB can lead to Noise-Induced Hearing Loss (NIHL).
» **LED Indicator:** Multi-color LED always keeps you informed of the system state.
» **Home Button:** A soft button from any screen that returns the user to the panel’s Home screen.
» **Microphone and Speaker:** A built-in microphone and speaker provide clear 2-Way Voice communication during alarm events
between users at the 2GIG EDGE Panel and operators at the Central Station.
» **24-Hour Backup Battery:** A 24-hour backup battery to support the 2GIG EDGE Panel during temporary AC power failures and
outages.
» **USB Port:** A convenient USB port at the top of the 2GIG EDGE Panel that can be used with a USB thumb drive (not supplied) to update
the system’s firmware.
» **WiFi:** The built-in WiFi module allows the system to be connected to a WiFi network for dual path communication, OTA updates, and
connection with secondary keypads.
» **Access Point:** The built-in Access Point allows for a direct connection with secondary keypads, cameras, and doorbells via WiFi
without the need to connect to a local network.
**Capabilities of the 2GIG EDGE Panel**
The system includes these capabilities:

» **Smart Areas:** The system supports a Maximum of 4 Smart Areas.  Zones may be assigned across Smart Areas to allow for
independent control. This option is disabled out of the box and can be enabled at the panel or remotely using Alarm.com dealer tools.
» **Security Codes:** The system supports a maximum of 100 unique, programmable, security codes for accessing system functions. You
are provided with one (1) Master User Code, one (1) Duress Code, and one (1) Installer Code (reserved for use by 2GIG alarm dealers and
installers), and the ability to create 98 additional user codes for accessing the system.

*Installation Guide for the 2GIG EDGE Security Panel*
6

![Image 1 on page 6](images/2GIG_Edge_Installation_Guide_p6_img1.jpeg)


---

## Page 7

» **Z-Wave and Z-Wave Plus** **and S2 Compatibility:** Installers (and Master users, if configured on the system) can add up to 232
smart home devices to communicate with the 2GIG EDGE Panel using the Z- Wave and Z-Wave Plus wireless communication protocol.
The 2GIG EDGE Panel can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufacturers
and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase
reliability of the network. This device is a security enabled Z-Wave Plus product that is able to use encrypted Z-Wave Plus messages to
communicate to other security enabled Z-Wave Plus products.
» **2-Way Voice:** Operators at the Central Station can communicate directly with end users through the 2GIG EDGE Panel. Operators can
also silently listen-in after receiving a user duress report.
» **Date, Time, and Weather Forecasts** 1 : Users can view the current date, time, and weather forecast in an easy-to-read format.
» **System Vocabulary/Voice Descriptors:** A list of vocabulary words integrates with the on-screen user interface and audio
announcements. This lets installers customize the sensor names that display on the 2GIG EDGE Panel, as well as for the audible system
announcements. For example, when someone opens the front door, the system can be set up to announce “front door”.
» **False Alarm Reduction:** The 2GIG Edge Panel conforms to Security Industry Alarm Coalition’s ANSI/SIA CP-01-2010.
» **Duress:** The system supports a Duress feature, which is a user programmable pin number. When enabled the user can enter the code if
they’re forced to do something against their will.

1 Date, Time and Weather Forecasts are supported by most Remote Service Providers in most regions.  Consult your provider to determine if this feature is enabled.

**Introduction to Smart Areas**
Smart Areas is the partitioning solution of the 2GIG EDGE Panel. Partitioning is the process of dividing security sections of a home or building into
smaller areas so that users can arm some sections of the house while leaving other areas disarmed. This provides home and building owners
both security and convenience, as it allows them to walk through their structure without concern of tripping alarms for areas they’d like to keep
secure and armed. Some examples of partitioning use cases include:

» Arming a section of a room that contains a safe that contains gun collections or valuables. These areas may not be accessed as
frequently as the other areas in the room.
» Having a portion of the home designated for use by others, such as guests or property rentals. Partitioning enables the homeowner to arm
some sections of the house they’d like to be ‘off limits’ to other people.
» Disarming the garage while the homeowner is at work to allow a package to be delivered and stored safely on the premises.
» Secure swimming pool or spa area to help reduce the risk of drowning accidents. In California, it is now required that newly-built pools
and spas include at least one safety measure, including an alarm.

Smart Areas was designed for ease of setup and everyday use. For installation, the process for adding device enrollments has been simplified. All
smart area parameters are displayed on the screen for quick scanning. This reduces time for the installer, who with legacy partitioning systems
would have to memorize the codes and work flow, in addition to working through each parameter in a list to verify them.  With the addition of
Smart Areas, the 2GIG EDGE panel becomes a self-contained partitioning panel, complete with user interface, controller, wireless transceiver, and
communicator (cell radio and/or Wi-Fi) all-in-one package. This reduces complexity for the installer. All of the equipment is self-contained; there
are no modules that require additional set up procedures.

For the end user, Smart Areas is a one-touch solution that provides Global System Access. They can now access any partition/Smart Area with
appropriate authorization. ‘Arm/Disarm’ and ‘Emergency/Panic’ functions can be accessed quickly. No matter where in the menu a user finds
themselves, all they need to do is press the ‘Home’ button and they immediately return to the ‘Arm/Disarm’ screen. Past partitioning examples
required users to swipe from screen to screen. This added time, complexity and confusion for the user. The simplified user interface will reduce
confusion and frustration for those who may not interact with their security system every day. With the common tasks up front, it’s easy to select
without having to memorize.

Copyright © 2022 Nortek Security & Control LLC
7

![Image 1 on page 7](images/2GIG_Edge_Installation_Guide_p7_img1.jpeg)


---

## Page 8

**INTERNAL COMPONENTS**

This illustration details the internal components of the 2GIG EDGE Panel.
*2GIG EDGE Panel - Internal Components*
C

D
B

E
A

F

G


| Callout | Component | Description |
| --- | --- | --- |
| A | Third Hand Hanging Strap | A durable hanging strap provides installers with an extra hand when installing and servicing the 2GIG EDGE Panel. |
| B | USB Port | A built-in USB port for updating the panel’s firmware. |
| C | Piezo Sounder | An internal 85-dB Piezo Sounder. |
| D | Terminal Block | Two terminal blocks with screw-terminal positions for connecting the 2GIG EDGE Panel to electrical power (DC IN+/DC IN –), hardwire loops/wired zones (ZONE1/ZONE2), solid state output (BELL+/BELL-), and an open collector output (OCL1/OCL2). |
| E | Backup Battery | A backup battery used with the 2GIG EDGE Panel to extend service during a power outage. |
| F | Receiver Board | The main receiver board. |
| G | Speaker | An internal speaker that sounds, navigation tones, alert tones, and supports crystal clear 2-Way Voice communication with echo suppression. |


*Installation Guide for the 2GIG EDGE Security Panel*
8

---

## Page 9

**Additional Accessories**
The installer typically sets up the system to communicate with a variety of wired and/or wireless sensors. Some sensors are visible on the wall
or ceiling, such as Wireless Smoke/Heat/Freeze Alarms and Wireless Carbon Monoxide Detectors. Others may be hidden in door jambs, such as
Recessed Door/Window Contacts. Sensors might also be installed in additional locations, such as a Glass Break Detector and a Passive Infrared
Motion Detector.

**NOTE:** A variety of 2GIG and GoControl branded devices are compatible with the 2GIG EDGE Security & Smart Home System. Sensors
manufactured by other companies may also be compatible with the system. For information, visit dealer.2gig.com

**IMPORTANT:** To ensure that the system’s sensors are operating properly, it is important for 2GIG alarm dealers and system owners to
ensure sensor batteries and wireless signals are tested at least once a year.

Depending on the specific installation, systems may also be installed with one or more of the following 2GIG accessories:
**Kits & Keypads**
» 2GIG Control Panel Desktop Kit
» 2GIG EDGE Remote Keypad
» 2GIG PAD1
**Antennas**

» 2GIG External Mount Antenna
**Sensors & Peripherals**

» 2GIG Thin Door/Window Surface Contact
» 2GIG Recessed Door/Window Contact
» 2GIG Passive Infrared (PIR) Motion Detector
» 2GIG Glass Break Detector
» 2GIG Smoke/Heat/Freeze Alarm
» 2GIG Smoke/Heat Detector
» 2GIG Panic Button Remote
» 2GIG Carbon Monoxide Sensor
» 2GIG Takeover Module
» 2GIG Doorbell
» Universal Garage Door Receiver
» 2GIG Tilt Sensor
» 2GIG Bypass Sensor
» 2GIG Flood Sensor
» 2GIG Repeater

**NOTE:** 2GIG eSeries (encrypted) & unencrypted 2GIG sensors are compatible with eSeries panels including 2GIG EDGE Panel.
**Smart Home Controls**
Consult your 2GIG alarm dealer for information about installing compatible Z-Wave smart home controls and Video Cameras including:

» Lights
» Locks
» Thermostats
» Garage Doors
» Video doorbells
» IP Cameras
» Sirens

Copyright © 2022 Nortek Security & Control LLC
9

---

## Page 10

**IMPORTANT INFORMATION**

The 2GIG EDGE Security & Smart Home System conforms to the Security Industry Alarm Coalition’s *ANSI/SIA CP-01-2010: Control Panel*
*Standard - Features for False Alarm Reduction.* The system also meets the residential security system certification criteria for the ETL Listed
Mark.

**For Residential Settings**
When installing the system in a residential setting, be aware of the following:

» **Fire warning systems must be installed in accordance with national codes:** In the United States, fire warning
systems must be installed in accordance with *ANSI/NFPA 72: National Fire Alarm and Signaling Code* and *ANSI/NFPA 70: National*
*Electric Code.* Before installing this system, always ensure that you are in compliance with any national, regional, and local laws, rules,
and/or guidelines. In Canada, the system must be installed in accordance with CAN/ULC-S540.
» **A permit may be required for this alarm system:** Some cities and municipalities may require an alarm system permit. Before
installing this system, always ensure that you are in compliance with any national, regional, and local laws, rules, and/or guidelines.
» **This system is intended for use with approved-model smoke alarms only:** For use as a smoke alarm system, there
must be at least one (1) approved 2GIG-branded smoke alarm programmed into the 2GIG EDGE Panel. See dealer.2gig.com.
» **Failure to follow ETL requirements voids this system’s ETL Listed Mark:** Failure to install the 2GIG EDGE Panel and
accessories in accordance with the ETL requirements documented in this manual voids its ETL Listed Mark.
**Operating Temperature**
The recommended storage temperature for the 2GIG EDGE Panel is -10°C to 60°C (14°F to 140°F). For optimal use, operation temperature is 0°C
to 49°C (32°F to 120°F). No altitude range limitations have been reported while transporting the 2GIG EDGE Panel.
**PLANNING THE INSTALLATION**

**Choose the Location for the Panel’s Backplate**
Before installing the system, the first step is to create an installation plan for the premises. Next, determine the mounting location for all system
components, including the 2GIG EDGE Panel and all sensors. If the system includes wired sensors, you will need to connect the wiring to the
panel’s terminal block.

**Recommended Tools and Equipment**
To install the system, these tools and equipment are recommended:
» 2-Conductor Power Wire (if connecting the panel’s power supply to the system’s terminal block)
» Drywall Saw (or Equivalent)
» Screwdrivers
» Staple Gun
» Wire Stripper

**Choose the Wall Location**
When choosing a location for mounting the 2GIG EDGE Panel, work with the end user to determine the best location. See also “Create the
Installation Plan” above. For best results, keep the following items in mind:

» Always choose an indoor location that is protected from temperature extremes.
» Always choose a location that is above ground and centrally located.
» Always choose a location where you can connect the 2GIG EDGE Panel to an unswitched outlet. Do NOT connect the 2GIG EDGE Panel to
a switch-controlled outlet.
» Always choose a location above ground level. Do NOT install the 2GIG EDGE Panel below ground level, as this can impair wireless range.
» Avoid choosing a location that can be easily viewed from doors or windows.
» Avoid choosing a location that is within reach of small children.
» Avoid choosing a location in direct sunlight.
**NOTE:** If mounting the 2GIG EDGE Panel on a wall is not an option, the 2GIG Desktop Kit can be purchased for use with the 2GIG EDGE
Security & Smart Home System. This is an accessory that lets one mount the 2GIG EDGE Panel on a stand that can be placed on a flat
surface, such as desk or counter. Use of this option may affect compliance with state or regional codes.

*Installation Guide for the 2GIG EDGE Security Panel*
10

---

## Page 11

**Where to Place Wireless Sensors**
When placing the system’s wireless sensors, it is important to remember that they communicate with the 2GIG EDGE Panel over radio frequency
(RF). This subjects the system to radio interference, which can be caused by a variety of sources, such as other RF devices, construction
materials, or even when placing sensors in close proximity to other appliances, electronic devices, or electrical wiring.

**CAUTION!** While the 2GIG EDGE Panel includes a sensitive receiver that typically allows for placement of wireless sensors in nearly
all locations, it is important to always install sensors in areas that provide the best possible signal strength. *Minimum signal strength*
*required: -90 dBm* .

To ensure the system and sensors are placed appropriately, review the following illustration.

Control Panel Location Relative to Sensors

**INCORRECT**
Sensors at the other end of the
house might be too far away
**CORRECT**
Centrally Locate
Control Panel

Control Panel Location Height

CONTROL
PANEL

CONTROL
PANEL
Basement
Basement

**CORRECT**
Mount Control Panel as HIGH
above earth level as practical
**INCORRECT**
Locating Control Panel below
earth level impairs range

Sensor Signal Loss Through Materials
90% - 100%
Of Full Power
65% - 95%
Of Full Power
10% - 70%
Of Full Power

Concrete with Steel
Reinforcement or Metal
Lath and Plaster
Wallboard and
Wood Studs
Light Concrete
Or Brick

Location of Sensors
SENSOR
Less
than
3 ft
above
slab
DOOR
DOOR
Large
metal
appliance
Wall
e
slab
Minimum
3 ft
Concrete
slab
floor
Concrete
slab
floor
(refrig.)

OR
SENSOR
SENSOR

CORRECT
INCORRECT
INCORRECT

Copyright © 2022 Nortek Security & Control LLC
11

---

## Page 12

**Where to Place Burglary Protection Sensors**
The following diagram shows a typical residential installation and the various types of wireless sensors and their function.
Burglary Protection Sensors—Residential Installation
FRONT AND SIDE DOOR SENSORS
(WITH ENTRY/EXIT DELAY)

ES
DW
DC
PIR
GB
DW
DW

**ENTRY**
**LIVING**
DW
DW
TH
**KITCHEN**

CP
DW
**DINING**
**BED**
DW
**BED**
**BATH**
**DEN**
DW
DW
DW
DW

**CP:** CONTROL PANEL
**DW:** DOOR/WINDOW SENSOR
**PIR:** MOTION DETECTOR
**GB:** GLASS BREAK SENSOR
**RK:** REMOTE KEYPAD
**ES:** EXTERNAL SIREN
**DC:** DOORBELL CAMERA
**TH:** THERMOSTAT
GB
PIR

**GARAGE**

DW
DW

RK
MAIN AND SIDE GARAGE DOOR SENSORS
(WITH ENTRY/EXIT DELAY)

DW

**Where to Place Fire Protection Sensors**
IN THE UNITED STATES, CANADA, AND OTHER COUNTRIES REQUIRED TO MEET THIS STANDARD: THIS EQUIPMENT MUST BE INSTALLED IN
ACCORDANCE WITH CHAPTER 2 of ANSI/NFPA 72: National Fire Alarm and Signaling Code (National Fire Protection Association, Batterymarch Park,
Quincy, MA 02269).

**Where NOT to Install a Smoke Alarm**
» Do NOT install a smoke alarm in a location where the normal ambient temperature is below 40°F (4.4°C) or higher than 100°F (37.8°C).
» Do NOT install a smoke alarm directly above a sink, shower, or bathtub.
» Do NOT mount a smoke alarm next to a door or window affected by drafts.
» Do NOT install near an extractor fan or air vent.
» Do NOT mount a smoke alarm outside. The alarm is designed for indoor use only.
» Do NOT mount a smoke alarm in or below a cupboard.
» Do NOT mount a smoke alarm in a location where air flow is obstructed by curtains, furniture, or other items.
» Do NOT mount a smoke alarm where dirt, dust, or grease can collect and block the sensor.
» Do NOT mount a smoke alarm where it can be knocked, damaged, or inadvertently removed.
» Do NOT place any smoke alarm within 10 ft (3.04 m) of a kitchen appliance, furnace, water heater, or other source of combustion to
minimize the risks of setting off a nuisance alarm.

*Installation Guide for the 2GIG EDGE Security Panel*
12

---

## Page 13

**INSTALL EXTERNAL ATTIC MOUNT ANTENNA (OPTIONAL)**

If you will be installing the optional External Attic Mount Antenna, follow these steps:
**Mount Antenna**

**1.** Mount the antenna plate as high as possible on a wall or in the attic ( **A** ).
**2.** Drop the antenna’s 10-foot cable down to the 2GIG EDGE Panel ( **B** ).

**3.** Remove the four screws that secure the back panel, and then carefully remove the back cover from the panel.

**4.** Feed the Antenna cable through the main opening in the panel’s mounting plate, then set the assembly aside.

Copyright © 2022 Nortek Security & Control LLC
13

![Image 1 on page 13](images/2GIG_Edge_Installation_Guide_p13_img1.png)


---

## Page 14


| Install Jumper |  |  |
| --- | --- | --- |
| 1. Carefully disconnect the existing wir Exi 2. Connect the Jumper Wire from the v should snap into place on each term 3. Insert the exposed wire from Step 1 | e from the terminal location where one side of t Terminal | he Jumper will be connected. |
|  |  |  |
|  | sing Wire Disconnected acated terminal to the vacant Jumper terminal a inal. Jumper Terminal | djacent to the Antenna Terminal. The jumper wi Antenna Terminal |
|  | Jumper Wire Jum into the available foam holder to isolate it from Insert Wire | per Terminal exposure to other board components. |
|  |  |  |


*Installation Guide for the 2GIG EDGE Security Panel*
14

---

## Page 15

**Connect the Antenna** .

**1.** Connect the antenna terminal to the board terminal. You should feel it snap into place.
**2.** Insert the antenna wire into the plastic clip.

Antenna
Wire Clip

Antenna Terminal

**3.** Secure the back plate to the panel.

Copyright © 2022 Nortek Security & Control LLC
15

---

## Page 16

**MOUNT THE PANEL**

**Mount the Backplate to a Wall**
Before mounting the 2GIG EDGE Panel in its permanent location, use the guidelines below to choose
the placement. Also ensure you have the recommended tools and equipment. See **Recommended**
**Tools and Equipment** , page 10.
LEVEL
NOT LEVEL

**1.** Remove the screw from the bottom of the panel.  A locking mechanism keeps it from being
removed from the panel.

**2.** Insert your fingers into the oval shaped hole, then pull carefully to separate the backplate
from the panel.

**3.** Position the backplate at the desired location on the wall using the attached Level to align
the panel.

**4.** Insert a pencil into the placement feature on the top of the panel and make a mark hole
locations as needed.

**5.** Cut a slot in the dry wall for the AC power cord and other electrical wiring (if needed).
**6.** Route the barrel connector for the power supply or 2-conductor wire (if connecting power to
the panel’s terminal block) through the wiring cutout.

**7.** If you are installing any additional wiring, route those wires through the cutout.
**WARNING!!** To avoid serious injury or death while wiring the terminal block connections,
do NOT connect the panel’s power supply to a power source. Always ensure that you
disconnect the backup battery before servicing the panel’s internal components.

Illustration displays both types of power connection:
Install the 2 - conductor power wires or Barrel Connector

Wall Tamper

POWER IN:
Barrel Connector

POWER IN +
POWER IN –

**8.** Attach the backplate to the wall using the four (4) wall anchors and screws
(supplied).

Back Plate
**NOTE:** The Wall Anchor is the wall tamper and MUST be anchored to work.
**9.** If desired, attach the panel’s third-hand hanging strap to the hook at the
bottom of the backplate in preparation for wire connection.

Hanger

2GIG Edge Panel (upside down)

*Installation Guide for the 2GIG EDGE Security Panel*
16

---

## Page 17

**Connect an External Alarm Sounder**
The terminal block inside the 2GIG EDGE Panel includes two (2) solid-state bell terminals (BELL+/BELL-) for an external alarm sounder. An external
alarm sounder is typically housed outside of a property, in a location that will attract the most attention, in order to scare unwanted intruders
away with an audible alarm. When choosing a location for the sounder, ensure it is protected from harsh weather (either housed indoors or in a
weatherproof box). It should also be mounted in a location where the siren can be easily heard by occupants.

» **If you are installing or replacing a new external sounder:** First, install or replace the external sounder in the desired
location. Once in place, route the wiring to the panel’s terminal block.
» **If an external sounder is already installed:** First, disconnect power to the external sounder. Ensure Panel is disconnected from
power and battery, then route the sounder’s existing wiring to the panel’s terminal block.
**IMPORTANT:** The 2GIG EDGE Panel is designed to connect to Solid-State Relay sounders only. To avoid damage to the output, do NOT
connect an Electromechanical Relay bell to the BELL+ or BELL- position on the panel’s terminal block. In addition, bell output is only
provided when the panel’s power supply is connected to an AC power source.

**To connect an external alarm sounder to the 2GIG EDGE Panel:**
**1.** Install the sounder in a secure, weatherproof location where it can be easily heard.

**2.** Disconnect the sounder from its power source.
The bell output can be programmed for supervision
to detect if the wire to the bell is cut.
**3.** Ensure the 2GIG EDGE Panel is disconnected from both the
AC power source and the backup battery.
Piezo/Siren

**4.** Route the wiring from the sounder through the wiring
cutout in the back of the 2GIG EDGE panel.
For sounders with low current  consumption or if
the Piezo siren on the sounder produces a hum
or noise, install an 820Ω resistor in parallel with
the sounder.

**5.** Connect the sounder’s wires to the BELL+ and BELL-
positions on the panel’s terminal block.

**6.** Connect the battery and AC power source.
1 : GND
2 : AUX+
**NOTE:** For sounders with low current consumption, low
current relays, or in the event that the Piezo Sounder
produces a humming sound or noise, install an 820Ω
resistor in parallel with the sounder.
3 : GND
4 : BELL+
5 : BELL–
Supervised bell output
6 - 12VDC @ 200mA
Maximum
6 : ZONE 1
*Wiring Diagram—Bell Output*
7 : ZONE 2
**TIP:** After the installation is complete, navigate to the
Panel Programming menu to configure siren supervision.
This lets the system notify both the user and the Central
Station if the wire between the external alarm sounder
and 2GIG EDGE Panel is cut. By default, this setting is
turned OFF. See “Q212: Siren supervision time.”
8 : GND
Use Solid State Sounders ONLY.
Do NOT connect to an electromechanical bell.

**Optional Desktop Kit**

**NOTE:** If necessary, the Panel can be mounted on a stand that can be placed on a flat surface, such as desk or counter using the
2GIG Desktop Kit. Keep in mind that this option may affect compliance with state or regional codes. For additional information see the
installation instructions for the 2GIG-EDG-DESK.

*Optional 2GIG Desktop Kit—Rear View*

Copyright © 2022 Nortek Security & Control LLC
17

---

## Page 18

**Connect the Hardwire Loops**
The 2GIG EDGE Panel supports up to two (2) wired zones. Typically, these zones are used for hardwired Door/Window contact sensors. You first
install the contact sensors and then route the loop wiring to the 2GIG EDGE Panel. This type of connection is commonly referred to as hardwire
loops.

**IMPORTANT:** The hardwire loops on the 2GIG EDGE Panel are designed to support contact sensors such as magnetic reed switches
or pressure pads. They are not designed for hardwire smoke detectors, carbon monoxide detectors, motion detectors, or glass break
detectors.

**TIP:** If you are planning to upgrade the existing wired security system at the home or business to a wireless system or if you have a
need to retrofit any pre-wired sensors in newer construction for wireless, you can purchase the 2GIG Hardwire Conversion Kit ( 2GIG-
TAKE-KIT1) .

**To install the hardwire loop wiring for the contact sensors:**
**1.** Install the wired contact sensors.

**2.** Route the contact sensor’s loop wire(s) through the wiring cutout in the back of the 2GIG EDGE Panel.
**3.** Use the diagram below as a guide for connecting the sensor’s loop wires to the terminal block on the 2GIG EDGE Panel.
» **Normally Closed (N/C):** Used for Normally Closed (N/C) circuits. This means the circuit on the contact switch is closed when the
magnets are aligned on the door/window contact. When armed, the 2GIG EDGE Panel activates an alarm signal when it detects that the
door or window is no longer in the normally closed state.
» **Normally Open (N/O):** Used for Normally Open (N/O) circuits. This means the circuit on the contact switch is open when the magnets
are aligned on the door/window contact. When armed, the 2GIG EDGE Panel activates an alarm signal when it detects that the door or
window is no longer in the normally open state.
» **End-of-Line Resistor (EOLR):** Used to supervise the sensor for open or short circuit conditions with an End- of-Line Resistor
(EOLR). If EOLR supervision is required, you must install a 2.2 kΩ resistor (not supplied). End of Line Resistors must be installed at the
location in the loop farthest away from the panel. This feature allow for the use of an EOL resistor for existing zones.
**NOTE:** For compliance with UL 38: Manual Signaling Boxes for Fire Alarm Systems, stranded conductors clamped under wire binding
screws or similar parts shall have the individual strands soldered together or shall be equivalently arranged.

*Wiring Diagram — Hardwire Loops*


|  |  |  | DC IN DC IN + DC IN – |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

GND
POWER IN
AUX+

GND

Bell +

Bell –

Zone 1

Zone 2

GND

**TIP:** After the installation is complete, you must program the wired zone into the 2GIG EDGE Panel. During programming, you must
define the normal state of the circuit for each wired zone. See “Program a Wired Zone.”

*Installation Guide for the 2GIG EDGE Security Panel*
18

---

## Page 19

**Connect the Power Wires**
There are two ways to connect the wires for the power supply to the 2GIG EDGE Panel:
**1.** **Terminal Block:** Securely fasten a 2-conductor power wire (not supplied) to the appropriate DC IN+/DC IN– screw positions on the
terminal block of the 2GIG EDGE Panel.

**2.** **Barrel Connector:** A plug-in power supply with a barrel connector can be plugged into the DC power adapter’s barrel jack on the
2GIG EDGE Panel 14VDC Power input.  Uses 3.5mm Barrel connector for input power as an alternate to DC IN+/DC IN– Terminal Block.

**IMPORTANT:** When selecting a wall outlet, never connect the plug-in power supply to a switch-controlled outlet.
**Terminal Block – Maximum Wire Gauge and Length**
The most common way to connect the AC power supply for the 2GIG EDGE Panel is to use the system’s terminal block. This requires you securely
fasten 2- conductor power wire (not supplied) to the appropriate DC IN+/DC IN– screw terminals.

*2GIG EDGE Panel—Terminal Block*

| American Wire Gauge (AWG) | Max Length (ft) | Max Length (meters) |
| --- | --- | --- |
| 22 AWG | 50 | 15.2 |
| 20 AWG | 80 | 24.4 |
| 22 AWG 2-pairs (19 AWG equivalent) | 110 | 33.5 |
| 18 AWG | 125 | 38.1 |


**Connecting the power supply to the 2GIG EDGE Panel:**
**1.** Locate an unswitched wall outlet for the plug-in power supply. Do NOT connect the power supply to the outlet at this time.

**2.** Route 2-conductor power wire from the plug-in
power supply through the wiring cutout on the
backplate of the 2GIG EDGE Panel. See “Connect
the Power Wires” above.

**WARNING!!** The proper wiring sequence for
the DC power supply terminal block is always
ground to ground, positive to positive, and
negative to negative. However, grounding the
2GIG EDGE Panel is NOT required for proper
operations.

**3.** Insert the positive wire into the DC IN+ terminal
position. Then tighten the terminal block’s contact
screw.

**IMPORTANT:** Do not over-tighten the terminal
block’s contact screws.

**4.** Insert the negative wire into the DC IN– terminal
position. Then tighten the terminal block’s contact
screw.

**WARNING!!** Do NOT plug the power supply
into the outlet at this time. Always complete all
system wiring and then secure the backplate to
the 2GIG EDGE Panel before connecting its power
supply to the outlet.

GND
DC IN
POWER IN
AUX+
DC IN +
GND
DC IN –
Bell +
OCL 1
Bell –
OCL 2
Zone 1
TX
Zone 2
RX
GND

Copyright © 2022 Nortek Security & Control LLC
19

---

## Page 20

**Connect Power (Barrel Connector)**
An alternate method for connecting the AC power supply for the 2GIG EDGE Panel is to use the optional barrel connector (3.5mm).
To connect the power supply’s barrel connector to the 2GIG EDGE Panel:
**1.** Locate a wall outlet for the plug-in power supply. Do NOT connect the power supply to the outlet at this time.
**IMPORTANT:** When selecting a wall outlet, never connect the plug-in power supply to a switch-controlled outlet.
**2.** Route the power wire from the plug-in power supply through the wiring cutout on the backplate of the 2GIG EDGE Panel.
**3.** Plug the barrel connector into the DC power adapter barrel jack on the back of the 2GIG EDGE Panel.


| W to 4. Afte | Barrel Connector |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- |
|  | ARNI the 2 | NG!! Do N GIG EDGE | OT plu Panel | g the powe before con | r supply into the outlet at this time. A necting its power supply to the outle | lways complete all system wiring and then secure the backplate t. |
|  | r connecting or wiring |  |  | the DC power supply on the panel, connect th |  | e backup battery (see below). |
| Conne 5. Ens sho | ct the Backup Battery ure the backup battery is properly seated in the chassis. The battery’s label should be facing up and the battery’s connector wire uld be on the left with the wire running in the empty space between the battery compartment. |  |  |  |  |  |


Battery Power Terminal
**6.** Insert the wired battery pin into the PCB battery
connector.

**7.** Plug-in the power supply to an outlet.
*2GIG EDGE Panel—Backup Battery Connector*

**WARNING**
» Batteries must not be misused.
» Lithium batteries have a cycle life, so please replace the old battery when it reaches it's service life.
» While replacing the battery pack, it’s important to handle with care. Do not drop or damage the battery. Follow replacement
instructions, and transport the old battery pack in a special battery fireproof bag. Consult local regulations to dispose old batteries.
» Must keep battery pack away from children.
» Panel will boot with only the battery connected AC power is not required to boot).  Battery should be disconnected before shipping.

*Installation Guide for the 2GIG EDGE Security Panel*
20

---

## Page 21

**Replacing the Battery**


| Follow the steps below to replace a battery in the 2GIG EDGE Panel: 1. Remove the four screws that secure the back panel, and then carefully remove the back cover from the panel. |  |  |
| --- | --- | --- |
| 2. Carefully detach the power cable from the battery to be replaced. |  | Detach |
|  | he battery to be |  |
| 3. Take hold of the battery, and carefully detach it from the panel. Note: You may need to apply a reasonable amount of force to separate the battery from the adhesive that holds it in place. |  | Remove Battery |
| Adhes 4. Peel off the adhesive strip from the back of the new battery. |  | ive Strip |


Copyright © 2022 Nortek Security & Control LLC
21

---

## Page 22


|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| Replacing the Battery (continued) |  |  |  |  |
|  |  |  |  |  |
| 4. Insert the new battery, and attach the power cable |  |  | Connect Power |  |
| 5. Replace the back cover. |  |  |  |  |


*Installation Guide for the 2GIG EDGE Security Panel*
22

---

## Page 23

**Terminal Blocks Wiring Diagram**
The 2GIG EDGE Panel includes an 8-position terminal block and a 6-position terminal block. The table below describes each position on the
terminal blocks.

**NOTE:** Terminal block accommodates up to 18 gauge wire.
*Terminal Block Positions**


|  |  |  | DC IN DC IN + DC IN – |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

GND
**9**
AUX+
**2**
**10**
GND
**3**
**11**
Bell +
**4**
**12**
Bell –
**5**
**13**
Zone 1
**6**
**14**
Zone 2
**7**
GND
**8**


| Position | Label | Description |
| --- | --- | --- |
| 1 | GND (DC OUT–) | GND (DC OUT–) |
| 2 | AUX+ | 5VDC @500mA Max |
| 3 | GND | Ground (Low Side Hardwire Zone) |
| 4 | Bell + | 5-14VDC @ 200mA Max NOTE: Bell Output is only active when the 2GIG Edge Panel is powered by the AC power source. |
| 5 | Bell – |  |
| 6 | ZONE 1 | Hardwire Loop Zone 1 |
| 7 | ZONE 2 | Hardwire Loop Zone 2 |
| 8 | GND | Ground (Low Side Hardwire Zone) |
| 9* | DC IN + | 14 VDC Power Input (+). Only provides power when the panel’s power supply is connected to an AC power source. |
| 10* | DC IN – | 14 VDC Power Input (–) |
| 11 | OCL 1 | Open Collector Output 1 |
| 12 | OCL 2 | Open Collector Output 2 |
| 13 | TX | Image Sensor TX |
| 14 | RX | Image Sensor RX |


Copyright © 2022 Nortek Security & Control LLC
23

---

## Page 24

**Control Panel Wiring Diagram**
The following diagram shows the Control Panel wiring.
*Control Panel Wiring Diagram*
Hardware loops can be
programmed as normally
open or normally closed

2.2 K +/- %5 1/4 W
Normally Closed
Contact
Example
hookup
showing
an armed
LED. The
Open Colector
output can be
programmed
to activate
during various
conditions.
Open
Collector
Output
250 mA
@ 16 VDC
Maximum
End-of-Line
Resistors
are
optional
on
hardwire
loops
1 K
UL NOTE: Wiring for
all wired sensors and
annunciators must
use UL Listed low
voltage Class 2 or
better grade wire.

2.2 K +/- %5
1/4 W
Normally
Closed
Contact
LED
Sensor and display
voltages must comply
with Class 2 low
voltage requirements
systems shall be
installed in
accordance with ANSI/
NFPA 72, CSA C22.1,
CAN/ULC S302 and
CAN/ULC S301.

Supervised
Bell Output
14 VDC
@ 200 mA
Maximum

Plug-in 14 VDC
1.7 AMP
Switching
Power Supply

Piezo
Siren

OBSERVE POLARITY
when connecting the
Power Supply

**Control**
**Panel**

9
10
3
4
5
6
7
8


|  | DC IN DC IN + DC IN – |
| --- | --- |
|  |  |
|  |  |

GND
**9**
AUX+
**2**
**10**
GND
**3**
**11**
Bell +
**4**
ALL output
voltages are
Class 2
Power provided only
when the Control
Panel’s power supply
is connected to an
AC power source
**12**
Bell –
**5**
**13**
Zone 1
**6**
**14**
Zone 2
**7**
GND
**8**

*Installation Guide for the 2GIG EDGE Security Panel*
24

---

## Page 25

**Hang the 2GIG EDGE Panel**
To hang the 2GIG EDGE Panel on the mounting plate:
**1.** Ensure all installed wiring is securely fastened.
**2.** Place the upper lip of the back of the panel chassis over the back top of the backplate, then flip the 2GIG Edge Panel downward.
**3.** Push the 2GIG EDGE Panel over the mounting bracket until it clicks into place.
**4.** Secure the lower set screw.

Back Plate
Attached to Wall

**Install Retaining Wall Bracket and Connect the AC Power Supply**
After you have completed all of the required system wiring and connected the battery backup, install the wall bracket and connect the AC power
supply to the wall receptacle.

**NOTE:** For compliance with ANSI/NFPA 70: National Electric Code in the United States, you must install the power supply
retaining bracket.

To install the wall bracket and connect the AC power supply:
**1.** Locate a wall outlet for the plug-in power supply. Do NOT connect the power supply to the receptacle.
**IMPORTANT:** When selecting a wall outlet, never connect the plug-in power supply to a switch-controlled outlet.
**2.** Peel the adhesive backing off the power supply’s retaining wall bracket and attach it to the receptacle.
**3.** Secure the bracket to the wall using the fastening screw.
**4.** Spread the ears of the retaining bracket apart. Then plug the power supply into the outlet.
*Standard Style – Center Fastener*
*Decora Style – Center Fastener*
*Secure with Fastener*


|  |  |
| --- | --- |
|  |  |


STANDARD
DECORA

DECORA
STANDARD

---

## Page 26

**Update Firmware**
As 2GIG releases firmware updates for the 2GIG EDGE Panel, download the update to a USB thumb drive and then connect it to the USB port on
the 2GIG EDGE Panel.

To update the firmware:
**1.** Download the latest firmware update from dealer.2gig.com.
**2.** Copy the firmware update to a USB thumb drive (not supplied).
**NOTE:** The USB thumb drive must be FAT/FAT 32 formatted. The system will not read an NTFS formatted thumb drive.
**3.** Remove the USB protector from the USB port on the top of the 2GIG EDGE Panel.
**4.** Insert a thumb drive storing the desired firmware version into the USB port at the top of the 2GIG EDGE Panel. The **Firmware Update**
icon appears in the **Status Icons** area and the **Firmware Update Available** from **USB Device** message appears.

*2GIG EDGE Panel—USB Port*

**5.** Tap **UPDATE** .
*Firmware Update Available from USB Device*

**NOTE:** Firmware Update Available from USB Device message appears for approximately 10 seconds. If you are not able to tap the
Update button in the message in that time, you can alternately tap the System Settings button or the Firmware Update button in the
system icons area. Then enter the Master User Code, and then tap Firmware Update to start the update process. The 2GIG EDGE Panel
turns BLACK and in a few moments, th **e Updating Firmware** message appears.

**IMPORTANT:** During the update process, do NOT disconnect the 2GIG EDGE Panel from its power source and do NOT remove the USB
thumb drive until the update is complete.

When complete, the system restarts automatically and a new message appears in the system’s Inbox to notify users that the firmware update was
successful.

**6.** Remove the USB flash drive once update is complete.
**7.** Re-install the USB protector from the USB port on the top of the 2GIG EDGE Panel
**8.** Check the panel’s firmware version to confirm that the firmware update occurred.

*Installation Guide for the 2GIG EDGE Security Panel*
26

![Image 1 on page 26](images/2GIG_Edge_Installation_Guide_p26_img1.jpeg)


![Image 2 on page 26](images/2GIG_Edge_Installation_Guide_p26_img2.jpeg)


![Image 3 on page 26](images/2GIG_Edge_Installation_Guide_p26_img3.jpeg)


---

## Page 27

**INSTALLER TOOLBOX**

The Installer Toolbox is password-protected. To use this feature, you must enter an Installer Code. The factory default code is 1561.
**REMINDER:** Change the installer code before finishing installation.
To access the Installer Toolbox :


| 1. Tap the Settings icon ( ). |  |
| --- | --- |
| 2. Tap KEYPAD. |  |
| 3. Enter 1561 to gain access to the panel settings, then tap Installer Toolbox. 4. Scroll down then tap the Installer Toolbox icon. |  |


Copyright © 2022 Nortek Security & Control LLC
27

![Image 1 on page 27](images/2GIG_Edge_Installation_Guide_p27_img1.jpeg)


![Image 2 on page 27](images/2GIG_Edge_Installation_Guide_p27_img2.jpeg)


![Image 3 on page 27](images/2GIG_Edge_Installation_Guide_p27_img3.jpeg)


![Image 4 on page 27](images/2GIG_Edge_Installation_Guide_p27_img4.jpeg)


![Image 5 on page 27](images/2GIG_Edge_Installation_Guide_p27_img5.png)


---

## Page 28


| 5. Tap Panel Programming to view programming options (see below). |  |
| --- | --- |
| Panel Programming – Wireless Zones |  |
| You can program up to 100 wireless zones per system. To get started, tap Wireless Zones to view the Wireless Zones screen. |  |
| Selecting a Wireless Zone 1. On the left side of the Wireless Zones screen, swipe up or down to scroll the list of zones. 2. Tap and highlight one of the available zones. 3. Tap EDIT ZONE to view settings for the selected zone. |  |
| Equipment Code 1. Tap Equipment Code. 2. Tap ≡ to expand the list. 3. Tap to select the desired equipment code from the list. 4. Tap  to move to the next option. |  |
| Sensor Type 1. Tap Sensor Type. 2. Tap ≡ to expand the list. 3. Tap to select the appropriate sensor type from the list. NOTE: You can also use the keypad to enter the two-digit code to display a Sensor Type. 4. Tap  to move to the next option. |  |
| Sensor Equipment Type (if needed) If you selected 04-Interior Follower, 06-24-Hour Silent Alarm, 07- 24-Hour Audible Alarm, 24-Hour Auxiliary Alarm, 10-Interior with Delay, 23-No Response Type in “Sensor Type" above, you must also select this option (continued next page). |  |


*Installation Guide for the 2GIG EDGE Security Panel*
28

![Image 1 on page 28](images/2GIG_Edge_Installation_Guide_p28_img1.png)


![Image 2 on page 28](images/2GIG_Edge_Installation_Guide_p28_img2.jpeg)


![Image 3 on page 28](images/2GIG_Edge_Installation_Guide_p28_img3.jpeg)


![Image 4 on page 28](images/2GIG_Edge_Installation_Guide_p28_img4.png)


![Image 5 on page 28](images/2GIG_Edge_Installation_Guide_p28_img5.jpeg)


---

## Page 29


| If you selected a Sensor Type other than those listed above, skip this step. 1. Highlight Sensor Equipment Type. 2. Choose Contact, Emergency or Motion. Available options vary, depending on the selected Sensor Type. 3. Tap  to move to the next option. |  |
| --- | --- |
| Enter TXID 1. Tap TXID. 2. Tap Learn to enter Learning Mode. This panel listens for the 7-digit TX ID transmission from the sensor or peripheral. TIP: Along with Learning Mode, you also have the option to manually enter the 7-digit TX ID using the keypad. 3. Trigger the sensor or peripheral (see the product’s Installation Instructions). When the 7-digit TX ID is received, Sensor Received appears. 4. Verify that the 7-digit TX ID on product and touchscreen match, then tap Accept. 5. Tap  to move to the next option. |  |
| Sensor Loop 1. Highlight Sensor Loop. 2. Choose Loop 1, Loop 2, or Loop 3. NOTE: To determine the appropriate loop number, see the Installation Instructions included with the sensor or peripheral. 3. Tap  to move to the next option. |  |
| Voice Descriptor Create a voice descriptor for the sensor or peripheral. 1. Highlight Voice Descriptor. 2. Tap Edit Voice Descriptor to reveal the keypad. 3. Enter the first few letters of the desired word. 4. Tap the matching word. 5. Repeat the steps above to enter the desired phrase. 6. Tap Done. 7. Review the voice descriptor. 8. Tap  to move to the next option. |  |
| Sensor Chime 1. Highlight Sensor Chime. 2. Choose the desired chime from the list. The default setting is Disabled. |  |
| Smart Areas Assignment 1. Highlight Smart Areas Assignment. 2. Under Smart Areas Assignment, choose a Smart Area (Partition) for the zone. 3. Tap  to move to the next option. |  |
| Transmission Delay 1. Highlight Transmission Delay. 2. Select Enabled or Disabled. 3. Tap  to move to the next option. |  |


Copyright © 2022 Nortek Security & Control LLC
29

![Image 1 on page 29](images/2GIG_Edge_Installation_Guide_p29_img1.jpeg)


![Image 2 on page 29](images/2GIG_Edge_Installation_Guide_p29_img2.jpeg)


![Image 3 on page 29](images/2GIG_Edge_Installation_Guide_p29_img3.jpeg)


![Image 4 on page 29](images/2GIG_Edge_Installation_Guide_p29_img4.jpeg)


![Image 5 on page 29](images/2GIG_Edge_Installation_Guide_p29_img5.jpeg)


![Image 6 on page 29](images/2GIG_Edge_Installation_Guide_p29_img6.jpeg)


---

## Page 30


| Sensor Reports 1. Highlight Sensor Reports. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| --- | --- |
| Sensor Supervised 1. Highlight Sensor Supervised. 2. Under Sensor Supervised, choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| Next Steps The wireless zone is now programmed. Next, choose one of these options: ¾ To program the next wireless zone, tap Next Zone. Then, repeat the programming steps for the next zone. ¾ To erase all of the programmed settings for the wireless zone, tap Reset Zone. ¾ To go to the list of wireless zones, tap Back to Zones. ¾ Changes are saved instantly, so simply exit the toolbox to start using the new sensor/device. |  |
| Panel Programming – Built-In Zones |  |
| You can program up to three (3) Built-In Zones per system (two Hard-wired zones and the Panel Glassbreak detector). To get started, navigate to the Installer Toolbox. Tap Panel Programming, then tap the Built-In Zones option. |  |
| Selecting a Wired Built-In Zone 1. On the left side of the Built-In Zone screen, review the list of zones. 2. Tap one of the available zones to highlight it. A zone is available when it appears in gray text. 3. Tap EDIT ZONE. |  |
| Sensor Type 1. Highlight Sensor Type. 2. Tap ≡ to expand the list. 3. Select the appropriate sensor type from the list. For example: for a Door/Window Contact for a Patio Door, perhaps select 03-Perimeter. 4. Tap  to move to the next option. |  |
| Normal State 1. Highlight Normal State. 2. Choose one of these options: ¾ Normally Open (NO): Sends alert signal to the security system when the sensor’s circuit is no longer in the NO state. ¾ Normally Closed (NC): Sends alert signal to the security system when the sensor’s circuit is no longer in the NC state. End-of-Line Resistor (EOL): Choose when an end- of-line (EOL) resistor is present. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
30

![Image 1 on page 30](images/2GIG_Edge_Installation_Guide_p30_img1.jpeg)


![Image 2 on page 30](images/2GIG_Edge_Installation_Guide_p30_img2.jpeg)


![Image 3 on page 30](images/2GIG_Edge_Installation_Guide_p30_img3.jpeg)


![Image 4 on page 30](images/2GIG_Edge_Installation_Guide_p30_img4.jpeg)


![Image 5 on page 30](images/2GIG_Edge_Installation_Guide_p30_img5.jpeg)


---

## Page 31


| Voice Descriptor 1. Highlight Voice Descriptor. 2. Tap Edit Voice Descriptor to reveal the keypad. 3. Enter the first few letters of the desired word. 4. Tap the matching word above the keypad. 5. Repeat the steps above to enter a phrase. 6. Tap Done. 7. Review the voice descriptor. 8. Tap  to move to the next option. |  |
| --- | --- |
| Sensor Chime 1. Highlight Sensor Chime. 2. Choose the desired chime from the list. The default setting is Disabled. |  |
| Smart Areas Assignment 1. Highlight Smart Areas Assignment. 2. Choose a Smart Area (Partition) for the zone. 3. Tap  to move to the next option. |  |
| Transmission Delay 1. Highlight Transmission Delay. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| Sensor Reports 1. Highlight Sensor Reports. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |


Copyright © 2022 Nortek Security & Control LLC
31

![Image 1 on page 31](images/2GIG_Edge_Installation_Guide_p31_img1.jpeg)


![Image 2 on page 31](images/2GIG_Edge_Installation_Guide_p31_img2.jpeg)


![Image 3 on page 31](images/2GIG_Edge_Installation_Guide_p31_img3.jpeg)


![Image 4 on page 31](images/2GIG_Edge_Installation_Guide_p31_img4.jpeg)


![Image 5 on page 31](images/2GIG_Edge_Installation_Guide_p31_img5.jpeg)


---

## Page 32


| Glass Break To program the built-in Glass Break sensor, adjust the following settings. Sensor 1. Tap Glass Break. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| --- | --- |
| Voice Descriptor 1. Highlight Voice Descriptor. 2. Tap Edit Voice Descriptor to reveal the keypad. 3. Use the keypad to enter the first few letters of the desired word. 4. Tap the matching word above the keypad. 5. Repeat the steps above to enter a phrase. 6. Tap Done. 7. Review the voice descriptor. 8. Tap  to move to the next option. |  |
| Sensor Chime 1. Highlight Sensor Chime. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| Smart Areas Assignment 1. Highlight Smart Areas Assignment. 2. Choose a Smart Area (Partition) for the zone. 3. Tap  to move to the next option. |  |
| Transmission Delay 1. Highlight Transmission Delay. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
32

![Image 1 on page 32](images/2GIG_Edge_Installation_Guide_p32_img1.jpeg)


![Image 2 on page 32](images/2GIG_Edge_Installation_Guide_p32_img2.jpeg)


![Image 3 on page 32](images/2GIG_Edge_Installation_Guide_p32_img3.jpeg)


![Image 4 on page 32](images/2GIG_Edge_Installation_Guide_p32_img4.jpeg)


![Image 5 on page 32](images/2GIG_Edge_Installation_Guide_p32_img5.jpeg)


---

## Page 33


| Sensor Reports 1. Highlight Sensor Reports. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| --- | --- |
| Panel Programming – Keyfobs |  |
| Program up to 32 keyfobs per system. To begin, navigate to the Installer Toolbox, then tap Panel Programming > Keyfobs. |  |
| Select a Keyfob 1. Swipe up to move through the list of keyfobs. 2. Tap to select one of the available keyfobs. 3. Tap Edit Keyfob. 1. Highlight Fob Active. 2. Under Fob Used, choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| Select Equipment Code 1. Highlight Equipment Code. 2. Tap ≡ to expand the list. 3. Tap to select the desired equipment code from the list. 4. Tap  to move to the next option. |  |
| Serial Number 1. Highlight Serial Number. 2. Tap Learn to enter Learning Mode. 3. The 7-digit TX-ID listed on the product is detected. 4. Press any button on the keyfob for three 3 – 5 seconds. The Sensor Received message appears if successful. TIP: Along with Learning Mode, you also have the option to manually enter the 7-digit TX ID using the keypad. 5. Verify the on-screen serial number matches the keyfob’s 7-digit TX ID, then tap Accept. 6. Tap  to move to the next option. |  |
| Edit Voice Descriptor Create a voice descriptor for the keyfob using the words in the system’s vocabulary. 1. Highlight Voice Descriptor. 2. Tap Edit Voice Descriptor to view the keypad. 3. Enter the first few letters of the desired word. 4. Tap the matching vocabulary word above the touchscreen keypad to select it. 5. Repeat the steps to enter phrases, then tap Done. 6. Review the voice descriptor. 7. Tap  to move to the next option. |  |


Copyright © 2022 Nortek Security & Control LLC
33

![Image 1 on page 33](images/2GIG_Edge_Installation_Guide_p33_img1.jpeg)


![Image 2 on page 33](images/2GIG_Edge_Installation_Guide_p33_img2.png)


![Image 3 on page 33](images/2GIG_Edge_Installation_Guide_p33_img3.jpeg)


![Image 4 on page 33](images/2GIG_Edge_Installation_Guide_p33_img4.png)


![Image 5 on page 33](images/2GIG_Edge_Installation_Guide_p33_img5.jpeg)


---

## Page 34


| Smart Areas Assignment 1. Highlight Smart Areas Assignment. 2. Under Smart Areas Assignment, choose a Smart Area (Partition) for the keyfob. 3. Tap  to move to the next option. |  |
| --- | --- |
| Emergency Key 1. Highlight Emergency Key. 2. Choose one of these options: ¾ Disabled: Turns the emergency key function OFF. ¾ Auxiliary: Triggers an auxiliary alarm. ¾ Audible: Triggers an audible alarm on the system. ¾ Silent Panic: Triggers a silent distress signal. 3. Tap  to move to the next option. |  |
| Fob Can Disarm 1. Highlight Fob Can Disarm. 2. Under Fob Can Disarm, choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| Arm with No Entry Delay 1. Highlight Arm with No Entry Delay. 2. Choose Enabled or Disabled. 3. Tap  to move to the next option. |  |
| Fob Output 1. Highlight Fob Output. 2. Choose one of these options: ¾ Disabled: This deactivates the option. ¾ Toggle Output: Press the Auxiliary (*) button to control the device connected to the Open Collector Output #1. For example: open and close a garage door. ¾ Momentary Output: Press the Auxiliary (*) button to change the state of the device connected to the Open Collector Output #1. For example: turn the system-controlled lights ON or OFF. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
34

![Image 1 on page 34](images/2GIG_Edge_Installation_Guide_p34_img1.jpeg)


![Image 2 on page 34](images/2GIG_Edge_Installation_Guide_p34_img2.jpeg)


![Image 3 on page 34](images/2GIG_Edge_Installation_Guide_p34_img3.jpeg)


![Image 4 on page 34](images/2GIG_Edge_Installation_Guide_p34_img4.jpeg)


![Image 5 on page 34](images/2GIG_Edge_Installation_Guide_p34_img5.jpeg)


---

## Page 35


| Panel Programming – Keypads |  |
| --- | --- |
| You can program up to eight (8) wireless keypads per system. To get started, navigate to the Installer Toolbox. Then, tap Keypads. This reveals the Keypads screen. |  |
| NOTE: The 2GIG Edge panel and Remote Keypads must be connected the same WiFi network, or the Remote Keypads must be connected to the access point of the 2GIG EDGE Panel before starting keypad programming. See Network Settings, page 38. Keypad (#) 1. Swipe up to move through the list of keypads. 2. Tap to select one of the available keypads, then tap Edit Keypad. Make sure the Keypad Used setting is highlighted. 3. Under Keypad Used, choose Enabled or Disabled. 4. Tap  to move to the next option. |  |
| 5. Tap PAIR KEYPAD. The panel will listen for a Keypad to pair. |  |
| 6. The panel will prompt to enter a code on the secondary panel. |  |
| 7. On the secondary panel, enter the pairing code. |  |


Copyright © 2022 Nortek Security & Control LLC
35

![Image 1 on page 35](images/2GIG_Edge_Installation_Guide_p35_img1.png)


![Image 2 on page 35](images/2GIG_Edge_Installation_Guide_p35_img2.jpeg)


![Image 3 on page 35](images/2GIG_Edge_Installation_Guide_p35_img3.jpeg)


![Image 4 on page 35](images/2GIG_Edge_Installation_Guide_p35_img4.jpeg)


![Image 5 on page 35](images/2GIG_Edge_Installation_Guide_p35_img5.jpeg)


---

## Page 36


| 8. The panel will display the Keypad as “Paired”. 9. Tap  to move to the next option. |  |
| --- | --- |
| Smart Areas Assignment 1. Highlight Smart Areas Assignment. 2. Choose a Smart Area (Partition) for the Keypad. 3. Tap  to move to the next option. |  |
| Edit Voice Descriptor 1. Highlight the Voice Descriptor setting. 2. Tap ADD VOICE DESCRIPTOR to reveal the touchscreen keypad. 3. Enter the first few letters of the desired vocabulary word. 4. Tap the matching vocabulary word above the touchscreen keypad to select it. 5. Repeat the steps above to enter the desired phrase for the keypad. 6. Tap Done. 7. Review the voice descriptor. |  |
| Reset Keypad/Next Keypad ¾ Tap Reset Zone to erase all the programmed settings for the zone. ¾ Tap NEXT KEYPAD to program another Remote Keypad. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
36

![Image 1 on page 36](images/2GIG_Edge_Installation_Guide_p36_img1.jpeg)


![Image 2 on page 36](images/2GIG_Edge_Installation_Guide_p36_img2.jpeg)


![Image 3 on page 36](images/2GIG_Edge_Installation_Guide_p36_img3.jpeg)


![Image 4 on page 36](images/2GIG_Edge_Installation_Guide_p36_img4.jpeg)


---

## Page 37


| Panel Programming – Image Sensors |  |
| --- | --- |
| Program up to 10 Image Sensors. |  |
| Navigate to Installer Toolbox menu, tap Panel Programming and then tap Image Sensors . |  |
| Image Sensor To add an Image Sensor: 1. Tap Image Sensor [##] found within the left column. 2. Tap ADD IMAGE SENSOR. The panel will listen for the Image Sensor. |  |
| 3. Place the Image Sensor in Learn Mode (refer to the Image Sensor manual for Learn Mode instructions). 4. The panel will prompt when an Image Sensor is found. 5. Tap OK. |  |
| 6. Image Sensor details are displayed. 7. Tap  to move to the next option. After Image Sensors have been added to the 2GIG EDGE Panel in Wireless Zones programming, the Image Sensor details will be displayed in Image Sensor settings. The Image Sensor will be displayed with the following: ¾ Zone number ¾ Signal Strength ¾ MAC address of Image Sensor ¾ Rules ¾ Firmware Version ¾ Sensitivity ¾ Battery level |  |
| Sensor Type ≡ 1. Tap to access the list of Sensor Types (if you know the two-digit code for the sensor type, use the numeric keypad). |  |
| 2. Tap the type of sensor. 3. Tap  to move to the next option. |  |


Copyright © 2022 Nortek Security & Control LLC
37

![Image 1 on page 37](images/2GIG_Edge_Installation_Guide_p37_img1.png)


![Image 2 on page 37](images/2GIG_Edge_Installation_Guide_p37_img2.png)


![Image 3 on page 37](images/2GIG_Edge_Installation_Guide_p37_img3.png)


![Image 4 on page 37](images/2GIG_Edge_Installation_Guide_p37_img4.jpeg)


![Image 5 on page 37](images/2GIG_Edge_Installation_Guide_p37_img5.jpeg)


![Image 6 on page 37](images/2GIG_Edge_Installation_Guide_p37_img6.jpeg)


![Image 7 on page 37](images/2GIG_Edge_Installation_Guide_p37_img7.png)


---

## Page 38


| Voice Descriptor 1. Tap EDIT VOICE DESCRIPTOR. |  |
| --- | --- |
| 2. Use the keypad to enter the first few letters of the desired word. 3. Tap the matching word above the keypad. 4. Repeat the steps above to enter a phrase. 5. Tap DONE. 6. Tap  to move to the next option. |  |
| Sensor Chime 1. Tap Sensor Chime to assign a sound to the Image Sensor. 2. Tap  to move to the next option. |  |
| Sensitivity 1. Tap Sensitivity, then select High, Normal or Low. 2. Tap  to move to the next option. |  |
| Smart Area Assignment 1. Tap Smart Area Assignment, then assign the Image Sensor to a particular Smart Area zone (S1, S2, S3 or S4). 2. Tap  to move to the next option. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
38

![Image 1 on page 38](images/2GIG_Edge_Installation_Guide_p38_img1.png)


![Image 2 on page 38](images/2GIG_Edge_Installation_Guide_p38_img2.jpeg)


![Image 3 on page 38](images/2GIG_Edge_Installation_Guide_p38_img3.png)


![Image 4 on page 38](images/2GIG_Edge_Installation_Guide_p38_img4.jpeg)


![Image 5 on page 38](images/2GIG_Edge_Installation_Guide_p38_img5.jpeg)


---

## Page 39


| Transmission Delay 1. Tap Transmission Delay. 2. Tap Enabled or Disabled. 3. Tap  to move to the next option. |  |  |
| --- | --- | --- |
| Sensor Reports 1. Tap Sensor Reports. 2. Tap Enabled or Disabled. 3. Tap  to move to the next option. |  |  |
| Sensor Supervised 1. Tap Sensor Supervised. 2. Tap Enabled or Disabled. |  |  |
| Reset Keypad/Next Keypad ¾ Tap RESET ZONE to erase all the programmed settings for the zone. ¾ Tap NEXT ZONE to program another Image Sensor. |  |  |
| Panel Programming – Network Settings |  |  |
| Wireless Network 1. Tap an available Wireless Network Name. 2. Correctly enter the assigned network password to connect. 3. Tap  to go back to the Network Settings menu. |  |  |
| 4. Enter network password at the Keyboard Entry Screen, and tap CONNECT. |  |  |


Copyright © 2022 Nortek Security & Control LLC
39

![Image 1 on page 39](images/2GIG_Edge_Installation_Guide_p39_img1.jpeg)


![Image 2 on page 39](images/2GIG_Edge_Installation_Guide_p39_img2.jpeg)


![Image 3 on page 39](images/2GIG_Edge_Installation_Guide_p39_img3.jpeg)


![Image 4 on page 39](images/2GIG_Edge_Installation_Guide_p39_img4.png)


![Image 5 on page 39](images/2GIG_Edge_Installation_Guide_p39_img5.jpeg)


![Image 6 on page 39](images/2GIG_Edge_Installation_Guide_p39_img6.jpeg)


---

## Page 40


| Forget Network Tapping FORGET NETWORK disconnects the 2GIG EDGE Panel from the wireless network and erases the password so that it will not automatically reconnect to the network. |  |
| --- | --- |
| Join Other Network Tapping Join Other Network allows you to join a network not shown in the list. 1. Return to the Wireless Network screen. 2. Tap JOIN OTHER NETWORK. 3. Enter the wireless network name, then tap NEXT. 4. Select the Security Type and Security Mode, then tap NEXT. 5. Enter the password. |  |
| WPS Tapping WPS allows you to connect securely to routers that support WPS. 1. Tap WPS on 2GIG EDGE Panel. 2. Tap Connect. 3. Locate and press the WPS on your router. 2GIG EDGE Panel will securely connect with the router. 4. Once Authorization is successful, tap ACCEPT. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
40

![Image 1 on page 40](images/2GIG_Edge_Installation_Guide_p40_img1.jpeg)


![Image 2 on page 40](images/2GIG_Edge_Installation_Guide_p40_img2.jpeg)


![Image 3 on page 40](images/2GIG_Edge_Installation_Guide_p40_img3.jpeg)


![Image 4 on page 40](images/2GIG_Edge_Installation_Guide_p40_img4.jpeg)


![Image 5 on page 40](images/2GIG_Edge_Installation_Guide_p40_img5.jpeg)


![Image 6 on page 40](images/2GIG_Edge_Installation_Guide_p40_img6.jpeg)


---

## Page 41


| Access Point Setup the Panel Access Point. 1. Tap Network Settings. 2. Tap Access Point. 3. Enable Access Point: ¾ Optional: Tap ( ) to enter a new SSID name ¾ Optional: Tap ( ) to enter a new password ¾ Optional: Tap ( ) IP address. The last two octets of the Access Point can be changed to customize the setup. 4. If edits have been made, tap SAVE SETTINGS to save. NOTE: Make a note of SSID and Password for use in WiFi setup of 2GIG EDGE Remote Keypads, approved video doorbells and cameras. 5. Tap  to go back to the Network Settings menu. |  |
| --- | --- |
| Smart Home Settings |  |
| You can add up to 232 Z-Wave devices to the network. After adding or removing a device you should always rediscover the network. Tap Settings, then Smart Home Settings to view the Smart Home Settings menu. Refer to the Smart Home Manual for the 2GIG EDGE Security Panel for complete use and setup information. View All Devices Displays all Z-Wave Smart Home Devices connected to the panel. |  |
| Add Device 1. Tap Add Devices. The Listening for Devices to Add page appears. 2. Walk to and trigger the device on the network. When the system discovers a device, the system automatically adds it and the Adding Device message appears. 3. Tap OK. The newly discovered device appears. Any device information captured during the discovery process appears below the device name. |  |
| Remove Device At the Smart Home Settings menu, tap Remove Device. Follow on-screen instructions to remove specific devices. |  |
| Check Network 1. Tap Check Network to check the network for failed nodes. 2. Tap TEST. The system scans the network for failed nodes. This can take several minutes and some of the Z-Wave functions will be unavailable until the rediscovery is complete. |  |
| Rediscover Network 1. Tap Smart Home Settings. 2. Tap TEST. 3. Tap START. The Working screen appears. |  |


Copyright © 2022 Nortek Security & Control LLC
41

![Image 1 on page 41](images/2GIG_Edge_Installation_Guide_p41_img1.png)


![Image 2 on page 41](images/2GIG_Edge_Installation_Guide_p41_img2.jpeg)


![Image 3 on page 41](images/2GIG_Edge_Installation_Guide_p41_img3.jpeg)


---

## Page 42


| System Test |  |
| --- | --- |
| NOTE: The Panel Test and Network Test were not evaluated to ANSI SIA CP-01: 2010, Initiation of Test and Termination Test Sensor Tests After installing the system, sensors, and peripherals, perform a walk test to ensure proper console operations and to test wireless reception and signal strength. ¾ Tap Sensors Tests, then walk to and trigger each sensor. |  |
| Panel Testing Tap each button and respond Yes or No to each question. If any of the tests fail, please contact your dealer for assistance. |  |
| Disable Sounder Press YES to disable the Sounder. The panel will beep. The siren will be silent for 30 minutes or until it is re-enabled manually. |  |
| Cell Radio Test/Status At the Radio Status screen, tap Test Cell Radio. Status for Signal Strength, Serial Number, Subscriber ID, Registration Status, Connection Status and Power Status will be displayed. |  |
| Network Test Tap this option to test LAN, Internet and Backend network connection status. NOTE: The system is to be tested upon completion of the installation. |  |


*Installation Guide for the 2GIG EDGE Security Panel*
42

![Image 1 on page 42](images/2GIG_Edge_Installation_Guide_p42_img1.jpeg)


![Image 2 on page 42](images/2GIG_Edge_Installation_Guide_p42_img2.jpeg)


![Image 3 on page 42](images/2GIG_Edge_Installation_Guide_p42_img3.jpeg)


![Image 4 on page 42](images/2GIG_Edge_Installation_Guide_p42_img4.jpeg)


![Image 5 on page 42](images/2GIG_Edge_Installation_Guide_p42_img5.jpeg)


---

## Page 43


| Panel Programming – Advanced Programming |  |
| --- | --- |
| You can program a variety of settings for the 2GIG EDGE Panel. To get started, navigate to the Installer Toolbox. Then, tap Panel Programming > Advanced Programming > System Configuration. |  |
| Advanced Programming Options include: System Configuration Timers, Delays & Counts Panel Configuration Troubles Reporting On the left side of each option's screen are a variety of programming questions related to how the 2GIG EDGE Panel and different system components operate. 1. Highlight a question [Q### - (settings differ based on the question)]. 2. Tap available options to adjust settings. 3. Tap  to move to the next question, or tap  to return to the previous menu. NOTE: Ensure that the settings you program are in compliance with all national, state, and local regulations. NOTE: For more in-depth information about the list of questions available in the Panel Programming menu, see Advanced Programming, page 43. |  |


**ADVANCED PROGRAMMING**

**System Configuration**
This section details the Panel Programming questions. **A dagger (†) indicates a factory default setting** . *A double dagger (‡) indicates a*
*default setting for compliance with ANSI/SIA CP-01-2010: Control Panel Standard - Features for False Alarm Reduction* .

**Q101: Change installer code**
Defines the unique four-digit code for installers to use when accessing the Installer Toolbox. See **Installer Toolbox** , page 27.
Choose one of these options:

» † **1561** : This is the factory default setting.
» **Enter a unique code.** If you change the Installer Code, be sure to remember it so you can access the system later. The Installer Code
must be unique from the Master User Code and all other user codes.
**IMPORTANT:** To minimize the risk of unwanted persons circumventing the system, alarm dealers and professional installers are advised
to change the system’s default Installer Code to a unique one. This helps to prevent unwanted persons from gaining access to critical
programming features of the 2GIG EDGE Panel.

**Q102: Security pin code length**
Configures the system’s pin code length.
Choose one of these options:

» † **4 Digits:** Installer, Master, duress and user codes will be 4 or 6 digits long.
» **6 Digits:** Installer, Master, duress and user codes will be 6 digits long.

**NOTE:** If changing from 4 to 6-digit pin codes, all existing codes will be appended with “11”. The default 6-digit Installer pin code is
156111 and Master 111111.

**NOTE:** When changing from 6 to 4-digit pin codes all pin codes will be truncated, removing the last 2 digits. If this action causes
conflicts, the system will prompt to resolve the conflicts. Conflicts can be resolved by defaulting the user codes or changing the existing
pin codes so that no first four digits of the pin codes are the same.

Copyright © 2022 Nortek Security & Control LLC
43

![Image 1 on page 43](images/2GIG_Edge_Installation_Guide_p43_img1.png)


![Image 2 on page 43](images/2GIG_Edge_Installation_Guide_p43_img2.png)


![Image 3 on page 43](images/2GIG_Edge_Installation_Guide_p43_img3.png)


![Image 4 on page 43](images/2GIG_Edge_Installation_Guide_p43_img4.png)


![Image 5 on page 43](images/2GIG_Edge_Installation_Guide_p43_img5.png)


![Image 6 on page 43](images/2GIG_Edge_Installation_Guide_p43_img6.jpeg)


---

## Page 44

**Q103: Lock installer programming**
This feature prevents system takeovers by locking the installer programming features in the System Configuration menu after 48 hours. The 48-hour
lockout timer starts when the installer exits System Configuration mode. To restore access after the 48-hour period, installers must reset the lockout timer
using the backend dealer portal. When this feature is enabled, the following programming features are locked out after 48 hours:

» Q101: Enter installer code (4 or 6 digits)
» Q103: Lock installer programming
» Q104: Lock default programming

Choose one of these options:
» † **Disabled (Full Access):** This turns the feature OFF. Installer programming remains unlocked after 48-hours.
» **No Access:** This turns the feature ON. The programming features are fully restricted after 48-hours.
» **Limited Access:** This turns the feature ON. The programming features are partially restricted after 48-hours.

**Q104: Lock default programming**
Prevents system takeovers by limiting the installer’s ability to restore the factory default settings of the 2GIG EDGE Panel.
Choose one of these options:

» † **Allow Reset of All Defaults:** Lets installers restore the factory-default values to the 2GIG EDGE Panel.
» **Allow Limited Reset of Defaults:** Lets installers restore some of the factory-default values, with the exception of *Q101: Enter*
*installer code (4 or 6 digits)* above, *Q103: Lock installer programming* above, *Q104: Lock default programming* above. This setting takes effect
48 hours after the setting is changed, and the countdown timer starts when you exit the System Configuration menu.
» **Do Not Allow Reset of Defaults:** Does not let installers restore the factory default values to the 2GIG EDGE Panel. This setting
starts when you exit the System Configuration menu.

**Q105: 2-way voice**
Configures the system to automatically turn the 2-Way Voice feature ON or OFF after the type of alarm you specify. This gives the Cellular Radio
Module in the 2GIG EDGE Panel the ability to automatically dial the Central Station and connect with an operator after an alarm sounds. Once
connected with the Central Station, people on the premises can communicate with the operator using the built-in speaker and microphone.

Choose one of these options (next page):
» **Disabled** : Disable 2-way voice.
» † **Stay on line** : Default. 2-way voice is enabled.
» **Stay on line, incl fire & CO alarms** : 2-way voice is enabled and includes fire and CO alarms.

**Q106: Disable siren after two-way audio**
Configures the system to automatically turn the alarm siren ON or OFF after the end of a 2-Way Voice session. For this setting to take effect,
“Q105: 2-way voice” above must be enabled.
Choose one of these options:

» **Enabled:** Choose this setting if you want the alarm siren to remain OFF after a 2-Way Voice session ends.
» † **Disabled:** Choose this setting if you want the alarm siren to resume after a 2-Way Voice session ends.
**NOTE:** When set to disabled, the alarm siren will only resume after a 2-way voice session when the corresponding alarm bell cutoff time
has not expired. See *Q206: Burglary bell cutoff time* and *Q207: Fire bell cutoff time* .

**Q107: Smart Areas**
Configures “Smart Areas” (partitioning) feature allowing the system to be divided into four separate areas. Once enabled, zones, keyfobs, keypads,
and users can be assigned to Smart Areas allowing individual control of each area.
Choose one of these options:

» **Enabled:** Smart Areas button will be displayed on 2GIG EDGE Panel and all 2GIG EDGE Remote keypads. Zones, Keyfobs, Keypads can
be assigned to a single Smart Area.  Users can be assigned and control assigned Smart Areas. Smart Areas Settings will allow naming of
all four areas.
» † **Disabled:** Smart Areas button will not be displayed on the home screen of the 2GIG EDGE Panel and Remote Keypads.  Smart Areas
Settings will only display the main system.

**NOTE:** Programming of Zones, Keyfobs, and Keypads is not restricted and all devices can be programmed and assigned to any of the
four Smart Areas but will be inactive if assigned to Smart Area 2-4 until this feature is enabled.

*Installation Guide for the 2GIG EDGE Security Panel*
44

---

## Page 45

**Q108: Z-Wave feature**
Configures the system to show or hide the Smart Home Controls button on Home screen of the touchscreen. When this feature is enabled, it
provides users with access to the smart devices on the network.
Choose one of these options:

» **Disabled and Hidden:** Hides the Smart Home Controls button on the Home screen.
» **Disabled but Visible:** Shows the Smart Home Controls button on the Home screen. When a user taps the button, the This feature is
not currently activated message displays.
» † **Enabled:** Shows the Smart Home Controls button on the Home screen. Users can operate smart devices from the touchscreen or
remotely.

**Q109: Master user can access Z-Wave setup**
Configures the system to allow persons who know the system’s Master User Code to gain access to the System Settings > Smart Home Settings menu.
Choose one of these options:

» **Enabled:** This makes the Smart Home Settings button available in the System Settings menu after entering the Master User Code.
» † **Disabled:** This grays out the Smart Home Settings button and makes it unavailable in the System Settings menu.

**Q110: Smart Home Controls require master code**
Configures the system to prompt the user for the master code when attempting to access the Smart Home Controls menu (if enabled). See *Q108:*
*Z-Wave feature* above.
Choose one of these options:

» **Enabled:** When a user taps the Smart Home Controls button, the Enter Your Code to Access Smart Home
» Controls screen appears.
» † **Disabled:** Opens the Smart Home Controls menu, without prompting the user for a code.

**Q111: Main Panel Sounder Follows**
Configures the system to allow alarms in all Smart Areas to sound the Main panel.
Choose one of these options:

» † **All Smart Areas:** Alarms from any Smart Area will alert and sound at the 2GIG EDGE Panel.
» **Main Panel Smart Area Only:** Only alarms in Smart Area 1 will alert at the 2GIG EDGE Panel, alarms in Smart Areas 2-4 will only
alert on keypads assigned to those areas.
**NOTE:** With both options alarms for all Smart Areas are visible by entering the Smart Areas Screen via the Home Screen button.

**Q112: Z-Wave siren mode**
Configures the system to sound any Z-Wave sirens that have been added to the network.
Choose one of the options:

» † **Sound for Burglary and Fire/CO:** Configures the system to sound any connected Z-Wave sirens during a burglary, fire, or CO
alarm.
» **Sound for Burglary Only:** Configures the system to sound any connected Z-Wave sirens during burglary alarms only.

**Q113: Quick arming**
Turns the system’s quick arming feature ON and OFF. This feature can be assigned individually for each Smart Area.  (Smart Areas feature must
be enabled (Q107) for settings for S2-S4 to affect the system) When ON, any occupant can arm the system. When OFF, only persons who know an
active user code can arm the system.
Choose one of these options:

» † **Enabled:** Turns the feature ON and does not require occupants to enter a user code to arm the system.
» **Disabled:** Turns the feature OFF and requires occupants to enter an active, user code or Face Recognition (if enabled) to arm the
system.

**Q114: Auto stay**
Turns the system’s Auto Stay feature ON and OFF. This feature can be assigned individually for each Smart Area.  (Smart Areas feature must be
enabled (Q107) for settings for S2-S4 to affect the system)  When ON, the system monitors the Exit Delay doors after the user arms the system in
Away Mode at the 2GIG EDGE Panel. If no one exits that door before the Exit Delay countdown expires, the system automatically arms itself in Stay
Mode. *See Q201: Exit delay* , in seconds (45-120). This setting does not go into effect when arming the system in Away Mode with a keyfob or from
Alarm.com.

Copyright © 2022 Nortek Security & Control LLC
45

---

## Page 46

Choose one of these options:
» **Disabled:** Turns the feature OFF. The system arms itself in Away Mode at the end of the Exit Delay countdown.
» † ‡ **Enabled:** Turns the feature ON. The system monitors the Exit Delay door when the system is armed and if no one exits the door
before the Exit Delay countdown expires, the system automatically arms the system in Stay Mode. For compliance with ANSI/SIA CP-01-
2010, this feature is enabled by default.

**Q115: Exit delay restart**
Configures the system to restart the Exit Delay countdown if a user must re-enter the premises through an Exit Delay door during the initial Exit
Delay countdown. This feature can be assigned individually for each Smart Area. (Smart Areas feature must be enabled (Q107) for settings for S2-
S4 to affect the system)  This is useful when a user arms the system, exits the premises, and then needs to quickly enter/exit the premises before
the countdown expires. As long as the user exits the premises during the Exit Delay Restart countdown, there is no need to disarm and re-arm the
system. When this feature is turned ON, the Exit Delay timer will restart one (1) time.
Choose one of these options:

» † ‡ **Enabled:** Turns the feature ON. If the user exits and then re-enters the premises before the Exit Delay countdown expires, the Exit
Delay countdown restarts before the system is armed. For compliance with ANSI/SIA CP-01-2010, this feature is enabled by default
» **Disabled:** Turns the feature OFF.
**NOTE:** When the Exit Delay Restart feature is enabled on the system and the user arms the system with the Silent Exit feature enabled,
the system will restart the exit countdown using the Silent Exit timer, instead of the Exit Delay timer.

**NOTE:** When the Exit Delay Restart feature is enabled on the system and the user triggers the Exit Delay Restart feature, the Quick Exit
button is disabled.

**Q116: Allow quick exit**
Configures the system to allow users to quickly exit the premises while the system is armed in Stay Mode. When this feature is turned ON and
a user taps Arm Stay, a Quick Exit button appears on the System Armed screen. When a user taps Quick Exit , the system starts the Exit Delay
countdown and the user must exit the premises before the countdown expires. After the countdown expires, the system automatically re-arms
itself in the specified arming mode.
Choose one of these options:

» † **Enabled:** Turns the feature ON. This enables the Quick Exit button on the System Armed screen.
» **Disabled:** Turns the feature OFF.

**NOTE:** The Quick Exit button is not available on the System Armed screen when the user invokes the Exit Delay Restart feature. See
*Q115: Exit delay restart* .

**Q117: Quick bypass**
Configures the system to allow users to bypass a sensor without prompting the user to enter a user code. This feature can be assigned
individually for each Smart Area.  (Smart Areas feature must be enabled (Q107) for settings for S2-S4 to affect the system)  Typically, this feature
is disabled, so a user must enter a valid user code before bypassing a sensor.
Choose one of these options:

» **Enabled:** Turns the feature ON.
» † **Disabled:** Turns the feature OFF.

**Q118: Auto unbypass for manual bypass**
Manually bypassed sensors can have their bypass automatically removed at disarming or have their bypasses remain in place.
You have these options:

» † **Enabled:** Turns the feature ON. The system automatically removes bypasses from manually bypassed sensors when the system is
disarmed.
» **Disabled:** Turns the feature OFF. Manually bypassed sensors will remain bypassed when the system is disarmed.

**Q119: Alert on disarm with keyfob after alarm**
Configures the system to activate a unique sound when the system in the alarm state is disarmed by a keyfob. The unique sound is four (4) beeps
from the speakers on the 2GIG EDGE Panel and four (4) chirps from an external alarm sounder (if installed).
Choose one of these options:

» **Enabled:** Turns the feature ON. The system emits the unique sound.
» † **Disabled:** Turns the feature OFF.

*Installation Guide for the 2GIG EDGE Security Panel*
46

---

## Page 47

**Q120: Keyfob arm/disarm confirmation**
Configures the system to activate a unique sound when the system is armed/disarmed with a keyfob. This feature can be assigned individually for
each Smart Area.  (Smart Areas feature must be enabled (Q107) for settings for S2-S4 to affect the system)  When enabled, the panel’s speaker
emits one (1) beep when arming and two (2) beeps when disarming the system with a keyfob. If an external alarm sounder is installed the system
sounds one (1) chirp when arming and two (2) chirps when disarming the system. Choose one of these options:
» **Enabled** : Turns the feature ON. The system emits the unique sound.
» † **Disabled:** Turns the feature OFF. The system does not emit the unique sound.

**Q121: Keyfob/remote arming mode on system not ready**
Defines how the system behaves when the system is armed remotely while sensors are open. Choose one of these options:
» † **Auto-Bypass with Zone Participation on Restore:** Automatically bypasses all open sensors when the system is remotely
armed and, while armed, automatically removes the bypass if the sensor is restored to its normal state.
» **Auto-Bypass:** Automatically bypasses all open sensors when the system is remotely armed.
» **Arm Only When System Ready:** Does not allow the system to arm remotely when sensors are open.

**Q122: Alarm cancel display**
Configures the system to display an alert message letting the user know that an alarm cancellation report was sent to the Central Station. The
message is displayed if the alarm is canceled within the number of minutes specified in *Q204: Alarm cancel time, in minutes (5-255)* .
Choose one of these options:

» † ‡ **Enabled:** Turns the feature ON. This displays an alert message notifying the user that an alarm cancellation report was sent to the
Central Station. For compliance with ANSI/SIA CP- 01-2010, the default setting for this feature is enabled.
» **Disabled:** Turns the feature OFF. The system will not display an alert message when a cancellation report is sent to the Central Station.

**Q123: Cross sensor zones 99-100**
Defines the alarm verification requirement for a cross sensor zone. A cross sensor zone is comprised of two wireless sensors and both sensors
must be violated before the system activates the alarm. This means that before a cross sensor zone can activate an alarm, the sensors for both
Wireless Zone 99 and Wireless Zone 100 must be violated.
If only one of the two sensors in the cross sensor zone is violated, the system automatically transmits a trouble report about the violated sensor
to the Central Station. If both sensors in the cross zones are violated within the amount of time specified in *Q209: Cross sensor timeout, in seconds*
*(10-120)* , the system activates an alarm and also transmits an alarm report to the Central Station.

**NOTE:** Carbon Monoxide Detectors and Smoke/Heat Alarms cannot be used in cross sensor zones.
Choose one of these options:

» **Enabled:** Turns the feature ON. The system transmits a trouble report to the Central Station when one sensor in a cross sensor zone is
violated and sets off an alarm when both sensors are violated.
» † **Disabled:** Turns the feature OFF.

**Q124: Event logs**
Configures the system to define the types of system events that are recorded in the system’s History.
You have these options:

» **Disabled:** Does not record events.
» **All Events Except Open/Close/Bypass:** Records all events, except sensor opening, closing, and bypassing.
» **All Events Except Open/Close:** Records all events, except sensor opening and closing.
» † **All Events:** Records all events.

**Q125: LED Mode Control**

*Disabled* (Default) Panel LED will show status during AC power loss. *Enabled* - Panel LED will turn off during AC power loss. (Required for UL985).
Choose one of these options:

» **Enabled:** Turns the feature ON.
» † **Disabled:** Turns the feature OFF.

**Q126: Commercial Burglary Support**
Allows the panel to be configured for UL1610 installations. *Enabled* - Allows the panel Entry timers (Q202 & Q203) to be set for less than 30
seconds. *Disabled* (Default) – Entry timers are limited to a minimum of 30 seconds.

» **Enabled:** Turns the feature ON.
» † **Disabled:** Turns the feature OFF.

Note: Enabling Q126 changes panel settings only. UL-1610 must also be enabled on the Alarm.com account.

Copyright © 2022 Nortek Security & Control LLC
47

---

## Page 48

**Timers, Delays & Counts**

**Q201: Exit delay, in seconds**
Configures the number of seconds for the Exit Delay countdown. Different times may be programmed for each Smart Areas. (Smart Areas feature
must be enabled (Q107) for values for S2-S4 to affect the system) This is the amount of time occupants have to exit the building through a door after
arming the system. The doors programmed as Exit/Entry 1 and Exit/Entry 2 use this timer. When the user arms the system, the countdown starts.
The 2GIG EDGE Panel beeps once every two (2) seconds during the countdown. For the last 10 seconds, the beeps speed up to warn occupants
that they have less than 10 seconds to exit the premises.
Choose one of these options:

» **45-120 Seconds:** Choose a value between 45 and 120 seconds.
» † ‡ **60 Seconds:** For compliance with ANSI/SIA CP-01-2010, the default Exit Delay feature is set to 60 seconds.
**NOTE:** Arming the system from a remote location with a web-enabled device, such as a computer or smart phone, does NOT initiate the
Exit Delay countdown.

**Q202: Entry delay 1, in seconds**
Configures the number of seconds for the Entry Delay 1 timer. Different times may be programmed for each Smart Areas.  (Smart Areas feature
must be enabled (Q107) for values for S2-S4 to affect the system) This specifies the amount of time occupants have to disarm the system after
entering the premises through a door. Typically, the primary entrance programmed as an Exit/Entry 1 door uses this time. When the user enters
the premises, the countdown timer starts. The 2GIG EDGE Panel beeps once every two (2) seconds during the countdown.
Choose one of these options:

» **30-240 Seconds:** Choose a value between 30 and 240 seconds.
» † ‡ **30 Seconds:** For compliance with ANSI/SIA CP-01-2010, the default Entry Delay 1 feature is set to 30 seconds.

**Q203: Entry delay 2, in seconds**
Configures the number of seconds for the Entry Delay 2 timer. Different times may be programmed for each Smart Areas.  (Smart Areas feature must
be enabled (Q107) for values for S2-S4 to affect the system) This specifies the amount of time occupants have to disarm the system after entering the
premises through a door. Typically, secondary entrances that require a slightly longer entry time are programmed as an Exit/Entry 2 door. For example,
a back, side, or garage entry door. When a user enters the premises while the system is armed, the Entry Delay 2 countdown starts. The 2GIG EDGE
Panel beeps once every two (2) seconds during the countdown.
Choose one of these options:

» **30-240 Seconds:** Choose a value between 30 and 240 seconds.
» †‡ **45 Seconds:** For compliance with ANSI/SIA CP-01-2010, the default Entry Delay 2 feature is set to 45 seconds.

**Q204: Alarm cancel time, in minutes**
Configures the system to transmit a cancellation report to the Central Station whenever an alarm is canceled by a user within the amount of time
specified here. To learn how to change the setting for the alarm information that displays on the touchscreen, see “Q122: Alarm cancel display” below.

» † ‡ **5 Minutes:** For compliance with ANSI/SIA CP-01-2010, the minimum required setting is 5 minutes. This can be extended to a
greater number of minutes without affecting compliance.
» **6-254 Minutes:** Enter a value between 6 and 254 minutes.
» **255:** To transmit a cancellation report anytime the system is disarmed after an alarm, enter 255.

**Q205: Alarm abort window transmission delay**
Configures the amount of time the system will wait to initiate the digital transmission when an alarm condition is triggered. This setting specifies
the number of seconds the user has to manually abort the alarm, in the event of a false alarm.

**NOTE:** The transmission delay can be increased to 45 seconds without affecting ANSI/SIA CP-01 compliance only if the combination of
Q205 and *Q202: Entry delay 1, in seconds (30-240)* in *Q203: Entry delay 2, in seconds (30- 240)* does not exceed one (1) minute.

Choose one of these options:
» **15 seconds:** The system waits 15 seconds to initiate the dialer.
» † ‡ **30 seconds:** For compliance with ANSI/SIA CP-01-2010, the default minimum setting is 30 seconds. This setting can be increased
to 45 seconds without affecting compliance only if the combination of this setting.
» **45 seconds:** The system waits 45 seconds to initiate the dialer.

**Q206: Burglary bell cutoff time**
Defines the amount of time the system sounds the burglary alarm after the alarm is activated. After the time set here expires, the alarm siren
shuts OFF.

**NOTE:** This setting only affects the 2GIG EDGE Panel alarm. It does not affect any auxiliary alarms that may be installed. Typically,
auxiliary alarms are set to sound for an unlimited amount of time.

*Installation Guide for the 2GIG EDGE Security Panel*
48

---

## Page 49

Choose one of these options:
» † **4 Minutes** : The alarm siren shuts OFF after 4 minutes.
» **8 Minutes:** The alarm siren shuts OFF after 8 minutes.
» **12 Minutes:** The alarm siren shuts OFF after 12 minutes.
» **16 Minutes:** The alarm siren shuts OFF after 16 minutes.
» **Unlimited Time:** The alarm siren must be shut OFF manually.

**Q207: Fire bell cutoff time**
Specifies the amount of time a Carbon Monoxide Detector or Smoke/Heat/Freeze Alarm should sound after the alarm is activated. After the time
set here expires, the alarm siren shuts OFF.

**NOTE:** This setting only affects the panel alarm. It does not affect any auxiliary alarms that may be installed. Typically, auxiliary alarms
are set to sound for an unlimited amount of time.

Choose one of these options:
» † **4 Minutes:** The alarm siren shuts OFF after 4 minutes.
» **8 Minutes:** The alarm siren shuts OFF after 8 minutes.
» **12 Minutes:** The alarm siren shuts OFF after 12 minutes.
» **16 Minutes:** The alarm siren shuts OFF after 16 minutes.
» **Unlimited Time:** The alarm siren must be shut OFF manually.

**Q208: Swinger shutdown count**
Specifies the swinger shutdown count for burglary protection zones. This defines the maximum number of times a zone’s sensor can activate (i.e.,
“trip”) an alarm during a single arming session. For example, if the count is set to two (2) trips, a window contact sensor would be permitted to
trip the alarm a maximum of two (2) times during a single arming session.

Choose one of these options:
» **1-6 Trips:** Use the touchscreen’s numeric keypad to specify a value between one (1) and six (6) trips.
» † ‡ 2 **Trips:** For compliance with ANSI/SIA CP-01-2010, this is the default setting.

**Q209: Cross sensor timeout, in seconds**
Defines the maximum number of seconds it takes the system to activate an alarm when both sensors in a cross sensor zone are violated. The
value you define here specifies the maximum amount of time that can pass between the violation of sensors programmed for Wireless Zone 99
and Wireless Zone 100. If both sensors are violated within the amount of time specified here, the system activates an alarm. If only one of the
sensors is violated during the timeout interval, the system transmits a trouble report to the Central Station and does not activate an alarm.

**NOTE:** For the timeout to affect the system, the Cross Sensor Zones feature must also be enabled on the system. See *Q123: Cross*
*sensor zones 99-100* .

You have these options:
» † **10 Seconds:** Defines the cross sensor time interval as 10 seconds.
» **1- 120 Seconds:** To extend the timeout interval, the installer programs a value between 1 to 120 seconds.

**Q210: Time to detect AC loss, in minutes**
Configures the system to display a trouble alert in response to AC power loss after a specified amount of time has passed. By default, the system
is configured to both display and sound a trouble alert when the 2GIG EDGE Panel is without AC power for 10 minutes. When AC power is restored
to the 2GIG EDGE Panel, the trouble alert condition clears automatically after one (1) minute.

Choose one of these options
» **0 Minutes:** Turns the feature OFF.
» † **10 Minutes:** The system displays a trouble alert on the touchscreen and sounds a trouble siren when the 2GIG EDGE Panel is without
AC power for 10 minutes.
» **1-30 Minutes:** Enter a value between one (1) and 30 minutes
**NOTE:** The Time to Detect AC Loss feature also transmits a trouble report to the Central Station. The time at which the trouble report is
sent depends on what the installer configured for *Q211: Random AC loss report time* below.

**Q211: Random AC loss report time**
Configures the 2GIG EDGE Panel to transmit the Central Station a trouble report about AC power loss. When enabled, the system transmits the report
at a random time that falls within 45 minutes of the time at which the Time to Detect AC Loss, in Minutes feature was first triggered. See *Q210: Time to*
*detect AC loss, in minutes* on the previous page. When enabled, this feature minimizes network congestion for the Central Station, should a regional area
experiencing a widespread power outage affect a large number of 2GIG EDGE Panel users.

Copyright © 2022 Nortek Security & Control LLC
49

---

## Page 50

Choose one of these options:
» † **Enabled:** Turns the feature ON.
» **Disabled:** Turns the feature OFF.

**Q212: Siren supervision time**
Configures the system to supervise the wire between an external alarm sounder (if installed) and the 2GIG EDGE Panel. In the event that the
supervised wire is cut, the system waits the number of seconds specified here and then displays a trouble alert on the panel’s touchscreen. It also
transmits a trouble report to the Central Station.

Choose one of these options:
» † **Disabled:** Turns the feature OFF.
» **15 Seconds:** Turns the feature ON. 15 seconds after a wire cut is detected, the system displays a trouble alert on the touchscreen and
also transmits a trouble report to the Central Station.
» **30 Seconds:** Turns the feature ON. 30 seconds after a wire cut is detected, the system displays a trouble alert on the touchscreen and
also transmits a trouble report to the Central Station.
» **45 Seconds:** Turns the feature ON. 45 seconds after a wire cut is detected, the system displays a trouble alert on the touchscreen and
also transmits a trouble report to the Central Station.
**Panel Configurations**

**Q301: Police emergency key**
Configures the system to respond in two (2) ways when a user manually activates a panic alarm on the 2GIG EDGE Panel. The system can either
be set to emit a loud, patterned warning siren or to set off a silent panic alarm with no siren. You can also disable the Panic button so that it is not
visible on the 2GIG EDGE Panel.

Choose one of these options:
» **Disabled:** Turns the feature OFF and hides the Panic button from the Alarm screen.
» † **Audible:** Turns the feature ON. This makes the Panic button visible on the Alarm screen. The system sounds a loud, patterned warning
siren after the user activates a panic alarm.
» **Silent Panic:** Turns the feature ON. This makes the Panic button visible on the Alarm screen. The system sounds a silent panic alarm
with no warning siren after the user activates a panic alarm.

**Q302: Fire emergency key**
Configures the system to show or hide the Fire button on the Alarm screen of the 2GIG EDGE Panel. When set to Audible, the button is visible and the
system emits a loud, patterned warning siren when a user manually activates a fire emergency alarm on the 2GIG EDGE Panel.

Choose one of these options:
» **Disabled:** Turns the feature OFF and hides the Fire button from the Alarm screen.
» † **Audible:** Turns the feature ON. This makes the Fire button visible on the Alarm screen. The system sounds a loud, patterned warning
siren after the user activates a fire alarm.

**Q303: Emergency key**
Configures the system to show or hide the Emergency button on the Alarm screen of the 2GIG EDGE Panel. When set to Audible, the button is
visible and the system emits a loud, patterned warning siren when a user sets off an emergency alarm on the 2GIG EDGE Panel.
Choose one of these options:

» **Disabled:** Turns the feature OFF and hides the Emergency button from the Alarm screen.
» † **Audible:** Turns the feature ON. This makes the Emergency button visible on the Alarm screen. The system sounds a loud, patterned
warning siren after the user activates an emergency alarm.

**Q304: On-Board Camera**
Configures the system to turn off the On-Board camera used any of panel features such as “snapshots” and “Face Recognition”.
Choose one of these options:

» **† Enabled:** On-Board camera is on.  Camera turns on momentarily when panel features, such as face recognition or photo snapshot,
are active
» **Disabled:** On-Board camera is turned off.  All features using On-Board camera are unavailable.

**NOTE:** This is a global setting.

*Installation Guide for the 2GIG EDGE Security Panel*
50

---

## Page 51

**Q305: Temperature display units**
Specifies the temperature scale used by the system to display weather forecasts on the touchscreen.

**NOTE:** Weather forecasts are only available on the 2GIG EDGE Panel when enabled by the service provider.
Choose one of these options:
† **Fahrenheit:** Displays information using the Fahrenheit temperature scale.
**Celsius:** Displays information using the Celsius temperature scale.
**Q306: Configuration change acknowledgement**
Configures the system to annunciate or suppress annunciation of the panels status after a reboot or panel programming.

» † **Enabled:** The panel will announce the panel status when the panel powers up, reboots, or exits programming.
» **Disabled:** This option will suppress the annunciation of the panel status when the panel powers up, reboots, or exits programming.
**NOTE:** When any changes are made to the panel from Alarm.com, including programming questions, changes to sensors, adding,
deleting, or changing users, the 2GIG EDGE panel will announce its status. Example: “System disarmed, ready to arm.” Changing Q306
to Disabled will suppress this annunciation from the panel.

**NOTE:** Q306 will only affect the annunciation of the status of the panel, as described above. Q306 will not affect any other annunciations
of the 2GIG EDGE panel.

**Q307: Open collector #1 output**
Defines output mode for the external device connected to the OCL1 position of the panel’s terminal block. See **Control Panel Wiring Diagram** ,
page 24.

**NOTE:** For compliance with ANSI/SIA CP-01-2010, you must set Open Collector Output #1 to 11 - Follows Internal Sounder Alarm.
**NOTE:** If you enabled a keyfob auxiliary button to trigger the panel’s Open Collector #1, make sure this question is set to 00 Disabled,
“Program a Keyfob.”

Choose one of these options:

| Code | Open Collector Output | Code | Open Collector Output |
| --- | --- | --- | --- |
| 00 | Disabled | 06 | Activated on Burglary Alarm |
| 01 | Activated When Armed | 07 | Activated on Fire Alarm |
| 02 | Activated When Disarmed | 08 | Activated on Any Alarm |
| 03 | Activated on FTC (Failure to Communicate | 09 | Activated on Any System Trouble |
| 04 | Activated on Siren Supervision | † 11 | Follows Internal Sounder Alarm |
| 05 | Activated on Radio Fault | 12 | Follows Exit/Entry Beeps |


**Q308: Open collector #2 output**
Defines the output mode for the external device connected to the OCL2 position of the panel’s terminal block. See **Control Panel Wiring Diagram** ,
page 24.

**NOTE:** The factory default setting for *Open Collector Output #2 is 00-Disabled* .
Choose one option from *Open Collector Output Table* (above).
**Q309: Allow backlight always on**
Configures the system to always display the option to leave the touchscreen’s backlight on. This is useful when users want to demonstrate panel
features, without the system backlight timing out.

**IMPORTANT:** Leaving the backlight ON for extended periods of time may result in image retention. To avoid this, it is recommended that
you only enable this feature when the panel is intended for use as a demonstration system.

Choose one of these options:
» **Enabled:** The backlight for the touchscreen is always ON.
» † **Disabled:** The backlight for the touchscreen dims automatically after 60 seconds of inactivity.

**NOTE:** **Timeout** has to be set in Screen Settings in order for this option to take affect.

Copyright © 2022 Nortek Security & Control LLC
51

---

## Page 52

**Troubles**

**Q401: Radio modem network failure time, in minutes**
Configures the system to display a trouble alert on the touchscreen when the system loses its cellular radio network connection. The number of
minutes you specify here defines the amount of down time that must pass before the system issues a trouble alert report. Once network service is
restored for five (5) minutes, the trouble alert condition automatically clears itself.
Choose one of these options:

» **0 Minutes:** Turns the feature OFF. The system does not issue a trouble alert
» **1-255 Minutes:** Turns the feature ON. Use the touchscreen’s numeric keypad to enter the number of minutes between 1 and 255.
» † **30 Minutes:** Turns the feature ON and issues a trouble alert on the 2GIG EDGE Panel after 30 minutes of down time.

**Q402: Radio network failure causes trouble**
Configures the system to display a trouble alert on the touchscreen when it logs a trouble alert condition with the cellular network connection.
The 2GIG EDGE Panel will display an alert message on the touchscreen after the number of minutes specified in *Q401: Radio modem network failure*
*time, in minutes (0-255)* above expires.
Choose one of these options:

» † **Enabled:** Turns the feature ON. The 2GIG EDGE Panel displays a visual trouble indicator after a cellular radio network failure.
» **Disabled:** Turns the feature OFF. The 2GIG EDGE Panel will not display a visual indicator after a cellular radio network failure.

**NOTE:** Regardless of the setting selected here, a radio network failure will always be logged in the System History.
Once the network connection is restored, the system automatically clears the visual indicator. A record of the trouble alert condition is stored in
the **System History** .

**Q403: Radio network failure reports**
Configures the system to transmit a trouble report to the Central Station when the system detects a cellular radio network failure.
Choose one of these options:

» † **Enabled:** Turns the reporting feature ON. The 2GIG EDGE Panel will transmit a trouble report to the Central Station after a cellular
radio network failure.
» **Disabled:** Turns the reporting feature OFF. The 2GIG EDGE Panel will not transmit a trouble report to the Central Station after a cellular
radio network failure.

**Q404: Broadband network failure time in minutes**
Configures the system to display a trouble alert on the touchscreen when the system loses its broadband network connection.  The number of
minutes you specify here defines the amount of down time that must pass before the system issues a trouble alert report.  Once the broadband
connection is restored for five (5) minutes, the trouble condition automatically clears itself.
Choose one of these options:

» **0 minutes:** Turns the feature OFF.  The system does not issue a trouble alert
» **1-255 minutes:** Turns the feature ON.  Use the touchscreen’s numeric keypad to enter the number of minutes between 1 and 255
» † **30 Minutes:** Turns the feature ON and issues a trouble alert on the 2GIG EDGE Panel after 30 minutes of down time.

**Q405: Broadband network failure causes trouble**
Configures the system to display a trouble alert on the touchscreen when it logs a trouble alert condition with the broadband network connection.
The 2GIG EDGE Panel will display an alert message on the touchscreen after the number of minutes specified in *Q404:  Broadband network failure*
*time, in minutes (0-255)* above expires.
Choose one of these options:

» † **Enabled:** Turns the feature ON.  The 2GIG EDGE Panel displays a visual trouble indicator after the broadband network failure.
» **Disabled:** Turns the feature OFF.  The 2GIG EDGE Panel will not display a visual indicator after a broadband network failure.  Once the
network connection is restored, the system automatically clears the visual indicator.  A record of the trouble alert condition is stored in the
System History.

**Q406: Broadband network failure reports**
Configures the system to transmit a trouble report to the Central Station when the system detects a broadband network connection.
Choose one of these options:

» † **Enabled:** Turns the reporting feature ON.  The 2GIG EDGE Panel will transmit a trouble report to the Central Station after a broadband
network failure.
» **Disabled:** Turns the reporting feature OFF.  The 2GIG EDGE Panel will not transmit a trouble report to the Central Station after a
broadband network failure.

*Installation Guide for the 2GIG EDGE Security Panel*
52

---

## Page 53

**Q407: Trouble doesn’t sound at night**
Prevents audible trouble alerts from waking users during nighttime hours. When this feature is turned ON, audible trouble alerts are suppressed
between the pre-configured hours of 10:00 PM - 9:00 AM. This setting does not suppress any other trouble alert features. The system will
continue to display trouble alert messages on the touchscreen.

It will also continue to transmit trouble reports to the Central Station, as well as to log trouble alerts in the system’s Alarm History.
If the reported trouble condition clears on its own or a user acknowledges the condition(s) on the Control Panel before 9:00 AM, no trouble tones
will sound after 9:00 AM. However, the trouble condition is recorded in the system’s Alarm History.
Choose one of these options:

» † **Enabled:** Turns the feature ON.
» ‡ **Disabled:** Turns the feature OFF. For compliance with UL 985: Household Fire Warning System Units, this setting must be disabled.

**Q408: RF jam causes trouble**
Configures the system to activate a trouble condition when the wireless receiver in the 2GIG EDGE Panel detects that one of the system’s RF
transmitters is causing an RF jam. For this setting to go into affect, you must also enable *Q504: Trouble reports to CS* .
Choose one of these options:

» **Enabled:** The system detects RF jamming.
» † **Disabled:** The system does not detect RF jamming.

**Q409: System tamper causes trouble**
Configures the system to activate a trouble condition if one of the tamper switches on the 2GIG EDGE Panel (wall tamper switch or cell radio
tamper switch) is triggered while the system is disarmed. The system will also activate an alarm condition if a tamper switch is triggered while
the system is armed.
You have these options:

» † **Enabled:** The system activates a trouble condition.
» **Disabled:** The system does not activate a trouble condition.

**CS Reporting**

**Q501: CS lack of usage notification time, in days**
Configures the system to monitor itself for lack of usage. If the system is not armed for the number of days you specify here, an inactivity report is
sent to the Central Station.
Choose one of these options:

» **0 Days:** Turns this feature OFF.
» **1-255 Days:** Turns this feature ON and transmits an inactivity report to the Central Station after the specified number of days.
» † **7 Days:** Turns this feature ON and transmits an inactivity report to the Central Station after seven (7) days of inactivity.

**Q502: Periodic test, in days**
Configures the system to automatically transmit periodic test reports about the panel's connections to the Central Station at the recurring interval
you specify here.
Choose one of these options:

» **0 Days:** Turns the feature OFF. The system does not transmit periodic test reports to the Central Station.
» **1-255 Days:** Turns the feature ON. The system transmits periodic test reports to the Central Station at recurring intervals using the
number of days specified here.
» † **30 Days:** Turns the feature ON. The system transmits periodic test reports to the Central Station once every 30 days.

**Q503: Programming mode entry reports to CS**
Configures the system to transmit programming reports to the Central Station. When enabled, this setting automatically transmits a report to the
Central Station when programming mode is started and terminated.
Choose one of these options:

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Programming access setting on Alarm.com monitoring settings supersedes Q503 Programming mode entry reports to CS.

Copyright © 2022 Nortek Security & Control LLC
53

---

## Page 54

**Q504: Trouble reports to CS**
Configures the system to transmit trouble reports to the Central Station when the system detects that any sensor encounters a trouble condition.

**NOTE:** This setting does not affect trouble reports caused by Control Panel conditions. It only affects trouble reports caused by sensors.
» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Trouble setting on Alarm.com monitoring settings supersedes Q504: Trouble reports to CS.

**Q505: Trouble restore reports to CS**
Configures the system to transmit reports to the Central Station when a sensor’s trouble condition clears.
Choose one of these options:

» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Trouble restore setting on Alarm.com monitoring settings supersedes Q505: Trouble restore reports to CS.

**Q506: Manual bypass reports to CS**
Configures the system to transmit reports to the Central Station whenever a sensor is manually bypassed by a user.

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Bypass setting on Alarm.com monitoring settings supersedes Q506: Manual bypass reports to CS.

**Q507: Bypass restore reports to CS**
Configures the system to transmit reports to the Central Station when a bypassed sensor (forced or manually bypassed) is restored.
Choose one of these options:

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Bypass setting on Alarm.com monitoring settings supersedes Q507: Bypass restore reports to CS

**Q508: Force bypass reports**
Configures the system to transmit a report to the Central Station when a user force-bypasses a sensor while the system is armed.
You have these options:

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Forced bypassed sensors are always recorded in the event log, regardless of the setting of this programming question. Bypass
setting on Alarm.com monitoring settings supersedes Q508: Force bypass reports to CS.

**Q509: AC loss reports to CS**
Configures the system to transmit reports to the Central Station if the 2GIG EDGE Panel loses AC power. When enabled, this setting waits the
number of minutes specified in *Q210: Time to detect AC loss, in minutes* , page 49. If *Q211: Random AC loss report time* above is enabled, the report will
be sent at a random time of up to 45 minutes after the power loss event.

» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.
When the system loses AC power, a *“Power Lost”* message appears on the touchscreen and the system icon state changes to show that the 2GIG
EDGE panel is not operating on AC power.

**Q510: AC restore reports to CS**
Configures the system to transmit a report to the Central Station when AC power is restored to the 2GIG EDGE Panel. When enabled, AC power
must be restored for one (1) minute before the trouble condition clears from the system.
You have these options:

» † **Enabled:** The system transmits a report to the Central Station. If *Q211: Random AC loss report time* above is enabled, the report will be
sent at a random time up to 45 minutes after the trouble conditions clears.
» **Disabled:** The system does not transmit a report to the Central Station.

*Installation Guide for the 2GIG EDGE Security Panel*
54

---

## Page 55

**Q511: System low battery reports to CS**
Configures the system to transmit low battery reports about the 2GIG EDGE Panel to the Central Station.
Choose one of these options:

» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.

**Q512: System low battery restore reports to CS**
Configures the system to transmit a report to the Central Station after a low battery condition on the 2GIG EDGE Panel is restored.
Choose one of these options:

» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.

**Q513: RF low battery reports to CS**
Configures the system to transmit low battery reports about the system’s sensors and peripherals to the Central Station.
Choose one of these options:

» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.

**Q514: Sensor low battery restore reports to CS**
Configures the system to transmit a report to the Central Station after a low battery condition for a sensor is restored.
Choose one of these options:

» † **Enabled:** The system transmits a report to the Central Station.
» **Disabled:** The system does not transmit a report to the Central Station.

**Q515: System disarmed reports to CS**
Configures the system to transmit a report to the Central Station when the system is disarmed by a user. The report includes the keyfob or user
code that disarmed the system.
Choose one of these options:

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Arming setting on Alarm.com monitoring settings supersedes Q515: System disarmed reports to CS

**Q516: System armed reports to CS**
Configures the system to transmit a report to the Central Station when the system is disarmed by a user. The report includes the keyfob or user
code that disarmed the system.
Choose one of these options:

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Arming setting on Alarm.com monitoring settings supersedes Q516: System armed reports to CS

**Q517: Alarm restore reports to CS**
Configures the system to transmit reports to the Central Station after an alarm, either when the Bell Cutoff Time expires or when the system is
disarmed.

You have these options:
» **Enabled:** The system transmits a report to the Central Station. Depending on the number of trips set for a cross sensor zone, the
feature works as follows:

» If enabled and *Q208* on page 1 is set to two (2) trips, the system transmits a report when the triggering sensor is closed (i.e., in its
normal state) at the Bell Cutoff Time or if the sensor is closed after the Bell Cutoff Time.
» If enabled and *Q208* on page 1 is set to one (1) trip, the system transmits a report only if the sensor is closed at the time the system is
disarmed. Reports are not sent if a sensor is in swinger shutdown until the time of disarm and the sensor is closed.
» † **Disabled:** The system does not transmit a report to the Central Station.
**NOTE:** Alarms setting on Alarm.com monitoring settings supersedes Q517: Alarm restore reports to CS.

Copyright © 2022 Nortek Security & Control LLC
55

---

## Page 56

**Q518: Smart test reports**
Configures the system to transmit smart test reports to the Central Station. A smart test report is designed to reduce incoming network traffic for
the Central Station. When enabled in combination with *Q502: Periodic test, in days (0-255)* , all non-test reports occurring during normal operations
will restart the periodic test report timer (for example, alarm, restore, trouble, etc.). Periodic test reports are only sent when the 2GIG EDGE Panel
has not reported in any way to the Central Station.
Choose one of these options:

» **Enabled:** The system transmits a report to the Central Station.
» † **Disabled:** The system does not transmit a report to the Central Station.

**Restore the Factory Default Settings**

You can restore the Control Panel settings back to their factory defaults.
A soft reset lets you select which settings to restore back to the factory defaults.
To perform a soft reset:
**1.** Navigate to the **Installer Toolbox** options.
**2.** Tap **RESTORE DEFAULTS** .
**3.** At the **Restore Defaults** screen, tap the switch adjacent to areas that you would like to restore and tap **RESTORE** .
*Restore Defaults Screen*

This restores the factory defaults setting for the areas selected, and then the system restarts.

**2GIG EDGE REMOTE KEYPAD**

The Remote Keypad (2GIG-EDG-RK) is a wall-mounted, full-color, touch screen interface that provides all of the same easy-to-use keypad
functions available on the Control Panel. It is designed for indoor use only and gives users the ability to arm and disarm the system, see the status
of sensor zones, and control Smart Home devices.

For installation and pairing instructions, refer to the manual for the 2GIG EDGE Remote Keypad.

*Installation Guide for the 2GIG EDGE Security Panel*
56

![Image 1 on page 56](images/2GIG_Edge_Installation_Guide_p56_img1.jpeg)


---

## Page 57

**PANEL PROGRAMMING**

| (04) Interior Follower | This sensor type is for interior sensors, such as motion detectors, interior doors, and other sensors that detect human presence inside the protected premises. This type of sensor is called a “follower” due to its action when the system is armed. in the Away mode. After the exit delay expires and the system is armed, if an interior follower sensor is triggered, an instant alarm will occur. If an exit/entry delay sensor is triggered first, the interior follower sensor will also be delayed. Interior follower sensors are always bypassed and not active when the system is armed in Stay mode. This allows the premises to be occupied while still protecting the perimeter. |
| --- | --- |
| (05) Day Zone | This sensor type is the same as a perimeter zone, except that when the system is disarmed, a violation displays a trouble alert on the Console’s display. This type of sensor is commonly used to protect sensitive areas that require notification and possibly a Central Station trouble report, but not an alarm when the system is disarmed. |
| (06) 24-Hour Silent Alarm | This sensor type is active independent of the system arming status. The code for silent panic is sent to the Central Station, but for safety, there are no visual or audible indications locally that this sensor type has been triggered. |
| (07) 24-Hour Audible Alarm | This sensor type is continuously armed 24-hours-a-day. A sensor programmed to this type will trigger a local alarm and the bell output regardless of the mode the system is in. This sensor type is typically used for an audible panic alarm. |
| (08) 24-Hour Auxiliary Alarm | This sensor type is continuously armed 24-hour-a-day. A sensor programmed to this type will trigger an alarm regardless of the mode the system is in. The bell output will not activate, but the local sounder will continue until it is acknowledged at the Control Panel. This sensor type is typically used for a monitoring device, such as a flood or temperature sensor. There is no time out for the internal sounds; it will continue until a user code is entered. |

When programming wireless and wired zones, as well as keyfobs
and keypads, installers are required to choose options for a variety of
settings. This topic describes each setting and its available options.

**Sensor Programming Reference**
Required for all wired and wireless zones.

| Sensor Type | Description |
| --- | --- |
| (00) Unused | This is the setting for unused sensor numbers that do not have a sensor programmed into them. No system action occurs at any time from this sensor type. |
| (01) Exit/Entry 1 | This sensor type is reserved for doors that are used for exit and entry of the protected premises. When the system is armed in the Stay or Away mode, the exit delay timer starts. There is an exit delay regardless of whether the system is armed in Stay or Away mode. When the exit delay timer expires, the system is fully armed. With the system fully armed, when this type of sensor is triggered, the Entry Delay 1 timer starts. The system must be disarmed before the Entry Delay 1 timer expires, or an alarm will occur. If the entry delay timer is turned OFF during arming, the exit/entry delay sensors will act as non-delayed instant sensors at the end of the exit delay. |
| (02) Exit/Entry 2 | This sensor type operates the same as the Exit/Entry 1 sensor type except that it starts the Entry Delay 2 timer. This provides a method of having a longer entry delay on certain openings, such as a garage door, to provide the end user more time to disarm the system. |
| (03) Perimeter | This sensor type is for perimeter doors and windows that will not be used to enter or exit the protected premises while the system is armed. An instant alarm will occur when this type of sensor is triggered with the system armed in either the Stay or Away mode. |


Copyright © 2022 Nortek Security & Control LLC
57

---

## Page 58


| (09) 24-Hour Fire † | This sensor type is continuously armed 24-hours-a-day. A sensor programmed to this type will trigger the local alarm fire sounder and the bell output regardless of the mode the system is in. This sensor type is typically used for wireless smoke detectors. This sensor type is always active and cannot be bypassed. |
| --- | --- |
| (10) Interior with Delay | This sensor type operates as a delayed sensor when the system is armed in the Away mode, and when triggered, will start the Entry Delay 1 timer. If the system is armed in Away mode with no Entry Delay (armed instant), this sensor type will trigger an instant alarm. If the system is armed in Stay mode (or Stay mode with no Entry Delay), this sensor type will be bypassed. |
| (14) 24-Hour Carbon Monoxide † | This sensor type is continuously armed 24-hours-a-day. A sensor programmed to this type will trigger the local alarm pulse sounder and the bell output regardless of the mode the system is in. This sensor type is typically used for wireless carbon monoxide detectors. This sensor type is always active and cannot be bypassed. |
| (16) 24- Hour Fire Verification † | This sensor type is continuously armed 24-hours-a-day. A sensor programmed to this type can trigger the local alarm fire sounder and the bell output regardless of the mode the system is in. This sensor type is typically used for wireless smoke detectors. This sensor type is always active and cannot be bypassed. For verification, this sensor type must be violated twice in two (2) minutes, or remain violated for 30 seconds. If any other fire sensor (verified sensor type or not) violates within two (2) minutes, both sensors will cause a fire alarm. |
| (23) No Response Type | This sensor type is a special zone that can be monitored for activity or inactivity by the Central Station. It does not affect security system status. |
| (24) Silent Burglary | This sensor type is for silent triggering the burglary alarm with perimeter doors and windows that will not be used to enter or exit the protected premises while the system is armed. The Control Panel’s sounder and the bell output will not activate. An instant silent alarm will occur when this type of sensor is triggered with the system armed in either the Stay or Away mode. |
| (32) Remote Device | Special Zone with Wireless Repeater |

**Sensor Equipment Type**
For wireless zones that have been specified as being on one of these
equipment types (for example, *04-Interior Follower, 06-24-Hour Silent*
*Alarm, 07- 24-Hour Audible Alarm, 08 24-Hour Auxiliary Alarm, 10-*
*Interior with Delay, 23-No Response Type* ), installers must also select
one of the **Sensor Equipment Types** listed below.


| Sensor Type | Sensor Equipment Type |
| --- | --- |
| (04) Interior Follower | Contact, Motion |
| (06) 24-Hour Silent Alarm | Contact, Emergency |
| (07) 24-Hour Audible Alarm | Contact, Emergency |
| (08) 24-Hour Auxiliary Alarm | Contact, Freeze, Water, Temperature, Emergency |
| (10) Interior with Delay | Contact, Motion |
| (23) No Response Type | Contact, Motion |


This zone type is selected by the installer when pairing the panel with
peripheral devices that can utilize localized troubles (such as RF jam,
low battery, tamper, or AC loss detected by the peripheral device).  This
sensor is continuously active and will cause a trouble at the panel for
all problem conditions.  When the panel is in an armed state, this sensor
type will cause an alarm for TAMPER and RF JAM.  All trouble conditions
will be sent to the monitoring station if reporting is enabled with the
exception of AC LOSS.  This will only be displayed at the panel.

**Equipment Codes**
Required for all wireless zones, keyfobs, and keypads.

**Wireless Zones—Equipment Codes**
0000-Other
2862-eSeries Thin Door/Window Contact
0862-2GIG Thin Door/Window Contact
2863-eSeries Recessed Door Contact
0863-2GIG Recessed Door Contact
2869-eSeries PIR with Pet Immunity
0869-2GIG PIR with Pet Immunity
2864-eSeries Glass Break Detector
0864-2GIG Glass Break Detector
2058-eSeries Smoke Detector (USA)
1058-2GIG Smoke Detector

† Indicates sensor types that are not allowed for hardwired loops.

*Installation Guide for the 2GIG EDGE Security Panel*
58

---

## Page 59

**Keyfobs**
2860-eSeries CO Detector (USA)
1026-2GIG CO Detector
0000-Other
2069-eSeries FireFighter SMK/CO Listener
2866-eSeries Key FOB
1069-FireFighter SMK/CO Listener
0866 - KEY2-345
2070-eSeries Water Sensor
0577 - Exiting Keyfob Remote
1070-2GIG Fall Detector Pendant (2GIG -F1-345)
***NOTE:** eSeries sensors are only compatible with the 2GIG EDGE panel.
1072-2GIG Smoke Ring
**Transmission ID (TXID)**
Required for all wireless zones.
2868-eSeries Panic
0868-2GIG Panic Button Remote
It’s a 7-digit Transmission ID (TXID) that the Control Panel uses to
identify a sensor TXID is printed on the sensor box or the label on the
sensor body.
1071-2GIG Personal Help Button (2GIG-PHB-345)
2865-eSeries Outdoor Door/Window
**Normal State**
This applies only to wired zones.
0865-2GIG Outdoor Door/Window Sensor
2065-eSeries Flood Sensor
**Setting**
1065-2GIG Floor Sensor
Normally Open (EOL optional)
2061-eSeries Tilt Sensor
Normally Closed (EOL optional)
1062-2GIG Tilt Sensor
1063-2GIG Doorbell
**Sensor Loop**
Required for all wireless zones. Refer to the device manual.
2873-eSeries Takeover Module
0873-2GIG Takeover Module
2067-eSeries Repeater
1067-2GIG Repeater
0655-Existing Door/Window Contact
0609-Existing Motion Detector
0475-Existing Glass Break Detector
0616-Existing Smoke Detector
0692-Existing CO Detector
0708-Existing Heat Sensor
0556-Existing Flood/Temp Sensor
1061-Tilt Sensor
0470-HW R-D/W '5818MNL'
0637-Honeywell D/W '5816'
0530-HW PIR '5894PI'
0533-HW PIR '5890'
0519-HW Glass Break '5853'
0589-HW Smoke '5808W3'
0557-HW Heat Sensor '5809'
0624-HW Flood Sensor '5821'

Copyright © 2022 Nortek Security & Control LLC
59

---

## Page 60


| J | - |
| --- | --- |
| K | Key (121), Keyfob (122), Keypad (123), Kids’ (124), Kitchen (125) |
| L | Laundry (126), Leak (305), Left (127), Level (128), Library (129), Light (130), Lights (131), Liquor (132), Living (133), Loading (134), Lock (135), Loft (136), Low (137) |
| M | Main (138), Maintenance (139), Man (281), Master (140), Medical (141), Medicine (142), Menu (143), Middle (144),Monitor (145), Mother (299), Motion (146), Motion Detector (147), Mud (148) |
| N | Nine (149), Nineteen (150), Ninety (151), No Delay (155), No Entry Delay (156), North (152), Not (153), Not Ready (154), Nursery (157) |
| O | Off (158), Office (159), On (160), One (161), One Hundred (162), Output (163), Outside (164), Oven (306), Overhead (260) |
| P | Panel (165), Panic (166), Pantry (167), Patio (168), Perimeter (169), Person (300), Phone Line (170), Play (171), Police (172), Pool (173), Porch (270), Pound (174), Power (175), Press (176), Previous (177), Pump (178) |
| Q | - |
| R | Radio (179), Ready (180), Rear (181), Refrigerator (261), Relay (182), Remote (183), Repeat (184), RF Jam (185), Right (186), Room (187 |
| S | Safe (188), Second (189), Security (190), Sensor (191), Sensors (192), Service (262), Session (193), Set (194), Seven (195), Seventeen (196), Seventy (197), She (301), Shed (198), Shop (199), Side (200), Silent (201), Siren (202), Six (203), Sixteen (204), Sixty (205), Skylight (206), Sliding (207), Smoke (208), Spa ( 302), Son’s (282), Sounder (209), South (210), Space (211), Spare (212), Stairs (213), Star (214), Status (215), Stay (216), Stop (217), Storage (218), Study (219), Sump (220), Sun (283), Sunroom (263), Supervision (221), Switch (286), System (222) |
| T | Tamper (223), Temperature (224), Ten (225), Terminated (226), Theater (284), Thermostat (227), Third (228), Thirteen (229), Thirty (230), Three (231), To (232), Tool (233), Transmitted (234), Transmitter (235), Trouble (236), Turn (237), TV (268), Twelve (238), Twenty (239), Two (240) |
| U | Unlock (241), Upper (242), Upstairs (243), User (244), Utility (245) |
| V | Valve (246), Video (247), Voice (269) |
| W | Wall (248), Warehouse (264), Water (249), West (250), Window (251), Wine (303), Wing (285), Wireless (252), Workshop (304) |
| X | - |
| Y | Yard (253) |
| Z | Zero (254), Zone (255) |

**Transmission Delay**
Required for wired and wireless zones.

| Dialer Delay | Choosing this setting ... |
| --- | --- |
| Enabled (Default) | Turns the Transmission Delay feature ON |
| Disabled | Turns the Transmission Delay feature OFF |


**Voice Descriptor**
Required for all wireless and wired zones.

| Letter | On the touchscreen keypad, enter the first few letters of the Vocabulary Word (or its Numeric Code) |
| --- | --- |
| A | Abort (002), AC (003), Access (004), Alarm (005), And (006), Announcement (007), Apartment (266), Area (008), Arm(009), Armed (010), Arming (011), At (012), Attic (013), Audio (014), Auto (015), Automation (016), Auxiliary (017), Away (018) |
| B | Baby’s (019), Back (020), Balcony (256), Basement (021), Bathroom (022), Battery (023), Bedroom (024), Bell (272), Bluetooth (287), Bonus (025), Boy’s (273), Break (026), Button (027), Bypass (028), Bypassed (029) |
| C | Cabinet (030), Camera (274), Cancel (031), Carbon Monoxide (032), Cave (275), Celsius (289), Cellar (033), Cellular (034), Cell (288), Cell Radio (035), Center (036), Check (037), Chest (038), Children’s (039), Chime (040), Closet (041), Code (042), Communications (043), Computer (044), Control (045), Cool (046), Corner (271), Courtyard (257), Crawl (047), Current (048) |
| D | Daughter’s (276), Day (049), Deck (258), Degrees (050), Den (051), Detached (259), Detector (052), Dim (053), Dimming (290), Dining (054), Disarm (055), Disarmed (056), Disarming (291), Dock (057), Door (058), Doorbell (277), Downstairs (059), Driveway (060) |
| E | East (061), Eight (062), Eighteen (063), Eighty (064), Electric (065), Eleven (066), Emergency (067), Encrypted (292), Enter (068), Entrance (069), Entry (070), Error (071), Exercise (072), Exit (073), Exit Now (074), Exterior (075), External (076) |
| F | Face (293), Facial (294), Failure (077), Family (078), Fan (079), Fahrenheit (295), Father (296), Fifteen (080), Fifty (081), Fire (082), Fire Alert (083), Fire Detector (084), First (085), Five (086), Flood (087), Floor (088), Fluid (089), Foil (090), For (091), Forty (092), Four (093), Fourteen (094), Fourth (095), Foyer (267), Freeze (096), Freezer (097), Front (098), Furnace (099) |
| G | Game (100), Garage (101), Gas (102), Gate (265), Girl’s (278), Glass (103), Glass Break (104), Grill (307), Guest (105), Gun (106) |
| H | Hall (107), Hallway (108), Hanging (109), Hang Up (110), Heat (111), High (112), Home (113), Hot Tub (297), House (114) |
| I | Ice (115), Image (279), Image Sensor (280), In Law (298), Inside (116), Instant (117), Interior (118), Intrusion (119), Is (120) |


*Installation Guide for the 2GIG EDGE Security Panel*
60

---

## Page 61

**Sensor Reports**
Required for all wireless and wired zones.

| Sensor Reports | Choosing this setting ... |
| --- | --- |
| Enabled (Default) | Sends reports to the Central Station. |
| Disabled | Does NOT send reports to the Central Station. |


**Sensor Supervised**
Required for all wireless zones.

| Sensor Supervised | Choosing this setting ... |
| --- | --- |
| Enabled (Default) | Enables the sensor supervision feature. |
| Disabled | Disables the sensor supervision feature. |


**Sensor Chime**
Required for all wireless and wired zones.

**Sensor Chime Setting**

Disabled (Default)

Voice Only

Ding-Dong #1 with Voice

Ding-Dong #2

Ding-Dong #2 with Voice

Ding-Dong #1

Ding-Ding

Ding-Ding with Voice

Ding-Dong #3

Ding-Dong #3 with Voice

Chime #1

Chime #1 with Voice

Chime #2

Chime #2 with Voice

Copyright © 2022 Nortek Security & Control LLC
61

---

## Page 62

**Advanced Programming Reference**
This table summarizes the system’s panel programming questions, the available settings for each question, and each question’s factory-default
setting.


| Question Number | Question Text | Available Settings | Factory Default Setting | Programming Category | Page Reference |
| --- | --- | --- | --- | --- | --- |
| Q101 | Enter installer code (4 or 6 digits) | Unique 4-Digit Number | 1561 | System Configuration | 42 |
| Q102 | Security pin code length | 4 or 6 digits | 4 | System Configuration | 42 |
| Q103 | Lock installer programming | Disabled (Full Access) No Access Limited Access | Disabled (Full Access) | System Configuration | 43 |
| Q104 | Lock default programming | Allow Reset of All Defaults Allow Limited Reset of Defaults Do Not Allow Reset of Defaults | Allow Reset of All Defaults | System Configuration | 43 |
| Q105 | 2-way voice | Disabled Stay online Stay online, including fire and CO alarms | Stay online | System Configuration | 43 |
| Q106 | Disable siren after two-way audio | Yes No | No | System Configuration | 43 |
| Q107 | Smart Areas | Enabled Disabled | Disabled | System Configuration | 43 |
| Q108 | Z-Wave feature | Disabled and Hidden Disabled but Visible Enabled Enabled with Local Scenes Hidden | Enabled | System Configuration | 44 |
| Q109 | Master user can access Z-Wave setup | Enabled Disabled | Disabled | System Configuration | 44 |
| Q110 | Smart Home Controls require master code | Enabled Disabled | Disabled | System Configuration | 44 |
| Q111 | Main Panel Sounder Follows | All Smart Areas Main Panel Smart Area Only | All Smart Areas | System Configuration | 44 |
| Q112 | Z-Wave siren mode | Sound for Burglary and Fire/CO Sound for Burglary Only | Sound for Burglary and Fire/ CO | System Configuration | 44 |
| Q113 | Quick arming | Enabled Disabled | Enabled | System Configuration | 44 |
| Q114 | Auto stay | Enabled Disabled | ‡Enabled | System Configuration | 44 |
| Q115 | Exit delay restart | Enabled Disabled | ‡Enabled | System Configuration | 45 |
| Q116 | Allow quick exit | Enabled Disabled | Enabled | System Configuration | 45 |
| Q117 | Quick bypass | Enabled Disabled | Disabled | System Configuration | 45 |
| Q118 | Auto unbypass for manual bypass | Enabled Disabled | Enabled | System Configuration | 45 |


*Installation Guide for the 2GIG EDGE Security Panel*
62

---

## Page 63


| Question Number | Question Text | Available Settings | Factory Default Setting | Programming Category | Page Reference |
| --- | --- | --- | --- | --- | --- |
| Q119 | Alert on disarm with keyfob after alarm | Enabled Disabled | Disabled | System Configuration | 45 |
| Q120 | Keyfob arm/disarm confirmation | Enabled Disabled | Disabled | System Configuration | 46 |
| Q121 | Keyfob/remote arming mode on system not ready | Auto-Bypass with Zone Participation on Restore Auto-Bypass Arm Only When System Ready | Auto-Bypass with Zone Participation on Restore | System Configuration | 46 |
| Q122 | Alarm cancel display | Enabled Disabled | Enabled | System Configuration | 46 |
| Q123 | Cross sensor zones 99-100 | Enabled Disabled | Disabled | System Configuration | 46 |
| Q124 | Event log | Disabled All Events Except Open/Close/Bypass All Events Except Open/Close All Events | All Events | System Configuration | 46 |
| Q125 | LED Mode Control | Enabled Disabled | Disabled | System Configuration | 46 |
| Q126 | Commercial Burglary Support | Enabled Disabled | Disabled | System Configuration | 46 |
| Q201 | Exit delay, in seconds (45-120) | 45-120 Seconds | ‡60 Seconds | Timers, Delays & Counts | 47 |
| Q202 | Entry delay 1, in seconds (30-240) | 30-240 Seconds | ‡30 Seconds | Timers, Delays & Counts | 47 |
| Q203 | Entry delay 2, in seconds (30-240) | 30-240 Seconds | ‡45 Seconds | Timers, Delays & Counts | 47 |
| Q204 | Alarm cancel time, in minutes (5-255) | 5-255 Minutes | 5 Minutes | Timers, Delays & Counts | 47 |
| Q205 | Alarm abort window transmission delay | 15 Seconds 30 Seconds 45 Seconds | 30 Seconds | Timers, Delays & Counts | 47 |
| Q206 | Burglary bell cutoff time | 4 Minutes 8 Minutes 12 Minutes 16 Minutes Unlimited Time | ‡4 Minutes | Timers, Delays & Counts | 47 |
| Q207 | Fire bell cutoff time | 4 Minutes 8 Minutes 12 Minutes 16 Minutes Unlimited Time | ‡4 Minutes | Timers, Delays & Counts | 48 |
| Q208 | Swinger shutdown count (1-6) | 1-6 Trips | 2 Trips | Timers, Delays & Counts | 48 |
| Q209 | Cross sensor timeout, in seconds (10-120) | 10-120 Seconds | 10 Seconds | Timers, Delays & Counts | 48 |
| Q210 | Time to detect AC loss, in minutes | 0-30 Minutes | 10 Minutes | Timers, Delays & Counts | 48 |
| Q211 | Random AC loss report time | Enabled Disabled | Enabled | Timers, Delays & Counts | 48 |
| Q212 | Siren supervision time | Disabled 15 Seconds 30 Seconds 45 Seconds | Disabled | Timers, Delays & Counts | 49 |


Copyright © 2022 Nortek Security & Control LLC
63

---

## Page 64


| Question Number | Question Text | Available Settings | Factory Default Setting | Programming Category | Page Reference |
| --- | --- | --- | --- | --- | --- |
| Q301 | Police emergency key | Disabled Audible Silent Panic | Audible | Panel Configuration | 49 |
| Q302 | Fire emergency key | Disabled Audible | Audible | Panel Configuration | 49 |
| Q303 | Emergency key | Disabled Audible | Audible | Panel Configuration | 49 |
| Q305 | Temperature display units | Fahrenheit Celsius | Fahrenheit | Panel Configuration | 49 |
| 0306 | Configuration Change Acknowledgement | Enabled Disabled | Enabled | Panel Configuration | 50 |
| Q307 | Open collector #1 output | 00 - Disabled 01 - Activated when Armed 02-Activated when Disarmed 03-Activated on FTC 04 - Activated on Supervision 05-Activated on Radio Fault 06 - Activated on Burglary Alarm 07 - Activated on Fire Alarm 08 - Activated on Any Alarm 09 - Activated on Any System Trouble 11 - Follows Internal Sounder Alarm 12 - Follows Exit/Entry Beeps | 11-Follows Internal Sounder Alarm | Panel Configuration | 50 |
| Q308 | Open collector #2 output | 00 - Disabled 01 - Activated when Armed 02-Activated when Disarmed 03-Activated on FTC 04 - Activated on Supervision 05-Activated on Radio Fault 06 - Activated on Burglary Alarm 07 - Activated on Fire Alarm 08 - Activated on Any Alarm 09 - Activated on Any System Trouble 11 - Follows Internal Sounder Alarm 12 - Follows Exit/Entry Beeps | 00-Disabled | Panel Configuration | 50 |
| Q309 | Allow backlight always on (demo mode) | Enabled Disabled | Disabled | Panel Configuration | 50 |
| Q401 | Radio modem network failure time, in minutes (0-255) | 0- 255 Minutes | 30 Minutes | Troubles | 51 |
| Q402 | Radio network failure causes trouble | Enabled Disabled | Enabled | Troubles | 51 |
| Q403 | Radio network failure reports | Enabled Disabled | Enabled | Troubles | 51 |
| Q404 | Broadband network failure time | 0-255 Minutes | 30 | Troubles | 51 |
| Q405 | Broadband network failure causes trouble | Enable Disable | Enabled | Troubles | 51 |
| Q406 | Broadband network failure reports | Enable Disable | Enabled | Troubles | 51 |
| Q407 | Trouble doesn’t sound at night | Enabled Disabled | Enabled | Troubles | 52 |
| Q408 | RF jam causes trouble | Enabled Disabled | Disabled | Troubles | 52 |
| Q409 | System tamper causes trouble | Enabled Disabled | Enabled | Troubles | 52 |


*Installation Guide for the 2GIG EDGE Security Panel*
64

---

## Page 65


| Question Number | Question Text | Available Settings | Factory Default Setting | Programming Category | Page Reference |
| --- | --- | --- | --- | --- | --- |
| Q501 | CS lack of usage notification time, in days (0- 255) | 0- 255 Days | 7 Days | Reporting | 52 |
| Q502 | Periodic test, in days (0-255) | 0-255 Days | 30 Days | Reporting | 52 |
| Q503 | Programming mode entry reports to CS | Enabled Disabled | Disabled | Reporting | 52 |
| Q504 | Trouble reports to CS | Enabled Disabled | Enabled | Reporting | 53 |
| Q505 | Trouble restore reports to CS | Enabled Disabled | Enabled | Reporting | 53 |
| Q506 | Manual bypass reports to CS | Enabled Disabled | Disabled | Reporting | 53 |
| Q507 | Bypass restore reports to CS | Enabled Disabled | Disabled | Reporting | 53 |
| Q508 | Force bypass reports | Enabled Disabled | Disabled | Reporting | 53 |
| Q509 | AC loss reports to CS | Enabled Disabled | Enabled | Reporting | 53 |
| Q510 | AC restore reports to CS | Enabled Disabled | Enabled | Reporting | 53 |
| Q511 | System low battery reports to CS | Enabled Disabled | Enabled | Reporting | 54 |
| Q512 | System low battery restore reports to CS | Enabled Disabled | Enabled | Reporting | 54 |
| Q513 | RF low battery reports | Enabled Disabled | Enabled | Reporting | 54 |
| Q514 | Sensor low battery restore reports to CS | Enabled Disabled | Enabled | Reporting | 54 |
| Q515 | System disarmed reports to CS | Enabled Disabled | Disabled | Reporting | 54 |
| Q516 | System armed reports to CS | Enabled Disabled | Disabled | Reporting | 54 |
| Q517 | Alarm restore reports to CS | Enabled Disabled | Disabled | Reporting | 54 |
| Q518 | Smart test reports | Enabled Disabled | Disabled | Reporting | 55 |


Copyright © 2022 Nortek Security & Control LLC
65

---

## Page 66

**ANSI/SIA CP-01-2010 Features to Limit False Alarms**
For compliance with *ANSI/SIA CP-01-2010: Control Panel Standard - Features for False Alarm Reduction* , the installer can set a variety of
different options designed to limit occurrences of a False Alarm.


| ANSI/SIA CP-01-2010 | 2GIG System Feature | Installation & Programming Guide |
| --- | --- | --- |
| 4.2.2.1 Exit Time | Exit Delay | “Q201: Exit delay, in seconds (45-120)” “Q116: Allow quick exit” |
| 4.2.2.2 Progress Annunciation | Exit Delay Announcement | “Q201: Exit delay, in seconds (45-120)” |
| 4.2.2.3 Exit Time Restart | Exit Delay Restart | “Q115: Exit delay restart” |
| 4.2.2.4 Exit Error | Exit Error | See the User Guide for the 2GIG EDGE Panel |
| 4.2.2.5 Unvacated Premises | Auto Stay | “Q114: Auto stay” |
| 4.2.3.1 Entry Delay | Entry Delay | “Q202: Entry delay 1, in seconds (30-240)” “Q203: Entry delay 2, in seconds (30-240)” |
| 4.2.3.2 Progress Annunciation | Entry Delay Announcement | “Q101: Enter installer code (4 or 6 digits)” |
| 4.2.3.3 Disarm | Disarming Features | See the User Guide for the 2GIG EDGE Panel |
| 4.2.4.1 Control Buttons | Keyfob/Remote Arming Mode on System Not Ready. | “Q121: Keyfob/remote arming mode on system not ready” |
| 4.2.4.2 Manual Alarms | Emergency Alarm Features | See the User Guide for the 2GIG EDGE Panel |
| 4.2.4.3 System Acknowledgment | Alert Keyfob Disarming After Alarm Keyfob Arm/Disarm Confirmation | “Q119: Alert on disarm with keyfob after alarm” “Q120: Keyfob arm/disarm confirmation” |
| 4.2.4.4 Remote Arming | Key Fob Arming | “Q119: Alert on disarm with keyfob after alarm” |
| 4.3.4.5 Remote Disarming | Key Fob Arming | “Q120: Keyfob arm/disarm confirmation” |
| 4.2.5.1 Abort Window | Abort Window Dialer Delay | “Q205: Alarm abort window transmission delay” |
| 4.2.5.1.1 Disarm | Abort Window Dialer Delay | “Q502: Periodic test, in days (0-255)” |
| 4.2.5.1.2 Abort | Abort Window Dialer Delay | “Q502: Periodic test, in days (0-255)” |
| 4.2.5.2 Alarm Transmission | Abort Window Dialer Delay | “Q205: Alarm abort window transmission delay” |
| 4.2.5.3 Disarm | Disarm | See the User Guide for the 2GIG EDGE Panel |
| 4.2.5.4 Cancel Window | Alarm Cancel Time, Alarm Cancel Display | “Q204: Alarm cancel time, in minutes (5-255)” |
| 4.2.6.1 Use of Duress Feature | User Duress Report | “Covert Distress Signal” |
| 4.2.6.2 Duress Code | Duress Code | “User Duress Pin” |
| 4.2.7 Initiation of Manual Alarms | Panic, Fire, or Emergency Alarm | See the User Guide for the 2GIG EDGE Panel |
| 4.3. Cross Zoning | Cross Sensor Zones, Cross Sensor Timeout | “Q123: Cross sensor zones 99-100” “Q209: Cross sensor timeout, in seconds (10-120)” |
| 4.3.2 Swinger Shutdown | Swinger Shutdown Count (1-6) | “Q208: Swinger shutdown count (1-6)” “Q517: Alarm restore reports to CS” |
| 4.3.3 Fire Alarms | Fire & Carbon Monoxide Protection | “Sensor Type — 24-Hour Fire” “Sensor Type — 24-Hour Fire Verification” |
| 4.6.3 System Test | Console Test Sensors Test | “Testing the System” |


*Installation Guide for the 2GIG EDGE Security Panel*
66

---

## Page 67

**LIMITED WARRANTY**

This product is warranted against defects in material and workmanship for three (3) years. This warranty extends only to wholesale customers
who buy directly from Nortek Security & Control LLC or through Nortek Security & Control’s normal distribution channels. Nortek Security &
Control LLC does not warrant this product to consumers. Consumers should inquire from their selling dealer as to the nature of the dealer’s
warranty, if any.

There are no obligations or liabilities on the part of Nortek Security & Control LLC for consequential damages arising out of or in connection with
use or performance of this product or other indirect damages with respect to loss of property, revenue, or profit, or cost of removal, installation,
or re-installation. All implied warranties for functionality are valid only until the warranty expires. This Nortek Security & Control LLC Warranty is in
lieu of all other warranties, expressed or implied.

All products returned for warranty service require a Return Authorization Number (RA#). Contact Returns at 1-855-546-3351 for an RA# and other
important details.

**Waste Electrical and Electronic Equipment (WEEE) Statement**

**This symbol on a product or on its packaging indicates that this product is not to be thrown away with**
**everyday waste.**

Instead, it is your responsibility to dispose of electrical and electronics equipment by handing it over to a designated
collection point for the recycling of waste electrical and electronic equipment (W.E.E.E.). The separate collection
and recycling of your waste electrical and electronic equipment at the time of disposal will help to conserve natural
resources and ensure that it is recycled in a manner that protects human health and the environment. For more
information about where you can drop off your waste equipment for recycling, please contact your local city office, or
your household waste disposal service, or the shop where you purchased the product.

**WARNINGS**

**Limitations of Alarm Products**
This product should be tested periodically to make sure it is working properly. The product, if used properly, may reduce the risk of burglary,
robbery, and other adverse events that have the potential to result in injury or loss of life; however, Nortek Security & Control is not an insurer. This
product is neither insurance nor a guarantee that such an event will be prevented, and users should protect themselves with proper insurance.
Nortek Security & Control makes no representation that this product cannot be compromised or circumvented, that it will provide an adequate
warning, or that it will prevent any personal injuries, property damage, or other losses. Like any alarm product, it may be bypassed, it is subject
to compromise, and it may fail to warn for a variety of reasons, including, but not limited to: improper installation or positioning; improper
maintenance; tampering; dead or improperly installed batteries; sensing limitations; component failures; receivers; intrusions may be outside of a
product’s designated range and certain environmental conditions may impact performance, and audible alarm signals may be outside of hearing
range, muted by doors, walls, and floors, unheard by deep sleepers or the hearing-impaired, or overwhelmed by other sounds.

**Risk of Noise Induced Hearing Loss**
The Alarm is equipped with a warning siren. Exposure to high sound levels or prolonged exposure to the warning siren can result in Noise Induced
Hearing Loss (NIHL)

Copyright © 2022 Nortek Security & Control LLC
67

![Image 1 on page 67](images/2GIG_Edge_Installation_Guide_p67_img1.png)


---

## Page 68

**A** **L A R M  D** **E A** **L E R  I N F O R M** **A T** **I O N**
**Company Name:**
**Your Account Number:**
**Installation Date:**

www.2gig.com

©2022 Nortek Security & Control LLC. All rights reserved. 2GIG is a registered trademark of Nortek Security & Control LLC.
10025596 Rev-D