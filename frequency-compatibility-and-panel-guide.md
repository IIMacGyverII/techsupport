# MaxOut™ Technology — Compatible Security Control Panels

**Source:** MaxOutTech.com product pages, product data sheets, installation manuals in this folder, and expanded research (Grok, May 2026).  
**Compiled:** May 2026  
**Panel manuals:** Included in this KB folder as `.md` files — see Section 6 for file listing

---

## About MaxOut™ Technology

MaxOut™ Technology (maxouttech.com) is a wireless security and life-safety sensor manufacturer based in St. Michael, MN. Their sensors operate on three RF frequencies — **319.5 MHz**, **345 MHz**, and **433 MHz** — each of which is associated with a specific ecosystem of security control panels.

---

## How RF Frequency Determines Panel Compatibility

MaxOut sensors are frequency-matched to control panels. The control panel's built-in wireless receiver must match the sensor's transmission frequency. Sensors from different frequency families are **not interchangeable** unless the panel has a multi-frequency receiver or a separate plug-in receiver.

---

## Compatible Control Panels by Frequency

### 319.5 MHz — UTC / Interlogix / GE / ITI / Qolsys Ecosystem

MaxOut 319.5 MHz sensors (model suffix `-319-NN`) work with all control panels that use the standard 319.5 MHz Interlogix "Learn Mode" protocol. These include products sold under the following brand names (many are the same underlying hardware sold under different names over the years):

| Brand | Notes |
|---|---|
| **UTC Fire & Security** | Parent company of Interlogix; panels sold under UTC label |
| **Interlogix** | Major brand for residential/commercial panels using this frequency |
| **GE Security** | GE-branded panels (GE exited security hardware; panels continued under Interlogix) |
| **ITI (Interactive Technologies Inc.)** | Early brand; panels fully compatible |
| **Qolsys** | Modern touchscreen panels (IQ Panel series); use 319.5 MHz as native frequency |
| **Caddx / GE Caddx** | Part of the GE/Interlogix family |

**Specific panel models and series confirmed compatible:**

| Panel | Model(s) | Notes |
|---|---|---|
| **Qolsys IQ Panel 2 / 2+** | IQ Panel 2, IQ Panel 2+ | Native 319.5 MHz; sensor learn via auto-enroll/QR scan |
| **Qolsys IQ Panel 4 / 4+** | IQ Panel 4, IQ Panel 4+ | Native 319.5 MHz; also supports via IQ RF cards |
| **Interlogix Simon XT** | Simon XT | Learn sensors via programming menu |
| **Interlogix Simon XTi** | Simon XTi | Learn sensors via programming menu |
| **Interlogix Simon XTi-5 / XTi-5i** | Simon XTi-5, Simon XTi-5i | Learn sensors via programming menu |
| **Interlogix Concord 4** | Concord 4, Concord Express | Wireless sensor programming in installer menu |
| **GE / Caddx NetworX** | NX-4, NX-6, NX-8, NX-8E | Programming locations for wireless zones |
| **Interlogix UltraSync / ZeroWire** | ZW-6400 and variants | Simon platform variant |
| **ELK M1 / M1EZ** | M1, M1EZ8 | Requires ELK-M1XRF319 receiver module (not native — add-on) |

> **Note:** Interlogix went out of business in 2019. However, the installed base of Interlogix/GE/UTC panels remains very large, and the 319.5 MHz protocol is still actively supported by Qolsys, making MaxOut 319.5 MHz sensors highly relevant for both legacy replacement and new Qolsys installs.

**Sensor enrollment method (319.5 MHz panels):**  
Enter installer programming → navigate to wireless sensor/zone menu → activate the MaxOut sensor (open/close reed switch, press tamper, or pull battery tab) → panel auto-learns the serial number → assign zone type and exit programming.

---

### 345 MHz — Honeywell / Resideo / 2GIG Ecosystem

MaxOut 345 MHz sensors (model suffix `-345-NN`) work with all control panels that use the standard Honeywell 345 MHz protocol. This is the most widely deployed residential wireless security frequency in North America.

| Brand | Notes |
|---|---|
| **Honeywell Home / Resideo** | Honeywell's security division was rebranded Resideo in 2018; all panels still use 345 MHz |
| **2GIG Technologies** | Independent brand fully compatible with 345 MHz protocol; popular with dealers |

