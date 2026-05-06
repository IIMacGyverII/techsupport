# MaxOut™ Technology — Installer FAQ

**Audience:** Security alarm installers and technicians  
**Products:** MaxOut™ wireless RF sensors and detectors  
**Contact:** maxouttech.com | sales@maxouttech.com | 763-497-1059

---

## General / Compatibility

**Q: How do I know which MaxOut sensor to order for a given panel?**  
A: Match the sensor's frequency suffix to the panel brand:
- `-319-NN` → UTC, Interlogix, GE, ITI, Qolsys (IQ Panel 2/4)
- `-345-NN` → Honeywell/Resideo (VISTA, LYNX, ProSeries), 2GIG (GC2e, GC3, Edge)
- `-433-D-NN` → DSC PowerSeries (PC1616/1832/1864) and PowerSeries Neo

**Q: Can I use a 319 MHz sensor on a Honeywell panel?**  
A: No. The sensor's frequency must match the panel's wireless receiver. A 319.5 MHz sensor will not be learned by a 345 MHz Honeywell receiver, and vice versa.

**Q: Are MaxOut sensors direct drop-in replacements for legacy sensors?**  
A: Yes — they are designed as functional replacements. Key substitutions:
| MaxOut Sensor | Replaces |
|---|---|
| RF-CMDWS-319-NN | Interlogix 60-362N-10-319.5 |
| RF-CMDWS-345-NN | Honeywell 5818MNL |
| RF-RDWS-319-NN | UTC/GE/Sentrol R1125T-N |
| RF-RDWS-345-NN | Honeywell 5818MNL |
| RF-SHK-319-NN | UTC/GE/Sentrol 5414W |
| RF-CMDWS-OD-345-NN | Honeywell 5816OD |
| RF-ARGB-319-NN | UTC/GE/Sentrol 5600W |

When replacing a legacy sensor, the panel zone programming can typically stay unchanged — just enroll the new MaxOut serial number in place of the old one.

**Q: Does MaxOut make sensors for Napco, Bosch, DMP, or Elk?**  
A: Not currently. MaxOut sensors are designed for the Interlogix/GE (319.5 MHz), Honeywell/2GIG (345 MHz), and DSC (433 MHz) ecosystems only.

**Q: Interlogix went out of business — does that mean 319 MHz sensors are obsolete?**  
A: No. The 319.5 MHz protocol is still fully active through Qolsys (IQ Panel 2 and IQ Panel 4). There is also a massive installed base of Interlogix/GE/UTC panels still in service. MaxOut 319.5 MHz sensors work on all of them.

**Q: Does the Qolsys IQ Panel 4 support MaxOut sensors?**  
A: Yes. The IQ Panel 4 uses 319.5 MHz as its native wireless frequency. Enroll MaxOut `-319-NN` sensors the same way as any other 319.5 MHz sensor — via auto-learn or QR scan in the Installer settings.

---

## Enrollment / Programming

**Q: What is the general enrollment procedure for any MaxOut sensor?**  
A: All MaxOut sensors use the same basic "Learn Mode" enrollment process:
1. Enter installer programming on the panel.
2. Navigate to the wireless sensor/zone menu.
3. Select the zone number to assign.
4. When prompted to trip/activate the sensor, do one of the following (whichever applies):
   - Open and close the reed switch (move magnet away from sensor)
   - Press the tamper button
   - Pull the battery pull tab (first install)
5. The panel auto-learns the sensor's serial/ID number.
6. Assign the zone type (e.g., Entry/Exit, Perimeter, Motion).
7. Exit programming.

**Q: How do I enroll a MaxOut sensor on a Honeywell VISTA panel?**  
A: At the keypad:
1. Press `*56` to enter Zone Programming.
2. Navigate to the zone number.
3. Set **Zone Type** (e.g., `01` = Entry/Exit, `03` = Perimeter).
4. Set **Input Type** to `3` (RF Sensor).
5. Trip the MaxOut sensor — the panel auto-fills the 7-digit serial number.
6. Confirm and exit with `*99`.

