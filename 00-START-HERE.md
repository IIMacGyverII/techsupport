# MaxOutTech Tech Support Knowledge Base

**Company:** MaxOut™ Technology | St. Michael, MN | maxouttech.com  
**Purpose:** AI tech support knowledge base for MaxOutTech wireless security sensors  
**Last Updated:** May 2026

---

## How to Use This Knowledge Base

Ask questions like:
- *"How do I enroll a RF-CMDWS-345-NN on a Honeywell VISTA-20P?"*
- *"What panels are compatible with MaxOut 319.5 MHz sensors?"*
- *"Show me the installation steps for the RF-ARPIR-319-NN motion detector."*
- *"What does RF-CMDWS-345-NN replace?"*
- *"How do I program a Simon XTi-5 to learn a new door sensor?"*

---

## Quick Navigation

### Compatibility & Company Info
- [Frequency Compatibility & Panel Guide](./frequency-compatibility-and-panel-guide.md) — **START HERE for panel compatibility questions**
- [Product Line Card](./product-line-card.md) — Full product listing with part numbers

### Panel Programming Manuals (by frequency)
**319.5 MHz — Interlogix / Qolsys**
- `319_Qolsys-IQ-Panel-2_Installation-Manual_v2.5.md`
- `319_Qolsys-IQ-Panel-4_Installation-Manual_v4.0.md`
- `319_Qolsys-IQ-Panel-4_User-Guide_v4.1.md`
- `319_Simon-XT_Installation-Manual.md`
- `319_Simon-XTi_Installation-Guide_Rev-B.md`
- `319_Simon-XTi-5_Installation-Guide.md`
- `319_Concord-4_Installation-Manual.md`
- `319_Concord-4_User-Manual.md`
- `319_GE-NetworX-NX8_Installation-Manual.md`
- `319_UltraSync-ZeroWire_Installation-Manual.md`

**345 MHz — Honeywell / 2GIG**
- `345_VISTA-20P_Installation-Instructions.md`
- `345_VISTA-15P-20P_Programming-Guide.md`
- `345_LYNX-L7000-L5200_Installation-Setup-Guide.md`
- `345_LYNX-L7000_User-Guide.md`
- `345_ProA7-ProA7Plus_Installation-Manual.md`
- `345_2GIG-GC2e_Installation-Programming-Guide.md`
- `345_2GIG-Edge_Installation-Guide.md`

**433 MHz — DSC**
- `433_DSC-PowerSeries-PC1616_Installation-Manual_v4.5.md`
- `433_DSC-PowerSeries-PC1616-1832-1864_Programming-Guide.md`
- `433_DSC-PowerSeries-Neo-HS2016-HS2128_Installation-Manual.md`

### MaxOut Sensor Documents
- **Data Sheets (specs & compatibility):** all files matching `*_PDS.md`
- **Installation Manuals:** all files matching `*_Installation-Manual*.md`

---

## Frequency → Panel Brand Quick Reference

| Sensor Suffix | Frequency | Compatible Panel Brands |
|---|---|---|
| `-319-NN` | 319.5 MHz | UTC, Interlogix, GE Security, ITI, Qolsys |
| `-345-NN` | 345 MHz | Honeywell/Resideo, 2GIG |
| `-433-D-NN` | 433 MHz | DSC (PowerSeries, PowerSeries Neo) |

---

## Sensor Quick Reference

### Perimeter Sensors
| Part Number | Product | Frequencies |
|---|---|---|
| RF-CMDWS-319/345/433-NN | Mini Door/Window Sensor | 319.5, 345, 433 MHz |
| RF-CMDWSX-319/345-NN | Extended Door/Window Sensor | 319.5, 345 MHz |
| RF-RDWS-319/345-NN | Recessed Door/Window Sensor | 319.5, 345 MHz |
| RF-SHK-319/345-NN | Total Window/Shock Sensor | 319.5, 345 MHz |
| RF-CMDWS-OD-319/345-NN | Extreme Outdoor Sensor | 319.5, 345 MHz |

### Detection Sensors
| Part Number | Product | Frequencies |
|---|---|---|
| RF-ARPIR-319/345-NN | Wall PIR Motion Detector | 319.5, 345 MHz |
| RF-PIR-433-D-NN | Wall PIR Motion Detector (DSC) | 433 MHz |
| RF-CPIR-319-NN | Ceiling PIR Motion Detector (360°) | 319.5 MHz |
| RF-ARGB-319-NN | Glass Break Detector | 319.5 MHz |

### Life Safety & Environmental
| Part Number | Product | Frequencies |
|---|---|---|
| RF-ROR-135S-319/345-NN | Rate-of-Rise Heat Detector | 319.5, 345 MHz |
| RF-APCMB-345-NN | Combo Smoke/Heat/CO Detector | 345 MHz |
| RF-WATER-319/345-NN | Water/Flood Sensor | 319.5, 345 MHz |