**Known compatible panel families (Honeywell/Resideo):**
- **VISTA Series** — e.g., VISTA-15P, VISTA-20P, VISTA-21iP (with wireless receiver add-on such as the 5800 series receivers: 5881ENH, 5883H, etc.)
- **LYNX Plus / LYNX Touch Series** — e.g., L3000, L5100, L7000
- **ProSeries** — e.g., PROA7, PROA7PLUS (next-generation Resideo panels)
- **Ademco / First Alert** — older Honeywell OEM platforms using 345 MHz

**Known compatible panel families (2GIG):**
- **2GIG GoControl** — GC2, GC2e
- **2GIG GC3 / GC3e**
- **2GIG Edge**

> **Note:** The 345 MHz MaxOut sensors are direct functional replacements for Honeywell 5800-series sensors. For example, the RF-CMDWS-345-NN is listed as a replacement for the Honeywell 5818MNL, and the RF-CMDWS-OD-345-NN replaces the Honeywell 5816OD.

**Sensor enrollment method — Honeywell VISTA panels:**  
Enter `*56` Zone Programming Menu at the keypad → select the zone number → set **Zone Type** (e.g., `01` = Entry/Exit, `03` = Perimeter) → set **Input Type** to `3` (RF Sensor) → trip the MaxOut sensor (open/close reed or activate tamper) to auto-learn the 7-digit serial number → confirm serial → exit with `*99`. Full steps in `Honeywell_VISTA-15P_20P_Programming_Guide.pdf`.

**Sensor enrollment method — 2GIG / LYNX Touch / ProSeries:**  
Enter installer toolbox → Wireless Zones (or Sensor Programming) → select zone → set sensor type → activate learn mode → trip the MaxOut sensor → confirm serial → save and exit.

---

### 433 MHz — DSC Ecosystem

MaxOut 433 MHz sensors (model suffix `-433-D-NN`) work with DSC (Digital Security Controls) panels that use the 433 MHz PowerSeries wireless protocol.

| Brand | Notes |
|---|---|
| **DSC (Digital Security Controls)** | Now owned by Johnson Controls / Tyco |

**Known compatible DSC panel families:**
- **PowerSeries** — e.g., PC1616, PC1832, PC1864 (with WLS922 or compatible wireless receiver)
- **PowerSeries Neo** — e.g., HS2016, HS2032, HS2064, HS2128 (with HSM2HOST9 receiver)
- **Alexor** — All-wireless DSC platform

> **Note:** The 433 MHz MaxOut product line is smaller — currently the Mini Door/Window Sensor (RF-CMDWS-433-D-NN) and the Wall Mounted PIR (RF-PIR-433-D-NN).

**Sensor enrollment method — DSC PowerSeries:**  
Enter installer programming (`*8` + installer code) → Section `[804]` (PC1616/1832/1864) or wireless enrollment menu (Neo) → select zone → activate sensor learn → trip the MaxOut sensor to transmit its ID → assign zone definition → exit programming with `#`. Full steps in `DSC_PowerSeries_PC1616_PC1832_PC1864_Programming_Guide.pdf` and `DSC_PowerSeries_Neo_HS2016_HS2032_HS2064_HS2128_Installation_Manual.pdf`.

---

## Product-to-Panel Compatibility Summary

| MaxOut Product | Part Number(s) | 319.5 MHz Panels | 345 MHz Panels | 433 MHz Panels |
|---|---|---|---|---|
| Mini Door/Window Sensor | RF-CMDWS-319/345/433 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | DSC |
| Mini Door/Window Sensor Extended | RF-CMDWSX-319/345 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Recessed Door/Window Sensor | RF-RDWS-319/345 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Total Window / Shock Sensor | RF-SHK-319/345 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Extreme Outdoor Sensor | RF-CMDWS-OD-319/345 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Glass Break Detector | RF-ARGB-319-NN | UTC, Interlogix, GE, ITI, Qolsys | — | — |
| Wall Mounted PIR Motion | RF-ARPIR-319/345, RF-PIR-433 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | DSC |
| Ceiling Mounted PIR (CPIR) | RF-CPIR-319-NN | UTC, Interlogix, GE, ITI, Qolsys | — | — |
| Rate-of-Rise Heat Detector | RF-ROR-135S-319/345 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Combo Smoke/Heat/CO Detector | RF-APCMB-345-NN | — | Honeywell, 2GIG | — |
| Water Sensor | RF-WATER-319/345 | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Keyfob System Control | RF-KEYFOB-319-NN | UTC, Interlogix, GE, ITI, Qolsys | — | — |
| Keyfob Panic Button | RF-FOB-PANIC-NN | UTC, Interlogix, GE, ITI, Qolsys | Honeywell, 2GIG | — |
| Long-Range Panic Button | RF-PANIC-319-NN | UTC, Interlogix, GE, ITI, Qolsys | — | — |
| Panel Tamper Switch | ACC-TS-HS-KIT | (Hardwired — not RF) | — | — |