A 5800-series wireless receiver must be installed (5881ENH, 5883H, or equivalent).  
Full steps: `345_VISTA-15P-20P_Programming-Guide.md`

**Q: How do I enroll a MaxOut sensor on a DSC PowerSeries panel?**  
A: Enter installer programming (`*8` + installer code) → Section `[804]` → select zone → activate learn mode → trip the sensor to transmit its ID → assign zone definition → exit with `#`. Requires WLS922 or compatible wireless receiver.  
Full steps: `433_DSC-PowerSeries-PC1616-1832-1864_Programming-Guide.md`

**Q: How do I enroll on a DSC PowerSeries Neo?**  
A: Similar process but through the wireless enrollment section (not Section 804). Requires HSM2HOST9 wireless receiver module.  
Full steps: `433_DSC-PowerSeries-Neo-HS2016-HS2128_Installation-Manual.md`

**Q: The panel won't learn the sensor. What should I check?**  
A: Common causes:
1. **Wrong frequency** — confirm the sensor suffix matches the panel brand.
2. **Out of range** — test the sensor from the mounting location before permanent install. Move closer to panel if it fails.
3. **Metal interference** — mounting on or near metal affects RF range. Test first.
4. **Dead battery** — pull tabs should be removed; replace battery if low.
5. **Panel not in learn mode** — confirm the panel is actively in the sensor enrollment screen before tripping the sensor.
6. **Wireless receiver not installed or enabled** — VISTA panels require a 5800-series receiver; DSC panels require WLS922 or HSM2HOST9.

---

## Mounting & Installation

**Q: Where should I mount the sensor vs. the magnet on a door?**  
A: Mount the sensor body on the **fixed frame** and the magnet on the **moving door or window**. For double doors, mount the sensor on the less-used door and the magnet on the other door.

**Q: What is the maximum gap between sensor and magnet?**  
- RF-CMDWS (Mini Door/Window): **3/8" maximum**
- RF-CMDWSX (Extended): **3/8" maximum**
- RF-RDWS (Recessed): follow recessed bore alignment
- RF-CMDWS-OD (Outdoor): **3/4" for wood, 1/2" for metal** mounting surfaces