### Control & Accessories
| Part Number | Product | Frequencies |
|---|---|---|
| RF-KEYFOB-319-NN | Keyfob System Control (arm/disarm/panic) | 319.5 MHz |
| RF-FOB-PANIC-319/345-NN | Keyfob Panic Button | 319.5, 345 MHz |
| RF-PANIC-ONE-BUTTON-319-NN | Long-Range Panic Button | 319.5 MHz |
| ACC-TS-HS-KIT | High Security Panel Tamper Switch | Hardwired |

---

## Sensor Enrollment Summary (by Panel Type)

### Interlogix / GE / Qolsys (319.5 MHz)
Enter installer programming → navigate to Sensors/Wireless Zones → activate Learn Mode → trip the MaxOut sensor (open reed switch, activate tamper, or pull battery tab) → panel auto-learns the serial number → assign zone type → exit programming.

**Specific panel series:** Qolsys IQ Panel 2/4, Simon XT/XTi/XTi-5, Concord 4, NetworX NX-4/6/8, UltraSync/ZeroWire.

### Honeywell / Resideo VISTA (345 MHz)
At keypad: `*56` → select zone number → set Zone Type (e.g., 01 = Entry/Exit) → set Input Type to `3` (RF) → trip the MaxOut sensor to transmit serial number → confirm → exit with `*99`.  
*(Requires 5800-series wireless receiver: 5881ENH, 5883H, or similar)*

### 2GIG / LYNX Touch / ProSeries (345 MHz)
Enter installer toolbox → Wireless Zones (or Sensor Programming) → select zone → Learn Mode → trip the MaxOut sensor → confirm serial → save and exit.

### DSC PowerSeries / PowerSeries Neo (433 MHz)
`*8` + installer code → Section `[804]` (PC1616/1832/1864) or wireless enrollment section (Neo) → select zone → activate learn → trip MaxOut sensor → assign zone definition → exit with `#`.  
*(Requires WLS922 receiver for PowerSeries; HSM2HOST9 for PowerSeries Neo)*

---

## Legacy Replacement Cross-Reference

| MaxOut Sensor | Replaces (Legacy Part) |
|---|---|
| RF-CMDWS-319-NN | Interlogix 60-362N-10-319.5 |
| RF-CMDWS-345-NN | Honeywell 5818MNL |
| RF-RDWS-319-NN | UTC/GE/Sentrol R1125T-N |
| RF-RDWS-345-NN | Honeywell 5818MNL |
| RF-SHK-319-NN | UTC/GE/Sentrol 5414W |
| RF-CMDWS-OD-345-NN | Honeywell 5816OD |
| RF-ARGB-319-NN | UTC/GE/Sentrol 5600W |

---

## Panel Manuals Index

### 319.5 MHz — Interlogix / Qolsys
| File | Purpose |
|---|---|
| `319_Qolsys-IQ-Panel-2_Installation-Manual_v2.5.md` | Sensor auto-learn, QR scan enrollment |
| `319_Qolsys-IQ-Panel-4_Installation-Manual_v4.0.md` | IQ Panel 4 install & sensor enrollment |
| `319_Qolsys-IQ-Panel-4_User-Guide_v4.1.md` | IQ Panel 4 user reference |
| `319_Simon-XT_Installation-Manual.md` | Simon XT sensor learn mode |
| `319_Simon-XTi_Installation-Guide_Rev-B.md` | Simon XTi sensor programming |
| `319_Simon-XTi-5_Installation-Guide.md` | Simon XTi-5/XTi-5i sensor programming |
| `319_Concord-4_Installation-Manual.md` | Concord 4 wireless sensor programming |
| `319_Concord-4_User-Manual.md` | Concord 4 user reference |
| `319_GE-NetworX-NX8_Installation-Manual.md` | NetworX NX-8 wireless zone programming |
| `319_UltraSync-ZeroWire_Installation-Manual.md` | UltraSync/ZeroWire installation |

### 345 MHz — Honeywell / 2GIG
| File | Purpose |
|---|---|
| `345_VISTA-20P_Installation-Instructions.md` | VISTA-20P wiring and setup |
| `345_VISTA-15P-20P_Programming-Guide.md` | Full programming guide incl. *56 wireless enrollment |
| `345_LYNX-L7000-L5200_Installation-Setup-Guide.md` | L7000/L5200 wireless sensor enrollment |
| `345_LYNX-L7000_User-Guide.md` | L7000 user reference |
| `345_ProA7-ProA7Plus_Installation-Manual.md` | ProSeries wireless setup |
| `345_2GIG-GC2e_Installation-Programming-Guide.md` | GC2/GC2e wireless zone programming |
| `345_2GIG-Edge_Installation-Guide.md` | 2GIG Edge wireless zones |

### 433 MHz — DSC
| File | Purpose |
|---|---|
| `433_DSC-PowerSeries-PC1616_Installation-Manual_v4.5.md` | PC1616 installation & wireless receiver |
| `433_DSC-PowerSeries-PC1616-1832-1864_Programming-Guide.md` | Full programming, wireless enrollment |
| `433_DSC-PowerSeries-Neo-HS2016-HS2128_Installation-Manual.md` | Neo installation, HSM2HOST9 receiver |

---

*MaxOut™ Technology — maxouttech.com | sales@maxouttech.com | 763-497-1059*