---

## Legacy Products Replaced by MaxOut Sensors

The line card in this folder lists direct replacement part numbers, which is useful for identifying additional compatible panels (anything that accepted the original sensor also accepts the MaxOut replacement):

| MaxOut Sensor | Replaces |
|---|---|
| RF-CMDWS-319-NN | Interlogix 60-362N-10-319.5 |
| RF-CMDWS-345-NN | Honeywell 5818MNL |
| RF-RDWS-319-NN | UTC/GE/Sentrol R1125T-N |
| RF-RDWS-345-NN | Honeywell 5818MNL |
| RF-SHK-319-NN | UTC/GE/Sentrol 5414W |
| RF-CMDWS-OD-345-NN | Honeywell 5816OD |
| RF-ARGB-319-NN | UTC/GE/Sentrol 5600W |

---

## Notes on Finding Additional Compatible Panels

- Any panel that accepts **319.5 MHz Interlogix/GE/UTC format** sensors will work with MaxOut 319.5 MHz products. This includes many OEM-branded panels made by Interlogix.
- Any panel that accepts **Honeywell 5800-series** format sensors will work with MaxOut 345 MHz products.
- Any panel with **DSC PowerSeries 433 MHz wireless** support will work with MaxOut 433 MHz products.
- MaxOut does **not** currently produce sensors for **Napco**, **Bosch**, **Elk Products**, **DMP**, or **Alarm.com native** panels (though Alarm.com works through compatible panels listed above).

---

## Instructions for Grok to Research and Expand This List

If you (Grok) are reading this document and need to find additional compatible panels, here are the research steps that were used to compile this document and how to expand it further:

### Step 1 — Start at MaxOutTech.com
- Visit `https://maxouttech.com/products` — each product page lists compatible brands explicitly under "Compatibility and Part Numbers."
- Visit `https://maxouttech.com/documentation` — download/view installation manuals for specific panel programming steps.
- Visit `https://maxouttech.com/line-card` — the line card lists "Replaces:" entries showing which legacy sensors MaxOut products substitute for.

### Step 2 — Cross-Reference by Frequency Protocol
Use the frequency as the key to find every compatible panel:

- **319.5 MHz:** Search for "319.5 MHz wireless security panels" or "Interlogix learn mode panels list." Any panel that accepts the Interlogix/GE 319.5 MHz format will be compatible. Key search terms: `"319.5 MHz" "learn mode" control panel`, `Interlogix compatible panels list`, `GE Security wireless panels 319`.
- **345 MHz:** Search for "Honeywell 5800 series compatible panels" or "345 MHz wireless security panels." Any panel with a Honeywell 5800-series compatible receiver is compatible. Key search terms: `"345 MHz" Honeywell compatible panels`, `5800 series receiver panels`, `Resideo compatible control panels`.
- **433 MHz:** Search for "DSC PowerSeries 433 MHz compatible wireless sensors." Key search terms: `DSC "433 MHz" wireless sensors compatible panels`, `PowerSeries Neo wireless receiver`.

### Step 3 — Check OEM / White-Label Relationships
Many panels are the same hardware sold under different brand names. Research:
- Interlogix OEM partners (Caddx, Sentrol, GE branded panels, UTC Fire & Security, Aritech in Europe)
- Honeywell OEM partners (First Alert, Ademco)
- 2GIG and its relationship with Nortek Security & Control

### Step 4 — Installer and Dealer Forums
Search these resources for real-world compatibility reports:
- `alarm.com dealer forum 319.5 MHz compatible panels`
- `alarmforum.net MaxOut sensors`
- `diy.alarm.com compatible sensors` (Alarm.com panels often accept 319.5 or 345 MHz sensors)
- Reddit: r/homesecurity, r/DIYsecurity — search for "MaxOut" or the specific part numbers