**Q: Does mounting on metal affect performance?**  
A: It can reduce range and affect the magnet gap. MaxOut sensors use a patented raised antenna design (isolated 1/8" above the circuit board) to minimize this, but always **test signal strength from the intended mounting location before permanently installing**.

**Q: How high should door/window sensors be mounted?**  
A: Mount at least **5 inches above the floor** to avoid physical damage. Standard practice is top of the door or window frame.

**Q: Can I mount MaxOut sensors outdoors?**  
A: Only the **RF-CMDWS-OD** (Extreme Sensor) is rated for outdoor use. It has a water-tight internal gasket and a rugged enclosure tested down to **–32°F (–35.6°C)**. Standard indoor sensors should not be used outdoors.

**Q: How do I mount the outdoor sensor (RF-CMDWS-OD)?**  
A: Use the included mounting screws, or use plastic zip-tie straps through the sensor housing for post or pipe mounting. Mount the sensor on the non-moving frame/post and the magnet on the moving gate or door.

**Q: Where should I mount a PIR motion detector (RF-ARPIR)?**  
A: Mount on a flat wall or in a corner at **7.5 feet (2.3 m)** height for standard coverage, or up to **10 feet (3 m)**. Face it away from windows, fireplaces, heating vents, and direct sunlight. Mount on an insulated exterior wall facing inward for best performance. Do not place on a shelf — mount permanently to a rigid surface.

**Q: Where should I mount the RF-ROR heat detector?**  
A: On the **ceiling**, at least **4 inches from any wall**. If wall-mounted, it must be within **6 inches of the ceiling**. Best locations: kitchens, garages — areas prone to smoke where a smoke detector would cause false alarms. Avoid placement near fireplaces, stoves, or heaters.

---

## PIR Motion Detectors

**Q: Does the RF-ARPIR have pet immunity?**  
A: Yes. The RF-ARPIR-319-NN and RF-ARPIR-345-NN are designed for **pet immunity up to 22 lbs.** It uses a special micro-element lens array that produces stronger optical signals for humans than for small pets. 

Important caveats:
- Pets must not be allowed to climb on furniture within the detection area.
- Short-haired pets even under 22 lbs. may produce enough infrared radiation to trigger the sensor.
- Always test with the specific pet present before completing the installation.
- Room temperature must be kept between 60°F and 120°F (16°C–49°C).

**Q: The PIR is triggering false alarms. What should I check?**  
A:
- Is it aimed at a window, air vent, heater, or fireplace? Reposition away from heat sources.
- Is there reflected sunlight hitting the sensor? Reposition or shade.
- Are pets climbing on furniture within the detection zone? Reposition or adjust height.
- Is it mounted on a vibrating or non-rigid surface? Move to a solid wall.
- Check sensitivity setting — the RF-ARPIR has a selectable sensitivity adjustment.

**Q: What is the coverage pattern of the RF-ARPIR?**  
A: The RF-ARPIR is a wall-mounted PIR with a wide-angle detection pattern. Coverage and range are specified per the installation manual; refer to `RF-ARPIR_Wall-PIR-Motion-Detector_PDS.md` for the coverage diagram. Corner mounting provides broader area protection.

---

## Shock Sensor (RF-SHK)

**Q: What does the RF-SHK shock sensor protect against?**  
A: It provides **dual protection**: (1) a built-in reed switch that detects door/window open/close, and (2) a piezo vibration detector that senses shock from an intruder attempting to break glass or force a door. The reed switch and shock zone transmit on **separate zone IDs**, so the panel sees them as two independent zones.

**Q: How do I adjust shock sensitivity?**  
A: There is an adjustable potentiometer (Phillips head screw) on the sensor. Turn it to increase or decrease sensitivity. You can also bottom out the adjustment to effectively **disable the shock function** while leaving the reed switch active. An LED lights on shock activation and goes out on restore, which is useful during sensitivity adjustment.

**Q: Is the shock sensor mounted on the glass or on the frame?**  
A: Mount it on the **door or window frame** — not glued to the glass. The piezo is sensitive enough to detect vibration transmitted through the frame. Frame mounting also allows the reed switch to function properly.

---

## Water Sensor (RF-WATER)

**Q: Where should the water sensor be placed?**  
A: On the floor or a low surface near: water heaters, washing machine hose connections, under sinks, near sump pump pits, or any area where water accumulation is a concern. The sensor detects water when it rises above the contact probes on the bottom.

**Q: How does the water sensor avoid false alarms?**  
A: It checks for water every **5 minutes** and requires **two consecutive positive detections** before transmitting an alarm. This prevents brief splashes or condensation from triggering a false alarm.

**Q: What battery does the water sensor use?**  
A: Two (2) CR2032 3V lithium coin-cell batteries. The patented high-tension battery holders protect against power loss and are designed to maximize battery life. The two-battery design delivers more than double the battery life of single-battery competitive sensors.

---

## Heat Detector (RF-ROR)

**Q: What are the temperature settings for the RF-ROR?**  
A: The RF-ROR-135S has a jumper-selectable fixed temperature threshold:
- **Low (jumper installed): 135°F (57°C)** — standard for most interior spaces
- **High (jumper removed or Hi position): 200°F (93°C)** — for higher-ambient areas like attics

In addition to the fixed threshold, it triggers on a **rate-of-rise of 12°F–15°F per minute** (6.7°–8.3°C/min) regardless of jumper setting.

**Q: Is the RF-ROR listed/approved?**  
A: Yes. It is **UL 521** listed (Heat Detectors for Fire and Protective Signaling Systems) and **UL 985** listed (Household Fire Warning Systems Units). Also **CAN/ULC-S530** (Canada) and CSFM Category 7270.

---

## Combo Smoke/Heat/CO Detector (RF-APCMB-345)

**Q: What does the RF-APCMB-345-NN detect?**  
A: Three threats in one device:
1. **Smoke** — photoelectric detection
2. **Heat** — thermistor, plus **41°F (5°C) freeze notification**
3. **Carbon Monoxide (CO)** — electrochemical detection

**Q: What panels is the APCMB compatible with?**  
A: **345 MHz only** — Honeywell/Resideo and 2GIG panels. There is no 319 MHz or 433 MHz version of this detector.

**Q: What is the alarm sound pattern?**  
A: Smoke/Heat alarm: **Temporal 3** pattern. CO alarm: **Temporal 4** pattern — the difference in tone pattern helps occupants distinguish smoke from CO.

**Q: Can the alarm be silenced?**  
A: Yes — push button Hush:
- Smoke/heat alarms: **7-minute silence**
- CO alarms: **5-minute silence**

**Q: How long does the detector last?**  
A: Rated for a **10-year operational life**. The unit sends an end-of-life notification signal to the panel when it needs replacement.

---

## Batteries

**Q: What batteries do MaxOut sensors use?**

| Sensor | Battery | Qty |
|---|---|---|
| RF-CMDWS (Mini Door/Window) | CR2032 3V lithium coin-cell (Varta or Panasonic) | 2 |
| RF-CMDWSX (Extended D/W) | CR2032 3V lithium coin-cell (Varta or Panasonic) | 2 |
| RF-CMDWS-OD (Outdoor) | CR123A 3V lithium (Varta or Panasonic) | 2 |
| RF-RDWS (Recessed D/W) | CR123A 3V lithium (Varta or Panasonic) | 1 |
| RF-SHK (Shock/D/W) | CR2032 3V lithium coin-cell | 2 |
| RF-ARPIR (Wall PIR) | CR123A 3V lithium | 1 |
| RF-CPIR (Ceiling PIR) | Refer to installation manual | — |
| RF-WATER (Water Sensor) | CR2032 3V lithium coin-cell | 2 |
| RF-ROR (Heat Detector) | CR123A 3V lithium | 1 |

**Q: How long do the batteries last?**  
A: Varies by sensor and usage. The RF-SHK shock sensor is rated up to **10 years** with the two-battery design. The RF-ROR heat detector's CR123A is also rated up to 10 years. MaxOut's patented antenna design reduces battery energy draw compared to competitors.

**Q: What should I do when a low battery alert comes in?**  
A: Replace the battery within **7 days** of the low battery alert. Do not leave the sensor operating on a low battery — transmission reliability degrades before the battery fully dies.

**Q: The battery pull tab is already removed on a new sensor. How do I enroll it?**  
A: Press and release the **tamper switch** to trip the sensor and initiate enrollment, or open/close the reed switch (move the magnet). The pull tab is only needed for initial activation on first install.

---

## Tamper & Supervision

**Q: What signals do MaxOut sensors transmit?**  
A: All supervised MaxOut sensors transmit:
- **Alarm** (open/trip) and **Restore** (close/restore)
- **Supervisory** (regular check-in signal)
- **Tamper** (cover or wall tamper)
- **Low battery**

**Q: What is the dual tamper feature?**  
A: Most MaxOut sensors have two independent tamper switches: one for the **cover** (opens when the sensor lid is removed) and one for the **wall mount** (activates if the sensor is pulled off the wall). Both transmit a tamper alarm to the panel. This provides protection against sensor defeat attempts.

**Q: What does the ACC-TS-HS-KIT do?**  
A: It is a hardwired **panel enclosure tamper switch** used to protect the security panel cabinet itself from removal or cover tamper. It can function as a wall tamper, cover tamper, or both. It features an adjustable plunger screw to accommodate different wall/cover gap sizes. Compatible replacement for the Sentrol 3025 tamper switch.

---

## RF Range & Signal

**Q: What is the transmission range of MaxOut sensors?**  
A: MaxOut sensors transmit at the **maximum FCC-allowable output power** for maximum signal strength. Open-air range can be 500 feet (152 m) or more. Practical in-building range varies significantly based on walls, metal framing, and other interference. Always **walk-test from the installation location** before permanent mounting.

**Q: What can reduce RF signal quality?**  
A: Key factors:
- Metal door/window frames (use the test mode to verify gap and position)
- Large metallic surfaces or HVAC ductwork near the sensor
- Mounting inside metal enclosures
- Concrete or masonry walls between sensor and panel
- Distance from panel

**Q: Why does MaxOut use a patented raised antenna?**  
A: The antenna is physically isolated **1/8" above the circuit board** and separated from the batteries. This eliminates "dead spots" in the 360° transmission pattern that occur when the antenna is surrounded by circuit components, and reduces battery energy draw by improving transmission efficiency.

---

## Specific Products — Quick Reference

**Q: What is the difference between RF-CMDWS and RF-CMDWSX?**  
A: The RF-CMDWSX (**Extended Contact**) adds **external contact wiring terminals** — you can run a wire pair from a separate hardwired contact through the sensor housing and connect it to the transmitter. This allows monitoring a remote contact (e.g., a window contact placed farther away) with a single wireless transmitter. The basic RF-CMDWS has no external contacts.

**Q: When should I use the recessed sensor (RF-RDWS) vs. the surface-mount (RF-CMDWS)?**  
A: Use the **RF-RDWS** when a concealed installation is required — it bores into the door frame and door edge for an invisible install. Use the **RF-CMDWS** for standard surface-mount applications where visibility is acceptable. The recessed sensor uses a CR123A battery (vs. CR2032 for the mini), so battery replacement requires removing the sensor from the bore hole.

**Q: What is the RF-ARGB glass break detector?**  
A: A 319.5 MHz acoustic glass break detector (available for Interlogix/GE/Qolsys panels only — no 345 or 433 MHz version). It detects the acoustic frequency of breaking glass. Position within line-of-sight of the protected glass; do not mount behind curtains or drapes. Replaces the UTC/GE/Sentrol 5600W.

**Q: What is the RF-KEYFOB vs. RF-FOB-PANIC — what is the difference?**  
A: The **RF-KEYFOB-319-NN** is a full system control fob with arm/disarm and panic functions — it operates like a standard keyfob remote (arm away, arm stay, disarm, panic). The **RF-FOB-PANIC** (319 and 345 MHz) is a **panic-only** button, used for medical or emergency panic activation without arm/disarm capability. The **RF-PANIC-ONE-BUTTON-319-NN** is a long-range single-button panic transmitter designed for extended range applications.

---

## Troubleshooting Quick Reference

| Symptom | Likely Cause | Action |
|---|---|---|
| Sensor won't enroll | Wrong frequency / panel not in learn mode / out of range | Verify frequency match; confirm panel is in enrollment screen; move closer |
| Low battery immediately after install | Pull tab not fully removed / dead battery | Remove pull tab completely; replace battery |
| Frequent supervisory loss | Out of range or marginal signal | Walk-test; relocate sensor closer to panel or away from metal |
| False alarms on shock sensor | Sensitivity too high | Reduce sensitivity with potentiometer adjustment |
| False alarms on PIR | Near heat source, window, or HVAC vent | Reposition away from heat sources and windows |
| Tamper alarm won't clear | Cover not fully seated or wall mount loose | Re-seat sensor cover; confirm sensor is flush on wall mount |
| Water sensor not alarming | Contacts not submerged / requires two detections | Check contact placement; sensor waits for two 5-minute checks |
| APCMB shows trouble LED | Dirty sensor or end-of-life | Clean sensor chamber or replace unit |

---

*MaxOut™ Technology — maxouttech.com | sales@maxouttech.com | 763-497-1059*  
*For the most current product documentation, visit maxouttech.com and select the Documentation page.*
