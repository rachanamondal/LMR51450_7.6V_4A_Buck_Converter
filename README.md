# LMR51450 7.6V 4A Buck Converter (KiCad Design)

This repository contains the design files for a **7.6V 4A DC-DC Buck Converter** using the **Texas Instruments LMR51450**.  
The design follows input/output filtering, proper trace widths, and general PCB routing guidelines.


## 📸 Snapshots
Schematic
PCB Routing
3D PCB View



# 📋 Bill of Materials (BOM)

Here are the main components required for the 7.6V 4A Buck Converter:

# U1 – LMR51430

Type: DC-DC Buck Converter IC

Package: SOIC-8

Notes: Main regulator IC (3A rated, similar family to LMR51450).


# L1 – Inductor 6.8 µH

Value: 6.8 µH

Type: Power Inductor (SMD)

Notes: Must support at least 3–4A current.


# C1 – Capacitor 0.1 µF

Value: 0.1 µF

Package: 0603/0805 SMD

Notes: Bootstrap capacitor.


# C2 – Capacitor 22 µF

Value: 22 µF

Package: SMD (1210/1206)

Notes: Input capacitor.


# C3 – Capacitor 22 µF

Value: 22 µF

Package: SMD (1210/1206)

Notes: Output capacitor.


# R1 – Resistor 10 kΩ

Value: 10kΩ

Package: 0603/0805 SMD

Notes: Lower feedback resistor.


# R2 – Resistor 85 kΩ

Value: 85kΩ

Package: 0603/0805 SMD

Notes: Upper feedback resistor (sets Vout = 7.6V with R1).


# D1 – Schottky Diode B240

Type: Schottky Diode

Part: B240

Package: SMA

Notes: Flyback/protection diode.


# J1 – Input Connector

Type: Screw Terminal, 2-pin

Notes: VIN + GND.


# J2 – Output Connector

Type: Screw Terminal, 2-pin

Notes: VOUT + GND.
