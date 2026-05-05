# Packed Bed Column – HYSYS Simulation Data (T-100 / COL1)
**Fluid Package:** Basis-1 / NRTL – Ideal  
**System:** Ethanol–Water Distillation

---

## 1. Column Configuration (Design > Connections)

| Parameter | Value |
|---|---|
| Column Name | T-100 |
| Sub-Flowsheet Tag | COL1 |
| Condenser Type | Total |
| Number of Stages (n) | 19 |
| P condenser | 101.3 kPa |
| P reboiler | 103.0 kPa |
| Feed Stream | 1 → Stage 17_Main Tower |
| Condenser Energy Stream | Condenser |
| Reboiler Energy Stream | Reboiler |
| Overhead Liquid Outlet | Distillate |
| Bottoms Liquid Outlet | Bottom |

---

## 2. Column Specifications (Design > Monitor)

| Specification | Specified Value | Current Value | Wt. Error | Active |
|---|---|---|---|---|
| Reflux Ratio | 2.000 | 2.000 | 0.0000 | Yes |
| Distillate Rate | 41.20 kgmole/h | 41.22 | 0.0005 | Yes |
| Reflux Rate | — | 82.44 | — | No |
| Btms Prod Rate | — | 58.78 | — | No |
| Comp Fraction | 0.9000 | 0.8341 | -1.0612 | Yes |

---

## 3. Material Streams

### Feed (Stream 1)

| Property | Value |
|---|---|
| Vapour Fraction | 0.0000 |
| Temperature | 78.00 °C |
| Pressure | 101.3 kPa |
| Molar Flow | 100.0 kgmole/h |
| Mass Flow | 2924 kg/h |
| Std Ideal Liq Vol Flow | 3.398 m³/h |
| Molar Enthalpy | -2.764×10⁵ kJ/kgmole |
| Molar Entropy | 40.73 kJ/kgmole·°C |
| Heat Flow | -2.764×10⁷ kJ/h |

**Composition (Mole Fractions):**

| Component | Feed |
|---|---|
| H₂O | 0.6000 |
| Ethanol | 0.4000 |

---

### Distillate

| Property | Value |
|---|---|
| Vapour Fraction | 0.0000 |
| Temperature | 78.17 °C |
| Pressure | 101.3 kPa |
| Molar Flow | 41.22 kgmole/h |
| Mass Flow | 1707 kg/h |
| Std Ideal Liq Vol Flow | 2.113 m³/h |
| Molar Enthalpy | -2.716×10⁵ kJ/kgmole |
| Molar Entropy | 56.51 kJ/kgmole·°C |
| Heat Flow | -1.120×10⁷ kJ/h |

**Composition (Mole Fractions – Liquid Phase):**

| Component | Distillate |
|---|---|
| H₂O | 0.1659 |
| Ethanol | 0.8341 |

---

### Bottom

| Property | Value |
|---|---|
| Vapour Fraction | 0.0000 |
| Temperature | 87.02 °C |
| Pressure | 103.0 kPa |
| Molar Flow | 58.78 kgmole/h |
| Mass Flow | 1217 kg/h |
| Std Ideal Liq Vol Flow | 1.285 m³/h |
| Molar Enthalpy | -2.791×10⁵ kJ/kgmole |
| Molar Entropy | 27.87 kJ/kgmole·°C |
| Heat Flow | -1.640×10⁷ kJ/h |

**Composition (Mole Fractions – Aqueous Phase):**

| Component | Bottom |
|---|---|
| H₂O | 0.9044 |
| Ethanol | 0.0956 |

---

## 4. Energy Streams

| Stream | Heat Flow |
|---|---|
| Condenser | 4.827×10⁶ kJ/h |
| Reboiler | 4.881×10⁶ kJ/h |

---

## 5. Stage Profiles (Parameters > Profiles)