### Step 5 — Compare Against Legacy Sensor Compatibility Lists
Because MaxOut sensors replace legacy sensors (see table above), find compatibility lists for those legacy sensors:
- Honeywell 5818MNL compatibility list → all panels on that list accept RF-CMDWS-345-NN and RF-RDWS-345-NN
- Interlogix 60-362N compatibility list → all panels on that list accept RF-CMDWS-319-NN
- GE/Sentrol 5414W compatibility list → all panels accept RF-SHK-319-NN

### Specific Search Queries to Try
```
MaxOutTech compatible panels site:maxouttech.com
"RF-CMDWS-319" OR "RF-CMDWSX" compatible control panels
"319.5 MHz" Interlogix learn mode panel list
Honeywell "5800 series" compatible panels full list
DSC PowerSeries 433MHz wireless compatible sensors list
Qolsys IQ Panel compatible sensors 319.5
2GIG GC2 compatible wireless sensors 345MHz
Honeywell VISTA wireless receiver compatible sensors
```

---

---

## Section 6 — Panel Manual File Index

All panel manual files are included in this KB folder as `.md` files.

### 319.5 MHz — Interlogix / GE / Qolsys

| File | Panel / Purpose |
|---|---|
| `319_Qolsys-IQ-Panel-2_Installation-Manual_v2.5.md` | Qolsys IQ Panel 2 — installation, sensor auto-learn/QR scan |
| `319_Qolsys-IQ-Panel-4_Installation-Manual_v4.0.md` | Qolsys IQ Panel 4 — installation, sensor enrollment |
| `319_Qolsys-IQ-Panel-4_User-Guide_v4.1.md` | Qolsys IQ Panel 4 — user/sensor setup |
| `319_Simon-XT_Installation-Manual.md` | Simon XT — learn mode sensor programming |
| `319_Simon-XTi_Installation-Guide_Rev-B.md` | Simon XTi — sensor programming |
| `319_Simon-XTi-5_Installation-Guide.md` | Simon XTi-5 / XTi-5i — sensor programming |
| `319_Concord-4_Installation-Manual.md` | Concord 4 — wireless sensor programming |
| `319_Concord-4_User-Manual.md` | Concord 4 — user reference |
| `319_GE-NetworX-NX8_Installation-Manual.md` | NetworX NX-8 — wireless zone programming locations |
| `319_UltraSync-ZeroWire_Installation-Manual.md` | UltraSync / ZeroWire ZW-6400 — installation |

### 345 MHz — Honeywell / Resideo / 2GIG

| File | Panel / Purpose |
|---|---|
| `345_VISTA-20P_Installation-Instructions.md` | VISTA-20P — installation wiring and setup |
| `345_VISTA-15P-20P_Programming-Guide.md` | VISTA-15P/20P — full programming guide, incl. `*56` wireless zone enrollment |
| `345_LYNX-L7000-L5200_Installation-Setup-Guide.md` | LYNX Touch L7000/L5200 — wireless sensor enrollment |
| `345_LYNX-L7000_User-Guide.md` | LYNX Touch L7000 — user reference |
| `345_ProA7-ProA7Plus_Installation-Manual.md` | ProSeries PROA7/PROA7PLUS — installation and wireless setup |
| `345_2GIG-GC2e_Installation-Programming-Guide.md` | 2GIG GC2/GC2e — installation and wireless zone programming |
| `345_2GIG-Edge_Installation-Guide.md` | 2GIG Edge — wireless zone setup |

### 433 MHz — DSC

| File | Panel / Purpose |
|---|---|
| `433_DSC-PowerSeries-PC1616_Installation-Manual_v4.5.md` | PowerSeries PC1616 — installation and wireless receiver setup |
| `433_DSC-PowerSeries-PC1616-1832-1864_Programming-Guide.md` | PowerSeries PC1616/1832/1864 — full programming guide, wireless enrollment |
| `433_DSC-PowerSeries-Neo-HS2016-HS2128_Installation-Manual.md` | PowerSeries Neo HS2016–HS2128 — installation, HSM2HOST9 receiver, wireless enrollment |

---

*Document created from MaxOutTech.com product pages, product data sheets/installation manuals in this workspace folder, and expanded research (Grok, May 2026). For the most current information, always verify at [maxouttech.com](https://maxouttech.com).*