| Stage | Stage Name | Pressure [kPa] | Temp [°C] | Net Liquid [kgmole/h] | Net Vapour [kgmole/h] |
|---|---|---|---|---|---|
| 0 | Condenser | 101.3 | 78.17 | 82.44 | 1.716×10⁻⁷ |
| 1 | 1_Main Tower | 101.3 | 78.21 | 82.34 | 123.7 |
| 2 | 2_Main Tower | 101.4 | 78.26 | 82.26 | 123.6 |
| 3 | 3_Main Tower | 101.5 | 78.32 | 82.19 | 123.5 |
| 4 | 4_Main Tower | 101.6 | 78.38 | 82.12 | 123.4 |
| 5 | 5_Main Tower | 101.7 | 78.44 | 82.05 | 123.3 |
| 6 | 6_Main Tower | 101.8 | 78.51 | 81.97 | 123.3 |
| 7 | 7_Main Tower | 101.9 | 78.57 | 81.91 | 123.2 |
| 8 | 8_Main Tower | 102.0 | 78.64 | 81.83 | 123.1 |
| 9 | 9_Main Tower | 102.1 | 78.71 | 81.75 | 123.1 |
| 10 | 10_Main Tower | 102.2 | 78.80 | 81.67 | 123.0 |
| 11 | 11_Main Tower | 102.3 | 78.89 | 81.57 | 122.9 |
| 12 | 12_Main Tower | 102.3 | 79.00 | 81.45 | 122.8 |
| 13 | 13_Main Tower | 102.4 | 79.13 | 81.31 | 122.7 |
| 14 | 14_Main Tower | 102.5 | 79.29 | 81.13 | 122.5 |
| 15 | 15_Main Tower | 102.6 | 79.52 | 80.89 | 122.4 |
| 16 | 16_Main Tower | 102.7 | 79.87 | 80.54 | 122.1 |
| 17 | 17_Main Tower | 102.8 | 80.47 | 181.3 | 121.8 |
| 18 | 18_Main Tower | 102.9 | 80.69 | 180.0 | 122.6 |
| 19 | 19_Main Tower | 103.0 | 81.62 | 179.1 | 122.2 |
| 20 | Reboiler | 103.0 | 87.02 | 58.78 | 120.3 |

---

## 6. Column Internals – Packed Bed (Internals Tab)

| Parameter | Value |
|---|---|
| Active Internal | Internals-1 |
| Section | CS-1 |
| Start Stage | 1_Main Tower |
| End Stage | 18_Main Tower |
| Mode | Interactive Sizing |
| Internal Type | Packed |
| Tray/Packing Type | PALL |
| Packing Vendor | GENERIC |
| Packing Material | METAL |
| Packing Dimension | 2-IN OR 50-MM |
| Section Packed Height | 11.58 m |
| Diameter | 1.000 m |
| Include Static Vapor Head in Pressure Drop Calcs | Yes |
| Calculate Pressure Drop Across Sump | No |
| Liquid Residence Time | 60.00 seconds |

---

## 7. Tower Sizing (Sieve Reference Section)

| Parameter | Value |
|---|---|
| Tower | Main Tower |
| Uniform Section | Yes |
| Internal Type | Sieve |
| Diameter | 1.000 m |
| Tray/Packed Space | 0.5500 m |
| Tray/Packed Volume | 0.4320 m³ |
| Hold Up | 3.927×10⁻² m³ |
| Weeping Factor | 1.000 |
| Tray Sizing Analysis for Costing | Internals-1@Main |

---

## 8. PF Specs (Worksheet > PF Specs)

| Parameter | Stream 1 | Distillate | Bottom |
|---|---|---|---|
| Pressure Spec Active | No | No | No |
| Pressure [kPa] | 101.3 | 101.3 | 103.0 |
| Flow Spec Active | No | No | No |
| Flow Spec Basis | Molar Flow | Molar Flow | Molar Flow |
| Molar Flow [kgmole/h] | 100.0 | 41.22 | 58.78 |
| Mass Flow [kg/h] | 2924 | 1707 | 1217 |
| Std Ideal Liq Vol Flow [m³/h] | 3.398 | 2.113 | 1.285 |

---

## 9. Simulation Status

- **Converged:** Yes
- **Column has gaps:** Warning noted (19 stages defined, gap warning shown)
- **Internals Input:** Incomplete (warning shown)
